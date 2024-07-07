# Video_Action_Recognition
This project focuses on recognizing human actions in video sequences. The current model is trained to distinguish between two actions: "Stand Up" and "Sit Down".

## Description

The notebook implements a video action recognition model using deep learning techniques. The model is trained on a dataset consisting of video clips labeled with two classes: "Stand Up" and "Sit Down". The objective is to accurately identify these actions in new video sequences.

## Sample Videos

### Stand Up

<video width="320" height="240" controls>
  <source src="dataset_action_split\test\Stand up\video_85.avi" type="video/avi">
  Your browser does not support the video tag.
</video>

### Sit Down

<video width="320" height="240" controls>
  <source src="dataset_action_split\test\Sit down\video_7.avi" type="video/avi">
  Your browser does not support the video tag.
</video>

## How to Use

1. **Data Preparation**: Ensure your video dataset is organized and labeled correctly.
2. **Training**: Run the provided notebook to train the model on your dataset.
3. **Inference**: Use the trained model to classify actions in new video sequences.

## Requirements

- Python
- OpenCV
- TensorFlow
- Other necessary libraries (see requirements.txt)

## Running the Notebook

1. Clone the repository.
2. Install the required libraries.
3. Open the Jupyter notebook and run the cells sequentially.

