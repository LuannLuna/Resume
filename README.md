# Luann Luna - Senior iOS Resume

This repository contains my latest resume in both English and Portuguese, with automated PDF generation via GitHub Actions.

## 📄 View Resume

Choose your preferred language:

- 🇺🇸 **[English Resume](https://luannluna.github.io/Resume/)** - [Direct PDF Link](https://github.com/LuannLuna/Resume/raw/main/Luann_Luna_Resume_EN.pdf)
- 🇧🇷 **[Currículo em Português](https://luannluna.github.io/Resume/)** - [Link Direto para PDF](https://github.com/LuannLuna/Resume/raw/main/Luann_Luna_Resume_PT.pdf)

## 🏗️ Repository Structure

```
.
├── LaTeX/                          # LaTeX source files
│   ├── resume-en.tex              # English resume source
│   ├── resume-pt.tex              # Portuguese resume source
│   ├── Makefile                    # Local build automation
│   └── README.md                   # LaTeX-specific documentation
├── .github/workflows/              # GitHub Actions CI/CD
│   └── build-latex-resume.yml      # Auto-build workflow
├── index.html                      # GitHub Pages landing page
├── Luann_Luna_Resume_EN.pdf       # English PDF (auto-generated)
├── Luann_Luna_Resume_PT.pdf       # Portuguese PDF (auto-generated)
└── README.md                       # This file
```

## 🚀 How It Works

The resume is maintained as LaTeX source code with automated PDF building:

1. **LaTeX Source**: Resume content is in `LaTeX/resume-en.tex` (English) and `LaTeX/resume-pt.tex` (Portuguese)
2. **Local Building**: Use `make all` in the LaTeX directory to build both PDFs locally
3. **Automated CI/CD**: Any change to LaTeX source triggers GitHub Actions to build both PDFs
4. **GitHub Pages**: Landing page at https://luannluna.github.io/Resume/ allows language selection

## 💻 Building Locally

### Prerequisites
- LaTeX distribution (MacTeX or BasicTeX on macOS)
- Required packages: `enumitem`, `titlesec`, `hyperref`

### Installation (macOS)
```bash
# Full distribution (recommended)
brew install --cask mactex

# OR minimal distribution
brew install --cask basictex
sudo tlmgr install enumitem titlesec hyperref
```

### Build Commands
```bash
cd LaTeX

# Build both versions
make all

# Build English only
make en

# Build Portuguese only
make pt

# Clean build artifacts
make clean
```

## 📝 Making Updates

1. Edit the appropriate LaTeX source file:
   - English: `LaTeX/resume-en.tex`
   - Portuguese: `LaTeX/resume-pt.tex`

2. (Optional) Build locally to preview:
   ```bash
   cd LaTeX && make all
   ```

3. Commit and push changes:
   ```bash
   git add LaTeX/resume-*.tex
   git commit -m "Update resume content"
   git push
   ```

4. GitHub Actions automatically builds and deploys updated PDFs

## 🔗 Links

- **GitHub Pages**: https://luannluna.github.io/Resume/
- **LinkedIn**: https://linkedin.com/in/luannluna
- **GitHub**: https://github.com/LuannLuna

---

Built with LaTeX • Automated with GitHub Actions • Served via GitHub Pages
