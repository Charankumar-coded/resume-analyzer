# ResumeIQ — AI Resume Analyzer

A polished single-page resume review tool with modern UI/UX, ATS scoring, skill-gap detection, job match suggestions, and export-ready reports.

## Features
- Responsive dark-themed dashboard with clean pro-style layout
- Resume editor and job description editor with live word counts
- AI-powered ATS score, grade, match percent, and category breakdown
- Skill analysis showing matched, missing, and partial keywords
- Job match suggestions and actionable insight recommendations
- Local draft saving in browser storage for fast reuse
- Copy summary and download JSON report for sharing or recordkeeping

## How to use
1. Open `resume-analyzer.html` in a browser.
2. Paste your resume text into the Resume editor.
3. Paste the target Job Description into the Job editor.
4. Enter your Claude API key in the AI Settings field.
5. Click `Analyze with AI`.
6. Explore the `Overview`, `Skills`, `Matches`, `Insights`, and `Export` tabs.

## Notes
- The page UI works offline, but the AI analysis requires a valid Claude API key and network access.
- Your resume, job description, and API key are stored locally in the browser for convenience.
- Use the `Start fresh` button to clear your current session and begin again.
