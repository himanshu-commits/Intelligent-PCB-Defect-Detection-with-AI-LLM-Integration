
# **Intelligent PCB Defect Detection with AI & LLM Integration**

## **Project Overview**
This repository implements an **AI-powered PCB defect detection system** using **YOLOv8m** for anomaly detection. The system integrates **Llama-3.3-70b** to generate automated defect analysis reports. Additionally, it leverages **Groq's server** for high-performance computation and provides **PDF & audio report generation** using **gTTS** (Google Text-to-Speech).

**Key Features:**
- **98.2% Accuracy** in PCB defect detection using YOLOv8m.
- **Automated AI-generated defect analysis reports** with Llama-3.3-70b.
- **Efficient inference** powered by Groq's server.
- **PDF and audio-based reports** for user accessibility, generated with gTTS.

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

### **1. Jupyter Notebook Workflow**
To start the project, open the **Jupyter Notebook** file and run the cells sequentially. You can view and run the entire PCB defect detection workflow in the notebook.
```bash
jupyter notebook Intelligent_PCB_Defect_Detection.ipynb
```

### **2. Run defect detection**
Within the notebook, use the following code to start defect detection:
```python
# Example usage in notebook
defect_image_path = "path_to_pcb_image"
detect_defects(defect_image_path)
```

### **3. Generate reports**
To generate defect reports (both **PDF** and **audio**):
```python
# Example usage in notebook
generate_report(defect_image_path)
```

### **4. View generated files**
- The **PDF** report will be saved in the `reports/` directory.
- The **audio** report will be saved as an `.mp3` file in the same directory.

## **Project Structure**
```
/Intelligent-PCB-Defect-Detection-with-AI-LLM-Integration
│
├── Intelligent_PCB_Defect_Detection.ipynb  # Jupyter Notebook for defect detection and report generation
├── requirements.txt         # List of required libraries
├── /models                  # Directory to store model weights
├── /reports                 # Directory for generated reports
└── README.md                # Project documentation
```

## **Technologies Used**
- **YOLOv8m** for object detection.
- **Llama-3.3-70b** for automated defect analysis reports.
- **Groq’s server** for fast model inference.
- **gTTS (Google Text-to-Speech)** for generating audio reports.

## **License**
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## **Acknowledgments**
- YOLOv8 for efficient object detection.
- Llama-3.3-70b for natural language processing.
- Groq for high-performance inference.
- gTTS for text-to-speech conversion.

---

Make sure to update the `git clone` URL to match your repository. Also, if the Jupyter notebook has a different name, change it in the README.

Let me know if you'd like any more tweaks!
