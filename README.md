# rudupa.github.io — Engineering Tools Hub

The landing page for a collection of free, browser-based tools for embedded,
automotive, and real-time systems engineers. Served at
**https://rudupa.github.io/**.

This is a GitHub **user Pages** site: because the repository is named
`rudupa.github.io`, GitHub publishes it at the root of the domain. Each tool
lives in its own repository with its own project Page; this hub just links to them.

## Tools

| Tool | What it does | Live | Source |
|------|--------------|------|--------|
| **Time Synchronization Visualizer** | gPTP / IEEE 802.1AS & AUTOSAR STBM sync | [open](https://rudupa.github.io/EthTimeSync_Sim/) | [repo](https://github.com/rudupa/EthTimeSync_Sim) |
| **ChronoLens** | RTOS scheduling simulator (RM/EDF/FP/RR) | [open](https://rudupa.github.io/ChronoLens/) | [repo](https://github.com/rudupa/ChronoLens) |
| **ELF File Analyzer** | Inspect ELF headers, sections & segments | [open](https://rudupa.github.io/ElfFileAnalyzer/) | [repo](https://github.com/rudupa/ElfFileAnalyzer) |

## Adding a new tool

1. Create the tool in its own repo and enable GitHub Pages.
2. Add a `<a class="card">` block to `index.html` here, pointing at the new tool's
   Pages URL and source repo.

## Files

| File | Purpose |
|------|---------|
| `index.html` | Hub landing page with tool cards |
| `styles.css` | Dark theme |

## Author

**Ritesh Udupa** — [LinkedIn](https://www.linkedin.com/in/ritesh-udupa-4b694619/) · [GitHub](https://github.com/rudupa)

## License

MIT — see [LICENSE](LICENSE).
