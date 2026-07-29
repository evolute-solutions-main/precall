# HANDOFF CONTEXT — Evolute Solutions Pre-Call Doc Project

You're continuing work on a pre-call briefing page for Evolute Solutions, a contractor marketing agency run by Max. This doc captures all project context, decisions made, and current state.

---

## WHO I AM (THE USER)

- **Name:** Max
- **Company:** Evolute Solutions
- **What we do:** Growth partner (NOT a lead provider) for contractors in the US. We run ads, AI-driven lead response, human setters, calendar booking, pre-appointment indoctrination. Install the whole infrastructure into their business.
- **Background:** Software engineer at AWS, then at Elon Musk's xAI building chatbots for Starlink. Left to start Evolute. Based in Bali. Into meditation, done 10-day silent retreats.
- **Current offer:** $6K PIF (paid in full) for 3 months, with optional $35/appointment on top (per David Wehner's coaching)

---

## PROJECT CONTEXT

This pre-call doc is the **forced consumption asset** that gets sent to prospects AFTER they're booked for a sales call and BEFORE the actual call. The flow:

1. Setter runs cold SMS outbound to contractors
2. Prospects reply, setter calls them
3. Setter books Zoom with Max (the closer)
4. Setter creates 3-way group chat (prospect + Max + setter)
5. **Setter sends this pre-call doc + the Loom VSL in the group chat**
6. Prospect watches + reads before the Zoom

The doc's job is to:
- Tell them exactly what steps to take before the call (watch video, scroll, text questions)
- Kill skepticism (contractors have been burned by marketers repeatedly)
- Filter out wrong-fits (so Max doesn't waste Zoom time)
- Build trust with social proof
- Make them show up to the Zoom prepared, not cold

---

## ORIGIN: THE COACHING CALL

This all started from a coaching call with David Wehner (April 17). The relevant takeaways from that call that informed the doc:

- David's own pre-call doc template was used as structural inspiration (see "PATTERN" section below)
- The concept of "forced consumption" — making prospects go through the doc + video BEFORE the call, not after
- David's 4-part lockdown: email accept → group chat → save contact → open doc/VSL, all while the setter is on the phone with the prospect
- The setter training doc is already built (separate file)
- The cold SMS template is already built (separate file)

---

## DESIGN DECISIONS MADE

### Visual / brand
- **Colors:** ONLY white, yellow (`#ffd800`), red (`#ff4d4d`), and black. No grey anywhere.
- **Logo:** Evolute Solutions logo (yellow on black, "ES EVOLUTE SOLUTIONS"). Embedded as base64 in the HTML. Only appears in nav and footer — NOT on card interiors.
- **Fonts:** Bebas Neue for headlines/display, Inter for body, JetBrains Mono for technical labels and metadata
- **Aesthetic:** Bold, masculine, contractor-appropriate. Dark theme with yellow accents. Grain texture overlay. Radial yellow glow behind hero.
- **Self-contained:** Single HTML file. Logo embedded as base64. Only external dependency is Google Fonts CDN.

### Content / copy decisions
- **NO ad spend mentioned** anywhere — leave that for the sales call
- **NO guarantee mentioned** — was in an earlier VSL but not offered now
- **NO area exclusivity mentioned** — not universal
- **NO FAQ section** — removed, the rest of the doc covers it
- **Ad tracking flex** FAQ was removed along with the FAQ section
- **Results timeline:** "about a week to launch, from there it's smooth sailing" (NOT 30-60 days)
- **Close rate:** "25-45% when dialed in" (said in the "not for you" section)
- **Pricing:** Never shown — deferred to the sales call

### Hero copy (exact, locked):
> **Headline (Bebas Neue, white → yellow on second line):**
> "Before our call, **there are a few mandatory steps for you to complete.**"
>
> **Body:**
> "This is to make sure you know what we do before blocking off time to talk with us, gives you a chance to ask questions early, and make the call as quick as possible."
>
> **Red warning box:**
> "If you're not able to do this before our call, we'll need to pick a different time. Just takes a few minutes."

### The 3 steps (exact, locked):
1. **Watch the full walkthrough** — The video below. ~10 minutes. Feel free to watch at 1.5x speed. This is the most important step — everything else builds on it.
2. **Scroll through the rest of this page** — Client testimonials, the full system breakdown, and who we do and don't work with. Takes a couple minutes.
3. **Text us any questions before the call** — Just reply in the group chat with anything you want to make sure we cover. The more we handle beforehand, the more useful the call will be.

### The Loom VSL
Embed code:
```html
<div style="position: relative; padding-bottom: 56.25%; height: 0;"><iframe src="https://www.loom.com/embed/15cd96fbec2046b799181b7f12dc7f53" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"></iframe></div>
```
Length: ~10 min. Covers: who Max is, why we're different, the full system end-to-end, what to expect.

---

## FINAL SECTION ORDER (v4 — current state)

Strategy: Trust-first with scattered testimonials. Action CTAs first, differentiation early, proof sprinkled throughout, system detail in the middle, fit check late, bio at end.

1. **HERO** — "mandatory steps" headline + red warning
2. **3 STEPS** — big yellow-bordered cards: Watch / Scroll / Text
3. **VIDEO** — Loom iframe
4. **🏆 HERO TESTIMONIAL** — single standout with extra-large styling (deck builder, $93K single job, "you sketched me out at the beginning — but you have delivered")
5. **SECTION 01 / POSITIONING** — "We Are NOT A Lead Provider" + yellow comparison table (Lead Vendors vs Evolute)
6. **→ PROOF INTERLUDE 1** "What Our Partners Say" — 2 testimonials (Roofing Contractor / 9+ Jobs Signed; Contractor Partner / 20 Appts First 2 Weeks)
7. **SECTION 02 / THE SYSTEM** — 5 numbered pillars + dashboard/optimization footer
8. **→ PROOF INTERLUDE 2** "Real Results" — 2 testimonials (Planchel / Kitchen Remodeler Toronto; AJ / Kitchen Remodeler Brooklyn)
9. **SECTION 03 / FIT CHECK** — "Is This For You?" — is for / not for cards
10. **→ PROOF INTERLUDE 3** "Overflow Volume" — 1 testimonial, single centered (couldn't quote fast enough)
11. **SECTION 04 / THE BIG PICTURE** — "Scaling A Contracting Company Is Simple" — 4 problem/solution pairs
12. **SECTION 05 / ABOUT** — Max's bio with 10-day silent retreat fun fact
13. **LIBRARY CTA** — "Want to see more proof? View Full Library →" (placeholder link)
14. **FOOTER** — logo, tagline, "See you on the call."

---

## PLACEHOLDERS STILL TO FILL

1. **`LINK_TESTIMONIALS_HERE`** — URL for the full testimonials library (appears once, in the library CTA at the end)
2. **Testimonials** — currently populated with Max's placeholder pulls from his VSLs (AJ, Planchel, deck builder at $93K, etc). Max will provide real testimonial content to swap in.
3. **Testimonial avatars** — currently use first initial of the person/role (e.g., "D" for Deck Builder). Can be swapped for actual photos if Max provides them.

---

## KEY "NOT FOR YOU" LIST (important — took multiple iterations to land)

```
This is NOT for you if:
- You're a one-man shop or handyman doing smaller jobs
- You don't have enough profit or savings to reinvest into scaling
- You want free work until you close a deal — we partner with you, take over
  the front end and sales side, and build real systems in the trenches. If you
  won't invest in your own business, this isn't a fit.
- You're comfortable where you are and don't actually want to scale
- You expect every appointment to close (best-in-industry is 30-45%)
```

The "free work" line is important because it filters contractors who want pure performance-based deals — Max's offer is PIF + per-appt, not pure performance.

---

## CURRENT FILE STATE

- **File:** `/mnt/user-data/outputs/precall.html`
- **Size:** ~83 KB
- **Self-contained:** Logo embedded as base64, only external dependency is Google Fonts CDN
- **Latest version:** v4 (with scattered testimonials, reordered sections per trust-first strategy)

**The full v4 file is attached below this handoff doc.** You'll receive it as a separate file.

---

## RELATED FILES IN THIS PROJECT (already built, separate from pre-call doc)

1. **Setter training doc** (`setter_training_doc.md`) — Full script for setters calling cold SMS replies. Covers opener, mini-pitch, alignment check, discovery, frame flip, booking, 4-part lockdown, post-call cadence, objection handling. Based on David's coaching with contractor-specific translations. Should already be in context via previous convo if you have it.

2. **Cold SMS message** (locked, ready to send):
> "Hey, not gonna bs you and pretend like I'm a customer looking for work like all those other texts I'm sure you get....i saw you on Google and I'm looking for contractors who could benefit from a legit end to end system for high-quality in person appointments. Nothing like shared leads from those big sites or running generic ads that waste your time with tire kickers. We take care of everything end-to-end: find ppl who are in market for remodels (never shared), talk with them to make sure they're actually serious, and even send you out to meet them in person. Open to a chat to see if this might be a good fit?"

---

## WHAT'S LIKELY NEXT (for Claude Code to anticipate)

Based on the project trajectory:

1. **Swap real testimonials in** when Max uploads them (video interviews, screenshots, etc.)
2. **Fill in the library CTA link** once he has the URL
3. **Possibly add a favicon** to the HTML (not done yet)
4. **Possibly adjust avatars** to real photos
5. **Possibly deploy** — host somewhere (Netlify, Vercel, his own domain) so he can share a link rather than an HTML file

Max tends to iterate fast and ask for specific tweaks — he's good at knowing what he wants. If he asks for a change, just do it cleanly. He prefers brief confirmation of what you changed, not explanations of process.

---

## COMMUNICATION STYLE MAX PREFERS

- Direct, no fluff
- Push back when something is off — don't just agree
- Offer multiple options when there's a design call to make, but recommend one
- Bullet-point changes concisely after making edits
- Ask clarifying questions up front rather than guessing and redoing
- Flag editorial calls you made so he can veto if needed

---

## END OF HANDOFF CONTEXT
