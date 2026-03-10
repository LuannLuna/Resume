# Luann Luna - Senior iOS Resume

This repository contains my latest resume and a simple web page for easy viewing and downloading via GitHub Pages.

## Overview

The resume is maintained as LaTeX source code with automated PDF building via GitHub Actions. Every change to the LaTeX source automatically generates an updated PDF that is served through GitHub Pages.

## Repository Structure

```
.
├── LaTeX/                          # LaTeX source files
│   ├── resume.tex                  # Main resume source
│   ├── Makefile                    # Local build automation
│   └── README.md                   # LaTeX-specific documentation
├── .github/workflows/              # GitHub Actions CI/CD
│   └── build-latex-resume.yml      # Auto-build workflow
├── index.html                      # GitHub Pages landing page
├── Luann_Luna_Senior_iOS_Resume.pdf # Generated resume PDF
└── README.md                       # This file
```

## Editing the Resume

1. Edit `LaTeX/resume.tex` with your changes
2. (Optional) Build locally to preview: `cd LaTeX && make pdf`
3. Commit and push to `main` branch
4. GitHub Actions automatically builds and updates the PDF
5. Updated resume appears on GitHub Pages

For detailed build instructions and local development setup, see [LaTeX/README.md](LaTeX/README.md).

## GitHub Pages

The resume is automatically published via GitHub Pages at:
**https://luannluna.github.io/Resume/**

The page redirects directly to the latest PDF or provides a download link.