let posX;
let posY;
function setup() {
	createCanvas(windowWidth, windowHeight);
	// put setup code here
}

function draw() {
 posX = width/2;
 posY = height/2;
	noFill();
	background(255,105,180);
 stroke(255);
 strokeWeight(2);
 circle(posX,posY,height/2);
circle(posX- height/3/4,posY- height/3/4, height/12);
circle(posX+ height/3/4,posY - height/3/4, height/12);
circle(posX+ height/12/20,posY - height/12/20, height/20);
circle(posX,posY,height/2);
circle(posX+ height/14/10,posY - height/14/10, height/10);
circle(posX, posY+100,70,50);
circle(posX, posY +280,250,60);
line(posX- 80, posY+80);



}
