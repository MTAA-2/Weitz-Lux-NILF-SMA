# Social Media Justice Help Now — Case Review Page (Design Build)

Static landing page (HTML + CSS only, no PHP) built directly from the
user's uploaded design image, "A clearer path to a free case review,"
rather than from the usual landing-page framework.

## Files

- `index.html` — the page
- `css/style.css` — all styling

## Layout (follows the image closely)

- White header: WEITZ & LUXENBERG wordmark (navy serif) with the
  "Social Media Justice Help Now" subline; "Free case review" at right
- Pale-blue hero (#E7EEF4): eyebrow, serif headline "When social media
  harms, you deserve answers.", intro copy, two teal-check trust lines
  ("Free, confidential review" / "No attorney fee unless we win your
  case"), and the family-photo area with its "Illustrative image."
  caption
- White form card at right: "Start your free case review," the
  About you → Your experience → Contact details step indicator with the
  teal progress bar, the **iframe embed area**, then "No obligation to
  hire a lawyer." and the Privacy Policy link, as in the image
- "What happens next?" — three numbered steps with light-teal circles
  and dividers
- Footer strip exactly as in the image: "ATTORNEY ADVERTISING • Results
  are not guaranteed." / "Sponsored by Weitz & Luxenberg and The
  National Injury Law Firm, PLLC." with Privacy Policy / Disclaimer
  links at right. (The fuller sponsor block with both firms' addresses
  is on the framework version of this page if a longer disclaimer is
  wanted here.)

Palette: navy #14304D / #10263F, teal #0E6E63 with light tint #D9EBE7,
page #E7EEF4, lines #D5DEE7. Headlines and brand in Georgia serif, UI
text in Inter.

## Embeds carried over

- Form iframe: the current framework MTAA embed
  (nf_3270a8a1b0e4425cb70e9f97f2fa5a3c) sits in the card's embed area —
  swap its `src` to change forms. The frame area scrolls internally.
- MTAA CIPA block and Meta Pixel 1238664640565416 (ViewContent) in the
  head, as on the other pages (invisible; does not affect the design).

## Placeholder

- The hero photo is a styled placeholder box. Replace the
  `.photo-box` div with an `<img>` (markup shown in an HTML comment in
  index.html) to drop in the mother-and-daughter photo.
