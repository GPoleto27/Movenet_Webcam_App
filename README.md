# Movenet_Webcam_App
Pose estimation webcam application using Tensorflow's MoveNet model and OpenCV

Tensorflow announced their latest pose detection model, [MoveNet](https://blog.tensorflow.org/2021/05/next-generation-pose-detection-with-movenet-and-tensorflowjs.html)

So, I read the [documentation](https://tfhub.dev/google/movenet/singlepose/thunder/3) and decided to try to implement an application to showcase it's usage and it turned out quite nicely

## Clone the repo
``` git clone https://github.com/GPoleto27/Movenet_Webcam_App.git ```

## Move to repo local directory
``` cd Movenet_Webcam_App ```

## Install dependencies
``` pip install -r requirements ```

## Run
``` python3 movenet.py ```

It will pop up a window showcasing your webcam running the model, rendering the keypoint from the model

You may also edit the code to run it in specific image or video files
