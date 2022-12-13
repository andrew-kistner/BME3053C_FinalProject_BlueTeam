# BME3053C_FinalProject_BlueTeam
First download the shareemail folder
Make sure that the trained network in the .mat file is in the workspace when you try to load it. The network layers are added so you can see the breakdown of the deep network layers but you should not need it to run the code. The 4 "treatment" should be in the folder as .pngs and they are displayed when the classification matches the label. 

To run just add the image data store by name and the rest of the code should be able to work with that. You do have to edit the for loop with however many files you want to run from the folder. 
The if loop first sees if the classification matches the label. If it does, it will provide the treatment for that diagnosis. If it does not match then, you will get a message saying that "This image was misclassified. Please send for further testing."
