# MathSpark Buddy

A small, original, interactive mathematics-learning website built with plain HTML, CSS, and JavaScript.

## Features
- Responsive dark-gradient learning interface
- Rule-based maths chat (no LLM API)
- Mini-lessons: algebra, fractions, percentages, geometry, linear equations, indices
- Practice questions with hints and answer feedback
- Basic arithmetic calculator with input validation
- Homework/exam-completion boundary and unclear-input fallback

## Run locally
Open `index.html` in a browser.

## Publish with GitHub Pages
1. Create a GitHub repository named `mathspark-buddy` (or another name you prefer).
2. Upload `index.html` and `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose branch **main** and folder **/(root)**, then click **Save**.
6. Wait a minute or two. GitHub will show the published website URL in the Pages section.

## Important limitations
- This project does not call an LLM API. Replies are based on a small built-in topic library and keyword rules, so it cannot understand every possible question.
- GitHub Pages hosts only the website's static files. It cannot itself run a Telegram Bot webhook or keep a bot process running.
- To connect Telegram, create a bot with Telegram's official BotFather and add a separate backend/automation service that securely stores the Telegram bot token. Never put a Telegram bot token in this public repository or in `index.html`.
- The calculator only supports basic arithmetic expressions. Do not enter untrusted code.

## Suggested future improvements
- Add more curriculum topics and practice questions.
- Add a graphing feature with a graphing library.
- Add bilingual English/Chinese content.
- Add a Telegram backend after the web version is working.
