## Zaid Alhawamdeh

I build software on my own, and I try hard to break it before I trust it.

### Security research

Watson at [Sherlock](https://audits.sherlock.xyz). I read production Solidity and report
only what I can demonstrate. The method is refute-first: a finding is worth submitting
after I have failed to disprove it, not when it first looks plausible.

### Experience

Most of my work has been for companies, and it carries their name rather than mine —
production web systems across legal, real estate, rentals, maintenance, retail, travel and
education. I don't list clients; that is theirs to publish, not mine. What carried over is
the habit rather than the portfolio: ship the thing, then go looking for the reason it is
wrong.

### Products

| | |
|---|---|
| **[Ideon](https://ideonhq.com)** | Document an idea and get a timestamped record anyone can verify — including against us |
| **[Wakeel](https://wakeelhq.com)** | A sales agent a merchant trains in their own words, in their own dialect |
| **[al-Munqidh](https://almunqidh.com)** | Business health assessment for early-stage companies |
| **[SEALEDScan](https://sealedscan.com)** | A scanner. Deliberately neutral, deliberately free |

### Systems

**[WakeChain](https://wakechain.org)** — a proof-of-work chain written from scratch:
consensus, node, miner, browser wallet, and a light client that recomputes every block
header back to a pinned genesis **inside the visitor's browser**. No company operates it,
and checking it requires trusting no one — [see for yourself](https://wakechain.org/verify).

**LLM Memory OS** — an enforcement layer that wraps a language model instead of trusting
it. A fact is returned verbatim from memory, or the system abstains; the model is never
asked to produce one. Its only job is a yes/no judgement — *does this stored item answer
the question* — so it is a judge, never an author. The guarantee therefore does not rest
on the model behaving well: wrap one that says yes to everything and it still cannot invent
a phone number that was never stored, because there is no path from the model to the
answer. Memory persists to disk, every factual answer carries the source it came from, and
an unreachable model means abstain rather than guess.

### How I work

I work with AI models the way other people work with a team, and I say so out loud —
commits carry `Co-Authored-By` where they should. Who typed a line was never the
interesting part. Whether it survives someone trying to break it always is.

That is most of what I do: build the thing, then go looking for the reason it is wrong. A
surprising amount of software reports success while quietly doing nothing.
