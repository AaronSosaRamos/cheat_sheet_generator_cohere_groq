# Cheat Sheet Generator with Open Source LLMs and Cohere for Marvel AI

Welcome to the **Cheat Sheet Generator** repository! This project leverages **LangChain**, **Cohere embeddings**, **ChromaDB**, and open-source models **LLama 3** and **Mixtral** (provided by **Groq**) to generate concise, highly customized cheat sheets. Designed for learners, educators, and professionals, this tool transforms complex topics into accessible summaries.

---

## **Features**

### 🔹 **Seamless Integration with LangChain**
- Orchestrates interactions between models and user inputs for a streamlined experience.

### 🔹 **Robust Vector Search with ChromaDB**
- Ensures fast and contextually accurate retrieval using Cohere embeddings.

### 🔹 **Open Source Models for Flexibility**
- Utilizes **LLama 3** and **Mixtral** (provided by **Groq**) to generate domain-specific and user-friendly outputs.

### 🔹 **Customizable Output Formats**
- Supports cheat sheets in list, table, or step-by-step formats to suit different needs.

### 🔹 **Wide Applicability**
- Ideal for academic, professional, and personal use cases where quick references are essential.

---

## **Tech Stack**

- **LangChain**: Framework for managing pipelines and workflows.
- **Cohere Embeddings**: High-quality vector representations for semantic accuracy.
- **ChromaDB**: Scalable vector database for efficient storage and retrieval.
- **LLama 3** and **Mixtral**: Open-source LLMs (provided by **Groq**) fine-tuned for concise, contextual outputs.

---

## **Getting Started**

### **Prerequisites**
Ensure you have the following installed:
- Python 3.8+
- pip
- Dependencies listed in `requirements.txt`

### **Installation**
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/cheat-sheet-generator.git
   cd cheat-sheet-generator
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Set up Cohere API key and other environment variables:
   - Add your **Cohere API key** and your **Groq API Key** to a `.env` file:
     ```
     GROQ_API_KEY=your_api_key
     COHERE_API_KEY=your_api_key
     ```

4. Run the application:
   ```bash
   python main.py
   ```

---

## **Usage**

1. **Input a Topic**: Provide the topic or query for which you need a cheat sheet.
2. **Select Output Preferences**: Choose the format (e.g., bullet points, table) and level of detail.
3. **Generate**: The tool will retrieve relevant information, process it, and generate a cheat sheet tailored to your needs.

---

## **Examples**

### **Input**
```
Generate a cheat sheet on the topic: "Quantum Computing Basics."
```

### **Output**
```markdown
# Quantum Computing Basics

- **Qubits**: Fundamental units of quantum information.
- **Superposition**: A qubit can represent multiple states simultaneously.
- **Entanglement**: Qubits share a connection, allowing state changes to correlate.
- **Applications**:
  - Cryptography
  - Machine learning
  - Complex simulations
```

---

## **Contributing**

We welcome contributions to enhance this project! To contribute:
1. Fork the repository.
2. Create a new branch for your feature:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes and push:
   ```bash
   git push origin feature-name
   ```
4. Submit a pull request for review.

---

## **Acknowledgments**

This project would not have been possible without the incredible tools and support from:
- [LangChain](https://github.com/langchain-ai/langchain)
- [Cohere](https://cohere.ai/)
- [ChromaDB](https://www.trychroma.com/)
- [LLama](https://github.com/facebookresearch/llama) and **Groq** for providing the open-source LLMs
- The open-source community

---

## **License**

This project is licensed under the MIT License. See the `LICENSE` file for more details.

---

## **Contact**

For questions or feedback, feel free to reach out:
- **Author**: [Wilfredo Aaron Sosa Ramos](https://github.com/AaronSosaRamos)
- **Email**: your-email@example.com

Let’s make learning more accessible and efficient together! 🎉
```

Let me know if you'd like further modifications!
