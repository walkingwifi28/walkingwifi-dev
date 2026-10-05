# Design QA

- Source: `/var/folders/wc/kdbyg03x5r132xkd6c9dmjsh0000gn/T/codex-clipboard-8daaad1a-ca8d-457c-b1d2-8af85e095852.png` (934 × 1379)
- Implementation: `/tmp/walkingwifi-desktop.png` (934 × 1393 full-page capture)
- Browser: Codex in-app browser, desktop viewport 934 × 1379 CSS pixels, mobile 390 × 844 CSS pixels. Capture density: 1.
- State: initial page, white background.
- Full-page comparison: source and rendered captures opened together. Content, left margin, hierarchy and page order match. Company heading weight and undersized Oracle wordmark were corrected after initial capture; a second browser capture confirmed the corrections.
- Focused regions: technology logos inspected in the full-resolution capture; no separate crop required.
- Mobile: no horizontal overflow (document scrollWidth and viewport both 390); images loaded successfully.
- Link verification: all four anchors have HTTPS destinations and safe new-tab attributes. All four URLs updated and checked against the URLs supplied by the user.
- Browser console errors: none. Broken images: none.
- Static validation: local image references and alt text checked; git diff --check passed.
- Follow-up polish (P3): supplied logo variants differ slightly from the reference; platform font rendering and section positions vary by a few pixels.

final result: passed
