# 📊 Semantic HTML Lists & Complex Tables

> A clean, responsive educational web demonstration illustrating semantic HTML5 lists and complex multi-span tables with CSS styling and responsive media queries, built according to assignment specifications for SŠPU Opava.

[![Standards](https://img.shields.io/badge/Standards-HTML5%20%7C%20CSS3-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![Design](https://img.shields.io/badge/Design-Responsive%20(Mobile%20Friendly)-informational?style=for-the-badge)](style.css)
[![Project](https://img.shields.io/badge/Institution-SŠPU%20Opava-red?style=for-the-badge)](https://www.sspu-opava.cz/)
[![License](https://img.shields.io/badge/License-MIT-success?style=for-the-badge)](LICENSE)

---

## 📌 Project Overview

This project showcases fundamental web structuring techniques by translating a formal school specification (`predloha/predloha.pdf`) into semantic, standards-compliant HTML5 and responsive CSS3. 

The demonstration emphasizes:
1. All four standard HTML list structures.
2. A complex tabular data matrix using advanced cell spanning (`rowspan` and `colspan`).
3. Clean, responsive styling for viewports down to 800px.

---

## 📑 Implemented Components

### 1. Semantic HTML Lists
The document implements four distinct list archetypes:

- **Numbered / Ordered List (`<ol>`)**: Sequential listing of modern web browsers with custom numeric formatting.
- **Unordered List (`<ul>`)**: Categorized technical networking elements (IPv4 / IPv6 addresses, DNS records, and URL anatomy).
- **Multi-Level Nested List**: Hierarchical taxonomy separating computer engineering domains into Hardware components and Software classifications.
- **Description / Definition List (`<dl>`, `<dt>`, `<dd>`)**: Structured glossary defining international internet governance bodies (**ISOC**, **W3C**, **IANA**).

---

### 2. Complex Data Table Matrix
The project features a structured data table documenting student enrollment statistics at SŠPU Opava across academic disciplines:

```
+-------------------------------------------------------------------------+
|                  SŠPU Opava — Statistika oborů 2016/17                  |
+----------------------+--------------------+-----------------------------+
|                      |   Počet chlapců    |        Počet dívek          |
| Obor vzdělání        +---------+----------+----------+------------------+
|                      | 1. roč. | 2. roč.  | 1. roč.  | 2. roč.          |
+----------------------+---------+----------+----------+------------------+
| Informační technologie      ...                 ...                     |
| Strojírenství               ...                 ...                     |
| Umělecké obory              ...                 ...                     |
+-------------------------------------------------------------------------+
| Celkový součet (tfoot)                          ...                     |
+-------------------------------------------------------------------------+
```

#### Structural Highlights:
- **Semantic Sections**: Complete separation of table structure using `<thead>`, `<tbody>`, and `<tfoot>`.
- **Merged Cell Coordinates**: Strategic usage of `rowspan` for multi-row subject groupings and `colspan` for nested subheaders and summary totals.
- **Header Scopes**: Accessible data associations using `<th>` cells with appropriate styling.

---

## 🎨 Styling & Responsive Layout (`style.css`)

- **Balanced Color Palette**: Subtle alternating row background fills for effortless readability.
- **Typography**: Clean, readable sans-serif typography with calibrated cell padding.
- **Responsive Viewport Media Query**: Graceful scaling and horizontal scroll wrapping for viewports at or below `800px` screen width.

---

## 📁 Repository Structure

```
seznamy-tabulky/
├── index.html       # Primary semantic HTML5 document
├── style.css        # Cascading stylesheet with typography and table styles
├── predloha/        # Original assignment specifications
│   ├── predloha.pdf # Assignment reference PDF
│   └── predloha.txt # Source data specification text
└── README.md        # Technical project documentation
```

---

## 🚀 How to Open & Preview

No build steps or local servers are necessary.

### Direct Browser Launch
- **Linux**:
  ```bash
  xdg-open index.html
  ```
- **macOS**:
  ```bash
  open index.html
  ```
- **Windows**:
  Double-click `index.html` in File Explorer or run:
  ```powershell
  Start-Process index.html
  ```

---

## 📄 License

Created for educational purposes at SŠPU Opava. Licensed under the MIT License.
