# 🛒 NovaCart Generative AI Customer Support Assistant

A RAG-based Generative AI customer support assistant that answers customer questions using a curated NovaCart knowledge base.

The system uses semantic search to retrieve relevant support information and applies a relevance check before generating a response. If the required information is not available, the assistant safely falls back instead of inventing an answer.

## 🚀 Project Overview

The NovaCart Customer Support Assistant is designed to provide reliable responses to common customer-support questions related to:

- Account and password support
- Payment issues
- Order status
- Order tracking
- Order cancellation
- Customer support contact

The project demonstrates how Retrieval-Augmented Generation (RAG) can be used to build a grounded customer-support application.

## 🧠 How It Works

```text
Customer Question
       ↓
Gradio Chat Interface
       ↓
Question Embedding
       ↓
Semantic Search
       ↓
Relevant Knowledge Documents
       ↓
Similarity & Relevance Check
       ↓
Grounded Response
       ↓
Customer

## ✨ Key Features

- Semantic search using sentence embeddings
- Retrieval-Augmented Generation (RAG)
- 21-document customer-support knowledge base
- Cosine similarity for document retrieval
- Relevance and score-gap filtering
- Grounded responses based on retrieved knowledge
- Safe fallback for unsupported questions
- Free/open-source generative AI model
- Interactive Gradio web interface
- Support-topic transparency
- Tested with multiple customer question variations

## 🛠️ Technologies Used

- Python
- Google Colab
- Hugging Face Transformers
- Qwen Generative AI Model
- Sentence Embeddings
- Scikit-learn
- Cosine Similarity
- Gradio
- Retrieval-Augmented Generation (RAG)

## 📊 Evaluation

The assistant was tested using multiple variations of customer questions.

Examples included:

- Password recovery
- Payment failures
- Contacting support
- Order status
- Order cancellation
- Unsupported discount questions

The system successfully returned grounded answers for supported questions and used a safe fallback for unsupported questions.

## 💡 Example

**Customer:**

> My payment failed. What should I do?

**Assistant:**

> I'm happy to help. Customers should verify their payment details and try again. If the problem continues, they should contact their bank or NovaCart support.

**Customer:**

> Can I get a discount?

**Assistant:**

> I don't have enough information to answer that. Please contact NovaCart support.

## 🎯 Learning Outcomes

Through this project, I practiced:

- Building a semantic-search pipeline
- Creating document embeddings
- Implementing RAG concepts
- Working with transformer-based generative AI models
- Designing relevance checks
- Reducing unsupported AI responses
- Building an interactive AI application with Gradio
- Testing an AI application with different user queries

## 🔮 Future Improvements

Potential future improvements include:

- Conversation memory with improved context handling
- Larger and more diverse knowledge bases
- Advanced evaluation metrics
- Authentication and user management
- Integration with a real customer-support platform
- Deployment as a production web application

## 👩‍💻 Author

**Subhana Shaikh**

Generative AI Learner | BBA Graduate | AI Project Portfolio
