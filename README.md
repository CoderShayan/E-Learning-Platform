## E-Learning-Platform


⚠️ **Under Construction**(From 05 Nov 2025 to till now) — This project is a work in progress. Some pages, lessons, and features may be incomplete or subject to change. Expect breaking updates. Contributions and issue reports are welcome.

It is a lightweight, static, and open-source e-learning platform that provides high-quality, structured courses completely free — no login or subscription required.

## Key Ideas
- 100% free access to all courses
- Day-wise, structured lessons (Day 01 → Day 02 → Day 03 → …)
- Client-side progress tracking using LocalStorage
- Minimal, mobile-first UI for fast load and good SEO
- Static banners for monetization (limited and non-intrusive)

For full project objectives and scope, see the project brief: [About Project](About Project).

## Project Status
- Core static pages: mostly implemented
- Progress tracking (LocalStorage): implemented
- Responsive UI: ongoing improvements
- Quizzes, certificates, admin panel: planned / not yet implemented

## Included Files
- [About Project](About Project) — project description and objectives  
- [LICENSE](LICENSE) — project license (MIT)

## Technology
- Front-End: HTML, CSS, JavaScript
- Hosting: Static site hosting (e.g., Hostinger)

## Getting Started (Local)
1. Clone the repo:
   ```sh
   git clone <repo-url>
   cd E-Learning-Platform
   ```
2. Serve the site locally:
   ```sh
   # Python 3
   python3 -m http.server 8000
   ```
   Then open http://localhost:8000 in your browser.

## Contributing
- Open issues for feature requests or bugs.
- Add new course folders with day-wise lesson HTML files.
- Keep UI minimal and mobile-responsive.
- Document major changes in pull requests.

## Roadmap / To Do
- Add quizzes, leaderboards, and certificates
- Admin panel for content management
- Improve SEO and accessibility
- Add CI to validate links and build previews

## License
This project is released under the MIT License. See [`LICENSE`](LICENSE) for details.
