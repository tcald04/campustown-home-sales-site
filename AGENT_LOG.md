# Agent log

Add a dated entry each time you work with your AI coding agent, with the newest entry at the bottom. Each entry records what you asked the agent, what it produced, and what you checked or changed. Paste your key prompts in exactly as you typed them. Include at least one time the agent got something wrong, and how you caught it.

Copy this outline for each entry:

```markdown
## YYYY-MM-DD: What you worked on

- **Asked:** "Paste your prompt here."
- **Agent produced:** What it made or changed.
- **Checked or changed:** How you checked it, and what you fixed.
```

## 2026-11-21: Replaced the placeholder with a median-price page

- **Asked:** "Read AGENTS.md and docs/data_description_sheet.md first. Then replace the placeholder index.html with a page that shows the median sale price for each city, computed from data/college_town_home_sales.csv. Leave out sales under $10,000 and state that rule on the page."
- **Agent produced:** A static HTML page that loads the CSV in the browser, excludes prices below $10,000, computes each city's median and qualifying sales count, and displays the 18 cities in descending median-price order.
- **Checked or changed:** Verified the dataset with Python for all 18 cities and spot-checked that the HTML uses the CSV rather than hard-coded prices. No incorrect result or change was caught during this pass.
