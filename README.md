# Resume.

## Project Structure

- **Muhammad_Huzaifa.tex**: The main LaTeX source file for the Resume.
- **Muhammad_Huzaifa.pdf**: The compiled PDF version of the Resume.
- **.gitignore**: Configured to track only `.tex` and `.pdf` files, ignoring all other build artifacts.
- **Muhammad_Huzaifa.aux** and other auxiliary files: These are generated automatically by LaTeX during compilation and are not tracked by git.

## How to Use

1. **Edit the resume**  
   Make changes in the `Muhammad_Huzaifa.tex` file to update your Resume content.

2. **Compile the LaTeX File**  
   Use the following command to generate the PDF:
   ```bash
   pdflatex Muhammad_Huzaifa.tex
   ```
   This will produce `Muhammad_Huzaifa.pdf` and several auxiliary files.

3. **Version Control**  
   Only `.tex` and `.pdf` files are tracked in git. All other files (such as `.aux`, `.log`, etc.) are ignored.

## Requirements

- [LaTeX](https://www.latex-project.org/get/) distribution (e.g., TeX Live, MiKTeX)
