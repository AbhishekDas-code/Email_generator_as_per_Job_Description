# 📧📮 Sales Mail Generator as per Job Description
Cold email generator for services company using groq, langchain and streamlit. It allows users to input the URL of a company's careers page. The tool then extracts job listings from that page and generates personalized cold emails. These emails include relevant portfolio links sourced from a vector database, based on the specific job descriptions. 

**Imagine a scenario:**

- Nike needs a Machine Learning Manager and is spending time and resources in the hiring process, on boarding, training etc
- ABC Software Company is Software Development company can provide a dedicated software development engineer to Nike. So, the business development executive (Abhishek) from ABC Software Company is going to reach out to Nike via a cold email.

## Set-up
1. To get started we first need to get an API_KEY from here: https://console.groq.com/keys. Inside `app/.env` update the value of `GROQ_API_KEY` with the API_KEY you created. 


2. To get started, first install the dependencies using:
    ```commandline
     pip install -r requirements.txt
    ```
   
3. Run the streamlit app:
   ```commandline
   streamlit run app/main.py
   ```
**NOTE:**
The job URL used in this scenario may be invalid after some time, kindly use other job URL for smooth functioning of code
   

**Additional Terms:**
Commercial use of this software is strictly prohibited without prior written permission from the author. Attribution must be given in all copies or substantial portions of the software.
