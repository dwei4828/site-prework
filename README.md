# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **David Wei**

Time spent: **10-15** hours spent in total

Link to project: https://glitch.com/edit/#!/strong-light-spruce
		 https://strong-light-spruce.glitch.me

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
* [X] Playback speeds up on each turn
* [X] Computer picks a different pattern each time the game is played
* [X] Player only loses after 3 mistakes (instead of on the first mistake)
* [X] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [X] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!
* [X] Modified cluePauseTime and nextClueWaitTime to make game smoother
* [X] Reminds player how many lifes they have left when they make a wrong guess

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![]https://i.imgur.com/2Em4JTv.gif
![]https://i.imgur.com/SATn0lV.gif


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
[https://www.jquery-az.com/using-javascript-setinterval-with-clearinterval-4-demos/
https://www.w3schools.com/]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
[The most difficult challenge I encountered in creating this submission was when doing the ticking clock feature. At first I checked the w3school website to get some knowledge about setInterval() and clearInterval(), and then I tried to save the setInterval function to a global variable and create a start and stop function to call. Then I realized that it will start the timer before the user clicks on the start button. So I researched a bit more on how to use setInterval and clearinterval, then I decided to set the variable to some value first and then change it to setInterval function when the user presses the start button. It did solve the problem but a new problem appears which is the clearInterval function did not stop the timer after the game stops. I was stuck on this for a while and then I looked up more examples of different usage of setInterval, and then I realized that I can put my clearInterval function into my setInterval function with a condition that checks if the game stops or ends, this will immediately stops the timer after the game ends. There were some other small details that I changed in other functions when debugging, but that was the most challenging part of that feature in my opinion. It also taught me understanding different usage of an implement function is crucial for using it correctly to solve a problem.
]

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
[There are many questions about web dev that I have after completing the project, however, it comes to three really importants ones that I want to ask. The first is that if we want to save the data that was produced from this web page, how are we going to send the data to the database? For example if there is a score count for the game, and the user wants to keep track of his score but he can not keep this web page forever, what can we do to save the data in another place? The second question came up when I was implementing the additional features. I realized that I had to make changes to functions that I wrote before, and I believe sometimes one single change in a function would cause other functions to behave differently. I wonder if there is a big project with large front end workload, would there still be one developer that edits the CSS/HTML/JS files or there would be more developers? And if there are more developers, how do they prevent messing up other people’s function when implementing new features to the project? The last question is how would someone that is more familiar with back end languages utilized their back end knowledge to contribute to a web development project.]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
[If I had a few more hours to work on this project, there are two main features that I want to add. The first one is to change the game mode from a fixed amount of pattern, to unlimited. The game will keep going until the user uses up all 3 lives or the timer runs out. This way will make the game more interesting and people can actually use this to simulate some kinds of sequence memory benchmark. The second feature is related to the first one, since the game will keep going then it is also important to keep track of people’s record. I would add a highest score on the page that updates whenever there is a new high score. ]



## Interview Recording URL Link

[My 5-minute Interview Recording] https://www.loom.com/share/ce8b5f1e0d4c4810a9665b9362850dbc


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