# Making a Mug in Blender

I am graduating this spring, and with my graduation I will lose access to several applications that are critical for game development. One of those is Maya, a 3D modeling software that is the industry standard for modeling, animation, and rendering. However, there is a free software that does all of this, Blender. Because I still want to keep my 3d modeling skills sharp, I decided to learn blender. As a disclaimer, I followed a single blender tutorial several months ago, but have not touched it since, so I am somewhat familiar with the most basic of processes in blender. 

My goal with this exercise was to create a simple mug. While blender is similar to Maya, it has some major differences. Namely, the layout and hotkeys, which is something I had great difficulty with. 

I started with creating a cylinder by right clicking on the create primitive button and selecting the cylinder. Then I chose how wide and tall the cylinder would be. This process was quite easy because the creation button was very clear. I also inferred that there was more options to create primitives as that was afforded by the small gray triangle in the corner of the box. 


<img width="1150" height="609" alt="Screenshot 2026-05-13 102545" src="https://github.com/user-attachments/assets/bca4ebb5-a4dc-45cf-aec2-068d3447f3ba" />


Then, I swapped from object mode to edit mode so that I could edit the pieces of the cylinder. After swapping to edit mode, I also had to select the faces mode in the corner so that I would be able to edit the faces of the object instead of the default of vertexes


<img width="1150" height="609" alt="Screenshot 2026-05-13 102706" src="https://github.com/user-attachments/assets/ca945993-14aa-4dbc-96c3-744bfe7d5575" />

<img width="1150" height="609" alt="Screenshot 2026-05-13 102706" src="https://github.com/user-attachments/assets/d668c33a-f06a-4d63-ac8d-d1ce278cc565" />


To start molding the cylinder into a mug, I selected the topmost face and searched on the left side of the screen for a tool to help me with that. In Maya, this is usually done by extruding the face inwards, but in blender, that has to be done specifically with the inset face tool. It was extremely easy to find as the icon for the tool looked like the action that I would take. 


<img width="1150" height="609" alt="Screenshot 2026-05-13 102811" src="https://github.com/user-attachments/assets/c3ea2076-5889-4efb-a258-bc1bb1e0b137" />


I then searched for the extrude tool, which was also easy to find. It was near the top of the toolbar because of how frequently it is used. This makes blender more efficient as it prevents you from spending too much time scrolling or searching through menus to do a common action. I then dragged the handle down with the correct face selected and moved it to an appropriate position


<img width="1150" height="609" alt="Screenshot 2026-05-13 102834" src="https://github.com/user-attachments/assets/39104e0f-09fe-4a36-8362-59d6c91eeb8b" />


The next task that I wanted to do was to create a handle for the mug. To do this I wanted to add some horizontal cuts to the model. I looked for a tool that was similar to the insert edge loop tool in Maya. and I found the loop cut tool. Again, the icon for it clearly communicated the function of the tool which was helpful. However, I found that the tool could only insert loops at set points on the model. I tried holding down the control and shift keys to see if that would disable the snapping of the tool but that didn’t work; unfortunately, it did not fit my mental model of the tool. So I ended up adding cuts until I felt it was adequate. 


<img width="1150" height="609" alt="Screenshot 2026-05-13 102946" src="https://github.com/user-attachments/assets/a8358a72-df5e-4f0d-9697-2a0100d55e75" />


I then selected two faces where the handle would connect to the mug and extruded them.


<img width="1150" height="609" alt="Screenshot 2026-05-13 103212" src="https://github.com/user-attachments/assets/a4969030-aa5b-4636-b54e-8c2d51480b89" />


This is where I ran into difficulties, I was unsure on how to connect the two pieces of the handles. I first tried to rotate the end faces to 45 degree angles so I could bridge the faces. This was not possible because the faces I selected were slightly off from going in either the x or y direction. I then decided to bridge the faces and move it outwards. This gave me a nice handle shape that I could edit.


<img width="1150" height="609" alt="Screenshot 2026-05-13 103644" src="https://github.com/user-attachments/assets/ac18cf95-2ce5-40fb-acfb-d52fc0752566" />


After I created the handle shape, I wanted to select the corner edge of the handle so that I could bevel it into a rounder shape. In Maya, you can double click quickly on an edge to select the edge loop it is a part of. Blender does not let you do this, you have to open the select menu, navigate to the loops section, and click on edge loops. I found this process to be not satisfying and inefficient. 


<img width="1150" height="609" alt="Screenshot 2026-05-13 104158" src="https://github.com/user-attachments/assets/970dd949-c1b4-4026-ad29-4c9fb17dfd6c" />


After selecting the edge loop, I wanted to bevel the edge to round it out. However, when I tried to do this, nothing happened! There was no feedback as to what was wrong and I was stumped. What had happened was I pressed F when the edges were selected, this created geometry inside of the model that I only found after a few minutes of searching. I had pressed the F key because I wanted to put my current selection in focus, which is a feature of Maya. To focus on your selection, you need to press the ` key then press the view selected in the menu that popped up. 


<img width="1150" height="609" alt="Screenshot 2026-05-13 104849" src="https://github.com/user-attachments/assets/4d382686-bdcc-406e-bf22-d64f48407092" />


After deleting the extra faces, I was then able to select the edges and bevel them as I wanted. 


<img width="1150" height="609" alt="Screenshot 2026-05-13 105300" src="https://github.com/user-attachments/assets/23fafb52-1fc4-4bbe-91c1-30b5da16d7f9" />

<img width="1150" height="609" alt="Screenshot 2026-05-13 105515" src="https://github.com/user-attachments/assets/415cbf67-2e35-4867-a733-f68adf1a8064" />



Overall I feel that blender is a very well designed piece of software. While my mental model of 3D modeling software differs from how Blender functions, it still uses proper iconography to assist the user in the creation of 3D Models. 

