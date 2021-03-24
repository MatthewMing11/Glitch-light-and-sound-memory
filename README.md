# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Matthew Ming**

Time spent: **1** hours spent in total

Link to project: (insert your link here, should start with https://glitch.com...)

## Required Functionality

The following **required** functionality is complete:

* [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [x] "Start" button toggles between "Start" and "Stop" when clicked. 
* [x] Game buttons each light up and play a sound when clicked. 
* [x] Computer plays back sequence of clues including sound and visual cue for each button
* [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [x] User wins the game after guessing a complete pattern
* [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![](your-link-here)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

I used w3schools because I needed to double check what property was needed for me to access the length of a array.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

One challenge I encountered when creating this submission was trying to convert the flow diagram for the game's guessing logic into code. I overcame this obstacle by first trying to convert 
the flow diagram into pseudocode so I could understand the structure of my code before translating it into actual code. Specifically, I had a bit of trouble understanding when the turn was over since it wasn't clear to me when I read over the diagram and its description about what the progress variable represented. It was until I went over the flow
diagram that I noticed that the progress variable was being incremented when it wasn't the last turn. Clearly, this variable had to be associated with the turns of the game. I thought about it for some time and realized the progress variable measured the current turn of the game. I was now able to understand the logic fully and wrote my code according to how the logic was layered. I made sure to return in each if statement since I did not want to go through all the if statements by mistake.  
After working through the problem and writing the code, I reread the docs and noticed that my interpretation was inline with the definition given for the progress variable. This challenge taught me both to always look over the entire problem
when something is unclear and also to reread the docs as the answer to my questions are usually found there.


3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

Some questions I have about web development after completing my submission are how much math does the average web developer do to make their apps? and how much time does the average web developer take in styling their webpages?
From this submission, there was some amount of math needed to calculate how much time was allowed between inputs and how fast the web page rendered the button presses. I imagine that it takes a lot of math for advanced web pages to 
create the amazing effects they show to users like animated widgets and interactive elements on the webpage. I also looked over the styles made in this submission and wondered how long it takes to style the webpage. This basic
web page did not have much styling but it did take a lot of lines of code to wrote. I was wondering how much time is needed to code and style advanced web pages like Twitter to make it eye-catching and pleasing to the user. 

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

If I had a few more hours, I would first spend them on working on the additional features like adding 2 more buttons that have more varying tones than the already existing buttons and making the
time in the clue playback faster since it was slow enough for me to remember the clue pattern. I would then try to add the strike system and implement the random pattern for the game since 
these stretch goals are easy enough to implement. After I implemented these features, I would go back and comment most of the code so my code is more understandable if I choose to go back to it.
I would also change up the colors used in the style.css for the webpage because the colors I am currently using are the default ones used in the docs and are not very pleasing to the eye.



## License

    Copyright [YOUR NAME]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.