# DynaTech
The DynaTech AI Chatbot is an educational conversational assistant designed to teach users
fundamental Artificial Intelligence concepts and assess their understanding through topic-based
multiple-choice quizzes. It is built on the Botpress Cloud platform and deployed via a publicly
accessible shareable webchat link.

The chatbot serves a single, focused purpose: a user prompts an AI topic they wish to learn
about; the bot presents a concise lesson on that topic, and then a user can ask for a multiple
choice quiz to test their knowledge on a specific topic. Upon completion of the quiz, the user
receives a closing acknowledgement message.
Some of the AI topics covered are Machine Learning, Deep Learning, Natural Language
Processing (NLP), Computer Vision, Neural Networks, AI Ethics, Prompt Engineering, and
Generative AI.

2. Platform Selection & Implementation Approach
2.1 Selected Platform: Botpress Cloud
   
The chatbot is implemented on Botpress Cloud, a visual conversational AI development
platform. The following table justifies this selection against the specific requirements of an
educational quiz chatbot.
Selection Criterion
Justification
Visual Flow Builder
Botpress Studio's drag-and-drop canvas allowed the developer
to design the topic selection menu, lesson delivery, and quiz
question sequences without writing complex backend code.
Quick-Reply Buttons
Botpress natively supports interactive quick-reply to buttons,
which are ideal for presenting multiple-choice quiz options and
topic selection menus in a clean, tap-friendly format.
Conversation State
Management
No Infrastructure
Required
Botpress tracks conversation variables across turns, enabling
the bot to know which topic a user selected and which quiz
question they are currently on.
Botpress Cloud is a fully managed SaaS platform. No server
setup, hosting, or DevOps work was required- the bot is
deployed instantly via a shareable webchat URL.
Free Tier Availability
Shareable Webchat Link

The educational scope of this chatbot falls comfortably within
Botpress's free tier, making it a cost-effective choice for an
internal or academic project.
Botpress generates a ready-to-use, embeddable webchat link
(v3.6) enabling immediate access by any user with a browser
no app download or login required.

2.2 Implementation Approach
The chatbot was built using a straightforward three-step approach within Botpress Studio:
Step 1- Topic Menu Design: A welcome flow was created presenting the user with a menu of
eight AI topics via quick-reply buttons. Each button routes to the corresponding topic flow.
Step 2- Lesson & Quiz Flows: For each of the topics, a dedicated flow was built containing a
brief educational description of the topic followed by a series of multiple-choice quiz questions.
Each question is presented with selectable answer options.
Step 3- Quiz Completion: Upon answering the final question in a topic's quiz, the bot delivers a
closing message- 'Well done, you have completed the quiz'- ending the conversation flow for
that topic.

4. Implemented Q&A Pairs
The table below documents all Q&A pairs implemented across the AI topic flows. Each topic
includes a teaching segment followed by multiple-choice quiz questions. The answer options
presented to users are listed under each question.
Examples:
3.1 Machine Learning
Quiz Question
Answer Options
1
What is Machine Learning?
a) A type of computer hardware
b) A type of AI where systems learn from data
c) A programming language
2
3
Which of these is an example of
Machine Learning in everyday life?
Which of these is a type of Machine
a) Using a calculator
b) Email spam filters
c) Writing a letter by hand
a) Unsupervised Learning

Learning where the model learns from
labeled data?
b)SupervisedLearning
c)ReinforcementLearning
3.2DeepLearning

Quiz Question Answer Options
1 What isDeepLearning? a)AtypeofAIthatuseslayeredneural
networkstolearnfromdata
b)Awaytostoredatainadeepocean
c)Aprogramminglanguage

2 Whichoftheseisakeybuildingblock
ofDeepLearningmodels?
a)NeuralNetworks
b)Spreadsheets
c)WebBrowsers

3 Whichoftheseisareal-world
applicationforDeepLearning?
a)Imagerecognitioninsmartphones
b)Writingwithapencil
c)Sendingapostcard

3.3NaturalLanguageProcessing(NLP)
QuizQuestion AnswerOptions
1 WhatdoesNLPstandforinArtificial
Intelligence?
a)NaturalLanguageProcessing
b)NumericLogicProgramming
c)NetworkLearningProtocol

2 Whichoftheseisacommonuseof
NLP?
a)Translatinglanguagesautomatically
b)Buildingbridges
c)Cookingfood

3 WhichoftheseisachallengeforNLP
systems?
a)Understandingsarcasmandjokes
b)Boilingwater
c)Buildingbridges

3.4ComputerVision
QuizQuestion AnswerOptions
1 What isComputerVisioninArtificial
Intelligence?
a)Teachingcomputerstounderstandand
interpret imagesorvideos
b)Givingcomputerstheabilitytohearsounds
c)Makingcomputerswritestories

2 Whichisthereal-worlduseof
ComputerVision?
a)Facial recognitioninsmartphones
b)Makingphonecalls
c)Writingemails

6. Conversation Flows
The DynaTech chatbot follows a simple, linear conversation structure. There are three core
flows that every user interaction passes through, regardless of which topic is chosen.

4.1 Welcome & Topic Selection Flow
This is the entry point for all users. It runs once at the start of every conversation.
Step
Description
1- Greeting
The bot opens with a welcome message introducing itself as the
DynaTech AI learning assistant.
2- Topic Menu
The bot presents the user with a menu of AI topics: Machine
Learning, Deep Learning, NLP, Neural Networks, AI Ethics etc.
However, the user must prompt the Chatbot for topics.
3- User Selection
The user taps their chosen topic. This selection routes the
conversation to the corresponding topic flow.
4.2 Topic Lesson & Quiz Flow (Repeated for all Topics)
Once a topic is selected, the user enters that topic's dedicated flow. This flow structure is
identical across all topics- only the content changes.
Step
Description
1- Lesson Delivery
The bot sends a short educational message explaining the selected
AI topic in plain language.
2- Question 1
The bot presents the first multiple-choice question with four answer
options as quick-reply buttons (A, B, C, D).
3- User Answer
The user selects an answer option. The bot acknowledges the
response and proceeds to the next question.
4- Question 2
The second multiple-choice question is presented in the same
format.
5- Question 3
6- Completion
The third and other multiple-choice questions are presented.
After the user answers the final question, the bot displays the closing
message: 'Well done, you have completed the quiz.'
4.3 Flow Diagram Overview
The diagram below illustrates the overall conversation flow structure at a high level:
User Opens Chatbot
↓
Welcome Message & the space to prompt the Chatbot
↓
User Selects a Topic
↓
Topic Lesson Delivered
↓
Quiz: Question 1 → Question 2 → Question 3, etc.
↓
"Well done, you have completed the quiz."
8. Screenshot Examples
5.1 Welcome Message Menu
Shows the chatbot's opening greeting as well as the space to prompt the AI Chatbot.

5.2 Topic Lesson Delivery
Shows the bot delivering the educational lesson after the user has selected a topic, e.g.
Machine Learning. The user must prompt the Chatbot to give the topics to learn.
5.3 Multiple-Choice Quiz Question
Shows a quiz question being presented to the user with multiple-choice answer options
displayed.

5.4 Quiz Completion Message
Shows the final message displayed after the user answers the last quiz question: 'Well done,
you have completed the quiz.' For Example, here it says “Great job completing the Beginne
