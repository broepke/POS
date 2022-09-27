# A Quick Guide to Part of Speech Tagging

Part of Speech (POS) is a way to describe the grammatical function of a word [^WIKI]. In Natural Language Processing (NLP), POS is an essential building block of language models and interpreting text. While POS tags are used in higher-level functions of NLP, it's important to understand them on their own, and it's possible to leverage them for useful purposes in your text analysis.

> There is a hierarchy of tasks in NLP (see [Natural language processing](https://en.wikipedia.org/wiki/Natural_language_processing#Major_tasks_in_NLP) for a list). At the bottom are sentence and word segmentation. POS tagging builds on top of that, and phrase chunking builds on top of POS tags. These tags, in turn, can be used as features for higher-level tasks such as building parse trees, which can, in turn, be used for Named Entity Resolution, Coreference Resolution, Sentiment Analysis, and Question Answering [^QUORA].

There are **eight** (sometimes nine [^WIKI]) different parts of speech in English that are commonly defined [^POS].

1. **Noun**: A noun is the name of a person, place, thing, or idea.
2. **Pronoun**: A pronoun is a word used in place of a noun.
3. **Verb**: A verb expresses action or being.
4. **Adjective**: An adjective modifies or describes a noun or pronoun.
5. **Adverb**: An adverb modifies or describes a verb, an adjective, or another adverb.
6. **Preposition**: A preposition is a word placed before a noun or pronoun to form a phrase modifying another word in the sentence.
7. **Conjunction**: A conjunction joins words, phrases, or clauses.
8. **Interjection**: An interjection is a word used to express emotion. 
9. **Determiner or Article**: A grammatical marker of definiteness (the) or indefiniteness (a, an). These are not always considered POS but are often included in POS tagging libraries.

Read more here: https://www.dataknowsall.com/pos.html
