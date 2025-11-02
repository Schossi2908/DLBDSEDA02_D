# DLBDSEDA02_D
Portfolio Schostock Aufgabe 1

Website Datensatz:
https://www.kaggle.com/datasets/ashishkumarak/chatgpt-reviews-daily-updated

NLP-Pipeline für App-Bewertungen (Englisch)
-------------------------------------------------------------------
Ziele aus dem Anforderungstext:
1) Daten bereinigen und filtern (neueste App-Version, Score <= 2, etc.).
2) Texte in numerische Vektoren umwandeln (Bag-of-Words, TF-IDF).
3) Themen extrahieren (LSA, LDA).
4) Themenkohärenz ermitteln.

Voraussetzungen (Python-Pakete):
    pip install pandas numpy scikit-learn nltk gensim packaging

Erwartetes CSV-Format (reviews.csv):
    text,score,app_version
    "Die App stürzt ständig ab",1,"1.2.0"

Ausführung:
    python Auswertung_Chatgpt.py --csv reviews.csv

Ergebnis:
    - Begrenzung auf maximal 50 Topics (Übersichtlichtkeit der Ergebnisse)
    - Übersichtliche Konsolen-Ausgaben
    - Gefilteres Review.csv als eigene Datei
    - Dateien mit Top-Keywords je Thema (als eigene Datei je Filterung)
    - Themenkohärenz in eigener Datei
-------------------------------------------------------------------



