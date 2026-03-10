# LaTeX Resume

This directory contains the LaTeX source for Luann Luna's resume, with automated PDF building via GitHub Actions.

## Quick Start

### Building Locally

1. **Install LaTeX** (if not already installed):

   **macOS - Full Distribution (Recommended)**:
   ```bash
   brew install --cask mactex
   ```

   **macOS - Minimal Distribution**:
   ```bash
   brew install --cask basictex
   sudo tlmgr update --self
   sudo tlmgr install latexmk enumitem titlesec
   ```

2. **Build the PDF**:
   ```bash
   cd LaTeX
   make pdf
   ```

   The PDF will be generated in two locations:
   - `build/resume.pdf` (build artifact)
   - `../Luann_Luna_Senior_iOS_Resume.pdf` (final output for GitHub Pages)

3. **Clean build artifacts**:
   ```bash
   make clean
   ```

## Project Structure

```
LaTeX/
├── resume.tex          # Main LaTeX source file
├── Makefile           # Build automation
├── README.md          # This file
├── .gitignore         # Excludes auxiliary files
└── build/             # Generated files (git-ignored)
    ├── resume.aux
    ├── resume.log
    ├── resume.out
    └── resume.pdf
```

## Editing the Resume

1. Open `resume.tex` in your favorite text editor
2. Modify the content (contact info, experience, skills, etc.)
3. Build with `make pdf` to see changes
4. Review `build/resume.pdf`

### Key Sections in resume.tex

- **Header**: Name, title, contact information
- **Professional Summary**: Brief career overview
- **Experience**: Work history with accomplishments
- **Education**: Degrees and institutions
- **Technical Skills**: Languages, frameworks, tools
- **Projects**: Personal or open-source projects

## Automated Builds

This repository uses GitHub Actions to automatically build the PDF when changes are pushed to the `main` branch.

**Workflow**: `.github/workflows/build-latex-resume.yml`

When you push changes to `resume.tex`:
1. GitHub Actions compiles the LaTeX source
2. Generates `Luann_Luna_Senior_iOS_Resume.pdf`
3. Commits the PDF back to the repository
4. GitHub Pages serves the updated PDF

## Troubleshooting

### Build fails with "command not found: pdflatex"

Install a LaTeX distribution (see Quick Start above).

### Build succeeds but PDF looks wrong

1. Check `build/resume.log` for warnings:
   ```bash
   make log
   ```

2. Common issues:
   - Missing packages: Install with `tlmgr install <package-name>`
   - Syntax errors: Check LaTeX syntax in resume.tex
   - Encoding issues: Ensure UTF-8 encoding

### GitHub Actions build fails

1. Check the Actions tab on GitHub for error logs
2. Verify `resume.tex` builds locally first
3. Ensure all required packages use standard LaTeX distributions

## LaTeX Resources

- [LaTeX Documentation](https://www.latex-project.org/help/documentation/)
- [Overleaf Tutorials](https://www.overleaf.com/learn)
- [TeX Stack Exchange](https://tex.stackexchange.com/)

## Document Class & Packages

This resume uses:
- **Document class**: `article` (11pt, letterpaper)
- **Key packages**:
  - `geometry`: Page margins
  - `enumitem`: List customization
  - `hyperref`: Clickable links
  - `titlesec`: Section formatting
  - `inputenc` & `fontenc`: Character encoding

All packages are included in standard LaTeX distributions.
