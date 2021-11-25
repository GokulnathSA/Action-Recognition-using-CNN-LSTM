# Action-Recognition-using-CNN-LSTM
- Activity recognition is the problem of predicting the movement of a person or object based on some sensor data (accelerometer in a smartphone), Video footage, etc.
- It is formulated as a binary (or multiclass) classification problem.
- It is widely used in    
  1. Smart survivalence
  2. Video searching/retrival
  3. Intelligent robots
- The goal of my model is to output the action performed for a partical video apploaded.
- Materials used
  - [UCF 101](https://www.crcv.ucf.edu/data/UCF101.php) dataset is used for this study.
  - UCF101 is an action recognition data set of realistic action videos, collected from YouTube, having 101 action categories.
  - 5 categories are used for this study which are: Apply eye make up, Apply lip stick, Archery, Baby crying, balance beam. 
  - The dataset has videos of 25 individuals performing each activity.
  - Used 20 for training and 5 for testing.
- Model Summary
  1. Frame extraction and dataset preparation for Training CNN.
  2. Training CNN for activity classification.
  3. Feature extraction using CNN.
  4. Training LSTM using features extracted from CNN.
- Results
  | |Accuracy of CNN| Accurucy of LSTM|
  |---|--- |--- |
  |1 |74 |68 |
  |2 | 82 | 74 |
- Accuracy of the overall model can be improved by using end-end fine tuning of the CNN model or using a bigger Resnet model. 

  


 
