# Lyra Onboarding Deck — "The Run" (Souls-like theme)

> Rebuild of the one-page scroll site. Replaces the Claude-Maxxing / Minecraft content with an **expectation-setting** narrative for Lyra engineers about to go onto (or recently onto) a client.
>
> Source material: `presentation_info.md` (raw Lunch & Learn notes from Xavier, Eoin, Alfie, Falco, Anh).
> Structural reference: `index.html` (the existing scroll deck — reuse its components verbatim).
>
> **Status:** these notes are reconciled to the **shipped `index.html`** — the deck went out under the title **"The Run,"** and the Elden-Ring-specific proper nouns were toned down to universal gaming language (see Locked decisions). Headings, motifs, and on-screen copy below match what's actually rendered.

> **Locked decisions:**
> - **Theme:** **Soulslike — front-loaded difficulty as the spine.** Shipped under the title **"The Run."** Why it won over WoW/OSRS: the *difficulty curve is front-loaded* — the opening wall (the trial) is the hardest part, then it opens up and becomes sustainable. That's the exact shape of a Lyra run. (WoW/OSRS get easier→harder, which is backwards.)
> - **As shipped:** we kept the *universal* gaming megamemes everyone knows — git gud, the campfire, the boss health bar, the stamina bar, the fog, "the run" — and **dropped the Elden-Ring-specific proper nouns** for plainer gaming language: Tarnished → *Player One / "don't be an NPC"*, Margit → *"the first wall"*, `YOU DIED` → `GAME OVER`, `AN INVADER HAS APPEARED` → *"the village is under attack"*, Praise the Sun → *"party morale / +10 MORALE"*, `GREAT ENEMY FELLED` → `VICTORY`. Swapping back to harder Souls naming later is trivial.
> - **Tone:** Full send on memes.
> - **Length:** ~15 min. Slides tagged **[CORE]** (the essential 12) vs **[IF TIME]** / **[APPENDIX]**.
> - **Attribution:** Keep individual names on screen (small bylines — Xavier, Alfie, Falco).
> - **Dropped:** the "founder = the Host who summoned you" lore framing. Founder-empathy *content* stays (it's a spine-rule); we just present it straight.
> - **Art:** the build uses **real photo backdrops** (campfire, lava, fog, ruins, twilight); the death/victory frames are pure-typography motifs (`GAME OVER`, `VICTORY`, message signs) recreated in CSS so we're never blocked. (See §5.)

---

## 0. The brief, distilled

**Who this is for:** Lyra engineers. Australian, contracted out to US (mostly SV) startups. Mostly very young — first or second job. Smart but inexperienced. About to hit, or in the middle of, a **2-week trial** where the client decides if they keep them.

**What leadership actually wants the deck to land (the whole thesis):**
> **Happy clients + a sustainable workload for you.**

Everything resolves into two questions:
1. **What do clients expect from you?** (the bulk of the deck — the pillars)
2. **How do you keep your workload sustainable?** (woven through, concentrated near the end)

**Tone:** mindset + perspective, not a checklist of rules. We're giving young engineers *social and psychological tools* to read situations themselves, because every client is different. Reassuring but honest — the trial is genuinely hard, and we say so.

**Three rules that blanket almost every situation (the spine of the talk):**
1. Under-promise and over-deliver.
2. First impression is everything.
3. Empathise with the founder — they're betting a chunk of their raise on a random Aussie engineer.

---

## 1. The theme: **Souls-like — "The Run"**

### Why this theme beats the others

The most important thing to match is the **difficulty curve**, and only Souls gets it right:

- A trial is **front-loaded difficulty** — the first two weeks are the hardest part. Once you learn to *read the client*, it becomes manageable and sustainable.
- **Souls is the only candidate shaped like that.** The opening wall-boss (Margit, the Taurus Demon, the Gargoyles) filters more players than almost anything later. It *feels impossible* until the patterns click — then the game opens up. That's the trial, exactly: you're not bad, you just haven't learned the moveset yet.
- WoW (Tutorial Island → harder raids) and OSRS (easy lowbie → endless grind) get *easier→harder*. Backwards.

It's also the **richest meme toolkit** of the options, and the community vibe is wholesome despite the dark aesthetic: `GAME OVER`, git gud, the campfire, party morale, the troll soapstone signs. Full-send funny, not grim.

### The 1:1 mapping (the engine of the deck)

| Concept in the talk | Souls element | Why it maps |
|---|---|---|
| The Lyra engineer | **Player One** — a player with agency, not a background NPC | You shape your run; you don't shuffle around on rails like an NPC |
| The 2-week trial | **The first wall** — the opening boss-gate | The famous filter. Hardest because you haven't learned the patterns yet |
| Learning the client | **Learning the boss's moveset** | First tries you die; then you read it and it becomes manageable |
| The product / market problem | **The boss** you're fighting | You and the founder are on the same side, vs it |
| Working hours | **The stamina bar** | Finite. Don't empty it on every swing (burnout) |
| Intensity / productivity | **Patience & timing, not panic-rolling** — "git gud" | Roll at the right moment; output per hour, not flailing |
| Consistency / daily ritual | **Resting at the campfire** | Refill, save progress, repeat |
| A production fire / emergency | **"The village is under attack"** (red alarm banner) | A threat is in your world *now* — drop everything |
| Poorly-scoped / ambiguous work | **The fog wall — a new area, no map** | Scout cautiously; read the messages on the ground |
| Communication | **The orange-soapstone message system** | Players leave signs that guide each other. Good signals win |
| Mistakes | **`GAME OVER` → respawn at the checkpoint** | Every death teaches the level. Own it, go again — don't ragequit |
| Energy / vibes | **Party morale (+10)** | Be the teammate people *enjoy* having in the party |
| Understanding your work | **Knowing your build** | You know your stats/weapon; you can explain your approach |
| Going beyond your ticket | **Exploring the open world / side content** | Founding engineers don't run the main quest on rails |
| Leverage over the contract | **Leveling up; the world opening past the wall** | Clear the trial and it relaxes — more flex, more trust |

### Iconic motifs to put on screen (full send)

- **`GAME OVER`** red-serif death-screen treatment → the mistakes slide.
- **Boss health bar** with a name → hero (`THE CAMPAIGN · DAY ONE`, full), the wall (`THE FIRST BOSS · THE TRIAL · 2 WEEKS`), close (`THE FIRST WALL · FELLED`, drained to zero).
- **Orange-soapstone messages** ("roadbump ahead, here's a new ETA", "works on my machine ¯\\_(ツ)_/¯", "be wary of tardiness") → the comms slide + a recurring gag on tips slides.
- **"The village is under attack"** red alarm banner → the fires slide.
- **Campfire** — a real bonfire photo (`bonfire.jpg`) → consistency.
- **`+10 MORALE`** praise-glow → vibes / party-morale.
- **Fog** — a `fog-forest.jpg` backdrop → ambiguity (and the map preview).
- **`VICTORY`** boss-defeat screen → the close.
- **Stamina bar** → working hours.

---

## 2. The deck, slide by slide

Format for each slide:
- **[CORE]** / **[IF TIME]** / **[APPENDIX]** — runtime priority. The 12 `[CORE]` slides are the ~15-min talk; the rest enrich it / serve as the leave-behind.
- **Thrust** — the one thing this slide must make land.
- **Talking points** — what we *say* (bylines where the advice is personal).
- **ON SCREEN** — what's literally rendered (heading, component, motif). Headings follow the house style: short declarative, one *italic* emphasis word.

Reuse map → component from `index.html`: `.hero`, `.flow-diagram`, `.cove-acronym` (frameworks/acronyms), `.stat-grid`, `.portal-grid`, `.phase-row`, `.code-block`, `.big-quote` (transitions), `.run-map` (the overview/preview grid).

---

### SLIDE 00 — HERO · "The Run" · **[CORE]**
**Style:** `.hero` (dark). Boss-health-bar device.

- **Thrust:** Set the tone instantly — every client is a run; the first wall (the trial) is the hardest part, and we're going to teach you how to clear it.
- **Talking points:**
  - This talk came from real feedback: people genuinely didn't know what was expected of them on a client.
  - We're going to fix that today — clearly and honestly, across the *whole* run, not just week one.
- **ON SCREEN:**
  - Kicker: `LYRA ENGINEERING · WORKING ON A CLIENT`.
  - H1: **The Run.**
  - Sub: *Your whole time on a client, start to endgame — what clients expect from a Lyra engineer, and how to keep your workload sustainable. The first wall is your trial; the run is everything after.*
  - Device: a boss health bar near the bottom — `THE CAMPAIGN · DAY ONE`, full.
  - Lyra logo top-left (already in header).

---

### SLIDE 00b — THE MAP · "The whole *run*." (preview / abstract) · **[CORE]**
**Style:** `.dark` with a faint `fog-forest.jpg` backdrop. New `.run-map` component. *No* on-screen `.section-number` — it uses a kicker like the chapter-break slides (it's the agenda, not a chapter).

- **Thrust:** Hand the room the whole shape up front — one screen that previews every chapter, so they can see where the run is going before we walk it.
- **Talking points:**
  - Quick map before we start: here's the entire run on one screen.
  - The *intensity* peaks at the first wall (the trial); the *expectations* run the whole contract.
  - We'll take these in order — skim it now, then we go chapter by chapter.
- **ON SCREEN:**
  - Kicker: `THE MAP · THE WHOLE RUN AT A GLANCE`.
  - H2: The whole *run.*
  - `.run-map`: a 2-column quest log of all **19 chapters, numbered 01–19** (auto via a CSS counter), each a title + a punchy one-liner. Flows **down the left column (01–10), then down the right (11–19)**.
  - The map's numbers line up 1:1 with each slide's on-screen `.section-number`, so the audience can orient ("we're on 07 now").

---

### SLIDE 01 — "Two *win conditions*." · **[CORE]**
**Style:** `.light`, number `01`.

- **Thrust:** Reframe everything down to leadership's actual goal so the rest of the deck has a spine.
- **Talking points:**
  - Strip away the noise. Lyra wants exactly two things: **happy clients** and **a workload that doesn't destroy you.** Both. Not one.
  - A miserable engineer with a happy client isn't a win. Neither is the reverse.
  - So there are really only two questions: **what do clients expect from you?** (most of today, with tips) and **how do you stay sustainable?** (woven through, hit hard near the end).
- **ON SCREEN:**
  - H2: Two *win conditions.*
  - `.flow-diagram`: `Happy client` `+` `Sustainable workload` `=` `You stay in the party` (last node gold / "win").
  - `.phase-row` (2 blocks): `1 · What clients expect` (*the pillars + how to meet them*) · `2 · Staying sustainable` (*protect your stamina bar*).
  - Closing note: *Some of what follows peaks during your two-week trial — we'll flag those moments. Most of it is just how you work on a client, every week.*

---

### SLIDE 02 — "Don't be an *NPC*." (Founding engineer — the identity) · **[CORE]**
**Style:** `.dark`, number `02`. **The most important framing slide.**

- **Thrust:** Lyra sells you as a founding engineer. Internalise what that means — the whole bar is set by it.
- **Talking points:**
  - Lyra sells you as product-heavy, mid-to-senior talent. At an early startup that makes you a *founding engineer*; at a bigger one, same flavour.
  - Founding engineers don't move tickets To-Do → Doing → Done — that's NPC behaviour, running a script on rails. You have agency.
  - From the founder's POV, a founding engineer is: smart, locked in, knows their craft, understands the business + market, takes initiative, takes ownership, pushes the *whole company* to do better — not just their own tickets.
  - Product sense. No handholding. Works harder than the average eng — and is trusted because of it.
- **ON SCREEN:**
  - H2: Don't be an *NPC.*
  - Motif: `NPC` (struck through) → `PLAYER ONE`. (script-on-rails vs player-with-agency.)
  - `.portal-grid` (2×2) "What a founding engineer actually is":
    - **Owns outcomes** — not tickets. Pushes the company forward, not just their lane.
    - **Knows the terrain** — the industry, the major players, the market the startup fights in.
    - **Takes initiative** — contributes product ideas, doesn't wait to be told.
    - **No handholding** — works harder than average, trusted because of it.

---

### SLIDE 03 — "Stay *plugged in*." (founding-engineer homework) · **[IF TIME]**
**Style:** `.light`, number `03`.

- **Thrust:** Concrete habits that *signal* founding-engineer behaviour — cheap, hugely valued.
- **Talking points:**
  - Subscribe to general tech newsletters (e.g. ai.engineer) and — crucially — your client's **competitors'** newsletters/LinkedIn.
  - **SHARE what you find.** Even if the founder already thought of it, it proves you think deeply about their business and genuinely care. Highest-ROI thing you can do.
- **ON SCREEN:**
  - H2: Stay *plugged in.*
  - `.code-block` "loadout / subscriptions":
    - `> subscribe: ai.engineer/newsletter`
    - `> subscribe: <client's competitors>`
    - `> follow: competitors on LinkedIn / X`
    - `> action: SHARE findings + ideas in your updates`
  - Pull-quote: *"Sharing an idea the founder already had still wins — it proves you're thinking about their business, not just your ticket."*

---

### SLIDE 04 — "The first *wall*." (the trial, named honestly) · **[CORE]**
**Style:** `.accent-bg` (oxblood), number `04`. Chapter-break for the trial — kicker, inline boss bar, and a 3-phase row.

- **Thrust:** Name the trial honestly. It's going to be hard. That's the design, not a bug.
- **Talking points:**
  - The trial is ~2 weeks. The client is sussing out how you work, whether you fit.
  - Be honest with yourself: **most trials are brutal.** This is the founder betting a chunk of their raise on a random Aussie engineer. Expect it to be hard.
  - The hard part: you're *setting* expectations and *meeting* them at the same time.
  - But — clear the wall and the rest of the contract almost never stays this intense.
- **ON SCREEN:**
  - Kicker: `LEVEL 1 · THE TARGETED BIT`.
  - H2: The first *wall.*
  - Copy: *Your first two weeks are a trial — the opening boss. The client is sussing out how you work. Most trials are brutal: the founder is betting a chunk of their raise on a random Aussie engineer.*
  - Inline boss bar: `THE FIRST BOSS · THE TRIAL · 2 WEEKS`.
  - `.phase-row` (3 blocks): `1 · The Trial` (*~2 weeks · brutal · prove yourself*) · `2 · Settling in` (*earn leverage · the pace eases*) · `3 · Trusted` (*flexible · shape the work*).
  - Closing: *The intensity peaks in the trial, but the expectations below run the whole contract. Clear the wall and the run opens up.*

---

### SLIDE 05 — "Empathise with the *founder*." · **[CORE]**
**Style:** `.light`, number `05`. *(Founder-empathy content — presented straight, no summoning lore.)*

- **Thrust:** The single most useful lens — feel the founder's stakes and you'll make the right call 90% of the time.
- **Talking points:**
  - The founder usually took a pay cut to do this. They're spending tens of thousands of dollars on *you*. They answer to investors and deadlines.
  - These guys are unemployed, have a few hundred thousand (which really isn't much) to spend.
  - Treat it like a uni group project, what would your random international student that lives overseas do.
  - Communicate actively, every single thing. Over communicate.
  - Be nice and be proactive with your work
  - A lot of the stuff will be explained in future slides how to deal with that.
- **ON SCREEN:**
  - H2: Empathise with the *founder.*
  - Copy carries it: the founder took a pay cut, is spending tens of thousands on *you*, and answers to investors + deadlines. *(The old `.stat-grid` — `$10Ks` / `Pay cut` / `Investors` — was cut; it read as filler and the paragraph already lands the point.)*
  - Theme line: *It's their run. Play like a teammate who's there to win it — act how you'd want your engineer to act if it were your money and your dream.*

---

### SECTION BREAK — "What the client expects" *(optional `.highlight-bg` big-quote: **"Now — what they're actually watching for."**)* · **[IF TIME]**

---

### SLIDE 06 — "Mind your *stamina*." (Working hours) · **[CORE]**
**Style:** `.dark`, number `06`.

- **Thrust:** Hours are about *output and reliability*, not clocking time — but a 50hr contract is a visible promise.
- **Talking points:**
  - Some weeks you'll work over your contracted 40/50 — normal for professional work. But we don't want *consistent* overtime; that's a sustainability failure.
  - On a 50hr contract the client expects *more* output (quantity + quality) than a 40hr eng. Same-or-less is *worse* — "especially considering they're on 50."
  - From the client's POV you're *always* doing your contracted hours. Own that frame.
- **ON SCREEN:**
  - H2: Mind your *stamina.*
  - `.flow-diagram`: `50hr contract` `→` `client expects MORE` `→` `same-or-less = worse than 40hr`.
  - Hints (`.portal-grid` 2-up):
    - **Same start & end times** — consistency reads as reliability.
    - **Publish your hours** — tell the client when you're online/contactable; Slack notifications set for it (muted is fine).

---

### SLIDE 07 — "Patience over *panic*." (Work intensity) · **[IF TIME]**
*(Can fold into Slide 06 if tight.)*
**Style:** `.light`, number `07`.

- **Thrust:** More hours ≠ better engineer. Intensity and focus inside the hours is the whole game.
- **Talking points:**
  - 10x engineers don't work 400hr weeks — they often work normal hours. **Productivity is king: output per hour.** Panic-rolling (flailing more hours) gets you killed; patience and timing clear the fight.
  - Contracts are calibrated so a focused 9–5 / 8–6 is enough.
  - If Slack shreds your focus: use DND / Focus (F6) for deep-work blocks. New Slack feature mutes *per workspace*. Most US clients are offline from ~11am our time, so it's usually safe after. *(byline: Xavier runs DND most of the day, checks in periodically.)* **Keep communicating as needed** — DND is for focus, not going dark.
- **ON SCREEN:**
  - H2: Patience over *panic.*
  - `.stat-grid`: `10x` (*≠ 400hr weeks*) · `1hr` (*the unit that matters*) · `F6` (*DND for deep work*).
  - Motif: **git gud** (read the fight; stop panic-rolling).
  - Caveat: *DND ≠ MIA. Stay reachable.*

---

### SLIDE 08 — "Under-promise. *Over-deliver*." (Managing workload — sustainability core) · **[CORE]**
**Style:** `.dark`, number `08`.

- **Thrust:** The estimation discipline that protects you *and* impresses clients.
- **Talking points:**
  - If you regularly work past your hours, the fix usually starts at *estimation*. Don't oversell — it only ends in disappointment.
  - A good timeline = your honest estimate **+ a buffer**. *(byline: Xavier — the last 20% takes 80% of the time, so add 50–60%. Worst case you finish early.)*
  - Counterintuitive to *propose a slower timeline* — but beating your own deadline reads as far more valuable than hitting an "optimal" average-engineer estimate. Setback → trust-builder.
  - During the trial you'll likely work way over. That's the hardest stretch. Pass it and you've *earned leverage* — apply time-management strategies, ask for workflow changes; clients are far more flexible once they've invested in you. (Don't be an ass — they can still replace a difficult eng.)
- **ON SCREEN:**
  - H2: Under-promise. *Over-deliver.*
  - `.code-block` "estimation rule":
    - `honest_estimate = how long you really think`
    - `quote = honest_estimate * 1.5   # last 20% eats 80% of the time`
    - `# finishing early > hitting "optimal" > slipping a deadline`
  - Sidebar: *Trial = the hard yards. Clear the wall, earn the leverage to lighten the load.*

---

### SLIDE 09 — "Leave a *message*." (Communication > code) · **[CORE]**
**Style:** `.light`, number `09`. *(Native Souls fit — the orange-soapstone message system.)*

- **Thrust:** Output is *perceived through communication*, not commit count. The signal you leave is the work.
- **Talking points:**
  - Communication is seen more than code. Don't measure yourself by lines pushed.
  - Planning, scoping, discussing take more time than typing code now — that's normal. Put it in your updates; don't stress about a quiet commit graph if you're communicating a lot.
  - When you hit a roadbump: update the client ASAP with explanation + evidence, **and immediately give a new (generous) ETA.** Converts a trust dip into "reliable, finishes ahead."
  - In co-op, the players who call things out keep the whole party alive. Same here — **good signals win.**
- **ON SCREEN:**
  - H2: Leave a *message.*
  - Motif: two soapstone signs — *"heads up — roadbump ahead, here's a new ETA"* vs a troll sign *"works on my machine ¯\\_(ツ)_/¯."*
  - `.flow-diagram`: `Hit a roadbump` `→` `Tell client + evidence` `→` `New generous ETA` `→` `Trust ↑` (gold / "win").
  - Pull-quote: *"A quiet commit graph + loud communication beats loud commits + silence. Every time."*

---

### SLIDE 10 — "Party *morale*." (Energy / Vibes) · **[IF TIME]**
**Style:** `.dark`, number `10`.

- **Thrust:** People keep around engineers they *enjoy* working with. Be that, and don't be intimidated into a grey background character.
- **Talking points:**
  - Be positive and fun to work with. Talk about your weekend, your hobbies; ask what *they're* up to. **Be yourself — don't be intimidated.**
  - Be interested in the business: ask how customers find the product, give ideas outside your scope, express interest in parts of the company you assume you'll never touch. Worst case, nothing happens.
  - It *shows* when you rolled out of bed / slept at 4am into a meeting.
  - Control your emotions — frustration leaks in meetings. Fine to *name* that something's frustrating; it's about *tone*. *(byline: take a few hours / a day to cool off before reacting.)*
- **ON SCREEN:**
  - H2: Party *morale.*
  - Motif: a **`+10 MORALE`** praise-glow (the engineer people enjoy having around).
  - `.portal-grid` (2×2):
    - **Be a person** — weekend, hobbies, ask about theirs. Be yourself.
    - **Be curious** — about customers, product, parts of the business "above your pay grade."
    - **Show up awake** — they can tell when you didn't sleep.
    - **Keep your cool** — frustration is fine to *name*, not to *vent*. Cool off first.

---

### SLIDE 11 — "Rest at the *campfire*." (Consistency) · **[IF TIME]**
**Style:** `.light`, number `11`.

- **Thrust:** A consistent engineer beats a spiky one. Build a ritual that keeps you centred.
- **Talking points:**
  - A consistent engineer is worth more than a variable one, even if the variable one has higher peaks.
  - *(byline: Xavier runs a **daily checklist** and a **weekly checklist** — it catches the things you'd almost skip and keeps you centred.)* If consistency is hard for you, this is the fix.
- **ON SCREEN:**
  - H2: Rest at the *campfire.*
  - Visual: a real **campfire photo** (`bonfire.jpg`), desaturated.
  - `.code-block` "the ritual":
    - `daily: standup ready · review inbox · re-read priorities · ship-or-update`
    - `weekly: demo progress · clean up · plan next · share a finding`
  - Line: *The campfire isn't lost time. It's why you don't lose your run.*

---

### SLIDE 12 — "Don't stand in the *fire*." (Fires / emergencies) · **[CORE]**
**Style:** `.dark` with a `lava-night.jpg` backdrop — high alarm. Number `12`.

- **Thrust:** When there's a real fire you stop everything. People genuinely don't grasp this.
- **Talking points:**
  - People don't handle fires well. Picture your house literally on fire. Are you still doing the dishes? **No. You put out the fire — or you make damn sure it's being handled.**
  - Assume a fire is hitting thousands of customers and costing tens of thousands in revenue. That's the urgency.
  - Be explicit: tell the client *"I'm dropping X and Y to handle this"* so it's clear you've reprioritised.
- **ON SCREEN:**
  - H2: Don't stand in the *fire.*
  - Banner motif: **`THE VILLAGE IS UNDER ATTACK`** (red alarm text).
  - `.flow-diagram`: `Fire detected` `→` `Drop normal work (say so)` `→` `Put it out / confirm it's handled`.
  - Line: *Washing the dishes while the house burns is not "staying on task."*

---

### SLIDE 13 — "Into the *fog*." (Dealing with ambiguity) · **[CORE]**
**Style:** `.dark`, number `13`. **The deepest content slide — Alfie's framework.**

- **Thrust:** You *will* get poorly-scoped work. Scoping it is *your* job, and there's a repeatable way.
- **Talking points:**
  - Poorly-scoped work is the default, especially when a company scales fast (tight deadlines + vague scope arrive together).
  - It's your responsibility to scope it and get stakeholders onboard — and to explain *why* their non-help makes it hard to do well.
  - *(byline: Alfie's checklist)* for any ambiguous/urgent task:
    1. **What** are we building and **why**? (context, user pain, product decisions)
    2. **Impact?** (does it solve the biggest pain; what % of users)
    3. **Urgency?** (when does the client expect it shipped)
    4. **Effort?** (how long to actually build)
    5. **Trade-offs** if the deadline's at risk (fast vs right; cut to must-haves)
    6. Realise mid-way you'll miss the agreed deadline → **escalate as early as possible**, then re-run step 5.
  - *(byline: Falco)* don't rush in half-understanding. Don't rely on Slack for urgent clarification — **propose a quick sync/call**, especially for UI work.
- **ON SCREEN:**
  - H2: Into the *fog.*
  - Visual: a fog-wall shimmer the content emerges through.
  - `.cove-acronym`-style numbered 1–6 list (reuse the big-letter component): **What · Impact · Urgency · Effort · Trade-offs · Escalate.**
  - Footer: *Urgent + unclear? Don't Slack it to death — leave a clear message, then call them. — Falco*

---

### SLIDE 14 — "Try it *solo* first." (Proactiveness) · **[IF TIME]**
**Style:** `.light`, number `14`.

- **Thrust:** Earn the right to ask for help by showing you tried.
- **Talking points:**
  - When you're stuck on something non-trivial, genuinely attempt it first — try the area solo before summoning.
  - When you *do* ask, lead with what you tried, your current understanding, *then* the question. Never make it look like you didn't put in the effort.
- **ON SCREEN:**
  - H2: Try it *solo* first.
  - `.code-block` "how to ask for help":
    - `1. what i tried: ...`
    - `2. what i think is happening: ...`
    - `3. the actual question: ...`
  - Theme line: *Scout the area before you call for backup. Never make it look like you didn't put in the effort.*

---

### SLIDE 15 — "*GAME OVER*." (You're human / owning mistakes) · **[CORE]**
**Style:** `.dark`, number `15`. **High-impact iconic slide.**

- **Thrust:** You'll make mistakes. The differentiator is *owning them instantly*. Deaths teach the pattern.
- **Talking points:**
  - You're human. You *will* mess up.
  - The move: be immediately clear — *"hey, I messed up with X — here's how I'll make sure it doesn't happen with Y."* Owning it fast is everything; people get genuinely frustrated when others *don't* fess up.
  - And: sometimes the client just isn't the right match for you. That's allowed.
- **ON SCREEN:**
  - The unmistakable **`GAME OVER`** red-serif full-bleed treatment.
  - Below: *…Continue? You respawn at the checkpoint. Every death teaches the level.*
  - `.code-block` "the owning-it template":
    - `> "I messed up X."`
    - `> "Here's the impact + the fix."`
    - `> "Here's how it won't happen with Y."`

---

### SLIDE 16 — "Know your *build*." (You're an engineer, not a vibe coder) · **[IF TIME]**
**Style:** `.light`, number `16`.

- **Thrust:** Understand your work deeply enough to defend it to technical people.
- **Talking points:**
  - You're an engineer, not a vibe coder. Understand what you built — know your build, not just which buttons you mashed.
  - Sometimes you'll explain your approach to *technical* people — be ready.
  - Regularly communicate *how* you approached a problem and what you considered. Shows you care, makes collaboration easier.
- **ON SCREEN:**
  - H2: Know your *build.*
  - `.flow-diagram`: `Understand it` `→` `Explain your approach` `→` `Easier collaboration + trust`.
  - Line: *Button-mashing clears the tutorial. It doesn't clear the boss.*

---

### SLIDE 17 — "Ways to get *kicked*." (The no-gos) · **[CORE]**
**Style:** `.dark`, number `17`.

- **Thrust:** A short, blunt list of things that actively damage you with clients.
- **Talking points:**
  - "It works on my machine, don't see the issue" — clients hate this. Don't.
  - Going MIA to "lock in." Silence reads as a problem, not focus.
  - Directly blaming the client. Even when they *are* at fault, there are professional, passive ways to make that clear. Defensive clients write you off for the rest of the contract.
  - Over-promising — promise treasure, deliver a mimic. Don't sell what you can't actually deliver.
- **ON SCREEN:**
  - H2: Ways to get *kicked.*
  - `.portal-grid` (red-bordered "debuff" cards):
    - **"Works on my machine"** — instant credibility hit.
    - **Going MIA to "lock in"** — silence ≠ focus, it reads as a problem.
    - **Blaming the client** — even when right, do it professionally or not at all.
    - **Over-promising** — promise treasure, deliver a mimic; don't sell what you can't deliver.

---

### SLIDE 18 — "The little *things*." (General tips) · **[IF TIME]**
**Style:** `.light`, number `18`.

- **Thrust:** Cheap, high-signal habits. Don't fumble the free points.
- **Talking points:**
  - Be ~1 minute early to every meeting. Tardiness *really* sets some people off and costs nothing to avoid.
  - (Bucket for small reusable tips: same hours, publish your contactable window, one-line owning of mistakes, share a finding in every update.)
- **ON SCREEN:**
  - H2: The little *things.*
  - Motif: a soapstone sign — *"be wary of tardiness."*
  - `.code-block` "free wins" ✓ checklist: `be 1 min early` · `same hours daily` · `share one finding / week` · `own mistakes in one line`.

---

### SLIDE 19 — "Boss *patterns*." (Situational playbook) · **[APPENDIX]**
**Style:** `.dark`, number `19`. *(Source notes: do the situational stuff at the end as attention drops.)*

- **Thrust:** A few concrete, recognisable situations with the move for each.
- **Talking points / ON SCREEN (`.portal-grid`, one card each):**
  - **"The task blew up past the deadline."** Don't silently tank it (makes great work look *average*, esp. to non-technical clients, and sets a brutal bar for you). Update ASAP with evidence + a *new, generous* ETA. Setback → "finishes ahead of schedule."
  - **"I'm blocked by someone else."** Pass the **blocked-potato** — ping the blocker immediately and make sure your boss can *see* it's not you they're waiting on.
  - **"Client only talks when something's broken."** Push for a sync; if hard, suggest a daily digest / short Loom. Ask for feedback on good work too — frame it as "it tells me where to keep pushing."
  - **"Unclear scope."** (links back to *Into the fog*) — scope it yourself, get stakeholders on the hook, propose a call.

---

### SLIDE 20 — CLOSE · "The run *continues*." · **[CORE]**
**Style:** `.cta-section` (gradient, `misty-twilight.jpg`), final.

- **Thrust:** Land the thesis one more time and leave them with the catharsis of clearing the trial — and the reminder that the run keeps going.
- **Talking points:**
  - Back to the two win conditions: happy client + sustainable you.
  - Under-promise, over-deliver. First impression is everything. Empathise with the founder.
  - Clear the wall and the run opens up — more leverage, more flexibility, more trust. But every client is a run; these rules hold the whole way through.
- **ON SCREEN:**
  - The **`VICTORY`** boss-defeat treatment; boss bar (`THE FIRST WALL · FELLED`) drains to zero.
  - H2: The run *continues.*
  - Recap chips: `Under-promise · Over-deliver` · `First impression is everything` · `Empathise with the founder`.
  - Closing copy: *Clear the trial and the run opens up — more leverage, flexibility, and trust. But every client is a run, and these three rules hold the whole way through: from the first wall to the endgame.*
  - CTA button → **Lyra Technologies** (`lyratechnologies.com.au`).

---

## 3. The CORE 12 (the ~15-min cut)

`00 The Run` → `The Map (the whole run at a glance)` → `01 Two win conditions` → `02 Don't be an NPC` → `04 The first wall` → `05 Empathise with the founder` → `06 Mind your stamina` → `08 Under-promise/over-deliver` → `09 Leave a message` → `12 Don't stand in the fire` → `13 Into the fog` → `15 GAME OVER` → `20 The run continues.`

Everything else is `[IF TIME]` (drop in if the room's engaged) or `[APPENDIX]` (the situational playbook — best at the tail). The full deck doubles as the leave-behind.

---

## 4. Open questions / clarifications (still need your call)

1. **Presenter split:** Bylines on the *advice* are in — do you also want a per-section "presented by" credit, or just the advice bylines?
2. **Real numbers:** Any *real* Lyra stats we could show on a stat-grid (trial pass rate, # engineers, # clients)? Real numbers hit harder than vague placeholders. *(The founder-stakes `$10Ks / Pay cut / Investors` grid was already cut for reading as filler — real numbers could earn a grid back.)*
3. **Old assets:** Strip the Minecraft / Steve-Jobs images from the repo, or leave them parked?
4. **Final CTA destination:** Real link for the closing button (Lyra handbook / Notion / Slack), or a pure mic-drop?
5. **Domain / meta:** New `<title>`, OG/Twitter tags and `og-image.png` — is there a domain this lands on (replacing `claudemaxxing.org`), or is it internal-only? (Affects whether real game screenshots are a licensing concern — see §5.)

---

## 5. Build notes (for implementation)

- `index.html` is **one self-contained file** — every component (`.flow-diagram`, `.portal-grid`, `.cove-acronym`, `.stat-grid`, `.phase-row`, `.code-block`, `.big-quote`) and all scroll/intersection JS is reusable as-is. This is a **content + copy swap**, not a rebuild.
- **Art plan (decision: real images where clean):** the build uses real photo backdrops (`bonfire.jpg`, `lava-night.jpg`, `fog-forest.jpg`, `ruins.jpg`, `misty-twilight.jpg`, `hero-ruins-fog.jpg`) for the campfire, fires, fog, trial, and close. The death/victory frames are **pure typography** (`GAME OVER`, `VICTORY`) recreated in CSS, so nothing depends on a copyrighted game asset. (If real FromSoftware screenshots ever get swapped in, that art is copyrighted — fine for an internal talk; flag it if it goes on a public domain.)
- CSS/SVG motifs in the build: a **boss health bar** component, the **`GAME OVER` / `VICTORY`** type treatments, a **soapstone message** sign, the **"village is under attack"** alarm banner, a **`+10 MORALE`** praise-glow, and the **`.run-map`** overview grid.
- Update `<head>`: `<title>`, OG/Twitter tags, `og-image.png`, and the `claudemaxxing.org` URLs → new title/domain.
- Keep the `.section-number` auto-counter, scroll-progress bar, hero letter-drop, and reveal-on-scroll observers — all carry over unchanged.
- **Numbering (current build):** every chapter carries a sequential on-screen `.section-number` **01–19** — including the three chapter-break slides that were previously unnumbered: the trial (`04`), the fires / "don't stand in the fire" slide (`12`), and `GAME OVER` (`15`). The new **`.run-map`** overview slide (right after the hero) self-numbers via a CSS counter — `counter(mapnum, decimal-leading-zero)` with `grid-auto-flow: column` so it reads down the first column then the second — so its 01–19 list always matches the slides without hand-editing. The `.section-number` count-up JS still animates the big faded corner numerals.
