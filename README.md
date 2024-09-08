# 🤖 Custom Chatbot Project

## Introduction

Welcome to my custom chatbot project! This chatbot is designed to interact in a friendly, conversational manner, answering questions about me and engaging in real-time dialogue. It can provide information on my education, skills, projects, and much more.

This project was built using advanced Natural Language Processing (NLP) techniques to create a personal chatbot that acts like a virtual assistant or even a virtual friend.

## Features

- **Personalized Conversations:** The chatbot is trained to answer questions about my background, education, experience, and hobbies.
- **Real-time Responses:** Engages in a smooth and friendly conversation, responding like a human friend.
- **Learning Section:** Provides insights into my journey in Artificial Intelligence, Machine Learning, and Software Engineering.
- **Showcases Projects:** The bot can discuss my key projects, like my Road Damage Detection using YOLOv8 project.
- **Continuous Improvement:** The chatbot is continuously learning from new data and interactions, making it smarter over time.

## How It Works

This chatbot uses a custom dataset created from personal information, structured in a CSV file. The chatbot leverages Hugging Face transformers for training and utilizes NLP models to understand and respond to user input.

### Data

The chatbot pulls information from a structured CSV file that contains different sections of personal details, such as:

- Name, age, city, and country
- Education background
- Specialized training
- Leadership and teamwork experience
- Completed courses
- Continuous learning initiatives
- Skills overview
- Personal interests and future goals

## Installation

To run this project locally, follow the steps below:

1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/custom-chatbot.git
    ```

2. **Navigate into the project directory:**

    ```bash
    cd custom-chatbot
    ```

3. **Install the necessary dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

4. **Set up Hugging Face:**

    - Sign up for a free Hugging Face account if you don’t have one.
    - Obtain an API key from Hugging Face.

5. **Run the chatbot:**

    ```bash
    python chatbot.py
    ```

## Usage

Once the chatbot is running, you can ask it a variety of questions, such as:

- "Tell me about your education."
- "What projects have you completed?"
- "What training have you done in AI?"
- "What's your dream job?"

You can also ask general conversational questions like:

- "What's your favorite programming language?"
- "Tell me about your hobbies."

## Customization

You can modify the chatbot’s responses by updating the `profile_data.csv` file with your own information. You can add new sections and data as needed, making the chatbot completely personalized.

## Technologies Used

- Python
- Hugging Face Transformers
- Natural Language Processing (NLP)
- Pandas for CSV file handling
- Machine Learning for training the model

## Future Enhancements

- Incorporating speech-to-text and text-to-speech capabilities for voice interaction.
- Enhancing the chatbot with more advanced AI features, like emotion detection or sentiment analysis.
- Expanding the dataset to provide richer responses and support more diverse questions.

## Contributions

Feel free to fork this repository and contribute by submitting pull requests. For major changes, please open an issue first to discuss what you would like to change.

