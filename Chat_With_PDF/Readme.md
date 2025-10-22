# Chat with PDF 

## Description.
Chat with PDF is a way to talk to lengthy PDFs. Here we will put the PDFs in certain formats in S3 Bucket and then in front end we will try to talk to PDF by asking some questions and expecting to get an answer from the PDF uploaded. 

## Concepts Used. 
Amazon Bedrock, RAG, Langchain, Streamlit, S3 Bucket, Docker, Titan Models, Python SDK. 

## Architecture Flowchart. 
<img src="Chat_With_PDF/Bedrock-ChatWithPdf.png" alt="Chat With PDF" width="400">

## Libraries/Modules/Frameworks used. 
1. Streamlit is an open-source Python library designed to simplify the creation and sharing of custom web applications, particularly for machine learning, data science, and general data analysis. It allows users to transform Python scripts into interactive web apps with minimal code, eliminating the need for extensive knowledge of front-end technologies like HTML, CSS, or JavaScript. 
2. Langchain Framework is an open-source framework designed to simplify the development of applications powered by large language models (LLMs). It provides tools and components that allow developers to build, integrate, and deploy AI systems capable of reasoning, retrieval, and dynamic interaction with external data sources
3. RecursiveCharacterTextSplitter is needed because when the statement or a paragraph ends it might be possible that the next paragraph also has some related context therefore we use this module. 

## Developer Instruction. 

## Contributor Expectation. 
