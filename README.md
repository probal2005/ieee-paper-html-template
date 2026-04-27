# 📄 IEEE Paper Template (HTML + CSS + MathJax)

A fully functional **IEEE-style research paper template built using HTML, CSS, and JavaScript**, designed to closely match the official LaTeX IEEE conference format.

This project allows you to write, preview, and print your research paper directly in the browser with **A4 layout, two-column format, and professional typography**.

---

## 🚀 Features

* 📑 **A4 Page Layout** (Print-ready)
* 📰 **Two-Column IEEE Format**
* 🔠 **Times New Roman Font (IEEE Standard)**
* 🔢 **Auto Section Numbering (I, II, III...)**
* 🧮 **MathJax Support (LaTeX Equations)**
* 🖼 **Auto Figure Numbering (Fig. 1, Fig. 2...)**
* 📊 **Table Formatting (IEEE Style)**
* 🧾 **Optional Reference Numbering**
* ✂️ **Auto Hyphenation (LaTeX-like)**
* 📐 **Justified Text Alignment**
* 👨‍💻 **Multi-Author Layout (Up to 6 Authors)**
* 🖨 **Print Button (A4 Export Ready)**

---

## 📂 Project Structure

```
📁 IEEE-HTML-Paper
 ┣ 📄 index.html   # Main paper file
 ┣ 📄 README.md    # Documentation
```

---

## 🛠 Technologies Used

* **HTML5**
* **CSS3 (Advanced Layout + Counters)**
* **JavaScript**
* **MathJax** (for equations)
* **Hyphenopoly.js** (for auto hyphenation)

---

## 🧑‍🔬 IEEE Format Supported

This template follows standard IEEE formatting:

| Element      | Format       |
| ------------ | ------------ |
| Title        | 24 pt        |
| Author Names | 11 pt        |
| Affiliations | 10 pt Italic |
| Abstract     | 9 pt         |
| Body Text    | 10 pt        |
| Headings     | Small Caps   |
| Captions     | 8 pt         |
| Layout       | Two Column   |

---

## ✍️ Sections Included

* Title
* Authors (up to 6)
* Abstract
* Keywords
* Introduction
* Literature Review
* Problem Statement
* Objectives
* Methodology
* Tools & Technologies
* Dataset
* Experimental Results
* Discussion
* Conclusion
* Future Scope
* Acknowledgment
* References

---

## ▶️ How to Use

1. Download or clone the repository:

   ```
   git clone https://github.com/your-username/ieee-html-paper.git
   ```

2. Open the file:

   ```
   index.html
   ```

3. Edit content:

   * Replace title, authors, and sections
   * Add your own data, images, and equations

4. View in browser:

   * Open with Chrome / Edge for best results

5. Print as PDF:

   * Click **Print Button**
   * Select **A4 Size**
   * Disable margins if needed

---

## 🖨 Print Settings (IMPORTANT)

For perfect IEEE output:

* Paper Size → **A4**
* Margins → **Default / None**
* Scale → **100%**
* Background Graphics → ✅ Enabled

---

## ⚙️ Customization

### Remove Section Numbering

```css
h2::before {
    content: "";
}
```

### Remove Reference Numbering

```css
.references div::before {
    content: "";
}
```

### Disable Equation Numbering

```css
.eq::after {
    display: none;
}
```

---

## ⚠️ Notes

* This is a **web-based alternative** to LaTeX IEEE template
* Output is visually similar but not officially certified by IEEE
* Best used for:

  * Final year projects
  * College papers
  * Draft research writing

---

## 📜 License

MIT License

---

## 🙌 Contribution

Feel free to:

* Fork the repo
* Improve styling
* Add new features (PDF export, citation tools, etc.)

---

## ⭐ Support

If you find this useful:
👉 Give it a **star ⭐ on GitHub**

---

## 📧 Contact

For queries or improvements, feel free to connect.

---

**Made with ❤️ for students and researchers**
