🤖 HR Policy Assistant (RAG Bot)

An intelligent Retrieval-Augmented Generation (RAG) chatbot designed to answer employee questions regarding company policies, guidelines, and handbook queries accurately and instantly.

🌟 Features

Context-Aware Responses: Retrieves precise answers directly from official company documents (e.g., Employee Handbook).

Hallucination Reduction: Grounded search restricts the LLM to verified organizational documents, ensuring compliance and accuracy.

Secure Architecture: Uses environment variables to protect private API keys and sensitive configuration data.

Interactive Querying: Supports Jupyter Notebook (code.ipynb) workflows for rapid experimentation and query testing.

📁 Project Structure

Intelligent RAG/
├── data/                    # Contains dataset and policy documents (e.g., Employee Handbook)
├── .env                     # Local environment variables (ignored by git)
├── .env.example             # Template for required environment variables
├── .gitignore               # Specifies intentionally untracked files
├── code.ipynb               # Main Python notebook implementing the RAG pipeline
└── README.md                # Project documentation
