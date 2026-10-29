# 📔 Project Diary: Developer Portfolio

## 🚀 SPRINT OVERVIEW
- **Duration:** 2 Days (Target: Complete & Deployed)
- **Tech Stack:** Semantic HTML5, Vanilla CSS3 (Dark Theme), GitHub Pages

---

### 🎫 TICKET-01: Technical Planning & Content Strategy
- **Status:** ⬜ DONE
- **Story:** As a developer, I want to map out my copy and links before writing code so that my development workflow is seamless and error-free.
- **Tasks:**
  - [x] Draft final text for the Hero Section introduction.
  >>> <p>Hello, i'm Refilwe,</p>
    <h1>A software developer based somewhere and i Design and build stuff.</h1>font = google sans code [
        <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Google+Sans+Code:ital,wght,MONO@0,300..800,1;1,300..800,1&family=Inter:ital,opsz,wght@0,14..32,100..900;1,14..32,100..900&family=Outfit:wght@100..900&display=swap" rel="stylesheet">
    ]
    <strong>Great Digital stuff!</strong>
    <btn>I want a website</btn>
     <btn>I want a Software Developer</btn> montserrat/tahoma

  - [x] Write impact-driven copy for the @mickiesThe KOTAPLACE project description.
  >>> @mickiesThe KOTAPLACE — E-Commerce MVC Infrastructure
An implementation of a dynamic restaurant ordering environment moving away from flat-file storage to automated data layers.
• Architecture: Structured an enterprise-standard Model-View-Controller framework to decouple data handling, route definitions, and interface delivery.
• Data Engineering: Replaced legacy, local JSON filesystem parsing (fs.readFile) with efficient MongoDB indexing and schema constraints to pull real-time database inputs.
• Traffic Control: Built custom Express middleware and endpoint routers to handle asynchronous data streaming securely.

  - [x] Gather URLs for GitHub profile, LinkedIn, and email contact links.
  >>> github >> github.com/fenfe
  >>> LinkedIn >> www.linkedin.com/in/dikutle-refilwe
  >>> email >> mmadikutle@gmail.com

  - [x] Select font family (e.g., system-ui or Google Fonts Inter) and neon accent color code.
  >>> fonts >> google sans code & outfit


---

### 🎫 TICKET-02: HTML Structure & Semantic Layout
- **Status:** ⬜ TO DO
- **Story:** As a user, I want a well-structured page layout so that I can easily read through the developer's experience and projects on any device.
- **Tasks:**
  - [x] Create `index.html` in the root folder.
  - [x] Build layout using HTML5 semantic elements (`<header>`, `<main>`, `<section>`, `<footer>`).
  - [ ] Add project containers with dedicated class names (`project-card`, `project-title`, `tags`, `links`).
  - [ ] Ensure all anchor tags (`<a>`) point to correct placeholders and use `target="_blank"` for external profiles.

---

### 🎫 TICKET-03: Dark Theme Styling & UI Polish
- **Status:** ⬜ TO DO
- **Story:** As a recruiter, I want a modern, high-contrast user interface so that navigating the developer's profile is visually pleasing and clean.
- **Tasks:**
  - [ ] Add internal `<style>` block or link an external `style.css` stylesheet.
  - [ ] Apply pitch-black body background and soft-white typography tokens.
  - [ ] Style project cards with custom subtle borders (`#262626`) and explicit hover interactions.
  - [ ] Implement color accents for clickable call-to-actions (Live Demo / GitHub Repo).

---

### 🎫 TICKET-04: Responsive Design Verification (Mobile Optimization)
- **Status:** ⬜ TO DO
- **Story:** As a hiring manager checking profiles on my smartphone, I want a fluid mobile layout so that text remains legible and links are easy to tap.
- **Tasks:**
  - [ ] Set global viewport meta tag in the HTML head.
  - [ ] Set max-widths and responsive horizontal padding rules on the core layout wrapper.
  - [ ] Use Chrome DevTools Device Emulator to verify layouts on small viewports (Mobile S/M/L).
  - [ ] Eliminate text overflows and fix unintended sideways scrolling.

---

### 🎫 TICKET-05: Git Versioning & Remote Production Deployment
- **Status:** ⬜ TO DO
- **Story:** As a user, I want the portfolio to be accessible via a public URL so that I can share it with employers globally.
- **Tasks:**
  - [ ] Initialize local repository (`git init`) and commit project files with atomic commit descriptions.
  - [ ] Create a public repository on GitHub and link the local codebase (`git remote add`).
  - [ ] Push local main branch to GitHub tracking origin (`git push -u origin main`).
  - [ ] Configure GitHub Pages via the repository settings to serve the build from the root directory.
  - [ ] Verify live domain access and confirm project outbound links execute flawlessly.
