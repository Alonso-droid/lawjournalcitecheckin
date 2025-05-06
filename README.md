# Law Review Cite-Checker

A web-based application for law review editors to streamline the citation checking process by automating Bluebook verification and providing integrated legal research functionality.

## Features

- **Split-panel Interface**: View document and sources side-by-side to minimize screen switching
- **Document Processing**: Upload and parse Word documents (.doc, .docx) with automatic footnote detection
- **Citation Analysis**: 
  - Automatically identify different citation types (cases, statutes, journals, books, websites)
  - Split footnotes into sub-citations (5A, 5B, 5C format)
  - Check against Bluebook rules with detailed error reports
- **Legal Research Integration**:
  - Web search functionality for citation verification
  - Direct links to major legal resources (CourtListener, Google Scholar, Cornell LII)
  - Integration with Harvard Library and other legal databases
- **Verification Workflow**:
  - Track verification status (Verified, Has Issues, Unverified)
  - Add and save verification notes
  - Mark citations as completely verified
- **Export Options**:
  - Generate comprehensive citation check reports
  - Export verification notes as PDF
  - Share results with team members

## Getting Started

### Online Version
The easiest way to use the Law Review Cite-Checker is through the live version:
https://[your-github-username].github.io/law-review-cite-checker

### Local Installation
To run the application locally:

1. Clone this repository git clone https://github.com/[your-github-username]/lawjournalcitecheckin.git

2. 2. Open `index.html` in your web browser
3. Upload a Word document with footnotes to begin

No server or installation required - runs entirely in your browser!

## Usage Guide

1. **Upload a Document**: Click "Choose File" and then "Upload Document"
2. **Review Footnotes**: The system will automatically extract and display footnotes
3. **Verify Citations**: 
- Click "Verify Citations" to automatically check Bluebook formatting
- Select individual footnotes or sub-footnotes to examine
- Use the search functionality to find original sources online
4. **Add Notes**: Document verification status with the built-in note-taking feature
5. **Export**: Generate reports or PDFs of your verification work

## API Integration (Optional)

For enhanced functionality, you can configure API keys for:
- CourtListener (case law research)
- Harvard Library (journal articles)

These can be configured in the Settings panel and are stored locally in your browser.

## Privacy & Security

- All document processing happens in your browser - no content is uploaded to external servers
- Verification data is stored locally in your browser
- No tracking or analytics

## Technology

Built with pure HTML, CSS, and JavaScript. Uses the following libraries:
- [Mammoth.js](https://github.com/mwilliamson/mammoth.js) for Word document processing
- [jsPDF](https://github.com/parallax/jsPDF) for PDF generation
- [html2canvas](https://github.com/niklasvh/html2canvas) for HTML rendering

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Created for law review editors to enhance citation checking efficiency
- Inspired by the challenges of traditional, manual cite-checking processes 
