# Flyfish Dev

Browser-native file preview, CAD viewing, document rendering, and developer tooling.

Flyfish Dev builds open-source components that help business systems preview complex files directly in the browser: Office documents, PDF/OFD, CAD drawings, archives, email, ebooks, code, media, and structured data.

<p align="center">
  <a href="https://file-viewer.app"><img alt="File Viewer" src="https://img.shields.io/badge/File%20Viewer-official%20site-16a34a?style=for-the-badge"></a>
  <a href="https://doc.file-viewer.app"><img alt="Documentation" src="https://img.shields.io/badge/Docs-file--viewer.app-2563eb?style=for-the-badge"></a>
  <a href="https://demo.file-viewer.app"><img alt="Demo" src="https://img.shields.io/badge/Demo-online-0f766e?style=for-the-badge"></a>
</p>

## Start Here

| Repository | What It Is | When To Use It |
| --- | --- | --- |
| [file-viewer](https://github.com/flyfish-dev/file-viewer) | Full open-source File Viewer monorepo and distribution entry | Start here for browser-native preview across 194+ extensions |
| [file-viewer-core](https://github.com/flyfish-dev/file-viewer-core) | Framework-neutral TypeScript rendering core | Build a custom integration on top of the low-level API |
| [file-viewer-vue3](https://github.com/flyfish-dev/file-viewer-vue3) | Standard Vue 3 component package | Vue 3 apps, admin systems, knowledge bases, contract portals |
| [file-viewer-react](https://github.com/flyfish-dev/file-viewer-react) | Standard React component package | React 18/19 products and design systems |
| [file-viewer-web](https://github.com/flyfish-dev/file-viewer-web) | Pure Web / JavaScript package | Native pages, Web Components, micro frontends, script-style integration |

## File Viewer Ecosystem

| Package Repository | Target |
| --- | --- |
| [file-viewer-vue2.7](https://github.com/flyfish-dev/file-viewer-vue2.7) | Vue 2.7 |
| [file-viewer-vue2.6](https://github.com/flyfish-dev/file-viewer-vue2.6) | Vue 2.6 |
| [file-viewer-react-legacy](https://github.com/flyfish-dev/file-viewer-react-legacy) | React 16.8 / 17 |
| [file-viewer-jquery](https://github.com/flyfish-dev/file-viewer-jquery) | jQuery and traditional pages |
| [file-viewer-svelte](https://github.com/flyfish-dev/file-viewer-svelte) | Svelte |

## Specialized Engines

| Repository | Focus |
| --- | --- |
| [cad-viewer](https://github.com/flyfish-dev/cad-viewer) | Browser CAD viewer for DWG, DXF, DWF, DWFx and XPS |
| [dwf-viewer](https://github.com/flyfish-dev/dwf-viewer) | Pure frontend DWF/DWFx/XPS viewing with WebGL and WASM |
| [styled-exceljs](https://github.com/flyfish-dev/styled-exceljs) | Styled SheetJS-compatible Excel parser and renderer |
| [hucre](https://github.com/flyfish-dev/hucre) | Zero-dependency spreadsheet engine for XLSX, CSV and ODS |
| [word-ai](https://github.com/flyfish-dev/word-ai) | Structure-preserving DOCX editing bridge for AI agents |

## Demos And Supporting Projects

| Repository | Purpose |
| --- | --- |
| [office-preview-js](https://github.com/flyfish-dev/office-preview-js) | Static Office preview demo for DOC/DOCX/PPT/PPTX/XLS/XLSX |
| [pptviewer](https://github.com/flyfish-dev/pptviewer) | Classic `.ppt` preview artifacts |
| [product-web](https://github.com/flyfish-dev/product-web) | Product website source |
| [shop](https://github.com/flyfish-dev/shop) | Digital product and license delivery system |
| [rtsp](https://github.com/flyfish-dev/rtsp) | RTSP Chrome runtime and SDK release artifacts |

## Project Principles

- Browser first: prefer static deployment, local parsing, and private-file friendly workflows.
- Production oriented: focus on real business files, large documents, workers, WASM, lazy loading, and predictable integration APIs.
- Framework friendly: keep core capabilities framework-neutral, then provide native packages for mainstream ecosystems.
- Clear ownership: each repository documents its package name, build output, license, and integration path.

For File Viewer documentation, demos, and package selection, start from [file-viewer.app](https://file-viewer.app).
