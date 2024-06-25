## Healthcare Device Data Classifier and Extractor.

This is a medical device classification and extractiion model, in this it would run a Streamlit web application that uses machine learning and OCR (Optical Character Recognition) to classify medical devices and extract relevant data from images of healthcare devices such as glucometers, oximeters, etc. It perfectly works at glucometer and oximeter devices...

## Introduction

This project is a combination of Classification and OCR Extraction model. I have used a pre-trained image classification model Inception V3 and fine tune it according to my data to identify the type of device and I have used EasyOCR for text recognition to extract relevant data (like glucose values) from those images.

## Features

- Upload images of healthcare devices
- Classify the type of medical device
- Extract and display relevant data from the uploaded images
- Save the extracted data to a CSV file
- Download the CSV file
- Clear the data
  
## Installation

To run this project locally, follow these steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/SGovindraj/medical_device.git
   cd medical_device
   ```

2. Create a virtual environment and activate it:
   ```bash
   python -m venv env
   source env\Scripts\activate
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Download the pre-trained classification model and save it as `device1.h5` in the project directory.

## Usage

To run the Streamlit application, use the following command:
```bash
streamlit run app.py
```

Then, open your web browser and go to `http://localhost:8501`.

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. **Fork the Repository**: Click the "Fork" button at the top right corner of the repository page to create your own copy of the repository.

2. **Clone Your Fork**: Clone your forked repository to your local machine using:
   ```bash
   git clone https://github.com/your-username/medical_device.git
   cd medical_device
   ```

3. **Create a New Branch**: Create a new branch for your feature or bug fix:
   ```bash
   git checkout -b feature-branch-name
   ```

4. **Make Your Changes**: Make the necessary changes to the code.

5. **Commit Your Changes**: Commit your changes with a clear and descriptive commit message:
   ```bash
   git commit -am 'Add detailed description of your changes'
   ```

6. **Push to Your Branch**: Push your changes to your forked repository:
   ```bash
   git push origin feature-branch-name
   ```

7. **Create a Pull Request**: Go to the original repository on GitHub and create a pull request from your fork. Provide a clear description of your changes and any additional information that might help the reviewers.

## License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.

## Contact

SGovindraj - [sgovindraj0606@gmail.com](mailto:sgovindraj0606@gmail.com)

Project Link: [https://github.com/SGovindraj/medical_device](https://github.com/SGovindraj/medical_device)

## Note: To Get a better result, use a clear HD images for extraction...
