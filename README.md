# Multi-RAG: A Multi-Retrieval GPT-4 Prototype

Dependencies:
1. Create a new virtual env: python -m venv venv
2. Activate the virtual env: source venv/bin/activate
3. Install requirements: 
    Unix: ./install_dependencies.sh
    Windows: install_dependencies.bat
    Note: replace faiss with faiss-cpu in the script if you don't have a GPU

Running the app:
1. Ingest the PDF with ingest.py
2. Run the app with streamlit run app.py