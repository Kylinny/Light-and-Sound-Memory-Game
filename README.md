# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Junyi Yao**

Time spent: **7** hours spent in total

Link to project: https://tar-square-cayenne.glitch.me/

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
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn


## Video Walkthrough (GIF)

This is a lost case.
![](https://cdn.glitch.global/0c9b2b51-8eed-4700-9b49-936f9abba15a/ezgif.com-gif-maker%20(1).gif?v=1648517200149)

This is a win case.
![](https://cdn.glitch.global/0c9b2b51-8eed-4700-9b49-936f9abba15a/ezgif.com-gif-maker%20(2).gif?v=1648517212860)
![](gif3-link-here)
![](gif4-link-here)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

I use https://stackoverflow.com/questions/5836833/create-an-array-with-random-values to help me 
create a random array for pattern each time the player starts the game. I know how to use Math.random but this
command is more succinct and convenient.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

The biggest challenge for me was to write the code for game logic. 
The flow chart was very helpful, and I did understand the logistics of the game. 
However, I still found it’s hard to start writing code for this part. 
These if-else statements seemed easy to implement, but when I tried to figure out the correct orders and conditions, there was much more to consider than I expected. 
I need to check if the gamer’s guess matches the correct pattern and then update each turn for one more clue. 
Probably because I’m not familiar with JS and HTML, I found it’s hard to update the process correctly and end the game when gamers make mistakes. 
To figure this out, I went through all functions I wrote for the game again and tried to find a way to coordinate with them and use them in my game logic function. 
I started with the most straightforward logic in the game that once you make a mistake, you lose the game. 
So that would be my first and foremost if-else condition. Starting from there, I built up more complicated logic like if I succeed, I continue for the next clue. 
Step by step, I sorted the general reasoning out. 
But there’s still something missing that doesn’t update the pattern accordingly. After being stuck on these problems for an hour, I decided to check the given answer. 
Then I realized that I didn’t use the guessCounter correctly for my function. 
That’s why it couldn’t update itself. I then fixed the bug in my if statement, and it worked well.


3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

Other than some technical questions related to languages CSS, HTML, or JavaScript I used in the Prework, which I think I can figure out by myself, I wonder if there could be more interactive features added on the web. 
Usually, a website is used to present something to the user, but I think if the user could modify or edit the existing web content, I might be able to build more interactive web-based games for players. 
I am also wondering how important UI/UX design is in web development. 
Since this pre-work assignment only involves the coding elements and a little color or sound design, I wonder if designing the interface or overall composition of the website is also an essential skill for a web developer.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

I will add additional features for the button, color, and sound. 
I was thinking maybe I could add a piece of music into the pattern and set the order so that when the player succeeds in clicking on the correct pattern, the player will hear the entire piece of music. 
I think I will also add more decorations to the buttons themselves because right now, they are very standard buttons. 
If I have more time, I probably will change the shape or the color or add some photos to the click function so that they will reveal some exciting pictures when the user clicks on them. 
I will probably also add more pages to the website and add a different level of difficulties, so the user could go through them and find it more like a game with multiple levels and layers. 
This might also involve some game designs. I can also make a board to keep track of players’ records in playing this game.



## Interview Recording URL Link

[My 5-minute Interview Recording](https://wustl.zoom.us/rec/share/THVJ5_McIolWdVo3lsfnb3SRI81rvArwkYi9v1Bxe2d45Kkbb5COBt-TDk21_wo5.MCLJ3GR_HloAe_hA?startTime=1648517713000)


## License

    Copyright [Junyi Yao]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.