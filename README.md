# Lists and Tables

## Project Overview
This static web project demonstrates the creation of HTML lists and a complex table based on the provided template. [cite_start]It includes data about study programs at SŠPU Opava for the 2016/17 school year[cite: 46].

## Implemented Content

### Lists
[cite_start]The project contains four types of HTML lists[cite: 8]:
* [cite_start]**Ordered list:** Contains examples of web browsers[cite: 7, 9, 10, 11].
* [cite_start]**Unordered list:** Provides examples of IP, DNS, and URL addresses[cite: 12, 13, 14, 15].
* [cite_start]**Nested list:** Categorizes Hardware and Software into subcategories[cite: 16, 17, 26].
* [cite_start]**Description list:** Explains the ISOC, W3C, and IANA organizations[cite: 37, 38, 40, 42].

### Tables
[cite_start]A complex HTML table is included[cite: 44]:
* [cite_start]It consists of a header, body, and footer[cite: 45].
* [cite_start]The `colspan` and `rowspan` attributes are used to merge cells across multiple columns and rows[cite: 45].
* [cite_start]It displays the number of students (boys and girls) across specific programs: Information Technology, Engineering, and Art[cite: 52].

## File Structure
* [cite_start]**`index.html`:** The main document containing semantic HTML (`ol`, `ul`, `dl`, `table`, `thead`, `tbody`, `tfoot`)[cite: 47, 48, 50, 53, 54, 55].
* **`style.css`:** Cascading stylesheets defining the visual appearance, colors, fonts, and responsive design for screen widths up to 800px.
* **`predloha.txt` / `predloha.pdf`:** The original assignments and source texts used to build the content structure.

## How to Run
This is a pure HTML and CSS project, meaning no web server is required. `index.html` and `style.css` must be located in the same folder.

* **Arch Linux:** Run `xdg-open index.html` in the terminal, or open the file directly via your file manager (e.g., Dolphin, Thunar).
* **Ubuntu:** Double-click `index.html` in the file manager (Nautilus) or run `xdg-open index.html` in the terminal.
* **Windows 10 / 11:** Double-click the `index.html` file in File Explorer. It will automatically open in your default web browser (e.g., Edge or Chrome).
