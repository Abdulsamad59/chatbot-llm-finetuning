# Projektstruktur

# === Ordnerstruktur ===
# chatbot-llm-finetuning/
# ├── README.md
# ├── chatbot_finetuning.ipynb
# ├── requirements.txt
# └── sample_data/ (hier kannst du PDFs ablegen, falls nötig)


# === Inhalt README.md ===

"""
# 💡 LLM Chatbot Fine-Tuning auf medizinischen Dokumenten

Dieses Projekt zeigt, wie ein Large Language Model (LLM) auf medizinische Daten (MedQuad-Datensatz) mit Hilfe von:
- LangChain
- Huggingface Transformers
- FAISS
- PEFT (Parameter Efficient Fine-Tuning)

feinjustiert wird.

## 🔧 Installationen

```bash
pip install -r requirements.txt
```

## 📊 Projektablauf

1. **PDF-Import**: Extrahieren von Inhalten aus PDF-Dateien
2. **Textsplitter & Embeddings**: Zerlegen in Textabschnitte und Einbetten
3. **Vectorstore (FAISS)**: Aufbau einer semantischen Suche
4. **Fine-Tuning des LLM**: Modellquantisierung und LoRA-Anpassung
5. **Evaluation**: Vorher-/Nachher-Vergleich mit Rouge-Scores & Wordclouds

## 📦 Dateien
- `chatbot_finetuning.ipynb` - Jupyter Notebook mit dem vollständigen Code
- `requirements.txt` - Notwendige Bibliotheken
- `sample_data/` - Beispielhafte Daten (Ordnerstruktur)

## 🛠️ Technologien
- Python
- LangChain
- Huggingface (Transformers, Datasets)
- FAISS
- TensorBoard
- PEFT
- TRL (Transformer Reinforcement Learning)

## 🌟 Ergebnisse
Nach dem Fine-Tuning verbessert sich das Modell in Bezug auf medizinische Abfragen deutlich, gemessen an Rouge-Scores und Antwortqualität.

---

"""
