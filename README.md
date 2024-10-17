# js-kawasilva15

function setup() {
  createCanvas(800, 800);
  background("BLACK")
}

function draw() {
  stroke("green");
  fill("purple");
  
  
  if (mouseIsPressed) {
    rect(mouseX, mouseY, 10, 10)
  }
}

