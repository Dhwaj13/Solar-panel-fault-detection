☀️ Solar Panel Fault Detection using VGG16

📌 Overview

This project implements a fault detection system for solar panels using Deep Learning (VGG16 Transfer Learning).
The model classifies solar panel images into categories such as:
	•	✅ Clean
	•	🐦 Bird-drop
	•	🌫️ Dusty
	•	❄️ Snow-Covered
	•	⚡ Electrical Damage
	•	🔨 Physical Damage

The entire project was developed in Google Colab and trained using image datasets of solar panels.

⸻

⚡ Features
	•	🖼️ Automatic Fault Detection from images
	•	🧠 VGG16 Transfer Learning for efficient feature extraction
	•	📊 Visualization of training/validation accuracy and loss
	•	✅ Evaluation with true vs predicted results

⸻

📂 Project Structure
📦 Solar-Fault-Detection

 ┣ 📜 solar fault detection.ipynb   # Main Colab Notebook
 
 ┣ 📜 README.md                     # Project documentation
 
 ┣ 📂 images/                       # Screenshots & results
 
 ┃ ┣ DATABASE.png

 ┃ ┣ RESULT.png
 
 ┃ ┣ TRUE VS PREDICTED.png
 
 ┃ ┣ VARIATION GRAPHS.png
 
 ┗ 📂 fault solar.zip               # Dataset (optional, or add dataset link)
 
▶️ Run in Google Colab

You can directly run the notebook in Colab:
🛠️ Tech Stack
	•	Python
	•	Google Colab
	•	TensorFlow / Keras
	•	VGG16 Pretrained CNN
	•	Matplotlib, Seaborn

⸻

📊 Results
	•	Achieved ~95% training accuracy and ~83% validation accuracy
	•	Model successfully detects multiple fault types in solar panels
	•	Visual comparisons of predicted vs actual labels

⸻
