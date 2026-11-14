# Practice Lab: Data Analytics in Accounting

A static practice website for the oral exam in *Data Analytics in Accounting*.
It has numbered data manipulation exams (Excel and SQL), a filterable question bank,
auto-checked regression interpretation exams, and a readiness dashboard with a
spaced-repetition review queue.

Live site: https://YOUR-USERNAME.github.io/practice-lab/

## Run locally
Open `index.html` in any browser. There is no build step and no dependencies.

## Add questions
Append a row to the `Q` array at the top of the script in `index.html`:
`["Topic","Excel or SQL","Question text","Model answer","Source file"]`

## Added functionality
Self-graded answers feed a per-topic readiness score and a spaced-repetition
review queue (progress is stored in the browser's localStorage).
