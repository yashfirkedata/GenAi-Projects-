# **Translator Chatbot**
Application using Open Source Models using groq api and api-deployment using langserve

**Used:**
* Langchain Expression Language
* ChatPromptTemplate
* Output Parsers
* API development using Langserve and Fastapi

### **Steps:**
1. Clone the repository 
2. Install requirements
3. Setup .env file with your GROQ_API_KEY

4. Run main.py
```
python main.py
```
5. Capture the api using Postman or ThunderClient
```
Postman >> Post request http://localhost:8080/chain/batch >> body >> raw >> json
```
```
{
  "inputs": [
    {
      "language": "string",
      "text": "string"
    }
  ],
  "config": {},
  "kwargs": {}
}
``` 

**You can go to http://localhost:8080/docs to check all functionalities available.**
