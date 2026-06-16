# USC-PIS Revision Response Log (June 2026 Finalization)

**GROUP LETTER:** [Insert Group Letter]  
**PROJECT TITLE:** University of San Carlos Patient Information System (USC-PIS)  
**DATE EVALUATED:** June 16, 2026

---

### ENTRY 1: INTER-PROFESSIONAL COORDINATION
**Recommendation/Comment:**
*Provide a clear method for different medical professionals (Doctors, Nurses, Dentists) to see each other's notes and coordinate patient care without violating data privacy.*

**Response:**
Thank you for pointing this out. We agree with this recommendation. Therefore, we have implemented the **Attributed Clinical Remarks system**. This feature allows medical staff to view a unified patient timeline containing clinical notes that are strictly attributed to their author (e.g., "Doctor [Name]" or "Nurse [Name]"). This ensures seamless coordination while maintaining an audit trail of who provided specific treatments.
*   **Location:** Chapter 3, Section 3.3.4 (Clinical Record Security Pipeline); Chapter 4, Section 4.3.4; and Appendix F (Test ID MRM-07).

---

### ENTRY 2: ADVANCED DATA FILTERING & MONITORING
**Recommendation/Comment:**
*The staff interface needs more granular filtering capabilities, specifically to monitor students by academic year and semester for school-wide health trends.*

**Response:**
Thank you for pointing this out. We agree with this recommendation. Therefore, we executed an **"Application Retooling" phase** to engineer an advanced real-time data filtering architecture. The staff-side interface now includes a dynamic filter bar that autonomously calculates semesters and isolates student cohorts by academic year level, allowing for instant monitoring of specific demographics.
*   **Location:** Chapter 3, Section 3.10.4; Chapter 4, Section 4.1.2 (Integration Test IT-04); and Appendix A (SDD Retooling Scope).

---

### ENTRY 3: REPORTING ENGINE EXPANSION
**Recommendation/Comment:**
*Rework the reporting module to provide professional-grade exports and a wider variety of clinical and administrative data categories.*

**Response:**
Thank you for pointing this out. We agree with this recommendation. Therefore, we have completely overhauled the professional reporting engine. The system now supports **nine diverse reporting categories** (e.g., Clinical Case Distribution, Operational Flow, etc.) and exports data natively to **five distinct formats** (PDF, Excel, CSV, JSON, and HTML). We also optimized the PDF engine for landscape-oriented, branded layouts.
*   **Location:** Chapter 3, Section 3.10.4; Chapter 4, Section 4.3.5 (Tables 4.7-4.10); and Appendix F (Reporting Engine Validation Table).

---

### ENTRY 4: READABILITY OF TECHNICAL DIAGRAMS
**Recommendation/Comment:**
*Major technical diagrams (ERD, Architecture, and Context Diagrams) are too small to read and lack sufficient detail.*

**Response:**
Thank you for pointing this out. We agree with this recommendation. Therefore, we have migrated all major technical diagrams (Figures 3.1, 3.2, 3.5, and 3.12) to **SidewaysFigure** environments. This allows the diagrams to occupy a full landscape page at maximum scale. We also enlarged the Context Diagram and Workflow Pipelines to **1.25x width** on dedicated pages to ensure all text and relational lines are perfectly legible.
*   **Location:** Chapter 3, Figures 3.1 through 3.12.

---

### ENTRY 5: MATHEMATICAL PROOF OF OBJECTIVES
**Recommendation/Comment:**
*Clearly demonstrate the attainment of the project's original objectives using quantifiable data from the testing phase.*

**Response:**
Thank you for pointing this out. We agree with this recommendation. Therefore, we added a new analytical section (**Section 4.3.7**) that mathematically justifies the successful achievement of Objectives 1 through 6. We utilized empirical improvement variances from our secondary comparative simulation (e.g., **+0.88 for reporting**, **+0.83 for campaigns**) to prove the system's massive operational gains over the manual baseline.
*   **Location:** Chapter 4, Section 4.3.7 (Attainment of Project Objectives) and Chapter 5, Section 5.2 (Conclusions).

---

### ENTRY 6: CLINICAL DATA STANDARDIZATION
**Recommendation/Comment:**
*Ensure all clinical workflows, especially medical certificates and dental records, follow standard professional terminology and institutional forms.*

**Response:**
Thank you for pointing this out. We agree with this recommendation. Therefore, we standardized the medical certificate workflow to follow **USC Form ACA-HSD-04F**, restricted fitness assessments to "physically fit/unfit," and documented the use of **FDI World Dental Federation notation (11-48)**. We also added the student-facing "Ready to be Claimed" status for digital certificates.
*   **Location:** Chapter 3, Section 3.2.2 (User Roles: Dentist) and Section 3.3.5 (The Medical Certificate Pipeline).

---

### ENTRY 7: DIFFERENTIATION OF UAT DATASETS
**Recommendation/Comment:**
*Clarify the distinction between the primary pilot test results and the secondary simulation to avoid confusing the reader.*

**Response:**
Thank you for pointing this out. We agree with this recommendation. Therefore, we have explicitly distinguished between the **Primary Pilot (N=70 students / N=7 staff)** and the **Secondary Simulation (N=30 students / N=8 staff)** throughout the Abstract, Chapter 4, and Chapter 5. We maintained separate satisfaction means (4.76/3.29 for primary and 4.73/4.17 for secondary) to ensure scientific transparency.
*   **Location:** Abstract, Section 4.3.5, and Section 5.2.

---

### ENTRY 8: PROJECT COSTS & SCOPE DEFERMENT
**Recommendation/Comment:**
*Update the cost estimates to reflect actual final expenses and justify why certain modules (Inventory/Scheduling) were deferred.*

**Response:**
Thank you for pointing this out. We agree with this recommendation. Therefore, we updated Appendix H to reflect the **actual finalized expenses (131,400.00 PHP)** incurred over 24 months. We also expanded Appendix N to formally justify the deferment of Inventory Management and Appointment Scheduling as a strategic decision to **ensure system stability, data security (PHI), and 100% SQA verification** of the core application.
*   **Location:** Appendix H (Finalized Project Costs) and Appendix N (Original Project Deliverables).

---

### GENERAL FORMATTING & POLISH
*   **Figure References:** Updated all abbreviated "Fig." instances to the formal text **"Figure"** (e.g., in Chapter 3).
*   **Interface Screenshots:** Enlarged all **29 screenshots** in Appendix L to **1.0x full text width** for maximum readability.
*   **Appendices:** Created **Appendix Q** (42+ individual survey charts) and **Appendix R** (Raw raw PDF data/survey files) to provide 100% data transparency.
*   **Submission Date:** Updated the official submission date on the Title Page to **June 2026**.
