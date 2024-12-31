https://feliciatrinh.github.io/projects/

# Personal Projects

## 2025

### Subscriptions - Flask, Python, SQLite, HTML

[GitHub Repo](https://github.com/feliciatrinh/subscriptions/tree/main)

I created a basic Flask app to track my subscriptions to streaming services and display statistics such as
- cost of each subscription
- total cost per month
- total cost per year
- number of films/tv shows watched per month
- most frequently used service

After installing the required packages in `requirements.txt`, you can run the app locally using
> flask run

## Fall 2019
### Alexa Skills - JavaScript, AWS Lambda
I created a trivia based Alexa skill called MAMAMOO Trivia. MAMAMOO is a South Korean kpop girl group. Upon opening MAMAMAOO Trivia, Alexa plays MAMAMOO's greeting.
Then, Alexa asks the player multiple choice questions and the player responds with the number of their answer choice. Alexa will also exit the game playing MAMAMOO's greeting.
Check it out [here](https://tinyurl.com/mamamootrivia)!

I am also developing a trivia based Alexa skill called Protobowl.
Quiz Bowl competitors will be able to use this Alexa skill to test their knowledge in the 7 official Quiz Bowl categories: philosophy, social sciences, religion, history, literature, geography, mythology, fine arts, and science.
The game will launch and prompt the player for a category.
After choosing a category, the player will be able to answer questions taken from past Quiz Bowl tournaments.

I plan to improve this Alexa skill in the future by integrating Echo Buttons.
Multiple players will then be able to play in teams and buzz-in, which would better match a real Quiz Bowl tournament.

## Spring 2019
### Menu Section API - Python, Django, SQLite
I built a server-side API using Django that would enable restaurant owners to update their menu dynamically. This RESTful application supports both browser and curl usage and presents data in a clearly formatted JSON.
I did this project to learn more about Django and APIs.
See code [here](https://github.com/feliciatrinh/api-menu-section).

# Internship Projects

## Summer 2019 - Summer 2020
### Picovoice - python, pip
I helped [Picovoice](https://picovoice.ai/) build pip packages for their open source, private AI technology. The pip package for their on-device wake-word detection engine, [Porcupine](https://github.com/picovoice/porcupine), is live at [PyPI](https://pypi.org/project/pvporcupine/). Feel free to demo it!

I also deployed two more pip packages for their speech-to-text ([Cheetah](https://github.com/picovoice/cheetah)) and speech-to-intent ([Rhino](https://github.com/picovoice/rhino)) engines.

### Picovoice - python, tutorials

I wrote [tutorials](https://picovoice.ai/tutorials/) and [python scripts](https://github.com/feliciatrinh/speech-to-intent-benchmark) that demonstrate how to objectively benchmark 5 different natural language understanding engines:
- Amazon Lex
- Google Dialogflow
- IBM Watson
- Microsoft LUIS
- Picovoice Rhino

### Picovoice - React

Created a React app that uses speech recognition to generate emojis by voice lookup.

# Academic Projects
Because of concerns over plagarism, I am unable to post the code for these projects publicly.

## Fall 2019
### Database Systems - Java, B+ trees
During the fall semester, I implemented a database system that will be able to support executing simple transactions in series. I've finished implementing a B+ tree index and efficient join algorithms (e.g. sort-merge join) so far. The next steps are query optimization, multi-granularity locking for concurrent execution of transactions, and database recovery.

### Encrypted File Sharing System — Golang

I designed and implemented a file sharing system (like Dropbox) that protects user privacy using public key encryption, digital signatures, hash-based message authentication code, and symmetric encryption
User files were encrypted and decrypted on the server, and the server supported sharing and revoking access.

## Summer 2019
### Convolutional Neural Networks - C, optimization, parallelism
I applied performance optimization techniques including vectorization using SIMD instructions and parallelism with OpenMP to achieve a 16-times speed up in image classification tasks.
Project spec [here](https://inst.eecs.berkeley.edu/~cs61c/su19//projects/proj4/).

### Compiler - C, RISC-V
I completed a basic compiler for a C like language that produced RISC-V. This project helped reinforce my understand of the relationship between C code and the assembly that implements it.
Project spec [here](https://inst.eecs.berkeley.edu/~cs61c/su19//projects/proj2/).

## Spring 2019
### Spam or Ham - Python, scikit-learn, NumPy, matplotlib
I trained and implemented a logistic regression classification model to detect and mark spam emails from potentially malicious users. I first preprocessed the data and used exploratory data analysis techniques aand precision-recall quantifiers on the emails for feature selection. I then validated the model and minimized overfitting by performing k-fold cross validation on selected features to attain 88.1-90% classification accuracy.

## Spring 2018
### Explorable Worlds Game - Java
I designed and implemented a single-player 2D tile-based game where the objective is to collect all the items to increase the player's sight in order to finish the level. I used a pseudo-random world generation algorithm to create a new map for every user input string. I implemented loading and saving gameplay and keyboard navigation (using AWDS) using StdDraw Princeton libraries.

This project helped introduce me to project development cycles.
Project spec [here](https://sp18.datastructur.es/materials/proj/proj2/proj2).

![Main Menu](assets/images/main-menu.png)Main Menu

![Seed Prompt](assets/images/seed-prompt.png)Seed Prompt

![Begin the Level](assets/images/begin-level.png)Begin the Level

![Collected Items](assets/images/four-items.png)Collected Enough Items

### Bear Maps - Java
I worked with real-world mapping data to complete the back end of a map application based off of Google Maps. The application supports scrolling, searching, and routing for locations in Berkeley.
Project spec [here](https://sp18.datastructur.es/materials/proj/proj3/proj3).
