# HapticVerse

HapticVerse is an interactive, simulation-based educational platform developed to enhance practical learning in dental training through immersive 3D technology. 

This project was created as a joint collaborative effort between **Jaya Engineering College** and **Ragas Dental College** to provide dental students with a repeatable, accessible, and high-fidelity environment for clinical skill development.

---

## The Challenge in Dental Education
Traditional dental education relies heavily on theoretical textbooks, static lectures, and limited clinical hours with live patients. Because clinical exposure is bounded by schedule constraints and patient availability, students frequently lack opportunities to repeatedly practice foundational diagnostic skills—such as identifying dental debris, calculus, and stains. Without consistent hands-on repetition, mastering these visual and physical assessments remains a bottleneck in undergraduate training.

## Our Solution
HapticVerse bridges this clinical gap by introducing a virtual training environment where students can interact with realistic 3D dental models. The platform digitizes the clinical workflow, allowing students to perform observation-based diagnostic tasks and receive automated, structured evaluations. By combining engine-driven visualization with academic management workflows, HapticVerse acts as a comprehensive software tool for both instructors and learners.

### Key Capabilities
* **Interactive 3D Tooth Simulation:** Detailed dental models with multi-camera navigation and orbital controls to inspect individual tooth surfaces from any angle.
* **Clinical Diagnostics & Indexing:** Direct detection and marking of localized debris, stains, and calculus, featuring automated calculations for metrics like the **Oral Hygiene Index (OHI)**.
* **Integrated Workflow System:** Dedicated dashboards for teachers to assign specific practical tasks and monitor student progression.
* **Session Persistence:** Built-in save and load functionalities to let students pause, resume, and archive their evaluation sessions.

---

## Technical Architecture

The platform combines real-time game engine technology, digital 3D asset creation pipeline, and standard database backends to ensure a lightweight yet robust application.

* **Core Engine & Logic:** Godot Engine (GDScript)
* **3D Assets & Interface Design:** Blender, Figma
* **Backend, API & Database:** Firebase, PHP, MySQL
* **Graphic Assets & Texturing:** Krita, Adobe Photoshop

---

## How It Works

1. **Assignment:** Instructors deploy specific diagnostic cases or tasks to the student cohort through the platform.
2. **Simulation & Navigation:** The student opens the assigned 3D dental model, using multi-camera interaction to inspect the dentition.
3. **Evaluation:** The student identifies, marks, and categorizes conditions like plaque, calculus, or staining directly on the model.
4. **Automated Calculation:** The system evaluates the inputs, automatically calculates the corresponding OHI metrics, and provides an instant scoring summary.
5. **Data Sync:** Results and progress records are pushed to the database for instructors to review and analyze performance curves.

---

## Project Status & Vision
HapticVerse was established to prove that modern real-time interactive technology can fundamentally enhance healthcare training. By decoupling foundational diagnostic training from strict laboratory hours, the project makes high-quality practical dental learning accessible and infinitely scalable.

The core platform has been completed and is under continuous iteration to expand clinical use cases, refine user interfaces, and integrate additional dental indexing systems.

---

## Project Team & Collaboration
* **Collaborating Institutions:** Jaya Engineering College & Ragas Dental College
* **Development Team:** Mogana Murali D, Gopika
