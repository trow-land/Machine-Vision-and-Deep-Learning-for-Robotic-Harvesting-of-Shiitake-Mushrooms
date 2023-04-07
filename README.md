# MSc-Dissertation-Shiitake-Harvest

This repository contains the code, documents, and datasets related to an MSc Dissertation project focused on utilizing computer vision and robotic systems for harvesting shiitake mushrooms. The project was conducted within the Centre for Machine Vision at the Bristol Robotics Laboratory.

## Project Aims and Objectives

### Aims

- To determine if current computer vision methods can be used to accurately count Shiitake mushrooms growing on a sawdust fruiting block.
- To investigate whether 3D imaging data will improve the detection of Shiitake mushrooms.
- To research whether 3D imaging can be used to plan the harvesting of Shiitake mushrooms with a robot arm.

### Objectives

- Create a dataset of Shiitake mushrooms using a 3D camera.
- Train an object detection model to detect Shiitake mushrooms on the fruiting block.
- Determine the pose of Shiitake mushrooms in relation to the fruiting block using either 2D or 3D data.
- Create a program that will order the detected Shiitake mushrooms and number them in a logical order for harvest.
- Create a separate dataset of the mushroom stems and make a cut-point estimation program to determine suitable cut-points.
- Stretch Objective: Utilise 3D vision to achieve grasp pose estimation of a robotic end effector at various cut points.

## Repository Structure

- `datasets/` - Contains the dataset of Shiitake mushrooms and mushroom stems used for training and testing the models.
- `code/` - Contains the source code for object detection, pose estimation, cut-point estimation, and harvest planning.
- `documentation/` - Contains project documentation, including the dissertation report, and any relevant research papers or resources.
- `results/` - Contains the evaluation results of the implemented methods and models.

## Getting Started

Please follow the instructions in the `INSTALL.md` file to set up the required dependencies and environment to run the code.

## Contributing

Please see `CONTRIBUTING.md` for details on how to contribute to this project.

## License

This project is licensed under the MIT License - see the `LICENSE.md` file for details.

## Acknowledgements

- Centre for Machine Vision, Bristol Robotics Laboratory
- Tom Rowland, MSc Student
- Dr Mark Hanses, Project Supervisor


## Contact

For any questions or inquiries, please contact Tom Rowland at tom_rowland@outlook.com.
