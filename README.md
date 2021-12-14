# final_project_NLP_2731

AI For Machine Comprehension
An intelligent machine comprehension system for passages in English. It takes a passage and user queries as input and returns the relevant answers to the user. The answers must be in the passage and the system should not need any external resources to find it.
Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.
Prerequisites
Apache XAMPP server
Jave Runtime environment 
Python
Build Project
A step by step series tell you have to get a development env running
1.	Unzip the zip file into the htdocs folder, eg. /htdocs/glint/
2.	Navigate to /htdocs/glint/php/MC/
Dowload Required Library files
•	Create a folder to host all the stanford models, e.g. mkdir /htdocs/glint/php/MC/resources/stanford-models.
•	Download Stanford Parser at https://nlp.stanford.edu/software/lex-parser.shtml , unzip, and:
o	Move stanford-parser.jar to stanford models folder, e.g. /your-path-to-stanford-models/stanford-models/stanford-parser.jar
o	Move stanford-parser-x-x-x-models.jar to stanford models folder.
o	Unzip stanford-parser-x-x-x-models.jar, move /edu/stanford/nlp/models/lexparser/englishPCFG.ser.gz to stanford-models/
•	Download Stanford NER at https://nlp.stanford.edu/software/CRF-NER.shtml , unzip, and:
o	Move stanford-ner.jar to stanford models folder.
o	Move stanford-ner-x-x-x.jar to stanford models folder (e.g. 3.7.0).
o	Move /classifiers/english.all.3class.distsim.crf.ser.gz to stanford -models folder.
o	Move /classifiers/english.muc.7class.distsim.crf.ser.gz to stanford- models folder.
The stanford models folder should look like this:
- stanford-models/
    | - stanford-parser.jar
    | - stanford-parser-x-x-x-models.jar
    | - englishPCFG.ser.gz
    | - stanford-ner.jar
    | - stanford-ner-x-x-x.jar
    | - english.all.3class.distsim.crf.ser.gz

3.	Navigate to localhost/glint/php/SentenceSimplification1/
•	Create a folder, e.g. mkdir /htdocs/glint/php/ SentenceSimplification1/lib/
o	Copy stanford-parser-x-x-x-models.jar 
o	stanford-parser.jar
o	Dowload arkref.jar from http://www.ark.cs.cmu.edu/ARKref/
4.	If not a Windows OS or if Xampp’s htdocs is not following C:/Software/xampp/htdocs/ format then navigate to htdocs/glint/php/SentenceSimplification1/ src/main/java/SentenceSimplification/ and to htdocs/glint/php/MC/ and replace the paths to ___/htdocs/. and Open htdocs/glint/php/SentenceSimplification1/ and build a jar file.

	
Running 
1.	Start Apache XAMPP server
2.	Hit http://localhost/glint/index.html on a web browser
3.	Click on any of the passages 
4.	Type your questions in the text bar below the passage
5.	Press Enter Key
6.	Answer will appear once the loading bar stops
OR
7.	Input your file or Scroll to Try Now! Section from Menu or scroll bar and type in your passage
8.	Click on START button 
9.	Question text box appears
10.	Follow from step 4


