# Healthcare Device Data Extractor and Classifier

A Streamlit web application that uses machine learning and OCR (Optical Character Recognition) to classify medical devices and extract relevant data from images of healthcare devices such as glucometers, oximeters, etc.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

This project provides a web interface for uploading images of healthcare devices. It uses a pre-trained image classification model to identify the type of device and EasyOCR for text recognition to extract relevant data (like glucose values) from those images.

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
   git clone https://github.com/your-username/your-repository.git
   cd your-repository






Here's the updated README content to reflect both the device value extraction model and the medical device classification model:

```markdown
# Healthcare Device Data Extractor and Classifier

A Streamlit web application that uses machine learning and OCR (Optical Character Recognition) to classify medical devices and extract relevant data from images of healthcare devices such as glucometers, oximeters, etc.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

This project provides a web interface for uploading images of healthcare devices. It uses a pre-trained image classification model to identify the type of device and EasyOCR for text recognition to extract relevant data (like glucose values) from those images.

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
   git clone https://github.com/your-username/your-repository.git
   cd your-repository
   ```

2. Create a virtual environment and activate it:
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows, use `env\Scripts\activate`
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

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

Your Name - [your-email@example.com](mailto:your-email@example.com) - [Your LinkedIn](https://linkedin.com/in/your-profile)

Project Link: [https://github.com/your-username/your-repository](https://github.com/your-username/your-repository)
```

This content includes details about both the device value extraction model and the medical device classification model. Make sure to replace placeholders with your actual information and ensure the `requirements.txt` file includes all necessary dependencies for your project. Save this content in a file named `README.md` in your repository.
