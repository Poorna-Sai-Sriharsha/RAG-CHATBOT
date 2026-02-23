## 🤖 RAG Chatbot

## 🔍 Overview
**RAG Chatbot** is a powerful, intelligent web-based application designed to bring advanced Retrieval-Augmented Generation (RAG) capabilities to Velagapudi Ramakrishna Siddhartha Engineering College (VRSEC). Built with a high-performance **Flask & LangChain backend** and an ultra-fast **React + Vite frontend**, this intelligent system parses institutional data, timetables, and documents to answer complex queries with high precision.

Perfect for students, faculty, and administrators looking to instantly query academic documents, interact with AI, and experience seamless multi-lingual support.

## 📸 Screenshots
![VRSEC-RAG Dashboard Preview 1](bot.png) (**Main Chat Bot Interface**)
![VRSEC-RAG Dashboard Preview 2](bot1.png)

## ✨ Features
  -  **Retrieval-Augmented Generation (RAG)** – Context-aware AI that answers questions based on real institutional data
  -  **ChromaDB Vector Storage** – Fast, semantic similarity search over thousands of document embeddings
  -  **LangChain & HuggingFace Integration** – Leveraging state-of-the-art open-source LLMs and SentenceTransformers
  -  **Dedicated Timetable & Data Parsing** – Custom RAG routers handling complex tabular institutional data
  -  **Bhashini Multi-lingual Support** – Advanced translation capabilities to make the chatbot accessible in multiple Indian languages
  -  **Interactive React Frontend** – Lightning-fast UI built with Vite and styled beautifully with Tailwind CSS
  -  **Fully Responsive Design** – Clean, modern layout that works seamlessly on desktop, tablet, and mobile
  -  **Secure & Lightweight Flask API** – Ensures quick response times and decoupled microservice architecture

## 🧠 How It Works
  - The app uses **React + Vite** for a highly responsive, single-page application (SPA) chat interface.
  - User queries are sent to a **Flask** backend that acts as the orchestration layer using **LangChain**.
  - Institutional documents and timetables are processed, chunked, and embedded into a **ChromaDB** vector database natively.
  - When a query is made, the system performs a semantic search to retrieve the most relevant context.
  - This context is fed to a large language model to generate an accurate, localized, and context-rich response.

## 🛠️ Built With
  - **Python 3.11** – Core backend logic and data processing
  - **Flask** – Web framework and REST API routing
  - **LangChain & HuggingFace** – LLM orchestration and embeddings
  - **ChromaDB** – High-performance vector database natively embedded
  - **React & Vite** – Lightning-fast frontend UI components
  - **Tailwind CSS** – Modern, responsive styling utility
  - **Node.js & npm** – Frontend environment management

## 🧰 Getting Started
To run the VRSEC-RAG Chatbot locally:

### Prerequisites
- **Python 3.9+** (preferably 3.11+)
- **Node.js** (v18+ recommended)
- **Git**

### Installation & Run

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Poorna-Sai-Sriharsha/RAG-CHATBOT.git
   ```

2. **Navigate to the Project Directory:**
   ```bash
   cd RAG-CHATBOT
   ```

3. **Set up and Run the Backend:**
   Open a new terminal and run:
   ```bash
   cd backend
   python -m venv venv
   # On Windows:
   venv\Scripts\activate
   # On macOS/Linux:
   source venv/bin/activate
   pip install -r requirements.txt
   python run.py
   ```
   *The Flask API will start running on `http://127.0.0.1:5000`.*

4. **Set up and Run the Frontend:**
   Open a second terminal and run:
   ```bash
   cd frontend-vrsec
   npm install
   npm run dev
   ```
   *The React development server will automatically start, typically accessible at `http://localhost:5173` or `http://localhost:5174`.*

5. **Open Your Browser:**
   Go to the local URL provided by Vite (e.g., `http://localhost:5173`). 
   You now have a fully functional VRSEC-RAG Chatbot running locally!

## 📊 Dataset Source
  - The chatbot processes documents and structured data specific to **Velagapudi Ramakrishna Siddhartha Engineering College (VRSEC)**.
  - Course timetables, academic syllabi, and administrative PDFs are securely vectorized down to the fragment.

## 🧪 Testing
  - Backend API tested on Python 3.9–3.11 environments.
  - Frontend components successfully verified in Chrome, Firefox, Edge, and Safari.
  - Responsive design confirmed on mobile and tablet screens.
  - Tested on Windows, macOS, and Linux.

## 📖 What I Learned
  - Architecting a full-stack Retrieval-Augmented Generation application from scratch.
  - Managing huge machine-learning dependencies and vector databases like ChromaDB cleanly.
  - Integrating advanced translation APIs (Bhashini) to dramatically enhance accessibility for regional users.
  - Seamlessly coupling a modern React/Vite UI to a multi-threaded Python/Flask API.
  - Understanding embeddings, semantic search clustering operations, and LLM context window limits.

## 🤝 Contributing
Contributions are welcome! If you have ideas for new features or improvements, feel free to fork the repository and submit a pull request. For major changes—such as swapping the LLM backend or changing the database schema—please open an issue first to discuss what you would like to change.
