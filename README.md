# DLBDSEDA02_D
Portfolio Schostock Aufgabe 1

Website Datensatz:
https://www.kaggle.com/datasets/ashishkumarak/chatgpt-reviews-daily-updated

NLP-Pipeline für App-Bewertungen (Deutsch) – von Rohdaten bis Themen
-------------------------------------------------------------------
Ziele aus dem Anforderungstext:
1) Daten bereinigen und filtern (neueste App-Version, Score <= 2, etc.).
2) Texte in numerische Vektoren umwandeln (Bag-of-Words, TF-IDF).
3) Themen extrahieren (LSA, LDA).

Voraussetzungen (Python-Pakete):
    pip install pandas numpy scikit-learn nltk gensim packaging

Erwartetes CSV-Format (reviews.csv):
    text,score,app_version
    "Die App stürzt ständig ab",1,"1.2.0"

Ausführung:
    python nlp_pipeline_reviews.py --csv reviews.csv --topics 8 --lsa-dim 100

Ergebnis:
    - Übersichtliche Konsolen-Ausgaben
    - Dateien mit Top-Keywords je Thema (optionale Speicherung)
-------------------------------------------------------------------
