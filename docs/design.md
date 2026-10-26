# Profile design

## Purpose and approved content direction

Help visiting engineers understand the main stack and development interests quickly.
The owner explicitly selected TypeScript, React, React Native, Expo, Cloudflare, and
Node.js. Keep those six technologies central; do not broaden the stack from inferred
workspace usage. Do not position the profile around API type safety or feature a
particular software project.

Do not repeat the account name as branding. Personal interests are a quiet footer,
not the headline or main visual subject. Avoid skill ratings, unsupported achievements,
employers, private repository names, locations, or usage metrics.

## Structure and visual decisions

Order: compact technical header, introduction, six technology badges, role mapping,
engineering interests, personal footnote. The header communicates Web/Mobile/Cloud;
the interests cover cross-platform development, UI/developer experience, and delivery.

Retain the requested cute/pop quality through cream, lilac, mint, and soft pink,
rounded badges, and a small editor layout. Keep the detailed content as selectable
Markdown/HTML. Official-site links let engineers explore unfamiliar technologies.

The desktop header is `assets/web-mobile-header.svg`. At viewport widths of 600 px
or less, `picture` selects `assets/web-mobile-header-compact.svg`, which omits the
small code panel for legibility. Local badge icon attribution is in
`assets/stack/NOTICE.md`. No dynamic third-party images, counters, animation, trackers,
or scheduled maintenance are needed.

The profile repository is the sole pin, preventing the automatic popular-repository
fallback from featuring another project. Its description names the six selected tools.

## Acceptance

- The live Overview centers the six user-selected technologies.
- No custom account-name banner, prominent hobby feature, project promotion, or API
  type-safety positioning remains.
- Every image loads, and the stack table and labels fit narrow viewports.
- Links resolve to official technology documentation or sites.
- Remote README and SVG blobs match local committed files.
- Temporary browser viewport overrides are reset after inspection.

Runtime self-review evidence is kept locally in `.agent-artifacts/`, excluded from Git.
This is not a user study or a complete accessibility audit of GitHub itself.
