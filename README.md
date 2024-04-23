# 10.3.9-using-II



```

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
  // dis = dist(x1,y1,x2,y2)

  // change into an oval(aka. ellipse) if above/bellow these lines
  line(0,y+50,width,y+50) // bottom line?
  line(0,y-50,width,y-50) // top line?

  if(mouseY>y+50  || mouseY<y-50){
    ov=200
  }else{
    ov=100
  }
  // set up an if statement that uses or || to change into an oval if above/below these lines
  ellipse(x, y,ov, 100 ); 


//text(dist(200,200,mouseX,mouseY),100,100)// do something to the oval if you mouse is inside of the circle. Dist() measures distance from the point 1 (center of circle) to point 2 (mouse))
  // if your inside of the circle do SOMETHING 
  
  //Set up an if statement that uses and && to change the scolour of the circle if it is inside of the lines

}
}
```
