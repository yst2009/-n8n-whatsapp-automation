# 🤖 WhatsApp Translation Automation Service

A fully automated SaaS workflow built with **n8n** and **WhatsApp Cloud API** to handle translation requests without human intervention.

## 🚀 Key Features
- **Automated Request Handling:** Routes PDF documents and payment screenshots intelligently.
- **Dynamic File Management:** Creates organized client folders in Google Drive automatically.
- **Payment Verification:** Processes payment screenshots and updates status in Google Sheets.
- **Scheduled Delivery:** Uses Cron jobs to deliver finished files to customers instantly.

## 🛠️ Tech Stack
- **Orchestration:** n8n (70+ Nodes)
- **API Integration:** WhatsApp Cloud API, Google Drive API, Google Sheets API
- **Logic:** JavaScript (ES6) for data transformation & validation.

## 📂 Project Files
- **Workflow:** The full logic is in the `whats_integration.json` file above.
- **Architecture:** Please refer to the image file in the repository list to see the system design diagram.
