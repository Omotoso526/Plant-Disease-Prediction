# Plant-Disease-Prediction

Here’s a polished, professional README.md for your Plant-Disease-Prediction project:


---

# 🌿 Plant Disease Prediction Web App

A user-friendly web application that leverages a Convolutional Neural Network (CNN) trained on the PlantVillage dataset to accurately detect and diagnose plant leaf diseases. Built with TensorFlow/Keras and powered by Streamlit or Flask for seamless user interaction.

---

## 🚀 Features

- **CNN-based classification** of 38+ disease classes (including healthy leaves)  
- **Interactive web interface** for easy image upload and real-time predictions  
- **Visual feedback** with confidence scores and disease labels  
- **Trained on Google Colab** with industry-standard tools and best practices 0

---

## 🛠 Tech Stack

- **Backend / AI**: TensorFlow & Keras (CNN architecture)  
- **Frontend**: Streamlit (or Flask + HTML/CSS/JS), providing a clean UI for end users  
- **Dataset**: PlantVillage (38 plant-health/disease categories) 1  
- **Environment**: Google Colab for model training, with `requirements.txt` listing all dependencies

---

## 📁 Repository Structure

. ├── Plant_Disease_Prediction.ipynb   # Model training & evaluation notebook ├── streamlit_app.py                 # App entry point (Streamlit-based) ├── app.py                           # Flask fallback or alternate server ├── requirements.txt                 # Project dependencies ├── test_images/                     # Sample leaf photos for quick testing └── images/                          # App screenshots showcasing image upload → predictions

---

## 📌 Installation

1. **Clone the repo**
   ```bash
   git clone https://github.com/Omotoso526/Plant-Disease-Prediction.git
   cd Plant-Disease-Prediction

2. Create & activate a virtual environment

python3 -m venv venv
source venv/bin/activate       # macOS/Linux
venv\Scripts\activate          # Windows


3. Install dependencies

pip install -r requirements.txt


4. Run the web app

For Streamlit:

streamlit run streamlit_app.py

For Flask:

python app.py



5. Access the app via http://localhost:8501 (Streamlit) or http://localhost:5000 (Flask)




---

🧠 How It Works

Model training: The CNN is trained on the PlantVillage dataset (~54,000 images across 38 categories), split into training and validation sets.

Inference:

1. User uploads a leaf photo via the web interface


2. The app preprocesses the image (resizing, normalization)


3. CNN predicts the class and outputs the top disease label with confidence


4. Result and prediction probabilities are displayed visually





---

📊 Performance

Achieved high accuracy during training and validation (typically > 90%)

Works best with clear, focused leaf images under good lighting

Future plans include improving robustness via more augmentation, balancing class distribution, and expanding the model's capacity



---

🎨 Screenshots


Leaf upload interface with disease status output


Prediction confidence dashboard

(Ensure screenshots are stored under /images and properly referenced in Markdown)


---

🧩 Future Enhancements

Mobile-friendly deployment (e.g., converting model to TensorFlow Lite)

Explainable AI using LIME or Grad-CAM for transparent predictions

Expanded dataset support: support for additional crops and disease classes

Recommendation engine: suggest treatments or care protocols based on detected diseases



---

🤝 Contributing

Contributions are welcome! Feel free to submit:

UI/UX improvements

Model optimization or architecture updates

Integration with external APIs (e.g. weather, farm management systems)

Bug fixes and documentation enhancements


✨ Contribution Steps

1. Fork the repository


2. Create a feature branch (git checkout -b new-feature)


3. Commit your changes


4. Push to your fork


5. Open a Pull Request with a clear description




---

📄 License

This project is released under the MIT License.


---

🏆 Acknowledgements

Inspiration from gokulnpc’s Plant-Disease-Prediction project 

Data and labels sourced from the PlantVillage dataset

Built with powerful tools: TensorFlow, Keras, Streamlit, and Flask



---

📬 Contact

Omotoso526 – Feel free to reach out for collaboration, questions, or enhancements!


---

Empowering farmers and gardeners with AI-driven plant health insights. 🌱

---

Let me know if you'd like adjustments (e.g. adding a Model Card, hosting instructions, or polished badges).3

