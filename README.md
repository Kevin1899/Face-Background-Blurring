
# Background Blur with Face Preservation

This repository contains Python code for blurring the background of images while preserving the face using the MTCNN face detection model. It is a simple example of how to use face detection to create visually appealing portraits.

## Prerequisites

Before using this code, make sure you have the following dependencies installed:

- OpenCV
- MTCNN
- NumPy
- Matplotlib

You can install these dependencies using `pip`:
pip install opencv-python opencv-python-headless mtcnn numpy matplotlib


## Usage

1. Clone this repository:

git clone https://github.com/yourusername/background-blur-face-preservation.git
cd background-blur-face-preservation

1.Place your images in the images directory that you want to process.

2.Modify the image_paths list in the Python script to include the paths to your input images:
image_paths = [
    'images/image1.jpg',
    'images/image2.jpg',
    # Add more image paths as needed
]
Run the script to process the images and save the results:

python background_blur.py

The processed images will be saved in the output_images directory.

# Customization
You can adjust the sigmaX parameter in the cv2.GaussianBlur function to control the level of blurriness.

If you want to improve the hair region detection, you may need to use a different method or library to extract the hair region accurately.

# Acknowledgments
The MTCNN face detection model is used to detect and extract face regions.

This code was inspired by the need to create visually appealing portraits with background blur while preserving the subject's face.

Feel free to customize and use this code in your projects. If you find it helpful or have any feedback, please let us know.

Happy coding!

![nhln](https://github.com/Kevin1899/Face-Background-Blurring/assets/30956591/e51eb088-b99a-493e-b6b2-3128a4ca7be1)    After Blurring image looks like->    ![nhln](https://github.com/Kevin1899/Face-Background-Blurring/assets/30956591/19b428d1-ecf2-4cce-8b07-cb1f01342b39)

![man](https://github.com/Kevin1899/Face-Background-Blurring/assets/30956591/64f2f0ee-abb3-44cb-9be0-6f3e03576a0d)   After Blurring image looks like ->   ![man](https://github.com/Kevin1899/Face-Background-Blurring/assets/30956591/c13a62be-6764-448a-ac6f-ab58bc93857a)

![Ym1](https://github.com/Kevin1899/Face-Background-Blurring/assets/30956591/89a76f36-56d9-45b8-a644-067501da45e1)   After Blurring image looks like->     ![Ym1](https://github.com/Kevin1899/Face-Background-Blurring/assets/30956591/338118bd-2d6a-4323-94dc-4baf394c6481)





