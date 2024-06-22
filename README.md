## Crop or Weed Detection using Roboflow
- Download the dataset from Kaggle using the command: kaggle datasets download -d ravirajsinh45/crop-and-weed-detection-data-with-bounding-boxes.
- Create a new dataset using the Roboflow computer vision tools.
- Roboflow takes images and labels as input.
- Roboflow performs data preprocessing and augmentation, and creates a new dataset with YOLO model weights and data.
- Import the dataset using the Roboflow API key and import the YOLOv8 algorithm through Ultralytics.
- Train the YOLOv8 model using data.yaml and training data.
- Test the model using test and validation data.
- Predict the test images with bounding boxes and class names.
### Note:

- All implementation is done in Google Colab. I use session storage for data location.
- A 'runs' directory is created when the YOLO model is performing.
