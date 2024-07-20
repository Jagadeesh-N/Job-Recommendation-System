# Job Recommendation System Using Content-Based Filtering

## Overview
This project aims to enhance the job-seeking experience by developing a content-based job recommendation system. Utilizing advanced Natural Language Processing (NLP) techniques, the Word2Vec model, and cosine similarity, the system matches job postings with user skills, ensuring precise and relevant job recommendations.

## Features
- **Data Collection**: Scrapes job postings from LinkedIn using Octoparse.
- **Data Preprocessing**: Standardizes and cleans the dataset for consistency.
- **Skill Extraction**: Uses SpaCy to accurately extract user skills from resumes.
- **Model Implementation**: Employs Word2Vec to convert text to vectors and cosine similarity to match user skills with job requirements.
- **Evaluation**: Measures system performance with precision evaluation to ensure accuracy in recommendations.

## Project Structure
- **data/**: Contains datasets including scraped job postings and standardized data files.
- **code/**: Jupyter notebooks with step-by-step project development and experimentation.
- **README.md**: Project documentation.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Jagadeesh-N/Job-Recommendation-System-Using-Content-Based-Filtering.git
   ```
2. Navigate to the project directory:
   ```bash
   cd job-recommendation-system
   ```
3. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage


## Results
The system achieved a precision rate of 82%, demonstrating its effectiveness in matching users with suitable job opportunities based on their skills.
