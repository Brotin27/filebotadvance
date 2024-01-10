# Advance File Bot

# Animated README

Here is an animated README file using ASCII art.

```js
const frames = [
  `
  +---------------------------------------+
  |       **  Animated README  **        |
  +---------------------------------------+
  
  This README file has some simple animations using ASCII art!
  
  `,

  `
  +---------------------------------------+
  |      ***  Animated README  ***       |
  +---------------------------------------+
  
  This README file has some simple animations using ASCII art!
  
    \__,__/
    
     
  `,

  `
  +---------------------------------------+ 
  |       **  Animated README  **        |
  +---------------------------------------+
  
  This README file has some simple animations using ASCII art!
  
     _  
    / _) 
    
  ` 
]

let counter = 0;

setInterval(() => {
  
  // Clear the console
  console.clear();

  // Print the current frame
  console.log(frames[counter]);

  // Increment or reset the counter
  counter++;
  if (counter >= frames.length) {
    counter = 0; 
  }

}, 500);

