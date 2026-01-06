# Contributing to Course Materials

Thank you for your interest in improving these course materials! We welcome contributions from students, instructors, and anyone in the community.

## How to Contribute

### 1. **Fixing Typos or Improving Content**

If you spot a typo, have a suggestion, or want to improve the clarity of the lecture notes or slides:

1. Fork this repository
2. Create a new branch: `git checkout -b fix/your-fix-name`
3. Make your changes:
   - **For lecture notes**: Edit the appropriate chapter file in `Lecture_Notes/chapters/`
   - **For slides**: Edit the corresponding file in `Slides/Week_XX/`
4. Commit with a clear message: `git commit -m "Fix typo in Chapter 2"`
5. Push and open a Pull Request

We'll review and merge your contribution!

### 2. **Asking Questions or Starting Discussions**

Have a question about the course material or want to discuss a concept?

- Use [GitHub Discussions](https://github.com/UCL-COMP0263-2026/Course-Materials/discussions) for questions and general discussion
- Use the 👍 emoji to upvote questions you find useful

### 3. **Reporting Issues**

Found a problem or have a suggestion? [Open an issue](https://github.com/UCL-COMP0263-2026/Course-Materials/issues) with:
- A clear description of the problem
- Where you found it (file, line number if possible)
- Any relevant context

## Structure of Materials

### Lecture Notes (`Lecture_Notes/`)

The lecture notes form a **single evolving book**:
- `main.tex`: The master file that ties everything together
- `chapters/`: Individual chapter files included in the main document
- `references.bib`: Bibliography entries
- Images are placed in `Common_Images/` or `Lecture_Notes/images/`

### Slides (`Slides/`)

Weekly presentation slides:
- Organized by week: `Week_01/`, `Week_02/`, etc.
- Each lecture is a standalone `.tex` file compiled to PDF
- Can use shared images from `Common_Images/`

## Contribution Guidelines

- **Be respectful**: We're a community of learners
- **Keep it clear**: Use clear commit messages and explain your changes
- **Test locally**: Compile your LaTeX changes before submitting
- **Use proper formatting**: Follow the existing style and structure
- **Attribution**: If adding large sections, consider adding your name in a comment

## Pull Request Process

1. Ensure your changes compile without errors
2. Add a clear PR title and description
3. Reference any related issues
4. Be ready for constructive feedback

Example PR description:
```
## Summary
Fixed typos in Chapter 2 and improved explanation of Algorithm X.

## Changes
- Fixed spelling error on page 15
- Clarified the complexity analysis section
- Added reference to recent paper

## Related Issues
Closes #42
```

## Building and Testing Locally

### Prerequisites
- TeX Live / MacTeX / MiKTeX
- Git

### Build Commands
```bash
# Build lecture notes
cd Lecture_Notes
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex

# Build a specific week's slides
cd ../Slides/Week_01
pdflatex lecture1.tex
```

Check for compilation errors and ensure the PDF looks correct.

## Questions?

- 📧 Open a [GitHub Discussion](https://github.com/UCL-COMP0263-2026/Course-Materials/discussions)
- 🐛 Found a bug? [Report an issue](https://github.com/UCL-COMP0263-2026/Course-Materials/issues)

---

**Thank you for helping improve these materials!** ✨
