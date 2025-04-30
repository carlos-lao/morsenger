# Morsenger: Morse Code iMessage App

## Overview
This iMessage extension allows users to send and receive messages in Morse code. Messages are inputed using a traditional telegraph-style button input and can be sent as text (both encoded and decoded) or audio.

## Features
- Users can send regular (i.e., Latin script) text messages using a telegraph-key input
- Users can send Morse-encoded messages as dot-dash text representation and/or as an audio file
- Users can change the speed (in wpm) of reading input and the default output audio
- Users can delete (and insert? idk we'll see) input during entry
- Decoded/encoded input is displayed to the user during entry
- Received messages can be played back at a different speed if the user has the app (??? idk maybe)

## UI Sketch
That's all you king. I'm so bad at UI design...

## Technical Plan
- Implement telegraph-key button to get user input
- Create `Message` model to encode, decode, and convert messages to audio
- Create some way to edit messages (deletion, insertion?)
- Allow speed adjustment for input and output (wpm)
- Make a custom display for opening messages with the extension
- Literally what else would this thing need...

## Split
- **Carlos**: implementing input UI, telegraph input, message encoding/decoding/editing, speed adjustment (I have a lot of this from the first version already)
- **Shantanu**: UI/UX design, implementing output UI, audio conversion/generation
