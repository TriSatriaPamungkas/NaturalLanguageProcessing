# 🏦 Banking NLP Chatbot --- UTS Natural Language Processing

Proyek ini merupakan implementasi **Natural Language Processing (NLP)**
untuk membangun **Chatbot FAQ Perbankan** 

------------------------------------------------------------------------

# 📁 Struktur Project

    .
    ├── Bank_UTS_NLP.ipynb
    ├── banking_knowledge_base_1000.csv
    ├── README.md

------------------------------------------------------------------------

# ⚙️ Requirements

Pastikan Python sudah terinstall:

    Python 3.8+

Install dependency:

``` bash
pip install pandas numpy matplotlib seaborn scikit-learn nltk
```

------------------------------------------------------------------------

# 📥 Download NLTK Resource

Jalankan kode berikut:

``` python
import nltk

nltk.download('punkt')
nltk.download('punkt_tab')
nltk.download('stopwords')
```

------------------------------------------------------------------------

# 🚀 Cara Menjalankan Project

## 1. Clone Repository

``` bash
git clone https://github.com/username/repository-name.git
```

Masuk ke folder project

``` bash
cd repository-name
```

------------------------------------------------------------------------

## 2. Jalankan Jupyter Notebook

``` bash
jupyter notebook
```

Buka file:

    Bank_UTS_NLP.ipynb

------------------------------------------------------------------------

## 3. Jalankan Semua Cell

Jalankan secara berurutan:

1.  Import Library\
2.  Load Dataset\
3.  Text Preprocessing\
4.  Vectorization\
5.  Cosine Similarity\
6.  Chatbot Function\
7.  Visualisasi\
8.  Chatbot Simulation

------------------------------------------------------------------------

# 📊 Dataset

Dataset:

    banking_knowledge_base_1000.csv

Dataset berisi:

-   Question\
-   Answer

Pastikan dataset berada dalam folder yang sama.

------------------------------------------------------------------------

# 💬 Menjalankan Chatbot

Setelah menjalankan semua cell:

    WELCOME TO THE VIRTUAL COMMUNITY ASSISTANT
    Type 'exit', 'quit', or 'stop' to end the session.

Contoh:

    User : What is savings account?
    Bot  : Savings account is...

Untuk keluar:

    exit

------------------------------------------------------------------------

# 🧠 Metode yang Digunakan

## Text Preprocessing

-   Lowercase\
-   Cleaning Text\
-   Tokenization\
-   Stopword\
-   Stemming

## Feature Extraction

-   Bag of Words\
-   TF-IDF

## Similarity

-   Cosine Similarity

------------------------------------------------------------------------

# 📈 Visualisasi

Project menampilkan:

-   Top kata paling sering muncul\
-   Perbandingan BoW vs TF‑IDF\
-   Cosine similarity

------------------------------------------------------------------------
