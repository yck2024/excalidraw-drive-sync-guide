# 0001: Five-page static guide

Date: 2026-11-10. Status: accepted.

Use the same public page set as AI Prompt Assistant: `index.html`, `setup.html`, `release-notes.html`, `faq.html` and `privacy.html`. Share navigation, footer and one stylesheet; use relative asset and page URLs for the GitHub Pages repository prefix. Keep the guide build-free, accessible without JavaScript, with native expandable FAQ answers and full-size screenshot links.

The home introduces the extension through real screenshots; Setup explains actions and save limits; the FAQ answers troubleshooting questions; Privacy fully describes functional processing rather than claiming that no data is handled. No analytics. Website hosting is GitHub Pages; extension drawing traffic goes directly to Google, not a developer server.

Source of truth: extension repository origin/main at 54ebcf9, especially docs/store/1.2.0/{description.txt,whats-new.txt,permissions.md,privacy-practices.md}, the five approved screenshots and docs/decisions. The existing kengblog page supplies continuity in plain-language setup, use cases and the personal-site contact link. Updating that page and enabling Pages are outside this change.
