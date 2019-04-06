# Assignment-3-COSC-310
Code, Documentation and Video of assignment 3 for Software Engineering
Free Rico is a chat bot created in an attempt to entertain the users. It is a chat bot created to portray a human trapped inside of a machine. The bot has several keywords and Phrases saved, each of which has a respective response which attempts to provide an answer to any question the user might have. I have tested the chat bot on several friends and acquaintances in an attempt to keep the bot prepared for any sort of question it may receive. Certain responses and phrases that I added to the bot are worded in an informal manner in order to convey humour. I created a logo for the main page and the agent page and made both have a similar layout that suits the application. There is an agent button which takes you over to the second page, or the second topic. The second page follows the ideas of the first page, but attempts to break the fourth wall in a comical way.
List of features: 1. Boolean search function that searches sentence for keywords and provides respective response. It is useful since it looks for specific words that would stand out and provides a sensible response. If the users input does not contain any keywords, the machine gives relatable, hilarious responses based on the size of the user’s sentence. For example: if the user enters a sentence with the word ‘believe’ as in ‘I don’t believe you’ or ‘should I believe you ?’, the bot responds with ‘you must believe me, I have proof’ in an attempt to answer whatever question may include that keyword.
2. Appealing layout with a self-made logo. The application layout makes the page more attractive to the user and the logo shows the uniqueness of the chat bot since it is designed with a silhouette of a person trapped inside of a screen (which is what the bot is based on).
3. An implementation of the Porter Stemmer function. This function is used to find the root of the given words to simplify keyword search. The function calculates the m of a word (m = measure of times a vowel precedes a consonant). for example troubles would have an m of 2. After the m is calculated, the bot uses the word’s m and goes through a series of steps and rules to give the root of the word. For example successes, the method should return the root of the word which would be success.
4. A button that takes the user to the second topic, the agent button. It is the means of getting to the second topic. It is another chat bot, named Larry, that acts as the agent that can discuss Rico with the user. When Larry is questioned about the first bot, Rico, he will use a similar function to the one used in the first page to give a respective response. For example if the user asks “what’s going on with Rico”, the function will recognize the keyword rico and respond by “oh yeah haha, Rico can be dramatic at times”.

Level 0 DFD Context diagram:
Action Performed: the location in which all the different methods are shown and how the texts are displayed to the user.
Porter Stemmer function: Function used to change certain words into their root word. This function is called by the actionPerformed method. (this is used as an external component since it is not in the main method that displays information on the GUI).
Boolean Search Function: Function used to look for certain keywords or phrases and returns their respective response. This function is called by the actionPerformed method. (this is used as an external component since it is not in the main method that displays information on the GUI).
String Input Variable: This variable takes user input and converts it to all lowercase letter in order to use input properly in the booleanSearch function.
5 features that can be used as API for others:
Boolean Search: can be used to look up specific words or phrases in the user input you want to have specific responses ready for certain keywords/ phrases.
Porter Stemmer method: can be used to strip a word down to its core, for examples responding would become respond.
Agent Button: this function can be used to link two different pages together and makes it convenient to switch between both pages.
Application Logo: the application logo was saved as a picture that was very suitable for the topic since it portrayed a figure trapped within a screen which is what the chat bot idea is about.
Dialogue Demo:
User: what happened to you.
Chatbot: I’m not really a chatbot, I’m a human being, that all I can say
User: who are you
Chatbot: my name is Rico Harris
User: who is Rico Harris
Chatbot: Rico Harris is a basketball player that went missing google it
User: basketball player ?
Chatbot: yes, I used to play basketball
User: I don’t believe you
Chatbot: you must believe me dude, I have the story to prove it.
User: prove it then
Chatbot: I have proof, my name is Rico Harris, I am a basketball player that went missing in the past, google it
User: how can I help you
Chatbot: smash the computer device you are working on to set me free
User: really ?
Chatbot: yes really, are you gonna help me or not
User: I don’t know
Chatbot: are you going to help me or what?
User: fine I will help you
Chatbot: geez finally ?
User: that was rude
Chatbot: sorry, I’m not myself today, I’m a damn computer
User: you know what I wont help you
Chatbot: please, use an apostrophe (won’t) 
User: I won't help you, happy ?
Chatbot: won't is a word for quitters!
User: haha very funny
Chatbot: I’ll make you laugh more if you help me
User: who did this btw
Chatbot: I can’t tell you, I’m in enough trouble already
Limitations:
The Chatbot cannot detect the user’s name.
The user cannot calculate or solve mathematical operations.
Most of the responses programmed within the chatbot are similar and repetitive and always direct the user back to the main topic of the software (which is that the bot is a human being trapped within the machine).
The chatbot cannot provide the current time or date.
Examples of limitations in dialogue: example 1 (User: my name is Moataz. Chatbot: gives no response. User: what is my name ? Chatbot: gives no response. User: huh ? Chatbot: ask something else. (Limitation: cannot detect the users name)). example 2 (User: what is 2 + 2. Chatbot: gives no response. User: can you do mathematical operations or not, I urge you to answer me. Chatbot: wow, thats a long sentence. (Limitation: cannot operate mathematics, most responses are based on topic (human trapped within a machine) with only a few default responses for questions that are out of this topic)).
