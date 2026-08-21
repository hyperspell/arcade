# Hyperspell Arcade

Small games about big infrastructure, by the [Hyperspell](https://hyperspell.com) team.

**▶ Play: https://hyperspell.github.io/arcade/**

| Game | What it is |
|------|------------|
| [**Bedrock Spaceteam**](https://hyperspell.github.io/arcade/bedrock-spaceteam/) | Single-player Spaceteam over real production knobs. The waves replay a real five-month incident in which five reasonable engineering decisions quietly starved an LLM summarization pipeline — ending with the real paired-config fix (fallbacks −98%). When an order names a knob that's hardcoded, no amount of hunting will find it: slam 🔩 IT'S HARDCODED. |
| [**Ingestion Inspector**](https://hyperspell.github.io/arcade/ingestion-inspector/) | Papers, Please at the Ministry of Ingestion. You play the LLM content classifier guarding what enters a company's memory: stamp documents against the filters, survive the fail-open jump scare, run the two-key dry-run → apply sequence, and answer to the coworker whose charity fun run you soft-deleted. Comes with a [recruitment poster](https://hyperspell.github.io/arcade/ingestion-inspector/poster.html). |

## Honesty clause

The incidents, knobs, dates, spec rules, and percentages in these games are real. The dollar
amounts and traffic volumes have been replaced with deliberately outrageous ones. All documents
in Ingestion Inspector are fiction.

## Tech

Each game is one self-contained HTML file — no build, no dependencies, no network calls.
Written with [Claude](https://claude.com/claude-code).
