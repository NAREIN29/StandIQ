<div align="center">

# 📐 StandIQ

### Every tender, pointed at the right standard.

*A procurement intelligence platform that reads government tender documents, extracts technical requirements, and recommends the correct Bureau of Indian Standards (BIS) standards and certifications, with expert review built in.*

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![PDF.js](https://img.shields.io/badge/PDF.js-EC1C24?logo=adobeacrobatreader&logoColor=white)
![Bhashini](https://img.shields.io/badge/Bhashini-22_Indian_languages-orange)

**[🌐 Live Demo](https://NAREIN29.github.io/StandIQ/)**

</div>

---

## 🚩 The Problem

Government buyers write thousands of tenders for products such as LED street lights, cables, solar panels, cement and safety gear. Each product must meet the right **Indian Standard (IS)** and certification, such as the ISI mark or BIS registration.

- Officers often cite **outdated or wrong standards**, or miss mandatory certifications.
- Matching a specification to the correct standard needs **expert knowledge** that isn't always available.
- Tenders come in **many Indian languages**, and checking bidders' certificates is slow and manual.

## 💡 The Solution

StandIQ reads the tender, understands what is being bought, and recommends the standards and certifications that apply, with evidence and confidence for each one. A standards expert then reviews the result before it is used.

    Upload tender (PDF / DOCX / text / voice)
       → Extract requirements (product, specs, values)
       → Rank matching BIS standards with evidence
       → Standards expert reviews and decides
       → Procurement standards report (PDF)

---

## ✨ Features

### 📄 Tender analysis
- Upload **PDF, Word or text** tenders, or speak the requirement by **voice**
- Extracts products and technical values such as power (W), IP rating, luminous efficacy and cable cross-section
- Marks each requirement as **explicit**, **detected** or **missing**

### 🎯 Standards recommendation engine
- Ranks standards with a weighted score: semantic match, keywords, product, domain, scope and application
- **TF-IDF** text similarity plus a **concept graph**, so different wording with the same meaning still matches
- Shows the evidence sentence for every recommendation, with strong / possible / weak confidence
- Detects required certifications: **ISI mark, BIS registration (CRS), Hallmarking (HUID), NABL** and quality control orders

### 🧑‍⚖️ Expert review and learning
- Role-based workspace for **Procurement Officers** and **Standards Experts**
- Experts keep, remove or add standards with notes, and the engine **learns from their decisions**
- Review queue, history and **audit logs** for every action

### 📚 Standards knowledge base
- **49 verified standards** across lighting, solar, cables, IT equipment, construction, food and PPE
- Versions, amendments and supersession tracking, with **revision alerts**
- Compare standards side by side, and import or export the catalogue

### 🧾 Full procurement cycle
- **Spec generator** that writes standards-compliant tender specifications
- **Bid evaluation** that checks a bidder's document against the tender
- **Supplier certificate checks**
- **Insights for policymakers**: charts of trends across all analyses
- Downloadable **PDF report**

### 🌐 Language and accessibility
- **22 Indian languages** with translation and voice input through **Bhashini**
- **GIGW** (Government of India website guidelines) self-check
- Deployment readiness tracker (MeghRaj cloud, government sign-on, security audit) and a **GeM pilot** track

---

## 🧰 Tech Stack

| Layer | Technologies |
|---|---|
| **Frontend** | HTML5, CSS3, Vanilla JavaScript (single-page app) |
| **Document parsing** | PDF.js, Mammoth.js (Word), jsPDF (reports) |
| **Matching engine** | TF-IDF, cosine similarity, concept graph, weighted ranking, rule-based extraction |
| **Language** | Bhashini APIs (translation, speech recognition), MediaRecorder |
| **Hosting** | GitHub Pages |

---

## 🚀 Try the Demo

Open the **[live demo](https://NAREIN29.github.io/StandIQ/)** and sign in with a demo account:

| Role | What you can do |
|---|---|
| **Procurement Officer** | Create analyses from tenders and send them for review |
| **Standards Expert** | Review recommendations, manage the knowledge base and assign roles |

Demo data is stored only in your browser tab.

### Run locally

    git clone https://github.com/NAREIN29/StandIQ.git
    cd StandIQ
    open index.html

---

## 🗺️ Roadmap

- [x] Tender upload, requirement extraction and standards ranking
- [x] Expert review, learning from decisions and audit logs
- [x] Spec generator, bid evaluation and certificate checks
- [x] Bhashini languages and voice input
- [ ] FastAPI + PostgreSQL server version
- [ ] Full BIS catalogue intake with expert verification
- [ ] Hosting on MeghRaj with government single sign-on
- [ ] Pilot on the GeM portal

---

## 👤 Author

**Narein Muthukumaran**
B.E. Computer Science and Engineering, Saveetha School of Engineering · SIH 2025 Runner-Up

[LinkedIn](https://www.linkedin.com/in/narein-muthukumaran-s-524920402) · [GitHub](https://github.com/NAREIN29) · nareinsen29@gmail.com

---

<div align="center">

⭐ If you find this project useful, consider giving it a star!

</div>
