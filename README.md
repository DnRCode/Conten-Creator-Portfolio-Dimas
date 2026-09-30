# Dimas Adi Darmawan — Content Creator & Social Media Specialist Portfolio

Static site, no build step, no framework — same plain HTML/CSS/JS approach as
the reference codebase this was derived from. Deploy by uploading this folder
as-is to any static host (GitHub Pages, Netlify, Vercel, Cloudflare Workers,
Canva Sites, etc.) with `index.html` at the root.

## What changed in this pass

This is a repositioning pass on top of the "Digital Marketing & Creative
Communication" reference build, narrowing the narrative to **Content
Creator / Social Media Specialist / KOL**. No new photos, certificates or
facts were added or removed — every number, date and credential is exactly
as it was in the reference. What changed is framing:

- **Hero** — role line is now "Content Creator / Social Media Specialist /
  KOL"; lead copy foregrounds on-camera talent and social content work; CTA
  is "See my content"; the marquee keyword set and the "Open to work" badge
  (now "Open to collab") were updated to match.
- **About** — lede and both body paragraphs reframed around being
  comfortable on both sides of the camera (creating/filming/managing content
  *and* appearing as talent in it); the "Focus" fact is now "Content Creation
  · Social Media Management · KOL / Brand Partnerships."
- **Selected Work** — three project tags renamed to match the new framing:
  Alluvia skincare is now tagged "KOL Collaboration" (copy now says he
  planned, produced *and starred in* the campaign under his own creator
  account), the Disnaker infographics/Reels project is "Social Media
  Content," and the modelling photo studio project is "On-Camera Content."
  The other six project tags (People Storytelling, Coursework · Talent/
  Producer Role, Public Communications, Creative & Design) were left as-is —
  they already fit a creator narrative without changes.
- **Core Competencies** — the two content-related skill groups were renamed
  and reordered: "Marketing & Creative" → **"Content & Social Media"** (now
  leads with Content Creation, Social Media Management, Personal Branding,
  Brand & KOL Partnerships), and "Additional Skills" → **"Production &
  On-Camera"** (now leads with On-Camera Presenting & Talent). Language and
  Tools groups are unchanged.
- **Contact / footer / meta tags** — title, description and section-lead
  copy updated to say Content Creator / Social Media Specialist / KOL
  instead of Digital Marketing / Content Strategy / Creative Communication.
- **Experience section** — left mostly as-is (these are real jobs/
  internships that support credibility regardless of framing); only the
  section's intro sentence was lightly reworded.

## Bug fix carried over from review

The reference build's header nav wrapped onto two lines at common desktop
widths (~1440px) once a 7th nav item ("Leadership") was added without
adjusting the header's available width. Fixed here by giving the header its
own slightly wider max-width (independent of the page's content container)
and trimming the nav's internal spacing — verified at 1440px with no wrap,
and confirmed no regression at mobile widths.

## Still open (carried over from the reference build's own notes)

These were flagged as unresolved before this pass and remain unresolved —
none of them are addressed by the repositioning above:

1. **Instagram handle split** — `@gulagin__` on the Alluvia project link vs.
   `@dimasdarmawan2` on the general Contact link. Worth unifying if a single
   handle is the intended public creator handle.
2. **"Fluoxetine" film poster** — sensitive subject matter (an antidepressant
   drug name); copy stays neutral (typography/poster-design skill only, no
   plot detail). Confirm keep/remove.
3. **External links unverified** — YouTube, Instagram and Canva links in this
   build were not independently re-checked as part of this pass (this
   environment cannot reach those domains to test them).

## Verified before delivery (this pass)

- All `src`/`href`/`data-lightbox` paths still resolve — no new broken
  images or links introduced by the copy edits.
- No console/page errors on load.
- Header nav fits on one line at 1440px (previously wrapped); no regression
  at 390px mobile width (no horizontal scroll).
- Lightbox, mobile menu and scroll-reveal all confirmed working.
