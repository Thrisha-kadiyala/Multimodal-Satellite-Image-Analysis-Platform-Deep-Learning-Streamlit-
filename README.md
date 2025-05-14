# Multimodal-Satellite-Image-Analysis-Platform-Deep-Learning-Streamlit-
🛰️ Multimodal Satellite Image Analysis using AI
 A powerful Streamlit-based application that leverages advanced deep learning models to analyze satellite images through Image Classification, Segmentation, and Landslide Detection.

 🚀 Features
 🌍 Interactive Map Interface
 Capture and analyze real-world satellite data by clicking directly on the map.

 🏷 Image Classification
 Classify land types using ViT, ResNet, and VGG models (e.g., Forest, Residential, River, etc.).

 🎭 Image Segmentation with YOLO
Detect and segment objects in satellite images pixel-by-pixel using YOLOv8.

🏔 Landslide Detection
Classify regions as landslide or non-landslide using a Vision Transformer (ViT) model.

📥 Multiple Input Modes

Upload satellite images manually
Select via interactive map
Enter latitude & longitude directly
🧠 Models Used
Model	Task	Role
ViT	Classification, Landslide	Captures global patterns & long-range dependencies
ResNet	Classification	Learns deep spatial features using residual connections
VGGNet	Classification	Learns textures and patterns using deep CNN layers
YOLOv8	Segmentation & Detection	Pixel-wise segmentation and bounding-box object detection
🛠️ Tech Stack
Frontend: Streamlit, Folium
Backend: Python
AI/ML: PyTorch, TensorFlow, OpenCV, YOLOv8
Tools: Selenium, Matplotlib, Seaborn
🖥 How to Run
🔧 Install Requirements
pip install -r requirements.txt
Run command in terminal
streamlit run home.py 


Languages
Jupyter Notebook
96.1%
 
Python
3.8%
 
CSS
0.1%
Footer
