## Overview:  
This Django chatbot project is a web application that enables users to interact with an AI assistant powered by OpenAI's GPT API. It includes user authentication features like registration, login, and logout to ensure secure access. Once logged in, users can send messages, which are processed by the GPT model, and receive intelligent responses. All chat history is stored in a database and linked to individual user accounts. The frontend uses AJAX to provide a seamless and responsive chat experience within a simple user interface.

Usage:  
clone the repo  
pip install django
pip install openai
Update your api_key in Chatbot_using_Gpt4api/django_chatbot/chatbot/views.py file  
cd Chatbot_using_Gpt4api/django_chatbot/  
python3 manage.py runserver  
goto http://127.0.0.1:8000/register and login yourself http://127.0.0.1:8000/login  
