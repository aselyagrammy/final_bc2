# Kazakhstan Constitution: AI Assistant with On-Chain Vector Storage

This project is an MVP of an AI assistant that answers questions about the Constitution of the Republic of Kazakhstan. It uses large language models (LLMs), Streamlit for the user interface, and blockchain (Ethereum or Solana) for storing vector embeddings.

## Features

- Loads and processes the full text of the Constitution of Kazakhstan
- Indexes the content using a vector store
- Answers user questions via an LLM (OpenAI or Gemini)
- Saves vector embeddings on-chain (Ethereum or Solana)
- Simple and intuitive interface built with Streamlit

## Technologies Used

- Python 3.10+
- Streamlit
- LangChain or LlamaIndex
- OpenAI / Gemini API
- FAISS or ChromaDB
- Solidity or Rust (for blockchain integration)
- IPFS (optional)

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/aselyagrammy/final_bc2.git
cd final_bc2
````

### 2. Create and activate a virtual environment

```bash
python -m venv venv
source venv/bin/activate      # macOS/Linux
venv\Scripts\activate         # Windows
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Set up environment variables

Create a `.env` file in the root directory and add your API keys:

```env
OPENAI_API_KEY=your_openai_key
GEMINI_API_KEY=your_gemini_key
```

### 5. Run the Streamlit app

```bash
streamlit run app.py
```

### 6. (Optional) Deploy the smart contract

For Ethereum:

* Use Hardhat or Remix to deploy `EmbeddingsStorage.sol`
* Make sure you have MetaMask and test ETH in the Holesky testnet

For Solana:

* Install `solana-cli` and `anchor`
* Run deployment using `anchor deploy`

## Project Structure

```
final_bc2/
├── app.py                  # Streamlit application
├── constitution/           # Text files of the Constitution
├── blockchain/             # Smart contracts (Solidity or Rust)
├── embeddings/             # Embedding logic and storage
├── utils/                  # Helper functions
├── requirements.txt        # Python dependencies
└── README.md
```

## Future Improvements

* Add support for chat history
* User authentication and profile management
* Store embeddings in IPFS
* Visualize constitutional content by article or topic

## License

This project is licensed under the MIT License.
