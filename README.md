# Named_entity_recognition
Implemented several different models for named entity recognition (NER). NER is a
subtask of information extraction that seeks to locate and classify named entities in text into pre-defined
categories such as the names of persons, organizations, locations, expressions of times, quantities, monetary
values, percentages, etc. In the assignment, for a given a word in a context, we want to predict whether it
represents one of four categories:

Person (PER): e.g. Martha Stewart", Obama", Tim Wagner", etc. Pronouns like he" or she" are
not considered named entities.

Organization (ORG): e.g. American Airlines", Goldman Sachs", Department of Defense".


Location (LOC): e.g. Germany", Panama Strait", Brussels", but not unnamed locations like \the
bar" or the farm".

Miscellaneous (MISC): e.g. Japanese", USD", 1,000", Englishmen".

We formulate this as a 5-class classification problem, using the four above classes and a null-class (O) for
words that do not represent a named entity (most words fall into this category). For an entity that spans
multiple words (Department of Defense"), each word is separately tagged, and every contiguous sequence
of non-null tags is considered to be an entity.


Requirements : - 

tensorflow>=0.12

matplotlib


Stanford CS224n assignment3. 

There are three parts to this assignment 

1. A window into NER **Implemented** 


2. Recurrent neural nets for NER **Implemented**


3. Grooving with GRUs **Implemented**


![Questions](https://github.com/imraviagrawal/Named_entity_recognition/blob/master/assignment3.pdf)
