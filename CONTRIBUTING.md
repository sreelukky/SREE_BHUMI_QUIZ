# Contributing to SREE_BHUMI QUIZ

Thanks for your interest in contributing!


## Ways to Contribute
- Report bugs via **Issues** (use the *Bug report* template).
- Request features (use the *Feature request* template).
- Improve docs (README, examples).
- Open pull requests for fixes or enhancements.


## Development
This project is a single HTML file. You can iterate by simply opening `Bhumi_Quiz.html` in a browser.

If you need a local server for any reason:
```bash
python -m http.server 8080
```

## Coding Guidelines
- Keep it **simple** and **offline-friendly**.
- Avoid adding heavy dependencies.
- Preserve the expected MCQ format:
  ```
  1. Question text?
  A) Option 1
  B) Option 2
  *C) Correct Option*
  D) Option 4
  ```
  (Correct option wrapped with double asterisks around the letter and text.)

## Pull Requests
1. Fork the repo and create a feature branch.
2. Make changes and update docs as needed.
3. Run a quick smoke test by opening `Bhumi_Quiz.html` locally.
4. Open a PR using the **Pull request template** and describe your changes clearly.

## Releases
We use the `CHANGELOG.md` to track notable changes.
