# 11. Legal Lines for Tech Workers

> Software developers and IT professionals have access to tools that can easily cross criminal and civil lines. This chapter covers the boundaries.

---

### 1. Do not use your company's systems for personal snooping
- Cost: Zero.
- Plain language: Looking up your ex's address in the customer database, or reading a coworker's emails because you have admin access, is a fireable offence. It can also lead to criminal charges (Unauthorized Use of a Computer).
- Payoff: Avoids termination and a criminal record.
- Evidence: A (Criminal Code)
- Source: Criminal Code of Canada, s. 342.1.
- Note: Every query you run is logged. Companies frequently audit access logs when data breaches occur or complaints are made.

### 2. Never take source code when you leave a job
- Cost: Zero.
- Plain language: The code you wrote for your employer belongs to your employer (unless explicitly stated otherwise in your contract). Emailing the repo to your personal Gmail on your last day is theft of intellectual property.
- Payoff: Avoids devastating civil lawsuits (for breach of confidence and copyright infringement) and potential criminal charges (Mischief to Data or Theft over $5,000).
- Evidence: A (Intellectual Property Law)
- Note: This includes "helper scripts" you wrote on the clock. Leave with only your skills, not the code.

### 3. Comply with CASL (Canada's Anti-Spam Legislation) when building marketing tools
- Cost: Development time to implement opt-in flows.
- Plain language: You cannot send commercial electronic messages (emails, texts) to Canadians without their explicit or implied consent. You must include a working unsubscribe mechanism.
- Payoff: Avoids fines of up to $1 million for individuals and $10 million for corporations.
- Evidence: A (Federal Law)
- Source: CRTC. Canada's Anti-Spam Legislation.
- Note: "Pre-checked" consent boxes are not valid under CASL. Consent must be active.

### 4. PIPEDA: Do not collect data you don't need
- Cost: Development time.
- Plain language: Under Canada's privacy law (PIPEDA), you must get consent to collect personal information, you can only use it for the stated purpose, and you must protect it.
- Payoff: Avoids regulatory action from the Privacy Commissioner and class-action lawsuits following a data breach.
- Evidence: A (Federal Law)
- Source: Office of the Privacy Commissioner of Canada. PIPEDA in brief.
- Note: If you are building a database, ask: "Do we actually need the user's date of birth?" If no, don't collect it. Data you don't have can't be breached.

### 5. Web scraping can cross into civil and criminal liability
- Cost: Zero.
- Plain language: Scraping public data is generally legal, but bypassing authentication, ignoring rate limits, or ignoring explicit Terms of Service prohibitions can trigger lawsuits (e.g., breach of contract, trespass to chattels) or criminal charges (Unauthorized Use of Computer) if it damages the host's servers.
- Payoff: Avoids cease-and-desist letters and lawsuits.
- Evidence: B (Case Law)
- Note: Respect `robots.txt`, implement rate limiting in your scrapers to avoid causing a Denial of Service, and do not scrape data behind a login wall without permission.
