
```📊 Case Study 5: Trainer Statistics

📖 Project Overview
This project analyzes trainer allocation and demand forecasting at ARICH, where trainers have diverse skill sets and backgrounds. Some trainers are in-house employees, while others are consultants.  

The objective is to:
- Allocate trainers to in-house and corporate training based on demand and duration.  
- Match skill sets of trainers with company requirements.  
- Assess training requirements fulfilled by in-house vs. consultant trainers.  
- Identify skill gaps and recommend up-skilling strategies.  



🗂️ Repository Structure

project-trainer-statistics/
│
├── docs/
│ ├── CASE STUDY 5 SOUMYA S.docx # Case study write-up
│ ├── Trainer stats.pdf # Case study description & instructions
│ └── Case Study 5 -Trainer Statistics.pptx # Presentation slides
│
├── data/
│ └── trainers.xlsx # Input dataset (Trainer, Companies, Allocation)
│
├── src/
│ └── analysis.py # Python script for data analysis & visualization
│
├── outputs/
│ └── images/ # Visualizations & charts generated
│
└── README.md # Project documentation



📂 Dataset Description
The data is collected in Excel sheets (`trainers.xlsx`) with the following components:

1. Trainer – Trainer Id, Name, Work Experience, Technologies, Employee Type, Total Batches.  
2. Companies – Company Id, Technology, Trainers Count, Expected Start Date, Duration.  
3. Trainer Allocation – Trainer Id, Company Id, Start Date, Technology, Status (Fulfilled/Unfulfilled).  


⚙️ Process & Methodology
The project follows the Data Science Lifecycle:

1. Business Understanding – Trainer allocation & demand prediction.  
2. Data Collection – Extract data from `trainers.xlsx`.  
3. Data Cleaning – Handle missing values, check integrity, format dates.  
4. Exploratory Data Analysis (EDA) – Work experience distribution, technology demand, trainer skill sets, fulfillment status.  
5. Model Building –  
   - Decision Tree  
   - Linear & Logistic Regression  
   - Cross-validation & accuracy evaluation  
6. Visualization – Using `Matplotlib`, `Seaborn`, and `Plotly`.  
7. Deployment – Case study insights consolidated into outputs.  



🛠️ Technology Stack
- Python  
- Libraries:  
  - pandas, numpy – Data manipulation  
  - matplotlib, seaborn – Visualization  
  - scikit-learn – Machine learning models  
  - scipy – Statistical analysis  



📊 Key Insights
- High demand for Data Science and Java Full Stack courses.  
- Emerging technologies like AI/ML and Cloud Computing are gaining traction.  
- Consultant trainers are preferred for niche/specialized training.  
- Skill gaps exist in Robotic Process Automation and Cloud Computing, requiring upskilling.  
- In-house trainers are best suited for long-term, ongoing programs.  



🚀 How to Run
1. Clone the repository:

   git clone https://github.com/username/project-trainer-statistics.git


2. Install dependencies:

   pip install -r requirements.txt
   
3. Run the analysis:

   python src/analysis.py
   
4. Outputs (charts & graphs) will be saved in:
   
   outputs/images/
```
   












