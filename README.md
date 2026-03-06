MFI Internal Loan Management Portal (PoC)
Project Overview
This is a high-performance Angular & TypeScript proof-of-concept (PoC) designed for internal Microfinance (MFI) operations. The application demonstrates a reactive dashboard for loan officers to simulate, calculate, and visualize loan amortization schedules for clients in real-time.

Core Features
Reactive Loan Simulator: Built using Angular Reactive Forms and RxJS to provide instantaneous repayment calculations based on principal, interest rate, and term.

Amortization Engine: A custom TypeScript service that handles complex financial logic, ensuring precision in monthly principal vs. interest breakdowns.

Dynamic Data Visualization: Integrated charting (using Chart.js/Ng2-Charts) to visualize the interest-to-principal ratio over the life of the loan.

Staff Guarded Routes: Implementation of Angular Auth Guards to simulate a secure internal environment for authorized staff only.

Responsive Data Tables: Utilizes Angular Material for a clean, paginated, and sortable view of repayment schedules.

Technical Stack
Frontend: Angular 21 (Signals for state management)

Language: TypeScript (Strictly typed interfaces for all financial models)

Styling: Angular Material & SCSS (Custom theme consistent with banking standards)

Charts: Chart.js / Ng2-Charts

Utilities: RxJS for reactive data streams
