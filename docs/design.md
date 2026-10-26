# Profile design

## Purpose

Help visiting engineers quickly understand the technologies used and the engineering
areas that may start a useful conversation. The content hierarchy is technical focus,
stack by role, engineering interests, then a quiet personal footnote.

Do not repeat the account name as branding. Do not feature an individual software
project. Personal interests must not be the headline or the main visual subject.

## Content grounding

Technology names were checked against the current workspace package manifests on
2026-10-26. The published profile contains only technology names and broad engineering
topics, not private repository names, application architecture, employers, locations,
usage metrics, or claims of expertise. Framework versions are intentionally omitted.
The Web row uses vinext because it is present in the inspected manifests.

Official documentation links provide context for readers who want to explore the tools.
The interest bullets describe technical themes; no skill ratings or achievements are
claimed. The footer retains the two personal interests explicitly supplied by the owner.

## Visual decisions

Retain the requested cute/pop quality through cream, lilac, mint, and soft pink, with
rounded technology badges and a compact editor layout. Keep the title technical and
short so the stack is visible early. Use selectable Markdown for the detailed stack and
interest bullets rather than putting the entire profile in an image.

The desktop header is `assets/engineering-header.svg`. Below 600 px, `picture` selects
`assets/engineering-header-mobile.svg`, omitting the small editor panel to keep the
headline legible. Six local badges highlight the main tools; the table explains the
broader stack by layer. Icon source attribution is in `assets/stack/NOTICE.md`.
No third-party dynamic images, counters, animation, trackers, or scheduled jobs are used.

The profile repository remains the sole pinned item to avoid GitHub's automatic
popular-repository fallback. Its description summarizes the technical focus.

## Acceptance

- The live Overview leads with technical focus and readable technology badges.
- No custom name banner, large hobby feature, or individual project promotion remains.
- All technology images load; labels and the table fit desktop and narrow viewports.
- Technology links point to their official sites or official repositories.
- Engineering topics and role grouping are consistent with the inspected dependencies.
- Remote README and SVG files match the local committed state.
- Temporary browser viewport overrides are reset after inspection.

Runtime self-review evidence is kept locally in `.agent-artifacts/`, excluded from Git.
This is not a user study or a complete accessibility audit of GitHub itself.
