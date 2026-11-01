# Portfolio

Static GitHub Pages portfolio.

## Resume updates

Current approved resume: [29 October 2026](Chua_Siok_Cheng_AI_Engineer_Resume_2026-10-29.pdf).
The PDF is the source of truth; `resume_updated.md` is a text extraction for reference.

When a newer resume is approved:
1. Copy the approved PDF byte-for-byte with a dated filename; do not infer new employment details.
2. Update both PDF links in `index.html` and the visible updated date together.
3. Refresh `resume_updated.md` from that same PDF and check contact-link consistency.
4. Remove superseded PDFs from the published tree (previous versions remain in Git history).
5. Check both resume links, PDF readability, and desktop/mobile layout.
6. Review the change before merging to the publishing branch. After publication, verify both public links serve the approved file.

Preview locally with `python3 -m http.server 8000`. No build step or test framework is configured.
