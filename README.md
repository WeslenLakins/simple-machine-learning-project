# Multiple Object Detection Web App

This web application utilizes TensorFlow.js and a pre-trained COCO-SSD model to demonstrate real-time multiple object detection. Users can interact with the application through three main demos: classifying pre-set images, uploading images for classification, and using a webcam for continuous classification.

## Features

- **Classify Pre-set Images**: Click on any of the provided images to see the model's predictions about the contents of the image, including the positions of detected objects.
- **Upload Your Image**: Users can upload an image from their device to identify objects within it. The application will display the name of the detected objects along with the confidence level of the prediction.
- **Webcam Continuous Classification**: This feature allows users to get real-time classifications of objects seen by their webcam. It requires HTTPS and browser permissions to access the webcam.

## How to Use

1. **Wait for the Model to Load**: Upon loading the webpage, give it a moment for the TensorFlow model to load. The demo sections will become visible and interactive once the model is ready.
2. **Select a Demo**: Choose one of the demos mentioned above. For webcam classification, ensure you are on a secure (HTTPS) connection.
3. **Interact and Explore**: Follow the instructions for each demo. For image classification, simply click or upload an image. For real-time classification, enable your webcam as prompted.

## Technical Details

- **TensorFlow.js**: This application uses TensorFlow.js for integrating machine learning capabilities directly in the web browser, without requiring a server backend for processing.
- **COCO-SSD Model**: A pre-trained model capable of detecting multiple objects in images. This model is loaded directly from TensorFlow's model library.
- **JavaScript and HTML5**: The interactive components and the machine learning integration are all handled through JavaScript, while the layout and basic functionality are set up with HTML5.

## Requirements

- A modern web browser with JavaScript enabled.
- Webcam access for the real-time classification demo (optional).

## Running the App Locally

To run the app locally, simply clone the repository and open `index.html` in your web browser. Ensure you have an internet connection to load the TensorFlow.js library and the pre-trained model.

## Acknowledgements

Credit to Jason Mayes and the TensorFlow.js team for providing the machine learning model and the utilities to make this application possible.

## License

This project is open-source and available under the MIT License. See the LICENSE file for more details.

## Contributions

Contributions are welcome! Please submit a pull request or open an issue if you have any improvements or find any bugs.

---

For more detailed instructions and information about how the application works, visit the [project page](https://glitch.com/~tensorflow-js-object-detection) or view the source code on [GitHub](https://github.com/tensorflow/tfjs-models/tree/master/coco-ssd).
