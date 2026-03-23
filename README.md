# Imesco - Personal Finance Tracker

Imesco is a lightweight, visually appealing personal finance tracker built as a single-file web app (index.html). It helps users set itemized daily and monthly monetary goals, log expenses and income, and manage savings split into two culturally relevant sub-accounts: "Naija Contribution" and "Finland Contribution". The app focuses on clear progress visualization, short actionable recommendations, and a calm, accessible UI.

Why this project matters
- Demonstrates end-to-end product thinking: from design choices (color, contrast, mascot) to functionality (goals, transactions, savings split).
- Shows attention to user experience and accessibility: readable typography, dimmed background with bright detail cards, and concise recommendations.
- Practical, immediately usable MVP that stores data locally and supports CSV export for analysis.

Key features
- Create and manage itemized goals (daily or monthly).
- Log expenses and income with categories, items and notes.
- Separate Income section.
- Savings accounts split into:
  - Naija Contribution
  - Finland Contribution
- Dashboard with goal progress, recommendations, recent transactions and savings quick-actions.
- Simple recommendation engine based on goal progress thresholds.
- Local persistence via localStorage (no backend required) and CSV export for portability.
- Light, professional UI with a bold SVG mascot.

Tech stack (MVP)
- Single-file web app: HTML, CSS and vanilla JavaScript
- Local persistence: localStorage
- Export: CSV generation in-browser
- Fonts: Inter (Google Fonts)
- Charts / visuals: CSS-based progress bars (simple, dependency-free)

Getting started (run locally)
1. Clone or download this repository.
2. Place the provided `index.html` in the project folder (or use the one in this repo).
3. Open `index.html` in your browser (modern Chrome/Firefox/Edge/Safari).
   - No server or build step required.
4. Use the UI to add goals, transactions, and savings deposits/withdrawals.
5. Export transactions via the Export CSV button when needed.

Notes on data & privacy
- All data is stored locally in your browser (localStorage). The app does not send data to any server.
- Use the CSV export feature to back up or move your data.
- For multi-device sync or cloud backup, consider adding an authenticated backend (e.g., Firebase, Node + Postgres).

How this project highlights professional strengths (for HR reviews)
- Initiative: Built a complete, user-facing MVP end-to-end.
- User-centered design: Clear visual hierarchy, accessible typography, meaningful feedback.
- Problem-solving: Implemented a recommendation engine and clear data model within a simple codebase.
- Cross-cultural awareness: Built-in savings split for different contribution contexts (Naija & Finland), showing empathy for international use cases.
- Communication-ready: The app and repo can be used to discuss product decisions, technical choices, and next steps during interviews.

Potential next steps / roadmap
- Convert to a React app with component-based structure and routing.
- Add an authenticated backend (Node/Express + Postgres or Firebase) for cross-device sync.
- Add recurring transactions, budget categories, and enhanced charts (Chart.js/Recharts).
- Add unit and integration tests, CI/CD, and secure backups.

Contributing
- This is an MVP. If you would like to propose improvements or contribute, please:
  1. Open an issue describing the change.
  2. Submit a pull request with clear, focused commits and a short description of the impact.
- Suggested areas for contribution: accessibility improvements, unit tests, multi-language support, or backend sync.


Contact
- LinkedIn: https://www.linkedin.com/in/imebisua-ikoh
- Email: imeisua4u@gmail.com

If you're an HR professional reviewing this project, I'd be happy to walk through design decisions, trade-offs, and how this project maps to product and stakeholder goals in a short demo or interview.
