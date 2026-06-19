# nlp-pos-tagging
Part-of-Speech (POS) Tagging is a Natural Language Processing technique that assigns grammatical categories such as nouns, verbs, adjectives, and adverbs to words in a sentence. It helps computers understand sentence structure and improves language analysis.

# NLP Part-of-Speech (POS) Tagging using NLTK

## Overview

Part-of-Speech (POS) Tagging is a fundamental Natural Language Processing (NLP) technique that assigns grammatical categories such as nouns, verbs, adjectives, adverbs, pronouns, and prepositions to each word in a sentence. It helps computers understand the grammatical structure and meaning of text.

## Objective

To implement Part-of-Speech Tagging using Python and the NLTK library and identify the grammatical role of each word in a given sentence.

## Tools and Libraries

* Python
* NLTK
* Pandas
* Google Colab

## Dataset

A sample paragraph related to Natural Language Processing is used to demonstrate POS tagging.

## Implementation Steps

1. Install and import the required libraries.
2. Download the necessary NLTK resources.
3. Input a sample paragraph.
4. Tokenize the text into individual words.
5. Apply POS tagging using NLTK.
6. Display the tagged words in tabular format.
7. Analyze the grammatical categories assigned to each word.

## Sample Output

| Word       | POS Tag |
| ---------- | ------- |
| Natural    | NNP     |
| Language   | NNP     |
| Processing | NNP     |
| enables    | VBZ     |
| computers  | NNS     |
| understand | VB      |
| human      | JJ      |
| language   | NN      |

## Common POS Tags

| Tag | Meaning                    |
| --- | -------------------------- |
| NN  | Noun                       |
| NNS | Plural Noun                |
| NNP | Proper Noun                |
| VB  | Verb                       |
| VBD | Past Tense Verb            |
| VBG | Verb (Present Participle)  |
| VBZ | Verb (3rd Person Singular) |
| JJ  | Adjective                  |
| RB  | Adverb                     |
| PRP | Pronoun                    |
| DT  | Determiner                 |
| IN  | Preposition                |
| CC  | Coordinating Conjunction   |

## Applications

* Text Classification
* Named Entity Recognition (NER)
* Machine Translation
* Information Extraction
* Question Answering Systems
* Chatbots

## Conclusion

Part-of-Speech Tagging was successfully implemented using the NLTK library. The experiment demonstrated how grammatical labels are assigned to words, enabling better text understanding and serving as a foundation for advanced NLP applications such as Named Entity Recognition and syntactic parsing.
