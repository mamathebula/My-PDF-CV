# LaTeX CV — Mandla Mathebula

ATS-optimized 2-page CV in LaTeX format.

## Files

| File | Purpose |
|---|---|
| `cv.tex` | LaTeX source — edit this to update your CV |
| `CV-UPDATED.md` | Markdown version of the same CV content |

## How to Compile

### Option 1: Overleaf (Easiest)
1. Go to [overleaf.com](https://www.overleaf.com)
2. Create a new blank project
3. Replace the content with `cv.tex`
4. It compiles automatically — download the PDF

### Option 2: Local (if LaTeX is installed)
```bash
pdflatex cv.tex
```

### Option 3: Install LaTeX locally (macOS)
```bash
brew install --cask mactex
pdflatex cv.tex
```

## Section Order (ATS-Optimized)

1. Professional Summary
2. Technical Skills (keywords scanned early by ATS)
3. Professional Experience
4. Projects (with hyperlinks to GitHub/live sites)
5. Education
6. Certifications
7. Key Achievements

## How to Edit

- Open `cv.tex` in any text editor or Overleaf
- Sections are clearly labeled with `% Comments`
- Project titles are hyperlinked — update URLs if repo names change
- Page break is set before "Branch VIP Support Engineer" to keep it at 2 pages
- If content overflows, adjust margins (`\usepackage[margin=0.6in]{geometry}`) or trim bullets

## Formatting

- 11pt font, A4 paper, 0.6in margins
- Blue section headings with horizontal rules
- Clickable hyperlinks for LinkedIn, GitHub, Portfolio, and all projects
- Compact bullet points with measurable results
