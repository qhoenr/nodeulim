<instructions>
## 🚨 MANDATORY: CHANGELOG TRACKING 🚨

You MUST maintain this file to track your work across messages. This is NON-NEGOTIABLE.

---

## INSTRUCTIONS

- **MAX 5 lines** per entry - be concise but informative
- **Include file paths** of key files modified or discovered
- **Note patterns/conventions** found in the codebase
- **Sort entries by date** in DESCENDING order (most recent first)
- If this file gets corrupted, messy, or unsorted -> re-create it. 
- CRITICAL: Updating this file at the END of EVERY response is MANDATORY.
- CRITICAL: Keep this file under 300 lines. You are allowed to summarize, change the format, delete entries, etc., in order to keep it under the limit.

</instructions>

<changelog>
- 2026-06-15: Added wheel-event mapping in `index.html` so vertical scroll input moves horizontal canvas.
- Kept layout intact and enabled smoother horizontal movement behavior in `style.css`.
- 2026-06-15: Converted vertical stack to horizontal scroll by repositioning each 1080px section in `style.css`.
- Updated `.frame` to fixed 1080px height and 21120px horizontal canvas with `overflow-x` enabled.
- Mapped top-level section offsets from vertical `top` values to sequential horizontal `left` positions.
- 2026-06-15: Removed @FONTWARNING markers and remapped restricted font source in `globals.css`.
- Updated `Jeju Samdasu SpecialOTF-Regular` to use hosted TTF source as closest 400/normal match.
<!-- NEXT_ENTRY_HERE -->
</changelog>
