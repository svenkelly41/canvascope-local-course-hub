# Canvascope v10.1.0 - Chrome extension 2026

> **Canvascope v10.1.0 is a Chrome extension built for Canvas and Brightspace. It constructs local-first course indexes, makes course search faster, and supports planner and PDF workflows.**

[![Platform](https://img.shields.io/badge/Platform-Chrome-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v10.1.0-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/svenkelly41/canvascope-local-course-hub?style=flat-square)](https://github.com/svenkelly41/canvascope-local-course-hub)

---

<p align="center">
  <a href="https://svenkelly41.github.io/canvascope-local-course-hub/">
    <img src="https://img.shields.io/badge/Download-Canvascope%20Latest-brightgreen?style=for-the-badge" alt="Download Canvascope">
  </a>
</p>

> **[Direct Download - Canvascope v10.1.0](https://svenkelly41.github.io/canvascope-local-course-hub/)**

---

[Download Latest Build](https://svenkelly41.github.io/canvascope-local-course-hub/)

---

## About Canvascope

Canvascope targets students and course-centric workflows inside Canvas and Brightspace. Its core idea is a local-first index of course content, which means browsing and searching materials does not require a remote search service to answer every lookup.

That approach pays off when you need fast access to course documents, a planner-style task flow, and solid handling of PDF-heavy material. Offline PDF text extraction, OCR for scanned files, and a hybrid local AI RAG assistant are all bundled together, so several study tools live inside a single browser extension.

---

## Features

- Course content indexed locally first
- Search that stays scoped to the course you are in
- Planner tools for organizing academic work and tracking tasks
- PDF text extraction that works offline
- OCR-powered search for scanned PDFs
- Hybrid local AI RAG assistant offering in-context help
- Lectra PDF handoff with realtime synchronization
- Runs in Chrome against Canvas and Brightspace

---

## Installation

1. Grab the newest build from the project page.
2. Add the Chrome extension using the packaged release in this repository or the extension loading workflow.
3. Load Canvas or Brightspace in Chrome and let the extension set up its local index.

For a manual setup, clone or download the repository contents first, then point Chrome's extension management page at the unpacked folder.

---

## Usage

Once installed, open a course on a supported LMS and allow Canvascope to assemble the local course index.

A typical session looks like this:
1. Open a Canvas or Brightspace course.
2. Let the extension work through the available course content.
3. Search within the course to locate pages, documents, or extracted PDF text.
4. Switch to the planner tools to organize your academic work.
5. Reach for OCR or the local RAG assistant whenever course files need deeper text handling.

---

## Configuration

Canvascope relies on local course indexing plus browser-side settings for its workflow. Whatever options exist are generally handled through the extension interface and kept locally in the browser environment.

Example settings layout:

    {
      "course_indexing": "local-first",
      "search_scope": "current-course",
      "pdf_text_extraction": true,
      "ocr_search": true,
      "rag_assistant": "hybrid-local",
      "planner": true
    }

---

## Requirements

- Google Chrome
- An account or access to Canvas or Brightspace
- Sufficient local browser storage for course indexes and extracted content
- Permission to run the extension on the LMS pages you visit

---

## FAQ

**How do I get updates?**  
Visit the project download page to find the newest build and version.

**Where are my settings stored?**  
Unless the extension workflow says otherwise, configuration stays local in the browser.

**What if search results are incomplete?**  
Let indexing of the current course finish, then refresh the course view and search again.

**Does it work with PDF files?**  
Yes. Offline PDF text extraction is included, along with OCR search for scanned PDFs.

**How do I troubleshoot first launch issues?**  
Check that Chrome permissions are granted, confirm the extension is loaded, and reopen the supported LMS course so indexing can start.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
