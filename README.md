# GeoAI Engineer Technical Test

Welcome! This technical test is designed to evaluate your skills in automation, AI tooling, and geospatial analysis. It is divided into three independent tasks. You may use any programming language, tools, or AI models you are comfortable with.

---

## 📌 Overview

You will:
- Extract and standardize financial data from public reports.
- Use AI tools to extract and classify images.
- Apply computer vision techniques to detect coordinates in images.

---

## 📂 Tasks

### ✅ Task 1 – Automated Financial Report Extraction

**Goal:**  
Build a process to automatically extract financial data from company reports.

**Instructions:**
1. Go to the Torex Gold website:  
   [https://torexgold.com/investors/financial-reports/](https://torexgold.com/investors/financial-reports/)
2. Fetch all financial reports from **2021 to 2024**.
3. Extract relevant financial metrics (e.g., revenue, operating cost, EBITDA, etc.) into a single **Excel file**.
4. Reports may vary in format. Your solution must:
   - Include a **fallback mechanism** to handle missing or inconsistent data.
   - **Standardize** the output structure.
5. Implement a **validation mechanism** that shows a **% accuracy** score indicating how complete and reliable the extracted data is (100% = fully addressed).

---

### ✅ Task 2 – Image Extraction and Classification

**Goal:**  
Use AI tools to extract and categorize images from a document.

**Instructions:**
1. You will be provided with a document (`file_XX.pdf`).
2. Extract all images from this file.
3. Classify each image as either:
   - **Map**
   - **Table**
4. Use any AI model or image classification approach (e.g., OpenAI, Gemini, Vision Transformers, etc.).

---

### ✅ Task 3 – Geospatial Computer Vision

**Goal:**  
Apply computer vision to analyze geospatial images.

**Instructions:**
1. You will be given three images.
2. For each image:
   - Detect **any coordinate information** (e.g., latitude/longitude).
   - Extract the relevant **segment of the image** that contains or is associated with those coordinates.
3. You may use any OCR, image processing, or deep learning technique.

---

## 🚚 Submission Instructions

Please submit your solution as a **public GitHub repository** with the following structure:

your_name_GeoAITest/
│
├── task1/ # Notebook or code for Task 1
├── task2/ # Notebook or code for Task 2
├── task3/ # Notebook or code for Task 3
├── ppt/ # A brief presentation (max 6 slides)
└── README.md # (Optional) notes on your implementation

yaml
Copiar
Editar

### 📊 Presentation
In the `ppt/` folder, include a short presentation (maximum 6 slides) that explains:
- Your approach to each task
- Tools and models used
- Challenges and results

---

## ✅ Evaluation Criteria

We will assess:
- Clarity and modularity of your code
- Creativity and effectiveness of your approach
- Robustness of fallback mechanisms
- Accuracy and validation logic
- Clarity of communication in your presentation

---

Good luck, and feel free to reach out with any clarifying questions!
