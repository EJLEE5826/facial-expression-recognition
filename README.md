# facial-expression-recognition
Facial expression recognition on FER+ dataset using CNN(VGG16, EfficientNet)


### Training data
We provide a simple script generate_training_data.py in python that takes fer2013.csv and fer2013new.csv as inputs, merge both CSV files and export all the images into a png files for the trainer to process.

```
python generate_training_data.py -d <dataset base folder> -fer <fer2013.csv path> -ferplus <fer2013new.csv path>
```
