### Tech Industry Job Market Analysis in the Middle Eas
____________________________________________________________________________________________________________________________________________________________________________________________________
This project provides an in-depth analysis of the tech job market across key regions in the Middle East, including **Egypt, Saudi Arabia, the United Arab Emirates, Kuwait, and Qatar**. The dashboard created in this project visualizes data related to job postings, seniority levels, job titles, and top hiring companies, offering valuable insights into current trends in the tech industry.

![1](https://github.com/user-attachments/assets/e6962e60-1538-4fb5-8a32-45ec8cad770f)
![2](https://github.com/user-attachments/assets/b2b559f6-385b-40f5-8feb-06710f7f952e)
![3](https://github.com/user-attachments/assets/257f4dcc-f291-444e-9231-2244405c3890)

### Data Source: Aggregating Insights from the Middle East's Job Market
_____________________________________________________________________________________________________________________________________________________________________________________________________
To capture a comprehensive picture of the job market across the Middle East, we leveraged the power of automation! This dashboard incorporates data meticulously scraped from leading hiring platforms like `Wuzzuf, LinkedIn, and Indeed`. Our custom Python script, utilizing the `Selenium` library, scoured these websites between March and June 2024, gathering over 9,000 job postings.
This approach allowed us to harvest valuable information from a diverse range of sources, ensuring a well-rounded perspective on job trends in Egypt, UAE, Saudi Arabia, Kuwait, and Qatar. By combining data from these prominent platforms, we provide a richer and more insightful view of the current job landscape in the region.

### Features
_____________________________________________________________________________________________________________________________________________________________________________________________________
* **Regional Analysis**: Breakdown of tech job opportunities by country, highlighting differences in demand across the Middle East.
* **Job Title Insights**: Identification of in-demand job roles in technology, including emerging fields like AI, data science, and cloud computing.
* **Seniority Distribution**: Analysis of job postings based on experience levels, from entry-level to executive positions.
* **Employment Type**: Comparison of demand for remote, on-site, and hybrid job roles across different regions.
* **Top Hiring Companies**: Visualization of the leading companies in the tech sector and their hiring trends.
* **Time Series Analysis**: Examination of how the job market has evolved, identifying trends and the impact of global events.

### NLP Model: BERT
_____________________________________________________________________________________________________________________________________________________________________________________________________
This dashboard employs a custom skill extraction model built using the Transformers library and leveraging the power of BERT (Bidirectional Encoder Representations from Transformers). Our model analyzes job descriptions, meticulously identifying the most relevant skills employers are seeking. This allows the dashboard to provide highly accurate insights into the current skill demands across the Middle Eastern job market.
The BERT model has been fine-tuned specifically for this task, enabling it to understand the nuances of job descriptions in the tech industry and extract the essential skills that employers are looking for. By integrating this model into our analysis pipeline, we can offer a data-driven perspective on skill trends and requirements, helping job seekers and recruiters alike to navigate the evolving job landscape.
You can access the model on Hugging Face via the following link:

Hugging Face Link: https://huggingface.co/GalalEwida/LLM-BERT-Model-Based-Skills-Extraction-from-jobdescription 

### Job Title Normalization using Sentence Transformers
_____________________________________________________________________________________________________________________________________________________________________________________________________
This dashboard incorporates an advanced job title normalization process to ensure consistency and accuracy in the analysis. We use a model built with the Sentence Transformers library, specifically leveraging the power of the "all-MiniLM-L6-v2" variant. This model transforms job titles into dense vector representations, enabling us to compare and align different job titles to a standardized set.
Our approach involves encoding both the target job title and a predefined list of standardized job titles into embeddings. We then calculate the cosine similarity between these embeddings to identify the closest match. If a match exceeds a certain similarity threshold, the target job title is replaced with the standardized version. This ensures that job titles with slight variations, such as "Data Analyst Marketing" and "Data Analyst," are recognized as equivalent, thus providing a more unified view of the job market.
By integrating this model into our dashboard, we can harmonize job titles from diverse sources, offering a more accurate and streamlined analysis of job trends across the Middle Eastern tech industry.


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
