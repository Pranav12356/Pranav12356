
	
// position of the car
var x = 10;
    
draw = function myFunction() {
    
  
    background(151, 244, 247);
    
    
    fill(255, 0, 115);
    rect(x, 200, 100, 20);
    rect(x + 15, 178, 70, 40);
    
    // draw the wheels
    fill(77, 66, 66);
    ellipse(x + 25, 221, 24, 24);
    ellipse(x + 75, 221, 24, 24);
    
    x = x + 10;
};
 
