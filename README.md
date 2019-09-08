# E01b-Smiles
I have edited year and fullname in the LICENSE file. After editing, I made some changes on coordinates. As a result, I was able to place the smiley face at the center of the window. When I finished placing the face at the center, I edited READMe.ed. I really enjoyed the assignment. 

This exercise involves exploring variables and using Python Arcade. 

You will change several files to complete the assignment. You can find the instructions on Canvas.

If a comment is a single-line in Python, it will be marked by a # sign. If a comment needs more than one line, it will be marked by 3 matching quotations (''' or """). In VS Code, they will appear in a different color. Since the comments will be ignored, it is safe to include any information. 

While you are working on the assignments, please edit the LICENSE file. Replace the [year] with the current year and [fullname] with your full name. Please also edit README.md. Please describe what you have done. 

---

Before you start the assignment, Fork this repository and Clone it your computer. 

Please install Python Arcade before you start. We will be using Python Arcade for the first half of the semester. Next, click on the magnifying glass and search for CMD, or open the Terminal in VS Code and type the following:

*pip install arcade --user* 

pip is for downloading and installing Python packages. We will use a package called arcade. When the command is typed, you will be able to see the components it is installing with corresponding progress bars. 

We can start working when the installation is done.

Please open main1.py. There are some shapes. They are all drawn at (0,0), the bottom-left corner of the window. Use the shapes and draw a smiley face in the center of the window. The small gray dots are catch lights for the eyes. 

The result will look like this (Your result does not have to be as exact as the picture.):

![Smile!](https://github.com/BL-MSCH-C220-F19/E01b-Smiles/blob/master/smile.png) 

When the shapes are placed correctly, please save the file and open main2.py. I only defined coordinates (face_X and face_y), which is the center of the circle. Find out the offsets for the other shapes related to face_x and face_y. Please move all the shapes to the center of the window by using face_x and face_y. When you are done, please save.


In main3.py, there are new coordinates to represent each of the shapes: smile, eye1, eye2, catch1, and catch2. Define each of the coordinates related to face_x and face_y by using what you learned in main.2py. Move the face to the center of the window. You will only have to edit lines 13 through 18. When you are done, please save. 

Please open main4.py. You will be drawing many faces in the window. Draw a grid of overlapping faces by editing lines 20 through 24. When you are done, play with the values on lines 16 and 18. What happens when you play with the values? Please save your changes when you are done. 

When you finish the assignment, save the changes and push them back to GitHub. Submit the URL of your repository on canvas.

Next step is the extra credit. 

main5.py is difficult; however, it allows the smiley face to track mouse movements. Please add a comment to every line describing what is happening. Please save the changes. 

If you are interested to explore Python Arcade further, go to the following link: http://arcade.academy. Some sample projects will be available at [arcade.academy].

---

The grading criteria will be as follows:

* [1 point] Repository contains an appropriate software license
* [1 point] Repository contains a descriptive README.md
* [8] Accomplishes the objective of the exercise

10 points total
