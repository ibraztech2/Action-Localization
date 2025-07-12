# 🎬 Video Action Localization App
Video Action Localization App is a Streamlit-powered web interface that processes video input to detect and localize actions across frames using spatio-temporal deep learning models. It leverages MMAction2’s SlowFast-ACRN model for action recognition and Faster R-CNN for spatial localization.

A complete, Colab-ready solution for spatio-temporal action detection in videos, featuring:

✅ SlowFast-ACRN for action recognition
✅ Faster R-CNN for human/object detection
✅ Streamlit interface for interactivity
✅ Google Colab backend for GPU-powered inference

## 🚀 Quick Start
✅ Prerequisites
- A Google Colab account
- GPU runtime enabled in Colab (Runtime > Change runtime type > GPU)
- A free Ngrok account
- Your personal Ngrok Auth Token

## ✨ Features
- 📤 Upload .mp4, .avi, or .mov video files
- 🧠 Perform frame-wise action localization with SlowFast-ACRN
- 📥 Download annotated output video with bounding boxes and action labels

## 🧠 Model Architecture
Component	Description
Backbone	SlowFast Network with ACRN Head
Detector	Faster R-CNN (ResNet-50-FPN)
Trained On	Kinetics-400 Dataset

## 🛠️ Usage
This app is designed to run entirely in Google Colab, using GPU resources for efficient inference, while Streamlit provides the user interface.
- Run the notebook sequentially from top to bottom
- You may be prompted to restart runtime after dependency installations
- Once Ngrok tunnel is active, you'll get a public URL to access your Streamlit app

## 📁 Project Structure

├── Action_Localization.ipynb         # 🚀 Main Colab notebook for setup & execution
├── app.py                            # 💻 Streamlit app logic
├── checkpoints/                      # 🧠 Model weight files
│   ├── slowfast-acrn.pth             #    - Action recognition weights
│   └── faster_rcnn.pth              #    - Object detection weights
├── mmaction2/                        # 📦 MMAction2 framework (cloned repo)
│   ├── configs/                      #    - Model configuration files
│   ├── demo/                         #    - Sample media for testing
└── requirements.txt                  # 📌 Python dependencies

[Google colab](https://colab.research.google.com/drive/1_5k5CNtlGTmzqxFgkXAll-VXdB4l4KkJ#scrollTo=Uc_ZquyyK_Jk) 

👤 Author
Ibrahim Mustapha
Mechatronics Engineering Student | Computer Vision & AI Enthusiast
🔗 [GitHub](@ibraztech2)
🔗 [linkedin](https://www.linkedin.com/in/ibraztech)
📧 [Email](mustaphaibraz9@gmail.com)

