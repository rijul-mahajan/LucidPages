# Changelog

All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](https://semver.org/).

---

## [1.7.0]

### Added
- **Summary History**: Access and revisit previously generated summaries anytime.  
- **Multi-Language Support**: Generate summaries in multiple languages for global accessibility.  
- **Listen to Summaries (Text-to-Speech)**: Convert summaries to speech for hands-free reading.  

### Changed
- **UI Enhancements**: Modernized interface with refined icons, improved animations, and better responsiveness.  

### Fixed
- Minor bug fixes and improvements.  

---

## [1.6.1]

### Fixed

* Minor bug fixes and improvements.

---

## [1.6.0]

### Added

* **Quick Access Icon**: A floating, draggable icon for faster summarization. Its position is saved for convenience.
* **Highlight-to-Summarize**: A tooltip appears when you select text, allowing for instant summaries of specific sections.
* **Context Menu Integration**: Right-click on any selected text to summarize it directly from the context menu.
* **PDF Summarization**: Support for summarizing web-based PDF documents using PDF.js.
* **New Settings Toggles**: Dedicated toggles on the settings page to enable or disable the floating icon and selection tooltip.

### Security

* Configured backend with bot protection on Vercel.

### Fixed

* Minor bug fixes and improvements.

---

## [1.5.1]

### Fixed

* Minor bug fixes and improvements.

---

## [1.5.0]

### Added

* Redesigned AI chat feature, moved to a separate **overlay** for better accessibility and readability.
* Added a button to access the chat overlay.

### Fixed

* Minor bug fixes and improvements.

---

## [1.4.1]

### Fixed

* Minor bug fixes and improvements.

---

## [1.4.0]

### Added

* **Advanced AI Chat Context**: The AI chat is now fully context-aware. It uses the page summary, the full page content, and the recent conversation history to provide highly accurate and relevant answers.

### Fixed

* Minor bug fixes and improvements.

---

## [1.3.0]

### Added

* AI chat feature inside the summary container with an expandable toggle.
* Powered by Gemini model for Q&A about summaries, topics, or general content.

### Fixed

* Minor bug fixes and improvements.

---

## [1.2.0]

### Changed

* Migrated extension from **popup** to **Chrome Side Panel** for better readability and accessibility.
* Major UI/UX and layout redesign.

### Added

* **Fullscreen (Reading Mode)**: Expand button to view summaries in a distraction-free fullscreen mode.
* **Rich Summary Formatting**: Summaries are rendered with full Markdown support, including rich formatting for code blocks with language detection and a one-click copy button.
* **Keyboard Shortcuts**: Implemented shortcuts for power users, including `Ctrl/Cmd + S` to summarize and `Escape` to close overlays.

### Fixed

* Minor bug fixes and improvements.

---

## [1.1.0]

### Added

* **Complete UI/UX redesign** with a modern theme, colors, animations, and layouts.
* Settings page for customizing summary preferences:

  * Summary length
  * Summary type
  * Language complexity
* Ability to copy summaries to clipboard.
* Theme toggling.
* Backend (Gemini API) hosted on Vercel as a serverless function.

---

## [Other Enhancements]

These features were introduced progressively across multiple versions:

* **Notifications** for successful actions, errors, and information.
* **Intelligent Summary Caching**: Session-based caching with unique keys generated from page content + summary settings, ensuring instant delivery of cached summaries while automatically fetching new ones when content or settings change.
* **Smart Content Detection** powered by Mozilla Readability.
* **Local-only chat history** with *Clear History* option.
* **Automatic theme detection** and settings sync across extension pages.
* **Backend enhancements**:

  * CORS configuration to restrict allowed origins.
  * Quota tracking with retry logic and enhanced error handling.
  * IP blocking, malicious behavior detection, and stricter rate limiting.
  * New summary language complexity option: **ELI5**.
  * Admin authentication and backup API key failover logic.
* **Security improvements**:

  * Minimal browser permissions requested.
  * All API requests encrypted with HTTPS.
* **Broader browser support** (Chrome, Edge, Brave, Opera).
* General performance improvements, security enhancements, and UI/UX refinements in every release.
