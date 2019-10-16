https://feliciatrinh.github.io/projects/  
These are some of the projects I have enjoyed working on during my undergraduate career at UC Berkeley.

# Personal/Work Projects

## Summer 2019 - Present
### Picovoice - python, pip
I am helping [Picovoice](https://picovoice.ai/) build pip packages for their open source, private AI technology. The pip package for their on-device wake-word detection engine, [Porcupine](https://github.com/picovoice/porcupine), is live at [PyPI](https://pypi.org/project/pvporcupine/). Feel free to demo it!

I am currently working on deploying two more pip packages for their speech-to-text ([Cheetah](https://github.com/picovoice/cheetah)) and speech-to-intent ([Rhino](https://github.com/picovoice/rhino)) engines.

## Fall 2019
### Alexa Skills - JavaScript, AWS Lambda
I am currently developing a trivia based Alexa skill called MAMAMOO Trivia. Upon opening MAMAMAOO Trivia, Alexa asks the player multiple choice questions and the player responds with the number of their answer choice.

I am also developing a trivia based Alexa skill called Protobowl. Quiz Bowl competitors will be able to use this Alexa skill to test their knowledge in the 7 official Quiz Bowl categories: philosophy, social sciences, religion, history, literature, geography, mythology, fine arts, and science. The game will launch and prompt the player for a category. After choosing a category, the player will be able to answer questions taken from past Quiz Bowl tournaments.

I plan to improve this Alexa skill in the future by integrating Echo Buttons. Multiple players will then be able to play in teams and buzz-in, which would better match a real Quiz Bowl tournament.

## Spring 2019
### Menu Section API - Python, Django, SQLite
I built a server-side API using Django that would enable restaurant owners to update their menu dynamically. This RESTful application supports both browser and curl usage and presents data in a clearly formatted JSON. 
I did this project to learn more about Django and APIs.
See code [here](https://github.com/feliciatrinh/api-menu-section).

# Academic Projects
Because of concerns over plagarism, I am unable to post the code for these projects publicly.

## Fall 2019
### Database Systems - Java, B+ trees
Over the course of the semester, I have been implementing a database system that will be able to support executing simple transactions in series. I've finished implementing a B+ tree index and efficient join algorithms (e.g. sort-merge join) so far. The next steps are query optimization, multigranilarity locking for concurrent execution of transactions, and database recovery.

### Computer Security - Golang
I am designing and implementing a file sharing system (like Dropbox) that protects user privacy. In particular, user files are always encrypted and authenticated on the server. In addition, users can share files with each other.

I will guarantee confidentiality and integrity where applicable using public key encrpytion (e.g. RSA), digital signatures, hash-based message authentication code (HMAC), and symmetric key encryption.
Project spec [here](https://cs161.org/assets/projects/2/project2-problems.pdf).

## Summer 2019
### Convolutional Neural Networks - C, optimization, parallelism  
I applied performance optimization techniques including vectorization using SIMD instructions and parallelism with OpenMP to achieve a 16-times speed up in image classification tasks.  
Project spec [here](https://inst.eecs.berkeley.edu/~cs61c/su19//projects/proj4/).  

### Compiler - C, RISC-V
I completed a basic compiler for a C like language that produced RISC-V. This project helped reinforce my understand of the relationship between C code and the assembly that implements it.  
Project spec [here](https://inst.eecs.berkeley.edu/~cs61c/su19//projects/proj2/).

### Flight Simulator - C, memory management
I implemented a flight system that kept track of flights between series of airports using a linked list implementation. Each airport and its schedule of flights departing from it were represented as structs.  
Project spec [here](https://inst.eecs.berkeley.edu/~cs61c/su19//projects/proj1/).

### Datapath and Controls - CPU, Logisim  
I implemented a 32-bit processor based on RISC-V using a design/simulation tool called Logisim. I then improved the processor by implementing a two-stage pipeline.  
Project spec [here](https://inst.eecs.berkeley.edu/~cs61c/su19//projects/proj3-2/).  

## Spring 2019  
### Spam or Ham - Python, scikit-learn, NumPy, matplotlib  
I trained and implemented a logistic regression classification model to detect and mark spam emails from potentially malicious users. I first preprocessed the data and used exploratory data analysis techniques aand precision-recall quantifiers on the emails for feature selection. I then validated the model and minimized overfitting by performming k-fold cross validation on selected features to attain 88.1-90% classification accuracy.  

## Spring 2018
### Explorable Worlds Game - Java
I designed and implemented a single-player 2D tile-based game where the objective is to collect all the items to increase the player's sight in order to advance to the next level. I used a pseudo-random world generation algorithm to create a new map for every user input string. I implemented loading and saving gameplay and keyboard navigation (using AWDS) using StdDraw Princeton libraries.

This project helped introduce me to project development cycles.
Project spec [here](https://sp18.datastructur.es/materials/proj/proj2/proj2).  

### Bear Maps - Java
I worked with real-world mapping data to complete the back end of a map application based off of Google Maps. The application supports scrolling, searching, and routing for locations in Berkeley.  
Project spec [here](https://sp18.datastructur.es/materials/proj/proj3/proj3).
