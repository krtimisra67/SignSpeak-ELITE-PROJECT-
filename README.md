# SignSpeak-ELITE-PROJECT-
A real-time object detection and OCR pipeline using YOLO and Gemini API that not only detects and reads text from specific regions of images—but also speaks it out loud. Combines the power of YOLOv11 for detection, Gemini for intelligent text recognition, and text-to-speech to create a seamless "See → Read → Speak" experience.

# 📸 Gemini OCR - Object Detection & Text Recognition from Images

This project performs object detection on images, crops the detected regions, and extracts readable, natural-language text using **Gemini Pro Vision API**. Ideal for smart OCR use-cases, dark pattern detection, document parsing, and more!

---

## ✨ Features

- 🔍 Object Detection using YOLOv11s  
- ✂️ Automatic Cropping of Detected Regions  
- 🧠 OCR via Gemini Pro Vision API  
- 🗣️ Converts Extracted Text into Human-like Speech Text  
- 🎯 Clean Python Pipeline, Ready for Integration  

---

## 🖼️ Demo Flow

1. **Upload Image**  
2. **Detect Objects using YOLO**  
3. **Crop Detected Boxes**  
4. **Pass Cropped Regions to Gemini**  
5. **Extract & Speak Text**

---

## 🧪 Tech Stack

| Tool        | Purpose                  |
|-------------|---------------------------|
| `YOLOv11s`  | Object Detection          |
| `OpenCV`    | Image Processing & Cropping |
| `Google Gemini` | Vision-based Text Recognition |
| `PIL`       | Image Format Conversion   |
| `Colab` / Python | Execution Environment |

---

## ⚙️ Setup Instructions

### 🔧 1. Clone the Repo

```bash
git clone https://github.com/your-username/gemini-ocr.git
cd gemini-ocr
