# ☁️ CloudNova Technologies — AWS Static Website

A static company website deployed on **Amazon Web Services (AWS)** using **Amazon S3 Static Website Hosting**.

This project demonstrates practical knowledge of **AWS S3, IAM, security, versioning, static website hosting, Git, and GitHub**.

> ⚠️ CloudFront was intentionally not used in this project.

---

## 📌 Project Overview

CloudNova Technologies is a fictional technology company website created to demonstrate how a static website can be deployed and managed using AWS cloud services.

The website contains:

- Home page
- About page
- Services page
- Contact page
- Custom 404 error page
- CSS styling
- JavaScript interaction

---

## 🏗️ Architecture

```text
                         🌍 Internet
                              │
                              │ HTTP
                              ▼
                    ┌───────────────────┐
                    │    Amazon S3       │
                    │ Static Website     │
                    │     Hosting        │
                    └─────────┬─────────┘
                              │
                              ▼
                    ┌───────────────────┐
                    │  Website Files     │
                    │                    │
                    │  index.html       │
                    │  about.html       │
                    │  services.html    │
                    │  contact.html     │
                    │  error.html       │
                    │  css/             │
                    │  js/              │
                    └───────────────────┘

                         🔐 IAM
                           │
                           ▼
                  Least-Privilege Access