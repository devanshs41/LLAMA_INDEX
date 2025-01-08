# RAG System Using Llama2 with LlamaIndex

This repository contains a Jupyter Notebook that demonstrates the implementation of a Retrieval-Augmented Generation (RAG) system using Llama2 and LlamaIndex. The notebook provides step-by-step guidance for setting up the environment, preparing data, and using state-of-the-art models for querying and generation.

---

## Features
- **Comprehensive Setup**: Installs and configures essential libraries such as `transformers`, `sentence_transformers`, and `llama_index`.
- **Document Embedding**: Processes documents for efficient embedding generation using pre-trained models.
- **Query Handling**: Demonstrates the RAG workflow with example queries.
- **Integration with Llama2**: Leverages the Llama2 model for natural language generation tasks.

---

## Getting Started

### Prerequisites
Ensure you have the following installed:
- Python 3.8 or later
- Jupyter Notebook or JupyterLab
- Internet connection (to download libraries and models)

### Installation
To set up the environment, install the required dependencies:
```bash
pip install pypdf transformers einops accelerate langchain bitsandbytes sentence_transformers llama_index
```

### Running the Notebook
1. Clone this repository or download the notebook file.
2. Open the notebook in Jupyter or a similar environment.
3. Run the cells sequentially to set up and test the RAG system.

---

## Notebook Overview

### Sections
1. **Introduction**: Provides an overview of RAG and its use case.
2. **Environment Setup**: Installs and verifies dependencies.
3. **Embedding Preparation**: Shows how to prepare and generate embeddings from documents.
4. **Model Integration**: Explains how to connect Llama2 with LlamaIndex.
5. **Use Cases**: Demonstrates querying with examples.

### Key Dependencies
- **Hugging Face Transformers**: For accessing the Llama2 model.
- **LlamaIndex**: For embedding generation and document querying.
- **Sentence Transformers**: For creating vector embeddings of text data.

---

## Examples
The notebook includes examples to:
- Preprocess and embed documents.
- Query the system with natural language inputs.
- Generate responses using the Llama2 model.

---

## Acknowledgments
- [Hugging Face](https://huggingface.co/) for providing access to Llama2.
- [LlamaIndex](https://llamaindex.ai/) for retrieval-based solutions.

---

## License
This project is distributed under an open-source license. Refer to the individual library licenses for details.

---

## Support
If you encounter any issues or have questions, feel free to raise an issue or reach out via the repository’s discussion section.

