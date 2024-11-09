# Academix LaTeX Template

Academix is a comprehensive and flexible LaTeX template designed for writing academic articles, reports, and theses. Inspired by the [EPUSP Thesis Template](https://github.com/fbarbieri77/EPUSP_thesis_template), this template provides extensive customization options to suit various academic contexts, while adhering to professional formatting standards.

## Features
- Academic Document Class: Custom `academix` class for easy configuration.
- Versatile Formatting Options: Supports articles, reports, and theses with automatic styling for chapters, sections, and appendices.
- Math and Theorem Support: Enhanced typesetting for equations, theorems, proofs, and mathematical symbols.
- Advanced Float Handling: Improved figure and table placement with flexible formatting.
- Built-in Customization: Includes user-friendly commands for author details, cover page setup, dedication, acknowledgments, and more.
- Pre-Defined Templates: Includes templates for dedication, acknowledgments, abstract, and appendices.

## Getting Started

### Prerequisites

To use this template, you need a TeX distribution such as [TeX Live](https://www.tug.org/texlive/) or [MikTeX](https://miktex.org/), and a LaTeX editor such as [Overleaf](https://www.overleaf.com/), [Texmaker](https://www.xm1math.net/texmaker/), or [VS Code](https://code.visualstudio.com/) with the LaTeX Workshop extension.

### Installation

Clone the repository to your local machine:
```bash
git clone https://github.com/willfliaw/academix.git
```

### Usage

1. Open `main.tex` in your LaTeX editor.
2. Customize document details using the provided commands:
   ```latex
   \customAuthor{Your Name}
   \customTitle{Your Thesis Title}
   \advisor{Prof. Dr. Advisor Name}
   ```
3. Compile the document (`main.tex`) to generate your final PDF.

### Directory Structure

- `academix/`: Contains the `academix.cls` file and related class dependencies.
- `doc/`: Includes sample files such as `abstract.tex`, `acknowledgement.tex`, and `symbols.tex` to help you get started.
- `figures/`: Directory for storing images to be used in the document.
- `main.tex`: Main entry point for building your thesis or report.

### Customization

Academix is designed to be highly customizable:
- Formatting: Use document options (`a4paper`, `doubleSpacing`, `uppercaseChapter`, etc.) to adjust formatting.
- Cover Page: Customize author information, advisor, concentration field, and department using dedicated commands.
- Content Inclusion: Easily include pre-textual elements such as dedication, acknowledgments, and abstract by modifying the corresponding files in the `doc/` directory.

## Credits and Attribution

Academix is heavily inspired by the [EPUSP Thesis Template](https://github.com/fbarbieri77/EPUSP_thesis_template) by fbarbieri77. Many components were adapted to enhance flexibility and usability for broader academic writing contexts.

## Contributions

Contributions are welcome! Feel free to open issues for bugs or feature requests, or to submit pull requests with enhancements.

## Contact

For questions or suggestions, please contact:
[William Liaw](mailto:willfliaw@gmail.com)
