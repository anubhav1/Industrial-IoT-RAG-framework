# Industrial-IoT-RAG-framework

This code demonstrates a simple application where I will store old emails and publicly available data about energy companies' operations in Amazon Bedrock's Knowledge Bases. A user's prompt, augmented from the information retrieved from knowledge bases using RAG framework, results in more accurate, up-to-date, and comprehensive responses from the GenAI model.

![image](https://github.com/user-attachments/assets/8b891143-72a0-46f5-9847-577fc2a9911c)

# Requirements
- Python 3.12.x
- Ubunutu 24.x

# Commands
1. Install python dependecies
   
   ```pip3 install pip==24.0 && pip3 install -r setup/requirements.txt -U```

2. Write down your knowledge Base Id in `rag_back.py`
3. To run the app, type following command:
   
   ```streamlit run rag_front.py --server.port 8081```

4. Feel free to ask the following questions related to the pdfs in S3 data source.
