# BlogBot AI

BlogBot AI is an intelligent tool designed to generate blog content tailored to specific topics and writing styles. Using the LLaMA 2 model integrated with Streamlit, it offers an easy-to-use interface for creating high-quality blog posts effortlessly.

## Features

- **Custom Prompt Engineering:** Generates contextually relevant blog content for various writing styles such as Researchers, Data Scientists, and Common People.
- **Interactive Streamlit Interface:** User-friendly web application allowing users to input blog topics, select writing styles, and define word counts.
- **Optimized Model Performance:** Configured LLaMA 2 model parameters for optimal content generation and secured access through Hugging Face authentication.

## Installation

To get started with BlogBot AI, follow these steps:

1. **Clone the repository:**
    ```sh
    git clone https://github.com/SanjeethNC/BlogBot-AI.git
    ```

2. **Navigate to the project directory:**
    ```sh
    cd blogbot-ai
    ```

3. **Create and activate a virtual environment:**
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

4. **Install the required dependencies:**
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Ensure you have the necessary model files in the models directory. You can find the model I used here: https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML/tree/main
2. Run the Streamlit app:
    ```sh
    streamlit run app.py
    ```
4. Open your browser and go to access the BlogBot AI interface.
5. Enter the blog topic, select the writing style, and specify the number of words.
6. Click the "Generate" button to create your blog post.

## Tech Components

- **Streamlit:** For building the web interface.
- **CTransformers:** For integrating and using the LLaMA 2 model.
- **LLaMA 2:** For natural language processing and blog content generation.
- **Hugging Face:** For secure model access and authentication.


## Acknowledgements

Thanks to the Hugging Face team for their powerful models and tools. Special thanks to the Streamlit community for making web app development straightforward and fun.
