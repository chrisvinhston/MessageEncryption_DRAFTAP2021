# Message Encryption
(Week1 Iron Hack Project)
by Chris Vinhston and Estelle Liaubet
DRAFT April 2021, Iron Hack, Paris

https://static.lpnt.fr/images/2017/10/27/10978762lpw-10979123-article-jpg_4669854_980x426.jpg

## Content
1. Requirements & Deliverables
2. Project Description
3. Rules
4. Workflow & Organization

### 1. Requirements & Deliverables
The mandatory requirements that this project needs to satisfy are:
- Trello board  : https://trello.com/b/kMIED6Bi/message-encryption-project
- Git repository : https://github.com/EstelleLili/MessageEncryption_DRAFTAP2021
- Presentation available here : https://docs.google.com/presentation/d/18fC5gDu0Gr6lpsKmB4qqNLi-IoOSxhqMZvhXy3ad6AI/edit?usp=sharing
- Your code must include functions

### 2. Project Description
This game aims to encrypt input and decrypt it into output.
It will allow us to securely protect data.

### 3. Rules
The idea is to provide users an automatically generated key.
First user will give some input, which will be encrypted.
In order to decrypte it, second user shall enter the key, and see the decrypted message as an output.


### 4. Workflow & Organization
About the form:
First target was to come with the project and its architecture from project's board, to coding game and slides.
Then we had to begin to implement functions, to see we were making it (too) simple. After some iterations we find a good way to go further, helping each others, sharing the work and switching tasks when we were stuck/needed. 

About the content:
We both brainstormed using Trello.
We agreed onto a conceptual architecture (cf pseudocode).
We wrote down the code using differents draft files, then merged everything into one main python file.

About the repository:
    * .readme -> all information about the project
    * .gitignore -> safeguard to prevent us from pushing any file or extension indicated
    * pseudocode.py -> main architecture of what the code should looks like
    * secret.key -> to store securate automatically generated key
    * main.py -> all python code, aka the game
    * msg.csv -> store timestamp, message, encrypted_message and key
    


