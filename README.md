# COMP0263 - Solving Inverse Problems with Data-Driven Models

![Build Status](https://github.com/UCL-COMP0263-2026/Course-Materials/workflows/Build%20LaTeX%20Documents/badge.svg)

## Overview

This module bridges the gap between traditional mathematical inverse problem theory and modern deep learning. While modules like Inverse Problems in Imaging focus on hand-crafted model-based methods, this course explores how data-driven approaches and neural networks are revolutionising the field. You will learn to solve complex inverse problems - such as medical imaging, remote sensing, and deblurring - by learning regularisation functions and operators directly from data, while also discovering the pitfalls of data-driven approaches with regards to stability and convergence.

This repository contains both a comprehensive lecture notes document and weekly presentation slides, all automatically compiled to PDF via GitHub Actions.

## Contents

- **Lecture_Notes/**: A comprehensive evolving book containing all lecture material
- **Slides/**: Weekly presentation slides organised by week
- **Common_Images/**: Shared images and figures for both notes and slides

## Getting Started

### Latest Compiled PDFs

Download the latest compiled PDFs from:
- **Actions tab**: [GitHub Actions](https://github.com/UCL-COMP0263-2026/Course-Materials/actions) → Latest workflow run → Artifacts
- **Releases**: [Release section](https://github.com/UCL-COMP0263-2026/Course-Materials/releases)

### Local Compilation

To compile locally, you'll need a LaTeX installation (TeX Live, MacTeX, or MiKTeX).

```bash
# Compile lecture notes
cd Lecture_Notes
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex

# Compile slides
cd ../Slides/Week_01
pdflatex lecture1.tex
```

## Contributing

We welcome contributions! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

### Quick Tips for Contributors

- **Fixing typos or improving content**: Edit the appropriate chapter file in `Lecture_Notes/chapters/` or slide file in `Slides/`
- **Adding images**: Place them in `Common_Images/` so both notes and slides can use them
- **Questions or discussions**: Use [GitHub Discussions](https://github.com/UCL-COMP0263-2026/Course-Materials/discussions)

## License

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 3.0 Unported License](https://creativecommons.org/licenses/by-nc-sa/3.0/).

**In brief**: You are free to share and adapt this material for non-commercial purposes, as long as you provide attribution and distribute your contributions under the same license. See [LICENSE](LICENSE) for full details.

## Contact

For questions, please open a [GitHub Discussion](https://github.com/UCL-COMP0263-2026/Course-Materials/discussions) or contact the course instructors.
