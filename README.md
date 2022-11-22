# Bat-Ball-Tracking-System

<p align='center'>
<img src="https://user-images.githubusercontent.com/74819807/132974658-c488b0b5-f459-4210-9213-2d8316b10d4a.gif">
</p>

## Dataset

The dataset contains -

- train - This dataset contains “Images” folder - which has images containing bat and ball. There is a CSV file “bat_ball.csv” which contains following columns “class (label)” “X axis (Top Left X-coordinate of the image )” “Y Axis (Top Left Y-coordinate of the image)” “width(width of the class (bat or ball))” , “height (height of the class (bat or ball))” , “name (Name of the image)”, “image_width”, “image_height”
- test_videos - Contain videos on which your model needs to be tested
- train data contain images of three different resolutions i.e. 811 images (680, 720), 2 images (640, 678) and 11 images (1080, 1144)

Here are some training set images-

<p align='center'>
<img src="https://github.com/kushaldev75/Bat-Ball-Tracking-System/blob/main/dataset/train/images/U2_4_19.png" width="400" height="420">
<img src="https://github.com/kushaldev75/Bat-Ball-Tracking-System/blob/main/dataset/train/images/U1_22_16.png" width="400" height="420">
</p>

And below are some videos from test set-

<p align='center'>
<img src="https://user-images.githubusercontent.com/74819807/132973112-77503549-4bf0-4be3-a87e-0b21878b26c6.gif" width="400" height="420">
<img src="https://user-images.githubusercontent.com/74819807/132973285-7686af27-1269-42b9-ab63-6e00e593d613.gif" width="400" height="420">
</p>



## Result

Below is the result of Model tracking objects in real time on 7 test_set videos.
<p align='center'>
<img src="https://github.com/kushaldev75/Bat-Ball-Tracking-System/blob/main/results/combinegiftest.gif">
</p>


<p align='center'>
<img src="https://github.com/kushaldev75/Bat-Ball-Tracking-System/blob/main/results/results.png" >
</p>


Below is the Mosiac of some images from the validation set. **On Left**, we have images with ground truth labels whereas **On Right** we have YOLOv5 detection results.


One observation we can make is that in some images model doesn't do well at predicting bat in particular.

<p align='center'>
<img src="https://github.com/kushaldev75/Bat-Ball-Tracking-System/blob/main/results/val_batch1_labels.jpg" width="360" height="400">
&emsp;
&emsp;
<img src="https://github.com/kushaldev75/Bat-Ball-Tracking-System/blob/main/results/val_batch1_pred.jpg" width="360" height="400">
</p>


