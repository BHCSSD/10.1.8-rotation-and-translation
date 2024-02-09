# 10.1.8-rotation-and-translation
S&T

```
function setup() {
  createCanvas(800, 800);
  angleMode(DEGREES);
  rectMode(CENTER);
}
function draw() {
  background(220);
    rectMode(CENTER);
    //move the origin point

    rotate(45);             
    //draw at new origin point

    resetMatrix();          //sets origin and rotate back to normal

    rectMode(CORNER);
    rect(400, 400, 100, 100);

}
function mousePressed() { 
print("MouseX: " + mouseX + "     MouseY: " + mouseY);
} //end mousePressed

```
