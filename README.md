# FastAPIwithLangchain
Using FastAPI with Langchain as serializers to push in PDF Files to the system

Description - 
An API Framework containing an API that can be used to input and process a PDF File (only PDF supported for now) using various langchain serializers to test langchain as a PDF parser. 

How to run - 
Install the dependencies - 

pip install requirements.txt

You need to run 2 scripts given in this document as well - 
https://docs.google.com/document/d/1EgWAq3ySzN97KytKMOexndFF__XWxErW0PwQ3LxxRpk/edit

and to run the server run the command from FastAPI Folder: 

```
uvicorn app_core.app_core:app --reload
```

Then hit it over your local server: http://localhost:8000/docs#/default/create_upload_file_uploadfile__post

TestCases - 
Error Handling for wrong input of the pdf converter
<img width="1543" alt="Screenshot 2023-10-15 at 8 28 10 PM" src="https://github.com/Tanmay1108/FastAPIwithLangchain/assets/46091259/cc671c7e-b8b8-4d17-9d8d-9edb23f4a6f9">

Passed test case - 
<img width="1643" alt="Screenshot 2023-10-15 at 8 29 07 PM" src="https://github.com/Tanmay1108/FastAPIwithLangchain/assets/46091259/e8a5ec4f-dff7-4622-9a69-d1a271180f94">



UML DIAGRAM - ![FastAPI](https://github.com/Tanmay1108/FastAPIwithLangchain/assets/46091259/5d236ea5-873e-4808-9dcd-7a55e0a7f18e)
