# AI-Powered Career Advisor & Salary Predictor 🚀
 is an intelligent system designed to bridge the gap between job seekers and the market. By analyzing LinkedIn job postings, it provides accurate salary predictions using both classical Machine Learning and modern Deep Learning, coupled with a RAG-based AI assistant to answer career-related queries.

---

## 💡 Key Features

* **Salary Prediction**: Implements both **Random Forest** (Classical ML) and **Neural Networks** (Deep Learning) to estimate job salaries based on descriptions and metadata.
* **Semantic Search**: Uses **FAISS** (Facebook AI Similarity Search) to find relevant jobs based on semantic meaning rather than just keywords.
* **AI Career Advisor (RAG)**: A conversational AI powered by **LangChain** and **Groq (Llama 3.1)** that provides personalized career advice based on real-time data.
* **Interactive UI**: A **Gradio** web application for easy interaction with the AI Advisor.

---
## 🛠️ Project Structure

The project is contained within a comprehensive Jupyter Notebook that covers the entire end-to-end pipeline:

* **`Project_Workflow.ipynb`**: This is the main core of the project. It includes:
    * **Data Preprocessing**: Cleaning and preparing the LinkedIn dataset.
    * **Machine Learning**: Training and evaluating the Random Forest model for salary prediction.
    * **Deep Learning**: Implementation of a Neural Network using Sentence-Transformer embeddings.
    * **Semantic Search**: Building the FAISS index for job retrieval.
    * **AI Advisor (RAG)**: The final integration of LangChain and Groq for the conversational assistant.
* **`concept_explanation.md`**: A simplified breakdown of the technical concepts for easy understanding.
* **`requirements.txt`**: A list of all necessary Python libraries to run the notebook.
  
---

## 🚀 Live Demo
You can try the AI-Powered Career Advisor live here:  
**[Launch Gradio Web App](https://3ae65e2f73999fa2ab.gradio.live)**
