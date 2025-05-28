# Topic-Based Text Generation Using GPT-2

This project is a simple implementation of topic-based paragraph generation using OpenAI’s GPT-2 language model. The system takes a user-defined topic as input and generates a coherent paragraph using natural language generation.

✨ Features

- Generates text using GPT-2 from Hugging Face.
- Accepts user input for dynamic topic-based text generation.
- Runs entirely in a Jupyter Notebook.

## Setup Instructions

1. Clone the repository:
```
git clone <repo-url>
cd text-generation-gpt2
```

2. Install required dependencies:s
```
pip install -r requirements.txt


3. Run the notebook:
```jupyter notebook text_generation_gpt2.ipynb
```

🧠 How It Works

	1.	GPT-2 is loaded using HuggingFace’s transformers library.
	2.	A prompt is constructed as "Write a paragraph about <topic>:".
	3.	The prompt is tokenized and passed into the model.
	4.	The generated output is decoded and displayed.

🧑‍💻 Author

	•	Shahbaaz Khan
CSE (AIML)
Email: shahbaazkhan6300@gmail.com