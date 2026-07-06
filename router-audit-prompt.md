[router-audit-prompt.md](https://github.com/user-attachments/files/29713629/router-audit-prompt.md)
# The ROUTER Audit — Send This to Anyone Who Comments "ROUTER"

**What this is:** A prompt they paste into a NEW Claude chat (claude.ai, with "Search and reference past chats" turned on in Settings). Claude will pull their own conversation history and tell them, with receipts, whether they've been defaulting to the most expensive model out of habit instead of need.

**How to send it:** Drop the block below in a DM or pinned reply. Tell them: "Paste this into a fresh Claude chat. Takes 2 minutes, no signup, no cost."

---

## The Prompt (copy everything between the lines)

```
I want you to audit my own Claude usage and tell me if I've been
over-paying for AI power I didn't need — or under-using it where
I actually needed more.

Do this:

1. Search my past conversations from the last 30 days (use both
   recent_chats and conversation_search — don't rely on just one).
   Pull a representative sample across different topics, not just
   the most recent handful.

2. For each conversation, classify the TASK, not the topic:
   - QUICK LOOKUP: factual questions, simple rewrites, formatting,
     short summaries — a capable mid-tier model handles this fine.
   - ROUTINE PRODUCTION: drafting emails/posts/code snippets,
     everyday analysis, first-pass writing — mid-tier model, maybe
     with a second pass.
   - COMPLEX REASONING: multi-step analysis, long documents, real
     ambiguity, high stakes if wrong, work that gets reused or
     shipped — this is where a frontier-tier model earns its cost.
   - LONG-HORIZON / AGENTIC: multi-day projects, large codebases,
     autonomous multi-step work with real consequences if it goes
     sideways — frontier tier, no debate.

3. For each one, give me a one-line verdict: RIGHT-SIZED,
   OVER-SPENT (used more model than the task needed), or
   UNDER-POWERED (task needed more capability/context than it got,
   risking a worse answer).

4. Tally it up. Tell me honestly, in percentage terms, how much of
   my recent usage fell into each bucket.

5. Give me ONE plain-language rule I can actually follow going
   forward — not a flowchart, one sentence I'll remember mid-task.
   Something like: "If getting it wrong costs me more than the
   price difference, pay for the smarter model. If it doesn't,
   don't."

6. Flag anything that looks like a genuine blind spot — a category
   of task I keep running on the wrong tier without noticing.

Be direct. I'm not looking for reassurance, I'm looking for the
actual pattern. If the honest answer is "you've been fine the whole
time," say that too — don't manufacture a problem to seem useful.
```

---

## Why this works as a WRM asset
- It's genuinely useful on its own — no bait-and-switch, no "and now buy our course."
- It positions WRM as the team that thinks about AI spend like a P&L line, not a toy — matches the "exit strategist with a playbook" positioning.
- It's self-fulfilling proof of the video's Hill Beat: the prompt itself IS a router — it makes Claude do the judgment call Zach just talked about on camera.
- Zero cost to give away, scales infinitely, and every person who runs it either validates your point (over-spending) or gives you a testimonial-shaped DM either way.

## Optional follow-up DM (after they run it)
> "Whatever it told you — that's the muscle. Most people either torch budget on habit or under-power something that mattered. If you want that turned into an actual system instead of a once-off audit, that's literally what we build. No pitch if you're not interested, just let me know what the audit said 👀"
