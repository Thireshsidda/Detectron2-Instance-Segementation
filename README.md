# Traffic Signs Instance Segmentation with Detectron2 Flask App
![Detectron2 Logo](images/detectron2-logo.png)

## Introduction

Instance segmentation, a cornerstone in computer vision, surpasses traditional image recognition by precisely identifying and delineating individual objects within an image. This nuanced approach has wide-ranging applications, from enhancing autonomous vehicles to refining medical imaging.

In selecting Detectron2 for instance segmentation, a deliberate choice was made to embrace a library that stands as a beacon in the landscape of computer vision. Detectron2, an offspring of Facebook AI Research (FAIR), represents a confluence of robustness, accuracy, and extensibility. Its modular architecture allows for seamless integration into diverse applications, making it an ideal candidate for our instance segmentation Flask app.

The motivation behind this choice lies in Detectron2’s track record of excelling in object detection and segmentation tasks. Its pre-trained models, crafted through extensive research and fine-tuning, provide a solid foundation for accurate instance segmentation. Moreover, Detectron2’s active community and ongoing development ensure that the library stays at the forefront of advancements in the rapidly evolving field of computer vision.

## Overview
This project leverages the state-of-the-art Detectron2 library, developed by Facebook AI Research (FAIR), to bring instance segmentation to the forefront. By integrating it into a user-friendly Flask web application, the project not only demystifies complex image analysis but also opens avenues for interactive and accessible computer vision applications. Join us to explore the transformative potential of instance segmentation and its impact on reshaping our interaction with visual data.

### User Interface

![User Interface](images/ui.png)

### Streamlit User Interface

![Streamlit UI](images/streamlit_ui.png)

## Getting Started

Follow these steps to get started with the project.

### 1. Clone the Repository

```bash
git clone git@github.com:SHOCKWAVE07/Detectron2-FlaskApp.git
```
```bash
cd Detectron2-FlaskApp
```

### 2. Create and Activate virtual environment using conda

```bash
conda create --name your-env-name python=3.8
```
```bash
conda activate your-env-name
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Install major dependencies

```bash
conda install pytorch torchvision torchaudio cudatoolkit=11.0 -c pytorch
```
```bash
git clone https://github.com/facebookresearch/detectron2.git
```
```bash
cd detectron2
```
```bash
pip install -e .
```
```bash
cd ..
```

### 4. Run the Application

1. Flask App
```bash 
python run.py
```

2. Streamlit App
```bash
streamlit run streamlit_app.py
```

## Model precision

![Model precision](images/precision.jpg)


## Features
- **Instance Segmentation:** Utilizing Detectron2’s pre-trained models, our app achieves granular instance segmentation, precisely identifying and outlining individual objects within images. This is particularly beneficial in scenarios where detailed object understanding is paramount, such as in medical imaging for organ delineation.
  
- **User-friendly Interface:** The app boasts a user-friendly web interface, enabling users to upload images and visualize segmentation results effortlessly. This accessibility is key for users across various domains, from researchers experimenting with computer vision to professionals seeking quick insights from visual data.

- **Flask Web Application:** Developed on the Flask web framework, our application prioritizes simplicity and ease of deployment. Flask’s lightweight and modular nature makes it an optimal choice for hosting the app, ensuring a smooth user experience during deployment and interaction.

- **Conda Environment:** The inclusion of a recommended Conda environment underscores our commitment to a consistent and reproducible development environment. This ensures that users, regardless of their setup, can easily replicate and build upon the project without encountering versioning or dependency challenges.


## How it Works
##### To demystify the intricacies of our instance segmentation Flask app, let’s walk through the streamlined process it follows:
1. **User Uploads Image:** Users initiate the process by uploading images through the user-friendly web interface provided by our Flask application.

2. **Instance Segmentation:** The uploaded image undergoes a meticulous process powered by Detectron2’s pre-trained models. These models excel in discerning and delineating individual objects within the image, performing instance segmentation with a high level of accuracy.

3. **Result Display:** The segmented image, now enriched with colour-coded masks representing detected instances, is presented back to the user. This step provides a visual understanding of how the model has identified and segmented various objects within the uploaded image.

4. **Easy Deployment:** Designed with user convenience in mind, the Flask web application ensures easy deployment. Users have the flexibility to run the application locally or deploy it on a server, adapting to their specific needs and preferences.

## Requirements
- Python 3.x
- Conda (for managing the virtual environment)
- Detectron2 library
- Flask

## Usage
1. Clone the repository.
2. Create a conda environment and install dependencies.
3. Run the Flask application using `python run.py`.
4. Access the application at [http://localhost:5000](http://localhost:5000) in your web browser.

## Conclusion
In conclusion, our instance segmentation Flask app powered by Detectron2 opens the door to a realm of possibilities in computer vision. By providing a user-friendly interface, seamless deployment options, and leveraging state-of-the-art instance segmentation, the project invites users to explore the nuances of this transformative technology.



## Author

👤 **Thiresh Sidda**

* LinkedIn: [@ThireshSidda](https://www.linkedin.com/in/thiresh-sidda)
* GitHub: [@ThireshSidda](https://github.com/Thireshsidda)
