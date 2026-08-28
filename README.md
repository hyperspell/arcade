# Hyperspell Arcade

Small games about big infrastructure, by the [Hyperspell](https://hyperspell.com) team.

**▶ Play: https://hyperspell.github.io/arcade/**

| Game | What it is |
|------|------------|
| [**Six-Second Shift**](https://hyperspell.github.io/arcade/six-second-shift/) | A frantic crew-of-one console game over real production knobs: orders arrive under a countdown, and the waves replay a real five-month incident in which five reasonable engineering decisions quietly starved an LLM summarization pipeline — ending with the real paired-config fix (fallbacks −98%). When an order names a knob that's hardcoded, no amount of hunting will find it: slam 🔩 IT'S HARDCODED. |
| [**Ingestion Inspector**](https://hyperspell.github.io/arcade/ingestion-inspector/) | Checkpoint bureaucracy at the Ministry of Ingestion. You play the LLM content classifier guarding what enters a company's memory: stamp documents against the filters, survive the fail-open jump scare, run the two-key dry-run → apply sequence, and answer to the coworker whose charity fun run you soft-deleted. Comes with a [recruitment poster](https://hyperspell.github.io/arcade/ingestion-inspector/poster.html). |
| [**The Sharing Machine**](https://hyperspell.github.io/arcade/sharing-machine/) | A Factorio-flavored factory about the opposite problem: what a company's memory shares back out. Place an inclusion gate on the belt (there is no slot upstream of ingestion), watch an enforcing drop filter beat your share rule — and a disarmed one protect nothing — then fix a wrong drop the only way that works: refine the filter. Ends by calibrating a scored gate with an ask-a-human band and teaching it until it goes quiet. |

## Honesty clause

The incidents, knobs, dates, spec rules, and percentages in these games are real. The dollar
amounts and traffic volumes have been replaced with deliberately outrageous ones. All documents
in Ingestion Inspector and The Sharing Machine are fiction.

## Tech

Each game is one self-contained HTML file — no build, no dependencies, no network calls.
