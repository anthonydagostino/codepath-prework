# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Anthony D'Agostino**

Time spent: **10** hours spent in total

Link to project: (insert your link here, should start with (https://glitch.com/~lightandsoundmemoryanthonydagostino)

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
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![](http://g.recordit.co/lvKMQtCHd7.gif)
![](http://g.recordit.co/Tw6dPl7sqL.gif)
![](gif3-link-here)
![](gif4-link-here)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
StackOverflow, Google images and w3schools

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
While attempting to implement some of the optional features, I struggled on figuring out how to make the button have a background image when pressed. I knew I would most likely have to replace the background color when the button is actively pressed down. After looking on w3schools for the background-image command, I found out I should keep the background color in case the image became unavailable, and I implemented the background-image command to style.css. I still needed to find an image to link and at first I tried just copying and pasting the url link to find out it didn't work. Within 10 minutes of researching how to resolve the issue, I figured out I needed to drag the google image into the assets section of my glitch project. Once I had the image in the assets folder, I could then copy that link in order to use it in my background-image command. I repeated this for every button so that when it was actively being clicked on, the image would be displayed on the button. This resolved the issue I was having after taking the time and effort into work through different ways in order to obtain a solution and I successfully implemented different images for each button!

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
How would I go about making this game have its own website? How would I go about making movement without the user doing anything? Is there an easy way to place things where I want them? For example, if I wanted to move a button to the bottom center is it just trial and error testing out different spacing or is there another way? Are HTML, CSS and JavaScript the only three languages used for web development? Are they the only three that I will need to be using? Will knowing other languages such as C or C++ be useful at all for web development?

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
Before even reading this question I was thinking about how I would go about implementing a feature which would prompt the player to select the gamemode difficulty prior to starting the game. Having three different game difficulty levels, easy, medium, and hard, with each level of difficulty the player would have to repeat the pattern with a shorter time limit. Another feature the difficulty levels would have would be increasing the speed of the computer playing the pattern as the levels progressed and just having more buttons right from the start. My initial thought was to have a different page which asked which difficulty level you would like to play at, but I am not entirely sure how to do that. If I was not trying to make a separate page to prompt for difficulty level, I would have the three levels appear before any buttons or start button appear, and once selected the difficulty level the player would then see the buttons and the start button appear.


## Interview Recording URL Link

[My 5-minute Interview Recording](https://youtu.be/BU8T0L_UJVI)


## License

    Copyright Anthony D'Agostino

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
