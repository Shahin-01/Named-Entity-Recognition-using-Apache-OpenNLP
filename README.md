This project has been implemented to apply basic Natural Language Processing
(NLP) techniques to a real web text collection using Java programming language.
Our primary goal is to extract some useful information from the given text. In our
experiment, we have been given a text file with some documents that each is in a
separate line of our file. These documents outline people (the soccer players),
organizations (the teams that those players play for) and locations (the stadiums
where teams play their home games).
To do this, we have used Apache OpenNLP machine learning tool to extract
named entities. The following components of this toolkit have been included to
our program:
• opennlp-tools-1.5.3 – main executable library file
• opennlp-maxent-3.0.1- maximum entropy modeling framework for
information integration from ample number of sources for classification purposes
• en-ner-person.bin- binary file that is used to find people’s names
• en-ner-location.bin- binary file that is used to find location names
• en-ner-organization.bin- binary file that is used to find organization names
• en-token.bin – a tokenizer that is trained on the data
