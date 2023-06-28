# Multi-modal Machine Learning for Vehicle Rating Predictions using Image, Text, and Parametric Data

We propose a multi-modal learning model for more comprehensive and accurate vehicle rating predictions. Specifically, the model simultaneously learns features from the parametric specifications, text descriptions, and images of vehicles to predict five vehicle rating scores, including the total score, critics score, performance score, safety score, and interior score.

The paper submitted to IDETC/CIE2023, the International Design Engineering Technical Conferences & Computers and Information in Engineering Conference, has been accepted. 

The arXiv version of the paper can be accessed at the following link: https://arxiv.org/abs/2305.15218

You can explore our website page at http://decode.mit.edu/projects/vehicleratings/ for more information.


## Data

The dataset consists of parametric specifications, text descriptions, and images of vehicles. We will soon be uploading the dataset for access.

## Using the code and trained models

As our work was carried out on Google Colab, we highly recommend running all the codes and tests there. You can conveniently access the Google Colab page at xxx.

### Setting up the workspace

To effectively utilize Colab Notebook, follow these steps:

1. Begin by creating an encompassing folder that will house the code, data, and model weights. Let's refer to this folder as "Vehicle Rating Prediction".

2. Within the "Vehicle Rating Prediction" folder, upload all the necessary code files, as well as the parametric and text data files.

3. In the same "Vehicle Rating Prediction" folder, create two sub-folders: "new_images_with_folder" for storing exterior images, and "new_interior_images_with_folder" for storing interior images.

4. Additionally, establish a sub-folder named "model weight" within the "Vehicle Rating Prediction" folder. This sub-folder will store the results of both the unimodal and multi-modal models.

5. Lastly, generate a sub-folder called "SHAP" within the "Vehicle Rating Prediction" folder. Inside the "SHAP" folder, create three additional sub-folders: "SHAP_Image", "SHAP_Parametric", and "SHAP_Text". These sub-folders will be used to store the results of the model interpretability analysis using SHAP.

By following these instructions, you will ensure the organized storage of code, data, model weights, and interpretability results within the Colab Notebook environment.

### Training new models

To train new unimodal models, simply execute the code within the following files: xxx, xxx, and xxx.

Once you have obtained satisfactory results and wish to train new multi-modal machine learning models, follow these steps:

1. Start by utilizing the "Get Predictions from Trained Model" file to obtain score predictions from the trained unimodal models.

2. Next, employ the "Get Linear Regression Weights" file to acquire the initial setting weights for training the multi-modal learning model.

3. Finally, utilize the "MML_Model" file to train the multi-modal learning models.

By following these steps, you can effectively train both unimodal and multi-modal machine learning models based on your specific requirements.

### SHAP analysis

%The relative code is provided in the [EvaluateCompressor.ipynb notebook](code/EvaluateCompressor.ipynb).

### Model Weights

To accommodate the extensive memory requirements of our models, we have stored the corresponding model weights on Google Drive. You can access the relevant model weights by visiting the following URL: [model weights](https://drive.google.com/drive/folders/1rPnwaib5kEDgx0ThQLfJgNYx8qKuibgC?usp=sharing).

## Citation

If you use the dataset, code or model, you can cite our publication:

Su, Hanqi, Binyang Song, and Faez Ahmed. "Multi-modal Machine Learning for Vehicle Rating Predictions Using Image, Text, and Parametric Data." arXiv preprint arXiv:2305.15218 (2023).
