# Image Segmentation using Mean Shift Algorithm 

This program implements the Mean Shift algorithm for image segmentation using the provided image as input. The goal is to separate the vegetables in the image by selecting a suitable bandwidth that results in distinct segmentation.

## Image Data 📷

The image used for segmentation can be found at the following link: [Image Link](https://drive.google.com/file/d/15-6l7_51OZ3wIw37d8a6SX2dfWxUQGl4/view?usp=sharing) 🔗

## Usage 🖥️

1. Download the image from the provided link and save it locally.
2. Load the image into the program environment.
3. Implement the Mean Shift algorithm for image segmentation.
4. Adjust the bandwidth parameter to achieve optimal separation of vegetables in the image.
5. Generate the segmented image, where the vegetables are distinctly separated.

## Algorithm and Parameters 🧪

The Mean Shift algorithm is used for image segmentation, which is a non-parametric clustering technique. The algorithm works by iteratively shifting each pixel in the image towards the mode of its local density distribution.

To perform image segmentation, a suitable bandwidth parameter is chosen. The bandwidth determines the spatial range for pixel grouping. By adjusting the bandwidth, we can control the level of separation between the vegetables in the image. Experimentation and visual inspection can help determine the optimal bandwidth value.

## Results 📊

The program will generate the following results:

- Segmented image where the vegetables are visually separated.
- The choice of bandwidth and its impact on the separation of vegetables.

Feel free to explore and modify the code to suit your needs. If you have any suggestions or improvements, please feel free to contribute to the repository.
