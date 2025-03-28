# Jisu Chatbot

Jisu Chatbot is a test project using Rasa machine learning for basic conversational interactions. It can introduce itself, describe its creator, explain its capabilities, and provide insights into how it was built.

## Features
- Basic interactions and responses
- Built using Rasa Open Source
- Local testing and training capabilities

## Prerequisites
Make sure you have the following installed before setting up the chatbot:
- Python (>=3.8, <3.11)
- Virtual environment (recommended)
- Rasa Open Source

## Setup

1. **Clone the Repository**
```sh
git clone https://github.com/JisuKayl/Rasa-Machine-Learning-Test.git
cd jisu-chatbot
```

2. **Create and Activate Virtual Environment**
```sh
python -m venv venv
```
- **On Windows:**
```sh
venv\Scripts\activate
```
- **On macOS/Linux:**
```sh
source venv/bin/activate
```

3. **Install Dependencies**
```sh
pip install -r requirements.txt
```

4. **Train the Model**
```sh
rasa train
```

5. **Test in Shell Mode**
```sh
rasa shell
```

6. **Run the Action Server (if needed)**
```sh
rasa run actions
```

## Running the Chatbot
To start the chatbot and interact with it, use:
```sh
rasa shell
```

## Notes
- The `.gitignore` file ensures that virtual environments, Rasa model artifacts, cache files, and logs are not tracked in the repository.
- This is a test project, and no external integrations (such as APIs or databases) are included.

## License
This project is for testing and learning purposes only.

## Screenshot/s
![image](https://github.com/user-attachments/assets/86fd609a-abfa-4e31-a41b-74aad4f1c0be)
