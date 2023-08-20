# AI-Face-Detection

AI-Face-Detection is a Python project that utilizes the power of artificial intelligence to detect and analyze faces within images. It employs the OpenCV library and pre-trained deep learning models to identify both gender and approximate age range of detected faces.

![Sample Result](sample_result.jpg)

## Features

- Utilizes OpenCV for efficient image processing and computer vision tasks.
- Incorporates pre-trained deep learning models for face detection, gender classification, and age estimation.
- Outputs the gender and age of detected faces overlaid on the original image.

## Getting Started

1. Clone the repository to your local machine:

   (```bash)
   git clone https://github.com/your-username/AI-Face-Detection.git
   (```)
s
2. Install the required dependencies:

   (```bash)
   pip install -r requirements.txt
   (```)

3. Download the necessary model files from the following links and place them in the project directory:

   - [opencv_face_detector.pbtxt](model_links/opencv_face_detector.pbtxt)
   - [opencv_face_detector_uint8.pb](model_links/opencv_face_detector_uint8.pb)
   - [age_deploy.prototxt](model_links/age_deploy.prototxt)
   - [age_net.caffemodel](model_links/age_net.caffemodel)
   - [gender_deploy.prototxt](model_links/gender_deploy.prototxt)
   - [gender_net.caffemodel](model_links/gender_net.caffemodel)

4. Run the main script with an image of your choice:

   (```bash)
   python main.py --image PATH_TO_IMAGE.jpg
   (```)

## Sample Output

The project's main script, `main.py`, takes an image as input, detects faces, and provides information about the gender and approximate age of each detected face. The result is displayed in a window showing the original image with annotations.

## Social Links

Follow me for more inspiration:

- [![Sololearn](https://image-link-to-sololearn-icon)](https://www.sololearn.com/profile/26555651) Follow me on Sololearn
- [![Instagram](https://image-link-to-instagram-icon)](https://www.instagram.com/alisaeed.thabt/) Follow me on Instagram
- [![GitHub](https://image-link-to-github-icon)](https://github.com/MAS-RA/paint-web-app) Check out the project on GitHub
- [![Buy Me a Coffee](https://image-link-to-coffee-icon)](https://www.buymeacoffee.com/AliSaeedThabt) Buy Me a Coffee

## Demo

![Demo Image](https://developer.bmde-labs.com/storage/article_images/d916y4TG7rIrYt05x391jbvPtn8rPAJ2RJNAjpqh.png)

## Contributing

Contributions to AI-Face-Detection are welcome! Feel free to open issues, suggest enhancements, or submit pull requests to improve the project.

## License

This project is licensed under the [Your License] License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

This project was inspired by the work of Mahesh Sawant.

---

For updates and announcements, follow us on Twitter [@AIFaceDetect](https://twitter.com/AIFaceDetect). Join our Discord community [here](https://discord.gg/ai-face-detection) to connect with other developers and enthusiasts.

Let's make face detection smarter and more accurate with the power of AI! Your contributions are highly appreciated.
EOT
