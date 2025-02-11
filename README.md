# UCAS, ICTP-AP Cover Letter Template (国科大投稿信模板)

![LaTeX](https://img.shields.io/badge/LaTeX-Professional-blue) ![Overleaf](https://img.shields.io/badge/Overleaf-Compatible-green) ![GitHub stars](https://img.shields.io/github/stars/iphysresearch/UCAS_ICTP_AP-cover_letter-template?style=social) ![GitHub](https://img.shields.io/github/license/iphysresearch/UCAS_ICTP_AP-cover_letter-template)

A professional and customizable LaTeX cover letter template designed for academic submissions, particularly tailored for researchers affiliated with the **University of Chinese Academy of Sciences (UCAS)** and/or the **International Centre for Theoretical Physics Asia-Pacific (ICTP-AP)**. This template ensures a polished and formal presentation for submitting manuscripts to academic journals.

---

## Features

- **Customizable Colors**: Easily switch between predefined colors (e.g., blue or black) for a personalized touch.
- **Professional Layout**: Includes sections for sender and editor details, a formal greeting, and a structured body for the cover letter content.
- **Logo Support**: Add your institution's logo for a branded look.
- **Detailed Annotations**: Clear comments guide users on how to modify each section, making it beginner-friendly.
- **Overleaf-Compatible**: Ready to use on Overleaf or any LaTeX editor.

---

## Quick Start
### Option 1: Use on Overleaf
1. Click the link below to open the template directly in Overleaf:     [![Overleaf Template](https://img.shields.io/badge/Overleaf-Template-blue)](https://www.overleaf.com/latex/templates/ucas-ictp-ap-cover-letter-template/xyz123)  

### Option 2: Download and Upload to Overleaf
1. **Download the Repository**:
   - Click the "Code" button on this GitHub page and select "Download ZIP".
2. **Upload to Overleaf**:
   - Log in to your Overleaf account.
   - Click "New Project" → "Upload Project" and select the downloaded ZIP file.
### Option 3: Use Locally
1. **Clone the Repository**:
   ```shell
   git clone https://github.com/iphysresearch/UCAS_ICTP_AP-cover_letter-template.git
   ```
2. **Open in LaTeX Editor**:
   - Open the [`main.tex`](main.tex) file in your preferred LaTeX editor (e.g., Overleaf, TeXShop, or TeXworks).
3. **Customize**:
   - Replace placeholders (e.g., `[Name]`, `[your.email@ucas.ac.cn]`, `[Journal of Old Friends]`) with your personal and editorial information.
4. **Compile**:
   - Compile the `.tex` file to generate a polished PDF cover letter.

---

## Customization
### Switching Colors
The template supports easy color switching between **MyBlack** (default) and **MyBlue**. To switch colors, modify the following line in `main.tex`:
```latex
\newcommand{\MyColor}{MyBlack} % Default: MyBlack
% \newcommand{\MyColor}{MyBlue} % Uncomment to switch to MyBlue
```
### Switching Logo
The template includes two default logos: `logo_ucas.jpg` (UCAS) and `logo_ictp-ap.jpg` (ICTP-AP). To switch logos:
1. Replace the default logo file with your institution's logo.
2. Ensure the logo is placed in the same directory as the `.tex` file.
3. Update the logo filename in the following line in `main.tex`:
```latex
\fancyhead[L]{\includegraphics[width=0.6\textwidth]{logo_ictp-ap.jpg}} % Replace with your logo filename
```
   
### Modifying Content
The template includes detailed annotations (comments) to guide you through each section. Look for placeholders enclosed in square brackets (e.g., `[Name]`, `[your.email@ucas.ac.cn]`) and replace them with your information. You can also delete or modify sections based on your needs.

---

## Example
Here’s an example of how the template looks when customized with different logos and colors:
| **UCAS Logo** | **ICTP-AP Logo** |
|---------------|------------------|
| ![UCAS Black](example_ucas_black.png) | ![ICTP-AP Black](example_ictp_black.png) |
| ![UCAS Blue](example_ucas_blue.png) | ![ICTP-AP Blue](example_ictp_blue.png) |

---

## Star History
Here’s the star history of this repository:
![Star History](https://starchart.cc/iphysresearch/UCAS_ICTP_AP-cover_letter-template.svg)

---

## Contributing
Contributions are welcome! If you have suggestions for improvements or find any issues, please open an [issue](https://github.com/iphysresearch/UCAS_ICTP_AP-cover_letter-template/issues) or submit a [pull request](https://github.com/iphysresearch/UCAS_ICTP_AP-cover_letter-template/pulls).

---

## License
This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgments
- Inspired by the need for a professional and customizable LaTeX cover letter template for academic submissions.
- Special thanks to the LaTeX community for their resources and support.

---

## Contact
For questions or feedback, please contact:  
📧 [your.email@ucas.ac.cn](mailto:your.email@ucas.ac.cn)  
🌐 [GitHub Repository](https://github.com/iphysresearch/UCAS_ICTP_AP-cover_letter-template)

---

**Happy Submitting!** 🚀
