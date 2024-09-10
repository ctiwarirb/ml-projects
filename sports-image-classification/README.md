The dataset is from Kaggle
https://www.kaggle.com/datasets/gpiosenka/sports-classification/code


Prepare Dataset
Datashould should be organized in subfolders for training, validation and testing e.g. 

dataset/
    train/
        class1/
        class2/
    valid/
        class1/
        class2/
    test/
        class1/
        class2/


Steps Involved
1. Image Processing: - Rescale the images to a common size e.g. 224x224 or 255x255.
2. Normalize pixel values to be in range [0,1] or [-1,1].
3. ImageDataGenerator for loading/augmenting images. 
3. Build the CNN model. 
4. Evaluate the model. 
5. Make predictions. 
6. Save the model.
7. Visualize performace

