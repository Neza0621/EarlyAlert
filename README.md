# EarlyAlert — Student Retention & Early Warning System

**EarlyAlert** is an interactive web interface prototype designed to identify students who may be at risk of dropping out and help educational institutions provide timely academic support.

The platform transforms academic indicators into clear, explainable risk alerts, helping coordinators, instructors, and student wellbeing teams make informed decisions.

## Features

- **Interactive Dashboard:** Visualizes student statistics, risk indicators, and alerts.
- **Multiple User Interfaces:** Four perspectives for Academic Coordinators, Wellbeing Teams, Instructors, and Students.
- **System Architecture:** A four-layer architecture covering data ingestion, storage, processing, and decision-making.
- **Data Flow Visualization:** An interactive five-step feedback loop explaining how information moves through the system.
- **Risk Score Simulator:** An adjustable weighted scoring model that calculates student risk levels in real time.
- **Responsive Design:** Adaptable layouts for desktop, tablet, and mobile devices.
- **Modern UI:** Glassmorphism, animated transitions, dynamic backgrounds, and interactive components.

## Technologies

- HTML5
- CSS3
- JavaScript (Vanilla)
- SVG
- Google Fonts (Inter)

No frontend frameworks or additional JavaScript libraries are required.

## System Architecture

The proposed architecture consists of four main layers:

1. **Ingestion:** Collects academic information from sources such as student information systems, attendance records, learning management systems, and payment records.
2. **Storage:** Processes and organizes incoming information through ETL operations and a data warehouse.
3. **Processing:** Applies a weighted risk model to evaluate student indicators.
4. **Decision:** Generates alerts and provides actionable information to academic coordinators and student wellbeing teams.

## Risk Assessment Model

The prototype uses a weighted scoring model with five academic and administrative indicators.

| Indicator | Weight |
|---|---:|
| Payment Arrears | 30% |
| Attendance Drop | 25% |
| Grade Decline | 20% |
| Previous Deferrals | 15% |
| Low LMS Usage | 10% |

**Alert Threshold:** 70/100.

The model is a conceptual proposal. Its weights would need to be validated through historical data and backtesting before real-world implementation.

## Getting Started

### Requirements

- A modern web browser (Chrome, Firefox, Edge, or Safari).
- An internet connection for loading Google Fonts.

### Installation

1. Download or clone this repository.
2. Locate the `index.html` file.
3. Open it directly in your browser.

Alternatively, run it using a local development server such as XAMPP.

No database configuration or backend installation is required for this interface demonstration.

## Project Purpose

EarlyAlert aims to support educational institutions in identifying potential student dropout risks before they become irreversible.

Its main principle is simple:

**Early detection. Clear explanations. Timely support.**

The system is designed to encourage intervention and student wellbeing, not punishment or discrimination.

## Project Status

**Phase 1 — Interactive Interface Demonstration**

This version focuses on the visual experience, system architecture, simulated user interactions, and conceptual risk assessment model.

It uses illustrative student data and client-side interactions. Backend integration, database persistence, real academic data processing, and a validated predictive model are not included in this version.

---

**Designed & Developed by Nezareth Gonzalez S.**  
*EarlyAlert — Supporting students before it's too late.*
