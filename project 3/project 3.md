# Project 3: Content Specification Plan for NLP Tutorial Creation
## Goals and Objectives
This project prepares a content specification plan on behalf of Temple University’s Loretta C. Duckworth Scholars Studio, which will guide the creation of two tutorials for the use of Natural Language Processing (NLP) with these software: spaCy, Colab, and Github. They will be aimed mainly at students, faculty and staff at Temple University and in general, novices to the practice of using natural language processing.
## Proposed documentation
The proposed tutorials are aimed at guiding new users through learning how to use two natural language processing functions. One such function is the use of spaCy token objects, the uppercase, lowercase, and titled attributes. Provided with a bulk of text and/or data, the user will gain the knowledge of how to search for and identify words that are written in all capitalized letters, all lowercased letters, or written capitalized, such that it falls under proper nouns. The other function is Named Entity Recognition (NER), the extraction of named entities from a text. Named entities refer to real world objects and can be identified and sorted by the type of object they are. Through these tutorials, users will understand the logic of how to code both processes and learn the steps well enough to be able to reproduce these processes independently. Ultimately, the user should be able to find and sort what kind of specific items are mentioned in a piece of text.
## Product Description
SpaCy is an extensive, open-source modern library for Natural Language Processing (NLP), which is in short, the computer’s ability to process and parse the written and spoken human language. SpaCy is written in Python, but can load spaCy models in several different programming languages. It has several functions that can be used to build applications to process large texts; examples of a few NLP functions are tokenization, part-of-speech (POS) tagging, and Named Entity Recognition (NER). Ultimately spaCy can be used to build information extraction or natural language understanding systems, or to pre-process text for deep learning. (“SpaCy 101:…”)

Colab, a product of Google Research, is a virtual notebook environment that allows a user to execute Python code from their browser. It does not require any set-up, running entirely on the digital cloud, and files created through Colab can be copied, downloaded, and shared. (“Colabatory: Frequently…”) It is naturally integrated with Google Drive, the digital storage space. It can be used for personal use and to collaborate with others.

Github is a platform for collaborative work on code projects, stored in repositories. It allows for many versions of a file to be saved and tracked through the edits, through its branching function, then merged into the official, main version. (“What is Github?”) It can be used for personal purposes, but is often used by organizations and groups. 
## Audience Profile
Target audience is comprised of Temple University students, staff, and faculty, especially the students. This means age, gender, and life experiences will vary widely, but students will most likely be in the 20s range and have a young adult’s familiarity with navigating basic web browsers, word-processers, and digital storage sites. 

Regardless, the majority are anticipated to have little to no experience with natural language processing and programming, and that these users are expected to need to use NLP over the course of their school years for coursework. Tutorials should approach with the mind that all terms, processes, and direction even that which is related to coding in general and not only spaCy, will be unfamiliar to the audience. In case some parts feel counterintuitive to the novice user, the tutorials need to provide adequate explanation for each part. 

The tutorials are expected to be distributed by Temple University’s Loretta C. Duckworth Scholars Studio. According to their “About” page, the Studio “offers spaces and resources for student and faculty consultations, workshops, and collaborative research in digital humanities, digital arts, cultural analytics, and critical making.” They have physical computer labs in which people can gather and be taught and advised directly. Alternatively, the tutorials will be in a digital format that can be accessed from any virtual environment. 
Our research has indicated that in general, first-time users experience frustration from being overwhelmed by information, or confused by the lack of familiarity with spaCy. With proper explanation they may understand what individually, one part of the code may do, but struggle to put them together to successfully create the intended application. Related to that, they struggle to construct applications because of the need for exact and proper syntax. 
## Usability Goals
Our data was gathered through observing and interviewing some first-time Temple student users of spaCy in the classroom. We used think-aloud protocol testing and were able to track the users’ thought processes while using the software. This raw data was analyzed for trends in regards to frustrations, common errors made, as well as what the users perceived as facilitating their learning. These trends are reinterpreted into solvable problems which our recommendations at the end of this documentation will address. 
## Publication Objectives
There are a number of tasks a user may want to complete when given a length of text and/or data. The user may want to identify what sort of topics are covered in the text or what is discussed with emphasis. Or maybe, the user would want to identify names that are brought up in the text or find acronyms – or that is to say specifically, capitalized words and words written in all capital letters. They may also want to be able to identify what type of objects each mentioned object in the text it. In this way, users would get a general idea of what the text is discussing. These are tasks that the following tutorials can help the user accomplish. 

One tutorial demonstrates and explains spaCy Token objects, some attributes, and what we can do with them. Specifically, it explains and demonstrates the [.is_upper], [.is_lower], and [.is_title] attributes. The first attribute will recognize any tokens written in all uppercase letters. The second will recognize any tokens written in all lowercase letters. The last will recognize any token with its first letter being capitalized, and *only* its first letter capitalized. 

The tutorial will first explain its purpose, and about tokens and attributes, then give a table of examples of attributes and their respective functions. Then it will give clear, step by step process of how to use an attribute. Each step shall be written large and clear, the numberings given as a heading and the description of the step succinctly given beneath. Side notes will be written as commentary in the code cells or to the literal side of the tutorial. The last step will be split into three variations, respective of each attribute being featured in this tutorial. Each variation will demonstrate the final output of running its respective attribute, using the same sentence as the example. This same sentence will create a point of comparison for each attribute, so the user gains further understanding of how it works and what it results in. 

The second tutorial demonstrates how to extract named entities from a large corpus of texts. This is called named entity recognition (NER). Using spaCy, users will be provided a ‘dictionary’ or ‘glossary’ of sorts (which can be customized through creating pipelines) that recognize certain tokens/entities that refer to real life objects. Through recognizing them, the entities can then be categorized by what type of real-life object it is referring to. This is what the tutorial will teach the users to do. 

This tutorial will first explain its purpose and the definition of NER. It will then provide a list of basic named-entity categories, so users will be able to recognize the tags in the example used later. Then it will give clear, step by step process of how to write an NER function. Like with the previous tutorial, each step shall be written large and clear, the numberings given as a heading and the description of the step succinctly given beneath. Side notes will be written as commentary in the code cells or to the literal side of the tutorial. The final step will demonstrate the function itself and show the final output, as well as the entities being recognized and named for their type in a neat, orderly way that is easy to comprehend by the audience. 
## Prototypes
### NER tutorial:
![NER1](https://github.com/1daytotheleft/ENG3810/blob/main/images/ner%201.png "sfs")

Start with large, clear title and succinct explanation of function that will be taught in this tutorial. 

![NER2](https://github.com/1daytotheleft/ENG3810/blob/main/images/ner2.png) 

Write number of steps in heading format, describe step below. Any additional notes are annotated with an asterisk. Within the code cell, add short notes to give the user a better idea of what each line accomplishes.

![NER3](https://github.com/1daytotheleft/ENG3810/blob/main/images/ner3.png)

This isn’t a step but give it a heading format so users understand it’s important. The notation format is thus also a little different, so users will know this section is to enrich understanding, not necessarily part of the process in creating the function.
 
![NER](https://github.com/1daytotheleft/ENG3810/blob/main/images/ner4.png)

Go back to using the heading and notation format used to step 1.

![NER](https://github.com/1daytotheleft/ENG3810/blob/main/images/ner5.png)

Use same format as previous. 
 
 ![NER](https://github.com/1daytotheleft/ENG3810/blob/main/images/ner6.png)

Use same format as previous. This is the final step to be demonstrated. The final output should be shown as well. 
 
 ![NER](https://github.com/1daytotheleft/ENG3810/blob/main/images/ner7.png)

A content table at the side will make it easy for the user to refer back to a particular step it they need it.
### Token/Attribute tutorial:
![Token](https://github.com/1daytotheleft/ENG3810/blob/main/images/token1.png)

Start with a clear, noticeable title. Briefly explain that this tutorial uses spaCy, as these attributes are specific to spaCy, and include which version is being used. 
 
 ![Token](https://github.com/1daytotheleft/ENG3810/blob/main/images/token2.png)

Provide a list of token attributes for the user to peruse, so the user has an idea of what it looks like on its own without yet being put into code cells. 
 
 ![Token](https://github.com/1daytotheleft/ENG3810/blob/main/images/token3.png)

This section explains each attribute’s description. It provides examples of what the attribute would judge as true and what it would judge as false, AKA what counts and what doesn’t. most important part of definition is bolded and capitalized. Each description is written in parallel syntax so user has easiest way to see point of contrast between each. 
 
 ![Token](https://github.com/1daytotheleft/ENG3810/blob/main/images/token4.png)

Steps are written in heading format. Notes are written below. Notes in code cells are short and simply show user what each line does specifically. 
 
 ![Token](https://github.com/1daytotheleft/ENG3810/blob/main/images/token5.png)

Same as above.
 
 ![Token](https://github.com/1daytotheleft/ENG3810/blob/main/images/token6.png)

Basic idea of step 3 is given, then presented in 3 variations, each using one of the three featured attributes. The final output is shown for each. Notation to the side points out to user which tokens have been marked true or false with each attribute. 
## Conclusion
Here are our recommendations based on our research and analyses of competitors: 
-	Provide an index and/or introductory section which explains basic programming terms and spaCy-specific terms. 
    - The index should be instantly reachable with hyperlinks or anchor links
-	Instructions should be explicit and clear
-	Provide graphics and visuals to facilitate understanding
-	Provide multiple examples of what’s being taught and what should be returned upon running it, so the user can see what variable and/or entity is being altered and how it affects the output
-	Let the examples be shown with each step, so the user can see what each step is asking for
-	Provide practice problems at the end with most of the code given but obvious blanks to fill out; users should be able to identify what entity needs to be altered or added based on the instructions and examples provided earlier
-	Exact punctuation and syntax of each code should be explicitly explained
-	Separate tutorials for each function and/or concept
    - Make it so they can be learned in a specific order
    - OR add links to related tutorials to functions and/or concepts will need to be understood as a prerequisite to learning this concept 

 
## APA Reference List
- *About.* Temple University Library. https://sites.temple.edu/tudsc/about/
- *Colaboratory: Frequently asked questions.* Google Research. https://research.google.com/colaboratory/faq.html
- *SpaCy 101: Everything you need to know.* Spacy. https://spacy.io/usage/spacy-101
- *spaCy Tutorial: Complete Write-up.* Machine Learning Plus. https://www.machinelearningplus.com/spacy-tutorial-nlp/#introduction 
- (2021, May 28). *What Is GitHub? A Beginner’s Introduction to GitHub.* Kinsta. https://kinsta.com/knowledgebase/what-is-github/