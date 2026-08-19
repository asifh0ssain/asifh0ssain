# Asif Hossain

I build systems that make decisions with money on the line — lead generation, marketing attribution, and quantitative research — and I spend most of my effort on the part that decides whether their output can be trusted.

---

### What I work on

**Attribution and revenue systems** — multi-touch attribution over messy real-world funnels, with the identity resolution and consent handling that has to sit underneath it. Flask, SQLAlchemy, PostgreSQL, argon2, TOTP.

**Outbound and lead generation** — enrichment pipelines, signal extraction, deliverability, and suppression handling. The interesting problem is not sourcing contacts; it is knowing which claims about a prospect are actually supported by evidence.

**Quantitative research** — options strategy backtesting: point-in-time data, transaction-cost and fill modelling, survivorship-free universes, and a risk fence that refuses trades rather than reporting them optimistically.

---

### How I work

Three habits that show up in every repository I own:

**Register the hypothesis before running the test.** A strategy designed after seeing results is not a strategy, it is a search. My backtesting work commits a written pre-registration — universe, entry rule, exit rule, success criterion — before the out-of-sample run, so the result can only confirm or falsify, never be reshaped to fit.

**Publish the nulls.** Most tested ideas fail. In one case a promising calendar spread survived the entire search and then died on a data-source check — it was an artifact, worth exactly nothing. That gets written down with the same care as a success. A research log with no failures in it is a marketing document.

**Audit the grader, not just the output.** An LLM scoring pipeline of mine returned 100/100 on copy containing a fabricated product name and a misattributed source. The generator was wrong; the validator being confidently wrong was the real defect. Systems that evaluate themselves need adversarial checks, or they will tell you what you want to hear.

The same instinct runs through the code: a strategy engine with **738 tests and zero runtime dependencies**, a do-not-contact and consent ledger kept under version control because it is the state with legal weight, and cost and slippage assumptions written down as explicit gates rather than buried constants.

---

### Stack

`Python` · `Flask` · `SQLAlchemy` · `PostgreSQL` · `SQLite` · `pytest` · `React` · `JavaScript` · `PHP` · `WordPress`

---

### A note on this profile

Most of what I build is client work or proprietary research, so it lives in private repositories — the public surface here is deliberately thin. I intend to open-source the general-purpose pieces as they stabilise: the risk fence, the pre-registration harness, and the factuality-audit tooling are the strongest candidates.

If you want to talk about any of the above, or need detail on work that isn't public, reach out.

---

📫 **asif@obitodigital.com**
