# GCI-World-2026 Course Repository

![GCI World](https://img.shields.io/badge/GCI-World_2026-blue)
![Python](https://img.shields.io/badge/Python-3.10%2B-yellow)
![License](https://img.shields.io/badge/License-MIT-green)

This repository contains the complete curriculum, lecture materials, exercises, datasets, and resources for the **GCI-World-2026** Data Science and Machine Learning course, offered by Matsuo-Iwasawa Laboratory, The University of Tokyo.

The structure follows top-tier academic repository standards (similar to MIT/Oxford OpenCourseWare) to ensure clarity, reusability, and professional workflow standards.

---

## 📖 Course Overview

The curriculum is designed to take you through the complete data science workflow:

1.  **Understanding Data:** Basics of statistics, data types, and visualization.
2.  **Processing Data:** Cleaning, handling missing values, and feature engineering.
3.  **Building a Model:** Introduction to supervised and unsupervised learning.
4.  **Evaluating a Model:** Key metrics and model validation techniques.

The course covers essential Python libraries such as **NumPy, Pandas, Matplotlib, Seaborn, and Scikit-learn**, alongside foundational concepts in statistics, SQL, and machine learning. It concludes with practical exercises, a competition, and a final assignment.

---

## 🗓️ Course Schedule

The course runs from **September to December 2026**. Below is a summary of the key milestones:

| Phase | Dates | Topics |
| :--- | :--- | :--- |
| **Pre-Lecture** | July 31 – Sept 9 | Python Basics, Statistics, ML Intro |
| **Core Lectures** | Sept 17 – Dec 17 | Data Science, Numpy, Pandas, Matplotlib, Supervised/Unsupervised Learning, SQL, etc. |
| **Final Assignment** | Deadline: Nov 26 | Competition & Final Project |

For a detailed roadmap, see `00_Course_Information/student_guide.pdf`.

---

## 📂 Repository Architecture

```text
GCI-World-2026/
│
├── README.md                           # Course overview, prerequisites, and setup instructions
├── .gitignore                          # Standard Python/Jupyter notebook cache filters
├── LICENSE                             # MIT License (Academic & open-source sharing)
├── requirements.txt                    # Core dependencies (NumPy, Pandas, Matplotlib, Scikit-Learn)
│
├── 00_Course_Information/              # Administrative and onboarding guides
│   ├── student_guide.pdf               # Syllabus, grading policy, and timelines
│   ├── how_to_use_omnicampus.pdf       # Platform navigation guide
│   ├── how_to_use_google_colab.pdf     # Cloud environment setup for Python notebooks
│   ├── how_to_submit_homework.pdf      # Git/Platform assignment submission workflow
│   └── guidelines_generative_ai_citation_integrity.pdf  # Academic integrity policy
│
├── 01_Pre_Lecture/                     # Foundational prep-work before core sessions
│   ├── 00_Opening/
│   │   ├── prep0_slides.pdf
│   │   └── prep0_lecture_video.txt
│   ├── 01_What_is_Data_Science/
│   │   ├── prep1_slides.pdf
│   │   └── prep1_lecture_video.txt
│   ├── 02_Basics_of_Python/
│   │   └── prep2_lecture_video.txt
│   ├── 03_Basics_of_Statistics/
│   │   ├── prep3_slides.pdf
│   │   └── prep3_lecture_video.txt
│   └── 04_What_is_Machine_Learning/
│       ├── prep4_slides.pdf
│       └── prep4_lecture_video.txt
│
├── 02_Core_Lectures/                   # Main course modular lectures
│   ├── 01_Introduction_to_Data_Science/
│   │   └── lecture_slides.pdf
│   ├── 02_Manipulating_Data_Using_Numpy/
│   │   └── lecture_slides.pdf
│   ├── 03_Cleaning_Data_Using_Pandas/
│   │   └── lecture_slides.pdf
│   ├── 04_Visualizing_Data_Using_Matplotlib/
│   │   └── lecture_slides.pdf
│   ├── 05_Supervised_Learning/
│   │   └── lecture_slides.pdf
│   ├── 06_Model_Evaluation/
│   │   └── lecture_slides.pdf
│   ├── 07_Competition_Final_Assignment_Tutorial/
│   │   └── lecture_slides.pdf
│   ├── 08_Feature_Engineering/
│   │   └── lecture_slides.pdf
│   ├── 09_Marketing_and_Data_Science/
│   │   └── lecture_slides.pdf
│   ├── 10_SQL/
│   │   └── lecture_slides.pdf
│   ├── 11_Unsupervised_Learning/
│   │   └── lecture_slides.pdf
│   ├── 12_Time_Series_Analysis/
│   │   └── lecture_slides.pdf
│   ├── 13_Guest_Session/
│   │   └── guest_speaker_notes.md
│   └── 14_Special_Contents/
│       └── advanced_topics_reading.md
│
├── 03_Exercises_and_Assignments/       # Code-along exercises and practical labs
│   ├── classification/
│   │   └── exercise_classification_lvl0.ipynb
│   └── regression/
│       └── exercise_regression_lvl0.ipynb
│
├── 04_Data/                            # Centralized repository storage for datasets
│   ├── raw/                            # Immutable raw data assets
│   │   ├── car_price_data.csv
│   │   └── classification_practice.csv
│   └── processed/                      # Transformed data targets for practice
│       ├── regression_lvl1_practice.csv
│       ├── regression_lvl2_practice.csv
│       └── regression_lvl3_practice.csv
│
└── 05_Solutions/                       # Self-evaluation notebooks and reference keys
    └── README.md                       # Guide to running verification tests

🚀 Environment Setup & Installation

To run the course notebooks locally, ensure you have Python 3.10+ installed, then execute:

```bash
# 1. Clone the repository
git clone https://github.com/your-username/GCI-World-2026.git
cd GCI-World-2026

# 2. Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

# 3. Install all required library dependencies
pip install -r requirements.txt
```

After installation, you can launch Jupyter Notebook or JupyterLab:

```bash
jupyter notebook
# or
jupyter lab
```

---

📦 Dependencies

All required Python libraries are listed in requirements.txt. The core dependencies include:

Category Libraries
Core Data Analysis numpy, pandas
Data Visualization matplotlib, seaborn
Machine Learning scikit-learn, scipy
Database Connectivity sqlalchemy, ipython-sql
Interactive Environment notebook, ipykernel

---

⚠️ Academic Integrity & Generative AI Policy

This course has a strict policy on academic integrity and the use of Generative AI tools. Please review the guidelines_generative_ai_citation_integrity.pdf in 00_Course_Information/.

Key Points:

· Responsibility: You are responsible for the accuracy of any AI-generated output.
· Purpose: The goal is learning. Submitting raw AI output as your homework is a violation.
· Plagiarism: All external sources must be properly cited.
· Sharing: Do not share your final assignment or competition code.

---

🔗 Useful Links

· Omnicampus Portal: https://edu.omnicampus.us/en/courses/170/
· GCI World Calendar: Google Calendar

---

📬 Contact

For any questions, please refer to the "Contact Us" page on the Omnicampus portal or the instructor contact information provided there.

---

⚖️ License

Distributed under the MIT License. See LICENSE for details.

---

This repository is for personal educational use only. All course materials are the property of Matsuo-Iwasawa Laboratory, The University of Tokyo.
