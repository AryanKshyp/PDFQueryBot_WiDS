# PDFQueryBot - A Chatbot over PDF using RAG

## Objective
Implement a chatbot that can answer the questions specific to any PDF.

## Description
Use any Large Language Model to create a basic chatbot that takes a PDF as argument and return answer based on the context from the pdf.
You can access the PDF from your folder, no need to integrate upload mechanism in the app.
Use [**UG Rulebook**](https://www.iitb.ac.in/newacadhome/ugrulebook.pdf) to test your chat bot.

## Structure
- LLM model initialization
- Pdf loading and parsing
- Text splitter
- Vector database
- Searching and passing the context to the prompt
- Custom prompt passing to the model and processing the output
- Displaying output using UI
- Optional: Evaluate how the LLM is doing and identify quantifiable metrics for that

## Deliverables
No need to make a very complex chatbot. 
- A python script or a github repo or a Jupyter notebook or a colab notebook with the code.
- The code should have a basic UI either in Streamlit/Gradio or just a python one.

## Resources 

- **GOOGLE**
- Youtube
- Chatgpt too, but sadly that will not be much of a help in case of langchain issues.

## Tips and advices

- You are free to use any other LLM you can find. Recommendation: Use Llama-2 7b parameter model using HuggingFace for simple and quick execution.
- Upload your project to github with a good readme file. (Other submition methods are also fine)

## If this project is too simple for you
**Optional Challenges**
Out of the scope of this courses, just for fun and future enhancements.
Only for people who are very much interested.
- Make a conversational chatbot that retains a memory or
- Make a chatbot over pdf without langchain or
- Make the UI more beautiful and with more features like temperature slider and with an option to upload the pdf.

Feel free to reach out if you any queries regarding the project 
