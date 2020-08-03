# Voice-to-Sign-Language-Translation

Proposed Solution

Sign language is a visual language that is used by deaf people as their mother tongue. Unlike acoustically   conveyed   sound   patterns,   sign   language   uses   body   language   and   manual communication to fluidly convey the thoughts of a person.
Due to considerable time required in learning the Sign Language, people find it difficult to communicate with these specially abled people, creating a communication gap.
Thus, we propose an application which takes in live speech or audio recording as input, converts it into text and displays the relevant Indian Sign Language images or GIFs.

Front-end using EasyGui.
Speech as input through microphone using PyAudio. Text Pre-processing using NLP.
Dictionary based Machine Translation.
 
Phases of the Project
•	Obtain audio from the Microphone and perform Speech Recognition using sphinx.
•	Convert the speech recognized to text.
•	Display relevant images or GI

Proposed Methodology

Sign language is a visual language that is used by deaf people as their mother tongue. Unlike acoustically conveyed sound patterns, sign language uses body language and manual communication to fluidly convey the thoughts of a person.
Due to considerable time required in learning the Sign Language, people find it difficult to communicate with these especially abled people, creating a communication gap.
Thus, we propose an application which takes in live speech or audio recording as input, converts it into text and displays the relevant Indian Sign Language images or GIFs.

Audio to Sign Language Translator
1.	Start
2.	Getting the Speech.
2.1.	Listen for 1 second and calibrate the energy threshold for ambient noise levels.
2.2.	Listen the Speech using Microphone.
Now the energy threshold is already set to a good value, and we can reliably catch speech right away.
3.	Recognise the Speech.
4.	Convert Speech to Text.
4.1.	Make the Text to lowercase for further manipulation.
5.	Detected Text
5.1.	If “goodbye” then exit.
5.2.	Else if Detected Text in predefined Dictionary Words. Display respective GIFs of the Phrase.
5.3.	Else Count the Letters of the Word/Phrase.
5.3.1	Display the Visual of the phrase with some delay of Actions.
5.4.	Continue all the steps from Step 3, and continue till the Speech Ends.
6.	If Error in Step 2, That is if no Speech Detected then display error message “Could not listen”.

Phases of the Project
•	Obtain audio from the Microphone and perform Speech Recognition using sphinx.
•	Convert the speech recognized to text.
•	Display relevant images or GIFs as applicable
 
NOVELTY / INNOVATION

•	Around 466 million people worldwide have disabling hearing loss (1), and 34 million of these are children.
•	It is estimated that by 2050 over 900 million people will have disabling hearing loss.
•	Hearing loss may result from genetic causes, complications at birth, certain infectious diseases, chronic ear infections, the use of particular drugs, exposure to excessive noise, and ageing.
-	Source:	World	Health
Organization
As per the data from WHO it is estimated 900 million people will have Hearing Loss disability, after all this there is not much available technology to make communication with deaf people. We aim to provide a technology to ease the communication.
Generally, to have communication people need to either know the sign language or they need the human translator to make the communication possible.

To provide the solution we will make a software that takes an input in the form of speech and displays the respective Sign Language for the phrase.
 
IMPLEMENTATION / DEMO

Sign language is a visual language that is used by deaf people as their mother tongue. Unlike acoustically conveyed sound patterns, sign language uses body language and manual communication to fluidly convey the thoughts of a person.
Due to considerable time required in learning the Sign Language, people find it difficult to communicate with these especially abled people, creating a communication gap.
Thus, we propose an application which takes in live speech or audio recording as input, converts it into text and displays the relevant Indian Sign Language images or GIFs.

Use Cases
	Interface
This is the opening interface of the Hearing Impairment Assistant which gives us option to start the Application using two options:
o	Live Voice
This allows user to start the interaction and get the resulted Indian Sign Language Visual from the given Speech.

o	All Done!
This option allows the user to exit the Program.
 
	Detecting Speech: Speech Recognition

The application will ask to say something, then it will turn on the micro phone of the system to listen to the voice. The program will listen for a specific amount of time if no speech is detected then it will ask again to say something.
Here in this scenario we spoke the word “hello” and program recognized the word and thus converted it into text.

	Speech to Text Conversation / Translation

The application in the previous scenario listened to speech and detected the word “hello”. Speech recognized is then converted to text for further manipulation.

	Manipulation Text to Derive the Required Indian Sign Language.
In the previous scenario we saw the program successfully detected the word “hello” now the application matches the word initially with a database of GIFs which show the animation of the word or a phrase. But if the Phrase or word is not present in the database then Application will show the detected phrase in Indian Sign Language Visual letter by letter.
