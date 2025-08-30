# LaTeX Resume Template

This repository provides a fully customizable LaTeX resume template along with a sample PDF output. It is based on the original work by **Jitin Nair** (2021) under the MIT License, and has been modified in 2025 to include generalized placeholders and usage instructions.

## Contents

- **cv.tex** — The LaTeX source file with placeholder fields and section prompts.
- **Resume_Software.pdf** — A compiled example PDF showcasing the template’s layout and styling.
- **LICENSE** — The MIT License, with copyright attributed to Jitin Nair and modifications by you.
- **README.md** — This usage guide.

## Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```

2. **Install LaTeX**
   Ensure you have a TeX distribution installed (e.g., TeX Live, MiKTeX). A minimal installation with `latex`, `pdflatex`, and required packages is sufficient.

3. **Customize the Template**
   - Open **resume-template.tex** in your text editor.
   - Replace all bracketed placeholders (`[Your Full Name]`, `[Company Name]`, `[Duration]`, etc.) with your personal information.
   - Follow the inline comments and section prompts to add your profile summary, education, skills, certifications, projects, and experience.

4. **Compile to PDF**
   From the repository root, run:
   ```bash
   pdflatex resume-template.tex
   bibtex resume-template      # only if you have bibliography entries
   pdflatex resume-template.tex
   pdflatex resume-template.tex
   ```
   Output: **resume-template.pdf**

5. **Review & Iterate**
   - Open the generated PDF to verify formatting and content.
   - Adjust spacing or styling by editing the `.tex` file as needed.

## License

This template is released under the **MIT License**:

- Original copyright © 2021 Jitin Nair
- Modified © 2025 by [Your Name]

See the complete terms in the **LICENSE** file.

---

Feel free to fork, customize, and improve this template for your own use!
