# 🚆 IRCTC Conversational IVR Modernization Framework

##  Project Overview
This project is developed as part of the Infosys Internship program. It aims to modernize traditional IVR systems by integrating conversational AI and voice-based interaction.

The system simulates an IRCTC railway service where users can:
- Check PNR status
- View train information
- Book tickets
- Interact using voice (IVR-like system)

---

##  Objectives
- Replace traditional keypad IVR with conversational interaction
- Improve user experience using voice input/output
- Simulate integration with modern AI platforms (ACS)

---

##  Project Modules

### 🔹 Module 1: System Analysis
- Studied traditional IVR systems
- Identified limitations and requirements

### 🔹 Module 2: Integration Layer
- Developed backend using FastAPI
- Acts as middleware between UI and system logic

### 🔹 Module 3: Conversational AI
- Implemented voice interaction
- Multi-step booking flow
- IVR-like system behavior

### 🔹 Module 4: Testing & Deployment
- Performed API testing using pytest
- Validated system flow (PNR, Train, Booking)
- Local deployment using FastAPI

---

##  Milestone Breakdown

| Milestone | Description |
|----------|------------|
| Milestone 1 | Analysis and Requirements |
| Milestone 2 | Backend Integration + UI |
| Milestone 3 | Voice + IVR Implementation |
| Milestone 4 | Testing and Deployment |

---

##  Technologies Used
- **Frontend**: HTML, CSS, JavaScript  
- **Backend**: FastAPI (Python)  
- **Voice**: Speech Recognition, Text-to-Speech  
- **Testing**: Pytest  

---

##  How to Run the Project

### 1. Install Dependencies
```bash
pip install -r requirements.txt
### 2. Run Server
uvicorn main:app --reload
### 3. Open in Browser
http://127.0.0.1:8000
### Running Tests (Milestone 4)
pytest
