# Umbraco Accessible DAW Prototype

## Project Goal

This project aims to develop a prototype Digital Audio Workstation (DAW) within the Umbraco 15 backoffice. A primary focus is prioritising accessibility.
## Early Development / Proof of ConceptCore Pillars
- Platform:  Umbraco 15 (.NET 8)
- Design: Accessible first (WCAG 2.2 AA)
- Outcome: Functional DAW prototype & Material for a technical presentation.

## Technology Stack (Planned)
- Backend: Umbraco 15, .NET 8, C#, Minimal APIs / API Controllers
- Frontend: Custom Umbraco Section, HTML, CSS, TypeScript/JavaScript, Web Audio API
- Umbraco Integration: Custom Sections, Document Types, Media Library

## Accessibility Focus

Accessibility is a core requirement, not an afterthought. Key considerations include:
- Full keyboard navigation and control.
- Semantic HTML structure and comprehensive ARIA implementation.
- Screen reader compatibility and testing (NVDA, JAWS, VoiceOver).
- Sufficient color contrast and visual clarity.
- Accessible alternatives for visual elements like timelines and waveforms.

## Quick Start / Setup

1. Prerequisites: .NET 8 SDK installed.
2. Clone: Clone this repository:
```
git clone https://github.com/jonnymuir/umbraco-daw.git
cd umbraco-daw
```
3. Navigate to Web Project:
```
cd daw.web
```
4. Run:
Start the Umbraco application:`dotnet run`
6. Setup Umbraco:
Open the application in your browser (e.g., `https://localhost:XXXXX`) and complete the Umbraco installation (SQLite is recommended for easy setup).
Log in using the credentials provided during dotnet new or created during setup.
7. Access the DAW: Once developed, the DAW interface will be accessible via a custom section in the Umbraco backoffice.
