# Module 4: Data Sharing and Resource Management (40 minutes)

### Facilitator: Yulia Levites Strekalova, Clinical Care (CHoRUS)

## Content Block: Collaborative Data Practices (15 minutes)

## FAIR Framework removed; Alternatives: ELSI, CARE, HIPPA, GDPR

### Opening Reality Check (2 minutes)
**Ask:** "How many of you have been part of a collaboration where data sharing was seamless and easy?"

**Say:** "Data sharing is often the biggest practical barrier to effective collaboration. Let's look at frameworks that make it work."

## Team Data Sharing Agreement Negotiation (30 minutes)

### **Scenario: Project "DeepHealth"**

**The Objective:** A multi-site study to develop an AI-driven tool that predicts health risks by merging genomic markers with social determinants of health (SDOH).

#### **The Stakeholders**

- **The University (Genomics Lab):** Focused on high-impact publications and "Open Science." They operate under a federal grant requiring data to be **Findable** and **Accessible** in public repositories within 12 months of collection.

- **The Community Clinic (Patient Advocacy):** Provides access to 5,000 high-risk patients. Their priority is **Security** and community trust. They are wary of "data extraction" and fear that sharing sensitive histories could stigmatize their patients or lead to insurance discrimination.

- **The Tech Partner (AI Solutions Corp):** Provides a proprietary machine-learning platform. They want the data to train their models, but they want to keep the "processed" data and the resulting algorithms **Secure** and proprietary for commercial use.

#### **The "Friction Points" (To be resolved)**

1. **The Interoperability Gap:** The Clinic’s data is in narrative PDF format (notes); the University’s is in structured genomic files. The Tech Partner wants both converted to their proprietary format, which the others cannot access without a paid license.

2. **The Timeline Conflict:** The University wants to upload raw genomic data to a public server _now_ to meet grant milestones. The Clinic wants a "Community Review Board" to approve every data release first.

3. **The Reusability Dilemma:** If the Tech Partner improves their AI model using this data, can the University use that improved model for their _next_ project without paying?

#### **Team Challenge**

 As a group, you must negotiate the "Data Prenup." You have **20 minutes** to agree on:

- **Ownership:** Who "owns" the merged dataset?
- **Access:** Does the Clinic have the right to "veto" a data release?

**FAIRness:** How will you make the data **Interoperable** without forcing everyone to buy the Tech Partner's software?

### Team Data Sharing Agreement: Project "DeepHealth"

1. **The Governance of "Who" (Ownership & Custodianship)**

- **The Primary Custodian:** Which partner is legally responsible for the storage and security of the _merged_ dataset?
- **The Intellectual Property (IP) Split:** If the Tech Partner’s AI improves using the University’s genomic data and the Clinic’s patient history, who owns the "improved model"? (e.g., Joint ownership, Tech Partner owns but University has free license, etc.)

2. **The FAIR+ Execution (The Technicals)**

- **Interoperability Standard:** To avoid the "PDF vs. Genomic" bottleneck, what will be the common "neutral" file format for shared analysis?
- **The Metadata Tax:** Who is responsible for the labor-intensive task of tagging and cleaning the data so it is **Findable**? How is this labor compensated/credited?

3. **The "Red Lines" (Security & Privacy)**

- **Veto Power:** Does the Community Clinic have the right to veto a public data release if they feel it risks "re-identification"?
 
    - [ ] Yes (Full Veto) [ ] Yes (Conditional Veto) [ ] No (Pre-agreed de-identification is sufficient)
 
- **Access Tiers:** Define who can see the raw, sensitive SDOH notes vs. the de-identified genomic markers.

4. **The Publication & Sharing Timeline**

- **The "Embargo" Period:** How many months does the University have to publish their primary findings before the data _must_ be made **Accessible** to the public per grant requirements?
 
- **The "Commercial Head-start":** How much time does the Tech Partner get to "vet" publications for trade secrets?
 
5. **Exit Strategy**

- If a partner leaves the project early:
    - Do they take "their" data with them?
    - Do the remaining partners lose the right to use the data already contributed?

### Debrief (8 minutes)

- Has your team identified the conflicts you didn’t realize existed?
- Who owns the data if the Tech Partner goes bankrupt?






This cheat sheet is designed to bridge the gap between high-level data theory and the "on-the-ground" reality of a research team. It breaks down the **FAIR+** acronym through the lens of **Team Science**.***

## **🔬 The FAIR+ Cheat Sheet for Research Teams**

### _A Guide to Collaborative Data Management_

#### **F — Findable**

_If you can't find it, it doesn't exist._

- **Metadata:** Data about the data. Does the file name Dataset\_V2\_Final\_ActualFinal.csv mean anything to a teammate six months from now?

- **Persistent Identifiers (PIDs):** Assigning a DOI or a unique ID so the data can be cited and located regardless of where it’s moved.

- **Searchability:** Is the data indexed in a place where your team (and the public, if required) can search for it?

#### **A — Accessible**

_Knowing it exists isn't the same as being able to open it._

- **Authentication:** Who has the "key"? Define the specific protocols (e.g., VPN, login credentials) required to reach the data.

- **Long-term Availability:** If the PI’s lab website goes down, where does the data live? (e.g., Institutional repositories like Zenodo or Dryad).

- **Open vs. Restricted:** "Accessible" doesn't always mean "Free for everyone." It means the _process_ for requesting access is clear and automated.

#### **I — Interoperable**

_Data should play well with others._

- **Machine-Readable:** Can a computer program (like an AI tool) ingest the data without a human having to manually re-format 1,000 PDFs?

- **Shared Vocabulary:** Does everyone on the team agree on what "Age" means? (e.g., Is it "Age at birth," "Age at enrollment," or "Age in months"?)

- **Non-Proprietary Formats:** Favoring .csv or .json over formats that require expensive, specialized software (like .sas7bdat or proprietary AI files).

#### **R — Reusable**

_Build for the future, not just the deadline._

- **Documentation (The "Readme"):** Does the data include a "User Manual" that explains the variables, the methodology, and the limitations?

- **Licensing:** Using clear licenses (like Creative Commons) so others know exactly how they are allowed to use, credit, or remix your work.

#### **+ — The "Plus" (Secure & Ethical)**

_FAIR is great; safe is better._

- **De-identification:** Ensuring human subject data is stripped of identifiers (HIPAA compliance).

- **Trust & Sovereignty:** Respecting the rights of communities (like the Clinic in our scenario) to control how their data is used, even if the data is "technically" findable.

- **Sustainability:** Ensuring the data remains secure and usable long after the grant funding ends.

***

**The Team Science Tip:** Data sharing is 20% technical and 80% cultural. Use these principles to build 

**Psychological Safety**—when everyone knows the rules, they are more likely to share their best work.


