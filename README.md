##Command Line Speech Control

## Overview 
The goal of this project is to make a free software tool that allows the user to speak into a microphone and then have that transcribed and entered where the user wants.

## Background
Users with motor disability are often unable to use their hands to interact with a computer. Therefore, using tools that require heavy use of the hands such as typing is unfeasible or impossible for such users. 

##Motivation 
As well as being part of a third year BIT project, the main motivation behind the program is to allow people who are unable to type to be able to control the command line whithout having to pay unreasonable prices. Our software is free and anyone can contribute, this is a completely open source.

##Installation
To build this software on your computer, you will require the following: 
- Microsoft Windows
- Python 2.5 or higher 
- A high quality microphone or heasdset to improve the speech recognition 

###Users
1. Clone or download this repository to your local machine.
2. Navigate to the Users folder in the downloaded repository.
3. Open the application by locating and double clicking the Speech Transcriber file
	* If a security warning pops up click the "Run" button
4. Click "Start Speech Recognition" button to start the program searching for speech.
	* There are different speech recognition services that can be used. To change which one you use make sure that speech recognition is not running then select the circle next to the service you wish to use and then start the speech recognition. CMU Sphinx is the online service that will work offline. All others need to be connected to the internet.
5. Click into where you would like the words to be placed and then start speaking.
	* The program will keep transcribing what you say until you tell it to stop.
	* The enter key is automatically pressed when you have finished speaking so you will need to say everything you wish to all at once.
6. To stop the speech recognition you simply press the "Stop Speech Recognition" button. 

###Developers
1. Create a python virtual environment on your machine

	```
	C:\path\to\virtual\env virtualenv nameofenvironment
	```
2. Clone or download this repository to your local machine.
3. Activate the virtual environment

	```
	C:\path\to\virtual\env nameofenvironment\Scripts\activate
	```
4. Navigate your way to the Developers folder in the repository you downloaded.
5. Install the dependencies needed to run the program

	```
	pip install -r requirements.txt
	```
	
6. Download ActiveTcl from http://www.activestate.com/activetcl/downloads
7. To Run the program start the gui
	
	```
	python gui.py
	```

##Contributors
- David Rozado 
- Greg Field
- Logan Moffitt

##Built Using 
- Python
- Google Speech API
- Tkinter 
