# The RFC Journal

A newspaper-style archive of Internet protocol standards, inspired by the design principles of The Wall Street Journal.

**Live Site:** [jermainebethune.github.io/rfc-journal](https://jermainebethune.github.io/rfc-journal/)

## Purpose

The RFC Journal provides a clean, readable interface for exploring the foundational standards documents that power the Internet. Rather than the utilitarian presentation of traditional RFC archives, this site applies classic newspaper design principles to make technical standards more approachable:

- **Curated Protocol Collections** — RFCs organized by protocol family (UDP, QUIC) rather than raw chronological listing
- **Editorial Hierarchy** — Clear visual structure distinguishes between protocols, document metadata, and content
- **Typography-First Design** — Serif headlines, readable body text, and proper typographic scale

## Design

Built with [Astro](https://astro.build) for zero-JavaScript static output. The design system draws from WSJ's editorial style:

| Element | Implementation |
|---------|----------------|
| Headlines | Playfair Display (serif) |
| Body Text | Source Serif 4 |
| UI/Labels | Source Sans 3 |
| Colors | Black on cream (#FBF8F3), WSJ blue (#0274B6) accents |
| Layout | Multi-column grid with traditional newspaper rules |

## Protocols Covered

- **UDP** — User Datagram Protocol (12 RFCs, 1980–2022)
- **QUIC** — Modern encrypted transport (12 RFCs, 2021–2023)

## Development

```bash
npm install
npm run dev      # Start dev server at localhost:4321
npm run build    # Build static site to ./dist
```

## License

Content derived from IETF RFC documents, which are public standards.
