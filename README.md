📝 TEXT_SUMMARIZATION (NLP Project)
🏫 A Self-Learning Mini Project – Python & Gensim

This project was built as a personal learning exercise to understand the basics of text summarization using Natural Language Processing.
It demonstrates how to generate extractive summaries for large text inputs quickly and easily.

📌 Project Overview
This project leverages the `gensim` library to produce concise summaries by extracting the most relevant sentences from longer documents.

📈 Key Features
- Summarizes input text automatically
- Configurable summary ratio (default: 30%)
- Simple, clean Python script for educational purposes

🧪 Techniques Used
- Extractive Text Summarization
- Sentence Ranking
- Gensim's TextRank Algorithm

👨‍💻 Platform Used
- Local Python environment
- Google Colab
- vs code
- Jupiter notebook

🔗 Resources
📂 Gensim Documentation:
(https://radimrehurek.com/gensim/)

🧾 Example Usage
Here’s what running the script looks like:

```bash
python text_summarizer.py
✅ You will see a concise summary printed to your terminal.

📁 Project Structure
Your folder should look like this:
text-summarization/
├── text_summarizer.py
├── requirements.txt
├── .gitignore
└── README.md
⚙️ How to Run

✅ Option 1: Local Environment

1️⃣ Create a virtual environment:

bash
Copy
Edit
python -m venv venv
2️⃣ Activate it:

Windows:

bash
Copy
Edit
venv\Scripts\activate
Mac/Linux:

bash
Copy
Edit
source venv/bin/activate
3️⃣ Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
4️⃣ Run the script:

bash
Copy
Edit
python text_summarizer.py
✅ Option 2: Google Colab

1️⃣ Open a new Colab notebook.

2️⃣ Install gensim:

python
Copy
Edit
!pip install gensim==3.8.3
3️⃣ Copy and paste the code from text_summarizer.py into a cell.

4️⃣ Run the cell.

📝 Notes from the Author
"This project is my way of exploring NLP fundamentals and seeing how extractive summarization works in practice. It’s a simple example you can extend—try feeding it longer articles or experimenting with different ratios to see how summaries change."

– By Satyajit Mishra 

🙌 Special Thanks

Gensim Open-Source Contributors

Python Software Foundation

💬 Final Thoughts
If you’re new to NLP or Gensim, don’t worry—just read the script and experiment with different inputs.
Hands-on practice is the best way to learn.
