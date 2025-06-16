# Azure Static Web App Demo

This repository contains a simple static website built using HTML and CSS, deployed on **Azure Static Web Apps** using **GitHub Actions** for CI/CD. It is part of a two-repository project designed to demonstrate real-world Cloud Engineering and DevOps practices.

> ✅ This repo contains the **application (frontend)**.
> 🔧 Infrastructure as Code (IaC) for provisioning the Azure resources is maintained separately [here](https://github.com/kulkarniSreenidhi/azure-static-site-infra).

---

## 🌐 Live Demo

> 🚀 [Visit the deployed website here](https://your-azure-app-name.azurestaticapps.net)  
> *(Replace this with your actual deployed URL)*

---

## 📁 Project Structure

```bash
azure-static-site-demo/
├── index.html       # Home page
├── about.html       # About page
├── styles.css       # Global styles
├── .github/
│   └── workflows/
│       └── deploy.yml  # GitHub Actions workflow to deploy to Azure
└── README.md
