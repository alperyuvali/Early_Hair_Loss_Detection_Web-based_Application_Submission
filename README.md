# Early_Hair_Loss_Detection_Web-based_Application_Submission
# Project Submission

This repository contains my project submission.

The complete project file is available in the Releases section as a ZIP file.

## File

- project-full.zip

## Note

Please download the ZIP file from the latest release.

##How to use
1. Download all project files from the GitHub repository.
2. Upload the downloaded project files to Google Drive.
3. Open Google Drive and check that all project folders and files are inside the uploaded folder except the notebooks.
4. Check that the dataset folder is also uploaded correctly.
5. Open the dataset folder and make sure it contains the two class folders:
bald
notbald
6. Check that both class folders contain image files.
7. Open Google Colab.
8. Make sure the model file is available in the project folder:
models/final_model.keras
9. Make sure the class names file is available:
models/class_names.json
10. Open the project notebooks from the Google Drive.
11. Open 03_app notebook on Google Colab: 03_app.ipynb
12. Run 03_app.ipynb in Google Colab.
13. Mount Google Drive when the notebook asks for permission.
14. Check that the notebook path points to the correct Google Drive project folder.
15. Run all cells in 03_app.ipynb.
16. Wait until the Flask web application starts.
17. Open the generated web application link.
18. Upload a valid scalp image.
19. Click Analyse.
20. Check that the result page opens successfully.
21. Confirm that the page displays the predicted class, hair loss probability, and confidence score.
22. Check that the uploaded image is processed only for prediction and is not permanently saved.
