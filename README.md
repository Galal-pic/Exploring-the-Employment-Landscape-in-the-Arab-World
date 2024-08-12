### Exploring-the-Employment-Landscape-in-the-Arab-World
_________________________________________________________________________________________________________________________________________________________________________________________________________
This repository contains the code and resources for an interactive dashboard that allows you to explore job postings across the Middle East, focusing on **Egypt, UAE, Saudi Arabia, Kuwait, and Qatar**.


![1](https://github.com/user-attachments/assets/e6962e60-1538-4fb5-8a32-45ec8cad770f)
![2](https://github.com/user-attachments/assets/b2b559f6-385b-40f5-8feb-06710f7f952e)
![3](https://github.com/user-attachments/assets/257f4dcc-f291-444e-9231-2244405c3890)

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
Hugging Face Link: https://huggingface.co/GalalEwida/LLM-BERT-Model-Based-Skills-Extraction-from-jobdescription 
_____________________________________________________________________________________________________________________________________________________________________________________________________

## Key Insights:
Our latest analysis dives deep into the employment and financing landscape in Egypt, UAE, Saudi Arabia, Qatar, and Kuwait. Here are some of the key insights:
 * **Employment Types:**
 Full-Time Jobs: Dominant across all countries.
 Freelance & Remote Work: Notably present in Saudi Arabia and UAE.
 Contract Roles: Available in Qatar.
 
 * **In-Demand Job Titles:**
 Egypt: Software Engineers, Full Stack Developers.
 Saudi Arabia: Communications Engineers, Data Scientists.
 UAE: Business Analysts, Software Engineers.
 Kuwait: Research Analysts, Business Analysts.
 Qatar: Systems Product Managers.
 
 * **Key Skill Trends:**
 Software Development: High demand across all countries.
 Data Science: Growing rapidly, especially in Saudi Arabia and the UAE.
 Cybersecurity: Significant need in Saudi Arabia and UAE.
 Cloud Computing: Emerging importance, particularly in UAE.

* **Hiring Companies**
 Egypt: PwC leads the market.
 Saudi Arabia: Jadeer and Aramcoservices are top employers.
 UAE: Injazat is a major player.
 Kuwait: Intoude Foundation dominates.
 Qatar: Jobs Via Efinancialcareers and others are notable.

 * **Job Levels:**
 Mid-Level Roles: Predominant in Saudi Arabia and UAE.
 Balanced Distribution: Noted in Egypt across various seniority levels.
 Junior-Level Focus: Seen in Qatar and Kuwait.
 The report highlights the dynamic and evolving job market in the Middle East, driven by technological
 advancements and the growing importance of data-driven decision-making.
