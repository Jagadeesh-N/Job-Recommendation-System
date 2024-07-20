# Advanced Job Recommendation System

## Overview
The Job Recommendation System is designed to enhance the job search experience by leveraging content-based filtering techniques combined with Natural Language Processing (NLP) and the Word2Vec model. This approach ensures a personalized job matching process by analyzing user resumes and job postings to provide relevant job recommendations based on skills and location preferences. Additionally, the system suggests job opportunities aligned with users' aspirations to acquire new skills.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Data Acquisition Methods](#data-acquisition-methods)
- [Key Methodologies and Technologies Used](#key-methodologies-and-technologies-used)
- [System Design and Implementation Details](#system-design-and-implementation-details)
- [Performance Optimization and Validation](#performance-optimization-and-validation)
- [User-Centric Features](#user-centric-features)
- [Results](#results)
- [Future Enhancements](#future-enhancements)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features
- **Content-Based Filtering**: Matches jobs with users based on extracted skills and preferences.
- **NLP and Word2Vec**: Transforms textual data into vectors for precise matching.
- **Cosine Similarity**: Measures similarity between user skills and job requirements.
- **Professional Growth Recommendations**: Suggests additional job opportunities based on new skill acquisition.

## Data Acquisition Methods
### Job Posting Data
- **Initial Approach**: Web scraping from LinkedIn using Beautiful Soup.
- **Final Approach**: Utilized Octoparse to gather approximately 3,684 job postings, including job titles, descriptions, company details, and locations.

### User Data
- Extracted skills from user resumes using predefined skill lists and NLP techniques.

## Key Methodologies and Technologies Used
- **Content-Based Filtering**: Creating user and item profiles based on features.
- **SpaCy**: For extracting skills from resumes using pattern-based token matching.
- **Word2Vec**: Converts skills into 100-dimensional vectors for analysis.
- **Cosine Similarity**: Calculates similarity scores for skills and locations.

## System Design and Implementation Details
- **Data Collection and Preprocessing**: Standardized job posting data, extracted and processed skills from resumes.
- **Skill Extraction**: Used SpaCy and PdfReader to convert resumes into analyzable text.
- **Vectorization**: Used Word2Vec to create vector representations of skills.
- **Similarity Calculation**: Combined skill and location similarity scores for job recommendations.

## Performance Optimization and Validation
- **Evaluation Metric**: Precision was the primary metric for evaluating recommendation accuracy.
- **Precision Score**: Achieved an overall precision of 82% in job matching.

## User-Centric Features
- **Skill-Based Recommendations**: Focused on aligning user skills with job requirements.
- **Location Preferences**: Enhanced relevance by incorporating location preferences.
- **Professional Growth**: Suggested additional jobs based on users' willingness to acquire new skills.

## Results
- Demonstrated high precision in job matching, providing relevant job opportunities based on user skills and location preferences.
- Successfully recommended jobs to users, including suggestions for new skills and related job opportunities.

## Future Enhancements
- **Collaborative Filtering and Hybrid Methods**: Integrate user-job interaction data to refine recommendations.
- **Specialized Corpus**: Develop a domain-specific set of words to improve skill representation accuracy.
- **Dynamic Recommendations**: Adapt to changing user preferences and include additional factors such as company size and industry-specific requirements.
- **Feedback Loop**: Allow users to provide input on recommendations to continuously improve the algorithm.
- **Scalability**: Ensure efficient handling of larger datasets and support multiple languages.

## Installation
To install and run the Job Recommendation System locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/job-recommendation-system.git
   cd job-recommendation-system
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:
   ```bash
   python main.py
   ```

## Usage
1. Prepare your dataset and place it in the `data` directory.
2. Run the preprocessing script to clean and prepare the data:
   ```bash
   python preprocess.py
   ```
3. Execute the recommendation script to generate job recommendations:
   ```bash
   python recommend.py
   ```
