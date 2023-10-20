Development of this project has stopped!

## Radio Wave Hybrid Glitch Effect.  

## Radio Wave Hybrid Glitch Effect  is an interactive file made within P5 

## Description 
The name Radio Hybrid Glitch sounds very complex. However, it combines the theme of radio wave frequencies coupled with a glitch effect. As we know you cannot see radio waves and how they travel but thanks to digital media we are able to perceive how they travel. For example, we know radio waves contain information and travel from point A to point B. But what happens when these radio wave frequencies intersect? This is where user interaction comes into play as users will be able to do all types of things. For example, moving the mouse and controlling all 3 radio wave frequencies. You can reduce the wave to its simplest form. You can make the wave consume the entire screen and create a 90's television screen. You can even change the colour of the background by pressing the mouse key down over the program. But the rest I leave to you to explore and see what you can create. 

## Installation

If you simply want to view the glitch and play around with it the code is. https://editor.p5js.org/ZeusMXIV/full/yqNtJR3hB. I designed this program to be used in games and I am open to collaboration. Imagine if this was in a horror game and the user had the chance to play around with this glitch. It would strike fear into any gamer's heart. A worse thing a gamer fears is crashing and potentially losing their progress. To edit or add to my code https://editor.p5js.org/ZeusMXIV/sketches/yqNtJR3hB. 




## Usage
In case you alter something and something goes wrong you can come back to this and copy and paste the code. 

function setup() {
  createCanvas(600, 600);
  frameRate(60);

}

function draw() {
  if (mouseIsPressed) {
    background(random (0,255),random (0,255),random (0,255));
    frameRate(24);
  }
  else {
      background(220, 204, 0);    

  }
  fill(255);
  strokeWeight(4);
  stroke(255);


  for (let i = 0; i < 600; i++) {
    let r = random(-50, 50);
    let col = random(r, 255);

  stroke(col*r, col, col);
    line(25 + r, i, 150 + r, i);
    line(mouseX + r, i, 350 + r, i);
    line(425 + r, i, mouseY + r, i); 
    // line(mouseX - r, i, -mouseX - r, i);
  
   if(mouseIsPressed) {
    r = 600;
    line(0, 600, 0, 600);
    }
  }
  

}

What if I have never used P5 before and I want to learn? Visit The Coding Train at: https://thecodingtrain.com/tracks/code-programming-with-p5-js

## Contributing

I am happy for you to make any alterations necessary. I look forward to seeing any changes you're going to make. I have tested this amongst my peers but I also want to clarify that this is my first time using P5. Bugs and glitches shouldn't be a problem as it has been tested multiple times and on different occasions so it should run smoothly.


## License

[MIT](https://choosealicense.com/licenses/mit/)
