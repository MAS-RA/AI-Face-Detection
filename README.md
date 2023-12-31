# AI-Face-Detection

AI-Face-Detection is a Python project that utilizes the power of artificial intelligence to detect and analyze faces within images. It employs the OpenCV library and pre-trained deep learning models to identify both gender and approximate age range of detected faces.

![Sample Result](https://developer.bmde-labs.com/storage/article_images/dMk6gvY8IpyFZAQNYaOMiecCXQK5DiwnfzltPIsc.png)

### Usage

To run the face detection on an image, use the following command:

```bash
python main.py --image input/3.jpg
```

The output will display the gender and age range of detected faces:

```plaintext
Gender: Male
Age: 60-100 years
```

## Features

- Utilizes OpenCV for efficient image processing and computer vision tasks.
- Incorporates pre-trained deep learning models for face detection, gender classification, and age estimation.
- Outputs the gender and age of detected faces overlaid on the original image.

## Getting Started

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/MAS-RA/AI-Face-Detection.git
   ```

2. Move into the project directory:

   ```bash
   cd AI-Face-Detection
   ```

3. Download the `Models.zip` file from Mega using the following link:

   [Download Models.zip from Mega](https://mega.nz/file/DwdTxYQB#YuSENTebkWgtJSZcMcLtfSzB5GoSNKNZnSYAyB3miDk)

4. Extract the contents of the `Models.zip` file and place the `Models` folder in the same directory as `main.py`. Your directory structure should look like this:

   ```
   AI-Face-Detection/
   ├── input/        # Repository for input images
   ├── Models/       # Houses pre-trained model files
   │   ├── age_deploy.prototxt
   │   ├── age_net.caffemodel
   │   ├── gender_deploy.prototxt
   │   ├── gender_net.caffemodel
   │   ├── opencv_face_detector.pbtxt
   │   ├── opencv_face_detector_uint8.pb
   │   └── yolov3.weights
   ├── main.py       # Core script for face detection operations
   ├── README.md     # This comprehensive guide
   └── requirements.txt  # List of required libraries
   ```

5. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

6. Run the main script with an image of your choice:

   ```bash
   python main.py --image PATH_TO_IMAGE.jpg
   ```

## Sample Output

The project's main script, `main.py`, takes an image as input, detects faces, and provides information about the gender and approximate age of each detected face. The result is displayed in a window showing the original image with annotations.

## Social Links

Follow me for more inspiration:

- <a href="https://www.sololearn.com/profile/26555651" target="_blank"><img src="https://blob.sololearn.com/avatars/sololearn.png" alt="Sololearn" width="18" height="18"> Follow me on Sololearn</a>
- <a href="https://github.com/MAS-RA/paint-web-app" target="_blank"><img src="https://github.com/fluidicon.png" alt="GitHub" width="18" height="18"> Check out the project on GitHub</a>
- <a href="https://www.instagram.com/alisaeed.thabt/" target="_blank"><img src="https://www.instagram.com/static/images/ico/favicon-192.png/68d99ba29cc8.png" alt="Instagram" width="18" height="18"> Follow me on Instagram</a>
- <a href="https://www.buymeacoffee.com/AliSaeedThabt" target="_blank"><img src="https://image-link-to-coffee-icon" alt="Buy Me a Coffee" width="18" height="18"> Buy Me a Coffee</a>


## Demo

![Demo Image](https://developer.bmde-labs.com/storage/article_images/d916y4TG7rIrYt05x391jbvPtn8rPAJ2RJNAjpqh.png)

## Contributing

Contributions to AI-Face-Detection are welcome! Feel free to open issues, suggest enhancements, or submit pull requests to improve the project.

## License

This project is licensed under the MIT license. See the [LICENSE](LICENSE) file for details.

---

For updates and announcements, follow me on Instagram [@Alisaeed.thabt](https://www.instagram.com/alis

aeed.thabt/).

Let's make face detection smarter and more accurate with the power of AI! Your contributions are highly appreciated.
