# Pre-work - *Jasmine's Light and Sound Game*

**Jasmine's Light and Sound Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Jasmine Adelberg**

Time spent: **3** hours spent in total

Link to project: https://marked-humane-floor.glitch.me
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
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn



## Video Walkthrough (GIF)


![](https://i.imgur.com/TWy19MW.gif)

![](https://i.imgur.com/2pzCnrE.gif)


## Reflection Questions
**1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here.**
1) https://www.tutorialspoint.com/html/html_overview.htm - I’ve never used html before ive only worked with java and python. So before I began the program I looked through this website to learn and understand the basics and syntax before beginning the program. I did this so I can understand what I'm doing and why I'm writing certain things.
2)Looked at slides and past projects from the web programming course at my college. Not sharing links because I don’t have permission from the professor.

**2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)**
Overall, a challenge that I encountered when creating this submission was learning  HTML, CSS and JavaScript. I've never worked with these languages before and I have never had to do any web development.  The prework directions were really helpful and gave most of the code. But I wanted to understand the syntax and what I was doing and not just copy and paste the code. So to overcome my lack of knowledge with web development, I used the resources that I listed above to learn a little bit to the point that I could figure out what to code.  I would compare and correct it by looking at the code provided. Another challenge that I encountered was when I was testing my program, I was having issues with the noise. The specific issue was that the sound would get stuck and keep on playing. While I had a hard time figuring out why it was not stopping, it allowed me to use the debugger and really look at my code to find the error. It tested me to see if I knew what each line of code was doing and why it was there. In the end, It was a simple fix. I forgot this line of code: setTimeout(function(){stopTone() },len). 

**3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words)**
Some questions I have about web development after completing my submission is: 1) What code editor will we be using for this internship specifically? Will we continue using glitch? 2) What are the style guidelines (comments)? For my classes so far, we need to add docstrings and in-line comments a specific way. I was wondering if there is a proper way to comment for web development. 3) What are the types/specializations of web developers and how are they different? 4) With the rise of people using their phones for web searching, What are the key ways to make a website mobile friendly?

**4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)**
    If I had a few more hours to work I would complete all the other optional features that I didn’t complete and submit. Then if I had a lot more time,  I would’ve loved to figure out and implement a high score list. Before the game began, I would add an input feature to collect the name and store it, to later add to the high score list. The name and time would be added if the player won. The list would appear at the end if the player won or lost. I love games with this feature because I'm very competitive!



## Interview Recording URL Link

https://arizona.zoom.us/rec/share/aEIdZ6auXJDxHz5z0FGDjysvVshhD_Lburik2GkO3My-IStCk1xKHkE3Gv72L8Ak.RfY6wvpN1TNPaDIS?startTime=1648509100000


## License

    Copyright Jasmine Adelberg

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.