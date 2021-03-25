# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Anna Howell

Time spent: **11** hours spent in total

Link to project: https://glitch.com/edit/#!/sugared-rigorous-watchmaker

## Required Functionality

The following **required** functionality is complete:

* [X] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [X] "Start" button toggles between "Start" and "Stop" when clicked. 
* [X] Game buttons each light up and play a sound when clicked. 
* [X] Computer plays back sequence of clues including sound and visual cue for each button
* [X] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [X] User wins the game after guessing a complete pattern
* [X] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [X] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [X] Buttons use a pitch (frequency) other than the ones in the tutorial
* [X] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [X] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [X] Game button appearance change goes beyond color (e.g. add an image)
* [X] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [X] Made all elements scalaable to size of web page
- [X] Added a sound when the game ends
- [X] Made the game go on until the player loses
- [X] Added notification of the level when the player loses
- [X] Added different colors when the button is hovered over and a shadow to the buttons

## Video Walkthrough

https://recordit.co/4hUR4EfFKw


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
I consulted stackoverflow and w3schools as well as my prior knowledge of HTML/CSS. 

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
I added different audios as the sounds for this project, and when I did that I needed to figure out how to play the audios instead of frequencies. In order to do this I made the audios constants and then added them to the map, and then used the play method to play the audios instead. I originally had a bit of difficulty understanding why the audio that I was playing was overlapping. I realized that I needed to change the times in between the audio.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
I am most interested in learning about how to properly structure a webpage. I found that making sure things were sized and centered was a bit finnicky and my reading didn't really help me to understand why. I also would like to learn how to add elements to a page after the page has already been loaded. 

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
I was trying to make it so that the button was only pressed to the amount of time that the audio was playing, but the audios are different lengths and I would have to refactor certain functions to account for the fact that different buttons have different audio lengths. I also would've liked to add a level counter at the bottom of the webpage that lets you know your current progress in the game. I would also like to try to figure out how to include a high score table, and maybe make some additional stylistic chocies about the layout of the webpage. 



## License

    Copyright Anna Howell

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.