# Profile design

## Brief

The owner requested a cute, pop personal profile and explicitly shared two interests:
takoyaki and guitar. Present 88 / ha-chi88 and those interests in a friendly way.
The profile should not feature a software project or imply a technical specialization.

## Visual direction

Use cream, coral pink, mint, and lavender; rounded type, small cheerful symbols,
and tilted sticker-like panels with offset outlines. The layout uses typography,
standard emoji, and simple UI geometry. It needs no external image services, scripts,
trackers, generated illustrations, or scheduled maintenance.

The banner's color values are defined in `assets/hello-88.svg` and its compact variant.
System emoji and font appearance can differ by platform. Essential personal copy
is repeated as selectable Markdown/HTML, and the banner has useful alternative text.
No animation or color-only information is used.

The desktop header emphasizes the name between the two interests. At viewport widths
of 600 px or less, `picture` selects `assets/hello-88-mobile.svg`, which puts the
interests underneath the name. New asset paths distinguish this revision from the
previous design in GitHub's image caches.

The README is intentionally short: banner, personal greeting, and welcome.
GitHub's native contribution history remains below. Pin the profile repository itself
so the Overview does not fall back to automatically featuring other repositories.

## Acceptance

- The live Overview shows the new banner and greeting.
- The only stated personal interests are the user-provided takoyaki and guitar.
- No project feature, technical stack, related slogan, or project link remains in the
  README, banner, repository description, or pinned section.
- The desktop and compact images load, and narrow layouts have no horizontal overflow.
- The native avatar and account settings remain as they were.
- The public repository's root README and assets match the local committed files.

Runtime evidence is stored locally in `.agent-artifacts/` and excluded from Git.
This implementation review is not a user study or a full GitHub accessibility audit.
