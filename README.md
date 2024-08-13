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

## Others
- There is a jupyter notebook inside the training folder which was used to train the model on Google Colaboratory, which output a best.pt file which was stored in the models folder to use.
- The input video is in the input_videos folder

## Output
- Along with what's in the output_videos folder, here are screenshots of the video that was produced, which was too big to upload to github.

<img width="1470" alt="Screenshot 2024-08-13 at 8 28 42 PM" src="https://github.com/user-attachments/assets/8fbed414-7187-47b4-8b51-3a1125ae33c9">
<img width="1470" alt="Screenshot 2024-08-13 at 8 28 28 PM" src="https://github.com/user-attachments/assets/51eb6a32-2ed6-46f1-ad2d-6858f7cabaa4">
<img width="1470" alt="Screenshot 2024-08-13 at 8 28 18 PM" src="https://github.com/user-attachments/assets/a7a3373f-df05-497b-941a-d8fc66f95d66">
<img width="1470" alt="Screenshot 2024-08-13 at 8 28 11 PM" src="https://github.com/user-attachments/assets/83d351d6-1d77-4c9e-b28d-283a196f8c81">

## Enjoy!

