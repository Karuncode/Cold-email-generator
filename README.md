# 📧 Cold Mail Generator

This Cold Email Generator is designed for service-based companies, leveraging Groq, LangChain, and Streamlit. It allows users to input the URL of a company’s careers page, extract job listings, and generate personalized cold emails. These emails are enriched with relevant portfolio links, sourced from a vector database, based on the specific job descriptions.

## **Use Case Scenario**

Imagine this scenario:

- **Tesla** is looking for a Senior Data Scientist, but their hiring process is time-consuming and resource-intensive.
- **ByteWorks**, a data analytics consulting firm, has a candidate who matches Tesla’s needs perfectly. A business development executive, **Sara**, from ByteWorks can use this tool to generate a personalized cold email targeted at Tesla, highlighting the expertise of the candidate and how they fit Tesla's specific job requirements.

This saves time for both ByteWorks and Tesla by cutting through the standard application process and presenting a ready solution.

![img.png](img.png)

## **Architecture Diagram**

![img.png](architecture.png)

## **Set-up**

1. **API Key**:  
   Obtain a Groq API key from [here](https://console.groq.com/keys). Update the `GROQ_API_KEY` value inside the `app/.env` file with the API key.

2. **Install dependencies**:  
   Run the following command to install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the app**:  
   Start the Streamlit app by running the following command:
   ```bash
   streamlit run app/main.py
   ```

