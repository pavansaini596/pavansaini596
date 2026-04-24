<!--
============================================================
 GitHub Profile README
 Repo name: pavansaini596  (same as username — special repo)
 Path in that repo: README.md  (root)
 This file renders on your profile: github.com/pavansaini596
============================================================
-->

<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=600&size=28&pause=1000&color=0D9488&center=true&vCenter=true&width=720&height=45&lines=Senior+Backend+Engineer;I+build+systems+that+don%E2%80%99t+drop+jobs.;7%2B+years+in+the+trenches+of+PHP+%26+MySQL;Laravel+%C2%B7+Redis+%C2%B7+Queues+%C2%B7+Reconciliation" alt="Typing SVG" />

<br />

[![Portfolio](https://img.shields.io/badge/%F0%9F%8C%90_Portfolio-pavansaini.com-0d9488?style=for-the-badge&labelColor=0a0a0a)](https://pavansaini.com/)
[![Calendly](https://img.shields.io/badge/%F0%9F%93%85_Book_a_Call-30_min-2ea44f?style=for-the-badge&labelColor=0a0a0a)](https://calendly.com/pavansaini596/30min)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0a0a0a)](https://www.linkedin.com/in/pavansaini596/)
[![Email](https://img.shields.io/badge/Email-pavansaini596%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0a0a0a)](mailto:pavansaini596@gmail.com)

</div>

---

### 👋 Hey, I'm Pavan

I'm a **Senior Backend Engineer** from India (GMT+5:30) with **7+ years** of shipping production systems where *correctness matters more than cleverness* — payments, wallets, reconciliation, queue pipelines, multi-vendor aggregators.

Most of my work is in **PHP / Laravel**, but the interesting part isn't the language — it's the 2am problems: webhooks firing three times, slot APIs going sideways during sales, ledgers drifting by ₹1,498 nobody can account for. I enjoy making those problems quietly disappear.

Currently processing **15K+ monthly transactions** on a production healthcare aggregator, and writing a small open-source Laravel package that extracts one of the patterns I leaned on most.

---

### 🧰 My stack — honestly grouped

<table>
<tr>
<td valign="top" width="33%">

**🟢 Daily driver**  
*reach for first, ship in prod*

- PHP 8.x · Laravel · CodeIgniter
- MySQL · Redis
- REST APIs · Queue workers
- Payment gateways · 3rd-party APIs
- Docker · Linux · Git

</td>
<td valign="top" width="33%">

**🟡 Comfortable**  
*read, write, ship as needed*

- JWT · OAuth · Rate limiting
- System design · Microservices
- Laravel Horizon · Telescope
- Postman · Swagger · OpenAPI
- JavaScript · jQuery · HTML/CSS

</td>
<td valign="top" width="33%">

**🟠 Learning & exploring**  
*currently deepening*

- Claude API · OpenAI SDK
- Redis Streams · Event sourcing
- Observability (Prometheus)
- Packagist package authoring
- Deeper Linux / infra

</td>
</tr>
</table>

---

### 🎯 Where I do my best work

- **Multi-tenant aggregator systems** — normalizing data from 3+ vendors into one clean API. Price matching, slot matching, inventory sync.
- **Wallet & ledger design** — append-only ledgers, idempotent writes, daily reconciliation jobs that don't lie.
- **Queue-driven workflows** — retries, dead-letters, idempotency keys, exponential backoff, observable by correlation id.
- **Payment reconciliation** — webhook dedup, gateway drift detection, refund recovery.
- **Legacy rescue** — CodeIgniter / old Laravel codebases where &ldquo;we can't touch it, it's holding together with prayers&rdquo;. Usually fixable.

All client work is under NDA, but I'm always happy to do a **live architecture walkthrough** on a 30-min call.

---

### 🧪 What I'm building right now

> **[`laravel-idempotent-webhooks`](https://github.com/pavansaini596/laravel-idempotent-webhooks)** — a drop-in Laravel middleware that makes any webhook route idempotent.

Extracted from real payment-reconciliation work. Three lines to add, one line to configure, solves the &ldquo;webhook fires three times at 2am&rdquo; problem using a unique index — no distributed locks, no races.

```php
Route::post('/webhooks/razorpay', [RazorpayController::class, 'handle'])
    ->middleware('idempotent:razorpay,header:X-Razorpay-Event-Id,24h');
```

If that resonates with anyone who's ever debugged a double-charged customer at 2am — check the repo, star it, or poke a hole in it. Feedback very welcome.

---

### 📊 Some stats

<div align="center">

<a href="https://github.com/pavansaini596">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=pavansaini596&show_icons=true&theme=github_dark&hide_border=true&include_all_commits=true&count_private=true&bg_color=0d1117&title_color=5eead4&icon_color=5eead4&text_color=c9d1d9" />
</a>
<a href="https://github.com/pavansaini596">
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=pavansaini596&layout=compact&theme=github_dark&hide_border=true&langs_count=6&bg_color=0d1117&title_color=5eead4&text_color=c9d1d9" />
</a>

<br />

<img src="https://github-readme-streak-stats.herokuapp.com?user=pavansaini596&theme=github-dark&hide_border=true&background=0d1117&stroke=5eead4&ring=5eead4&fire=5eead4&currStreakLabel=5eead4" height="165" />

</div>

---

### 💬 Let's talk

I'm **open to full-time remote** backend engineering roles worldwide — healthcare, fintech, e-commerce, enterprise SaaS, or anywhere a resilient backend changes the outcome. Based in India · reasonable timezone overlap, no problem.

The fastest way to reach me:

| Channel | Best for |
|---|---|
| 🌐 [**pavansaini.com**](https://pavansaini.com/) | The full story — projects, experience, FAQ |
| 📅 [**Book a 30-min call**](https://calendly.com/pavansaini596/30min) | Role fit, architecture walkthrough, or just a chat |
| 📬 [**pavansaini596@gmail.com**](mailto:pavansaini596@gmail.com) | Project briefs, detailed asks |
| 💼 [**LinkedIn**](https://www.linkedin.com/in/pavansaini596/) | Formal intros, DMs, staying in touch |

---

<div align="center">

*&ldquo;The best backend engineers don't write the most code — they write the code that doesn't wake anyone up at 2am.&rdquo;*

<sub>Thanks for stopping by. If you're shipping something hard on the backend — let's talk.</sub>

<br />
<br />

<img src="https://komarev.com/ghpvc/?username=pavansaini596&style=flat-square&color=0d9488&label=Profile+views" alt="Profile views" />

</div>
