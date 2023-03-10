# Writeup: Track 3D-Objects Over Time

## ID_S1_EX1: Visualize range image channels
In this task the following things are obtained.
1. Range image is obtained
2. Intensity image is obtained
3. The image is cropped to view only =/- 90 degrees left and right
4. The image is converted into 8 bit channels

![alt text](./img/Ex1/eX1.png)

## ID_S1_EX2: Visualize Point-cloud
In this task the following things are obtained
1. 10 examples of vehicles in varying degree is found
2. It was noted that the stable arts of the vehicles found on point cloud are the front and back parts especially above the wheels. The front curves are visible clearly, similarly the back curves too.
3. One important thing is that vehicles very near to the Ego, or vehicles on a crowded space are difficult to grasp
4. The environmental assets like trees, bush are clearly visible

![alt text](./img/Ex2/Img1.png)
![alt text](./img/Ex2/Img2.png)
![alt text](./img/Ex2/Img3.png)
![alt text](./img/Ex2/Img4.png)
![alt text](./img/Ex2/Img5.png)

## ID_S2_EX1: Convert sensor coordinates to BEV-map coordinates
In this task, the following things are obtained
1. A BEV image of the point cloud is made

![alt text](./img/Ex3/image.png)

## ID_S2_EX2: Compute intensity layer of BEV-map
In this task, the following things are obtained
1. The intensity values in BEV-map is updated
2. Used normalization to eliminate the outliers
3. A heat map is made for the image created

![alt text](./img/Ex4/image.jpg)
![alt text](./img/Ex4/heatmap.png)

## ID_S2_EX3: Compute height layer of BEV-map
In this task, the following things are obtained
1. The height is normalizec from the BEV-map
2. The minimum height is removed from the point cloud
3. An even better image is obtained

![alt text](./img/Ex5/image.jpg)
![alt text](./img/Ex5/heatmap.png)

## ID_S3_EX1: Add a second model from a GitHub repo
In this task, the following things are obtained
1. The parameters for the model was obtained from SFA3d
2. The parameters are used to set up the model parameters
3. The model was set and the detections are obtained

## ID_S3_EX2: Extract 3D bounding boxes frommodel response
In this task, the following things are obtained
1. The bounding boxes are plotted from the detections

![alt text](./img/Ex6/fullimage.png)

## ID_S4_EX1-3: The metrics are calculated from the images
![alt text](./img/Ex7/precision.png)

