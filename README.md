# Personal Professional Portfolio — Divya Sri Karrolla

**Future Interns — Full Stack Web Development Internship — Task 1**
CIN ID: FIT/JUN26/FS18741

A single-page personal portfolio site showcasing my skills, projects, patent, and publication as an Electronics & Computer Engineering student, full-stack developer, and embedded systems enthusiast.

## 🔗 Live Site

https://divyareddy2701.github.io/FUTURE_FS_01/
## Features

- Interactive resume-style sections: About, Skills, Projects, Patent & Publication, Contact
- Real project write-ups: SpendWise, the gesture-based ISL communication device (patent-filed), Dhriti, Hybrid Cloud VPN, and SafeStep
- Contact form (via [formsubmit.co](https://formsubmit.co), no backend required to start)
- Fully responsive layout (mobile / tablet / desktop)
- Semantic HTML, keyboard-focus states, and `prefers-reduced-motion` support for accessibility
- SEO-friendly meta description and heading structure

## Tech Stack

| Layer | Technology |
|---|---|
| Frontend | HTML5, CSS3 (custom properties), vanilla JavaScript |
| Fonts | IBM Plex Mono, Manrope (Google Fonts) |
| Contact form | FormSubmit (no backend needed) |
| Optional backend | Node.js + Express (see "Adding a real backend" below) |

## Folder Structure

```
FUTURE_FS_01/
├── index.html          # Full site — markup, styles, and script in one file
├── assets/
│   └── Divyasri_Karrolla_Resume.pdf   # Add your resume PDF here
├── README.md
├── LICENSE
└── .gitignore
```

## Running Locally

No build step required.

```bash
git clone https://github.com/divyareddy2701/FUTURE_FS_01.git
cd FUTURE_FS_01
# then just open index.html in a browser, or serve it:
python3 -m http.server 5500
```

Visit `http://localhost:5500`.

## Before You Deploy — Checklist

- [x] Contact form is configured with my email: karrolladivyasri@gmail.com
- [x] LinkedIn and GitHub links are updated with my usernames
- [x] Resume PDF added to `assets/Divyasri_Karrolla_Resume.pdf`
- [x] Contact form activated using FormSubmit
- [ ] Update the live site link in this README once deployed

## Deployment (GitHub Pages)

1. Push this repo to GitHub as `FUTURE_FS_01`
2. Go to **Settings → Pages**
3. Under "Build and deployment", set Source to `Deploy from a branch`, branch `main`, folder `/ (root)`
4. Your site will be live at:

https://divyareddy2701.github.io/FUTURE_FS_01/
## Adding a Real Backend (Optional Extension)

The task allows an optional Node.js backend for the contact form or a simple blog. A natural next step:

- `POST /api/contact` — Express route that validates input and sends an email via Nodemailer, storing a copy in MySQL/MongoDB
- `GET /api/projects` — serve project data from a database instead of hardcoding it in HTML, enabling a simple admin panel to add new projects later

This isn't required for the current deliverable but is a good talking point in interviews about scaling a static site into a full-stack one.

## Author

**Divya Sri Karrolla**
Pre-final year B.Tech, Electronics & Computer Engineering
Anurag University, Hyderabad

## License

MIT — see [LICENSE](LICENSE).
