Voice Assistant - Chitti
This Python script is a virtual assistant that uses speech recognition to understand and execute voice commands. It can perform a variety of tasks, including:

Searching Wikipedia
Opening YouTube, Google, and StackOverflow
Playing music from a directory
Telling the time
Opening Visual Studio Code
Sending emails
Dependencies
The following libraries must be installed to run this script:

pyttsx3
speech_recognition
datetime
wikipedia
webbrowser
os
smtplib
Usage
Run the script in your terminal or IDE of choice.
The AI assistant will greet you and ask how it can help you.
Speak a command, such as "open YouTube" or "play music".
The AI assistant will interpret the command and execute it.
Functions
speak(audio): Uses the pyttsx3 library to speak the audio string.
wishMe(): Greets the user based on the time of day.
takeCommand(): Uses the speech_recognition library to listen to the user's voice command and convert it to text.
sendEmail(to, content): Uses the smtplib library to send an email to the specified recipient with the given content.
Commands
wikipedia: Searches for a topic on Wikipedia and reads the summary.
open youtube: Opens YouTube in the default web browser.
open google: Opens Google in the default web browser.
open stackoverflow: Opens StackOverflow in the default web browser.
play music: Plays a random song from a directory.
the time: Tells the current time.
open code: Opens Visual Studio Code.
email to harry: Sends an email to a specified recipient with a specified message.
goodbye, bye, quit: Exits the script and says "Have a nice day".




