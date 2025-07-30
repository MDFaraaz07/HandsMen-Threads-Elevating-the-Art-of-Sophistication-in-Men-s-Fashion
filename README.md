# HandsMen-Threads-Elevating-the-Art-of-Sophistication-in-Men-s-Fashion

**Salesforce SBVIP SkillWallet Internship Project • 2025**

---

## 🚀 Project Overview

HandsMen Threads is a Salesforce-powered CRM solution developed during the **SBVIP SkillWallet Internship (2025)**. The system automates business workflows including **order processing**, **inventory management**, and a **dynamic loyalty program**—tailored for fashion and retail brands.

---

## 📌 Key Features

- **Automated Order Confirmations** — Customers receive real‑time emails after placing orders  
- **Inventory Monitoring & Low‑Stock Alerts** — Email notifications triggered when stock drops below 5 units  
- **Loyalty Program Automation** — Apex Batch updates customer tiers automatically  
- **Secure Access Control via RBAC** — Profiles & permission sets enforce data access restrictions  
- **Modular Architecture** — Easily extendable for new features like Returns, Campaigns, or Multi‑brand Products

---

## 🧩 Project Data Model

| Object         | Purpose                              |
|----------------|--------------------------------------|
| Customer       | Stores client data and loyalty status|
| Order          | Tracks purchase transactions         |
| Product        | Product catalog with stock details   |
| Inventory      | Monitors current stock levels        |
| LoyaltyTier    | Defines reward tiers and points      |

✅ Relationship Logic:

- One‑to‑many: Customer ➝ Orders  
- Many‑to‑one: Orders ➝ Product  
- One‑to‑one: Customer ↔ LoyaltyTier

---

## 🛠️ Tools & Technologies

- **Salesforce Lightning App Builder** – Custom UI  
- **Record‑Triggered Flows** – Order confirmation, Stock alerts  
- **Apex Triggers & Batch** – Loyalty logic and data processing  
- **Validation Rules** – Ensures data integrity  
- **Scheduled Apex** – Nightly batch jobs for loyalty and inventory sync  
- **Email Templates** – Branded email notifications  
- **GitHub & SFDX CLI** – Source versioning and deployment workflow

---

## 📝 What You’ll Find in This Repo

handsmen_project/
├── force-app/ # Salesforce metadata: objects, classes, triggers, flows
├── screenshots/ # Project UI & flow screenshots
├── README.md # This overview file
└── Project Report.docx # Full-formatted report for submission

---

## ▶️ How to Clone & Deploy

```bash
git clone https://github.com/MDFaraaz07/HandsMen-Threads-Elevating-the-Art-of-Sophistication-in-Men-s-Fashion.git
cd "HandsMen-Threads-Elevating-the-Art-of-Sophistication-in-Men-s-Fashion"
sfdx force:source:deploy -p force-app
Optionally authenticate to your org using the Salesforce CLI before deployment.

🎥 Demo Video
Watch my walkthrough demo: [url]

📚 What I Learned
Building scalable CRM models in Salesforce

Designing declarative flows and validation logic

Writing Apex Triggers & Batch Classes

Applying best practices in data security and UI design

Effective deployment using Salesforce DX and Source Control

✍️ About the Author
Faraaz Khan
Salesforce Developer • 2025 SBVIP SkillWallet Intern
📧 Email: faraazk275@gmail.com
🔗 LinkedIn: www.linkedin.com/in/faraaz-khan078

