# MobileNet

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

MobileNet is a TensorFlow.js-based image classification web application.

## Demo
You can try the live demo at https://code4fukui.github.io/MobileNet/

## Features
- Real-time image classification using the MobileNet model
- Classifies a wide range of objects, animals, and more
- Displays the top classification results with confidence scores
- Uses the camera on your device to capture the video stream

## Requirements
- A modern web browser that supports the HTML5 `<video>` element and the JavaScript APIs used (e.g., Chrome, Firefox, Safari)

## Usage
1. Open the [demo page](https://code4fukui.github.io/MobileNet/) in your web browser.
2. Grant the website access to your device's camera when prompted.
3. The application will start classifying the objects in the camera's view and display the results.

## Data / API
The image classification is powered by the pre-trained MobileNet model, which is loaded from the TensorFlow.js library.

## License
MIT License — see [LICENSE](LICENSE).