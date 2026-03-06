# Prepress Tools Hub

A Bootstrap 5 landing page providing quick access to internal prepress tools hosted on `tjintranet.github.io`, with direct links to the Switch and PACE MIS systems.

## Features

- **Two-section layout** — tools organised into Production and Development categories
- **Favourites** — bookmark any tool with the star icon; state persisted in `localStorage`
- **Favourites filter** — funnel toggle in the header to show only bookmarked tools
- **Dark/light mode** — theme toggle persisted across sessions via `localStorage`
- **Responsive grid** — 4 columns on large screens, 2 on medium, 1 on small

## Tool Sections

### Production Tools
| Tool | Description |
|------|-------------|
| PACE Metadata to XML for DBS | Converts PACE metadata Excel files to DBS XML format |
| DBS Datamatrix Barcodes | Generates DBS Datamatrix barcodes |
| Book Weight Calculator | Calculates book weights for POD |
| Spine Size Calculator | Calculates book spine sizes |
| Micron to Volume Converter | Converts paper micron values to volume |
| QR Code Generator | Creates EUDR-compliant QR codes |
| PDF Dummy Pages | Generates PDF dummy pages for testing impositions |

### Development Tools
| Tool | Description |
|------|-------------|
| XML Parser | Parses and inspects XML files |
| JDF Parser | Parses JDF/JT job definition files |
| Enhanced XML Reader | Read, search and export XML content |
| XSLT Transformer | Transforms XML/JDF documents via XSLT |

## Header Links

- **Switch** — links to the internal Switch job submission interface (`192.168.10.233:51089`)
- **PACE** — links to the ePace MIS login (`192.168.10.251`)

## Dependencies

- [Bootstrap 5.3.2](https://getbootstrap.com/)
- [Bootstrap Icons 1.11.3](https://icons.getbootstrap.com/)
- [Google Fonts — Roboto](https://fonts.google.com/specimen/Roboto)
