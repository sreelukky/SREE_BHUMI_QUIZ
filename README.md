# SREE_BHUMI QUIZ

A single-file, offline-friendly quiz application for creating and running MCQ-style quizzes.  
This repo packages **Bhumi_Quiz.html** and all the usual GitHub support files so you can publish and maintain it easily (including GitHub Pages deployment).

## Quick Start
1. **Open locally:** just double-click `Bhumi_Quiz.html`.
2. **Serve (optional):**
   ```bash
   python -m http.server 8080
   # then open http://localhost:8080/Bhumi_Quiz.html
   ```
3. **Deploy on GitHub Pages:**
   - Push this repository to GitHub.
   - Go to **Settings → Pages** and set the branch to **main** and the folder to **/** (root).
   - Or keep the included workflow (see `.github/workflows/pages.yml`) which auto-publishes Pages on every push to `main`.

## Features
- Works fully **offline** (single HTML file).
- Imports questions from DOCX using **Mammoth.js** (already bundled in the HTML).
- Uses standard MCQ format (A–D) with the correct option wrapped in `**`.
- No server or build step required.

## Project Structure
```
.
├─ Bhumi_Quiz.html
├─ README.md
├─ LICENSE
├─ .gitignore
├─ CONTRIBUTING.md
├─ CODE_OF_CONDUCT.md
├─ SECURITY.md
├─ CHANGELOG.md
└─ .github/
   ├─ ISSUE_TEMPLATE/
   │  ├─ bug_report.md
   │  └─ feature_request.md
   ├─ PULL_REQUEST_TEMPLATE.md
   ├─ FUNDING.yml
   └─ workflows/
      └─ pages.yml
```

## MCQ Format (required)
Use this exact pattern:
```
1. Question text?
A) Option 1
B) Option 2
*C) Correct Option*
D) Option 4
```
- **Exactly four options (A–D).**
- The correct option must be wrapped with **double asterisks** around the **letter and text**.

## Contributing
Please see [CONTRIBUTING.md](CONTRIBUTING.md). Be kind and follow our [Code of Conduct](CODE_OF_CONDUCT.md).

## Security
If you find a security issue, **do not** open a public issue. Follow the instructions in [SECURITY.md](SECURITY.md).

## License
Released under the MIT License. See [LICENSE](LICENSE) for details.
