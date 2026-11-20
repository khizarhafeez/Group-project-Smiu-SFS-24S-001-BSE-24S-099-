# SMIU Events Portal

A modern, mobile-friendly front-end website for the **Sindh Madressatul Islam University (SMIU) Student Affairs Office**. Students can discover university events, explore societies, register for events and contact the office.

Built with plain **HTML5, CSS3 and vanilla JavaScript** (no frameworks, no build step).

---

## Group Members

| # | Name | Roll No. | GitHub Username |
|---|------|----------|-----------------|
| 1 | Muhammad Khizar | SFS-24S-001 | [khizarhafeez](https://github.com/khizarhafeez) |
| 2 | Muhammad Wasif | BSE-24S-099 | [MuhammadWasif1234](https://github.com/MuhammadWasif1234) |

---

## Who Built What

| Member | Files built | Pages / parts |
|--------|-------------|---------------|
| **Muhammad Khizar** | `index.html`, `css/style.css`, `events.html` | Home page, Events page, shared styling |
| **Muhammad Wasif** | `contact.html`, `js/main.js`, `js/events-data.js` | Contact page, site-wide JavaScript, event and society data |

---

## Screenshots of the Home Page

### Desktop

<img width="2732" height="4954" alt="home-desktop" src="https://github.com/user-attachments/assets/08ddf0d2-3666-415d-b298-dd2c11e14d04" />


### Phone

<img src="screenshots/home-mobile.png" alt="Home page on phone" width="320">

---

## Pages

| Page | File | What it does |
|------|------|--------------|
| Home | `index.html` | Hero banner, quick stats, upcoming events preview, society directory, call-to-action |
| Events | `events.html` | Full event list with live search, category filters and a registration form (modal) |
| Contact | `contact.html` | Office details, FAQ and a validated contact form |

## Features

- Responsive layout for desktop, tablet and phone, with a hamburger menu on small screens
- Event search and category filters
- Registration form with validation (registrations are saved in the browser's `localStorage`, front-end demo only)
- Contact form with validation and a success message
- Accessible markup: labels, ARIA attributes and keyboard support (Esc closes the modal)

## Project Structure

```
smiu-events-portal/
├── index.html
├── events.html
├── contact.html
├── css/
│   └── style.css
├── js/
│   ├── events-data.js
│   └── main.js
├── screenshots/
│   ├── home-desktop.png
│   └── home-mobile.png
└── README.md
```

---

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/khizarhafeez/smiu-events-portal.git
   cd smiu-events-portal
   ```
   (Or download the project as a ZIP and extract it.)
2. Open `index.html` in any modern browser (Chrome, Edge, Firefox). No server or installation is needed.
3. Optional: run a local server, for example `python -m http.server 8000`, then visit `http://localhost:8000`.

To see the mobile layout, open the browser developer tools (F12) and switch on the device toolbar.

---

## Git Commit History

Each page was developed in **5 commits**, using the format `type(page): message`.

### Home Page (`index.html`)

| # | Commit message |
|---|----------------|
| 1 | `feat(home): add base HTML structure and meta tags` |
| 2 | `feat(home): add responsive navbar and footer` |
| 3 | `feat(home): add hero section and statistics cards` |
| 4 | `feat(home): add upcoming events preview and societies grid` |
| 5 | `style(home): polish layout, spacing and mobile responsiveness` |

### Events Page (`events.html`)

| # | Commit message |
|---|----------------|
| 1 | `feat(events): create events page layout with page hero` |
| 2 | `feat(events): render event cards from data file` |
| 3 | `feat(events): add live search and category filter chips` |
| 4 | `feat(events): add registration modal with form validation` |
| 5 | `fix(events): support deep links, Esc to close and mobile polish` |

### Contact Page (`contact.html`)

| # | Commit message |
|---|----------------|
| 1 | `feat(contact): create contact page layout and hero` |
| 2 | `feat(contact): add office information panel` |
| 3 | `feat(contact): add contact form with subject dropdown` |
| 4 | `feat(contact): add JavaScript form validation and success message` |
| 5 | `feat(contact): add FAQ accordion and responsive styling` |

---

## Teamwork Challenge

The biggest problem we faced as a team was working with Pull Requests and merging our code together. Since we built different pages at the same time, our changes met in shared files such as the navigation bar, `style.css` and `main.js`, and this caused conflicts when we tried to merge. At first we were unsure how to review each other's Pull Requests and which version of the code to keep. We solved it by agreeing on who owns which files, pulling the latest changes from the main branch before starting new work, keeping each Pull Request small and focused on one page, and resolving conflicts together by comparing both versions and keeping the correct parts. After this, our merges became much smoother and we learned how important communication and regular pulling are in team projects.

---

## Credits

Developed by the SMIU web development team for the Student Affairs Office.
