## 🧾 Project Overview
This project demonstrates a headless multi-brand storefront using **Salesforce B2C Commerce** and a custom frontend (React or PWA Toolkit). It features two lifestyle brands:
- **UrbanEdge** – Streetwear fashion
- **ZenNest** – Home & wellness products

The project is built using MACH principles: **Microservices**, **API-first**, **Cloud-native**, and **Headless**.

---

## ✨ Features
- 🛍️ Multi-brand catalog with brand-specific theming
- 🛒 Shared cart and checkout across brands
- 🧠 CMS-driven content using Contentful or Salesforce CMS
- 🌐 Responsive design for mobile and desktop
- 🔐 Optional JWT-based authentication

---

## 🧰 Tech Stack

| Layer       | Technology                  |
|-------------|------------------------------|
| Frontend    | React / PWA Toolkit          |
| Backend     | Salesforce B2C Commerce APIs |
| CMS         | Contentful / Salesforce CMS  |
| DevOps      | Docker, GitHub Actions       |
| Infra       | Vercel / Netlify / AWS       |

---

## 🏗️ Architecture
[Frontend (React/PWA)] <--> [Salesforce Commerce APIs] <--> [CMS (Contentful/Salesforce CMS)]
## 🚀 Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/MACHsmith/multibrand-storefront-salesforce.git
   cd multibrand-storefront-salesforce
   
2. **Install dependencies**
   ```bash
   npm install

4. **Run the frontend**
   ```bash
   npm start

6. **Connect to Salesforce backend**
   - Configure API endpoints and credentials
   - Enable CORS and API access
     
7. **CMS Integration**
   - Add Contentful or Salesforce CMS credentials
   - Sync content models

## 📄 License
MIT License
