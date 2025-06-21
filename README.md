# ArSL-Mobile: Arabic Sign Language Recognition App 🤟📱🇪🇬

This repository contains our graduation project for recognizing *Arabic Sign Language (ArSL)* using deep learning models, 3D avatar visualization, and a mobile-based interface. The system is designed to bridge communication gaps for the Deaf and Hard-of-Hearing community.

---

## 🔍 Project Overview

- *Input*: Live or recorded hand gestures.
- *Output*: Arabic text + optional 3D avatar animation.
- *Platform*: Mobile app (Android)
- *Modules Used*:
  - 🧠 VGG16 model for static gesture recognition
  - 🔍 YOLOv10 for real-time hand tracking
  - 🤖 MediaPipe-based model (KarSL) for sequence detection
  - 🧱 Blender + Unity for 3D Avatar rendering

---

## 📁 Project Structure

| Folder/File       | Description |
|------------------|-------------|
| models/         | Trained models: VGG16, YOLOv10, MediaPipe |
| docs/           | Final report and documentation |
| presentation/   | Final project presentation |
| src/            | Source code (preprocessing, prediction, visualization) |
| demo/           | [Demo video link below 🔽](https://drive.google.com/file/d/1LMRk9N7-vqd7KeM2_cq8SQvBxDAkNdBH/view?usp=sharing) |

---

## 📽 Demo Video

You can view the full project demo here:  
🎥 [Watch Demo on Google Drive](https://drive.google.com/your-real-demo-link-here)

---

## 🧠 Models Description

- *VGG16*: Used for recognizing isolated signs.
- *YOLOv10*: Detects hand in real time to enable dynamic gesture recognition.
- *KarSL (MediaPipe)*: Custom gesture detection pipeline with temporal tracking.

---

## 🚀 Technologies Used

- *Python, **TensorFlow/Keras, **OpenCV*
- *Blender* for avatar animation
- *Unity* for avatar rendering (optional)
- *Android Studio / Java* for mobile interface
- *Google Drive* for deployment demo

---

## 📝 Documentation

- 📄 [Final Report (PDF)]([docs/your-doc-link.pdf](https://docs.google.com/document/d/1LO_vQUTEZL_v1J3De9CTEANo28H8U2IZ/edit?usp=sharing&ouid=116460896971091558315&rtpof=true&sd=true))
- 📊 [Presentation Slides (pptx)](https://docs.google.com/presentation/d/1LIy_rSNrzDbog-fIrrPJsLSa9jTNkw2Q/edit?usp=sharing&ouid=116460896971091558315&rtpof=true&sd=true)

---

## 📌 Notes

- Models are uploaded locally .
- If demo video you can view it using the Drive link.
- This project was submitted as a graduation project in the field of AI and Natural Language Understanding.

---
