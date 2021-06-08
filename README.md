MACHINE LEARNING: CLASSIFY IMAGES OF COLON CANCER

## :pencil: BINARY CLASSIFIER

Binary class classifier is developed to classify histopathological images of colon cells determining if a given cell image contains cancer cells or not ('isCancerous'). 

"isCancerous_Classification.pynb" notebook consists of the code snippets related to :

(1) Exploratory Data Analysis : To identify the distribution of images based on whether they are cancerous or not and find relations between positive and negative samples based on their mean brightness and rgb values.

(2) Model Development : Multiple models were developed with different architectures both on the patch images and stain normalized images and certain performance metrics were used to differentiate such models based on how correctly cancerous and non cancerous cells are identified. All the models were saved in "models_isCancerous" and the best fit model was further chosen for transfer learning.

(3) Transfer Learning : The best fit model used for ultimate judgement was used as a medium to help the new model learn such that cell types can be classified correctly. Apart from that fine tuning was done after the feature extraction process such that the model can act as a generic model based on the spatial hierarchy of features learned by our pre trained model.


## :pencil: MULTI CLASS CLASSIFIER

Multi class classifier is developed to classify histopathological images of colon cells based on the various cell types namely - "Fibroblast", "Inflammatory", "Epithelial" or "Others".

"CellTypes_Classification.ipynb" notebook consists of the code related to :

(1) Exploratory Data Analysis : To identify the distribution of images based on each cell types and find relations between different cell types based on their mean brightness and rgb values.

(2) Model Development : Multiple models were developed with different architectures both on the patch images and stain normalized images and certain performance metrics were used to differentiate between them. For the ultimate judgement, the best fit model was taken based on certain performance metrics and training time.


## :pencil: DATASETS

Datasets for the above project can be found in "Image_classification_data" directory. The given directory consists of :

(1) Patched Images : "Image_classification_data/patch_images"

(2) Stained Images : "Image_classification_data/transformed_images"

(3) Main Dataset : "Image_classification_data/data_labels_mainData.csv"

(4) Extra Dataset : "Image_classification_data/data_labels_extraData.csv"


## :pencil: CONTRIBUTION

(1) Prabhav Mohit Mehra
