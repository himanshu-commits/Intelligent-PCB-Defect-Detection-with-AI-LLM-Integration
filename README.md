
# **Intelligent PCB Defect Detection with AI & LLM Integration**

## **Project Overview**
This repository implements an **AI-powered PCB defect detection system** using **YOLOv8m** for anomaly detection. The system integrates **Llama-3.3-70b** to generate automated defect analysis reports. Additionally, it leverages **Groq's server** for high-performance computation and provides **PDF & audio report generation** using **gTTS** (Google Text-to-Speech).

**Key Features:**
- **98.2% Accuracy** in PCB defect detection using YOLOv8m.
- **Automated AI-generated defect analysis reports** with Llama-3.3-70b.
- **Efficient inference** powered by Groq's server.
- **PDF and audio-based reports** for user accessibility, generated with gTTS.

- ![pcb1_prediction](https://github.com/user-attachments/assets/0a4716aa-35e8-4873-8e73-d6e1a43e0fa1)


## **Installation**

### **1. Clone the repository**
```bash
git clone https://github.com/himanshu-commits/Intelligent-PCB-Defect-Detection-with-AI-LLM-Integration.git
cd Intelligent-PCB-Defect-Detection-with-AI-LLM-Integration
```
### **2. Set up the environment**
- Make sure you have **YOLOv8m** pre-trained weights.
- Ensure **Groq’s server** is accessible for model inference.
- Download the **Llama-3.3-70b** model from Hugging Face (or use a compatible model).

## **Usage**

### **1. Jupyter training Notebook Workflow**
To start the project, open the **Jupyter Notebook** file and run the cells sequentially. You can view and run the entire PCB defect detection workflow in the notebook.
```bash
jupyter notebook training-pcb-yolov8.ipynb
```
**2. Jupyter testing Notebook Workflow**
To test the project, open the **Jupyter Notebook** file and run the cells sequentially. You can view and run the entire PCB defect detection workflow in the notebook.
```bash
jupyter notebook final_testing-pcb-yolov8_with_llm_integration.ipynb
```

### **3. View generated files**
- The **PDF** report will be saved as .pdf format
- The **audio** report will be saved as an `.mp3` format

## **Technologies Used**
- **YOLOv8m** for object detection.
- **Llama-3.3-70b** for automated defect analysis reports.
- **Groq’s server** for fast model inference.
- **gTTS (Google Text-to-Speech)** for generating audio reports.

## **Acknowledgments**
- YOLOv8 for efficient object detection.
- Llama-3.3-70b for natural language processing.
- Groq for high-performance inference.
- gTTS for text-to-speech conversion.
