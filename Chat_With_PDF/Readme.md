# Chat with PDF 

## Description.
Chat with PDF is a way to talk to lengthy PDFs. Here we will put the PDFs in certain formats in S3 Bucket and then in front end we will try to talk to PDF by asking some questions and expecting to get an answer from the PDF uploaded. 

## Concepts/Libraries/Frameworks used. 
1. Amazon Bedrock, RAG, Langchain, Streamlit, S3 Bucket, Docker, Titan Models, Python SDK. 
2. Streamlit is an open-source Python library designed to simplify the creation and sharing of custom web applications, particularly for machine learning, data science, and general data analysis. It allows users to transform Python scripts into interactive web apps with minimal code, eliminating the need for extensive knowledge of front-end technologies like HTML, CSS, or JavaScript. 
3. Langchain Framework is an open-source framework designed to simplify the development of applications powered by large language models (LLMs). It provides tools and components that allow developers to build, integrate, and deploy AI systems capable of reasoning, retrieval, and dynamic interaction with external data sources
4. RecursiveCharacterTextSplitter is needed because when the statement or a paragraph ends it might be possible that the next paragraph also has some related context therefore we use this module. 

## Architecture Flowchart. 
![Chat with PDF](Bedrock-ChatWithPdf.png)

## Developer Instruction. 
1. You have to host your Admin Site to upload the PDF is s3 bucket.
2. You have to host User Site to chat with PDF. 

## Contributor Expectation. 
In case of any bug or any new ideation that can enhance this. Please emailto: ashutosh1.kumar.ara@gmail.com
