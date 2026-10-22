# 📄 PDF Annotator

A modern, interactive PDF annotation web application built with React and TypeScript. Read PDF documents, highlight important content, add notes, draw shapes, navigate document sections, and export annotated PDFs through a clean, user-friendly interface.

## ✨ Features

- **📖 PDF Viewer** — Open and read PDF documents directly in the browser.
- **🖍️ Text Highlighting** — Highlight important text and keep annotations organized.
- **📝 Text Annotations** — Add notes and comments to selected content.
- **🟨 Area Highlighting** — Highlight specific regions of a PDF page.
- **✏️ Drawing Tools** — Annotate documents with drawing and shape tools.
- **🖼️ Image Annotations** — Add image-based annotations.
- **✍️ Editable Notes** — Create and edit free-text annotations.
- **🔎 PDF Search** — Search document text and navigate through matching results.
- **📑 Document Outline** — Navigate sections using the PDF table of contents.
- **📃 Page Navigation** — Browse pages and access document thumbnails.
- **🌙 Dark Mode** — Switch between light and dark viewing modes.
- **📤 Export PDF** — Export your annotated document.
- **📋 Annotation Management** — Search, sort, and review annotations by page.
- **🔍 Zoom Controls** — Adjust the PDF zoom level for comfortable reading.

## 🖥️ Application Preview

The application provides a three-panel interface with annotation management on the left, document outline and page navigation in the center, and the PDF viewer on the right.

![PDF Annotator application preview](<img width="1894" height="1060" alt="image" src="https://github.com/user-attachments/assets/3148e9c2-581e-41a3-b973-24eb3ce7711b" />
)

> To display the preview image, save a screenshot of your application as `pdf-annotator-preview.png` inside the `docs` folder.

## 🛠️ Tech Stack

- **React** — Component-based user interface
- **TypeScript** — Type-safe JavaScript development
- **Vite** — Development server and build tooling
- **PDF.js** — PDF rendering and document processing
- **Tailwind CSS** — Utility-first styling
- **Lucide React** — Icons
- **PDF-related libraries** — PDF processing and annotation export

## 🚀 Getting Started

### Prerequisites

Install the following software:

- [Node.js](https://nodejs.org/) — preferably an LTS version
- npm — included with Node.js
- [Git](https://git-scm.com/)

### 1. Clone the repository

```bash
git clone https://github.com/mohithshuka/pdf-annotation.git
cd pdf-annotation
```

### 2. Install dependencies

From the project root, run:

```bash
npm install
```

### 3. Start the development server

```bash
npm run dev
```

Open the local URL displayed in your terminal. The project configuration typically uses:

```text
http://localhost:3000
```

Use the actual URL printed by Vite if it differs.

### 4. Build the project

To build the library and example application using the project's configured build process, run:

```bash
npm run build
```

For the Vercel-specific build script, use:

```bash
npm run build:vercel
```

## 📘 How to Use

1. **Open a PDF:** Click **Open PDF** and select a document.
2. **Navigate the document:** Use the outline, page navigation, or search tools.
3. **Annotate content:** Select text or use the available annotation tools.
4. **Manage annotations:** Review highlights, search annotations, and organize them by page.
5. **Customize your view:** Adjust zoom and switch between light and dark modes.
6. **Export your work:** Click **Export PDF** to save the annotated document.

*Available tools and export behavior may depend on the current implementation.*

## 📂 Project Structure

```text
pdf-annotation/
├── docs/                  # Documentation
├── example/               # Example application
│   ├── src/               # Example source code
│   ├── index.html         # Example HTML entry point
│   └── vite.config.ts     # Vite configuration
├── src/                   # PDF annotation library source
│   ├── components/        # React components
│   ├── hooks/             # Custom React hooks
│   ├── lib/               # PDF utilities and helpers
│   ├── style/             # Component styles
│   ├── index.ts           # Library entry point
│   └── types.ts           # TypeScript types
├── package.json
├── tsconfig.json
└── vite.config.ts         # Example-specific configuration
```

## 🌐 Deployment

The application can be deployed to platforms such as [Vercel](https://vercel.com/).

For this repository, configure Vercel using the root project directory and verify that the build completes successfully before setting the generated static output directory.

## 🔮 Future Improvements

- Cloud storage for PDF documents and annotations
- User authentication and personalized workspaces
- Automatic saving and restoration of annotations
- Collaborative annotation and document sharing
- Additional annotation tools and customization options
- Improved mobile and tablet support

## 🤝 Contributing

Contributions, bug reports, and feature suggestions are welcome.

1. Fork the repository.
2. Create a feature branch.
3. Make your changes and test them.
4. Submit a pull request describing your improvements.

## 📄 License

This project uses the MIT License inherited from the underlying `react-pdf-highlighter-plus` project. Check the repository's `LICENSE` file for the applicable terms.

## 👨‍💻 Author

**Mohith Shuka**

- GitHub: [@mohithshuka](https://github.com/mohithshuka)
- Project: [PDF Annotator](https://github.com/mohithshuka/pdf-annotation)

---

⭐ If you find this project useful, consider giving the repository a star!
