# Codibu.com

> ⚠️ **Note:** The **core repositories of Codibu.com are private and owned by the client.**  
> This repository only contains a **public project overview and documentation** for demonstration purposes.  
> No proprietary code is shared here.  

🌐 **Live Project:** [https://www.codibu.com](https://www.codibu.com)

---

## Table of Contents

- [Features](#features)  
- [Technologies Used](#technologies-used)  
- [Project Highlights](#project-highlights)  
- [How It Works](#how-it-works)  
- [Agile Testing & Deployment](#Agile Testing & Deployment)   

---

## Features

- **Automated WordPress Site Creation**  
  Users can launch a fully functional WordPress website in a few clicks. The system provisions a WordPress instance on **AWS Lightsail**, installs the selected demo theme, and provides all site details in the dashboard.  

- **Domain Purchase, Transfer & Management**  
  Users can buy or transfer domains and manage them from the **Codibu dashboard**. Integrated with **AWS Route 53**, and SSL certificates are automatically issued upon successful domain connection.  

- **Subscription & Payment Management**  
  Integrated **Stripe** and **PayPal** to handle subscriptions securely. Users can view payment history, update payment methods, and switch between platforms seamlessly.  

- **Flexible User Authentication**  
  Users can register or log in via **Google, Facebook, Amazon**, or manual email registration with **email verification**.  

- **GPLDL Themes & Plugins Management**  
  Users can freely download premium GPLDL themes and plugins. The system automatically checks for updates, downloads the latest versions, and provides them to users at no cost.  

- **Single Sign-On (SSO) Integration**  
  Allows users to **log in to other platforms using their Codibu.com credentials**, providing a seamless cross-platform experience and centralized access management.  

- **Support Ticket & Live Notifications**  
  Implemented a **support ticket system** allowing users to submit issues, track progress, and receive responses directly in their dashboard. **Real-time notifications** keep users instantly updated about support replies, payments, domain status, and system updates.  

---

## Technologies Used

- **Backend:** Laravel (PHP Framework)  
- **Cloud Services:** AWS Lightsail, AWS Route 53  
- **Payment Gateways:** Stripe, PayPal  
- **Authentication:** Social logins (Google, Facebook, Amazon), Email verification, SSO  
- **Real-Time Features:** Live notifications, support ticket system  

---

## Project Highlights

- End-to-end development from planning and research to deployment  
- Remote development for a U.S. client  
- **Live SaaS platform running at [Codibu.com](https://www.codibu.com)**  
- Scalable SaaS architecture with automated provisioning and updates  
- Focus on user experience, automation, and performance  

---

## How It Works

1. Users sign up via social login or email verification.  
2. Users create a WordPress website in a few clicks — the system provisions the site on AWS Lightsail.  
3. Users purchase or transfer a domain; the system automatically configures DNS and SSL.  
4. Users manage subscriptions through Stripe or PayPal and view payment history.  
5. Users can download GPLDL themes/plugins with automatic updates.  
6. Users can access other platforms via SSO using Codibu credentials.  
7. Users submit support tickets and receive **real-time notifications** for updates, payments, and system alerts.  

---

## Agile Testing & Deployment

- Configured **GitHub Actions** to automatically validate code and ensure smooth collaboration on every push and pull request.  
- Follows Agile-style practices by providing rapid feedback and preventing broken code from being merged.  
- Once changes are merged or pushed to the **main branch**, GitHub Actions automatically deploys the latest version to the production server.  
- This setup reduces manual steps, speeds up delivery, and keeps the production environment up to date with minimal effort.

