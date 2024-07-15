### Exploring-the-Employment-Landscape-in-the-Arab-World
_________________________________________________________________________________________________________________________________________________________________________________________________________
This repository contains the code and resources for an interactive dashboard that allows you to explore job postings across the Middle East, focusing on **Egypt, UAE, Saudi Arabia, Kuwait, and Qatar**.


![WhatsApp Image 2024-07-13 at 8 28 07 PM](https://github.com/user-attachments/assets/316e3d0d-2cca-4af4-94c6-19bc09b8f3c2)

### Features
_____________________________________________________________________________________________________________________________________________________________________________________________________
* Explore over **8,000** job postings: Gain insights into the job market landscape across the region.
* Filter by various criteria: Narrow your search by employment type **(full-time, contract, etc.), company size, country, and seniority level**.
* Identify in-demand skills: Discover the most sought-after **skills** by employers for targeted job searches.
* Drill down into specific jobs: Explore the skill requirements for individual job posting

### Data Source: Aggregating Insights from the Middle East's Job Market
_____________________________________________________________________________________________________________________________________________________________________________________________________
To capture a comprehensive picture of the job market across the Middle East, we leveraged the power of automation! This dashboard incorporates data meticulously scraped from leading hiring platforms like **Wuzzuf, LinkedIn, and Indeed**. Our custom `Python` script, utilizing the `Selenium` library, scoured these websites between March and June 2024, gathering over 8,000 job postings.

This approach allowed us to harvest valuable information from a diverse range of sources, ensuring a well-rounded perspective on job trends in Egypt, UAE, Saudi Arabia, Kuwait, and Qatar. By combining data from these prominent platforms, we can provide you with a richer and more insightful view of the current job landscape in the region.

### NLP Model: BERT
_____________________________________________________________________________________________________________________________________________________________________________________________________
This dashboard employs a custom skill extraction model built using the Transformers library and leveraging the power of BERT (Bidirectional Encoder Representations from Transformers). Our model analyzes job descriptions, meticulously identifying the most relevant skills employers are seeking. This allows the dashboard to provide you with highly accurate insights into the current skill demands across the Middle Eastern job market.
Hugging Face Link : https://huggingface.co/GalalEwida/LLM-BERT-Model-Based-Skills-Extraction-from-jobdescription 
