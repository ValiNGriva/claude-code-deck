# Claude Code: the agent that acts

A 30-slide teaching deck for SCTP professionals on a learning journey with Claude Code.

**The one idea:** a chatbot tells you what to do; an agent does it. Everything else follows
from that — the four-line brief, the permission dial, and the checking you owe it.

## ▶ Open the deck

**Use the published link, not the GitHub file view:**

```
https://valingriva.github.io/claude-code-deck/
```

For a specific slide, add the number to the **direct file** link:

```
https://valingriva.github.io/claude-code-deck/claude-code.html#12
```

> **On github.com you will see source code, not slides.**
> Clicking `index.html` in this repo shows the raw HTML markup, which is expected — GitHub is
> a code host, not a web host. Use the `.github.io` link above to see the deck itself.

### Other ways to open it

| Way | What you get |
|---|---|
| **`valingriva.github.io/claude-code-deck/`** | ✅ the deck, rendered — use this |
| `…/claude-code.html#12` | ✅ jumps straight to slide 12 |
| `…/claude-code-deck/#12` | ❌ falls back to slide 1 — the redirect drops the `#` |
| Download the file, open in Chrome | ✅ works offline, no server needed |
| `github.com/…/blob/main/claude-code.html` | ❌ raw HTML source |

> `index.html` is only a redirect to `claude-code.html`. Browsers discard the URL fragment
> (`#12`) when following it, so **deep links must use the `claude-code.html` address**, not
> the bare folder.

The file is self-contained: fonts are embedded, nothing is fetched at runtime, so a
downloaded copy renders identically with no network.

## Navigation

| Key | Action |
|---|---|
| `→` `←` `space` | next / previous slide |
| `Home` `End` | first / last slide |
| `F` | fullscreen |
| click left/right half | advance / go back |
| swipe | advance / go back (touch) |

## Print to PDF

`File → Print → Save as PDF`, margins **None**, background graphics **on**.
One slide per page at 1440×810 — 30 pages.

## Structure

| Part | Slides | |
|---|---|---|
| Opening | 1–7 | three gut calls, then what they showed |
| Block 1 | 8–13 | what an agent is |
| Block 2 | 14–19 | how you hand over a task |
| Block 3 | 20–26 | permissions and the trust dial |
| Close | 27–30 | three things, exit poll |

Runs about 40 minutes with the three activities (slides 12, 17, 24) at 4–5 minutes each.

## Files

| File | |
|---|---|
| `claude-code.html` | **the deck** — the only copy of the content |
| `index.html` | 1 KB redirect so the bare folder URL lands on the deck |

Edit `claude-code.html` only. There is no second copy to keep in sync.

## A note on what this deck does and doesn't claim

The permission levels are described by **behaviour** ("ask every time", "plan only", "edits
without asking", "full access"), not by product menu names, because those change between
releases and this deck could not verify them against live documentation. Teach the behaviour,
and check the current names before delivery.