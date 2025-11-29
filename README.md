# Iris Flower Classifier 🌸

[![Streamlit](https://img.shields.io/badge/Streamlit-Live%20App-red)](https://your-app-link.streamlit.app)
[![Python](https://img.shields.io/badge/Python-3.9%2B-blue)](https://python.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Made with ❤️](https://img.shields.io/badge/Made%20with-%E2%9D%A4%EF%B8%8F-red)](#)

> A fun and interactive **Streamlit web app** that classifies Iris flowers (Setosa, Versicolor, Virginica) using a trained Machine Learning model — just move the sliders and see the magic!  
> Perfect for beginners, AI talks, workshops, or showing off ML in minutes.

![Demo GIF](demo.gif)
<!-- Replace with your actual GIF later -->

## Live Demo
Try it now: [https://iris-classifier-amit.streamlit.app](https://iris-classifier-amit.streamlit.app) *(Deploy for free on Streamlit Community Cloud!)*

## Features
- Interactive sliders for Sepal & Petal measurements
- Real-time prediction with a pre-trained ML model
- Beautiful flower image display based on prediction
- Super beginner-friendly — no code needed to use!
- 100% open source & easy to customize

## Screenshots

| Input Sliders                  | Prediction + Image              |
|--------------------------------|---------------------------------|
| ![Sliders](images/screenshot1.png) | ![Result](images/screenshot2.png) |

## How It Works
1. You adjust the four flower measurements using sliders
2. Click **"Predict type of Iris"**
3. The model instantly predicts the species
4. A real photo of the predicted flower appears!

### Supported Species
- **Iris Setosa**
- **Iris Versicolor**
- **Iris Virginica**

## Quick Start (Run Locally)

```bash
git clone https://github.com/Amit3729/iris-classifier.git
cd iris-classifier
pip install -r requirements.txt
streamlit run app.py
