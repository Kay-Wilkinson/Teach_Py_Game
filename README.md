# Teach the basics of Python...
# using a Spy Caper Game! 

This is a game designed to teach the very basics of Python and to motivate the players to continue learning this awesome language. The game only uses vanilla python so no virtual environments are needed at this stage. I chose to use a D&D role player style game for this, so a bit of imagination and acting can go a long way! 

## Getting Started
Clone the documents and print them out. 
Ensure that each participant has Python 3 on thier computer. 


## Prerequisites

https://www.python.org/downloads/

(This was designed to be used with a particular company's system to pull certain ID's and data to move forward in the game. 
Small work around for these will be needed to fit the game to your needs/situation) 

The Man from U.N.C.L.E soundtrack is a nice accompaniment with this game. 

## Nature of the Game

A plane carrying a specialised payload lost contact with its handlers on Vauxhall Street. Military Intelligence Six (MI6) reported the issue immediately.

The plane had limited fuel reserves and so, can only land at a number of locations. The mission needs to recover:
1.	The flight number 
2.	The mission ID
3.	The landing location 
4.	The passcode to the safe to recover the payload.

Her Majesty’s Government have given limited, but special use, of their code cracker file which will be needed to crack the final code which will release the doors to the plane.

Your mission dossier will include all the information needed to complete each mission stage.

You are provided with the following tools:
1.	A python cheat sheet
2.	Pilot dossier
3.	Aircraft dossier
4.	A map 

The internet can also be used to solve the problems. Alternatively, MI6 have also sent two operatives to assist with the mission.

You have an hour to complete the mission, or the payload and all souls aboard the aircraft will be lost.

Good night, and good luck.

## In Game Tasks 

### Task 1: 
Open a file and name it ‘mission.py’. In the file, declare a variable called playerName in your text editor of choice. Set it to your players name. Print the variable and run this from the terminal. 

### Task 2: 
The flight number needs to be found. The flight number is a code made of the Pilot’s licence ID number and the age of the plane. 
Find these values in your dossier pack. Declare each as variables (datatype = string) and concatenate them together as a new variable called flightNumber. 
Print the result.

### Task 3.
The mission ID number is critical to recovering the aircraft. Some of the mission id was decrypted but some of the transmission was corrupted. What was left of the recovered values can be found in your dossier. Crack the corrupted code by:
1.	Creating a variable for each number 
2.	Subtract two from the first number. Store the result in a new variable as a string.
3.	Multiply the second number (a float) by 2. Store the result in a new variable as a string.
4.	Add 2 to the final number. Store the result in a new variable as a string.
5.	Concatenate the strings together (in order) and print the result.

### Task 4.
The airport ID of the destination airport needs to be recovered. Find the ID’s found on your map. 
1.	Put these values into an array/list.
2.	Write a ‘For loop’.
3.	Nest an ‘IF/Else’ statement inside your For Loop. (Use your cheat sheet if you are stuck) that will ‘break’ ‘if’ x is equal to “2d96e.89fcc.1df5”
4.	Print the result of the For loop. 

### Task 5(a).
Crack the final code to recover the payload. 
1.	Go to admin.spotxchange.com 
2.	Submit the flightNumber under ‘publisher’
3.	Search under campaigns for the Airport_ID. 
4.	Search for the mission ID number under the channel tools. Check in the ‘Internal Notes’ for the mission. The rest of the code will be in there. 
5.	Copy the first half of the code and the second half into an array called ‘code’.

### Task 5(b).
1.	Import the code_cracker.py file into your mission.py file.
2.	Call the crack_code(code) function. 
3.	Run the mission.py file to see the cracked code. 
4.	Find the cracked code in ‘Creative Review’ to recover the payload and complete the mission. 


