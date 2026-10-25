# Research Report: No-Code FAQ Chatbot for College Admissions
**Student:** [Your name], 2nd-year CSE, Dhanalakshmi College of Engineering

## 1. Target audience
Prospective students and parents (primary); admissions office staff (secondary, receive escalations).

## 2. Research method (use at least two AI research tools)
| Tool | Prompt used (see 11_Prompt_Library) | Key finding |
|---|---|---|
| ChatGPT / Gemini | P1 Common admission questions | Most queries are about eligibility, dates, fees, documents, scholarships, placements |
| NotebookLM | P2 Summarise brochure + notices | Answers must be grounded in uploaded sources only |
| Claude | P3 Chatbot design principles | Add fallback, source-only answers, escalation triggers |
*(Paste your actual tool outputs/screenshots in an appendix.)*

## 3. Common question groups
Eligibility, process, courses, fees, scholarships, campus, placements, contact, policy (see 04_FAQ_Base.csv).

## 4. Chatbot design principles found
1. Answer only from verified public documents. 2. Say "I don't know" rather than guess. 3. Never promise seats, marks cutoffs or placements. 4. Always offer a human contact. 5. Keep answers short and cite the source. 6. Log unanswered questions to improve the FAQ.

## 5. Sources to collect and verify
College brochure, official website, admission notices, counselling/official guideline documents (e.g. TNEA site), fee notice. Record each in 09_Verification_Report.md.

## 6. Conclusion
A no-code bot grounded in a verified 40-question FAQ, with a fallback and human hand-off, can answer routine questions accurately while sending risky ones (dates, fees, outcomes) to staff.
