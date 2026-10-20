### nuncaeslupus

I build tools that make LLM agents do careful, measurable work, and the small utilities I need along the way.

**MCP** = ships an MCP server. **Skill** = ships a Claude Code skill or plugin.

#### Tools for AI agents

| Project | What it is | Agent interface |
|---|---|---|
| [**drawspec**](https://github.com/nuncaeslupus/drawspec) | Declarative diagram spec to clean, themeable SVG. JSON with no coordinates, so an LLM can write it. | MCP, Skill |
| [**doc-control**](https://github.com/nuncaeslupus/doc-control) | Deterministic tool for AI agents to edit Word documents. Every change is a tracked change the writer can reject. | MCP |
| [**comparador-luz-gas**](https://github.com/nuncaeslupus/comparador-luz-gas) | Queries the CNMC energy-offer comparator (Spain) and returns JSON ready for an LLM. | MCP |
| [**research-buddy**](https://github.com/nuncaeslupus/research-buddy) | Structured AI research collaborator: versioned Markdown research documents built into a single-file HTML site. | |

#### Claude Code workflow

| Project | What it is | Agent interface |
|---|---|---|
| [**claude-arsenal**](https://github.com/nuncaeslupus/claude-arsenal) | Claude Code plugin marketplace: specs before code, failing tests first, acceptance gates with numbers, a gated task queue. | Skill |
| [**integral-job-search**](https://github.com/nuncaeslupus/integral-job-search) | Candidate-centred job search run as a conversation in Claude Code. One dimension model from what you need to the interview. | Skill |
| [**integral-connectors**](https://github.com/nuncaeslupus/integral-connectors) | Job-board connectors for integral-job-search: four data files per board, no code. | |
| [**literary-critic**](https://github.com/nuncaeslupus/literary-critic) | Lets an LLM index, analyse and advise on a whole novel manuscript like a professional editor, across drafts. | Skill |

#### Utilities

| Project | What it is |
|---|---|
| [**ai-chat-exporter**](https://github.com/nuncaeslupus/ai-chat-exporter) | Browser extension that exports ChatGPT, Claude and Gemini conversations to PDF, Markdown, DOCX and more. |
| [**image-to-svg**](https://github.com/nuncaeslupus/image-to-svg) | Raster-to-SVG converter that runs in the browser. Nothing is uploaded. |
| [**farma-kit**](https://github.com/nuncaeslupus/farma-kit) | Fills in the header of Spanish pharmacy prescription coupon sheets, in the browser. |
| [**numerador-facturas**](https://github.com/nuncaeslupus/numerador-facturas) | Numbers PDF invoices in batch, in the browser. Nothing is uploaded. |
| [**pdf-password-breaker**](https://github.com/nuncaeslupus/pdf-password-breaker) | Recovers the password of your own PDF by trying candidates you define, in the browser. |
| [**html-cleaner**](https://github.com/nuncaeslupus/html-cleaner) | Bookmarklet that removes clutter from a page using per-site rules. |
| [**model-generator**](https://github.com/nuncaeslupus/model-generator) | One-shot generator: JSON spec to FastAPI backend with models, routes, migrations and tests. |
| [**completescraper**](https://github.com/nuncaeslupus/completescraper) | A complete and easy to use web scraping library for Python. |

Most of these are built with claude-arsenal's spec-driven workflow and gated task queue.
