 FakeNewsDetect — AI News Verifier

This is the repository for **FakeNewsDetect**, our final-year project at Jadara University. It's a full-stack web app designed to check whether a news article is real or fabricated using natural language processing and a fine-tuned BERT transformer model.


💡 What it does

Most fake news detectors out there just look for simple keywords or lack a usable interface. We wanted to build something practical that actually understands context:

* **Contextual NLP Classification:** Runs the news text through BERT to check the actual meaning rather than basic word matching.
* **Confidence Rating:** Shows a percentage alongside the classification result so the user knows how confident the model is.
* **History Logs:** Every check gets saved to a Supabase database, allowing users to look back at previous queries.
* **Data Tools:** Includes search, filtering, record deletion, and the option to export analysis history into a CSV file.
* **Responsive Dashboard:** Built with Next.js and Tailwind CSS (includes dark/light theme options).



🛠️ Stack & Tools

* **Frontend:** Next.js, TypeScript, Tailwind CSS
* **Database & Auth:** Supabase (PostgreSQL)
* **Model & ML:** BERT (Transformer Model), Python, Node.js
* **Deployment & Version Control:** Git, GitHub


 🔍 How it Works

1. The user pastes a news paragraph or full article into the input box.
2. The text is validated, cleaned, and tokenized before being passed to the BERT model.
3. The model calculates contextual embeddings and outputs the verdict (`Real` or `Fake`) plus the confidence percentage.
4. The output displays on the dashboard and gets logged into Supabase automatically.


 ✍️ Authors

Developed as part of the Graduation Project requirement at Jadara University (2026).
* **Mahmoud Al-Omari** (Cybersecurity) & Team
