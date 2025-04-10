# 🍣 Delivery Sushi – Food Business Locator

**Delivery Sushi** is a real-world full-stack web application built for a local food business. This platform helps users discover top-rated sushi restaurants and provides admin tools to manage menus, taxes, and promotions — with production-grade DevOps practices behind the scenes.

🔗 [View Live](https://www.ottawadeliverysushi.com).

📁 *Private GitHub Repository*

---

## 🧾 Project Overview

This app serves as a **food business locator**, helping customers discover highly rated sushi restaurants (4.5★+, 400+ reviews) in the Ottawa region. It also includes a backend admin dashboard to manage business operations — fully integrated with CI/CD, HTTPS redirection, and uptime automation.


---

## 🧱INFRASTRUCTURE

![Blank diagram](https://github.com/user-attachments/assets/10806249-cb32-4252-becd-86a9ed12cb4a)

---

## 🧱 Tech Stack

### Frontend
- HTML, CSS, JavaScript, jQuery

### Backend
- PHP, MySQL, phpMyAdmin
- XAMPP (Dev), HostGator + cPanel (Production)

### DevOps & Deployment
- AWS EC2
- Jenkins (CI/CD Pipeline)
- GitHub Webhooks
- Custom Bash Scripts

---

## 🛠️ Key Features

- 📍 **Restaurant Locator**  
  - Browse top-rated sushi restaurants with over 400 reviews

- 🧾 **Admin Controls**  
  - Add/edit menu items  
  - Update HST pricing  
  - Launch promotional banners & seasonal specials

- 🔄 **CI/CD Integration**  
  - Automated deployments via Jenkins on EC2  
  - GitHub webhook triggers for real-time updates

- 🛡️ **HTTPS Enforcement for Safari Compatibility**  
  - Enforced secure HTTPS via `.htaccess` to fix Safari access issues

---


## 🔭 Deployment Pipeline (DevOps Flow)

1. 🧑‍💻 **You push code to GitHub**  
   - Frontend (HTML, CSS, JS, jQuery)  
   - Backend (PHP)  
   - Database logic (MySQL schema updates or queries if versioned)

2. 🔔 **GitHub Webhook is triggered**  
   - GitHub sends a webhook payload to your Jenkins instance hosted on AWS EC2

3. 🤖 **Jenkins picks up the job**  
   - Jenkins pulls the latest code from GitHub  
   - Runs any build/test steps (if configured)  
   - Executes a custom Bash deployment script

4. 🛄 **Bash Script uses FTP/SFTP**  
   - Script uploads files directly to your cPanel directory on HostGator

5. 🌐 **HostGator (via cPanel) serves your site**  
   - Apache + PHP on the server processes backend logic  
   - Files are live — visible to users through HTTPS-secured URLs (thanks to `.htaccess`)

---


## 💡 Recent Updates

- ✅ Implemented HTTPS redirection in `.htaccess` (Safari fix)
- ✅ Integrated Jenkins on AWS EC2 with GitHub CI/CD
- ✅ Added seasonal menu items + updated HST logic
- ✅ Optimized for performance and mobile responsiveness


---

## 🙋‍♂️ About the Developer

I'm **Hans Kang**, a full-stack developer and DevOps enthusiast passionate about bridging business needs with tech-driven solutions.

- 🌐 [Portfolio](https://hanskang.com)  
- 📫 [LinkedIn](https://www.linkedin.com/in/hanskkang)
