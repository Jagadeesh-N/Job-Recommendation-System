# Job Recommendation System Using Content-Based Filtering

## Introduction
The job market is highly competitive, making it challenging for job seekers to find positions that match their skills and career aspirations. This project addresses this challenge by developing a job recommendation system based on content-based filtering. By leveraging advanced Natural Language Processing (NLP) techniques, the Word2Vec model, and cosine similarity, the system provides precise and relevant job recommendations tailored to individual users.

## Dataset
The dataset for this project comprises job postings scraped from LinkedIn using Octoparse. It includes detailed information about job titles, descriptions, required skills, and other relevant attributes. Additionally, user resumes were processed to extract skills using NLP techniques. The final dataset used for training and evaluation contains over 3,684 job postings and hundreds of predefined user skills.

## Tools and Libraries
- **Python**: The primary programming language used for development.
- **SpaCy**: An NLP library used for skill extraction from resumes.
- **Word2Vec**: A model for converting textual data into vectors.
- **Cosine Similarity**: An algorithm for measuring the similarity between user skills and job requirements.
- **Octoparse**: A web scraping tool used for collecting job postings from LinkedIn.
- **Pandas**: A library for data manipulation and analysis.
- **Jupyter Notebooks**: For developing and documenting the project.

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

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/Jagadeesh-N/Job-Recommendation-System-Using-Content-Based-Filtering.git
   ```
2. Navigate to the project directory:
   ```bash
   cd job-recommendation-system
   ```
3. Run the Script:
   ```
   The model is in the ipynb file,execute the ipynb file using jupyter notebook or upload the file in google collaborator 
   ```
   
## Results
The system achieved a precision rate of 82%, demonstrating its effectiveness in matching users with suitable job opportunities based on their skills.
