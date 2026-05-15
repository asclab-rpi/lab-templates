# Welcome to the ASCLab

For your onboarding, the following is suggested: 
1. Join the lab Discord server: https://discord.gg/ZbUrbz569
2. Connect with Prof. Singh and other lab members on LinkedIn and ResearchGate. 

# ASCLab Lab Templates

All graduate and undergraduate students preparing slides for talks, seminars or technical reports covering research performed at the
[Advanced Space Concepts Laboratory (ASCLab)](https://www.asclabrpi.com) at Rensselaer Polytechnic Institute should use the templates from this repo.

---

## Contents

| File | Description |
|------|-------------|
| `asclab_report_template.tex` | LaTeX template for technical and research reports |
| `asclab_presentation_template.pptx` | PowerPoint template for research presentations |

---

## LaTeX Report Template

### Requirements

The easiest option is [Overleaf](https://www.overleaf.com) — upload the `.tex` file and compile in the browser with no local installation needed. RPI has an institutional Overleaf license; log in with your RPI email for full access. For local compilation, use [TeX Live](https://tug.org/texlive/) (Linux/macOS) or [MiKTeX](https://miktex.org/) (Windows).

### Usage

1. Edit the metadata block near the top of the file:
   ```latex
   \newcommand{\ReportTitle}{Your Title Here}
   \newcommand{\AuthorList}{First Author, Sandeep K. Singh}
   \newcommand{\ReportNumber}{ASCLab-TR-2026-XX}
   ```
2. Compile twice for correct cross-references:
   ```bash
   pdflatex asclab_report_template.tex
   pdflatex asclab_report_template.tex
   ```

---

## PowerPoint Template

Open `asclab_presentation_template.pptx` in PowerPoint and edit placeholder text directly. Replace grey figure boxes with your own plots or diagrams.

Includes 8 slides: Title, Outline, Motivation, Background, Methodology, Results, Conclusion, and Thank You.

---

## Contact

**Prof. Sandeep K. Singh** · sandes5@rpi.edu · [asclabrpi.com](https://www.asclabrpi.com)
