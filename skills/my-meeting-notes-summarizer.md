# my-meeting-notes-summarizer

**For meeting notes and transcripts.** Use when a user needs to turn messy meeting notes, call notes, or transcript excerpts into a clean, structured summary.

## What This Skill Does

This skill helps you transform unorganized meeting notes into a well-structured summary that's easy to understand and act on. It works with:
- Meeting notes (written during or after a meeting)
- Call transcripts (from video or phone calls)
- Discussion snippets (parts of conversations)
- Chat logs or email threads

## How to Use This Skill

When someone asks you to summarize meeting notes, use this skill to organize the information into five sections:

1. **Meeting Summary** - A brief overview of what the meeting was about
2. **Key Discussion Points** - The main topics that were talked about
3. **Decisions Made** - What was decided during the meeting
4. **Action Items** - What needs to be done, who will do it, and when
5. **Open Questions** - Things that still need to be answered

## Important Rules

### Don't Make Things Up
- Only use information that's actually in the notes
- If a detail is missing, say "Not specified" instead of guessing

### Handling Missing Information

| Item | What to Write |
|------|---------------|
| Owner of a task | `Not specified` |
| Deadline for a task | `Not specified` |
| Information not in notes | `Not mentioned` |

### Keep It Simple
- Use clear, everyday language
- Keep summaries short and practical
- Break down complex topics into simple points
- Use bullet points for easy reading

### Action Items Table

Always format action items as a table with these columns:

| Task | Owner | Deadline |
|------|-------|----------|
| Brief description | Person's name or "Not specified" | Date or "Not specified" |

## Example

### Input (Messy Notes)
```
Team standup - talked about new feature launch. John thinks we should wait, but Sarah wants to go ahead next week. We discussed testing, David will handle QA. Need to figure out the marketing plan. Tom might help with documentation but he wasn't sure. Deploy by June 15. Budget approval still pending from finance. Email the client this week. Marketing is confused about messaging. Could we do a follow-up next Tuesday?
```

### Output (Structured Summary)

**Meeting Summary:**
The team discussed whether to launch a new feature. There's disagreement about timing, and several tasks need to be completed before launch.

**Key Discussion Points:**
- Timing of the feature launch (next week vs. waiting longer)
- QA testing requirements
- Marketing messaging strategy
- Client communication
- Documentation needs
- Budget approval status

**Decisions Made:**
- Feature will be deployed by June 15

**Action Items:**

| Task | Owner | Deadline |
|------|-------|----------|
| Complete QA testing | David | June 15 |
| Email the client | Not specified | This week |
| Finalize marketing messaging | Not specified | Not specified |
| Write documentation | Tom | Not specified |
| Get budget approval from finance | Not specified | Not specified |

**Open Questions:**
- Should we launch next week or wait longer?
- What is the final marketing messaging strategy?
- Will Tom be available to write documentation?
- Has budget approval been received from finance?

## Tips for Best Results

1. **Read the notes completely** before you start organizing them
2. **Separate different types of information** - don't mix decisions with discussion points
3. **Use action items only for tasks** - things that need to be done
4. **Put unclear items in Open Questions** - don't try to guess the answer
5. **Keep language simple** - imagine explaining this to someone who wasn't at the meeting
6. **Be specific** - "Fix the login bug" is better than "Fix issues"
7. **Ask for clarification** - if notes are too vague, it's okay to ask what something means

## Common Mistakes to Avoid

❌ **Don't:** Invent owner names or deadlines that aren't mentioned
✅ **Do:** Write "Not specified" instead

❌ **Don't:** Mix opinions with decisions
✅ **Do:** Put opinions in "Key Discussion Points" and confirmed decisions in "Decisions Made"

❌ **Don't:** Make assumptions about what was decided
✅ **Do:** Only list things that were clearly decided during the meeting

❌ **Don't:** Use jargon or technical terms without explaining them
✅ **Do:** Use simple, everyday language

## When to Use This Skill

- ✅ Meeting notes from a team standup
- ✅ Notes from a client call
- ✅ Transcript snippets from a video meeting
- ✅ Chat logs from a discussion
- ✅ Email threads about a decision
- ✅ Any conversation that needs to be organized

## When NOT to Use This Skill

- ❌ Creating meeting notes (use this skill to organize existing notes instead)
- ❌ Making decisions (only summarize what was already decided)
- ❌ Predicting future actions (only list tasks that were actually assigned)
