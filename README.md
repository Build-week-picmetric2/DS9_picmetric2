# DS_picmetric2
Data Science repository for picmetric2. PicMetric uses a YOLO v3 Convolutional Neural Network to perform object detection on uploaded images. 

# Components
### Flask_api:
    - Flask API built with Python 3.7
    - Used for connecting front end and back end with the model.
    - Deployed on AWS with pickled Keras-YOLO3 model with serialized weights.

### Picmetric2_models	
    - Keras-YOLO3 pre-trained model built with Python 3.7 
    - Contains model and all supporting functions to build model using omitted weights file.
    - Contains all supporting functions for detected object box formatting.
    - Takes in an image object or URL and returns a series of label predictions and their certainty values.

### picmetric2_notebooks
    - Notebook version of models, functionality testing only.
    - Includes resnet50 model for comparison testing; not deployed.

# Data Science Team
## Machine Learning Engineers (DS9)
- Marilyn Landim Esko
- Todd Patterson Ramirez Gonzalez

## Data Engineers (DS10)
- Christopher Huskey
- Jud Taylor

