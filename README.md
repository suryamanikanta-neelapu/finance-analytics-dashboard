FinVault 
-->High-Performance State-Driven Finance Dashboard
        1.A professional-grade analytics interface built to demonstrate a mastery of Vanilla JavaScript and Information Architecture.
        2.This project avoids heavy frameworks to showcase core engineering principles: performance, reactivity, and clean DOM manipulation.
-->Tech StackEngine: 
        1.Vanilla JavaScript (ES6+)
        2.State: Centralized State Management Pattern
        3.UI/UX: Tailwind CSS (Modern Glassmorphism)
        4.Charts: Chart.js (Real-time data reconciliation)
-->Core Functionality
        1.Financial Summary: Real-time calculation of Balance, Income, and Expenses.
        2.Data Engine: Instant fuzzy search and categorical filtering.
        3.RBAC (Role-Based Access Control): * Viewer: Read-only access to charts and history.Admin: Write-access for record deletion and data modification.
        4.Automated Insights: Logic layer identifying top spending categories and savings ratios.
-->Architectural Decisions
        1.Reactivity: Instead of fragmented DOM updates, the app follows a State --> Render flow. Every user interaction updates a single source of truth (the state), which triggers a synchronized UI refresh.
        2.Responsive Logic: Implemented a mobile-first grid system that maintains data density across all device breakpoints.
        3.Performance: Near-zero overhead and instant load times by leveraging native browser APIs over external libraries.
-->Setup & Deployment
        1.Download the repository.
        2.Launch index.html in any modern browser.