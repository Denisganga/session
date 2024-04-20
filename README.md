# Building a chatbot using the chatgpt API on a session conducted on March 29, 2024
![Example Image]([Screenshot_2024-03-31_08_10_58.png])

![Example Image]([Screenshot_2024-03-31_08_10_58.png])

![Example Image]([WhatsApp%20Image%202024-03-29%20at%2010.55.22%20PM.jpeg])

## Mental Health Chatbot using Django and ChatGPT API

This project is a mental health chatbot built using Django and integrating the ChatGPT API for generating responses. The chatbot aims to provide support and assistance to users who may be struggling with mental health issues by offering a conversational interface where they can express their feelings and receive empathetic responses and helpful resources.

## Prerequisites

- Python (version 3.11.7)
- Django (version 3.2.20)
- OpenAI API key (version 0.28)

## Features

- **Conversational Interface**: Users can interact with the chatbot through a conversational interface, providing a comfortable environment for expressing their thoughts and emotions.
- **Empathetic Responses**: The chatbot is designed to provide empathetic and supportive responses to users, helping them feel understood and heard.
- **Integration with ChatGPT API**: The chatbot leverages the power of OpenAI's ChatGPT API to generate natural and contextually relevant responses based on user input.


## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Denisganga/session/edit/main/README.md
   ```
2. Navigate to the project directory:

3. Create a virtual environment (optional but recommended):
 ```bash
 python3 -m venv myenv
 ```

4. Activate the virtual environment:

- On macOS and Linux:

  ```
  source myenv/bin/activate
  ```

- On Windows:

  ```
  myenv\Scripts\activate
  ```

5. Install the project dependencies:

6.  Set Up OpenAI API Key

From the OpenAi website get your API key and add it in your views.py file

7. Apply Migration

```bash
python3 manage.py makemigrations
python3 manage.py migrate
```
8. Run the development server

```bash
python3 manage.py runserver
```


