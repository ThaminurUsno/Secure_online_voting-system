# 🗳️ Secure Online Voting System
## CSE327 Project | Team NextGen

**Parliament Election of Bangladesh 2026**

---

## 📁 Project Structure

```
voting_system/
├── config/
│   ├── config.php          # App config (DB, admin credentials, constants)
│   └── bootstrap.php       # Loads all classes in correct order
├── classes/
│   ├── patterns/           # ★ DESIGN PATTERNS
│   │   ├── Database.php    # SINGLETON Pattern
│   │   ├── UserFactory.php # FACTORY Pattern
│   │   ├── AuthProxy.php   # PROXY Pattern
│   │   └── AuditDecorator.php # DECORATOR Pattern
│   ├── models/
│   │   ├── UserModel.php
│   │   ├── CandidateModel.php
│   │   ├── VoteModel.php
│   │   ├── OTPModel.php
│   │   └── UnbanModel.php
│   └── controllers/
│       ├── AuthController.php
│       ├── AdminController.php
│       ├── ModeratorController.php
│       ├── VoterController.php
│       └── MailController.php
├── views/shared/
│   ├── layout_top.php      # Sidebar + topbar HTML header
│   └── layout_bottom.php   # Closing HTML tags
├── admin/
│   ├── dashboard.php
│   ├── candidates.php
│   ├── tally.php
│   ├── voters.php
│   └── audit.php
├── moderator/
│   ├── dashboard.php
│   └── voters.php
├── voter/
│   ├── dashboard.php
│   ├── vote.php
│   ├── verify.php
│   ├── candidates.php
│   └── unban.php
├── assets/
│   ├── css/style.css
│   ├── js/app.js
│   └── images/candidates/  # Uploaded candidate photos
├── sql/
│   └── schema.sql          # Full DB schema + seed data
├── index.php               # Login / Register page
└── logout.php
```

---
