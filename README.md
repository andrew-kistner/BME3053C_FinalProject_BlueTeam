# BME3053C_FinalProject_BlueTeam
Part 1
1. First download the shareemail folder
2. Make sure the folder named Testing.Zip is extracted so that Matlab can read the images inside
3. Open "codetrainimage.mlx
4. Make sure that all the folders and subfolders are loaded into the path
5. Run the code. It will take around 5-6 minutes to load the trained network.
6. After it loads it should be good by itself and will show you the accuracy as a fraction in decimal form.
Hint
Make sure that the trained network in the .mat file is in the workspace when you try to load it. When you load neuralnettumor, it should load as trained_network1 in the workspace and it is renamed into net later on.

Part 2

After Part 1 works, load "ApplicationTreatment.mlx"
Note: Make sure to do this after you run the code in part 1 since it uses the variables already loaded into the workspace to save on time.

The steps should be in the file as comments but basically you will need to make sure that the ApplicationGrader folder is in the path. This folder has 4 images. One image per class. You will need to add the image based on what you want to run. If you want to run the pituitary, write "pituitary.jpg". Note: The pituitary is loaded as the basis. You will need to change the image name to whatever 4 cases you want to run. The other 3 cases you can do are "meningioma.jpg", "glioma.jpg", and "notumor.jpg".

The 3 "treatments" should be in the folder as .pngs and they are displayed when the classification matches the label. The treatment groups are no cancer, pituitary, glioma, and menningioma. Note, the no cancer treatment is simply a printed statement saying that no treatment is necessary.

Then when you run the code, It will ask you what time of tumor it is. You will need to write: "pituitary_tumor", "no_tumor", "meningioma_tumor", or "glioma_tumor" exactly like that so it matches the output labels. 

Then there is no further input required and you should either get a message that it is correctly classified and then the treatment, or incorectly classified, and to please choose another image.

Thank you for your time.
