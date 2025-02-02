# HTMLBlogMaker

**HTMLBlogMaker** is a responsive, integrated web tool that allows you to quickly convert plain text (using a simple Markdown-like syntax) into styled HTML code for your blog posts. It also includes an HTML combiner that lets you merge multiple produced HTML parts into one final HTML document. This tool is ideal for bloggers and content creators who want to generate clean, customizable HTML without writing code from scratch.

## Features

- **Text-to-HTML Conversion**
  - Write your blog content in plain text using simple markers:
    - Use `#` for Header 1 (collapsible).
    - Use `##` for Header 2.
    - Use `###` for Header 3.
    - Use `####` for Header 4.
    - Use `#####` for Header 5.
    - Use `######` for Header 6.
  - **Header Styling Hierarchy:**
    - **Header 1:** Displayed with a background color (from the chosen color scheme) and white text; font size is **24px** (bold).
    - **Headers 2–6:** Have no background (transparent) and use different text colors (each a slightly different shade in the same spectrum as the default). Their font sizes descend as follows:
      - **Header 2:** 22px (bold)
      - **Header 3:** 20px (bold)
      - **Header 4:** 18px (bold)
      - **Header 5:** 16px (bold)
      - **Header 6:** 12px (bold)
    - **Body text:** 12px normal weight.
  - Collapsible functionality: Header 1 sections are collapsible, allowing you to hide/show content.
  - Automatic inline styling is applied based on the selected color scheme.

- **Color Scheme Customization**
  - Choose from three color schemes:
    - **Default:**  
      - Page Header: `#8B5E3C`  
      - Produced Header (Header 1): `#DCA54A`  
      - Collapsible Content: `#FFFEF6`
      - Headers 2–6: Descending shades from the default spectrum.
    - **Blue:**  
      - Page Header: `#0056b3`  
      - Produced Header: `#66afe9`  
      - Collapsible Content: `#cce5ff`
    - **Green:**  
      - Page Header: `#28a745`  
      - Produced Header: `#8fce8f`  
      - Collapsible Content: `#dff0d8`
  - When the color scheme is changed, the produced HTML preview and final generated HTML update automatically.

- **HTML Combiner**
  - Combine multiple produced HTML parts (each a complete HTML document) into one final HTML document.
  - Each input box (called a "box" in English) lets you paste produced HTML code.
  - The first box is fixed; additional boxes can be removed if added by mistake.
  - The combiner extracts the `<body>` content from each part and wraps them in a new, complete HTML document.

- **Copy-to-Clipboard Functionality**
  - Easily copy the produced HTML preview, the final HTML document, or the combined HTML code with a single click.

- **Responsive and Mobile-Friendly**
  - The tool is fully responsive and adjusts its layout for desktops, tablets, and mobile devices.

## Installation

1. **Clone or Download the Repository:**
   ```bash
   git clone https://github.com/yourusername/HTMLBlogMaker.git
