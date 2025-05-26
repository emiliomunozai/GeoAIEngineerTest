# GeoAI Engineer Technical Test

Welcome! This technical test is designed to evaluate your skills in automation, AI tooling, and geospatial analysis. It is divided into three independent tasks. You may use any programming language, tools, or AI models you are comfortable with. Using already existing algorithms or programs for any task is a valid approach if it is well documented, you dont need to program everything from 0.

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
3. Extract the metrics that allow you to build this two tables in a Quaterly basis with anual summaries.
<img width="693" alt="image" src="https://github.com/user-attachments/assets/bacd4614-dfba-497f-b3dc-413c23ee7754" />

4. Reports may vary in format. Your solution must:
   - Include a **fallback mechanism** to handle missing or inconsistent data. (Saying not found is a good answer)
   - **Standardize** the output structure.
5. Implement a **validation mechanism** that shows a **% accuracy** score indicating how complete and reliable the extracted data is (100% = fully addressed).

---

### ✅ Task 2 – Image Extraction and Classification

**Goal:**  
Use AI tools to extract and categorize images from a document.

**Instructions:**
1. Using this report https://d1vqu5ynjuwmto.cloudfront.net/assets/files/10526/q4_2023_txg_ep.pdf
2. Create a process that:
   - Extract all images from the file or a new file and
   - Classify each image as either:
   - **Map**
   - **Table**
   - **Picture**
Use any AI or tool you consider model or image classification approach (e.g., OpenAI, Gemini, Vision Transformers, etc.).

---

### ✅ Task 3 – Geospatial Computer Vision

**Goal:**  
Apply computer vision to analyze the previously source maps.

**Instructions:**
1. For each image/map:
   - Detect **any coordinate information** (e.g., latitude/longitude).
   - Extract the relevant **segment of the image** that contains or is associated with those coordinates.

You may use any OCR, image processing, or deep learning technique.

---

## 🚚 Submission Instructions

Please submit your solution as a **public GitHub repository** with the following structure:\

your_name_GeoAITest/\
│\
├── task1 / # Notebook or code for Task 1\
├── task2 / # Notebook or code for Task 2\
├── task3 / # Notebook or code for Task 3\
├── .ppt # A brief presentation (max 6 slides)\
└── README.md # (Optional) notes on your implementation\


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
