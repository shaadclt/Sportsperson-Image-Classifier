# Sportsperson Image Classifier

This project is an image classifier that can identify different sportspersons using OpenCV, Haar cascades, and logistic regression. The classifier is deployed using Flask, allowing users to interact with it through a web interface.

## Features

- Classification of sportspersons: The image classifier can identify 5 sportspersons.
- OpenCV and Haar cascades: The classifier leverages the power of OpenCV library and Haar cascades for object detection and recognition in images.
- Logistic regression: The classifier uses logistic regression as the underlying machine learning algorithm to classify the sportspersons.
- Web interface: The classifier is deployed using Flask, providing a user-friendly web interface for users to upload images and obtain the classification results.

## Installation

To set up the Sportsperson Image Classifier on your local machine, follow the steps below:

1. Clone the repository:

```bash
git clone https://github.com/shaadclt/Sportsperson-Image-Classifier.git
```

2. Navigate to the project directory:

```bash
cd Sportsperson-Image-Classifier
```

3. Create a virtual environment (optional but recommended):

```bash
python3 -m venv venv
```

4. Activate the virtual environment:

```bash
source venv/bin/activate
```

5. Install the required dependencies:

```bash
pip install -r requirements.txt
```

## Usage

1. Ensure you are in the project directory and the virtual environment is activated (if created).

2. Start the Flask server:

```bash
python app.py
```

3. Open your web browser and visit `http://localhost:5000`.

4. You will see the web interface for the image classifier. Click on the "Choose File" button to upload an image.

5. Select an image containing a sportsperson and click "Upload" to classify it.

6. Wait for the classifier to process the image. Once complete, you will see the predicted sportsperson label displayed on the web page.

7. You can upload more images and classify them as desired.

## Customization

You can customize the Sportsperson Image Classifier to fit your specific requirements. Here are a few suggestions:

- **Training data**: The classifier's performance heavily relies on the quality and diversity of the training data. Consider collecting additional labeled images of different sportspersons to improve the accuracy.
- **Model selection**: Instead of logistic regression, you can experiment with other machine learning algorithms or even deep learning models to achieve better results. OpenCV provides various other classifiers and frameworks to explore.
- **Web interface**: You can enhance the web interface by adding additional features such as displaying probability scores, allowing batch image uploads, or implementing user authentication.

## Contribution

Contributions are welcome to improve the Sportsperson Image Classifier. If you find any issues or have suggestions for enhancements, please open an issue on the GitHub repository.

If you would like to contribute code, follow these steps:

1. Fork the repository.
2. Create a new branch.
3. Make your changes and commit them.
4. Push your changes to your forked repository.
5. Open a pull request in the original repository.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

The Sportsperson Image Classifier project builds upon various open-source libraries and resources. The following sources were particularly helpful:

- OpenCV: [https://opencv.org](https://opencv.org)
- Flask: [https://flask.palletsprojects.com](https://flask.palletsprojects.com)
- Haar cascades: [https://docs.opencv.org/3.4/db/d28/tutorial_cascade_classifier.html](https://docs.opencv.org/3.4/db/d28/tutorial_cascade_classifier.html)

We would like to express our gratitude to the authors and contributors of these projects for their valuable work.
