var position = 20;
var speed = 3;

draw = function() {
      
    background(255, 255, 255);
    fill(0, 255, 68); // start color
      if (mouseIsPressed && mouseY<=200 && mouseY>=0 ){
         
          fill(222, 49, 222); // start color
   

     }
     
    rect(0, 0, 400, 200);  // the button
    // The button text
    fill(0, 0, 0);
    textSize(30);
    text("Press me!", 145, 115);
    fill(255, 0, 0);
     position = position + speed;
     
   
    
    rect(mouseX, mouseY, 30, 30); 
};
