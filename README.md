# hw3

• What code draws the blades of grass?
    stroke(random(60, 70), 100, 90);
    line(x, height-10, x + random(-10, 10), height-10-random(h));
  
• What code makes the "lawnmower" come by? How often does it come by?
    if (random() > 0.999); Random

• What's the point of the h variable?
    Changing the height of the grass, and the length of the grass should be after mowing.
    
• What do the three numerical arguments of colorMode do?
    colorMode(mode, max1, max2, max3, [maxA])
    max1	Number: range for the red or hue depending on the current color mode
    max2	Number: range for the green or saturation depending on the current color mode
    max3	Number: range for the blue or brightness/lighntess depending on the current color mode
    maxA	Number: range for the alpha
    
• What does the -10 do in the second and fourth arguments of the line function, height-10-random(h)? Why is it there?
    The grass will start from height y=190. In order to create randomness of the grass height, you minus random hight, which is 10.

• What's the point of an object?
    The variables wouldn't float around in the code. It will help you organize better coding.
    An object is a collection of related data and/or functionality (which usually consists of several variables and functions — which are     called properties and methods when they are inside objects.)

• What's an example of a range you might use for the map function?
       Range of color value/hue, range of height/width or position. 
       
• What line of code would give me a random year in the last century?
    var x = random (1918,2018);
