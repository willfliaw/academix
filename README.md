# Academix LaTeX Template

**Academix** is a versatile and comprehensive LaTeX template designed for academic writing, including articles, reports, and theses. Drawing inspiration from the [EPUSP Thesis Template](https://github.com/fbarbieri77/EPUSP_thesis_template), this template offers extensive customization to suit a wide range of academic and professional formatting needs.

---

## 📋 Features

- **Custom Document Class**: Simplify your workflow with the `academix` class, designed for academic documents.
- **Versatile Document Types**: Supports articles, reports, and theses, with automatic styling for chapters, sections, and appendices.
- **Advanced Math Support**: Enhanced typesetting for equations, theorems, proofs, and mathematical symbols.
- **Improved Float Management**: Enhanced figure and table placement with robust formatting options.
- **Customizable Pre-Text Elements**: Templates for dedication, acknowledgments, abstract, and appendices are included for quick setup.
- **User-Friendly Commands**: Easily configure author details, cover pages, and other common elements.
- **Professional Formatting Options**: Fine-tune document appearance with options for paper size, spacing, font styles, and more.

---

## 🚀 Getting Started

### Prerequisites

To use the Academix template, ensure you have the following installed:
- A TeX distribution: [TeX Live](https://www.tug.org/texlive/) or [MikTeX](https://miktex.org/).
- A LaTeX editor: [Overleaf](https://www.overleaf.com/), [Texmaker](https://www.xm1math.net/texmaker/), or [VS Code](https://code.visualstudio.com/) with the **LaTeX Workshop** extension.

---

### Installation

Clone the repository to your local machine:
```bash
git clone https://github.com/willfliaw/academix.git
```

Alternatively, you can download it directly as a ZIP file.

---

### Usage

1. Open `main.tex` in your LaTeX editor.
2. Customize your document by modifying the provided commands.
3. Add or edit textual content in the `doc/` directory.
4. Compile `main.tex` to generate your final PDF.

---

### Directory Structure

- `academix/`: Contains the `academix.cls` file and other class dependencies.
- `doc/`: Includes sample files for dedication, acknowledgments, abstract, and more.
- `figures/`: Directory for storing images used in the document.
- `main.tex`: The main entry point for your project.

---

### Customization

Academix is designed with flexibility in mind:
- **Formatting Options**: Adjust settings such as paper size, line spacing, and chapter styles using class options in `academix/class_options.tex`.
- **Cover Page**: Personalize author details, advisor information, concentration field, and more with dedicated commands.
- **Pre-Text Elements**: Modify files like `dedication.tex`, `acknowledgment.tex`, and `abstract.tex` in the `doc/` directory to customize your content.

---

## ⚠️ Disclaimer: CamelCase Style

LaTeX traditionally uses lowercase commands and variable names, albeit inconsistently. While this convention is widely followed, the Academix template adopts the **camelCase style** for its custom commands and variables. The rationale behind this choice includes:

- **Readability**: camelCase commands are easier to read and distinguish from LaTeX's default commands.
- **Consistency**: A consistent naming style is preferable to an inconsistent mix of styles.
- **Separation**: Custom commands contrast clearly with LaTeX's built-in parameters, reducing ambiguity.

It’s important to note:
- Default LaTeX objects that have been redefined in Academix retain their original names for compatibility.
- This decision prioritizes usability and clarity for users of the template.

While this approach may differ from LaTeX conventions, it is designed to enhance the user experience by providing a structured and easily recognizable command style.

---

## 🤝 Contributions

Contributions are welcome! If you encounter bugs, have feature requests, or wish to improve the template, feel free to:
1. **Open an Issue**: Report bugs or suggest enhancements.
2. **Submit a Pull Request**: Contribute directly to the repository.

---

## 💡 Credits

This template is inspired by the [EPUSP Thesis Template](https://github.com/fbarbieri77/EPUSP_thesis_template) by fbarbieri77. Many elements have been adapted to provide greater flexibility for a wide range of academic writing needs.

---

## 📬 Contact

For questions, suggestions, or feedback, reach out to:
**William Liaw**
📧 [willfliaw@gmail.com](mailto:willfliaw@gmail.com)
