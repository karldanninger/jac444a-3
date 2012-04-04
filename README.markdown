# JAC444: Assignment 2 

After creating the JAR files, I've imported the JAR files into Eclipse again. I've checked that there's no compilation error. I will lose 50% if that's not the case.

Instructions:


Proposal for ASSIGNMENT2 :
Feature Set:

1. Be able to plot a location based on the map GUI & give the coordinates relative to HOW/WHERE you initially rendered the map.
  Bonus: Save location???
  
2. Introduce a list of clicked locations Bunus: RE-render the map to the specific location chosen.
  - maybe include a textfile with all locations saved that the application can use to plot recent locations

If time permits:

3. Render multiple locations in one instance to flip between (from the locations saved from features 1 & 2)

# Separate Log Files :

[Karl's Log](./jac444a-3/blob/master/karl-log) ~ [Ronito's Log](./jac444a-3/blob/master/ronito-log)

# Main CHANGELOG :

March 18 ____________________
 - Initial Commits
 - Studied Code
 - Tested multiple methods
 
March 20 ____________________
-Was added as a collaborator with Karl's gitHub
-This allows us to work within one repo

March 24 ____________________
-Commenting was added to the file

March 25 ____________________
-More commenting was added to the file

March 30 ____________________
-Combo box was added and coding was done for it

March 31 ____________________
-GUI was updated and started coding within the mouseListener

April 1  ____________________
-Finalized logic for combo box
-Added instructions in the JTextArea
-Got coordinates of the mouse and integrated it with the coordinates given

April 2  ____________________
-Did coding for 4 quadrants of the map
-Worked on zoom anon. inner class 

April 3  ____________________
-Finalized the coding for each quadrant
-Finalized zoom anon. inner class with resetters 

Split up main features ***

RJ will build the main logic on how to plot new points on the map.  Splitting the
map into 4 quadrants to help plotting new locations relative to the location used.

Karl will take care of saving the plotted locations & to append them to a file.
This file will then be used to populate a list of previous saved locations that
the user can use to render previous clicks.

