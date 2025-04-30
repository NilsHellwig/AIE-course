# Kurskonzept: AI engineering - building applications with foundation models

## 📚 Kapitelübersicht

### Kapitel 1: Einführung in Foundation Models und Large Language Models (1 VL)

- Was sind Foundation Models? [Stefan Böhringer]
- Entstehung/Einführung transformer-basierter Sprachmodelle
- Training großer Sprachmodelle (Verfahren, Energieaufwand, Trainingsdaten) [Nils Hellwig]
- Unterschiede zu klassischen ML-Modellen
- Hausaufgabe: Google Colab Notebook hochladen (mit Live-Demo im Kurs) [Nils Hellwig]

---

### Kapitel 2: Modelllandschaft und Prompt Engineering (3 VL) [Nils Hellwig]

- Open-Source vs. proprietäre Modelle
- Vergleich: OpenAI GPT, LLaMA, Gemma, Mistral, etc.
- Auswahlkriterien (Modellgröße, Rechenaufwand, Lizenz, Use-Case, Benchmarks LLM)
- Was sind Hyperparameter
- Prompt-Grundlagen und Struktur
- Output Validation
- Prompting Strategien: Zero-Shot, Few-Shot, RAG, Chain-of-Thought etc. (Sehr gute Quelle: https://www.promptingguide.ai/techniques)

#### Praktische Tools

- CUDA Grundlagen: Wie nutze ich die GPU, nvidia-smi etc.
- LLM Inference mit Open WebUI
- Umsetzung in Ollama / LangChain / Batched prediction mit vLLM / Haystack

---

### Kapitel 3: Retrieval-Augmented Generation (RAG) (2 VL) [Stefan Böhringer]

- Architektur von RAG-Systemen
- Chunking-Strategien
- Prompt Rewriting
- Vektorspeicher: ChromaDB, Elsasticsearch, DuckDB
- Anbindung externer Wissensquellen (z.B. PDFs, SQL, Websites)
- Anwendungsfälle: Chatbots, FAQ-Systeme, Expertenassistenten
- Auswahl geeigneter Beispiele zur Augmentierung

#### Praktische Tools

- Umsetzung in Haystack, Langchain/Langgraph

---

### Kapitel 4: Fine-Tuning von LLMs (1 VL) [Nils Hellwig]

- Vorteile/Nachteile
- Wie speichere ich finetuned Modelle?
- Offen: Mit Google Colab? Für Abschlussprojekt evtl. unrealistisch.

#### Praktische Tools

- Einführung in Unsloth

---

### Kapitel 5: Infrastruktur, Deployment und Evaluation (4 VL) [Stefan Böhringer]

- Aufbau robuster APIs
- Umgang mit (abstrakten) Klassen und Typen in Python
- RestAPIs: LLM bereitstellen, Authentification
- Skalierung und Monitoring in Produktion: Phoenix, Langsmith
- Frontend mit Gradio [Nils Hellwig]

#### Praktische Tools

- Deployment mit Haystack, Langchain und FastAPI

---

### Kapitel 6: Abschluss - Sicherheit, Ethik und Governance (1 VL) [Stefan Böhringer]

- Projektbesprechung: Themen / Abgabeformat [Nils Hellwig]
- Sicherheitsaspekte: Jailbreaking, Injection Prevention [Nils Hellwig]
- Datenschutz & Recht (z.B. DSGVO)
- Auditierbarkeit & Reproduzierbarkeit
- Responsible AI Guidelines, EU AI Act

---

## 🛠️ Voraussetzungen

- Grundkenntnisse in Python, ggf. Online-Kurs für Python empfehlen, falls nicht im Studium behandelt.
- Interesse an KI, NLP oder MLOps
- Notebooks kompatibel mit Colab 

### Grundlagen

- Zerlegung von Text in Wörter/Sätze: `nltk`, `spaCy`, `transformers`
- Stoppwörter entfernen & Normalisierung, Kleinbuchstaben, Lemmatization, Stemming
- Wortfrequenzen berechnen (Bag-of-Words): `Counter`, `TfidfVectorizer`, Visualisierung mit `matplotlib` / `wordcloud`
- POS-Tagging & Named Entity Recognition (NER)\*\*
- Grammatikalische Analyse mit `spaCy` oder `nltk`
- Erkennung von Eigennamen, Orten, Organisationen
- Vektor-Repräsentationen (Embeddings): Word2Vec, GloVe, Sentence Transformers
- Cosine Similarity zur Textähnlichkeit
- Evaluation & Metriken in NLP
- Accuracy, Precision, Recall, F1-Score
- Markdown Grundlagen und Konvertierung von Dokumenten in das Markdown Format

### Offene Punke

- Wo eingliedern
- Übungsaufgaben während des Semesters
- Welche Hardware
- frontend?
