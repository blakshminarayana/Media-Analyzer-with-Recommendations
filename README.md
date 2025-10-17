# 🎥 Full Media Analyzer with Recommendations

This project performs **comprehensive analysis of images and videos** using AI models.  
It detects objects, faces, explicit content, generates captions, hashtags, and even provides **media recommendations** based on similarity.

## 🚀 Features
- Object detection (YOLOv8)
- Scene classification (CLIP)
- Image captioning (ViT-GPT2)
- Face analysis (DeepFace)
- NSFW/Explicit content detection
- Media similarity recommendations
- Works for both dataset and external uploads

## 🧠 Models Used
- **YOLOv8** – Object detection  
- **CLIP (OpenAI)** – Scene classification & embeddings  
- **ViT-GPT2** – Caption generation  
- **DeepFace** – Age & gender analysis  
- **NSFW Detector** – Explicit content safety filter  

## 📂 Folder Structure
Full-Media-Analyzer/
├── main.ipynb
├── requirements.txt
├── README.md
├── dataset/
│ ├── Images/
│ └── Videos/
└── samples/

bash
Copy code

## ⚙️ Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/Full-Media-Analyzer.git
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Run the notebook (main.ipynb) in Jupyter or Google Colab.

📊 Example Output
Objects Detected: Person, Car, Dog

Caption: "A man walking a dog beside a car"

Hashtags: #person #walking #dog #car

NSFW Status: Safe Photo (Probability: 0.98)

Recommendations: Shows top 3 similar media