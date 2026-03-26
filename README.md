# Research Data Portfolio — Luis Enrique Lescano Borrego

**Research Data Librarian | AI & Metadata | PhD Candidate | TEDx Speaker**

Welcome to my portfolio of applied projects in **Research Data Management (RDM)**. Here I showcase practical implementations that combine my experience in institutional repositories, metadata automation, open science infrastructures, and artificial intelligence.

These projects reflect my daily work helping universities and research organizations transform disconnected data into interoperable, FAIR‑aligned, and scalable knowledge ecosystems.

---

## 📌 Projects

### 1. Metadata Automation for Repositories (DSpace / OpenAIRE)
[`metadata-automation/transform_metadata.ipynb`](metadata-automation/transform_metadata.ipynb)

Automates the transformation of raw metadata (CSV/Excel) into ingestion formats compatible with **DSpace** and **OpenAIRE 4.0**.  
- Cleans and normalises author names, dates, and identifiers  
- Maps to Dublin Core and local DSpace schemas  
- Validates compliance with FAIR principles  
- Reduces manual processing time by ~40%

**Tech:** Python, pandas, CSV, JSON

---

### 2. Repository Harvesting & Analytics with OAI-PMH
[`oai-pmh-analysis/harvest_repository.ipynb`](oai-pmh-analysis/harvest_repository.ipynb)

Harvests metadata from any OAI‑PMH endpoint and builds interactive visualisations to support institutional decision‑making.  
- Retrieves records using the `Sickle` library  
- Parses XML and extracts key metrics (publications/year, downloads, open access rate)  
- Generates time‑series plots and collaboration maps  
- Provides a ready‑to‑use dashboard for research visibility

**Tech:** Python, Sickle, pandas, matplotlib, plotly

---

### 3. AI‑Assisted Data Management Plan (DMP) Generator
[`dmp-assistant/dmp_assistant.ipynb`](dmp-assistant/dmp_assistant.ipynb)

An interactive notebook that helps researchers create a **Data Management Plan** aligned with funder requirements (e.g., Horizon Europe, NSF).  
- Uses `ipywidgets` for a simple Q&A interface  
- Suggests best practices based on the researcher’s answers  
- Automatically generates a structured DMP in Markdown  
- Checks completeness against mandatory elements (persistent identifiers, data sharing, archiving)

**Tech:** Python, ipywidgets, Jinja2 templates, (optional) OpenAI API for advanced recommendations

---

## 🧠 About Me

I am a **Research Data Librarian** with a background in open science, digital libraries, and knowledge infrastructure. I design and implement interoperable systems that connect research outputs, metadata, and institutional workflows.

Currently, I am a PhD candidate researching the evolution of knowledge systems in the context of AI and open science. I also lead **Bibliobytes**, a consultancy that has helped over 15 universities in Latin America migrate to modern, standards‑based platforms.

- 🎤 **TEDx speaker** — *“La sociedad que olvidó leer”*
- 🌍 **Instructor** for CEDIA (Ecuadorian Network for Research and Education)  
- 📚 **Expertise**: DSpace, Koha, OJS, APIs, metadata standards (MARC21, Dublin Core, OpenAIRE), AI applied to libraries, research data management, FAIR principles

---

## 📫 Connect

- **LinkedIn:** [linkedin.com/in/luis-enrique-lescano](https://www.linkedin.com/in/luis-enrique-lescano)
- **Personal site:** [luislescano.bibliobytes.org](https://luislescano.bibliobytes.org)
- **Email:** luislescano@bibliobytes.org

---

## 🔧 How to Use This Repository

Each project folder contains:
- A Jupyter Notebook (`.ipynb`) with step‑by‑step code and explanations  
- A `README.md` inside the folder with specific setup instructions  
- Sample data (or instructions to fetch open data) for reproducibility

**Requirements:**  
Python 3.9+ with packages listed in `requirements.txt` (coming soon).  
You can run the notebooks locally or in Google Colab.

---

## ⚖️ License

This portfolio is shared for demonstration purposes. Feel free to adapt the code under the [MIT License](LICENSE) (to be added). If you find it useful, a mention or star is appreciated!
