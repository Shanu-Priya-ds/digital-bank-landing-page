## Challenges you encountered during the project.
 - I found very difficult to put the hero image to be overlayed on exact place as the design
 - Articles section cards weren't not alligned as per the design, faced challenge to give proper gap between the card. If i give margin, it moved one of the card  to the next row.
  - For nav section, initially added a code with flex it worked for desktop, for mobile I had to change the layout to work.


## Your approach to solving these challenges.
    - Learnt more about the absolute and relative position, by doing a sample program for the image overlay in a seperate html file. Then applied the concept to the project. To place the image not to overlap on the navbar, used the transform method in CSS, which helped to arrive with the proper alignment as possibily close to the given design.
    - Iniitally tried to use the glutter proeprty to provide gap between the cards. But, it didn't work. The issue was each card content was wrappend in a container, have used the same container for grid column. Seperating the card container from the column container solved the issue.
    - Updated the navigation section with different classes for two device breakpoints, by using the different bootstrap classes.


## Improvements you would make if given more time.
  IF I get more time, 
  - will fix the image on hero section to cover the entire viewport on right side, currently it fits into the container
  - will fix the hero section image cropping for mobile device, now it is not exactly same as the design given.