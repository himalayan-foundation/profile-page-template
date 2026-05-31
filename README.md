<h1 align="center">Academic & Professional Page Template</h1>

<p align="center">
  A clean, elegant, zero-dependency personal website template.<br>
  <strong>One template — works for everyone.</strong>
</p>

<p align="center">
  <a href="#-quick-start"><img src="https://img.shields.io/badge/Quick_Start-5_minutes-500000?style=for-the-badge"></a>
  <a href="#-who-is-this-for"><img src="https://img.shields.io/badge/9_Personas-Supported-7a1c1c?style=for-the-badge"></a>
  <a href="#-live-demo"><img src="https://img.shields.io/badge/Live_Demo-View-c8a96e?style=for-the-badge"></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML-Plain-orange">
  <img src="https://img.shields.io/badge/Build_Tools-None-brightgreen">
  <img src="https://img.shields.io/badge/Dependencies-Zero-brightgreen">
  <img src="https://img.shields.io/badge/Hosting-GitHub_Pages_Free-blue">
  <img src="https://img.shields.io/badge/License-MIT-lightgrey">
</p>

---

## 🟢 Live Demo

**Foundation site (root):** https://himalayan-foundation.github.io
**Generic template (subdirectory):** https://himalayan-foundation.github.io/academic-page-template

---

## 👥 Who Is This For?

Click the badge that matches you. Each one tells you exactly which sections to enable.

<table>
<tr>
<td align="center">
  <a href="#-professor"><img src="https://img.shields.io/badge/👨‍🏫_Professor-500000?style=for-the-badge"></a><br>
  <sub>Faculty, researchers, lab heads</sub>
</td>
<td align="center">
  <a href="#-phd--ms-student"><img src="https://img.shields.io/badge/🎓_PhD_/_MS_Student-7a1c1c?style=for-the-badge"></a><br>
  <sub>Graduate students, researchers</sub>
</td>
<td align="center">
  <a href="#-teacher"><img src="https://img.shields.io/badge/📚_Teacher-9b2c2c?style=for-the-badge"></a><br>
  <sub>K-12 / college instructors</sub>
</td>
</tr>
<tr>
<td align="center">
  <a href="#-engineer"><img src="https://img.shields.io/badge/💻_Engineer-2563eb?style=for-the-badge"></a><br>
  <sub>Software, hardware, any level</sub>
</td>
<td align="center">
  <a href="#-manager--executive"><img src="https://img.shields.io/badge/💼_Manager_/_Exec-1e40af?style=for-the-badge"></a><br>
  <sub>Leaders, directors, VPs</sub>
</td>
<td align="center">
  <a href="#-consultant--freelancer"><img src="https://img.shields.io/badge/🤝_Consultant-0e7490?style=for-the-badge"></a><br>
  <sub>Independent, contract</sub>
</td>
</tr>
<tr>
<td align="center">
  <a href="#-founder--entrepreneur"><img src="https://img.shields.io/badge/🚀_Founder-c2410c?style=for-the-badge"></a><br>
  <sub>Entrepreneurs, startup CEOs</sub>
</td>
<td align="center">
  <a href="#-researcher-non-academic"><img src="https://img.shields.io/badge/🔬_Researcher-15803d?style=for-the-badge"></a><br>
  <sub>Industry / nonprofit research</sub>
</td>
<td align="center">
  <a href="#-nonprofit--organisation"><img src="https://img.shields.io/badge/🌍_Nonprofit_/_Org-166534?style=for-the-badge"></a><br>
  <sub>Foundations, NGOs, labs</sub>
</td>
</tr>
</table>

---

## 🚀 Quick Start

### Step 1 — Use this template
Click the green **"Use this template"** button at the top of this repo → **"Create a new repository"**

Name it:
- `your-username.github.io` → site lives at root
- anything else → site lives in subdirectory (one extra config line, see below)

### Step 2 — Pick your persona below
Scroll to your persona section. Copy the `sections.json` block for your use case.

### Step 3 — Edit your content
Open each enabled JSON file in `data/` and replace placeholder content with yours.

### Step 4 — Add your photo (optional)
Drop a photo at `assets/img/profile.jpg`. If none, the site shows initials gracefully.

### Step 5 — Set up the contact form (2 minutes)
1. Go to [web3forms.com](https://web3forms.com) → enter your email → copy your Access Key
2. Paste it into `profile.json` as `"form_access_key"`
3. Done — no backend, no cost

### Step 6 — Enable GitHub Pages
Repo → **Settings** → **Pages** → Source: `main` branch, `/ (root)` → Save
Live in 60 seconds.

---

## 📋 Persona Guides

Each guide shows you the exact `sections.json` config to copy.

---

### 👨‍🏫 Professor

![Use](https://img.shields.io/badge/Best_For-Faculty,_Lab_Heads,_Researchers-500000)

**Enable these 8 sections:**

```json
[
  { "id": "about",        "title": "About",         "file": "profile.json",      "enabled": true },
  { "id": "research",     "title": "Research",      "file": "research.json",     "enabled": true },
  { "id": "publications", "title": "Publications",  "file": "publications.json", "enabled": true },
  { "id": "news",         "title": "News",          "file": "news.json",         "enabled": true },
  { "id": "awards",       "title": "Awards",        "file": "awards.json",       "enabled": true },
  { "id": "students",     "title": "Students",      "file": "students.json",     "enabled": true },
  { "id": "teaching",     "title": "Teaching",      "file": "teaching.json",     "enabled": true },
  { "id": "contact",      "title": "Contact",       "file": "profile.json",      "enabled": true }
]
```

> 💡 **In `profile.json`** include: `university`, `department`, `links` for Google Scholar / lab website / institutional profile.

---

### 🎓 PhD / MS Student

![Use](https://img.shields.io/badge/Best_For-Graduate_Students,_Early_Researchers-7a1c1c)

**Enable these 7 sections:**

```json
[
  { "id": "about",        "title": "About",              "file": "profile.json",      "enabled": true },
  { "id": "research",     "title": "Research Interests", "file": "research.json",     "enabled": true },
  { "id": "publications", "title": "Publications",       "file": "publications.json", "enabled": true },
  { "id": "projects",     "title": "Projects",           "file": "projects.json",     "enabled": true },
  { "id": "skills",       "title": "Skills",             "file": "skills.json",       "enabled": true },
  { "id": "awards",       "title": "Awards",             "file": "awards.json",       "enabled": true },
  { "id": "contact",      "title": "Contact",            "file": "profile.json",      "enabled": true }
]
```

> 💡 **In `profile.json`** mention: your advisor, thesis topic, expected graduation year in your bio. Include your GitHub link.

---

### 📚 Teacher

![Use](https://img.shields.io/badge/Best_For-K--12_/_College_Instructors-9b2c2c)

**Enable these 6 sections:**

```json
[
  { "id": "about",     "title": "About",              "file": "profile.json",   "enabled": true },
  { "id": "research",  "title": "Subjects & Methods", "file": "research.json",  "enabled": true },
  { "id": "teaching",  "title": "Courses",            "file": "teaching.json",  "enabled": true },
  { "id": "awards",    "title": "Recognition",        "file": "awards.json",    "enabled": true },
  { "id": "volunteer", "title": "Community",          "file": "volunteer.json", "enabled": true },
  { "id": "contact",   "title": "Contact",            "file": "profile.json",   "enabled": true }
]
```

---

### 💻 Engineer

![Use](https://img.shields.io/badge/Best_For-Software,_Hardware,_Any_Level-2563eb)

**Enable these 7 sections:**

```json
[
  { "id": "about",          "title": "About",          "file": "profile.json",        "enabled": true },
  { "id": "skills",         "title": "Skills",         "file": "skills.json",         "enabled": true },
  { "id": "experience",     "title": "Experience",     "file": "experience.json",     "enabled": true },
  { "id": "projects",       "title": "Projects",       "file": "projects.json",       "enabled": true },
  { "id": "certifications", "title": "Certifications", "file": "certifications.json", "enabled": true },
  { "id": "awards",         "title": "Achievements",   "file": "awards.json",         "enabled": true },
  { "id": "contact",        "title": "Contact",        "file": "profile.json",        "enabled": true }
]
```

> 💡 **In `profile.json`** include `links` for GitHub, LinkedIn, personal portfolio.

---

### 💼 Manager / Executive

![Use](https://img.shields.io/badge/Best_For-Directors,_VPs,_Executives-1e40af)

**Enable these 6 sections:**

```json
[
  { "id": "about",      "title": "About",       "file": "profile.json",    "enabled": true },
  { "id": "experience", "title": "Career",      "file": "experience.json", "enabled": true },
  { "id": "projects",   "title": "Initiatives", "file": "projects.json",   "enabled": true },
  { "id": "speaking",   "title": "Speaking",    "file": "speaking.json",   "enabled": true },
  { "id": "awards",     "title": "Recognition", "file": "awards.json",     "enabled": true },
  { "id": "contact",    "title": "Contact",     "file": "profile.json",    "enabled": true }
]
```

> 💡 **In bio**, lead with scope: teams led, P&L responsibility, transformation outcomes.

---

### 🤝 Consultant / Freelancer

![Use](https://img.shields.io/badge/Best_For-Independent_Professionals-0e7490)

**Enable these 7 sections:**

```json
[
  { "id": "about",      "title": "About",        "file": "profile.json",    "enabled": true },
  { "id": "research",   "title": "Services",     "file": "research.json",   "enabled": true },
  { "id": "skills",     "title": "Expertise",    "file": "skills.json",     "enabled": true },
  { "id": "experience", "title": "Background",   "file": "experience.json", "enabled": true },
  { "id": "projects",   "title": "Case Studies", "file": "projects.json",   "enabled": true },
  { "id": "speaking",   "title": "Speaking",     "file": "speaking.json",   "enabled": true },
  { "id": "contact",    "title": "Work With Me", "file": "profile.json",    "enabled": true }
]
```

---

### 🚀 Founder / Entrepreneur

![Use](https://img.shields.io/badge/Best_For-Startup_CEOs,_Builders-c2410c)

**Enable these 6 sections:**

```json
[
  { "id": "about",      "title": "About",        "file": "profile.json",    "enabled": true },
  { "id": "experience", "title": "Ventures",     "file": "experience.json", "enabled": true },
  { "id": "projects",   "title": "Building",     "file": "projects.json",   "enabled": true },
  { "id": "news",       "title": "Press",        "file": "news.json",       "enabled": true },
  { "id": "speaking",   "title": "Talks",        "file": "speaking.json",   "enabled": true },
  { "id": "contact",    "title": "Get In Touch", "file": "profile.json",    "enabled": true }
]
```

---

### 🔬 Researcher (Non-Academic)

![Use](https://img.shields.io/badge/Best_For-Industry_/_Nonprofit_Research-15803d)

**Enable these 7 sections:**

```json
[
  { "id": "about",        "title": "About",        "file": "profile.json",      "enabled": true },
  { "id": "research",     "title": "Research",     "file": "research.json",     "enabled": true },
  { "id": "publications", "title": "Publications", "file": "publications.json", "enabled": true },
  { "id": "projects",     "title": "Projects",     "file": "projects.json",     "enabled": true },
  { "id": "speaking",     "title": "Talks",        "file": "speaking.json",     "enabled": true },
  { "id": "awards",       "title": "Recognition",  "file": "awards.json",       "enabled": true },
  { "id": "contact",      "title": "Contact",      "file": "profile.json",      "enabled": true }
]
```

---

### 🌍 Nonprofit / Organisation

![Use](https://img.shields.io/badge/Best_For-Foundations,_NGOs,_Labs-166534)

**Enable these 7 sections:**

```json
[
  { "id": "about",     "title": "About",       "file": "profile.json",   "enabled": true },
  { "id": "research",  "title": "Focus Areas", "file": "research.json",  "enabled": true },
  { "id": "news",      "title": "Updates",     "file": "news.json",      "enabled": true },
  { "id": "students",  "title": "Team",        "file": "students.json",  "enabled": true },
  { "id": "teaching",  "title": "Programmes",  "file": "teaching.json",  "enabled": true },
  { "id": "awards",    "title": "Recognition", "file": "awards.json",    "enabled": true },
  { "id": "contact",   "title": "Contact",     "file": "profile.json",   "enabled": true }
]
```

---

## 🎨 Customisation

### Change the colour scheme
Open `index.html`, find the `:root` block near the top, change three lines:

```css
--primary:       #500000;   /* your brand colour */
--primary-light: #7a1c1c;   /* lighter shade (hover) */
--primary-pale:  #f9f1f1;   /* very light tint (backgrounds) */
```

**Recommended palettes:**

| Brand | Primary | Light | Pale |
|---|---|---|---|
| ![Maroon](https://img.shields.io/badge/-Maroon_(default)-500000?style=flat-square) | `#500000` | `#7a1c1c` | `#f9f1f1` |
| ![Navy](https://img.shields.io/badge/-Navy-1e40af?style=flat-square) | `#1e40af` | `#3b82f6` | `#eff6ff` |
| ![Forest](https://img.shields.io/badge/-Forest-15803d?style=flat-square) | `#15803d` | `#22c55e` | `#f0fdf4` |
| ![Orange](https://img.shields.io/badge/-Burnt_Orange-c2410c?style=flat-square) | `#c2410c` | `#ea580c` | `#fff7ed` |
| ![Teal](https://img.shields.io/badge/-Teal-0e7490?style=flat-square) | `#0e7490` | `#0891b2` | `#ecfeff` |
| ![Slate](https://img.shields.io/badge/-Slate-334155?style=flat-square) | `#334155` | `#475569` | `#f1f5f9` |
| ![Purple](https://img.shields.io/badge/-Purple-6b21a8?style=flat-square) | `#6b21a8` | `#9333ea` | `#faf5ff` |

### Subdirectory deployment
If your repo isn't named `username.github.io`, open `index.html` and find:
```js
const BASE = "";
```
Change it to your repo name:
```js
const BASE = "/your-repo-name";
```

### Hide / reorder sections
Edit `data/sections.json`. Set `"enabled": false` to hide. Drag items in the array to reorder.

---

## 📁 File Structure

```
your-repo/
├── index.html                     ← Site shell (edit only for colour/branding)
├── README.md
├── data/                          ← ALL your content lives here
│   ├── sections.json              ← Which sections to show + their order
│   ├── profile.json               ← Identity, bio, contact, form key
│   ├── research.json              ← Research / focus / expertise / services
│   ├── publications.json          ← Papers, articles, reports
│   ├── news.json                  ← News, updates, press
│   ├── awards.json                ← Awards, honours, recognition
│   ├── students.json              ← Students / team / collaborators
│   ├── teaching.json              ← Courses / programmes / workshops
│   ├── experience.json            ← Work history (corporate, engineer, mgr)
│   ├── projects.json              ← Projects, portfolio, case studies
│   ├── skills.json                ← Skills (grouped or flat list)
│   ├── speaking.json              ← Talks, podcasts, panels
│   ├── certifications.json        ← Certifications, licenses
│   └── volunteer.json             ← Volunteering, community service
└── assets/
    └── img/
        └── profile.jpg            ← Your photo (or omit for initials)
```

**You only ever edit files in `data/`.** Never need to touch `index.html` for content changes.

---

## 🧩 Section Reference

What each section file contains, with the supported data fields:

<details>
<summary><strong>profile.json</strong> — identity, contact, links, form key</summary>

```json
{
  "name": "Your Name", "title": "Your Title", "department": "Optional",
  "affiliation": "Optional", "university": "Optional", "eyebrow": "Optional line above name",
  "photo": "assets/img/profile.jpg",
  "email": "you@example.com", "phone": "+1 000 0000", "location": "City, Country",
  "website": "https://...", "address": "Multi\nline\naddress",
  "links": [{ "label": "GitHub", "url": "...", "icon": "link", "primary": true }],
  "bio": ["Paragraph 1", "Paragraph 2"],
  "education": [{ "degree": "Ph.D.", "field": "...", "institution": "...", "location": "...", "year": "2020" }],
  "contact_intro": "Opening for contact section",
  "collaboration_areas": ["Bullet 1", "Bullet 2"],
  "form_access_key": "your-web3forms-key"
}
```
Available `links[].icon` values: `email`, `phone`, `office`, `scholar`, `lab`, `link`, `profile`, `globe`
</details>

<details>
<summary><strong>experience.json</strong> — work history with timeline</summary>

```json
[{
  "role": "Senior Engineer", "company": "Acme Corp",
  "company_url": "https://acme.com", "location": "San Francisco",
  "start": "2020", "end": "Present",
  "description": "Short summary of the role",
  "highlights": ["Bullet 1", "Bullet 2", "Bullet 3"]
}]
```
</details>

<details>
<summary><strong>projects.json</strong> — portfolio cards</summary>

```json
[{
  "title": "Project Name", "year": "2024", "role": "Lead Developer",
  "description": "What you built and why it mattered",
  "tags": ["Python", "ML", "AWS"],
  "link": "https://...", "link_label": "View →"
}]
```
</details>

<details>
<summary><strong>skills.json</strong> — grouped OR flat</summary>

```json
[
  { "category": "Languages", "items": ["Python", "Go", "Rust"] },
  { "category": "Cloud",     "items": ["AWS", "GCP", "Kubernetes"] }
]
```
Or flat: `["Python", "Go", "Rust", "AWS"]`
</details>

<details>
<summary><strong>speaking.json</strong> — talks, podcasts, panels</summary>

```json
[{
  "title": "Talk title", "venue": "Conference name",
  "location": "City, Country", "date": "March 2025",
  "type": "Keynote", "link": "https://..."
}]
```
</details>

<details>
<summary><strong>certifications.json</strong> — credentials</summary>

```json
[{
  "name": "Cert name", "issuer": "Issuing org",
  "year": "2024", "expires": "2027", "link": "https://..."
}]
```
</details>

<details>
<summary><strong>volunteer.json</strong> — community service</summary>

```json
[{
  "period": "2022 – Present", "role": "Advisor",
  "organization": "Org name", "location": "City",
  "description": "What you did"
}]
```
</details>

<details>
<summary><strong>publications.json</strong> — papers, articles</summary>

```json
[{
  "year": 2024, "title": "Paper title", "authors": "Author list",
  "venue": "Journal or conference", "month": "March 2024", "link": "https://..."
}]
```
</details>

<details>
<summary><strong>news.json</strong> — updates, press</summary>

```json
[{ "date": "May 2025", "title": "Headline", "description": "Body", "link": "https://..." }]
```
</details>

<details>
<summary><strong>awards.json</strong> — recognition</summary>

```json
[{ "year": 2024, "title": "Award name", "org": "Issuing organisation" }]
```
</details>

<details>
<summary><strong>students.json</strong> — team, collaborators, alumni</summary>

```json
{
  "collaborators": [{ "name": "Org Name", "role": "Partner type" }],
  "current":       [{ "name": "Person Name", "degree": "Role", "photo": "" }],
  "alumni":        [{ "name": "Person", "degree": "Role", "current_position": "Where now" }]
}
```
</details>

<details>
<summary><strong>teaching.json</strong> — courses, programmes</summary>

```json
[{ "name": "Course or programme name", "level": "Undergraduate / Graduate / Workshop" }]
```
</details>

---

## 🧪 Testing Locally

You can't open `index.html` by double-clicking — browsers block local fetch for security.

```bash
cd your-project-folder
python3 -m http.server 8000
# Open: http://localhost:8000
```

---

## ❓ FAQ

**Q: Do I need to edit `index.html`?**
A: Only if you want to change the colour scheme. All content goes in `data/`.

**Q: Can I add a new section type the template doesn't have?**
A: Yes. Add a new entry to `sections.json`, create the JSON data file, then add a render function + case in `index.html`. The template prints a JSON fallback if no renderer exists.

**Q: Does this work without a contact form?**
A: Yes. Leave `form_access_key` empty in `profile.json` and the contact section shows a clean "Send Email" button instead.

**Q: What if I don't have a photo to upload?**
A: Leave `"photo": ""` in `profile.json`. The site shows your initials in a styled circle automatically.

**Q: Do I need a paid plan anywhere?**
A: No. GitHub Pages is free, Web3Forms free tier covers 250 submissions/month. Total cost: $0.

**Q: How do I add a custom domain?**
A: Repo Settings → Pages → Custom Domain → enter your domain → enable HTTPS. Add an A/CNAME DNS record at your registrar.

**Q: Can I add or remove sections?**
A: Yes. Edit `data/sections.json` — `enabled: false` hides, reordering the array reorders the nav. To add a brand new section type not listed here, you'd add a renderer in `index.html`.

---

## 📄 License

MIT — free to use, fork, modify, and distribute. Attribution appreciated but not required.

---

<p align="center">
  Made with care by the <a href="https://himalayanfoundation.org">Himalayan Foundation</a><br>
  Open-source templates for the research community.
</p>
