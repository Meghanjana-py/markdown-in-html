# Markdown to HTML Converter

A simple, single-page web application that converts Markdown input to HTML, leveraging `marked.js` for conversion and `highlight.js` for syntax highlighting of code blocks. It initially loads `input.md` from the project root and allows users to upload custom Markdown files.

## Features

*   **Markdown to HTML Conversion**: Uses `marked.js` for robust and accurate Markdown parsing.
*   **Syntax Highlighting**: Integrates `highlight.js` to automatically detect and beautifully format code blocks in various programming languages.
*   **Responsive Design**: Built with Tailwind CSS for a modern, mobile-first, and fully responsive user interface.
*   **Initial `input.md` Load**: Automatically fetches and renders `input.md` from the project root upon page load.
*   **File Upload Functionality**: Allows users to upload any local `.md` file for conversion.
*   **Dark Mode Support**: Basic dark mode styling is included via Tailwind CSS classes.

## Technologies Used

*   **HTML5**: The structure of the web page.
*   **CSS (Tailwind CSS CDN)**: For responsive and modern styling.
*   **JavaScript**: Powers the client-side logic.
*   **[Marked.js](https://marked.js.org/)**: A fast Markdown parser and compiler written in JavaScript.
*   **[Highlight.js](https://highlightjs.org/)**: JavaScript syntax highlighter for the web.

## Setup and Usage

To get this application running locally, follow these simple steps:

1.  **Clone the Repository** (or save the `index.html` file):
    If you have a repository containing these files, clone it:
    ```bash
    git clone <your-repository-url>
    cd <your-repository-directory>
    ```
    If you only have the `index.html` file, save it as `index.html` in a new directory.

2.  **Place `input.md`**: Ensure your Markdown content file, named `input.md`, is located in the same directory as `index.html`. This file will be loaded by default when you open the application.

3.  **Open in Browser**: Simply open the `index.html` file in your preferred web browser. You can do this by double-clicking the file or by navigating to it via your browser's file menu.

    The application will automatically load and render `input.md`. You can then use the "Choose Markdown File" input to upload and convert other `.md` files from your local machine.

## Project Structure

```
.|
├── index.html       # The main web application file
├── README.md        # This README file
├── LICENSE          # The MIT License file
└── input.md         # The default Markdown file to be loaded
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
