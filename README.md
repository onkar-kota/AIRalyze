# Image Based Air Pollution detection using Inception-V3 Model

## 1. Introduction

Air pollution has become an alarming environmental issue globally due to rapid urbanization and industrialization. Among different air pollutants, airborne particulate matter (PM) with diameters less than 2.5 micrometers (PM2.5) has significant harmful effects on the human body as these particles are capable of transmitting hazardous chemicals into the human lung and blood and cause cardiovascular, respiratory and cerebrovascular diseases, reduced lung functions, and heart attacks. Therefore, PM2.5 concentration has been used as a worldwide major air quality metric. Efficient and inexpensive air quality monitoring tools could bring significant benefits to human health and air pollution control.

## 2. Objectives

- To investigate image-based air quality analysis, in particular particulate matter concentration in Air.
- To provide reliable data for regular people to understand and gauge the quality of air in their immediate surroundings.
- To Develop low-Cost System to Predict Air Quality.
- Differentiate Air Quality in immediate.

## 3. Problem Statement

- Analyzing Image in order to get Air Pollution Data.
- There is hardly any reliable data for common people to understand and gauge the quality of air in their immediate surroundings.
- Sensor-based methods are expensive, image-based air quality measurements are often inexpensive and thus a promising direction.

## 4. **Data Collection and Preprocessing**

Here we have used google images and locally collected data

Dataset contains two files and related sub-files

1. Validate
    1. Irrelevant input
    2. Moderate pollution
    3. No pollution
    4. Severe pollution
2. train
    1. Irrelevant input
    2. Moderate pollution
    3. No pollution
    4. Severe pollution
    
Dataset segregation

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/e23afb5d-8530-4b15-b34a-f41ccba8f784/Untitled.png)

Sample images

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/ff3a9150-d1ce-4958-8cbc-8041db01d8ab/Untitled.png)

## 5. Mapping the real-world problem to a Machine learning Problem

- Here CNN(Convolutional Neural Networks) method is used of image segmentation
- This method applies CNN for air quality analysis, in particular image-based PM2.5 concentration estimation for any locations.
- The RGB color channels of the image are input to the deep learning network to estimate PM2.5 concentration directly, which overcomes the restrictions of having sensors, auxiliary data, fixed location, or sophisticated image features.
- Using a pretrained (CNN) model to output a transmission map.
- Run the transmission map on a convolutional neural network module and output a prediction.

  ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/3f808056-680d-47e6-ad61-c822370a0342/Untitled.png)

[App video.mp4](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/37b7b46b-1156-43ee-a0ea-380b3ddb7454/App_video.mp4)

## 7. Conclusion

Air pollution is a severe problem that is only going to become worse. Low and middle-income countries have the most sensitive populations to air pollution. Image-based estimations have the potential to expand the geographical coverage of air quality around the world. Air quality data can also have a significant impact on public health.
