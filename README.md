# HaloWorld

### World rhythms for a global hit

### See live in [https://haloworld.netlify.com/](https://haloworld.netlify.com/)

#### Project Rules

No use of JS libraries or frameworks: pure Vanilla.

#### What I learned with this project:

-   Data attributes & keyCodes;
-   How to deal with audio files in JS (audio.play(), audio.pause(), volume control);
-   Input type range;
-   Take over code started by someone else (it's more interesting thank I thought);
-   Fonts from Google Fonts can look quite different in Chrome and Firefox;
-   Use classList;
-   Clap when samai is playing is not [as straightforward as you might think](https://daturaonline.com/rhythm-breakdown-samai#)!

#### Main Challenge:

-   When I first added pause, I was shown how to start/stop audio to a single audio track using `let playing = false` at the beggining
    of my script. After I decided to transform my project into something else than the original proposition, I needed to add pause to each
    track and leaving this let as is was not helpful. It took me a while to find an elegant solution, tbh. Eventually I've gone with an array of booleans that updates the assigned value to false/true when the relevant key is pressed.

#### What I added to the [original idea from JavaScript30](https://github.com/wesbos/JavaScript30/tree/master/01%20-%20JavaScript%20Drum%20Kit):

-   Adition and control of a main track to the drum sounds;
-   Play/Pause and volume control to each key;
-   Background change on keypress;

#### What I would do if I had more time:

-   Refactor my code;
-   Make it mobile friendly (also accept touch instead of key presses only);
-   Replace "african waltz" with kuduro or kizomba (as african waltz doesn't seem to be thing);
-   Replace "hard rock" for an asian rhythm;
-   Add a box with brief info about the rhythm selected by user;

_Thanks to Chris Meah for presenting us to JavaScript 30 and for guidance when I got stuck :)_
