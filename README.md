# Diabeatix

Diabeatix is an interactive Streamlit application featuring an AI assistant. Users can interact with the assistant via text or voice input. The application utilizes OpenAI Whisper for voice transcription, an external API (aimlapi.com) for text-to-speech generation, and Langflow to orchestrate different AI workflows, including a memory-based chatbot and potentially a Retrieval-Augmented Generation (RAG) system. The assistant responds both textually and audibly.

## Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/i-mwangi/Diabeatix.git
    cd Diabeatix
    ```

2.  **Create and activate a virtual environment (optional but recommended):**
    ```bash
    python -m venv venv
    # On Windows
    .\venv\Scripts\activate
    # On macOS/Linux
    source venv/bin/activate
    ```

3.  **Install dependencies:**
    *(Assuming you have a requirements.txt file)*
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1.  **Run the Streamlit application:**
    ```bash
    streamlit run app.py
    ```

2.  Open your web browser and navigate to the local URL provided by Streamlit (usually `http://localhost:8501`).

*(Add any other relevant usage instructions or configuration details here)* 
