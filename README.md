# Football Player Analysis Project

## Overview
This project aims to detect and track football players, referees, and the football itself in video footage using the YOLO model, renowned for its accuracy in object detection. The project also involves training the model to enhance its detection capabilities. Additionally, players will be assigned to teams based on the color of their t-shirts, achieved through pixel segmentation and clustering using Kmeans. This analysis will allow us to calculate the ball possession percentage for each team. Optical flow will be used to measure camera movement between frames, providing accurate tracking of player movement. Perspective transformation will be applied to calculate real-world distances, enabling precise measurement of player movement in meters. Finally, the project includes calculating the speed and distance covered by each player. This comprehensive project covers multiple key concepts and real-world challenges, making it ideal for both novice and experienced machine learning practitioners.

## Components and Tools
The project utilizes the following key modules:
- **YOLO**: A powerful AI model for object detection.
- **Kmeans Clustering**: Used for pixel segmentation to differentiate t-shirt colors for team assignment.
- **Optical Flow**: Applied to track camera movement within video frames.
- **Perspective Transformation**: Used to model scene depth and calculate real-world distances.
- **Player Metrics**: Calculates the speed and distance covered by each player.

## Sample Input Video
- [Sample Video File](https://drive.google.com/file/d/1t6agoqggZKx6thamUuPAIdN_1zR9v9S_/view?usp=sharing)