


# RAG Implementation From Scratch

This project implements a Retrieval-Augmented Generation (RAG) model from scratch using Python. It integrates a retrieval mechanism (such as cosine similarity) with a language generation model to recommend activities based on user input.

## Overview

The RAG model combines a retrieval component with a generation component to enhance the quality of generated text. This implementation demonstrates how to use Python to build and deploy a recommendation system that responds to user queries with concise activity suggestions.

## Setup

To set up this project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/KasimVali2207/RAG_Implementation-From-Scratch.git
   cd RAG_Implementation-From-Scratch
   ```

2. **Install dependencies**:
   - Ensure you have Python installed (version >= 3.6)
   - Install required packages using pip:
     ```bash
     pip install -r requirements.txt
     ```

3. **Download and setup ollama**:
   - Download ollama from [ollama.com/download](https://ollama.com/download).
   - Open a command prompt or terminal and navigate to the downloaded ollama directory.
   - Run the following command to start the llama2 model:
     ```bash
     ollama run llama2
     ```
