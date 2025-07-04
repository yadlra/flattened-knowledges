# Flattened Knowledges

This project investigates how large language models (LLMs) summarise politically and epistemically diverse texts from Mexico — including Indigenous declarations, state policy documents, and mainstream news. It explores how machine learning systems may flatten, erase, or distort Indigenous worldviews and collective political framings during summarisation.

## ✨ Motivation

While LLM evaluation often focuses on benchmark performance or surface level bias, this project asks a deeper question: **What happens when we ask machine learning models to summarise texts grounded in epistemologies that resist linearity, extractivism, or Eurocentric development?** 

Using a corpus of Indigenous-authored texts (e.g. EZLN communiqués, community manifestos), NGO and state documents, and news articles, we compare how summarisation models reproduce or erase specific political framings, concepts, and relational worldviews.

## 🔍 Core Questions

- What types of knowledge are retained, omitted, or distorted in summaries?
- How do summarisation models deal with Indigenous concepts like *milpa*, *comunalidad*, or *tequio*?
- Can model outputs reveal structural tendencies to reduce epistemic diversity to a universalising frame?

## 🧰 Methods

- Summarisation with `bart-large-cnn` and Spanish LLMs
- Semantic comparison using `sentence-transformers`
- Bias and concept omission analysis
- Qualitative annotations and epistemic loss tracking

## 🇲🇽 Context

This project centres on the Mexican context, with a particular focus on how machine learning models engage with texts related to Indigenous resistance, land, and relational knowledge. 

## 📎 Status

In development. Notebooks, data sources, and results will be updated regularly.
