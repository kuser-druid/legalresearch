# Legal Research Document Repository

This repository is a document store for Claude's Legal Research project — case law PDFs, treatises, and reference materials used in ongoing research and drafting.

**Start here: [`catalog.md`](./catalog.md)** — an index of every document with citation, folder location, one-line holding, and cross-references for cases that speak to more than one topic. The catalog exists so a case is never duplicated across folders: it is filed once, in its primary subject folder, with other relevant topics noted alongside it.

## Structure

- `HUF-Hindu-Succession/` — case law on Hindu Undivided Family / joint family law
  - `Formation-and-Status/` — whether/when an HUF exists, who its members are
  - `Blending-of-Property/` — throwing separate property into the joint family stock
  - `Coparcenary-and-Succession/` — daughters' coparcenary rights, HSA 2005 amendment, Karta-ship
  - `Partition-and-Taxation/` — partial partition, HUF as taxable unit
- `Criminal-Procedure/`
  - `Arrest-and-PMLA-Safeguards/` — Art. 21/22 safeguards on arrest, grounds-of-arrest requirements under PMLA/UAPA/CrPC-BNSS (Pankaj Bansal → Prabir Purkayastha → Vihaan Kumar → Mihir Rajesh Shah → Jaskaran Jeet Singh Deol line of cases, plus V. Senthil Balaji on habeas corpus against remand orders)
- `Interpretation/` — treatises and instruments on statutory/treaty construction (Maxwell, Vienna Convention on the Law of Treaties)
- `Reference/` — working materials (e.g. topic-wise case digest with citation abbreviations)

## Conventions

- Documents are retrieval-first: Claude looks things up here rather than deep-reading by default, and reads in full only when a task requires it.
- A document belongs to exactly one folder (its primary topic). If it's relevant to more than one, that's recorded in `catalog.md`, not by copying the file.
- When adding new material: file it in the right topic folder (create one if none fits), then add/update its row in `catalog.md`.
