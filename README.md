# Smart Health – AI Health Assistant

An AI-powered health assistant built with Python and Streamlit. This project combines symptom-based disease prediction with deep-learning-based image classification for chest X-rays and skin lesions.

## Features

- **Symptoms Checker:** Predicts a possible disease based on selected symptoms and displays related descriptions and precautions.
- **Chest X-ray Analysis:** Classifies uploaded chest X-ray images into Normal or Pneumonia categories using a ResNet18-based model.
- **Skin Lesion Classification:** Classifies uploaded skin lesion images into supported categories using a ResNet18-based model.
- **Interactive Web Interface:** Provides a simple interface built with Streamlit.

## Technologies Used

- Python
- Streamlit
- Pandas and NumPy
- PyTorch and TorchVision
- Scikit-learn
- Pillow (PIL)
- Jupyter Notebook

## Project Structure

```text
Smart-Health/
├── app.py
├── README.md
├── requirements.txt
├── dataset.csv
├── pneumonia_model.pth
├── skin_cancer_model.pth
├── symptom_Description.csv
├── symptom_precaution.csv
├── Symptom-severity.csv
└── Symptoms.ipynb
```

*Note: The filenames above describe the main project files; check the exact spelling and capitalization in your repository.*

## Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/Anukul0708/Smart-Health.git
cd Smart-Health
```

### 2. Create and activate a virtual environment

On Windows:

```bash
python -m venv .venv
.venv\Scripts\activate
```

### 3. Install dependencies

```bash
python -m pip install --upgrade pip
pip install -r requirements.txt
```

### 4. Run the application

```bash
python -m streamlit run app.py
```

Open the local URL displayed in the terminal to use the application.

## How to Use

1. Start the Streamlit application.
2. Select a module from the sidebar.
3. For the Symptoms Checker, enter or select the available symptoms.
4. For image analysis, upload a suitable chest X-ray or skin lesion image.
5. Review the model's output and any information displayed by the application.

## Dataset Links

### Chest X-ray Dataset

[Open Chest X-ray Dataset on Google Drive](https://drive.google.com/drive/folders/12Gd2aoQ3Koo8IcSb8vGIPKzPbiFHfoQ5?usp=sharing)

### Skin Cancer Dataset

[Open Skin Cancer Dataset on Google Drive](https://drive.google.com/drive/folders/12Gd2aoQ3Koo8IcSb8vGIPKzPbiFHfoQ5?usp=sharing)

*Verify that each link points to the correct dataset folder before sharing this repository publicly.*

## Important Medical Disclaimer

This project is intended for educational and demonstration purposes only. Its predictions are not a medical diagnosis and must not replace professional medical advice, examination, or treatment. Model outputs may be inaccurate. Consult a qualified healthcare professional for medical concerns.

## Author

**Anukul Chandra Jha**

GitHub: [Anukul0708](https://github.com/Anukul0708)
