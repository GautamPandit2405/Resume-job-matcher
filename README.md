# Resume-to-Job Description Matcher

## Project Overview
This project compares resume text with a job description using Python, TF-IDF, and cosine similarity. It identifies overlapping keywords and potential skill gaps to support resume review.

## Objectives
- Clean and preprocess resume and job-description text.
- Convert text into numerical features using TF-IDF.
- Calculate cosine similarity between the two texts.
- Identify matching skills and potential skill gaps.
- Generate a readable matching report.

## Tools and Technologies
- Python
- Pandas
- scikit-learn
- TF-IDF
- Cosine Similarity
- Google Colab

## Features
- Text cleaning and preprocessing
- Resume–job similarity score
- Matching skill identification
- Potential skill-gap detection
- Automated report generation

## Repository Structure
- `notebooks/` — Python notebook containing the matching workflow
- `README.md` — Project documentation

## How to Run
1. Open `notebooks/resume_job_matcher.ipynb` in Google Colab.
2. Run the notebook cells in order.
3. Review the similarity score, matching skills, and potential skill gaps.

## Methodology
TF-IDF converts text into weighted numerical features. Cosine similarity compares the resulting text vectors. A separate keyword-based check identifies skills that appear in both the resume and job description.

## Limitations
The similarity score measures textual similarity, not the probability of being hired. Keyword matching may miss synonyms, context, and demonstrated proficiency. The tool does not validate the accuracy of resume claims.

## Responsible Use
Use the output as a starting point for manual review. It should not be used as an automated hiring decision or as the sole basis for evaluating a candidate.
