# Abhishek Prasad's Resume

[![Build & Deploy](https://github.com/abhishek622/resume/actions/workflows/build-and-deploy.yml/badge.svg)](https://github.com/abhishek622/resume/actions/workflows/build-and-deploy.yml)
[![GitHub Pages](https://img.shields.io/badge/View%20Online-GitHub%20Pages-brightgreen)](https://abhishek622.github.io/resume/)

## 📄 Resume

This repository contains the LaTeX source code for my professional resume. The resume is automatically built and deployed to GitHub Pages on every push to the `main` branch.

### 📥 Download

- [Download PDF](https://abhishek622.github.io/resume/abhishekprasad.pdf)
- [View Online](https://abhishek622.github.io/resume/)

### 🛠️ Building Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/abhishek622/resume.git
   cd resume
   ```

2. Compile the LaTeX document:
   ```bash
   pdflatex cv.tex
   # or use xelatex if needed
   # xelatex cv.tex
   ```

### 🔄 Automatic Deployment

The resume is automatically built and deployed using GitHub Actions. The workflow:

- Builds the LaTeX document
- Creates a web viewer
- Deploys to GitHub Pages

### 📄 License

This project is licensed under the [Apache License](LICENSE).
