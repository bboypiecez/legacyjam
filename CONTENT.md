# Legacy Jam — Content & Prompt Kit

Copy blocks and reusable prompts for building out the Legacy Jam website, socials and
Eventbrite listing. Everything here matches the live copy in `index.html` — edit in both
places if you change the message.

---

## 1. Core messaging

**Event name:** Legacy Jam 2026
**Tagline:** Cyphers / Culture / Community
**Dates:** October 23–25, 2026 · Toronto
**One-liner:** A three-day breaking festival connecting generations — battles, cyphers, workshops, talks and the after party.

**Hero mission line** (`.hero-mission`, below the tagline, above the dates/CTA
row — the site's top-of-page mission statement):
> Legacy Jam brings generations of Breaking together through battles,
> mentorship, cyphers, workshops, talks and community, celebrating people who
> built the culture while creating opportunities for the next generation to
> grow, connect and lead.

**Purpose statement (short):**
> Breaking is rooted in cyphers, community and culture — passed down generation to
> generation. Legacy Jam keeps that chain alive: celebrating the people who built
> Canadian breaking, investing in the youth who'll carry it forward, and putting
> Canadian breakers on the world stage.

**Elevator pitch (for Eventbrite / press):**
> Legacy Jam is Toronto's intergenerational breaking festival. Over three days, teachers
> battle beside their students, youth winners earn flights to Outbreak Europe 2027, and
> Canadian breakers face international guests in curated Legacy Exchanges — plus workshops,
> talks, and a party that brings the whole community together.

## 2. Battle formats (canonical descriptions)

Site section is titled "Battles and Prizes". Each card leads with a one-line
format/age description, then **Prize &rarr; Register link.** Prize is the
visual highlight of each card (bold, on a tinted background band); round
counts and the "purpose" line are intentionally left out of the public copy
to keep each card to a couple of lines. Generations Battle uses a plain-language
description instead of the Format/Age label pair, since "teacher and student
battle side by side" reads clearer than "2v2 / 10+ yr gap" for that format.
Generations Battle also carries a short maroon-tinted `.battle-note` between
the format line and the prize band, flagging a hard eligibility requirement:
every teacher/student pair must confirm their mentorship relationship via the
mentorship form (`https://www.surveymonkey.com/r/legacygenerations`) to be
eligible to battle. No other battle card has this note.

- **Generations Battle** — Teacher and student battle side by side (minimum
  10-year age gap per duo). Required: every pair must confirm their
  mentorship relationship via the mentorship form to be eligible to battle.
  *Prize: $2,500 cash: $1,200 winner · $500 second · $200 top 4 · $100 top 8.*
- **Youth Cypher Battle** — Format: 1v1. Age: Under 19.
  *Prize: Youth is the Future Camp entry + flight to Outbreak Europe, July 2027
  (flight, accommodation &amp; entry all covered, Slovakia). Site copy shows
  both the Outbreak Europe and Youth is the Future Camp logos side by side
  next to this prize.*
- **Pro Cypher Battle** — Format: 1v1. Age: 19+.
  *Prize: flight to Outbreak Europe, July 2027 (trip, entry &amp; accommodation,
  Slovakia).*

Legacy Exchanges is a showcase, not a competitive battle format, it lives in "The Festival"
copy, not the Battles section: *Curated battle conversations, Canadian breakers vs
international guests, built to inspire across generations.*

## 3. Ticket packages

*Competitors and Audience are door prices (walk-up, day-of); Workshops are
advance, Eventbrite-only prices. Early bird tickets
(no "super early bird" tier — just early bird) are on Eventbrite now, in
limited quantities for a limited time — site copy calls this out with a
"Limited time" badge in the tickets section lede, again as a bold
gold-highlighted line under the ticket list ("⏳ Early bird tickets are
limited and going fast — get yours on Eventbrite now."), once more in the
closing CTA section ("Early bird tickets are limited and going fast — grab
yours on Eventbrite now and claim your battle spot."), and now also as a small
"Early Bird" badge directly on every "Get Tickets" button site-wide (header,
hero, tickets section, schedule section, closing CTA).*

The closing CTA band (`.cta-final`, bottom of the site, "Lock In Your Spot")
now groups its buttons under two small uppercase `.cta-group-label` dividers
so it's clear which day each covers: "Sat · Battle Day" over "Register to
Battle" and "Get Tickets", and "Sun · Workshops & Panels" over a new "Get
Workshop Tickets" button linking to
`https://legacyworkshopsandpanel.eventbrite.ca`.

Site shows these as a single compact list (`.ticket-list`), not individual
cards with their own buttons, one "Get Tickets" button at the bottom links to
Eventbrite for Battle Day (Workshops and panels are a separate ticket, see
below). The list is split into two labelled groups (`.ticket-group-label`,
small uppercase gold dividers) so it's clear which rows a given day's
tickets cover: "Sat · Battle Day" (Competitors, Audience, Kids) and "Sun ·
Workshops" (Workshops). A one-line caption under the "Get Tickets" button
spells out exactly what it covers: "For Battle Day (Sat) tickets.
Sunday-only workshop tickets and free panel registration are below ↓" —
pointing at the separate workshop-callout box. The Full Festival Pass
bundle tier was removed from the site entirely (was $40 for both workshops
+ Battle Day) — every ticket is now bought separately per day.

| Package | Price | Includes |
|---|---|---|
| Competitors | $20, door price | Battle Day entry for competitors |
| Audience | $25, door price | Battle Day entry for spectators |
| Kids (under 10) | $5, door price | Battle Day entry for kids under 10 |
| Workshops | $20 each | Separate ticket. Book 1–2, or 2 for $30 |

**Workshops and panels are on a separate Eventbrite page from the main
Battle Day ticket.** Below the main ticket list/button, a compact "Sunday:
Panels & Workshops" callout (`.workshop-callout`) covers both in one
minimal box: a plain heading (no badge), two background-removed cutout rows
(`.instructor-duo`, each with a small `.cta-group-label` above it): first
"Panelists" (labelled "more to be confirmed soon") — Lazylegz ("Each One
Teach One" panel) and Phil Wizard ("Building Breaking Careers" panel), both
with background-removed cutout photos and a short caption ("Mentors &
Parents" / "Breaking Careers") — then "Workshop instructors" — Ronnie and
Puzzles, standing side by side with their name and topic (Ronnie: "Workshop
1: Creativity", Puzzles: "Workshop 2: Foundation to Style") — the venue
(Unity Studio, 1560 Yonge St Suite 204, Toronto, wheelchair accessible), a
single five-line list of all five slots (10–11 AM Doors, cyphers &
networking (free), 11 AM–12:15 PM Panel: Each One Teach One: Mentors,
Parents & the Legacy We Leave (Lazylegz, free), 12:15–1:30 PM Panel:
Building Breaking Careers: Skills, Mindsets & Pathways (Phil Wizard, free),
1:30–3:00 PM Workshop 1: Creativity (Ronnie), 3:00–4:30 PM Workshop 2:
Foundation to Style (Puzzles)) — full titles here match the main Schedule
section below, but without the longer descriptions (kept to a one-line
list to stay minimal) — one price line ("Panels free · Workshops $20 each, or 2 for
$30"), a clarifying note that panels are free but still ticketed ("Panels
are free, but you still need a ticket — tap below to register."), and a
single "Register & Get Tickets" button linking to
`https://legacyworkshopsandpanel.eventbrite.ca` (the same Eventbrite page
covers both, so one button replaces the previous two). Deliberately terse
— this box had grown text-heavy with duplicated copy and two near-identical
buttons, so it was trimmed to the minimum needed to register or buy.

## 4. Reusable prompts

**Instagram announcement post:**
> Write an Instagram caption (max 150 words, high energy, no hashtag spam — 5 hashtags max)
> announcing Legacy Jam 2026, Oct 24–25 in Toronto. Lead with "winners fly to Outbreak
> Europe 2027". Mention the Generations Battle (teacher × student 2v2), early-bird tickets
> on Eventbrite, and the tagline "Cyphers / Culture / Community". End with a call to
> register to battle — link in bio.

**Eventbrite listing description:**
> Write an Eventbrite event description for Legacy Jam 2026 using the elevator pitch,
> ticket table, schedule and battle formats in this file. Structure: 2-sentence hook,
> what's included per ticket tier, day-by-day schedule, battle formats with prizes,
> accessibility note, and travel info (out-of-town guests should email us and we'll
> help welcome them to the city; Generations Partners get an optional pre-booked
> airport shuttle — limited spots, book soon).

**Sponsor outreach email:**
> Write a 200-word sponsorship email for Legacy Jam 2026. Emphasize: intergenerational
> mandate (Generations Battle, youth prizes), international reach (Outbreak Europe / The
> Legits media partnership), existing funder (Toronto Arts Council) and academic partner
> (Sheridan College), and audience (dancers + families + hip-hop community in Toronto).
> Ask for a 20-minute call.

**Hero/poster image (for a designer or image model):**
> Elegant gold script wordmark "Legacy" with "— JAM —" in letter-spaced sans-serif beneath,
> on deep navy background, vintage-classy hip-hop aesthetic, subtle warm glow, palette:
> navy #0e1420, cream #f4e9cf, antique gold #e4c73d, deep maroon #6e2c24. No photos of
> people; typography-led; leave lower third clear for date and CTA text.

## 5. Schedule (canonical)

Site displays a "⏱️ Battles run on time — don't be late!" callout right under the
Schedule heading, above the day grid, followed by a short "Times may change —
check back for updates" hint.

**Fri Oct 23 — Welcome Jam** · Collective, 389 Spadina Ave, Toronto · 4–10 PM
Free, no registration required — just show up. Family & youth friendly. Kids
under 14 must be accompanied by a guardian at all times (site copy states
both of these right at the top of the Friday card, above the schedule list).
Two schedule lines, both 4–10 PM, each led with a pronounced uppercase
`.event-tag` label matching the visual weight of the day's `.day-label`:
**Welcome Jam** (cyphers, music & good vibes) and **Graffiti Workshops**
(open & youth sessions). No competitive battles, just a low-key kickoff to
meet people before Battle Day. The Collective logo (`.logo-row`, same asset
used under Program partners) appears at the bottom of the card since
Collective is the venue.

**Sat Oct 24 — Battle Day** · 918 Bathurst St (not wheelchair accessible) · 12–7:30 PM
12:00 arrive/register/cyphers → 1:00 Pro & Youth cypher prelims (2 circles, 1 hr) → 2:00
Generations prelims (1 rd, 1.5 hr) → 3:30 Legacy Exchange: Riko vs Konatsu (15 min) → 3:45 Breaking
Judges Showcase (15 min) → 4:00 Generations top 16 (1 rd)
→ 4:30 Pro & Youth top 8 (2 rds) → 5:00 Generations top 8 (1 rd) → 5:30 Legacy Exchange: East vs West Coast Youth Battle →
5:45 Pro & Youth top 4 (2 rds) → 6:15 Generations top 4 (2 rds) → 6:30 Pro & Youth finals
(3 rds) → 7:00 Generations final (2 rds) → 7:30 awards

**Children's Hip Hop Zone** — 1:00–6:00 PM, basement, 918 Bathurst St, ages 5–11.
Beginner moves, breaker-name & art name tag making, art stations, a hip hop
scavenger hunt & a mini kids' cypher. Parents must accompany their children at
all times.

**Legacy Party (19+)** — 9:00 PM, separate event, different venue (TODO: confirm
address before launch). Called out on the site as its own thing, not part of the
Battle Day timeline/venue.

*Flow rationale: youth battles finish early so families can leave before evening; the Pro
final closes the day at peak energy; the two Legacy Exchange battles are spread out as
palate-cleansers between tournament rounds. Only 2 Legacy Exchange battles this year (down
from 3 exhibitions in an earlier draft): Riko vs Konatsu, and an East vs West Coast Youth
Battle. A 15-minute Breaking Judges Showcase was added right after the Riko vs Konatsu
showcase (3:45 PM), giving both back-to-back showcases a matching 15-minute slot before
Generations top 16 resumes at 4:00.*

**Sun Oct 25 — Workshops & Panels** · Unity Studio, 1560 Yonge St Suite 204 (wheelchair accessible) · 10 AM–4:30 PM
Free block, 10 AM–1:30 PM: 10:00–11:00 cyphers (community) → 11:00–12:15 Panel Discussion:
"Each One Teach One: Mentors, Parents & the Legacy We Leave" (site `.sched-desc`: "Breakers
on teaching, mentoring & parenting — passing down skills, confidence & values. With
Lazylegz (Luca Patuelli).") → 12:15–1:30 Panel Discussion: "Building Breaking Careers:
Skills, Mindsets & Pathways" (site `.sched-desc`: "Breakers on building careers, businesses
& projects through breaking. With Phil Wizard (Olympic gold medalist), more TBA."). Both
panels are 1.25 hr each; cyphers open the free block, then run straight into the panels
with no bridging gap, ending right as the paid workshops start at 1:30.

*Official full panel descriptions (client-provided, used for Eventbrite/press — the
on-site `.sched-desc` above is a shortened version to keep the schedule compact):*
> **Each One Teach One: Mentors, Parents & the Legacy We Leave** — Breakers share personal
> stories about their experiences as teachers, mentors, and parents. Panelists explore
> raising their own kids, passing on what they've learned, and helping the next generation
> build skills, confidence, and strong values through breaking. Panelist: Lazylegz (Luca
> Patuelli).
>
> **Building Breaking Careers: Skills, Mindsets & Pathways** — Breakers who have built
> long-standing careers share how they've developed careers, businesses, and projects
> through breaking and in related fields. Panelists explore how they've made a living, the
> challenges they've faced, and how skills developed through breaking have helped them
> succeed across different career paths. Panelists: Phil Wizard (Olympic Gold Medalist),
> additional panelists TBA.
Paid workshops, 1:30–4:30 PM: 1:30–3:00 Workshop 1: Creativity, taught by Ronnie (Full Force,
SuperCr3w, 7 Commandoz, SuperWockeez, District Arts) → 3:00–4:30 Workshop 2: From Foundation
to Style, taught by Puzzles (Supernaturalz, Nooma Space Academy). Each workshop is 1.5 hr,
with the theme in the slot title and instructor credit shown as a `.sched-desc` sub-line
underneath (matching the panel sub-line pattern). $20 each workshop, or 2 for $30.
The Unity Charity logo (`.logo-row`, linked to unitycharity.com, same asset used under
Program partners) appears at the bottom of the card since Unity Studio is the venue.

*Cyphers and both panels are free and open to everyone; only the 2 workshops require a
ticket. Site copy calls out "(free)" next to each Sunday-morning schedule item and adds a
note under the list: "Cyphers & panels (10 AM–1:30 PM) are free. Workshops: $20 each, or 2
for $30." Same pricing repeated in the Tickets & Passes section (both the Workshops row
hint "or 2 for $30" and the paragraph below the ticket list). Each panel's full title
appears both in the Tickets section's compact list and under its title in the main
Schedule section; the `.sched-desc` sub-line there is a tightened one-sentence summary
(not the client's full verbatim description — see "Official full panel descriptions"
above for that) so the schedule stays compact, with the confirmed panelist(s) credited
in the same sentence; the `.workshop-callout` ticket box's hint text next to each panel
name also carries the panelist's name.*

## 6. Crew & volunteering

**MEC Crew bio (short):**
> MEC Crew is breakers, DJs and organizers working for and with the community —
> decades on the floor between them, battling, judging, teaching and building
> events. Breaking, DJing, hosting, teaching, visual art: they live the elements,
> and still show up for the cypher for the love of hip hop culture, breaking and
> building future generations.

**Organizing team (on the site, collapsed behind a "Meet the organizing team"
`<details>` dropdown so the About section stays short by default, one paragraph
per person). Pulled from the Canada Council / OAC grant crew bios source doc for
accuracy, condensed to 3–4 sentences each:**

- **Piecez** (Michael Prosserman): breaking since 1999, judged battles and taught
  workshops across Canada, Europe and Asia (Canadian Arctic to Japan and Hong
  Kong). 26 international competition wins; certified Breaking Judge and Head
  Judge with the World DanceSport Federation; judged the World Games and WDSF
  World Breaking Championships. Founder of Unity Charity (reached 250,000+ youth
  across Canada); bestselling author of *Building Unity*.
- **Boobjester** (Roberto Veruela Jr.): repping Winnipeg since 1994, member of
  Dangerous Goods Crew, Maximum Efficiency Crew and the Wintor Massiv Artist
  Collective. Organized major events (Red Bull BC One Canada, Red Bull Dance
  Your Style); Absolute Canadian B-boy Award, 2008; certified WDSF judge. Now
  National Program Director at Unity Charity.
- **B Bad** (Andel James): b-boy since 1999, DJing since 2010, blending hip hop,
  R&B, funk, breaks and soul for battles and cyphers. Performed at Red Bull BC
  One, Freestyle Session, Breaking Canada, The Notorious I.B.E. Youth work with
  Unity Charity since 2007; founded the 2U4U collective in 2017.
- **Switch B** (Adrian Bernard): repping Floor Assassins Militia and Maximum
  Efficiency Crew, 20+ years competing, 50+ competition wins (Skillz-O-Meter 5,
  2015). Represented Canada internationally (Seoul); Canadian Olympic breaking
  color commentator with CBC, 2024 Summer Olympics. Co-created The Breaking
  Draft, 2019 (Toronto and Vancouver).
- **MEDÊIO** (Rei Misiri): originally from Tirana, Albania, came up as a breaker
  in Canada (15+ first-place titles, Notorious IBE Netherlands) before moving
  into calligraphy and visual art. Still active as a judge/panelist/mentor
  (Yukon Cypher Fest, etc.). Visual art practice spans New York, Miami, Zurich,
  Barcelona, Los Angeles, with clients including Bloomingdale's, Porsche and
  Samsung.

*Full source bios (much more detail available — judged events, discography, awards,
exhibitions) are on file; the above is condensed to match the site's existing length.*

**Volunteer CTA:** "Apply to volunteer for Legacy Jam" — lives in its own
"Volunteer With Us" section right after Schedule, next to the media
pass request button. Links to `volunteer.html`, a built-in application form
that submits via FormSubmit to info@legacyjam.com (name, email, 19+, do you
drive, car access for the weekend, which volunteer roles — drivers,
tech/production, photography/videography, registration & check-in,
hospitality, setup & teardown, DJ/sound support — availability across Sat
Battle Day 12–7:30 PM, Sat after party 9 PM+, and Sun Workshops & Panels
10 AM–4:30 PM, plus a waiver & release of liability agreement).

**Media pass CTA:** "Request a Media Pass" — sits beside the volunteer button
in the same "Volunteer With Us" section, a plain `mailto:` link to
info@legacyjam.com with a short pre-filled body (name, outlet/handle, photo or
video, which day(s)).

**Generations Partner CTA:** "Become a Generations Partner" — links to
`generations-partner.html`, a built-in application form that submits via
FormSubmit to info@legacyjam.com (organization name, contact info, entering
the Generations Battle?, number of attendees, interested in optional
benefits?).

Confirmed Generations Partner logo, labelled with a small "Generations
Partners" title (`.partner-group`, matching the Funders/Academic
Partner/Media partners labels in the Partners & Funders section) right above
its own `.logo-row` below the CTA button: Now or Never Crew (links to
https://www.instagram.com/nowornevercrew/), 519 School of Hip Hop (logo
recoloured from its original white/light-grey outline art to dark navy, so
it reads against the white `.logo-row` card background), and The Heart (no
link provided). A second `.logo-row` right below
that stays `hidden` until the older, unconfirmed partners (BRKN Québec, The
Flava Factory, ABA, The Spot Arts Community, Breaking Canada, Tuff)
reconfirm for 2026.

## 7. Voice & style rules

- Simple words, short sentences. An excited 14-year-old and their parent should both get it.
- Lead with what the reader gets (prizes, experience), then details.
- "Breaking" (not "breakdancing"). "Cypher" spelled with a y.
- Always pair a claim with an action: every section ends in a link (tickets, register, follow).
- Accessibility first: real link text (never "click here"), alt text on every image,
  colour contrast ≥ 4.5:1 (the palette in `style.css` passes).
