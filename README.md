# LaTeX Resume Template

A resume template written in LaTeX. It includes common sections for software engineering resumes and uses a clean, readable layout.

## What's Inside

- Simple single-column layout
- Pre-structured sections for experience, projects, education, and skills
- Bullet point placeholders using the XYZ format to help describe achievements
- Fonts, spacing, and sections are labeled so they are easy to adjust

## Getting Started

**Option A: Overleaf**
Paste the contents of `resume.tex` into a new Overleaf project and start editing. No local setup needed.

**Option B: Local**

1. Install a LaTeX distribution: [TeX Live](https://www.tug.org/texlive/) or [MiKTeX](https://miktex.org/)
2. Clone the repo:
    ```bash
    git clone https://github.com/yourusername/resume-template.git
    cd resume-template
    ```
3. Open `resume.tex` in your editor and fill in your details
4. Compile to PDF:
    ```bash
    pdflatex resume.tex
    ```
5. Open `resume.pdf` and review the output before sending

## Tips

- Use the **XYZ format** for bullet points: *Accomplished [X] as measured by [Y], by doing [Z]*. Specific, quantified bullets are more useful than general ones.
- Keep it to one page.
- Update the skills section to match the job posting, since ATS tools compare your resume against the job description by keyword.
