# HaloWorld  
*World rhythms for a global hit*  
[https://haloworld.netlify.com/](https://haloworld.netlify.com/)

### What I learned with this project:  
  - Data attributes & keyCodes;  
  - How to deal with audio files in JS (audio.play(), audio.pause(), volume control);  
  - Input type range;  
  - Take over code started by someone else (it's quite interesting);  
  - Clap when samai is playing is not [as straightforward as you might think](https://daturaonline.com/rhythm-breakdown-samai#)  
  
### Main Challenge:  
  - When I first added pause, I was shown how to start/stop audio to a  single audio track using `let playing = false` at the beggining 
  of my script. After I decided to transform my project into something else than the original proposition, I needed to add pause to each 
  track and leaving this let as is was not helpful. It took me a while to find a solution, but I finally ended up with a functional array 
  of booleans that updates the assigned boolean to false/true everytime the relevant key is pressed.
  
### What I added to the [original idea from JavaScript30](https://github.com/wesbos/JavaScript30/tree/master/01%20-%20JavaScript%20Drum%20Kit):  
- Adition and control of a main track to the drum sounds;
- Play/Pause and volume control to each key;

  
### What I would do if I had more time:  
- Replace "african waltz" with kuduro or kizomba (as african waltz doesn't seem to be thing);  
- Replace "hard rock" for another asian rhythm;  
- Add a box with brief info about the rhythm selected by user;
  
  
*Thanks to Chris Meah for presenting us to JavaScript 30 and for guidance when I got stuck :)*   
