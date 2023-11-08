# MSc Dissertation Robotic Shiitake Harvest

This repository contains the code, documents, and datasets related to an MSc Dissertation project focused on utilising computer vision and robotic systems for harvesting shiitake mushrooms. The project was conducted within the Centre for Machine Vision at the Bristol Robotics Laboratory.

## For other ML/CV projects see [Machine Learning Projects](https://github.com/trow-land/Machine-Learning) and [Computer Vision Projects](https://github.com/trow-land/Computer-Vision-Projects)

## Project Aims and Objectives

### Aims

- To determine if current computer vision methods can be used to accurately count Shiitake mushrooms growing on a sawdust fruiting block.
- To investigate whether 3D imaging data will improve the detection of Shiitake mushrooms.
- To research whether 3D imaging can be used to plan the harvesting of Shiitake mushrooms with a robot arm.

### Objectives

- Create a dataset of Shiitake mushrooms using a 3D camera.
- Train a 2D and 3D object detection model to detect Shiitake mushrooms on the fruiting block.
- Create a program that will order the detected Shiitake mushrooms and number them in a logical order for harvest.
- Create a separate dataset of the mushroom stems and make a cut-point estimation program to determine suitable cut-points.
- Train a keypoint detection program to determine suitable cut-points

<!-- ![Uploading Mask-RCNN2.png…]() -->


<p align="center">
  <img width="870" height="490" src="https://github.com/trow-land/MSc-Dissertation-Shiitake-Harvest/blob/main/images/inference_gif.gif">
</p>

## Repository Structure

- `datasets/` - Contains the datasets of Shiitake mushrooms used for training and testing the models along with examples. 
- `code/` - Contains the source code for object detection, pose estimation, cut-point estimation, and harvest planning.
- `documentation/` - Contains project documentation, including the dissertation report, and any relevant research papers or resources.



## License

This project is licensed under the MIT License - see the `LICENSE.md` file for details.

## Acknowledgements

- Centre for Machine Vision, Bristol Robotics Laboratory
- University of Bristol & The University of the West of England
- Tom Rowland, MSc Student
- Prof. Mark Hansen, Project Supervisor


## Contact

For any questions or inquiries, please contact Tom Rowland at tom_rowland@outlook.com.


![mask_rcnn](https://github.com/trow-land/MSc-Dissertation-Shiitake-Harvest/blob/main/images/Mask-RCNN2.png)
