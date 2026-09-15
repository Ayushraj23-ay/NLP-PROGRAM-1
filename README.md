NLP Unit 1 Programs

A collection of basic Natural Language Processing (NLP) practical programs implemented using Python, NLTK, and spaCy.

This repository contains six practical programs covering fundamental NLP techniques, including Tokenization, Stemming, Lemmatization, Stop-word Removal, POS Tagging, Parsing, Chunking, and Named Entity Recognition (NER).

---

📚 Programs Included

1. Tokenization

📁 Folder: "01_Tokenization"
📄 File: "tokenization.ipynb"

Tokenization is the process of breaking text into smaller units called tokens, such as sentences and words.

Concepts Covered:

- Sentence Tokenization
- Word Tokenization

Technologies:

- Python
- NLTK
- spaCy

---

2. Stemming and Lemmatization

📁 Folder: "02_Stemming_Lemmatization"
📄 File: "stemming_lemmatization.ipynb"

This practical demonstrates techniques used to obtain the base or root form of words.

Stemming removes word endings to obtain a root form. The resulting word may not always be a valid dictionary word.

Lemmatization converts a word into its meaningful dictionary base form.

Concepts Covered:

- Porter Stemming
- WordNet Lemmatization

Technologies:

- Python
- NLTK Porter Stemmer
- NLTK WordNet Lemmatizer

---

3. Stop-word Removal

📁 Folder: "03_Stopword_Removal"
📄 File: "stopword_removal.ipynb"

Stop words are commonly occurring words that may provide limited useful information for certain NLP tasks.

Examples:
"the", "is", "a", "an", "and", "of"

Concepts Covered:

- Word Tokenization
- Stop-word Identification
- Stop-word Removal

Technologies:

- Python
- NLTK

---

4. Part-of-Speech (POS) Tagging

📁 Folder: "04_POS_Tagging"
📄 File: "pos_tagging.ipynb"

Part-of-Speech tagging assigns a grammatical category to each word in a sentence.

Examples:

- Noun
- Verb
- Adjective
- Adverb
- Preposition
- Determiner

Concepts Covered:

- Word Tokenization
- POS Tagging
- Grammatical Categories

Technologies:

- Python
- NLTK

---

5. Parsing and Chunking

📁 Folder: "05_Parsing_Chunking"
📄 File: "parsing_chunking.ipynb"

This practical demonstrates syntactic analysis using regular-expression-based chunking and dependency parsing.

Concepts Covered:

- POS Tagging
- Regular Expression Chunking
- Noun Phrase Chunking
- Dependency Parsing
- Grammatical Relationships

Technologies:

- Python
- NLTK
- spaCy

---

6. Named Entity Recognition (NER)

📁 Folder: "06_Named_Entity_Recognition"
📄 File: "ner.ipynb"

Named Entity Recognition (NER) identifies and classifies important entities in a given text.

Examples of Entities:

- Person
- Organization
- Location
- Date
- Money
- Geopolitical Entity

Concepts Covered:

- Named Entity Recognition
- Entity Classification
- Entity Labels

Technologies:

- Python
- spaCy

---

🛠️ Technologies Used

- Python 3
- NLTK
- spaCy
- Jupyter Notebook
- Natural Language Processing

---

⚙️ Installation

1. Install Python

Make sure Python 3 is installed on your system.

2. Install Required Libraries

pip install nltk spacy

3. Download the spaCy English Language Model

python -m spacy download en_core_web_sm

4. NLTK Resources

The required NLTK resources are downloaded in the respective notebooks.

These may include:

- "punkt"
- "punkt_tab"
- "stopwords"
- "averaged_perceptron_tagger_eng"
- "wordnet"
- "omw-1.4"

---

▶️ How to Run

The programs are implemented as Jupyter Notebooks (".ipynb").

You can run them using:

- Jupyter Notebook
- JupyterLab
- Google Colab
- VS Code with the Jupyter extension

Start Jupyter Notebook

jupyter notebook

Then open the required notebook and execute the cells sequentially.

For example:

01_Tokenization/tokenization.ipynb

Similarly, open the notebooks inside the other folders to run the remaining practicals.

---

📂 Repository Structure

NLP-Unit-1-Programs/
│
├── 01_Tokenization/
│   └── tokenization.ipynb
│
├── 02_Stemming_Lemmatization/
│   └── stemming_lemmatization.ipynb
│
├── 03_Stopword_Removal/
│   └── stopword_removal.ipynb
│
├── 04_POS_Tagging/
│   └── pos_tagging.ipynb
│
├── 05_Parsing_Chunking/
│   └── parsing_chunking.ipynb
│
├── 06_Named_Entity_Recognition/
│   └── ner.ipynb
│
└── README.md

---

🎯 Learning Objectives

By completing these practical programs, you will gain hands-on experience with the following fundamental NLP techniques:

- Sentence Tokenization
- Word Tokenization
- Stemming
- Lemmatization
- Stop-word Removal
- Part-of-Speech (POS) Tagging
- Parsing
- Chunking
- Named Entity Recognition (NER)

---

🎓 Course Outcome

These practical programs provide hands-on understanding of fundamental Natural Language Processing techniques and their implementation using popular Python NLP libraries.

The programs demonstrate how raw text can be processed, transformed, and analyzed using different NLP techniques.

---

👨‍💻 Author

Ayush Raj

GitHub: Ayushraj23-ay

---

📌 Note

This repository has been created for academic and practical learning purposes.

It demonstrates the implementation of fundamental NLP concepts using Python, NLTK, and spaCy.
