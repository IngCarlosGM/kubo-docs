# 🧊 Kubo Docs

![version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![license](https://img.shields.io/badge/license-MIT-green.svg)
![status](https://img.shields.io/badge/status-in%20development-orange.svg)

📌 **Tags:** `AWS` `IaC` `Terraform` `NestJS` `Prisma` `PostgreSQL` `React` `Zustand` `DDD` `Microservices` `CI/CD`

---

## 🌟 What is kubo?

**Kubo** is an open-source platform, highly modular and decoupled, designed to efficiently manage **services**, **pipelines**, and **environment variables** within AWS environments. Inspired by the concept of a "container" (kubo), it encapsulates internal resources, facilitating scalability, adaptability, and reusability in modern technical teams.

This documentation centralizes technical information, practical guides, and links to various repositories that make up the entire kubo ecosystem.

---

## 🎯 Objective

Provide development teams with a robust, customizable tool to:

- Manage services, pipelines, and environment variables.
- Accelerate the adoption of best practices in modern architectures.
- Simplify control, security, and auditability in internal technical processes.

---

## 🚀 Purpose

Kubo aims to be a comprehensive solution, ready to clone, customize, and internally implement by any company seeking to optimize their technical cloud workflows with a clean, decoupled design prepared to scale toward more complex architectures such as microservices or microfrontends.

---

## 📖 Detailed Documentation

Check out the complete and detailed technical documentation on our [Official Wiki on Notion](https://carlosgm.notion.site/1bf8019e0991804bacc5ca3e575edd93?v=1c08019e0991809ab970000c4a34d214&pvs=4).

---

## 🗂 Project Structure

Kubo consists of the following repositories:

| Repository                     | Description                                                      |
|--------------------------------|------------------------------------------------------------------|
| 📚 [kubo-docs](https://github.com/IngCarlosGM/kubo-docs)               | Complete technical documentation for the ecosystem               |
| 🔹 [kubo-app-web](https://github.com/IngCarlosGM/kubo-app-web)            | Frontend built with React + Vite + Zustand                       |
| 🔸 [kubo-iac-frontend](https://github.com/IngCarlosGM/kubo-iac-frontend)       | Frontend Infrastructure using Terraform for AWS                  |
| 🔹 [kubo-app-service](https://github.com/IngCarlosGM/kubo-app-service)        | Modular monolithic backend using NestJS, Prisma, and PostgreSQL  |
| 🔸 [kubo-iac-backend](https://github.com/IngCarlosGM/kubo-iac-backend)        | Backend Infrastructure using Terraform for AWS                   |
| 🔹 [kubo-iac-modules](https://github.com/IngCarlosGM/kubo-iac-modules)        | Shared core Infrastructure modules                               |
| 🔸 [kubo-iac-pipelines](https://github.com/IngCarlosGM/kubo-iac-pipelines)      | CI/CD pipelines specific to the project                          |

---

## 🛠 Technology Stack

### Frontend
- React + Vite
- Zustand (State management)

### Backend
- NestJS (DDD light)
- Prisma ORM
- PostgreSQL

### Infrastructure
- Terraform (IaC)
- AWS (Amazon Web Services)

### CI/CD
- GitHub Actions
- AWS CodePipeline

---

## 🔐 Security and Authentication

- JWT authentication
- Role-based permission control: `Admin`, `Tech Lead`, `Dev`
- Comprehensive action auditing

---

## ⚙️ Core Domains

- 📌 **Services:** Management of services and microservices.
- 🔄 **Pipelines:** Management and tracking of CI/CD pipelines.
- 🌱 **Environment Variables:** Complete and secure management, history, and rollback.
- 🧐 **Audit actions:** Audit changes made by team members.
- ⚙️ **Settings:** Settings for delegating roles and viewing roles delegated by other teams.
- 🔐 **Authentication and Security:** Access, role management, and auditing.
- 📢 **Events and Notifications:** System events, notifications integrable with observability systems.

---

## 🌍 Supported Environments

- **Develop** (active development)
- **Staging** (testing and validation)
- **Production** (live production environment)

---

## 💡 How to Use Kubo?

Clone, customize, and adapt the repositories according to your internal requirements. Its decoupled design facilitates migrating from monolithic to microservice architectures.
