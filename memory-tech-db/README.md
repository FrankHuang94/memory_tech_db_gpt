# Memory Technology and Semicap Database

This repository is a structured knowledge base on memory technology and the semiconductor capital-equipment ecosystem. The working objective is a database of more than 100,000 words, organized as standalone Markdown files so each topic can be updated without rewriting adjacent sections.

The database is written for readers who already understand semiconductor investing, supply chains, advanced packaging, and M&A. It does not try to be a beginner glossary. Each file is intended to capture the technical mechanism, the commercial consequence, the supply-chain bottleneck, and the evidence trail behind the claims.

## Repository Map

The main project lives under `memory-tech-db/`.

`INDEX.md` is the control table. It links every planned file, tracks the target word count, current draft status, current measured word count, and the total word count for the whole database.

`PROGRESS.md` is the working log. It records each completed file-level update, the subsection covered, the file word count, the running database total, and the next file to resume.

`SOURCES.md` is the master bibliography. It deduplicates sources across files and records URL, publish date, and the files where each source is used.

The numbered folders group the substantive research:

| Folder | Scope |
|---|---|
| `01-overview/` | Memory/storage fundamentals and market segmentation. |
| `02-history/` | DRAM, NAND, and packaging evolution. |
| `03-hbm-deep-dive/` | HBM architecture, generations, vendor roadmaps, IP, and customer ecosystems. |
| `04-hbf-emerging-tech/` | High-bandwidth flash and its position between HBM, NAND, and CXL. |
| `05-other-emerging-memory/` | CXL pooling, MRAM, ReRAM, PCM, computational storage, and Optane lessons. |
| `06-competitive-landscape/` | Vendor profiles and share tracking. |
| `07-semicap-ecosystem/` | Equipment, OSAT, substrates, testing, materials, and EDA. |
| `08-manufacturing-process/` | DRAM, NAND, and HBM manufacturing flows. |
| `09-research-frontier/` | Academic, industry, bonding, power, and thermal research. |
| `10-macro-drivers/` | AI datacenter demand, supply cycles, geopolitics, and export controls. |

## Writing Rules

Each substantive topic gets its own Markdown file. Avoid copying background passages from one file into another; cross-link instead. For example, a later HBM vendor-roadmap file should link back to the fundamentals chapter for the 1T1C DRAM explanation rather than restating the same cell-structure material.

Every factual claim involving a date, technical specification, capacity figure, market share, investment amount, price movement, or named product should carry an inline footnote. The footnote should include source title, publisher, publish date, and URL. When figures conflict, record the range and cite both sources rather than silently picking one.

Every technical file should include at least one Mermaid diagram. Manufacturing-process files should use step-by-step annotated Mermaid flows. Vendor profiles should include official image links and official video links when available.

## Research Method

Use recent sources first for live market facts. Supplier roadmaps, fab investments, product transfer rates, market share, pricing, and shortage timelines can change quickly, so dated sources from 2025-2026 should usually override older summaries unless the older source is being used for historical context. When a claim depends on a company announcement, prefer the company newsroom, annual report, investor presentation, JEDEC standard announcement, regulator filing, or reputable trade publication. When only a secondary source is available, make the source class clear in the wording.

For historical sections, older sources are acceptable when they establish release dates, standard publication dates, or generation chronology. The file should still separate settled history from current implications. A DDR2 release date and a 2026 DDR4 shortage claim are different types of evidence and should not be sourced with the same looseness.

When using estimates from market-research firms through media coverage, preserve the attribution. Do not convert a Counterpoint, Gartner, TrendForce, Omdia, SIA, WSTS, or company-management estimate into an unattributed fact. If two firms use different category definitions, record the difference.

## Count Discipline

Word-count targets are floors, not ceilings. The goal is dense, sourced specificity: named fabs, named process nodes, product generations, investment figures, ramp dates, customer dependencies, and competing estimates. Generic filler should be removed even if it makes a file shorter; the correct fix for a thin file is more primary detail, not looser prose.

After every file-level update, run a word-count check and update both `INDEX.md` and `PROGRESS.md`. `SOURCES.md` should be updated in the same edit whenever a new source enters the database.

## Quality Bar

A useful file should answer four questions. What changed technically? Which companies, fabs, standards, products, or customers made the change commercially relevant? What bottleneck does the change create or relieve? What evidence supports the numbers and timeline?

The best entries should be usable by an investor, strategist, corp-dev reader, or semiconductor operator who needs to compare memory technologies quickly. Tables are encouraged where they compress facts without flattening nuance. Mermaid diagrams are encouraged where process flow, hierarchy, package structure, or timing matters. A file can be long, but it should never make the reader hunt through generic prose for the actual claim.

## Current Status

The current checkpoint is recorded in `INDEX.md` and `PROGRESS.md`. Continue from the `Next file to begin` line in `PROGRESS.md`, unless a quality issue in an already drafted file needs immediate correction.
