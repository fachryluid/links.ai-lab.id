# links.ai-lab.id

This is a static link-sharing page built with HTML and Tailwind CSS.

---

## Tech Stack

*   HTML
*   Tailwind CSS

---

## Getting Started

### Requirement

*   Node.js and npm must be installed.

### Instalation

1.  Clone the repository:
    ```sh
    git clone https://github.com/AI-Lab-Indoneisa/links-ai-lab.git
    cd links-ai-lab.id
    ```

2.  Install dependencies:
    ```sh
    npm install
    ```

---

## How to Update / Modify

This project uses Tailwind CSS to style the HTML. You do not edit the `output.css` file directly.

### 1. Start the Development Watcher

Run this command in your terminal. It will watch for any style changes and automatically rebuild the CSS file.
```sh
npm run dev
```

### 2. Modify the Content and Styles

*   **To change links or text:** Edit the `index.html` file.
*   **To change styles (colors, spacing, etc.):** Add or modify Tailwind utility classes in `index.html` and add any custom CSS to `src/input.css`.

The `npm run dev` process will automatically compile your changes from `src/input.css` into `src/output.css`.

### 3. Commit Your Changes

Once you are done, commit all modified files, including `index.html`, `src/input.css`, and the generated `src/output.css`.

### 4. Build for Production (Optional)

Before deploying, you can run the build script to create a minified version of the CSS file.
```sh
npm run build
```