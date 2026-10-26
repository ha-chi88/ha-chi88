# Profile design

## Purpose and content

Make the GitHub Overview recognizable as 88 / ha-chi88, explain the public work,
and let visitors reach the code and documentation quickly.

Content is grounded in the public `ha-chi88/safe-webview-bridge` README and GitHub
profile inspected on 2026-10-26. The project describes TypeScript messaging between
Web and React Native WebView, Standard Schema validation, and separate platform
imports. Do not add employers, locations, contact details, private projects, or
unverified skill claims.

## Visual decisions

The existing profile has a coastal sunset avatar and GitHub's native repository and
contribution sections. Retain that context. The warm orange accent relates to the
sunset; charcoal and ivory keep the typography distinct in both GitHub themes.
This direction is an implementation choice, not recorded user approval or a user study.

Use a compact editorial layout: typographic introduction, one featured project,
and direct navigation. A metrics-heavy layout would duplicate the native contribution
section and put counters ahead of the actual work. No third-party image services,
generated illustrations, scripts, trackers, animated counters, or maintenance workflows
are needed. The SVGs implement the header's typography and layout as self-contained
vectors because GitHub sanitizes README CSS.

`assets/profile-header.svg` owns the desktop layout; the compact variant is selected
at a viewport width of 600 px or below through a native `picture` element. Essential
project details and links remain selectable HTML/Markdown text outside the header.
The image has alternative text; no information relies on motion or color alone.

## Visitor path

Overview → identify the developer and focus → read the featured library summary →
open its README, source, or security model. The footer links to all repositories.
Native GitHub navigation handles returning to Overview.

## Acceptance

- Public `ha-chi88/ha-chi88` repository with a root `README.md`, visible on Overview.
- Header loads from this repository, without clipping or external image dependencies.
- Japanese body text and the compact header remain readable at a narrow viewport.
- Featured project links resolve to the public project and the named sections/files.
- The public project is pinned; no private repository is published or featured.
- Final rendered-page evidence and validation notes are kept locally in
  `.agent-artifacts/`, excluded from Git.

GitHub's own Markdown typography, focus styles, and navigation remain authoritative;
this change does not claim a full accessibility audit of GitHub.
