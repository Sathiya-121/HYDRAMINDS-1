Markdown
# HYDRAMINDS | Cloud-Based Food Manufacturing ERP & Traceability Platform

An enterprise-grade, multi-tier food processing ERP and digital traceability platform designed to automate raw material quality control (QC), dynamic recipe formulation, FIFO/FEFO inventory management, rapid recall isolation, and consumer-facing QR provenance verification.

---

## 🏗️ Project Architecture

This application uses a multi-tier structure separating the Node.js backend API from the frontend assets:

```text
hydraminds-erp/
├── package.json           # Node.js dependencies and start scripts
├── server.js              # Express Backend API & In-Memory Enterprise Store
└── public/
    ├── index.html         # Frontend HTML UI (Tailwind CSS & FontAwesome)
    ├── style.css          # Custom Stylesheet & Theme Overrides
    └── script.js          # Client Logic & REST API Fetch Client
