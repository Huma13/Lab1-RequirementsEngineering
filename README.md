# Lab 1: Requirements Engineering & UML Use-Case Modelling

**Institution:** PES University – Department of Computer Science & Engineering  
**Student Name:** Huma  
**SRN:** PES2UG24AM066  
**Section:** 5A-AIML  

---

## 📌 Problem Statement #60
**Podcast Guest Scheduling & Outline Builder**

A web-based scheduling and episode preparation platform designed to streamline podcast interview coordination. The system enables **Show Hosts** to publish open time slots, **Podcast Guests** to book slots and submit structured discussion outlines (with optional biography links and headshots), and **Producers** to compile approved outlines into formatted PDF production sheets.

---

## 📂 Repository Contents (3 Final Deliverables)

| # | File Name | Description |
| :--- | :--- | :--- |
| **1** | `Requirements_Table_Huma_PES2UG24AM066.docx` | Complete Requirements Specification covering Functional Requirements (`FR-001` to `FR-005`) and Non-Functional Requirements (`NFR-001` to `NFR-002`) with priority, acceptance criteria, and rationale. |
| **2** | `Use_Case_Flow_Huma_PES2UG24AM066.docx` | Detailed Use-Case Flow Specification for **UC-02: Book Interview Slot**, including primary/secondary actors, `<<include>>` relationships, preconditions, postconditions, main success scenario, and alternate/exception flows (`4a`, `8a`). |
| **3** | `UML_Use_Case_Diagram_Huma_PES2UG24AM066.pdf` | Full UML Use-Case Diagram illustrating system boundaries, actors (**Podcast Guest**, **Show Host**, **Producer**), use cases (`UC-01` to `UC-07`), associations, `<<include>>`/`<<extend>>` dependencies, and requirement traceability. |

---

## 👥 Actors & Core Use Cases

* **Podcast Guest:**
  * `UC-01`: Browse Available Slots
  * `UC-02`: Book Interview Slot *(includes `UC-06: Send Calendar Invite`)*
  * `UC-03`: Submit Discussion Outline *(extended by `UC-07: Attach Biography Link`)*
* **Show Host:**
  * `UC-04`: Manage Host Availability
  * `UC-03`: Review & Approve Discussion Outline
  * `UC-05`: Generate Production Notes
* **Producer:**
  * `UC-05`: Generate Production Notes

---

## 🔗 Traceability Overview

* **Scheduling & Calendar Sync (`FR-001`, `FR-002`, `FR-003`):** Covered by `UC-01`, `UC-02`, `UC-04`, and `UC-06`.
* **Outline Submission & Host Moderation (`FR-001`, `FR-004`, `FR-005`):** Covered by `UC-03` and `UC-07`.
* **Performance & Usability (`NFR-001`, `NFR-002`):** Addressed through sub-second PDF production sheet generation (`UC-05`) and a streamlined mobile-friendly booking flow (`UC-01` – `UC-03`).
