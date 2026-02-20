# Salih Karabulut - Personal Website & CV

🚀 **[View Live CV](https://karabulut18.github.io/cv/)**

Automated LaTeX CV and Portfolio website for Salih Karabulut.

## Features
- **Modern LaTeX CV**: Professionally formatted resume built using the `memoir` class and a customized Wenneker template.
- **Automated CI/CD**: GitHub Actions workflow (`latex.yml`) automatically compiles the LaTeX source and deploys it to GitHub Pages on every push.
- **Portfolio Landing Page**: A clean, responsive landing page providing quick access to the CV (online and PDF) and social profiles.

## Project Structure
- `latex/`: Contains the LaTeX source files (`cv.tex`, `structure.tex`).
- `.github/workflows/`: Contains the CI/CD pipeline for automated builds and deployment.
- `docs/`: (Generated) Contains the compiled CV and landing page for GitHub Pages.

## How to Edit
1. Modify `latex/cv.tex` to update your professional information.
2. Push your changes to the `main` branch.
3. GitHub Actions will handle the compilation and deployment automatically.
