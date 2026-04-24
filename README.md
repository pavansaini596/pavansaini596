<!--
============================================================
 GitHub Profile README  —  Pavan Saini
 Repo: pavansaini596/pavansaini596  (special profile repo)
 Path in repo: README.md (root)
 Renders at: https://github.com/pavansaini596
 Structure mirrors resume for consistency across channels.
============================================================
-->

<div align="center">

# Pavan Saini

### Senior Backend Engineer

**Specializing in scalable APIs & high-performance systems**

<br />

[![Portfolio](https://img.shields.io/badge/%F0%9F%8C%90_Portfolio-pavansaini.com-0d9488?style=for-the-badge&labelColor=0a0a0a)](https://pavansaini.com/)
[![Calendly](https://img.shields.io/badge/%F0%9F%93%85_Book_a_Call-30_min-2ea44f?style=for-the-badge&labelColor=0a0a0a)](https://calendly.com/pavansaini596/30min)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-pavansaini596-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0a0a0a)](https://www.linkedin.com/in/pavansaini596/)
[![Email](https://img.shields.io/badge/Email-pavansaini596%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0a0a0a)](mailto:pavansaini596@gmail.com)

<br />

🇮🇳 India (GMT+5:30) &nbsp;·&nbsp; 🌍 Open to Remote Worldwide &nbsp;·&nbsp; 💼 Full-time

</div>

---

## 👤 Profile Summary

- **Senior Backend Engineer** with **7+ years** of experience building scalable, transaction-heavy backend systems across **Healthcare and Enterprise** domains. Expertise in **PHP (Laravel, CodeIgniter)**, REST API architecture, MySQL performance optimization, aggregator platforms and secure payment integrations, booking engines, wallet systems.

- Proven ability to **reduce API latency, optimize database queries,** and deliver high-performance backend solutions for high-volume applications.

- Experienced in using **AI tools like ChatGPT and Claude** for development productivity and integrating AI APIs for automation and intelligent workflows.

---

## 💼 Organizational Experience

### 🟢 Interactive12 · *SpiceJet — Flebo.in & Dialer Projects* — Senior Software Developer

`Feb 2023 — Present` · Full-Time

**Flebo.in** (Laravel)
- Implemented **multi-lab aggregator engine** (price, location, slot filtering)
- Developed **wallet system** managing secure transaction ledger and reconciliation workflows
- Integrated **3rd-party APIs** (Healthians, Redcliffe, Agilus) with sync logic
- Designed and optimized **REST APIs handling 15K+ monthly transactions** with scalable booking workflows
- Integrated payment gateway with booking confirmation workflow
- Built report upload, notification & doctor consultation modules

**Call Center Dialer** (Laravel)
- Engineered **auto-dialing backend** handling bulk outbound campaigns with retry logic and structured lead lifecycle management
- Integrated telephony APIs for outbound campaign automation
- Implemented retry scheduling & call disposition logic
- Built real-time call logs & performance analytics modules

### TechnoCravers Pvt. Ltd., Delhi · *SpiceJet — SpiceHealth Project* — Senior Software Developer

`Jan 2021 — Feb 2023` · Full-Time

**SpiceHealth** (CodeIgniter)
- **Optimized MySQL queries reducing API response time by ~30%**
- Designed complete sample lifecycle workflow (*Booking → Collection → Processing → Report Upload*)
- Developed role-based panels for Admin, Lab, Phlebotomist & Patients
- Built end-to-end pathology booking platform supporting high-volume daily operations across multiple roles
- Implemented secure payment gateway integration
- Developed report upload system with status tracking & notifications

### UWS Inc, Jaipur — Software Developer

`Jun 2020 — Dec 2020` · Full-Time

- **Employee Management System** — payroll, attendance tracking, reporting & data workflows
- **News Selling Platform** — subscription-based platform with admin, buy/sell workflow & payment logic

### PHP Development (Freelance) — Backend Developer

`Jan 2020 — Jun 2020`

- **School Management System** — attendance tracking, fee management, role-based admin panel

### Ekaaksh Innovation Pvt Ltd, Jaipur — Software (PHP) Developer

`Oct 2019 — Dec 2019` · Full-Time

- Employee Attendance Management System; WordPress and Core PHP projects

### Zrose Technology, Jaipur — Web Developer *(first role)*

`Mar 2019 — Sep 2019`

- **Find Doctor in Easiest Way** — Doctor Appointment Marketplace with multi-role panels (Super Admin, Doctor, Patient), slot-based scheduling

---

## 🛠 IT Skills

| Category | Stack |
|---|---|
| **Backend** | PHP (Laravel, CodeIgniter), REST API Development, System Design |
| **Database** | MySQL (Query Optimization, Indexing) |
| **Caching & Performance** | Redis, API Optimization, Caching Strategies |
| **Architecture** | Scalable Systems, Microservices Basics, Queue Systems (Laravel Queues, Background Jobs) |
| **API & Security** | Authentication, Authorization, JWT, API Versioning, Rate Limiting |
| **Integrations** | Payment Gateway Integration, Third-party APIs |
| **Tools & Technologies** | Git, Postman, Swagger (API Documentation), Docker (Basic), Logging, Error Handling & Debugging |
| **Deployment & Server** | Linux Basics, Hosting, cPanel / VPS |
| **Frontend** | JavaScript, HTML, CSS, Bootstrap, AJAX, jQuery |
| **CMS** | WordPress, Drupal |
| **AI & Automation** | ChatGPT, Claude, AI API Integration |

---

## 🎓 Education

**B.Tech · Computer Science Engineering**
Rajasthan Technical University · 2016 — 2020

**Training & Certification**
- C Programming Language — Alpine Technology Pvt. Ltd., Alwar
- Web Development Training — Zrose Technology, Jaipur *(2019)*

---

## 🧪 What I'm building right now

> **[`laravel-idempotent-webhooks`](https://github.com/pavansaini596/laravel-idempotent-webhooks)** — a drop-in Laravel middleware that makes any webhook route idempotent.

Extracted from real payment-reconciliation work. Three lines to add, one line to configure, solves the &ldquo;webhook fires three times at 2am&rdquo; problem using a unique index — no distributed locks, no races.

```php
Route::post('/webhooks/razorpay', [RazorpayController::class, 'handle'])
    ->middleware('idempotent:razorpay,header:X-Razorpay-Event-Id,24h');
```

If that resonates with anyone who's ever debugged a double-charged customer — check the repo, star it, or poke a hole in it.

---

## 📊 GitHub Activity

<div align="center">

<a href="https://github.com/pavansaini596">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=pavansaini596&show_icons=true&theme=github_dark&hide_border=true&include_all_commits=true&count_private=true&bg_color=0d1117&title_color=5eead4&icon_color=5eead4&text_color=c9d1d9" />
</a>
<a href="https://github.com/pavansaini596">
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=pavansaini596&layout=compact&theme=github_dark&hide_border=true&langs_count=6&bg_color=0d1117&title_color=5eead4&text_color=c9d1d9" />
</a>

</div>

---

## 💬 Let's talk

I'm **open to full-time remote** backend engineering roles worldwide — healthcare, fintech, e-commerce, enterprise SaaS, or anywhere a resilient backend changes the outcome.

| Channel | Best for |
|---|---|
| 🌐 [**pavansaini.com**](https://pavansaini.com/) | Full portfolio — projects, experience, FAQ |
| 📅 [**Book a 30-min call**](https://calendly.com/pavansaini596/30min) | Role fit, architecture walkthrough, or a quick intro |
| 📬 [**pavansaini596@gmail.com**](mailto:pavansaini596@gmail.com) | Project briefs & detailed asks |
| 💼 [**LinkedIn**](https://www.linkedin.com/in/pavansaini596/) | Formal intros & staying in touch |

<div align="center">

<br />

<sub>Software Development · Requirement Gathering · Database Development & Lifecycle Management</sub>

<br />
<br />

<img src="https://komarev.com/ghpvc/?username=pavansaini596&style=flat-square&color=0d9488&label=Profile+views" alt="Profile views" />

</div>
