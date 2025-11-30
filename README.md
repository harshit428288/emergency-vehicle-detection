# Emergency Vehicle Detection

**Detects emergency vehicles (Ambulance, Fire Truck, Police Car) in images and assigns priority/wait-time cues for traffic systems.**

This project uses a YOLO pre-trained model that was fine-tuned on a Roboflow dataset in Google Colab. The model draws bounding boxes, displays class labels and confidence scores, shows processed images, and also detects other vehicles so the system can estimate priority / wait-time according to vehicle type.

---

## 🚀 Features
- Detects **Ambulance**, **Fire Truck**, and **Police Car** in images.
- Draws **bounding boxes** and **class labels** on detected objects.
- Shows **confidence scores** for each detection.
- Displays processed image with overlays.
- Detects other vehicles (cars, bikes, trucks) as context for traffic-priority decisions.
- Simple logic to **suggest priority / estimated wait-time** for detected emergency vehicles (configurable rule-based approach).

---

## 🛠️ Tech stack
- **Model:** YOLO (pre-trained, fine-tuned)
- **Environment / Notebook:** Google Colab
- **Libraries:** Python, OpenCV, NumPy, (Ultralytics YOLO or PyTorch implementation)
- **Dataset:** Custom dataset exported from **Roboflow**

---

## 📁 Repository structure (suggested)
