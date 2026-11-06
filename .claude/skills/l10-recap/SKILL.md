---
name: l10-recap
description: Turn an Ops L10 Fathom recording into an EOS meeting record (To-Dos, IDS outcomes, cascading messages, rating) in eos/l10/. Use after an L10, or when Betty asks to recap, log, or catch up on L10 meetings.
---

# L10 Recap (from Fathom)

1. Find the recording. If Betty pasted a link, use `get_recording_by_url`. Otherwise list all accessible meetings around the date and match the Ops L10 title (see `eos/l10/README.md`). Confirm it's the Ops L10, not Leadership, Sales, Marketing, or BD.
2. Read the summary, then the transcript for detail. **Ground every line in what was said.** No guessing.
3. Write `eos/l10/YYYY-MM-DD.md` using the `_template.md` sections:
   - Scorecard / Rock items called off track
   - Headlines
   - **IDS:** each issue → root cause → solution → To-Do
   - **New To-Dos:** owner + due date (flag any missing either)
   - Cascading messages, meeting rating if given
   - **EOS coaching notes:** where the meeting drifted from L10 format (tangents in Scorecard/Rocks, IDS without a Solve, ran over)
   - Fathom link at the top
4. **Do not paste full transcripts** into the repo. They can contain member names and payment details. Keep it to summaries, decisions, and To-Dos, with members referred to by first name only.
5. Update `eos/issues-list.md` and list To-Dos that should go into ClickUp. Don't add them unless Betty asks.
