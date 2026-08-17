## Zaid Mustafa Alhawamdeh

I build software on my own, and I try hard to break it before I trust it.

### Security research

Watson at [Sherlock](https://audits.sherlock.xyz). I read production Solidity and report
only what I can demonstrate. The method is refute-first: a finding is worth submitting
after I have failed to disprove it, not when it first looks plausible.

### Experience

Since 2024 I have delivered working systems to **105+ clients** — most of that one platform
hardened until it could be replicated and adapted per company, alongside web systems across
several sectors.

The work carries their names rather than mine, and I keep it that way. I'm one person, not
an agency, and a client list is theirs to publish, not mine — putting those names on my own
page would be borrowing something I wasn't given. I'm glad to walk through any of it
privately with anyone who wants to see it.

What carried over is the habit rather than the portfolio: ship the thing, then go looking
for the reason it is wrong.

### Products

| | |
|---|---|
| **[Ideon](https://ideonhq.com)** | Document an idea and get a timestamped record anyone can verify — including against us |
| **[Wakeel](https://wakeelhq.com)** | A sales agent a merchant trains in their own words, in their own dialect |
| **[al-Munqidh](https://almunqidh.com)** | Business health assessment for early-stage companies |
| **[SEALEDScan](https://sealedscan.com)** | A scanner. Deliberately neutral, deliberately free |
| **[FeedParity](https://www.getfeedparity.com)** | Independent verification that Google Merchant Center sees the same catalogue Shopify does — read-only, changes nothing |

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

### Also

**[AFAQ PLUS International](https://afaqplusgroup.com)** — a business group I run in the UAE:
real estate, car rental, education advisory, and trade. Five companies. Not software — it is
where the software has to survive a payroll.

### How I work

I work with AI models the way other people work with a team, and I say so out loud —
commits carry `Co-Authored-By` where they should. Who typed a line was never the
interesting part. Whether it survives someone trying to break it always is.

That is most of what I do: build the thing, then go looking for the reason it is wrong. A
surprising amount of software reports success while quietly doing nothing.
