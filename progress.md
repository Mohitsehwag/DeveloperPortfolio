# Project Progress: DeveloperPortfolio

Semester 1 Capstone (100 marks) | Mohit Sehwag, KRMU

Tick each box when the item is done **and committed**. Commit after each question, not all at the end.

---

## Setup
- [ ] Create public repo named exactly `DeveloperPortfolio` on GitHub
- [ ] Clone it locally
- [ ] Create folders: `Linux/`, `ShellScripts/`, `API/`, `Portfolio/`, `Screenshots/`
- [ ] Add `.gitignore` (`__pycache__/`, `*.pyc`, `.env`, `.DS_Store`)
- [ ] Add root `README.md` (links to GitHub and LinkedIn)

## Question 1: Linux Commands & System Documentation (25 marks)
- [ ] `Linux/system_profile.md` with specs table (CPU, RAM, storage, OS and kernel)
- [ ] Binary section: 75 to binary (every division step)
- [ ] Binary section: 110101 to decimal (positional weights)
- [ ] One-sentence reason computers use binary
- [ ] `Linux/commands_output.txt` (`ls -la ~`, `ps aux | head -10`, `df -h`, `free -h`)
- [ ] Commit: `docs: add system profile and Linux command outputs`

## Question 2: Shell Scripting & Automation (25 marks)
- [ ] `ShellScripts/sysinfo.sh` (shebang, author comment, header, CPU, memory, top 3 processes, footer)
- [ ] `chmod +x` and run without errors
- [ ] Save output to `ShellScripts/sysinfo_output.txt`
- [ ] `ShellScripts/backup.sh` (argument check, folder check, timestamped `.tar.gz`, size shown, log line)
- [ ] `chmod +x` and test: `./ShellScripts/backup.sh ~/DeveloperPortfolio`
- [ ] Screenshot: `Screenshots/backup_demo.png`
- [ ] Commit scripts and output file

## Question 3: GitHub Repository & API Interaction (25 marks)
- [ ] Install `curl` and `jq`
- [ ] B1: `API/github_profile.json`
- [ ] B2: run the `jq` filter for name, repos, followers, joined
- [ ] B3: `API/sample_posts.json` and `jq length`
- [ ] B4: `API/api_summary.md` (REST API, status codes 200 and 404, jq filter explained)
- [ ] Commit: `data: add GitHub and JSONPlaceholder API responses and summary`
- [ ] At least 8 commits with Conventional Commit messages (`git log --oneline`)

## Question 4: Developer Portfolio & Career Roadmap (25 marks)
- [ ] A: `Portfolio/resume.pdf` (one page)
- [ ] B: `Portfolio/learning_roadmap.md`
- [ ] C: GitHub profile complete (photo, bio with university and 2+ skills, profile README, pinned repo)
- [ ] C: LinkedIn complete (photo, headline, education, project listed)
- [ ] C: Screenshots `Screenshots/github_profile.png` and `Screenshots/linkedin_profile.png`
- [ ] D: `index.html` at repo root
- [ ] D: Enable GitHub Pages (Settings, Pages, `main`, `/ (root)`)
- [ ] D: Open `https://mohitsehwag.github.io/DeveloperPortfolio` and check it loads

## Final Checks Before Evaluation
- [ ] All scripts executable and run without errors
- [ ] Screenshots referenced in `README.md`
- [ ] Repo is public and folders are visible on GitHub
- [ ] `git log --oneline` shows 8+ commits
- [ ] Terminal windows and browser tabs open for faculty
