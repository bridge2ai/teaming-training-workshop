# Module 4: Data Sharing and Resource Management (40 minutes)

**Facilitator:** Yulia Levites Strekalova, Clinical Care (CHoRUS)

**Materials:**
- [The FAIR Guiding Principles for scientific data management and stewardship (Paper)](https://drive.google.com/file/d/1AltSFugfMe7VLzObXUaf8TbcEfgXoVLP/view?usp=drive_link)
- [Messy Data Silos Compromise Patient Privacy (Audio)](https://drive.google.com/file/d/19mfupmeRzs7NbsV7mo_Xx1DoA049E607/view?usp=drive_link)

## Content Block: Team Data Sharing Agreement Negotiation (30 minutes)

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

## Activity 4: Team Challenge – The “Team Data Agreement” (20 minutes)

### **Team Challenge**

 As a group, you must negotiate the "Team Data Agreement" You have **20 minutes** to agree on:

- **Ownership:** Who "owns" the merged dataset?
- **Access:** Does the Clinic have the right to "veto" a data release?
- **FAIRness:** How will you make the data **Interoperable** without forcing everyone to buy the Tech Partner's software?

***

This cheat sheet is designed to bridge the gap between high-level data theory and the "on-the-ground" reality of a research team. It breaks down the **FAIR+** acronym through the lens of **Team Science**.

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

## Debrief (8 minutes)

Has your team identified the conflicts you didn’t realize existed?
Who owns the data if the Tech Partner goes bankrupt?

---

**Module Materials**

- [Pre-Read: The FAIR Guiding Principles for scientific data management and stewardship (PDF)](https://github.com/bridge2ai/teaming-training-workshop/blob/main/materials/Module-4/Module-4-FAIR-Principles.pdf)
- [Pre-Listen: Messy Data Silos Compromise Patient Privacy (Audio)](https://github.com/bridge2ai/teaming-training-workshop/blob/main/materials/Module-4/Module-4-Messy-Data-Silos-Compromise-Patient-Privacy.m4a)
- [Handout-1 (PDF)](https://github.com/bridge2ai/teaming-training-workshop/blob/main/materials/Module-4/Module-4-Handout-1.pdf)
- [Handout-2 (PDF)](https://github.com/bridge2ai/teaming-training-workshop/blob/main/materials/Module-4/Module-4-Handout-2.pdf)
- [FAIR+ Cheat Sheet (PDF)](https://github.com/bridge2ai/teaming-training-workshop/blob/main/materials/Module-4/Module-4-FAIRPlus-Cheat-Sheet.pdf)