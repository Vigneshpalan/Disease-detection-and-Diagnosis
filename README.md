# Plant Disease Detection System

## Project Overview
This project is part of **Phase 2** of the research paper titled **["Leveraging Super-Resolution Technology in Drone Imagery for Advanced Plant Disease Diagnosis and Prognosis"](https://ieeexplore.ieee.org/document/10921676)**. The system is designed to detect plant diseases from high-resolution images, including those captured by drones, and provides a comprehensive diagnosis. The deep learning model combines image classification with Natural Language Processing (NLP) to generate expert-level explanations of the detected diseases, enabling farmers to take timely action in managing crop health and minimizing losses.

The system employs cutting-edge techniques, including **super-resolution technology** to enhance image quality and improve diagnostic accuracy. The integration of drone imagery allows for wide-area scanning of crops, enabling efficient monitoring of plant health across large fields.

## Key Features
- **Real-time Disease Detection:** Automatically classify plant diseases from high-resolution images using a deep learning model.
- **Expert-level Diagnosis:** Generate detailed, NLP-based explanations of the diagnosed diseases, including possible treatment methods.
- **Super-Resolution Technology:** Enhance low-resolution images captured by drones to improve diagnostic accuracy and visibility of plant diseases.
- **User-friendly Interface:** A web-based interface for easy interaction, providing farmers with real-time insights into crop health.
- **Large-Scale Monitoring:** Leverage drone imagery to scan large fields efficiently, providing a comprehensive diagnosis of plant health.

## Technologies Used
- **Deep Learning** (TensorFlow / PyTorch)
- **NLP** (BERT / GPT)
- **Super-Resolution Technology** ((Real ESRGAN)for enhancing drone imagery)
- **Frontend** (Streamlit)
- **Backend** (Python)

## Project Architecture
The system consists of the following key components:
1. **Data Collection and Preprocessing:** Drone imagery and other plant disease datasets are collected and preprocessed to ensure high-quality training data.
2. **Super-Resolution Technology:** Low-resolution images are enhanced to improve clarity and detail, aiding in better disease detection.
3. **Model Training:** A deep learning model is trained using labeled plant disease data, allowing for accurate disease classification.
4. **NLP Integration:** An NLP model generates detailed explanations of the diseases detected, including suggested treatment options.
5. **User Interface Development:** The final model is deployed with an intuitive web interface, enabling users to easily upload images and get real-time disease diagnosis.

## Sample Predictions

![Healthy Plant](https://github.com/Vigneshpalan/Plant-Disease-Detection-and-Diagnosis/blob/main/Screenshot%202024-10-21%20215207.png)
*Figure 1: Healthy Plant*

![Diseased Plant](https://github.com/Vigneshpalan/Plant-Disease-Detection-and-Diagnosis/blob/main/Screenshot%202024-10-21%20215129.png)
*Figure 2: Diseased Plant Identified*

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

For more details, check out the research paper: [Leveraging Super-Resolution Technology in Drone Imagery for Advanced Plant Disease Diagnosis and Prognosis](https://ieeexplore.ieee.org/document/10921676).
