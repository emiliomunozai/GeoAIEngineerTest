GeoAI Engineer Technical Test
Overview
This technical test consists of three tasks designed to assess your ability to build AI-driven systems, automate information extraction, and apply computer vision techniques. You may use any programming language, AI tool, or platform you are comfortable with.

Task 1 – Automated Financial Report Extraction
Objective:
Build an AI or automation system to extract structured financial data from multiple annual reports.

Details:

Automate the sourcing and parsing of financial data from all reports available from 2021 to 2024 at:
https://torexgold.com/investors/financial-reports/

Consolidate this information into a single Excel file with a structured format, including key metrics such as revenue, cost, profit, etc.

The format of reports may vary over the years. Your system should include:

A fallback mechanism to handle missing or inconsistent fields.

A standardization process to ensure the Excel file has a consistent schema.

Implement a validation mechanism that:

Checks the completeness and accuracy of the extracted data.

Outputs a confidence or accuracy percentage, where 100% indicates a fully addressable report.

Task 2 – Image Extraction and Classification
Objective:
Use AI to extract and classify images from a document.

Details:

Given a document (file_XX.pdf), extract all embedded images using an AI model, tool, or any reliable method.

Automatically classify each image into one of two categories:

Map

Table

You may use multimodal models (e.g., Gemini, GPT-4 Vision, or others) or build your own logic to perform this classification.

Task 3 – Geospatial Computer Vision
Objective:
Extract coordinate data and relevant segments from imagery.

Details:

Analyze three provided geospatial images.

Identify and extract any coordinates present in the images (e.g., latitude/longitude).

Crop or segment the image based on those coordinates or geospatial features identified.

Submission Instructions
Create a public GitHub repository named:

nginx
Copiar
Editar
your_name_GeoAITest
With the following structure:

graphql
Copiar
Editar
your_name_GeoAITest/
│
├── task1/        # Code or notebook for Task 1
├── task2/        # Code or notebook for Task 2
├── task3/        # Code or notebook for Task 3
├── ppt/          # A brief presentation (max 6 slides)
└── README.md     # (Optional) Setup or explanation notes
Your presentation in ppt/ should:

Summarize your approach for each task

Highlight key results, tools used, and challenges

Demonstrate your technical decision-making
