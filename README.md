Resume Screening

This repository contains a machine learning project that automates the resume screening process using Python. The objective is to develop an efficient and accurate model capable of evaluating resumes based on predefined criteria.

<img src="Cover.png" alt="resume cover">
Table of Contents

Why Resume Screening?

Introduction

Modules & Libraries

Functionality

Tools & Technologies

Tech Innovations

Installation

Usage

Dataset

Model

Results

Contributing

License

Contact

Why Resume Screening?

Companies manually go through resumes, referrals, and applications for each recruitment cycle.

Large organizations receive thousands of resumes for a single job posting.

These resumes are categorized and forwarded to hiring teams.

Reviewing hundreds or thousands of resumes manually is extremely time-consuming.

To reduce manual effort, machine learning and NLP can automate screening and complete work that takes days in just a few minutes.

Introduction

Resume screening involves evaluating whether a candidate is suitable for a role based on their education, experience, skills, and other resume details.

It is essentially a pattern-matching process between job requirements and candidate qualifications.

The goal is simple:
➡️ Shortlist qualified candidates
➡️ Reject those who do not meet minimum requirements

Modules & Libraries
Modules

KNN: A supervised learning technique used for classification tasks. The "K" represents the number of nearest neighbors considered for making predictions.

NLP: Natural Language Processing helps computers analyze, understand, and derive meaning from human language.

Libraries

NumPy – Support for large multidimensional arrays and mathematical operations

Pandas – Data manipulation and analysis

Matplotlib – Creating graphs and visualizations

Seaborn – Statistical visualizations

SciPy – Scientific computing

Scikit-learn – Machine learning algorithms (classification, clustering, etc.)

NLTK – Text processing and natural language analysis

Functionality

The application screens resumes based on minimum and preferred qualifications such as:

Work experience

Education

Technical and soft skills

Competencies

Personality traits

These factors help evaluate candidate suitability for various job roles.

Tools & Technologies

Machine Learning

Artificial Intelligence

Text Mining

Natural Language Processing

Applicant Tracking System (ATS) concepts

These technologies automate the manual process of resume screening.

Tech Innovations

AI-based resume screening represents a new generation of recruitment tools.
These tools:

Reduce repetitive screening work

Integrate seamlessly with existing HR software

Enhance decision-making

Improve candidate filtering accuracy

This automation is transforming how companies manage hiring processes.

Installation

To get started, clone the repository and install dependencies.

git clone https://github.com/ujjawalanand851/Resume-Screening.git
cd Resume-Screening
pip install -r requirements.txt

Usage

Prepare your dataset of resumes

Preprocess data using the provided scripts

Train machine learning models

Use the trained model to screen new resumes

Detailed steps are available in the Jupyter notebooks.

Dataset

The dataset consists of resumes from various sources.
It is preprocessed to extract important features such as:

Skills

Experience

Education

Keywords

Profile information

Model

Multiple machine learning models are implemented, including:

Logistic Regression

Support Vector Machines

Random Forest

Neural Networks

Models are trained on labeled data to classify resumes as per defined categories.

Results

Model performance is evaluated using:

Accuracy

Precision

Recall

F1-score

Visual results and evaluation metrics are documented in the notebooks.

Contributing

Contributions are welcome!
For suggestions or improvements, feel free to open an issue or submit a pull request.

License

This project is licensed under the MIT License.
See the LICENSE file for details.

Contact

Ujjawal Anand
GitHub: ujjawalanand851
