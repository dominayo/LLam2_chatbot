# Streamlit Chat Application with Replicate LlamaV2 Model

This is a simple, interactive chat application powered by Streamlit and the Replicate LlamaV2 model. It uses Streamlit for the front end interface and Replicate's LlamaV2 model for generating responses based on user input.

## Prerequisites:

- Python 3.6 or higher
- Streamlit
- Python-dotenv
- Replicate

## Quickstart

1. Clone the repository

```bash
git clone <repo-url>
cd <repo-dir>
```

2. Install the dependencies 

```bash
pip install -r requirements.txt
```

3. Set the environment variables 

Create a `.env` file in the root of your project and add the following environment variables. 

```bash
# .env
REPLICATE_API_TOKEN=<Your Replicate LlamaV2 Key>
```

4. Run the Streamlit app

```bash
streamlit run app.py
```

