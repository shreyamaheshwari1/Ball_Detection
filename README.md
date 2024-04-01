# Ball_Detection
Project Description: Cricket Ball Trajectory Tracking

<b>1. Overview:</b>
Developed a deep learning project to accurately track the trajectory of a cricket ball during live matches.

 <b>2.Techniques Used:</b>
Employed YOLOv3 for real-time ball detection.
Designed a custom deep neural network architecture named "PatchModel" for trajectory prediction.

<b>3. PatchModel Architecture:</b>
Reduced image size to a patch of 72x72 for efficient processing.
Utilized two input images, leveraging convolution and deconvolution layers to predict ball trajectory.
Implemented binary cross-entropy as the loss function for training.

<b>4. Training Process:</b>
Manually annotated bounding box coordinates for the ball in the training dataset.
Trained the PatchModel architecture for a large number of epochs to optimize performance.

<b>5. Testing Strategy:</b>
Initially utilized YOLO for ball detection in consecutive frames.
Transitioned to PatchModel prediction when YOLO accuracy surpassed 80%.

<b>6. Workflow:</b>
Utilized YOLO-detected ball location to extract a patch from the frame.
Fed both the previously detected and current frames into PatchModel for trajectory prediction.

<b>7. Key Achievements:</b>
Successfully tracked cricket ball trajectory in live matches.
Implemented a hybrid approach combining real-time detection with trajectory prediction for accuracy and efficiency.
Contributed to advancements in sports analytics and tracking technologies.

<b>OUTPUT SAMPLE VIDEO LINK:-</b>
https://github.com/shreyamaheshwari1/Ball_Detection/assets/114720478/b824c4db-dc38-4440-a5e8-b4d4ac2cfae4



