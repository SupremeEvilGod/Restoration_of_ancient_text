Kannada Text Restoration Using AI
Overview

This project aims to restore degraded Kannada text using artificial intelligence. By employing advanced techniques like Convolutional Neural Networks (CNN), the system efficiently reconstructs damaged characters, enhancing accessibility to Kannada literature.
Table of Contents

    Installation
    Usage
    Methodology
    Dataset
    Results
    Contributions
    Future Work
    License

Installation

    Clone the repository:

    bash

git clone <repository_url>

Navigate to the project directory:

bash

cd <project_directory>

Install the required dependencies:

bash

    pip install -r requirements.txt

Usage

    Prepare your degraded Kannada text images.
    Run the restoration script:

    bash

    python restore_text.py --input <path_to_images> --output <output_directory>

    The restored texts will be saved in the specified output directory.

Methodology

    Data Collection: Handwritten text images are collected from online sources and 250 student samples.
    Image Processing: Contour techniques are used to detect and segment text into individual letters.
    Model Preparation:
        Tesseract: Various letter combinations are utilized.
        CNN: Words are broken down into separate letters for training.

Dataset

The project uses a combination of online handwritten PDFs and samples collected from students, ensuring a diverse representation of Kannada handwriting.
Results

The system achieves high accuracy in restoring Kannada characters, significantly improving access to degraded texts.
Contributions

    Developed by: [Your Name(s)]
    Guided by: [Instructor’s Name]

Future Work

Future improvements may include:

    Expanding the dataset to include more handwriting styles.
    Enhancing model efficiency and accuracy through additional training techniques.

License

This project is licensed under the MIT License.
