# Academic-assistant-project
#  The Conversational Academic Assistant

> Unlock the knowledge in your documents. Ask questions in natural language and get answers instantly, powered by Generative AI.

---

## The Problem

Students and researchers spend countless hours manually sifting through large PDF documents and research papers to find specific information. This time-consuming process hinders academic efficiency and makes learning more difficult than it needs to be.

## ✨ Our Solution

Our AI-powered academic assistant allows users to upload their study materials and start a conversation. The app leverages:
1.  **Accurate Text Extraction** to process content from uploaded PDFs.
2.  **Semantic Search** to find the most relevant text chunks that match the user's question.
3.  **Generative AI** to synthesize a direct, well-contextualized answer from the retrieved information.

This saves hours of manual work and makes study materials interactive and accessible, aligning with **SDG 4: Quality Education**.


> *A screenshot of our application in action.*

---

## 🔗 Live Demo

> 👉 **You can try our live application here:** [Link to your deployed Hugging Face Space will go here]

---

## 🛠️ Tech Stack & How It Works

Our application is built entirely in Python and leverages a state-of-the-art AI pipeline.

* **Frontend:** Streamlit
* **Language:** Python
* **AI Models:**
    * **Embedding (for Semantic Search):** `sentence-transformers/all-MiniLM-L6-v2`
    * **Generation (for Synthesizing Answers):** `mistralai/Mistral-7B-Instruct-v0.2`
* **Core Libraries:** `pypdf`, `faiss-cpu`, `transformers`, `torch`
* **Deployment:** Hugging Face Spaces with Docker

---

## 🏃‍♀️ How to Run Locally

To run this project on your own machine, follow these steps:

```bash
# 1. Clone the repository
git clone [Your GitHub Repository URL]

# 2. Navigate into the project directory
cd [Your-Repo-Name]

# 3. Install the required dependencies
pip install -r requirements.txt

# 4. Run the Streamlit application
streamlit run app.py
