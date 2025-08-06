# 🧠 VisionX – Image Captioning and Segmentation

**VisionX** is a deep learning-based project that combines two powerful tasks:
1. **Image Captioning** – generating natural language descriptions of images.
2. **Image Segmentation** – identifying object regions at pixel-level.

---

## 🧩 Features

- 🔍 Object-level semantic segmentation
- ✍️ Automated caption generation using CNN + LSTM
- 📦 Modular and scalable codebase
- 🧪 Jupyter notebooks for experimentation

---

## 🛠️ Tech Stack

- Python
- PyTorch
- torchvision
- OpenCV
- Matplotlib, NumPy
- NLTK 
- Pretrained models: ResNet, UNet, LSTM, InceptionV3

---

## 🧑‍💻 Contributors

| Name              | Role                        |
|-------------------|-----------------------------|
| Manasvi           | Image Captioning Lead       |
| Sarthak           | Image Segmentation Lead     |

---

## 🗂️ Folder Structure

Refer to the "Project Structure" section for a detailed breakdown.

---
```bash

VisionX-CaptionSeg/
│
├── README.md
├── requirements.txt
├── data                     # Dataset directory
│   
├── notebooks/               # Jupyter notebooks
│   ├── captioning_demo.ipynb
│   └── segmentation_demo.ipynb
├── src/
│   ├── captioning/          # Captioning code
│   │   ├── model.py
│   │   ├── train.py
│   │   └── utils.py
│   ├── segmentation/        # Segmentation code
│   │   ├── unet.py
│   │   ├── train.py
│   │   └── utils.py
│   
└── outputs                  # Saved results

```

### 1. Clone the repo

```bash
git clone https://github.com/maansvi-0/VisionX-CaptionSeg.git
cd VisionX-CaptionSeg


