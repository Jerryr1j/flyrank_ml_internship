
We are working on the "Visual Framing & Judgment" portfolio assignment (Week 03). My goal is to build a clean, intentional, and professional portfolio structure for my machine learning work without relying on cluttered or fake AI-generated designs.

Please help me build this step-by-step by giving me:
1. A simple, intentional visual identity setup :recommend a clean sans-serif font style, a professional 3-color palette like dark gray, white, and a subtle accent blue, and layout spacing rules

Planning the visual identity portion of a portfolio structure.
Planning the visual identity portion of a portfolio structure.
Step 1: Visual Identity Setup
The goal is restraint: one typeface, three colors, and a consistent spacing system. Consistency is what makes a portfolio look intentional rather than template-made.

Typography
Primary font: Inter (free on Google Fonts). It's neutral, highly legible on screen, and has a wide range of weights. Good alternatives are IBM Plex Sans (slightly more technical) or Source Sans 3.

Optional code font: JetBrains Mono, used only for code snippets, metrics, or file names.

Fallback stack: Inter, -apple-system, "Segoe UI", Roboto, sans-serif

Type scale (base 16px, ratio about 1.25):

Role	Size	Weight	Line height
Page title	40px	600	1.2
Section heading	28px	600	1.3
Subheading	20px	600	1.4
Body	16-18px	400	1.6
Caption / metadata	14px	400	1.5
Use only two weights (400 and 600). Avoid ALL CAPS beyond tiny labels, and avoid more than three sizes on a single page.

Color Palette
Role	Hex	Use
Dark gray	
#1F2328	Text, headings, footer
White	
#FFFFFF	Page background
Accent blue	
#2563EB	Links, buttons, key highlights only
Two supporting tints of the existing colors are fine, since they aren't new hues:

Secondary text: 
#5B6470 (a lighter dark gray)
Borders and subtle panels: 
#E5E7EB or 
#F6F7F9
Rules for using color:

Blue appears on roughly 5% of the page: links, one primary button, maybe a chart highlight.
Never use blue for large background blocks or decorative gradients.
Dark gray on white gives very strong contrast, and the blue has about 5:1 contrast on white, so both meet WCAG AA for body text.
In charts, use dark gray for baselines and blue for your model or result. This tells the viewer where to look.
Layout and Spacing Rules
8px grid. Every margin and padding is a multiple of 8 (8, 16, 24, 32, 48, 64, 96).
Content width. Keep text at a maximum of about 720px (60-75 characters per line). The overall page container can go up to 1100px.
Section spacing. Use 96px between major sections and 24-32px between a heading and its content.
Generous whitespace. If a page feels slightly too empty, it is probably right.
Left alignment. Left-align body text and avoid centered paragraphs. Center only a short hero title if you want.
One grid. Project cards use a consistent 2-column grid (1 column on mobile), with identical card sizes and the same spacing.
Images and charts. Use consistent aspect ratios, a thin 
#E5E7EB border or none, and a one-line caption beneath each.
No extras. Skip drop shadows, stock-looking AI art, emoji icons, and animated backgrounds. Let your charts, diagrams, and results be the visuals.
Quick CSS Starter
css
:root {
  --ink: #1F2328;
  --paper: #FFFFFF;
  --accent: #2563EB;
  --muted: #5B6470;
  --line: #E5E7EB;
}
body {
  font-family: Inter, -apple-system, "Segoe UI", Roboto, sans-serif;
  color: var(--ink);
  background: var(--paper);
  line-height: 1.6;
}
a { color: var(--accent); }
Quick Self-Check
Can I describe the whole system in one sentence? ("Inter, dark gray on white, blue only for links.")
Is anything on the page there purely for decoration?
Is spacing consistent between every section?
When you're ready, tell me and we'll move to Step 2: the portfolio structure (page map, what each ML project page should contain, and how to frame your results). If you have a preferred tool (plain HTML, GitHub Pages, Notion, Framer), let me know and I'll tailor it.


 FlyRank ML Internship - Capstone Launch & Story

 1. Live Portfolio URL
- Live Site: https://jerryr1j.github.io/flyrank_ml_internship

 2. Honest Build-In-Public Story
- What I Made: Built a clean, structured machine learning and data contract portfolio focusing on "Core first, AI second."
- Where AI Helped: AI helped me structure my Python data validation logic and clean up my prompt iteration steps so I could focus purely on data framing and judgment.
-What Broke & What I Learned: Initially, my data contract notebook failed on grain checks because of missing table slices, which taught me the critical importance of validating row uniqueness before building features.

3. Stack & Next Steps
- Tech Stack: Python, Pandas, scikit-learn, Hugging Face Warehouse datasets, and Markdown for structured portfolio framing.
- Next Named Piece:Week 04/05 Machine Learning Model Training & Evaluation Pipeline.
- Reminder Set:Sunday evening calendar reminder set for ongoing portfolio updates.
- # Portfolio Sustainability Note (Week 10)

## 1. How to Add the Next Case Study
Whenever I build a new feature or model, I will add it using the Week 2 three-beat shape:
- The Problem: What data or technical challenge was tackled.
- What I Did: The concrete steps (data contract, feature engineering, modeling).
- What Came of It:The final honest result or metric.
- Location: Added directly to my `work/case_studies.md` portfolio file.

## 2. Next Piece of Work & Reminder
- Next Named Piece: Week 04/05 Machine Learning Model Training & Evaluation Pipeline.
- Reminder Set:I have set a recurring calendar reminder on my device for every Sunday evening to review, update, and push new portfolio iterations.

## 3. Preservation of Build Context
- I am keeping this Claude Project intact. Because it already contains my project identity and technical stack context, future portfolio updates will be a short, cheap conversation rather than a complete rebuild.
