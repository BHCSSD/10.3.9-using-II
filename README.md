# 10.3.9-using-II



```javaScript
let ov = 100
let dis = 0
function setup() {
  createCanvas(400, 400);
  background(255);
}


function draw() {
  background(220);
  let x = width / 2;
  let y = height / 2;

//Step 1: change the circle into an oval(aka. ellipse) if above/bellow these lines
//set up an if statement that uses or || to change into an oval if above/below these lines
  line(0,y+50,width,y+50) // bottom line
  line(0,y-50,width,y-50) // top line


  ellipse(x, y,ov, 100 ); 

//Step 2: dist() is a function that measures the distance from point 1 (center of circle) to point 2 (mouse)). This is how we can do hitboxes with circles.  dist(x1,y1,x2,y2)
//Check to see if your mouse is inside of the circle. If your mouse is inside of the circle Change some attribute of the circle.

//Step 3: Set up an if statement that uses and && to change the color of the circle if it is inside of the lines but not inside of the circle. 

}

```
