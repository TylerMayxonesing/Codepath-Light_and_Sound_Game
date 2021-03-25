# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Tyler Mayxonesing**

Time spent: **15** hours spent in total

Link to project: https://glitch.com/edit/#!/light-ands-sound-game

## Required Functionality

The following **required** functionality is complete:

* [ ] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [ ] "Start" button toggles between "Start" and "Stop" when clicked. 
* [ ] Game buttons each light up and play a sound when clicked. 
* [ ] Computer plays back sequence of clues including sound and visual cue for each button
* [ ] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [ ] User wins the game after guessing a complete pattern
* [ ] User loses the game after an incorrect guess

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
https://hackmd.io/@TySwifty/BJyYR8t4d


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

I didn't use much in terms of outside resources. I did however ask my brother for conceptual help in the logic portion of the game. While he isn't a programmer, his relative insight and outside perspective helped me better understand and reason through the guess handling part of the code.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

The biggest challenge that I had while working on this submission was the dread of doing something that I had never done before. Trying out new things is usually very intimidating when you don't have anyone to work you through it in person. That being said, I was able to overcome this uncertainty by using my prior experience with app development to better understand the overall file structure that goes into developing a website. For one, script.js can be thought of as the actual logic of the code. In Android development, UI and logic are separated, so I reasoned that script.js was how the website behaves, and that index.html and style.css was for how the website looks. Additionally, the idea of a “div” was confusing at first, but then became very familiar. A div is a sort of container for elements, and in Android development, we typically work with views and view groups which are a collection of elements, such as button, containers, icons, etc. As soon as I began thinking of a div as view, the process of reading and writing html became somewhat easier.


3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

One question that I had once completing the project is how exactly are websites deployed and what steps would I have to take in order to publish a website and ensure maintenance long term? Another question that I had was which environment are websites typically developed in? Of course, Visual Studio was be a likely answer, but is there another preferred IDE that the web developer community prefers? Lastly, one other question that I had was what kinds of coding conventions are there when developing a website. For the code that we wrote on Glitch, we only have about three files, but are there cases when we would need several html, js, or css files, and also what types of libraries are at our disposal for web development?


4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

If I had a few more hours to work on this project, I would have liked to implement some music along with a timer which clicks. Both the music and the timer will become progressively faster as the game continues and as the pattern gets longer. I would have also liked to have added a more appealing Game Winning screen with stars and the color green in order to create a far greater sense of accomplishment. Adding multiple levels was also something that I considered. Each level would have a pattern which was longer than the previous one and would have a different song which would have a different beat and different tones connected with the buttons. This would motivate the user to get to the next level in order to see what music and which tones would be playing.


## License

    Copyright [Tyler Mayxonesing]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
