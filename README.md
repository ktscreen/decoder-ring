# Decoder Ring
Decoder Ring project made during Thinkful Software Engineering course

## Overview
This is a project I made during the Thinkful Software Engineering Flex course. This simple webpage takes in string inputs and will encode or decode them using three differeing methods of endoding.

The Ceaser Shift take the string input and shifts it's letters either forward or backwards through the alphabet to encode a message. It can then take the shifted word back and decode it if the shift value is given.
The Polybius Square uses a grid to assign each letter with a coordinate (with the exception of i and j which are assigned the same coordinate). The code can then take a coded string, split the string into coordinates, and decode the message and return it as a string.
The Substitution Cyper takes in a string and assigns its letters to a "substitution alphabet" to encode a message. In order to decode the message, the user must also input the correct substitution alphabet (refered to as the Alphabet Key on the webpage) to decode the message.

## Technology
Built using Node.js
Tested using Mocha and Chai
