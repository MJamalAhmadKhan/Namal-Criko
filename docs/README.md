# 🏏 Namal Criko - SRS Documentation

This directory contains the primary technical documentation for the **Namal Criko** project. The Software Requirements Specification (SRS) follow the **IEEE Standard 830-1984** to provide a professional foundation for the design and development phases.

---

## 📂 Folder Contents

| File / Folder | Description |
| :--- | :--- |
| `Namal_Criko_SRS.tex` | Professional LaTeX source file containing the complete SRS document. |
| `Namal_Criko_SRS.pdf` | The compiled, ready-to-print PDF version of the requirements. |
| `/images` | Sub-directory containing all modeling elements and diagram assets. |

---

## 📊 Modeling Elements

Per the milestone requirements, the following diagrams are included as appendices to define system architecture and behavior:

### 1. Context Diagram (Level 0 DFD)
Establishes the high-level relationship between the external entities (**Player** and **Admin**) and the **Namal Criko System**.

### 2. Level 1 Data Flow Diagram (DFD)
Visualizes the internal data movement between the following core processes:
* **User Authentication:** Managing secure Login and Sign-up.
* **Simulator Engine:** Facilitating interactive technique requests.
* **Administration System:** Handling user verification and content updates.
* **Help Desk:** Processing user queries and technical support.



---

## 📝 Document Highlights

The documentation reflects several critical requirements validated during the **2nd Meeting with the Requirement Provider (RP)**:

* **Mandatory Admin Authorization:** All new accounts remain in a "Pending" state until an Admin manually approves access.
* **Hybrid Learning Model:** Integration of 2D/3D simulations with descriptive technical text.
* **Specialized Training Categories:** Categorized training paths for Batting and Bowling (including Fast, Spin, and Slow styles).
* **Performance Metrics:** Tracking of player statistics such as Matches Played and Run Rate.

---

## ⚙️ Compilation Environment
This document was authored in LaTeX using the following configurations:
* **Document Class:** `article` (12pt, A4 Paper)
* **Key Packages:** `fancyhdr` (Headers/Footers), `longtable` (Data lists), `titlesec` (Standardized hierarchy).
* **Template Standard:** IEEE 830/29148 outline.

---
*Created as part of CSC-225 Software Engineering – Namal University Mianwali.*
