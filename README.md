# Contractor Sign Builder

Polished, print-ready contractor hazard sign generator — a small, self-contained HTML app for creating entrance signage for contractor work areas.

## Quick summary

Open `index.html` in any modern browser to launch the sign builder. The app runs entirely in the browser (no backend) and produces a print-friendly A4 sign you can save as PDF or print directly.

## Features

- Single-file static app (HTML with embedded CSS/JS and image data URIs)
- Form-driven input for project details, contacts, hazards, PPE and emergency information
- Live print preview and print/PDF export
- Print-optimised layout (A4, colour-aware print styles)
- Accessible markup and simple keyboard support

## Usage

1. Clone or download the repository and open `index.html` in your web browser.
2. Fill in the required fields (marked with *).
3. Review the live print preview on the right-hand panel.
4. Use the "Print / Save PDF" button to create a printable PDF or print to a physical printer.

Notes for printing:
- Use a colour printer for the best visual match to the preview.
- The print CSS targets A4 portrait by default and includes adjustments for high-fidelity printing (print-color-adjust).

## Customisation

- The UI, layout and symbols are embedded in `index.html` — edit the HTML/CSS directly to adjust styles, fonts or wording.
- Images are embedded as data URIs; replace or remove as needed.

## Development & maintenance notes

- Single-file approach keeps deployment trivial but makes incremental edits more error-prone; consider splitting CSS/JS into separate files for larger changes.
- Keep an eye on accessibility (contrast, alt text) when changing symbols or colours.

## Suggested repo description (one-line)
"Contractor Sign Builder — browser-based, print-ready contractor hazard sign generator (single-file HTML)."

## About (short)
A minimal, offline-friendly tool to create clear contractor entrance signs that conform to internal safety communication needs.

## Contributing
Contributions are welcome. Open an issue or submit a PR with small, focused changes.

## License
Add a LICENSE file or state the license here (recommend: MIT for public use).
