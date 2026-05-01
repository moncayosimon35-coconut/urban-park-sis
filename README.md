# 🌳 Urban Park Sis
**Innovative Urban Park Management System for Santander, Colombia.**

Urban Park Sis is a cutting-edge technological solution designed to transform how public spaces are managed. This system leverages **PostgreSQL/Oracle** database structures to optimize maintenance, security, and accessibility, ensuring that parks are safe, enjoyable, and inclusive for all citizens.

## 🌟 Core Focus
*   **Technological Innovation:** Integration of **IoT devices**, **AI-powered analytical cameras**, and **multiservice Wi-Fi posts**.
*   **Safety & Security:** Dedicated modules for surveillance centers, security personnel, and real-time IA incident reporting.
*   **Inclusive Design (A11Y):** Specialized tracking of accessibility assets and **audio-guided beacons** specifically designed for the elderly and people with disabilities.
*   **Citizen Engagement:** Features for community events, PQRSD reporting, and emergency SOS points to foster a sense of ownership and enjoyment of public spaces.

## 🛠️ Database Architecture
The system is organized into several strategic modules based on the schema in `gemini-code-1777245739320.sql`:

### 1. Geography & Organization
Manages the hierarchical structure from municipalities and communes down to specific parks and their usage zones (`municipio`, `comuna`, `parque`, `zona_uso`).

### 2. Stakeholders (People)
A comprehensive classification system for:
*   **Citizens:** Including detailed profiles with disability status and socioeconomic data.
*   **Servers:** Specialized roles such as security, emergency, cleaning, and business operators.

### 3. Smart Infrastructure (IoT & AI)
*   **Analytical Cameras:** Tracks hardware specs and links to **AI Reports** (`reporte_ia`) for automated event detection.
*   **IoT Devices:** Generic sensors and **Smart Trash Cans** (`caneca_inteligente`) with telemetry and differential alert rules.

### 4. Accessibility & Maintenance (A11Y)
Dedicated tables for accessibility assets and maintenance history, ensuring facilities for vulnerable populations are always operational.

### 5. Urban Services & Emergencies
*   **SOS Points:** Physical locations with panic buttons, first aid, and defibrillators.
*   **Connectivity:** Managed Wi-Fi zones and smart power outlets.
*   **Economic Management:** Control of businesses and commercial permits within park zones.

### 6. Administration & Procurement
Handles the lifecycle of contracts, contractors, bidding processes (`licitacion`), and work orders (`orden_trabajo`) to ensure transparency in park improvements.

---
**Developed by a Systems Engineering student** committed to improving urban life through technology and user-centric data management.
