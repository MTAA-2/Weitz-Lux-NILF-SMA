# Social Media Addiction Claims — Weitz & Luxenberg

Static GitHub Pages landing page (HTML + CSS only, no PHP) modeled on
https://www.socialmediajusticehelpnow.com/fc17beee/, styled after the
user's uploaded design image ("A clearer path to a free case review"),
and built on the latest generated framework (the asbestos build's files,
same index-10 / style-12 lineage).

## Files

- `index.html` — the page
- `css/style.css` — all styling

## Framework carried over (unchanged)

- MTAA CIPA block script; Meta Pixel 1238664640565416 (with ViewContent)
- Form embed nf_3270a8a1b0e4425cb70e9f97f2fa5a3c (the current framework
  embed from the uploaded files) in the overflow form card — the card
  hangs past the hero and the frame scrolls internally (`overflow: auto`)
- Relative footer legal links (`privacy-policy.html` / `disclaimer.html`),
  as in the uploaded framework. Note: the live sample instead links to
  weitzlux.com/privacy-policy/ and weitzlux.com/disclaimer/ — swap the
  two footer hrefs if you prefer the firm's own pages.

## Branding

Converted to the sample's sponsor, from its footer: **Weitz &
Luxenberg**, 1880 Century Park East, Suite 700, Los Angeles, CA 90067,
and **The National Injury Law Firm, PLLC** — Responsible CO Attorney
Stephen Dampier, CO Bar #22151, 8512 Central Ave, Suite 900, Phoenix,
AZ 85012. The sample displays **no phone number**, so the page is
phoneless and the header carries the text wordmark (white header, as in
the design image). Disclaimer carries the sample's own consent wording
(filling out the form does not create an attorney-client relationship),
its "Recovery is not guaranteed" line, and its medical-advice note.

Left out as unverified: a "Why Families Choose Us" trust block with a
"$1 billion+ recovered" claim appeared in only one of several live
renders (the page serves variant content) and was not used. A short
testimonial quote attributed to "Donna, NJ" on the live page was also
left out.

## Palette (from the uploaded design image; one accent from the live page)

- Deep navy #14304D — headlines, titles, top bar
- Teal #0E6E63 — CTA buttons, qualifier checks, cards-section overlay;
  hover #0B5A50
- Pale blue #EAF1F7 / #DCE8F2 / #CFDCE8 — light hero gradient and band
- Slate #3D5A76 — hero subcopy
- Light blue #79CCFF — highlights on dark backgrounds (sampled live)
- Dark navy #0A1D3B — footer (sampled live)
- Headlines in Georgia serif, matching both the image and the live page

CSS differs from the framework only in color values, heading
font-family values, and placeholder image URLs (verified by diff). The
hero is light per the design image, so its text/sub/badge colors were
recolored (color values only).

## Content (from the live page + design image)

- Hero from the design image: "When social media harms, you deserve
  answers." — serious mental health harm after using social media as a
  minor; free, confidential review; no attorney fee unless we win
- "What happens next?" — the image's three steps (share your experience,
  get a confidential review, understand your options)
- Social Media Claims: compulsive-use definition, ad-revenue /
  behavioral-psychology design allegations (Facebook, Instagram,
  Snapchat, TikTok named as on the sample page)
- Effects cards: Mental Illness; Physical Injuries; Quality of Life;
  Withdrawal Symptoms; Eating Disorders & Body Image; Bullying &
  Cyberbullying
- The Claim Process (light parallax band): intake review → contract →
  evidence and submission
- Qualifiers (the sample's three bullets) and FAQs from the form's own
  questions (claim for myself / loved one 13–17 / 18–25 / 26+ / passed
  away; apps incl. YouTube; use between ages 5 and 17; hours per day;
  treatment; existing representation), the no-testimony point, and the
  deadline paragraph (limited, varies by state — no date, as on the
  sample)

## Placeholders to replace

- `images/REPLACE-FAMILY-IMAGE.jpg` — side image (supportive family
  photo, as in the design image)
- `YOUR-IMAGE-URL-HERE` — hero parallax background
- `YOUR-IMAGE-URL-HERE-2` — effects-section parallax background
- `YOUR-IMAGE-URL-HERE-3` — claim-process parallax background
