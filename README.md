# -Al-Driven-Object-Detection-using-Digital-Twin-Simulations
Develop a YOLOv8-based object detection model trained on synthetic data from Duality AI’s Falcon platform to accurately detect Toolbox, Oxygen Tank, and Fire Extinguisher in a space station environment under challenges like lighting, occlusion, and varied angles.
# AstroSight: AI-Driven Object Detection using Digital Twin Simulations

AstroSight is an advanced object detection system developed using YOLOv8 and synthetic data generated from Duality AI's Falcon simulation platform. The project was created as part of the Microsoft Hackathon to demonstrate real-time object detection in inaccessible environments like space stations.

---

## 🚀 Project Objective

To develop a robust YOLOv8-based model capable of detecting and classifying three mission-critical objects in a simulated space station environment:
- 🔧 Toolbox
- 🧯 Fire Extinguisher
- 🛢️ Oxygen Tank

The model was trained to perform well under challenges such as:
- Varying lighting conditions
- Occlusion and overlapping
- Multiple viewing angles and distances

---

## 📁 Folder Structure

- `dataset/` – Training, validation, and test data (YOLO format)
- `model/` – YOLOv8 configuration and best trained weights
- `scripts/` – Custom training and inference scripts
- `app/` – Bonus Streamlit app for real-time demo
- `runs/` – Training logs and results
- `submission/` – Final zipped folder for hackathon submission

---

## 🧠 Technologies Used

- Python
- YOLOv8 (Ultralytics)
- OpenCV
- Falcon Digital Twin Platform (Duality AI)
- Streamlit (Bonus App)
- Git & GitHub

---

## 🛠️ Setup Instructions

1. Clone the repository:
git clone https://github.com/teambugbusters00/AI-Driven-Object-Detection-using-Digital-Twin-Simulations.git
cd AI-Driven-Object-Detection-using-Digital-Twin-Simulations

cpp
Copy
Edit

2. (Optional) Create and activate a virtual environment:
python -m venv venv
.\venv\Scripts\activate # for Windows

markdown
Copy
Edit

3. Install dependencies:
pip install -r requirements.txt

markdown
Copy
Edit

4. Train the model:
python scripts/train.py --data dataset/data.yaml --cfg model/config.yaml --weights yolov8n.pt --epochs 50

markdown
Copy
Edit

5. Run inference:
python scripts/predict.py --weights model/best.pt --data dataset/data.yaml --split test

java
Copy
Edit

6. Launch the app (Bonus):
cd app
streamlit run app.py

yaml
Copy
Edit

---

## 📊 Performance

- Achieved **mAP@0.5: 0.786** on test set
- High precision and recall under simulated constraints

---

## 📈 Market Use Cases

- Real-time astronaut support in space missions
- Industrial safety systems for tool tracking
- Educational simulations using synthetic CV data
- AI model benchmarking in controlled environments

---

## 📩 Contact

Developed by Team BUG BUSTERS  
🔗 GitHub: https://github.com/teambugbusters00  
📧 Email: jopingvijay47@gmail.com

---

