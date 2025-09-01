# Medicalchatbot

A conversational AI chatbot for medical queries.

## Features

- Answers medical questions using AI
- User-friendly interface
- Easy to set up and run locally

## How to Run

1. **Clone the repository**

    ```bash
    git clone https://github.com/SKrr8/Medicalchatbot.git
    cd Medicalchatbot
    ```

2. **Create and activate a conda environment**

    **Windows**:
    ```bash
    conda create -n medicalchatbot python=3.10
    conda activate medicalchatbot
    ```

    **macOS/Linux**:
    ```bash
    conda create -n medicalchatbot python=3.10
    conda activate medicalchatbot
    ```

3. **Install dependencies**

    ```bash
    pip install -r requirements.txt
    ```
    
    This will install all required packages including:
    - LangChain for AI workflows
    - Flask for the web interface
    - Sentence Transformers for embeddings
    - Pinecone for vector database
    - Additional utilities for medical NLP

4. **Run the application**

    ```bash
    python app.py
    ```

5. **Open your browser**

    Visit `http://localhost:5000` to interact with the chatbot.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

