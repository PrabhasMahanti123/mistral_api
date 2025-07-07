# YOJANA SAATHI

YOJANA SAATHI is a Streamlit application that serves as a knowledgeable assistant on various government schemes. It uses a powerful language model to provide precise and context-aware answers based on a curated collection of PDF documents.

## 🚀 Features

- **Intelligent Search**: Ask questions in natural language and get answers directly from the content of the provided PDF documents.
- **Interactive Chat**: A user-friendly chat interface to interact with the assistant.
- **Fast and Efficient**: Utilizes FAISS for efficient similarity search to quickly find relevant information.
- **Powered by Mistral**: Leverages the capabilities of Mistral's language models for high-quality responses.

## 🛠️ Getting Started

### Prerequisites

- Python 3.7+
- A Mistral API key

### Installation

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/PrabhasMahanti123/mistral_api.git
    cd mistral_api-main
    ```

2.  **Install the dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

3.  **Set up your API key:**

    Create a `.streamlit/secrets.toml` file and add your Mistral API key:

    ```toml
    MISTRAL_API_KEY = "your_mistral_api_key"
    ```

### Running the Application

To start the Streamlit application, run the following command in your terminal:

```bash
streamlit run app.py
```

The application will open in your web browser.

## 📁 Project Structure

```
.
├── app.py                  # Main Streamlit application file
├── requirements.txt        # Python dependencies
├── database/               # Directory for PDF documents
│   ├── AP.pdf
│   ├── assam_data.pdf
│   └── ...
├── .devcontainer/          # Dev container configuration
│   └── devcontainer.json
├── flag.jpeg               # Application icon
└── logo2.png               # Application logo
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue to discuss any changes.
