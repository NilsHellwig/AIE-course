# Kurskonzept: AI engineering - building applications with foundation models

## 📚 Kapitelübersicht

### Kapitel 0: Grundlagen des Natural Language Processing (Erste Sitzung)

- Zerlegung von Text in Wörter/Sätze: `nltk`, `spaCy`, `transformers`
- Stoppwörter entfernen & Normalisierung, Kleinbuchstaben, Lemmatization, Stemming
- Wortfrequenzen berechnen (Bag-of-Words): `Counter`, `TfidfVectorizer`, Visualisierung mit `matplotlib` / `wordcloud`
- POS-Tagging & Named Entity Recognition (NER)**  
- Grammatikalische Analyse mit `spaCy` oder `nltk`  
- Erkennung von Eigennamen, Orten, Organisationen
- Vektor-Repräsentationen (Embeddings): Word2Vec, GloVe, Sentence Transformers  
- Cosine Similarity zur Textähnlichkeit
- Evaluation & Metriken in NLP
- Accuracy, Precision, Recall, F1-Score  
- Markdown Grundlagen und Konvertierung von Dokumenten in das Markdown Format

---

### Kapitel 1: Einführung in Foundation Models und Large Language Models 
- Was sind Foundation Models?
- Unterschiede zu klassischen ML-Modellen
- Chancen und Herausforderungen

---

### Kapitel 2: Modelllandschaft und Prompt Engineering 
- Open-Source vs. proprietäre Modelle
- Vergleich: GPT, LLaMA, Claude, Mistral, etc.
- Auswahlkriterien (Modellgröße, Lizenz, Use-Case)
- Was sind Hyperparameter
- Prompt-Grundlagen und Struktur
- Prompting Strategien: Zero-Shot, Few-Shot, RAG, Chain-of-Thought etc. (Sehr gute Quelle: https://www.promptingguide.ai/techniques)

#### Praktische Tools
- Einführung in Ollama / LangChain / Batched prediction mit vLLM

---

### Kapitel 3: Retrieval-Augmented Generation (RAG) 
- Architektur von RAG-Systemen
- Vektorspeicher: ChromaDB, Elsasticsearch
- Anbindung externer Wissensquellen (z.B. PDFs, SQL, Websites)
- Anwendungsfälle: Chatbots, FAQ-Systeme, Expertenassistenten
- Auswahl geeigneter Beispiele zur Augmentierung

#### Praktische Tools
- Einführung in Haystack

---

### Kapitel 4: Fine-Tuning von LLMs

- Offen: Mit Google Colab? Für Abschlussprojekt evtl. unrealistisch.

#### Praktische Tools
- Einführung in Unsloth

---

### Kapitel 5: Infrastruktur und Deployment
- Aufbau robuster APIs
- Skalierung und Monitoring in Produktion

#### Praktische Tools
- Deployment mit Haystack, Langchain und FastAPI


---

### Kapitel 6: Abschluss - Sicherheit, Ethik und Governance (30 Minuten)
- Sicherheitsaspekte: Jailbreaking, Injection Prevention
- Datenschutz & Recht (z. B. DSGVO)
- Auditierbarkeit & Reproduzierbarkeit
- Responsible AI Guidelines

---


## 🛠️ Voraussetzungen
- Grundkenntnisse in Python, ggf. Online-Kurs für Python empfehlen, falls nicht im Studium behandelt.
- Interesse an KI, NLP oder MLOps

