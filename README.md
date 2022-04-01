# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Anderson Chen**

Time spent: **9** hours spent in total

Link to project: (https://glitch.com/edit/#!/burnt-picturesque-adasaurus)

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

* [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [x] Buttons use a pitch (frequency) other than the ones in the tutorial
* [x] More than 4 functional game buttons
* [x] Playback speeds up on each turn
* [x] Computer picks a different pattern each time the game is played
* [x] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:

Winning Game and Speeding Up
![](http://g.recordit.co/I0jG91hIU6.gif)

Losing Game and Three Strikes
![](http://g.recordit.co/yCdSiFKyNh.gif)

Start and Stop Buttons
![](http://g.recordit.co/fUl6B5NFci.gif)
![](gif4-link-here)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 


I used the website stack overflow and also rented a java script textbook from my school library "Eloquent JavaScript: A Modern Introduction to Programming"

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 



The first challenge that I encountered was the formatting of the JavaScript language. I had no prior experience of JavaScript at all and minimal experience with java itself. The required tasks of the project were not so daunting, as the instructions were concise and easy to follow. I did however encounter an error with running the program right before I had entered the guess function. The program wouldn't continue and play a sound after I pressed the start button. I opened up the console to try and debug and after about an hour or so, I found out that my naming had been mismatched for a couple of my buttons and my alignment was off for a few functions. I had copy and pasted some of the code from the tutorial, which messed up the alignment in a couple lines of code. After fixing these issues, I moved on to the optional features. I had no trouble adding additional buttons, but I had to look up how to utilize the Math.random function as I've never used JavaScript before. After a couple of hours playing around with the feature, I completed the task. Since I did some research and read through the textbook, I had no problem adding the speed up feature along with the strikes feature into the project.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 


During this project, I only created a simple memory game, but I was wondering how it could be used in conjunction PHP servers/ backend services and REST APIs to create websites that are synchronous that provide real time data to its users. Another thing that I am curious about is if other websites services like Webflow, Squaresites can truly replace JavaScript + CSS websites in the future. I know that JavaScript allows for fully customizable websites, but webflow along with other services seem to have come a long way in allowing their users to develop websites without knowing how to code. I am also curious to see how web development can also be applied to creating mobile applications and whether or not the process is similar. 

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 



If I had a few more hours to work on this project, I would probably add additional optional features that I didn't have much time to work on (midterm season, taking care of family). I would also like to have created a longer memory game with different levels of difficulty that ramped up in length and added squares as you progress. Instead of having random generated notes, I would've chosen specific songs and specific melodies for each level. For example, I would've added songs like twinkle twinkle little star with more than just 6 notes at higher difficulties. I also think it would be interesting if there were interacting graphics on the webpage to make it seem more appealing. The last thing that I would've done, is to create a leaderboard that has a record of all users and the highest level they've gotten to. 



## Interview Recording URL Link

[My 5-minute Interview Recording](your-link-here)


## License

    Copyright Anderson Chen

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
