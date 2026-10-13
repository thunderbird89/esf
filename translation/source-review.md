# Source review

A working list of slips in the stories, the timeline and the codex, compiled for cleanup before translation. It is not for publication; delete it when you are done.

## How to use it

- Every item has an ID and a checkbox. Tick the ones you want fixed as proposed. To fix something differently, edit its Fix line. To reject an item, delete it or write "skip" under it.
- Items marked "author decision" need your call. Write the option you want under the item.
- Bulk instructions work too: "fix every high-confidence item in Knock Knock", "everything in The Helpers except TH-12", or "all of section 3".
- Line numbers refer to the files as they are today. Edits shift later lines, so I locate each fix by its excerpt, not its number.
- Six reviewers compiled the story lists, so item layouts differ slightly between stories. Every item still gives the location, the problem and a proposed fix.

Scope: the 19 published stories, `timeline.md`, and the codex. *The Ghost Plane* and *Shadow Alliance* are left out because they are being rewritten.

Categories:

- (a) internal continuity: names, ranks, numbers, dates, or who-did-what that change within a story
- (b) canon conflict: contradicts `timeline.md`, the codex, or another story
- (c) typo, wrong word, or grammar
- (d) drafting leftover
- (e) real-world factual error
- (f) knowledge leak: a character, or narration in their point of view, knows something they can't
- (g) other: duplicated passages, broken logic, formatting slips

Confidence (high, medium, low) is how sure the reviewer is that something is wrong, not how much it matters.

## Summary

| Story | Slips | High confidence | Author decisions | Bold as emphasis | Inline dialogue |
|---|---:|---:|---:|---:|---:|
| *The Beginning Is A Delicate Time* (1947) | 37 | 14 | 8 | 0 | 22 |
| *The Cormorant Gambit* (2019) | 3 | 1 | 1 | 58 | 26 |
| *The Wraith* (2021) | 87 | 10 | 22 | 7 | 1051 |
| *Shade of Gray* (2022) | 65 | 15 | 12 | 0 | 8 |
| *Shadows in Tel Aviv* (2022) | 28 | 9 | 11 | 0 | 107 |
| *Silent Watchers* (2023) | 51 | 7 | 8 | 1 | 684 |
| *P = NP* (2024) | 19 | 1 | 3 | 0 | 0 |
| *Angels in Armor* (2024) | 55 | 8 | 11 | 0 | 32 |
| *Executive Authority* (2024) | 60 | 5 | 7 | 0 | 183 |
| *Adrenaline* (2024) | 26 | 2 | 3 | 0 | 0 |
| *Across the Sea* (2025) | 102 | 19 | 26 | 0 | 57 |
| *David v Goliath* (2025) | 98 | 21 | 25 | 0 | 18 |
| *Ex Mero Mutu* (2025) | 48 | 15 | 10 | 0 | 137 |
| *Torchlight* (2025) | 6 | 1 | 1 | 0 | 66 |
| *Flight of Icari* (2026) | 51 | 16 | 10 | 1 | 22 |
| *The Helpers* (2026) | 64 | 12 | 12 | 0 | 6 |
| *Knock Knock* (2027) | 143 | 44 | 39 | 0 | 15 |
| *Boundary Layer* (2027) | 3 | 1 | 0 | 0 | 0 |
| *The Adequate Machine* (2027) | 5 | 2 | 0 | 0 | 0 |
| Timeline, codex, cross-story | 13 | 4 | 6 | – | – |
| Total | 964 | 207 | 215 | 67 | 2434 |

Inline dialogue counts are paragraphs. Most of them sit in six stories written that way throughout; section 3 treats each of those as a single decision.

## 1. Slips

### The Beginning Is A Delicate Time

`story-the-beginning.md`: 37 items, 14 high confidence, 8 needing an author decision.

- [ ] TB-01 · L9, 20, 36, 52, 74, 92, 142 · (e) · low
  - Excerpt: `## 1947-07-07T23:34:16-06:00, Roswell, New Mexico`
  - Problem: Mountain Standard Time is -07:00. -06:00 applies only if New Mexico observed DST in 1947, which I couldn't confirm. (Fort Worth at -06:00 is correct.)
  - Fix: author decision. Verify, then use `-07:00` for the Roswell datelines if no DST applied.

- [ ] TB-02 · L16 · (c) · low
  - Excerpt: `like something inside exploded outwards`
  - Fix: `like something inside had exploded outwards`

- [ ] TB-03 · L22 · (c) · medium
  - Excerpt: `muttered a thanks to the young NC lady`
  - Problem: "NC lady" is unclear.
  - Fix: `muttered a thanks to the young WAC sergeant` (or "NCO").

- [ ] TB-04 · L22 · (c) · low
  - Excerpt: `He spent the better part of the early morning flying and driving in`
  - Fix: `He had spent`

- [ ] TB-05 · L22 · (e) · low
  - Excerpt: `the small airfield that suddenly lit up on the leadership's radar`
  - Problem: Roswell AAF was home of the 509th Bomb Group, the only atomic-capable bomber unit, so hardly "small".
  - Fix: `the remote airfield`

- [ ] TB-06 · L24 · (c) · high
  - Excerpt: `as to what that hell that thing in your hangar is`
  - Fix: `what the hell`

- [ ] TB-07 · L24 · (c) · high
  - Excerpt: `you flew me out here to middle of nowhere`
  - Fix: `to the middle of nowhere`

- [ ] TB-08 · L30 · (e) · low
  - Excerpt: `I've seen the reports of Soviet fighters we recovered`
  - Problem: no Soviet fighters were in US hands by mid-1947.
  - Fix: `I've seen the reports on Soviet fighters`

- [ ] TB-09 · L38 · (c) · medium
  - Excerpt: `but the crew has already jammed all communications`
  - Fix: `had already jammed`

- [ ] TB-10 · L38, 42 · (a) · medium
  - Excerpt: `the commander made a decision under his own authority.` / `It nodded.`
  - Problem: the same paragraph also switches between "their viewscreens" and "It saw".
  - Fix: `under its own authority`, and `observed the commotion on its viewscreens`.

- [ ] TB-11 · L38; codex/galaxy/xenari.md · (b) · low
  - Excerpt: `the commander made a decision under his own authority.`
  - Problem: Xenari act by consensus, and intervention requires Great Circle deliberation.
  - Fix: author decision. For example, add `pending the Circle's review`.

- [ ] TB-12 · L44 · (c) · high
  - Excerpt: `ready to apply it if needed.A high-pitched whine`
  - Fix: `if needed. A high-pitched whine`

- [ ] TB-13 · L44, 98, 182; codex xenari.md · (a)(b) · low
  - Excerpt: `a female voice spoke with a Southern accent.` vs `its mechanical voice` and `an unplaceable accent in its slightly mechanic-sounding voice`
  - Problem: the voice changes from scene to scene. The codex also says the Xenari mimic human speech near-perfectly.
  - Fix: author decision. Make the voice consistent (e.g. the warm Southern voice at L98 and L182).

- [ ] TB-14 · L62, 72 · (a) · low
  - Excerpt: `Platchett held up a metal tablet` / `Stevens approached, holding the symbol-covered tablet.`
  - Fix: `Stevens approached and took the symbol-covered tablet from Platchett.`

- [ ] TB-15 · L106–110; codex xenari.md, foundations.md · (b) · medium
  - Excerpt: `The Terran Advisory Council has been observing your development for several decades.` / `Representing various species`
  - Problem: in canon, the benefactors are the Xenari specifically, under the Stewardship Compact's mentorship clause. There is no multi-species council.
  - Fix: author decision. For example, `The Stewardship Circle of my people has been observing…` and `Many more, all of my people.`

- [ ] TB-16 · L118 · (e) · high
  - Excerpt: `## 1947-07-20T11:15:33-06:00, Pentagon, Washington D.C.`
  - Problem: the Pentagon is in Arlington, Virginia, and Eastern time is not -06:00.
  - Fix: `## 1947-07-20T11:15:33-05:00, Pentagon, Arlington, Virginia` (use -04:00 if DST applied).

- [ ] TB-17 · L120 · (e) · high
  - Excerpt: `Secretary of Defense James Forrestal sat at the head of the table`
  - Problem: the office was created by the National Security Act (26 July 1947), and Forrestal took it on 17 September. On 20 July he was Secretary of the Navy.
  - Fix: `Secretary of the Navy James Forrestal`

- [ ] TB-18 · L120–140, 146; CLAUDE.md · (b) · medium
  - Excerpt: `Your leaders have agreed to the preliminary contact framework`
  - Problem: the US military leadership and seven governments learn of an alien in 1947. Canon says national militaries and intelligence agencies don't know about the alien backers.
  - Fix: author decision. Limit the circle of who is briefed, or show the knowledge being compartmentalized or erased later.

- [ ] TB-19 · L138 · (e) · high
  - Excerpt: `The Russians. The British. The French. People we were shooting at two years ago.`
  - Problem: those three were WWII allies.
  - Fix: `The Russians. The Germans. The Japanese. People we were shooting at, or alongside, two years ago.`

- [ ] TB-20 · L146, 266 · (a) · medium
  - Excerpt: `Your leaders have agreed` vs `could be seen as conspiracy or treason by our respective leaders.`
  - Fix: L146 → `Your military chiefs have agreed to the preliminary contact framework`

- [ ] TB-21 · L156 · (g) · medium
  - Excerpt: `we could not simply abandon the pilot`
  - Problem: no pilot is ever found or mentioned.
  - Fix: `we could not simply abandon the wreck`, or add a recovered pilot earlier.

- [ ] TB-22 · L182 · (c) · high
  - Excerpt: `the strangest being they ever saw.The thing was short`
  - Fix: `saw. The thing`

- [ ] TB-23 · L182 · (c) · low
  - Excerpt: `the strangest being they ever saw`
  - Fix: `they had ever seen`

- [ ] TB-24 · L182 · (c) · high
  - Excerpt: `it wore a mask-like devices`
  - Fix: `a mask-like device`

- [ ] TB-25 · L182 · (c) · medium
  - Excerpt: `its large eyes glimmered like that of an insect`
  - Fix: `like those of an insect`

- [ ] TB-26 · L182 · (c) · medium
  - Excerpt: `slightly mechanic-sounding voice`
  - Fix: `slightly mechanical-sounding voice`

- [ ] TB-27 · L182; codex/galaxy/xenari.md, kryllians.md · (b) · high
  - Excerpt: `The thing was short, at most 160 cm` / `skin was a light bluish color` / `pulsed slowly with a blue light around a filter`
  - Problem: the Xenari benefactors are 2.2–2.8 m tall, with semi-translucent bioluminescent skin and no breathing mask. 150–160 cm with a breathing filter matches the Kryllians.
  - Fix: author decision. Make Thel'zar tall, frail and bioluminescent, and drop the filter mask.

- [ ] TB-28 · L196 · (e) · medium
  - Excerpt: `General Petrov, you commanded the 3rd Guards Tank Army during the Battle of Kursk.`
  - Problem: historically, Pavel Rybalko commanded that army.
  - Fix: `you commanded a tank corps of the 3rd Guards Tank Army`

- [ ] TB-29 · L204, 206, 288 · (a) · high
  - Excerpt: `Karl Schmidt from Berlin University` vs `Karl Schmitt of the Berlin University`
  - Fix: L288 → `Karl Schmidt of Berlin University`

- [ ] TB-30 · L222, 280 · (c) · low
  - Excerpt: `Japanese diplomat Takayama Nakamura`
  - Problem: "Takayama" is a surname, not a given name.
  - Fix: `Takayuki Nakamura`

- [ ] TB-31 · L248 · (c) · high
  - Excerpt: `"Gentleman, we're discussing the fate of our entire species.`
  - Fix: `"Gentlemen, we're…`

- [ ] TB-32 · L258 · (e) · high
  - Excerpt: `American engineer Robert Goddard on propulsion systems`
  - Problem: Goddard died on 10 August 1945.
  - Fix: author decision. A fictional engineer, or a living figure (e.g. Theodore von Kármán).

- [ ] TB-33 · L258 · (e) · medium
  - Excerpt: `British diplomat Sir Anthony Eden found common ground with his French counterpart, Auguste Champetier de Ribes`
  - Problem:
    - Champetier de Ribes died in March 1947.
    - Eden was an opposition MP in 1947, not a serving diplomat.
    - France's foreign minister was Georges Bidault.
  - Fix: author decision. For example, `former Foreign Secretary Sir Anthony Eden found common ground with French Foreign Minister Georges Bidault`

- [ ] TB-34 · L274, 276 · (a) · high
  - Excerpt: `## 1947-07-27T21:30:45-06:00` / `Days later, they were still in talks`
  - Problem: the dateline is only one day after the 26 July meeting.
  - Fix: `## 1947-07-30T21:30:45-06:00, Fort Worth Army Air Field, Texas`

- [ ] TB-35 · L284 · (c) · high
  - Excerpt: `shook his head."No.`
  - Fix: `shook his head. "No.`

- [ ] TB-36 · L290 · (c) · medium
  - Excerpt: `- Henry Smith, the American diplomat's face lit up -`
  - Fix: `- the face of Henry Smith, the American diplomat, lit up -`

- [ ] TB-37 · L292 · (c) · medium
  - Excerpt: `Hugh slammed on the table`
  - Fix: `Hugh slammed his hand on the table`

### The Cormorant Gambit

`story-the-cormorant-gambit.md`: 3 items, 1 high confidence, 1 needing an author decision.

- [ ] CG-01 · line 107 · (g) · high
  - Excerpt: `"We call it *creative problem-solving*."  As the *Cormorant* burned back toward the fleet`
  - Problem: Voss's line and the next narration paragraph are run together on one line.
  - Fix: break the line after `problem-solving*."` so "As the *Cormorant* burned back…" starts its own paragraph.
- [ ] CG-02 · lines 119, 122, 170 · (b) · medium
  - Excerpt: `To the Council of External Relations, Xenari High Command` / `Honored Elders,` / `In service to the High Council,`
  - Problem: codex/galaxy/xenari.md says the Xenari have no centralized rulers or military command. Policy comes from the Great Circle (Ish'kai-Zor), and the Zai'nor guild is the nearest thing to a military.
  - Fix: author decision. For example `To the Great Circle, by way of the Zai'nor` and `In service to the Great Circle,`. "Honored Elders" can stay, since the codex treats elders as respected advisors.
- [ ] CG-03 · line 202 · (c) · medium
  - Excerpt: `Their species were built for war—hardened, resilient, ruthless.`
  - Fix: `Their species was built for war` (or `His species was`)

### The Wraith

`story-american-wraith.md`: 87 items, 10 high confidence, 22 needing an author decision.

- [ ] AW-01
  - Where: lines 35, 187 (cf. 11, 39, 203)
  - Category: (a), medium confidence
  - Excerpt: `She was alone, but the sudden responsiveness of an entity she had all but thought mythical made her feel anything but.`
  - Problem: She is in a busy HQ: agents on calls (11), the "ambient hum of the office" (39), and she sits in a cubicle (203). Line 187 nevertheless calls it "the empty room".
  - Fix: Line 35 becomes `No one nearby was paying her any attention, but the sudden responsiveness of an entity she had all but thought mythical made her feel anything but alone.` In line 187, "to the empty room" becomes "to no one in particular".

- [ ] AW-02
  - Where: line 15 (cf. 193, 355)
  - Category: (c), low confidence
  - Excerpt: `Moscow was a fortress of counter-intelligence`
  - Problem: Spelled "counterintelligence" everywhere else.
  - Fix: `counterintelligence`

- [ ] AW-03
  - Where: line 23
  - Category: (c), low confidence
  - Excerpt: `its subject line blank except for one sentence:`
  - Problem: "Blank except for" contradicts itself.
  - Fix: `An email had appeared in her secure inbox, its subject line a single sentence:`

- [ ] AW-04
  - Where: lines 83, 85, 113, 171, 221, 237, 247, 283, 331, 337, 345, 351, 355, 357, 559, 627, 647, 649, 667, 675, 741, 745 (23 mentions)
  - Category: (b) and (e), high confidence
  - Excerpt: `plainclothes men with sharp eyes and hard stances inspecting every vehicle. GRU, no question about it.`
  - Problem:
    - Shade of Gray, line 191 (canon), has Monroe describe this same extraction as beating "multiple layers of FSB surveillance".
    - In the real world, the FSB handles domestic counterintelligence and checkpoints; the GRU is military intelligence.
  - Fix: Author decision. Either replace GRU with FSB throughout (including "GRU kill team" at 337 and 559), or change Shade of Gray line 191 to GRU. FSB is the recommended choice.

- [ ] AW-05
  - Where: line 89 (cf. frontmatter `timeline: 2021-03-21`)
  - Category: (e), low confidence
  - Excerpt: `Moscow’s unforgiving winter offered little hope of disappearing into the crowd`
  - Problem: The story is set in late March, so "unforgiving winter" is a stretch, though snow is plausible.
  - Fix: Optional: `Moscow’s lingering winter`

- [ ] AW-06
  - Where: line 91
  - Category: (c), medium confidence
  - Excerpt: `There was no point in calling it now.`
  - Problem: Reads as a slip for "calling in".
  - Fix: `There was no point in calling in now.`

- [ ] AW-07
  - Where: line 171 (cf. 143)
  - Category: (a), medium confidence
  - Excerpt: `The wiry man at the door spoke up, his voice low.`
  - Problem: Line 143 puts the stocky man at the window as lookout, and the wiry man unpacking the bag.
  - Fix: `The stocky man at the window spoke up, his voice low.`

- [ ] AW-08
  - Where: line 227 (cf. 163)
  - Category: (a), low confidence
  - Excerpt: `the sharp features and faint scar belonging to a man he’d never met`
  - Problem: Line 163 describes the mask face as "older, heavier, with deep-set eyes".
  - Fix: `the heavy features and faint scar belonging to a man he’d never met`

- [ ] AW-09
  - Where: line 227
  - Category: (c), low confidence
  - Excerpt: `stared back at him from a rearview mirror mounted on the driver’s visor`
  - Problem: A mirror on a sun visor is a vanity mirror, not a rearview mirror.
  - Fix: `stared back at him from a vanity mirror on the driver’s visor`

- [ ] AW-10
  - Where: lines 309–311, 729 (cf. 1021)
  - Category: (f), medium confidence
  - Excerpt: `Looked like it belonged in some sci-fi movie. They called it a Wraith.`
  - Problem:
    - Nobody names the craft in Marcus's hearing; the leader only says "Your ride" (309).
    - Marcus nonetheless knows the name, and Mercer repeats it (1021).
  - Fix: Line 309 becomes `The leader smirked. “Your ride. We call it a Wraith.”`

- [ ] AW-11
  - Where: line 741 (cf. 323)
  - Category: (a), low confidence
  - Excerpt: `We took off, and it was silent. No sound, no vibrations.`
  - Problem: Line 323 has "the floor vibrating beneath his feet".
  - Fix: `We took off, and it was silent. No sound, barely a vibration.`

- [ ] AW-12
  - Where: line 327 (cf. 305, 591)
  - Category: (g), low confidence
  - Excerpt: `Through a narrow viewport, he saw the warehouse below shrink away.`
  - Problem: The Wraith is parked inside a closed warehouse, and no roof opening or exit is ever shown. Orlov finds only heat marks on the rafters.
  - Fix: Author decision. One option is to insert a line before 327 such as `Above them, a section of the corroded roof slid aside.`

- [ ] AW-13
  - Where: line 381
  - Category: (c), low confidence
  - Excerpt: `But the Federation’s warning echoed in her mind—*Ask and ye shall receive.*`
  - Problem: The quoted line is a promise, not a warning.
  - Fix: `But the Federation’s message echoed in her mind—*Ask and ye shall receive.*`

- [ ] AW-14
  - Where: line 405 (cf. 439, 453)
  - Category: (a), medium confidence
  - Excerpt: `Paris is just a waypoint. You’ll be debriefed, and we’ll figure out where you go from there.`
  - Problem: On landing, the leader says "From here, you’re on your own" (439) and "Our job’s done" (453). There is no debrief.
  - Fix: `“That depends on you,” she said. “Paris is just a waypoint. Your own people take it from there. Right now, it’s about getting you off the radar.”`

- [ ] AW-15
  - Where: line 445 (cf. 439, 453, 455)
  - Category: (a) and (c), medium confidence
  - Excerpt: `When we arrive at the hotel, you just go up to the reception and tell them you have a reservation for the name James Sitwell.`
  - Problem:
    - She stays with the Wraith (453, 455), so "we" is wrong.
    - "for the name" should be "under the name"; Marcus says "under" at 477.
    - Line 439's "you’re on your own" also clashes with the two-man van escort that follows.
  - Fix: `When you arrive at the hotel, just go up to the reception and tell them you have a reservation under the name James Sitwell.`

- [ ] AW-16
  - Where: lines 461, 479 (cf. Shade of Gray line 191)
  - Category: (b), low confidence
  - Excerpt: `the van slowed to a stop outside a midrange hotel`
  - Problem: Shade of Gray says "the next day he was sitting in a safe house in Paris". In AW it is a hotel, two days after the plea.
  - Fix: Author decision. Amend Shade of Gray's wording (it could be read as Monroe paraphrasing).

- [ ] AW-17
  - Where: line 465
  - Category: (c), low confidence
  - Excerpt: `Go in, check in, and lay low.`
  - Problem: Standard usage is "lie low". It's acceptable as colloquial speech.
  - Fix: Optional: `lie low`

- [ ] AW-18
  - Where: line 497 (cf. 191, 353–365, 397)
  - Category: (a), low confidence
  - Excerpt: `The blinking light on her secure line was unusual this late`
  - Problem: The timing doesn't support "this late":
    - The ops brief starts at 1400 (191).
    - "Your package is being delivered" arrives about 20 minutes in (353–365).
    - Paris is "just over an hour" away (397), plus the drive to the hotel.
    - That puts the call at roughly 1600 Langley time.
  - Fix: `The blinking light on her secure line was unusual, but she had been conditioned to expect bad news from unknown numbers.`

- [ ] AW-19
  - Where: line 553 (cf. 37, 413–417, 497–549)
  - Category: (a) and (f), high confidence
  - Excerpt: `Someone in Paris had said a prayer for him. And someone, somewhere, had answered.`
  - Problem:
    - Alicia made the plea herself, in Langley (37, 417). Paris is where Marcus is.
    - She also never heard the "prayer" wording; Marcus doesn't pass it on during the call (497–549).
  - Fix: `She had asked for help with no one listening. And someone, somewhere, had answered.`

- [ ] AW-20
  - Where: line 557 (cf. 287)
  - Category: (g), low confidence
  - Excerpt: `### Ghosts in the Shadows`
  - Problem: Nearly duplicates the earlier heading `### The Ghost in the Shadows`.
  - Fix: Author decision. For example, `### Cold Trail`.

- [ ] AW-21
  - Where: line 741 (cf. 571, 577, 581, 589–591)
  - Category: (a), medium confidence
  - Excerpt: `No heat, no exhaust, not even tracks in the snow.`
  - Problem:
    - Orlov's team finds the van's tire tracks (571, 577) and a heat trail (589–591).
    - Line 581 says "No tire marks on the floor", although the van drove across a dusty floor (301–305).
  - Fix:
    - Line 741: `When we lifted, I looked back at the warehouse. No flare, no exhaust plume, nothing to show we’d ever been there.`
    - Line 581: delete "No tire marks on the floor,".

- [ ] AW-22
  - Where: lines 623–647
  - Category: (g), low confidence
  - Excerpt: `But I managed to get a name: General Viktor Rykov.`
  - Problem: The Russia–China bloc intelligence, which is the reason for the extraction, is never followed up.
  - Fix: Author decision. Add a payoff or trim.

- [ ] AW-23
  - Where: line 677 (cf. 155, 693)
  - Category: (a), medium confidence
  - Excerpt: `Said it was going to ‘make me disappear.’`
  - Problem: In the scene she says "Your ticket out of Moscow" (155), and Marcus himself later quotes "ticket out" (693).
  - Fix: `Said it was my ‘ticket out of Moscow.’`

- [ ] AW-24
  - Where: line 723 (cf. 237–269, 273–293)
  - Category: (a) and (g), low confidence
  - Excerpt: `The driver barely flinched when we hit checkpoints, and the disguise held up.`
  - Problem: There was only one checkpoint. "We passed through without a hitch" also omits the SUV tail and the chase.
  - Fix: `The driver barely flinched at the checkpoint, and the disguise held up. … We passed through, shook a tail, and kept moving.`

- [ ] AW-25
  - Where: line 891
  - Category: (c), medium confidence
  - Excerpt: `Alicia frowned audibly.`
  - Problem: A frown can't be heard over the phone.
  - Fix: `Alicia’s voice tightened.`

- [ ] AW-26
  - Where: line 961
  - Category: (f) and (g), low confidence
  - Excerpt: `her face shifting seamlessly into that of the Federation team leader from Marcus’s account`
  - Problem: Mercer has never seen the leader, and Marcus's description is minimal, so he can't recognize her face.
  - Fix: `her face shifting seamlessly into a stranger’s: dark curls, sharp features, exactly the Federation team leader Marcus had described.`

- [ ] AW-27
  - Where: line 1113 (cf. 1105–1107)
  - Category: (a), medium confidence
  - Excerpt: `He had followed the woman from the bar, keeping a discreet distance`
  - Problem: She "disappear[ed] into the night" while he "sat frozen" and then finished his whiskey. He did not follow her.
  - Fix: `He had come straight from the bar and found the woman meandering through the park with the unhurried confidence of someone who knew she was expected.`

- [ ] AW-28
  - Where: lines 1139, 1159
  - Category: (a), low confidence
  - Excerpt: `She held it out to him, her eyes locking onto his.`
  - Problem: She hands him the same phone again at 1159: `She stood, handing him the phone.`
  - Fix: Line 1139 becomes `She reached into her coat pocket and pulled out a small smartphone, turning it over in her fingers.`

- [ ] AW-29
  - Where: lines 1171, 1189, 1193, 1227 (cf. 1181, 1191)
  - Category: (g), medium confidence
  - Excerpt: `Be advised, we’re carrying Chief of Operations Harold Whitaker. Repeat, Harold Whitaker onboard.`
  - Problem:
    - Whitaker is standing on the tarmac.
    - Hermes then says the craft is "here at the request of" Whitaker (1227), but he never requested it.
    - Neither claim is ever explained as a ruse.
  - Fix: Author decision. Either:
    - make it an acknowledged ruse (Hermes: "The claim was necessary to secure your attention"), or
    - change the radio call to `We have business with Chief of Operations Harold Whitaker`, and line 1227 to `It is here for your Chief of Operations, Harold Whitaker.`

- [ ] AW-30
  - Where: line 1193
  - Category: (c) and (g), low confidence
  - Excerpt: `Maintain current heading for Runway 3.`
  - Problem: An aircraft can't instruct the tower to maintain a heading.
  - Fix: `We are maintaining current heading for Runway 3.`

- [ ] AW-31
  - Where: line 1221 (cf. `codex/foundations/artificial-intelligence.md`, lines 11, 15, 21; IW:147)
  - Category: (b), low confidence
  - Excerpt: `This is Hermes, AI liaison for the Federation.`
  - Problem: The codex says AIs with distinct personalities are named and always written in uppercase (HARBINGER and so on); vehicle AIs are "shackled". Hermes, and Tsel in IW, have strong personalities and act as Federation liaisons, yet are written in mixed case.
  - Fix: Author decision. Either treat them as shackled platform AIs and keep the mixed case, or render them as HERMES and TSEL.

- [ ] AW-32
  - Where: "its" at 1223, 1227, 1247, 1269, 1289, 1359, 2649; "his/he" at 1629, 1729, 1851, 1921, 2185, 2657, 2769, 2825, 2893, 3151, 3223; characters use "He" at 3101 and 3111 but "it" at 3207
  - Category: (a), medium confidence
  - Excerpt: `The voice was neither male nor female, its cadence unnervingly smooth.`
  - Problem: Hermes's pronoun switches back and forth. IW uses "it/its" for both Hermes and Tsel.
  - Fix: Author decision. "It/its" throughout is recommended: change the his/he lines listed above, and "He" at 3101 and 3111 to "It".

- [ ] AW-33
  - Where: line 1255 (cf. 319, 1331, 1369)
  - Category: (a), low confidence
  - Excerpt: `Despite the lack of visible instrumentation, the space radiated an unsettling sense of intelligence`
  - Problem: Elsewhere the walls are "lined with control panels and holographic displays" (319).
  - Fix: Author decision. For example, `Its consoles dark and flush with the walls, the space radiated…`

- [ ] AW-34
  - Where: line 1319
  - Category: (c), low confidence
  - Excerpt: `scanning the seams where panels joined seamlessly`
  - Problem: Self-contradictory wording.
  - Fix: `scanning for seams between the panels and finding almost none`

- [ ] AW-35
  - Where: line 1335 (cf. `covops.md`, line 8)
  - Category: (b), medium confidence
  - Excerpt: `“Yeah, we’ve all read the specs,” Tomas interrupted.`
  - Problem: covops.md says not even allies get the specifications of covert-ops assets.
  - Fix: `“Yeah, we’ve all had the briefing,” Tomas interrupted.`

- [ ] AW-36
  - Where: line 1337
  - Category: (f) and (b), high confidence
  - Excerpt: `Effective against both terrestrial and extraterrestrial sensors.`
  - Problem: Hermes tells a CIA team that extraterrestrial sensors exist, which breaks the setting's core rule that national agencies don't know about aliens.
  - Fix: `Effective against radar, thermal, and optical sensors alike.`

- [ ] AW-37
  - Where: lines 1337, 1341 (cf. `covops.md`, line 179; IW:457–461)
  - Category: (b), medium confidence
  - Excerpt: `It does not render the Wraith entirely invisible but creates an optical distortion that blends it with the environment.`
  - Problem: The codex calls the cloak "visually undetectable under most conditions". In IW, Tsel says "I am invisible" even at 100 m.
  - Fix: Author decision. For example, `It renders the Wraith visually undetectable under most conditions, though not perfectly.` The ripple imagery (311, 1201, 1245) can stay as a close-range artefact.

- [ ] AW-38
  - Where: line 1345 (cf. `covops.md`, lines 170, 224–225; AW 2673, 2725; plural cannons at 2683, 2687, 2689, 2705, 2717, 2721, 2723, 2743, 3151, 3155, 3171 against singular at 3157; JW:646)
  - Category: (b) and (a), high confidence
  - Excerpt: `including twin plasma emitters mounted beneath the nose and a rapid-fire railgun system capable of engaging both aerial and ground targets`
  - Problem:
    - Canon gives the Wraith one chin-mounted turreted plasma cannon and two dorsal internal missile banks. It has no railgun.
    - Hermes's list leaves out the missiles that the Wraith later fires (2673, 2725).
    - The cannon count wavers between plural and singular. JW's footage of the same raid shows a single cannon.
  - Fix:
    - In line 1345, replace the clause with `including a chin-mounted plasma turret and two banks of internal missile launchers mounted dorsally, capable of engaging both aerial and ground targets`.
    - Change "plasma cannons" to "plasma cannon", and "cannons" to "turret" at the lines listed above.

- [ ] AW-39
  - Where: line 1363 (cf. 1257, 2745)
  - Category: (a), low confidence
  - Excerpt: `ensuring it was always clear and directional without feeling omnipresent`
  - Problem: Line 2745 calls Hermes "the Wraith’s omnipresent AI", and line 1257 has its voice "emanating from all around him".
  - Fix: Line 2745 becomes `as though addressing the Wraith’s AI`.

- [ ] AW-40
  - Where: line 1371 (cf. 1373–1377, 1617–1621)
  - Category: (a), low confidence
  - Excerpt: `Lieutenant Carter, you’ll find the manual controls highly responsive.`
  - Problem: Hermes already treats Rena as the pilot, yet later she asks, `“Can I try? Y’know, flying you?”`
  - Fix: Author decision. For example, line 1617 becomes `“Say, Hermes? Mind if I take her up myself this time?”`

- [ ] AW-41
  - Where: line 1415 (cf. `nanotechnology.md`, lines 11, 15)
  - Category: (f), medium confidence
  - Excerpt: `“Nanomed kits? Aren’t those restricted?”`
  - Problem: A CIA specialist has no way of knowing that Federation nanomed kits exist or are restricted. The restriction is galaxy-wide.
  - Fix: `“Nanomed kits? As in nanotech?”` Hermes's reply at 1417 still works.

- [ ] AW-42
  - Where: line 1455 (cf. `covops.md`, lines 168, 204; IW:323)
  - Category: (b), high confidence
  - Excerpt: `“The vehicle bay accommodates one standard ground vehicle,” Hermes explained.`
  - Problem: Canon, and Tsel at IW:323, say the Wraith carries up to two Q-cars.
  - Fix: `“The vehicle bay accommodates two standard ground vehicles,” Hermes explained. “Currently, it houses a single Q-car equipped for covert operations.`

- [ ] AW-43
  - Where: line 1471
  - Category: (c), low confidence
  - Excerpt: `### Parting gift`
  - Problem: Every other heading is in title case.
  - Fix: `### Parting Gift`

- [ ] AW-44
  - Where: line 1475 (cf. 1467, 1473)
  - Category: (a), low confidence
  - Excerpt: `From a recessed compartment in the operations center’s wall, a panel slid open`
  - Problem: The team is at the vehicle bay at this point.
  - Fix: `From a recessed compartment in the bay’s wall, a panel slid open`

- [ ] AW-45
  - Where: line 1475 (cf. IW:29, IW:167; CLAUDE.md line 6)
  - Category: (b), low confidence
  - Excerpt: `a wireframe globe encircled by laurels, with two broken swords crossed beneath it`
  - Problem: The swords' position differs across tellings: "beneath" here, "crossed by" at IW:29, "behind" at IW:167. Canon says "crossed saltire".
  - Fix: Author decision. Standardize, for example `with two broken swords crossed saltire behind it`.

- [ ] AW-46
  - Where: line 3452 (cf. AW 1529, 3428; Shade of Gray lines 155, 197–199)
  - Category: (a) and (b), high confidence
  - Excerpt: `As Deputy Director of Covert Operations, your insight is critical`
  - Problem:
    - Line 1529 says she is "not the most senior agent in the room", and the promotion is never shown.
    - In March 2022, Shade of Gray calls her "Senior Field Agent Alicia Monroe".
    - Shade of Gray also has her say "I've tried to find out… There's almost nothing… I don't know a lot myself". In AW, she has already pitched and overseen a Wraith operation and been debriefed alongside Hermes.
  - Fix: Author decision. Options:
    - Line 3452 becomes `As the officer who oversaw this operation` (or "Senior Field Agent").
    - Or date the Iran raid and the hearing after March 2022, and soften Shade of Gray lines 197–199.

- [ ] AW-47
  - Where: line 1557
  - Category: (f), high confidence
  - Excerpt: `not about the Federation, not about the craft’s extraterrestrial origins.`
  - Problem: A CIA officer can't know the craft is extraterrestrial. This also contradicts Shade of Gray, where she knows "almost nothing".
  - Fix: `She couldn’t tell them the whole truth—not about the Federation, not about how little she knew of the craft herself.`

- [ ] AW-48
  - Where: line 1619
  - Category: (a), low confidence
  - Excerpt: `“Of course, Ms. Carter. Take a seat, and we’ll begin instruction.”`
  - Problem: Hermes calls her "Lieutenant Carter" in the same line.
  - Fix: `“Of course, Lieutenant. Take a seat, and we’ll begin instruction.”`

- [ ] AW-49
  - Where: line 1629 (cf. 1345, 1489, 1789, 2215, 2421)
  - Category: (a), low confidence
  - Excerpt: `Ascend at a fifteen-degree angle until we reach two thousand feet`
  - Problem: Hermes uses metric everywhere else.
  - Fix: `until we reach six hundred meters`

- [ ] AW-50
  - Where: lines 1651, 1957, 1971 (cf. 1963, 1983, 2015, 2941)
  - Category: (a), medium confidence
  - Excerpt: `The Wraith is equipped with four short-range reconnaissance drones`
  - Problem:
    - All four drones are at the second hub (1957, and used at 1963, 1983, 2009, 2015), yet Olivia has "her drone" at the convoy (1971). That makes five.
    - The "reconnaissance" drones also carry EMP, incendiary and stun payloads.
  - Fix: Author decision. For example, line 1651 becomes `six short-range drones … with optical, thermal, and electromagnetic sensors and small payload bays`.

- [ ] AW-51
  - Where: lines 1677–1681, 2201 (cf. 2211, 2221, 2243)
  - Category: (a), medium confidence
  - Excerpt: `Tomas and I will handle the ambush, and Olivia will coordinate with Hermes to monitor the situation.`
  - Problem: Both plans keep Olivia out of the field for phase three, but she is crouched at the roadside and fighting in the ambush (2211, 2243).
  - Fix: Line 2201 becomes `Tomas, Olivia, and I will handle the ambush, with Olivia running the drones from the treeline.` Adjust 1679 if needed.

- [ ] AW-52
  - Where: lines 1707, 2353, 2683 (cf. JW lines 632, 634, 646)
  - Category: (b), medium confidence
  - Excerpt: `forested hills rising into rocky crags and snow-dusted peaks`
  - Problem: JW replays footage of this raid but shows a "desert landscape", a "weapons manufacturing facility", an "infiltration team codenamed *Hermes*", and a single plasma cannon. AW has forested Gilan, a narcotics factory, Hermes as the AI, and Westin's team.
  - Fix: Author decision. Amending JW to match AW is recommended.

- [ ] AW-53
  - Where: lines 1855, 2067, 2819–2825 (cf. 1847, 1911, 1915)
  - Category: (g), high confidence
  - Excerpt: `“He’s not in our database. Could be local leadership—or someone higher up.”`
  - Problem:
    - In the field the VIP is unknown: Hermes calls the information "Limited" (1915), and Karami arrives late by SUV (1847).
    - At the start of the interrogation, James knows his name and his role (2067).
    - The debrief claims Hermes identified Karami "within 2.7 seconds" from Federation databases, "at the center of the compound".
  - Fix: Author decision. Options:
    - Identify him in the field: line 1855 becomes `“Got a match,” Olivia said, running the image through her recognition software. “Davood Karami. Local logistics, IRGC-connected.”` Then update 1911 and 1915.
    - Or keep him unknown, rewrite 2819–2825 so he was identified from his phone after capture, and have line 2067 credit the phone.

- [ ] AW-54
  - Where: line 1921
  - Category: (g), low confidence
  - Excerpt: `—he pointed to a sharp curve surrounded by dense foliage—`
  - Problem: Hermes has no body to point with.
  - Fix: `—a marker pulsed on a sharp curve surrounded by dense foliage—`

- [ ] AW-55
  - Where: line 1971 (cf. 2001)
  - Category: (a), low confidence
  - Excerpt: `Guards in the SUV—three, armed.`
  - Problem: Only two guards are dealt with; the third is never accounted for.
  - Fix: `Guards in the SUV—two, armed.`

- [ ] AW-56
  - Where: line 1973 (cf. 1971)
  - Category: (a), low confidence
  - Excerpt: `Olivia, disable the SUV. I’ll handle the rear truck.`
  - Problem: The SUV is at the rear, so "rear truck" is ambiguous.
  - Fix: `I’ll handle the second truck.`

- [ ] AW-57
  - Where: line 2023 (cf. 2163, 2171)
  - Category: (a), medium confidence
  - Excerpt: `clutching a phone that was clearly nonfunctional thanks to the spike’s EMP companion device.`
  - Problem: The phone is later "integrated into the Wraith’s systems" and receives Rezaei's call.
  - Fix: `clutching a phone that showed no signal, thanks to the jammer paired with the spike mat.`

- [ ] AW-58
  - Where: line 2041
  - Category: (a), low confidence
  - Excerpt: `their prisoner restrained and seated in a holding cell. Rena watched them board`
  - Problem: The prisoner is in the cell before the team boards.
  - Fix: `Back at the Wraith, Rena watched the team board; soon their prisoner was restrained and seated in a holding cell.`

- [ ] AW-59
  - Where: line 2213
  - Category: (c), low confidence
  - Excerpt: `Drones buzzed softly overhead, their silent engines providing a bird’s-eye view of the road.`
  - Problem: "Buzzed" contradicts "silent".
  - Fix: `Drones circled overhead, their engines all but silent, providing a bird’s-eye view of the road.`

- [ ] AW-60
  - Where: line 2367 (cf. 2295)
  - Category: (a), low confidence
  - Excerpt: `As Tomas guided the Colonel back to his restraints`
  - Problem: Rezaei is already bound to the table.
  - Fix: `As Tomas checked the Colonel’s restraints`

- [ ] AW-61
  - Where: line 2377 (cf. 2239–2263)
  - Category: (g), low confidence
  - Excerpt: `The IRGC will inevitably notice Colonel Rezaei’s disappearance within the next twelve hours`
  - Problem: His escort was left alive on the road beside burning vehicles, so discovery would be near-immediate.
  - Fix: Author decision.

- [ ] AW-62
  - Where: line 2397 (cf. 2699; `covops.md`, lines 171, 232)
  - Category: (g), low confidence
  - Excerpt: `I must note that the facility’s anti-air defenses will complicate close-range support.`
  - Problem: The anti-air defenses never appear; the Wraith hovers over the compound unopposed. Canon also says its shields withstand sustained anti-air fire.
  - Fix: Author decision. Cut the line, or show the anti-air fire hitting the shields.

- [ ] AW-63
  - Where: line 2581 (cf. 2585)
  - Category: (a), low confidence
  - Excerpt: `Meet us by the east wall.`
  - Problem: They actually meet "near the hub’s entrance".
  - Fix: `Meet us at the hub.`

- [ ] AW-64
  - Where: line 2591 (cf. 2549–2573)
  - Category: (a), low confidence
  - Excerpt: `You have a limited window to execute your objectives before reinforcements are alerted.`
  - Problem: Both sets of charges are already placed.
  - Fix: `You have a limited window to withdraw before reinforcements are alerted.`

- [ ] AW-65
  - Where: lines 2727, 2745, 3187
  - Category: (g), low confidence
  - Excerpt: `Hermes, remind me never to be on your bad side.`
  - Problem: This repeats Tomas's joke from 2727 eighteen lines earlier. James's "I’ve seen airstrikes before…" line (2745) is reused almost verbatim at 3187.
  - Fix: Cut the 2745 joke and reword one of the airstrike lines.

- [ ] AW-66
  - Where: line 2755
  - Category: (a), medium confidence
  - Excerpt: `we dismantled their entire operation in one night.`
  - Problem: The operation spans several nights: insertion, recon, the convoy, the call setting a meeting for "tomorrow evening", the ambush, and the factory.
  - Fix: `we dismantled their entire operation in a matter of days.`

- [ ] AW-67
  - Where: lines 2781, 1631, 3279 (cf. 1167)
  - Category: (e) and (a), medium confidence
  - Excerpt: `its stealth systems disengaging as it approached Langley’s secure airstrip.`
  - Problem: CIA headquarters has no airstrip. The story already established Pinewood Airfield (1167), yet also uses "the CIA’s airstrip" (1631) and a tarmac at Langley (3279).
  - Fix:
    - Line 2781: `as it approached Pinewood Airfield.`
    - Line 1631: `Below, Pinewood Airfield shrank rapidly`
    - Line 3279: Author decision (move the hangar image to Pinewood).

- [ ] AW-68
  - Where: line 2829 (cf. 1837–1839)
  - Category: (g), low confidence
  - Excerpt: `Hermes’s EWAR mitigated most risks`
  - Problem: No electronic warfare was used during the recon; Olivia avoided the jammer instead.
  - Fix: `Hermes’s EWAR stood ready, but we never needed it`

- [ ] AW-69
  - Where: lines 2863, 2865, 2867, 2869 (cf. 1957, 1995–2035)
  - Category: (g), high confidence
  - Excerpt: `The EMP system onboard the Wraith played a key role in ensuring a clean takedown by disabling the vehicles’ electronics`
  - Problem: The debrief contradicts the action:
    - In the action, Olivia's spike mat shredded the SUV's tires, Tomas shot out the lead truck's engine, and the guards fought back.
    - The only EMP was a device paired with the mat; the Wraith was at the second hub.
    - Rena's drones were all at the second hub, not providing overwatch.
  - Fix:
    - Line 2863: `“Olivia triggered a disguised spike mat under the escort SUV, while Tomas and I took the trucks. An EMP device paired with the mat killed their phones and radios.”`
    - Line 2865: `“It was textbook. The spikes stopped the SUV, Tomas shot out the lead truck’s engine, and the guards were still getting their bearings when we moved in.”`
    - Line 2867: `…showing the SUV slewing to a halt on shredded tires, followed by the team moving into position.`
    - Line 2869: `“Tomas stopped the lead truck,” James continued. “Olivia and I handled the guards around the SUV and the rear truck. Rena was running the drones over the second hub, so we were on our own. Within minutes, the guards were down, and we had Karami in custody.”`

- [ ] AW-70
  - Where: lines 2923, 2935, 2941, 2949, 2951 (cf. 2215, 2221, 2235–2257)
  - Category: (g) and (a), high confidence
  - Excerpt: `Olivia disabled the SUV’s tires with precision fire. I took the rear truck`
  - Problem: The debrief mixes up the two ambushes:
    - Rezaei's convoy had no truck and no spike strip; Olivia ran the EMP drone.
    - Olivia shot the guards' arms, not tires.
    - Rezaei rode in a sedan, not an SUV (2949).
    - There was no stun-charge drone (2941).
    - Rezaei surrendered when James aimed his rifle at him; Olivia did not disarm him (2951).
  - Fix:
    - Line 2923: `“Tomas and I positioned ourselves near the lead vehicle, while Olivia ran the EMP drone. Rena held the Wraith a few kilometers off, ready for pickup.”`
    - Line 2935: `“Once the EMP hit,” James continued, “we moved in fast. Tomas put the escort down with non-lethal rounds, while Olivia disarmed the sedan’s driver and guard. I covered the Colonel.”`
    - Line 2941: `…but Tomas’s non-lethal rounds put them down before they could.`
    - Line 2949: "SUV" becomes "sedan".
    - Line 2951: `“Rezaei went for something under his jacket,” James said, his tone darkening. “He thought better of it once he was looking down my rifle.”`

- [ ] AW-71
  - Where: lines 3007, 3013 (cf. 2375–2441)
  - Category: (g), low confidence
  - Excerpt: `Hermes analyzed the compound layout and provided an insertion plan while we were still in the air.`
  - Problem: In the action, the plan was made around the table while the Wraith held position above Rudbar.
  - Fix: `Hermes analyzed the compound layout and drafted an insertion plan while we held position above Rudbar.`

- [ ] AW-72
  - Where: line 3037 (cf. 2499–2509)
  - Category: (g), low confidence
  - Excerpt: `The guards didn’t even glance our way.`
  - Problem: Two bunker guards were taken down with a shock baton and a takedown.
  - Fix: `The only guards we met at the bunker went down before they could raise the alarm.`

- [ ] AW-73
  - Where: lines 3061/3067, 3183/3185, 2849/2851, 2995–2999, 3233/3237
  - Category: (g), low confidence
  - Excerpt: `The silence in the room stretched for several moments after the holographic display dimmed.`
  - Problem: Silence beats and break transitions are duplicated back to back, which looks like the seams of chunks stitched together.
  - Fix: Delete the first sentence of 3067 and the first sentence of 3185. Trim the repeated "The team relaxed slightly" transitions.

- [ ] AW-74
  - Where: line 3075 (cf. 2613, 2631)
  - Category: (g), medium confidence
  - Excerpt: `Hermes directed us to a fallback point—the power hub—since it was close and defensible.`
  - Problem: In the action, James chose the hub (2613), and Hermes called it "indefensible" (2631).
  - Fix: Replace the sentence with `I pulled us back to the power hub because it was the closest cover we had.`

- [ ] AW-75
  - Where: line 3089
  - Category: (c), low confidence
  - Excerpt: `bringing up live footage from the mission`
  - Problem: The mission is over, so the footage is recorded, not live.
  - Fix: `bringing up recorded footage from the mission`

- [ ] AW-76
  - Where: line 3233 (cf. 3169–3225, 3237–3275)
  - Category: (g), medium confidence
  - Excerpt: `We’ll take a break before discussing the factory’s destruction.`
  - Problem: They have just watched and discussed the factory's destruction, and after the break nobody discusses it.
  - Fix: `We’ll take a break before we wrap up.`

- [ ] AW-77
  - Where: line 3303 (cf. 2673–2677, 2725; also 3356, 3524, 3560)
  - Category: (g), medium confidence
  - Excerpt: `There’s no sign of conventional ordnance. No missile fragments, no shells.`
  - Problem: The Wraith fired at least six missiles at the convoy and the factory.
  - Fix: Author decision. Either `No missile fragments we can identify, no shells.`, or establish that Federation munitions leave no recognizable debris.

- [ ] AW-78
  - Where: line 3303 (cf. 3339, 3356)
  - Category: (a), medium confidence
  - Excerpt: `We found traces of explosives near the storage bunker`
  - Problem: The report then says "No evidence of traditional explosives", and Hosseini says "no traces of gunpowder or conventional explosives".
  - Fix:
    - Line 3339: `- Cause: Unknown. Explosive residue at storage bunker only; destruction of main facility inconsistent with conventional explosives or aerial strikes.`
    - Line 3356: `no conventional explosive signatures at the main facility`

- [ ] AW-79
  - Where: line 3335
  - Category: (e), low confidence
  - Excerpt: `head of the IRGC Intelligence Directorate`
  - Problem: The real body is the IRGC Intelligence Organization.
  - Fix: `head of the IRGC Intelligence Organization`

- [ ] AW-80
  - Where: lines 3342, 3348
  - Category: (e), medium confidence
  - Excerpt: `The Supreme Leader’s representative, a stoic cleric with an impassive demeanor, sat at the head of the table`
  - Problem: The real body is the Supreme National Security Council, and it is chaired by the President. This text calls it the "Supreme Council of National Security".
  - Fix:
    - Line 3348: `the Supreme National Security Council convened`
    - Have the President chair, with the cleric seated beside him.

- [ ] AW-81
  - Where: line 3412
  - Category: (c), low confidence
  - Excerpt: `That’s where Hermes was invaluable during the mission—he cracked under the psychological pressure.`
  - Problem: "He" is ambiguous, and it contradicts "not going to break easily" in the same speech.
  - Fix: `That’s where Hermes was invaluable during the mission—Rezaei cracked under the psychological pressure it applied.`

- [ ] AW-82
  - Where: lines 3428, 3452, 1171
  - Category: (e), low confidence
  - Excerpt: `John Michaels, the Director of Covert Operations`
  - Problem: The CIA has no Director of Covert Operations, Deputy Director of Covert Operations, or "Chief of Operations". The real post is Deputy Director for Operations.
  - Fix: Author decision. Decide this together with AW-46.

- [ ] AW-83
  - Where: line 3448
  - Category: (e), medium confidence
  - Excerpt: `members of the Congressional Intelligence Oversight Committee sat in a semi-circle`
  - Problem: No such committee exists. With a Senator in the chair, the real body would be the Senate Select Committee on Intelligence.
  - Fix: `members of the Senate Select Committee on Intelligence sat in a semi-circle`

- [ ] AW-84
  - Where: line 3462 (cf. 3430, 3440)
  - Category: (g), medium confidence
  - Excerpt: `I can confirm that Colonel Rezaei is in our custody`
  - Problem: She confirms custody of an IRGC colonel in an open hearing with the press present, right after leadership ordered everything "classified at the highest level".
  - Fix: `Senator, I can confirm that the operation dismantled a key component of the IRGC’s narcotics network. Custody questions belong in a classified session.`

- [ ] AW-85
  - Where: line 3522
  - Category: (e), low confidence
  - Excerpt: `In a secure briefing room at Mossad headquarters in Tel Aviv`
  - Problem: Mossad headquarters is at Glilot, north of Tel Aviv.
  - Fix: `at Mossad headquarters north of Tel Aviv`

- [ ] AW-86
  - Where: lines 3538–3578 (cf. IW:15, 33, 45–69; `timeline.md`, line 66)
  - Category: (b), medium confidence
  - Excerpt: `the Israeli Ambassador to the United States, Miriam Katz`
  - Problem: The same pressure campaign in IW and in timeline.md is led by "Ambassador Levi", a man ("He’s citing urgency", IW:33).
  - Fix: Author decision. Either rename Katz to Levi (and change the gender), or show the change of ambassador in IW.

- [ ] AW-87
  - Where: line 3593
  - Category: (d), low confidence
  - Excerpt: `**End of Epilogue.**`
  - Problem: Leftover end marker.
  - Fix: Delete the line.

### Shade of Gray

`story-shade-of-gray.md`: 65 items, 15 high confidence, 12 needing an author decision.

- [ ] SG-01 · front matter L7; L327, 449–557 (esp. 555); timeline.md:33, 39, 45, 51, 57 · (a)(b) · high
  - Excerpt: `"Tomorrow evening. Saturday. Newark docks, berth thirty-seven."`
  - Problem:
    - The front matter `2022-03-19` is a Saturday, yet day 1 is a normal office day with a morning briefing.
    - The story then runs "next three days", "By Thursday", "On Friday morning", and puts Newark on a Saturday. That makes Newark Saturday 26 March, followed by a Sunday debrief.
    - timeline.md puts Newark on Wednesday 23 March and San Francisco on Thursday 24 March, but the debrief on 27 March.
  - Fix (recommended): make day 1 Monday 2022-03-21.
    - Front matter: `timeline: 2022-03-21`.
    - timeline.md: investigation begins 21 March; develops 21–25; Newark 26 March; San Francisco the night of 26–27; aftermath 27 March.
    - See also SG-58 and SG-59.

- [ ] SG-02 · L13 · (e) · low
  - Excerpt: `took the elevator to the fifth floor where the Technology Crimes Division made its home.`
  - Problem: the FBI has no Technology Crimes Division (this work sits in the Cyber Division). timeline.md uses the same name, so it is canon-consistent.
  - Fix: author decision. Keep it as fictional, or use "Cyber Division" here and in timeline.md:34.

- [ ] SG-03 · L19–23, 145–147 · (g) · medium
  - Excerpt: `*We Are Watching.*` / `The phrase had been nagging at her, and now she realized why.`
  - Problem: the card is described as a logo plus a handwritten note. The phrase is never on it, so Marisa can't be recalling it from the card.
  - Fix: on L19, replace `Clean. Professional. Distinctly *not* government issue.` with `Beneath it, in small capitals: *We Are Watching.* Clean. Professional. Distinctly *not* government issue.`

- [ ] SG-04 · L53 and all uses; timeline.md:35 · (c) · low
  - Excerpt: `You may call me Jeane LeBouf.`
  - Problem: "Jeane" is not a French man's name ("Jean" is masculine; "Jeanne" is feminine). "LeBouf" is not a French spelling (Le Bœuf or Leboeuf).
  - Fix: author decision. Keep it as a deliberate alias, or use "Jean LeBœuf" / "Jean Leboeuf" throughout and in timeline.md.

- [ ] SG-05 · L59, 61 · (e) · medium
  - Excerpt: `all marked COSMIC TOP SECRET with additional caveats she'd never seen before`
  - Problem:
    - COSMIC TOP SECRET is a NATO marking, not a US one.
    - A DOE Q clearance (L59) does not grant SCI or JWICS access.
  - Fix:
    - L61: `all marked TOP SECRET//SCI with compartment caveats she'd never seen before`
    - L59: `accessible to you through your TS/SCI clearance`

- [ ] SG-06 · L147, 197; timeline.md:26, 233 · (b) · low
  - Excerpt: `She'd heard it before, years ago, in a different context. A counterintelligence briefing about unexplained interventions in foreign operations.`
  - Problem: timeline.md calls the March 2021 Nightingale extraction the "First documented Federation covert extraction operation", and lists 2021 as "First covert operations with allies". A briefing "years ago" about repeated interventions contradicts that.
  - Fix: author decision. Change "years ago" to "last year", or reword timeline.md to "first documented with the CIA".

- [ ] SG-07 · L191; story-american-wraith.md:45–49, 397–479 · (b) · low
  - Excerpt: `One day our asset was burned and trapped, the next day he was sitting in a safe house in Paris.`
  - Problem: in *The Wraith* the Federation's message reads "Two days", and Nightingale is dropped at a Paris hotel (Room 403), not a safe house.
  - Fix: `One day our asset was burned and trapped, two days later he was checking into a hotel in Paris.`

- [ ] SG-08 · L265, 305, 807, 1057, 1949 · (a) · medium
  - Excerpt: `The counterterrorism specialist—Agent Marcus Chen—leaned forward, frowning.` / `Senior Deputy DA Marcus Chen`
  - Problem: there are three Chens. Marcus Chen the FBI counterterrorism lead, a tactical-team "Chen" at Newark (L807, 1057), and a San Francisco prosecutor also named Marcus Chen.
  - Fix: rename the DA (e.g. `Senior Deputy DA Marcus Holt`, and "Marcus" stays in the dialogue). Either give the tactical-team Chen a distinct name, or state that Marcus Chen joined Hartfield's team.

- [ ] SG-09 · L389 · (c)(g) · medium
  - Excerpt: `We provide the former so you can legitimately obtain the latter.`
  - Problem: "the former" is "the how", which LeBouf has just said ESF withholds. The sentence is reversed.
  - Fix: `We provide the what; you rebuild it through a how that survives scrutiny.`

- [ ] SG-10 · L401, 405, 429, 455, 491, 523 and others; timeline.md:40; codex/foundations/artificial-intelligence.md · (b) · medium
  - Excerpt: `Cipher, I need signals intercept on the Baltimore warehouse...`
  - Problem: Cipher's job (codebreaking, intrusion, banking records, Signal) is exactly the named AI CIPHER's. The codex says named-AI names are "always written in all-uppercase".
  - Fix: author decision. If it is CIPHER, write `CIPHER` throughout, including timeline.md:40. Otherwise rename it so it doesn't collide.

- [ ] SG-11 · L571 · (c) · high
  - Excerpt: `They're based out of Quantico, specialist in urban assault and high-risk interdiction.`
  - Fix: `specialists in urban assault`

- [ ] SG-12 · L619, 671, 727 · (a) · medium
  - Excerpt: `The container ship was scheduled to dock at 2145.` / `Target container is being offloaded now`
  - Problem: the offload report comes at about 2050–2100, before the ship's scheduled docking time.
  - Fix: L619 → `The container ship was scheduled to dock at 2030. The target container would be offloaded by 2100.`

- [ ] SG-13 · L683–685 · (g) · low
  - Excerpt: `With LeBouf's visor retracted, these lens clusters were dark and inert, pushed to the sides of his helmet.`
  - Problem: this gives away the reveal one sentence early. The "But" that opens L685 then no longer contrasts with anything.
  - Fix: delete that sentence from L683. Make L685 read `But his visor was retracted, its lens clusters dark and inert at the sides of his helmet, and Marisa recognized the unremarkable face beneath.`

- [ ] SG-14 · L695 · (g) · medium
  - Excerpt: `aware of everything. Not quite electrical, not quite mechanical, but something that made the air feel charged.`
  - Problem: the sentence about the operators' gaze is spliced into the middle of the description of the humming sound.
  - Fix: move `Even without seeing their eyes behind the visors, … aware of everything.` to the end of the paragraph.

- [ ] SG-15 · L697, 1139; codex/foundations/offensive-weapons/rtk-6-hornet.md · (b) · low
  - Excerpt: `No visible magazines, no ejection ports, no iron sights`
  - Problem:
    - The codex says covert teams' standard rifle is the RTK-6 *Hornet*, which has a 60-round magazine and fires micro-explosive guided rounds.
    - The story's rifles have no magazines and fire "Kinetic impact rounds… minimal lethality".
  - Fix: author decision. Name a different (non-lethal) Federation rifle, or add the round type to the codex.

- [ ] SG-16 · L715, 723, 781 · (a) · low
  - Excerpt: `produced four small devices, each no larger than a hearing aid. "For your team.`
  - Problem: four earpieces cover Hartfield and his three agents, yet Marisa also inserts "her own earpiece".
  - Fix: `produced five small devices` plus `"For your team. And one for you, Agent Comey."`

- [ ] SG-17 · L749 · (c) · low
  - Excerpt: `sealing seamlessly without a visible seam`
  - Fix: `sealing without a visible seam`

- [ ] SG-18 · L805, 935, 1001 · (a) · medium
  - Excerpt: `two hundred meters from the target warehouse` / `The F-150 came to a stop thirty meters from Marisa's position.`
  - Problem: the truck stops at the loading bay 30 m from her. She is also "twenty meters from the entrance" seconds after breaking cover.
  - Fix: L805 → `fifty meters from the target warehouse`

- [ ] SG-19 · L901, 981, 989, 1147, 1153, 2019; timeline.md:49 · (a)(b) · medium
  - Excerpt: `Twelve total. All armed.` / `Twelve armed terrorists. Neutralized in under two minutes.`
  - Problem:
    - Twelve are inside (4+5+3, then "three on the upper level, nine on the main floor") before the five-man pickup team enters, which makes 17 in total. Yet 12 are neutralized and transported.
    - The Encore has "five defendants".
    - timeline.md says "Five suspects apprehended".
  - Fix: author decision. Either set L1147 and L1153 to seventeen, update timeline.md:49 to match, and reconcile SG:2019; or reduce the inside count to seven (L901 `Seven total… two near the loading bay, three in the main floor area, two on the second floor`; L981 `two on the upper level, five on the main floor`).

- [ ] SG-20 · L939–941, 953 · (g) · medium
  - Excerpt: `How the hell had ESF known he needed to adjust before he'd even done it?`
  - Problem: Marisa and Rodriguez react to an ESF instruction that never appears on the page.
  - Fix: insert before L939: `> "Agent Rodriguez, shift six inches right. Your line on the second vehicle is blocked."`

- [ ] SG-21 · L975 · (a) · low
  - Excerpt: `"—Marcus said they finished the second unit—"`
  - Problem: this adds a third Marcus, alongside Agent Marcus Chen, DA Marcus Chen, and canon's Nightingale (Marcus Adams).
  - Fix: `"—Travis said they finished the second unit—"` (or any other name)

- [ ] SG-22 · L831–835, 995–1001, 1017 · (a) · low
  - Excerpt: `Marisa pressed herself against her concrete pillar, her hands shaking`
  - Problem: she had already broken from cover, and her cover was a waist-high "concrete barrier". No pillar was ever introduced.
  - Fix: `Marisa threw herself behind a concrete pillar, her hands shaking`

- [ ] SG-23 · L1029, 1031 · (a) · medium
  - Excerpt: `The third operator.` / `The second ESF operator had taken them all out in seconds`
  - Fix: L1031 → `The third ESF operator had taken them all out in seconds`

- [ ] SG-24 · L1057, 1061 · (a) · medium
  - Excerpt: `Martinez, Rodriguez, take the left flank. Chen, with me on the right.` / `Hartfield entered first, Martinez covering his six.`
  - Fix: `Hartfield entered first, Chen covering his six.`

- [ ] SG-25 · L1077; codex/covops.md § Covert armors, foundations/shields.md · (b) · low
  - Excerpt: `Sparks erupted from the impact point on LeBouf's torso`
  - Problem: the codex says covert armor uses shield generators "in place of ballistic panels", so the bullet should be deflected before it reaches the suit.
  - Fix: author decision. For example: `A ripple of blue light flared a hand's width from LeBouf's torso`

- [ ] SG-26 · L1079, 1147, 1153 · (g) · low
  - Excerpt: `Three controlled shots, center mass. The extremist jerked backward and went down.`
  - Problem: three 5.56 rounds to center mass, yet "Zero enemy fatalities" and "All of them would survive".
  - Fix: author decision. Add `—into a plate carrier` to the shots, or have an ESF round drop the shooter instead.

- [ ] SG-27 · L1111 · (g) · low
  - Excerpt: `But the targets were already down.`
  - Problem: the fight is still going on (L1095, 1103).
  - Fix: `By then, most of the targets were already down.`

- [ ] SG-28 · L1189, 1229 · (a) · low
  - Excerpt: `A slight wind kicked up across the parking lot`
  - Problem: the characters are inside the warehouse, and no parking lot at the docks has been introduced.
  - Fix: `Outside, a slight wind kicked up across the lot beside the warehouse`

- [ ] SG-29 · L1239, 1797 · (a) · high
  - Excerpt: `Fifty meters long at least` / `a forty-meter spacecraft glided silently toward the runway`
  - Fix: L1797 → `a fifty-meter spacecraft`

- [ ] SG-30 · L1249, 1261, 1505, 1529–1531, 1533 · (a) · medium
  - Excerpt: `We have fifty-six minutes` / `They'd crossed the continent in twenty-three minutes.` / `37:12`
  - Problem: 56 minus 23 leaves about 33 minutes, yet the HUD reads 37 minutes after landing.
  - Fix: subtract 6 from every HUD value and dependent number: `31:12…`, `Thirty-one minutes.`, `29:47…`, `27:18…`, and L1569 `twenty-seven minutes`.

- [ ] SG-31 · L1265, 1273 · (a) · low
  - Excerpt: `We'll provide countermeasures—pressure suits, medications, monitoring`
  - Problem: no pressure suits appear; there are only the seat-mounted masks.
  - Fix: `masks, medications, monitoring`

- [ ] SG-32 · L1301, 1765 · (a) · low
  - Excerpt: `Filing emergency flight plan with FAA.` vs `No radar signature, no flight plan, no trace`
  - Fix: delete `Filing emergency flight plan with FAA.`

- [ ] SG-33 · L1239–1241, 1327, 1349, 1429; codex/covops.md § Wraith; air/talon.md · (b) · low
  - Excerpt: `Maximum acceleration. Seven point four gravities.` / `Shade has two vehicles in the cargo bay—Q-cars.`
  - Problem: Shade behaves like a Wraith (two Q-cars, autonomous AI, story line "wraith"), but performs a suborbital boost. The codex gives that capability only to the Talon; the Wraith has "low-emission engines" and intercontinental range.
  - Fix: author decision. State that Shade is a non-standard platform, or add suborbital capability to the codex.

- [ ] SG-34 · L1365 · (e) · high
  - Excerpt: `One hundred thousand feet. The boundary between atmosphere and space, crossed in less than a minute.`
  - Problem: 100,000 ft is about 30 km. The Kármán line is 100 km (about 330,000 ft).
  - Fix: `Three hundred thirty thousand feet. The boundary between atmosphere and space, crossed in under two minutes.` (This stays consistent with the 168 km apogee at L1401.)

- [ ] SG-35 · L1369, 1385 · (a) · high
  - Excerpt: `was beginning to paint the upper atmosphere with the first hints of dawn` / `the Great Lakes glittering in the early morning sun`
  - Problem: the launch happens at about 01:20 ET (landing in San Francisco at 22:43 PT, 23 minutes later). In March the whole continent is dark at that hour.
  - Fix:
    - L1369: end the sentence at `clarity impossible to see from the ground.`
    - L1385: `see the Great Lakes as dark shapes rimmed with city light`, and delete the day/night line clause.

- [ ] SG-36 · L1395, 1779, 1827, 1927, 1933, 1937 · (f) · high
  - Excerpt: `Whatever the EarthSpace Federation was, whatever infrastructure and capabilities they possessed`
  - Problem: Marisa is only ever told "ESF" (L59), and nobody expands the acronym for her. Her point of view can't use "EarthSpace Federation" or "the Federation".
  - Fix:
    - L1395, 1779, 1827, 1927: replace "the EarthSpace Federation" with "ESF".
    - L1933: `the impossible truth of ESF's shadow war`
    - L1937: `ESF assets might be passing overhead`
    - Alternatively, add a beat where LeBouf expands the acronym.

- [ ] SG-37 · L1409 · (a) · medium
  - Excerpt: `And less than twelve minutes to stop it.`
  - Problem: at apogee the devices are about 45 minutes from detonation. Only the landing is 11 minutes away.
  - Fix: `And less than forty-five minutes to stop it.`

- [ ] SG-38 · L1501, 1541 · (a) · high
  - Excerpt: `Local time twenty-two forty-three.` / `a perfect void in the morning light`
  - Fix: `a perfect void in the floodlit night`

- [ ] SG-39 · L1523 · (a) · medium
  - Excerpt: `Hartfield took the back left, Rodriguez the back right, Martinez the seat behind her.`
  - Problem: the seat behind the front passenger is the back right.
  - Fix: `Hartfield took the back left, Rodriguez the middle, Martinez the seat behind her.`

- [ ] SG-40 · L1529–1531, 1547, 1561–1563, 1577–1579 · (a) · low
  - Excerpt: `Estimated time to destination: eight minutes, twelve seconds.`
  - Problem: the HUD drops only about 4 minutes between leaving the airport and reaching the target.
  - Fix: author decision. Make the HUD gap about 8 minutes, or change the estimate to `four minutes, twelve seconds`.

- [ ] SG-41 · L1569, 1577–1579, 1587, 1621 · (a) · high
  - Excerpt: `And they had thirty-five minutes to find it.` / `I estimate ten minutes and thirty-seven seconds until the device reaches full power and detonates.`
  - Problem: the HUD and the narration say about 33 minutes; Shade says about 10.
  - Fix: L1587 → `…I estimate ten minutes and thirty-seven seconds until the capacitor bank reaches critical discharge—well ahead of the network's countdown.`

- [ ] SG-42 · L1597 · (a) · high
  - Excerpt: `The .308 round shattered the lock mechanism`
  - Problem: Hartfield carries an M4, which fires 5.56 (L1061, 1079, 1129).
  - Fix: `The 5.56 round shattered the lock mechanism`

- [ ] SG-43 · L1661, 1665 · (g) · low
  - Excerpt: `Four small hex screws, one at each corner.`
  - Problem: hex screws can't be removed with a Swiss Army knife screwdriver.
  - Fix: `Four small Phillips screws, one at each corner.`

- [ ] SG-44 · L1729 · (a) · medium
  - Excerpt: `This is Special Agent Comey, counter-terrorism.`
  - Problem: she is in Technology Crimes (L13, L161).
  - Fix: `This is Special Agent Comey, Technology Crimes, FBI headquarters.`

- [ ] SG-45 · L1733, 1743, 1765 · (a) · high
  - Excerpt: `dawn was beginning to touch the eastern sky`
  - Problem: the team landed at 22:43, and this is "the next hour" later, so it is about midnight. L1743 and L1765 also describe the morning.
  - Fix (recommended, consistent with SG-49 and SG-50):
    - L1733: `it was past one in the morning`
    - L1765: `manage the night's diverted flights`

- [ ] SG-46 · L1771 · (e) · medium
  - Excerpt: `its eight million residents never knowing how close they'd come`
  - Problem: San Francisco itself has about 0.8 million residents; the Bay Area has about 7.7 million.
  - Fix: `The Bay Area would wake up safe, its eight million residents never knowing how close they'd come`

- [ ] SG-47 · L1773 · (a) · low
  - Excerpt: `Twenty-four hours ago, she'd been a federal agent investigating a routine terrorism case.`
  - Problem: 24 hours earlier she was a week into the EMP case and planning Newark; it was never routine.
  - Fix: `A week ago, she'd been a federal agent working routine tech crimes.`

- [ ] SG-48 · L1775, 1783; cf. L207, L659 · (a) · high
  - Excerpt: `that warning delivered in the sterile conference room that felt like a lifetime ago: *"You're going to see things that will make you question what's possible."*`
  - Problem: Monroe gave the warning by phone, and the quote doesn't match her actual words.
  - Fix: `that warning delivered over a secure line that felt like a lifetime ago: *"You're going to see things that will make you question what you know about technology, about logistics, about what's achievable."*` Adjust L1783's "what was possible" if needed.

- [ ] SG-49 · L1761, 1799 · (a) · high
  - Excerpt: `Local time zero-six-thirty-seven.`
  - Problem: leaving at dawn (about 07:00 PT, 10:00 ET) plus 4.5 hours gives about 14:30 ET.
  - Fix (with SG-45): leave San Francisco at about 02:00 PT. Then `Local time zero-nine-thirty-one.` This also makes "By 1300 hours" (L1855) work after a 3-hour debrief.

- [ ] SG-50 · L1803 · (a) · medium
  - Excerpt: `The landing was as gentle as the takeoff had been brutal twelve hours ago.`
  - Problem: the Newark launch was about 01:20 ET; landing at 06:37 is about 5 hours later (about 8 under SG-49).
  - Fix: `eight hours ago` (with SG-49), or `five hours ago` if the current times are kept.

- [ ] SG-51 · L1805 · (a) · low
  - Excerpt: `Gone were the tactical vests, the combat gear, the obvious military hardware.`
  - Problem: they wore bodysuits and helmets (L683), not vests.
  - Fix: `Gone were the angular bodysuits and helmets, the obvious military hardware.`

- [ ] SG-52 · L1815, 1909 · (a) · medium
  - Excerpt: `Normal cars driven by normal people heading to normal jobs` / `Washington at rush hour`
  - Problem: the morning after the Saturday raid is a Sunday.
  - Fix: depends on SG-01. Either move the Newark raid to a weekday, or use `heading to Sunday brunch` and `The street was busy with weekend crowds.`

- [ ] SG-53 · L1821, 1829 · (a) · high
  - Excerpt: `LeBouf's Toyota was already parked when they arrived, its occupants nowhere to be seen.` / `Marisa caught herself studying LeBouf's reflection in the elevator's polished metal doors.`
  - Problem: LeBouf can't be both absent and beside her in the elevator.
  - Fix: L1829 → `Marisa caught herself thinking of LeBouf as she studied her own reflection in the elevator's polished metal doors.` Alternatively, have LeBouf waiting at the elevator.

- [ ] SG-54 · L1853, 1861, 1863 · (a) · low
  - Excerpt: `federal agents had just returned from orbit`
  - Problem: the flight was suborbital (L1265).
  - Fix: `returned from the edge of space`

- [ ] SG-55 · L1857 · (a) · low
  - Excerpt: `Her coffee mug sat where she'd left it three days ago`
  - Problem: she was at her desk on Friday evening (L557, 621); the debrief is on Sunday.
  - Fix: `two days ago`

- [ ] SG-56 · L1897 · (g) · medium
  - Excerpt: `Somewhere, Shade was probably already being prepped for another mission. Somewhere, the AI had returned to its mysterious duties`
  - Problem: Shade is the AI (L1261), so these two sentences describe the same thing as if they were separate.
  - Fix: `Somewhere, Shade was probably already being prepped for another mission, maintaining the invisible web that kept the world from tearing itself apart.` Delete the following sentence.

- [ ] SG-57 · L1949, 2019; timeline.md:59–60 · (e) · medium
  - Excerpt: `The San Francisco District Attorney's office occupied the fourth floor of a building on Bryant Street, with windows overlooking the Hall of Justice.`
  - Problem: federal WMD and terrorism charges from an FBI case go to the U.S. Attorney's Office (N.D. Cal.), not the county DA. Also, the SF DA's office was historically inside the Hall of Justice (850 Bryant), not across from it.
  - Fix: author decision. For example, `The U.S. Attorney's Office for the Northern District of California…`, `Assistant U.S. Attorney Jennifer Park`, `Senior AUSA Marcus…`, and matching edits in timeline.md.

- [ ] SG-58 · L1957, 1971 · (a) · high
  - Excerpt: `Investigation opened Monday, March twenty.` / `The MLAT request is dated March 22. The investigation opened on the seventh.`
  - Problem: 2022-03-20 was a Sunday. The opening date contradicts itself. If the case opened on the 7th, there is no "forty-eight hours" gap.
  - Fix (with SG-01): `Investigation opened Monday, March twenty-first.` and `The MLAT request is dated March 22. The investigation opened on the twenty-first.`

- [ ] SG-59 · L1961 · (a) · medium
  - Excerpt: `Friday morning, coordinated takedown.`
  - Problem: Friday only brought two Baltimore arrests (L533). The takedown was Saturday night.
  - Fix: `Friday morning, first arrests. Saturday night, coordinated takedown.`

- [ ] SG-60 · L501, 1961 · (a) · low
  - Excerpt: `complete Signal message transcripts between four suspects`
  - Problem: the Signal intercept was "between two of the known associates".
  - Fix: `between two suspects`

- [ ] SG-61 · L1967 · (e) · medium
  - Excerpt: `traveling northbound on Interstate 80 at 2347 hours`
  - Problem: I-80 is signed east–west.
  - Fix: `traveling eastbound on Interstate 80`

- [ ] SG-62 · L1513, 1811, 2043 · (a) · high
  - Excerpt: `a grey Honda Accord sat at a stoplight` vs `The other was a silver Honda Accord.`
  - Fix: `a silver Honda Accord sat at a stoplight`

- [ ] SG-63 · L2057 · (f) · low
  - Excerpt: `That was how the system worked, when the EarthSpace Federation was involved.`
  - Problem: this follows straight on from Jennifer's point of view. It is acceptable only if read as omniscient narration.
  - Fix: author decision. Use `when ESF was involved`, or mark the shift to omniscient narration more clearly.

- [ ] SG-64 · gray: L341, 1339, 1453; grey: L677, 795, 853, 929, 2043 · (c) · low
  - Excerpt: `an off-the-rack suit in charcoal gray` / `A grey minivan, completely unremarkable`
  - Fix: standardize on "gray" (US spelling, matching the title).

- [ ] SG-65 · timeline.md:55 · (b) · low
  - Excerpt: `Q-cars demonstrate physics-defying capabilities in urban pursuit`
  - Problem: there is no pursuit in the story.
  - Fix (timeline.md): `Q-cars carry FBI team across San Francisco at impossible speed`

### Shadows in Tel Aviv

`story-israeli-wraith.md`: 28 items, 9 high confidence, 11 needing an author decision.

- [ ] IW-01
  - Where: lines 7, 177, 225 (cf. 183, 185)
  - Category: (b), high confidence
  - Excerpt: `showing scenes from the Gaza Strip in 2024`
  - Problem: The story is dated `timeline: 2022-07-16`, yet the dossier shows 2024 events and carries entries dated "March 12, 2024" and "June 3, 2024".
  - Fix: Author decision. Either redate the dossier to events before mid-2022 (for example, the May 2021 conflict), or move the story. Moving it conflicts with JW and AiA.

- [ ] IW-02
  - Where: lines 13, 17, 19, 25, 165
  - Category: (e), low confidence
  - Excerpt: `General Anthony Harding, head of the Joint Chiefs, leaned forward, his jaw tight.`
  - Problem:
    - All the office-holders are fictional for July 2022. The real ones were Blinken, Burns, Sullivan, Milley and Lapid. Other canon stories use real leaders, such as Biden in Executive Authority.
    - The correct title is "Chairman of the Joint Chiefs of Staff".
  - Fix: Author decision. At minimum, `Chairman of the Joint Chiefs of Staff`.

- [ ] IW-03
  - Where: lines 15, 33
  - Category: (b), medium confidence
  - Excerpt: `Ambassador Levi is demanding an explanation`
  - Problem: AW's epilogue gives the ambassador as Miriam Katz. See AW-86.
  - Fix: As in AW-86.

- [ ] IW-04
  - Where: lines 17, 55, 91, 129, 217
  - Category: (a) and (b), high confidence
  - Excerpt: `after all, the Radbas operation indirectly supports their regional interests.`
  - Problem: The target is Rudbar in AW (2353, 3317, 3333 and elsewhere).
  - Fix: Replace "Radbas" with "Rudbar" in all five places.

- [ ] IW-05
  - Where: line 17 (cf. AW 3440, 3516)
  - Category: (b), low confidence
  - Excerpt: `The Wraith’s deployment was too public, even with our media blackout efforts.`
  - Problem: AW ends with "the Wraith remained a shadow".
  - Fix: `The Wraith’s footprint was too big to hide completely, even with our media blackout efforts.`

- [ ] IW-06
  - Where: line 21 (cf. `timeline.md`, lines 23–27; AW 1299)
  - Category: (b), medium confidence
  - Excerpt: `Are you telling me that after all these years, we still have no formal way to contact them?`
  - Problem: First contact was in March 2021, about 16 months earlier. Hermes also told Whitaker, "You may contact me directly".
  - Fix: `“Are you telling me that, more than a year in, we still have no formal way to contact them?”`

- [ ] IW-07
  - Where: lines 29, 167
  - Category: (b), low confidence
  - Excerpt: `with two broken swords crossed behind it`
  - Problem: The swords' position is inconsistent. See AW-45.
  - Fix: As in AW-45.

- [ ] IW-08
  - Where: line 31
  - Category: (f), high confidence
  - Excerpt: `The emblem carried weight, a reminder of their alien benefactors’ distant omnipotence.`
  - Problem: The US Secretary of State's point of view knows the Federation has alien backers.
  - Fix: `The emblem carried weight, a reminder of the Federation’s distant omnipotence.`

- [ ] IW-09
  - Where: line 39
  - Category: (d), high confidence
  - Excerpt: `Here’s the continuation of Chapter 1:`
  - Problem: Drafting leftover addressed to the writer.
  - Fix: Delete the line.

- [ ] IW-10
  - Where: lines 75–77
  - Category: (g), low confidence
  - Excerpt: `No doubt Harris had already heard about her slip.`
  - Problem: Harris knows about the slip seconds after Levi leaves the room.
  - Fix: Author decision. For example, `Within the hour, her intercom buzzed.`

- [ ] IW-11
  - Where: line 79
  - Category: (c), low confidence
  - Excerpt: `“Secretary Vance,” Harris’s voice was terse, almost accusatory.`
  - Problem: The dialogue is joined to a non-speech clause by a comma.
  - Fix: `“Secretary Vance.” Harris’s voice was terse, almost accusatory.`

- [ ] IW-12
  - Where: line 89
  - Category: (c), low confidence
  - Excerpt: `And god knows they can do that.`
  - Problem: "God" should be capitalized in this idiom.
  - Fix: `And God knows they can do that.`

- [ ] IW-13
  - Where: lines 139–143 (cf. AW 1221, 1299)
  - Category: (b), medium confidence
  - Excerpt: `you’re not just an operational AI, are you? You’re the closest thing we have to a direct line to the Federation.`
  - Problem: Harris presents this as a realization, but Hermes introduced itself to the CIA as "AI liaison for the Federation".
  - Fix: Author decision. For example, line 139 becomes `“Hermes,” he said slowly, “you told Whitaker you were the Federation’s liaison. I need you to be one now.”` Then adjust 141–143.

- [ ] IW-14
  - Where: line 157
  - Category: (c), low confidence
  - Excerpt: `“Handled? How? By who?”`
  - Problem: Formally "By whom?", but it is fine as speech.
  - Fix: Optional.

- [ ] IW-15
  - Where: lines 181–185, 225, 263 (cf. `timeline.md`, lines 83–88; AiA lines 11, 87, 1105)
  - Category: (b), high confidence
  - Excerpt: `operational reports from the Federation’s Landmate peacekeeping forces. He read with mounting dread.`
  - Problem:
    - Canon makes June 13, 2024 the first Landmate deployment. The dossier's entries predate it.
    - In Angels in Armor (AiA), "Mossad's blind" and "No nation claims them" in June 2024.
    - The name "Landmates" is coined by a television commentator (AiA:1105).
    - This conflict remains even if the story's date moves.
  - Fix: Author decision.

- [ ] IW-16
  - Where: lines 209–245, especially 217 (cf. CLAUDE.md; `timeline.md`, lines 85, 88, 236–237; AiA:87)
  - Category: (b), medium confidence
  - Excerpt: `It is a response from an entity that needs no introduction—the EarthSpace Federation.`
  - Problem:
    - A public, emergency Knesset session names the Federation and describes its forces in 2022. Canon puts the first open intervention and first formal acknowledgment in 2024.
    - "the operation we all observed… commonly known as the Radbas strike" also implies a public that knew about a covert raid.
  - Fix: Author decision. Make it a closed cabinet or security-cabinet session, and keep the Federation's name off the record.

- [ ] IW-17
  - Where: line 221 (cf. 197–199, 229)
  - Category: (a), low confidence
  - Excerpt: `he opened the dossier to its first page, the Federation’s insignia emblazoned above its message`
  - Problem: The message is on the last page.
  - Fix: `he opened the dossier to its first page, the Federation’s insignia emblazoned at its head`

- [ ] IW-18
  - Where: lines 249–287, especially 275 (cf. AiA lines 11–15)
  - Category: (b) and (e), high confidence
  - Excerpt: `civilians reporting a cautious optimism that had been absent for decades.`
  - Problem: The 2022–2024 montage shows a calmer Gaza. That contradicts October 7, 2023 and the war that followed, and Angels in Armor's June 2024 opening of Merkava tanks advancing "through the ruins of Zeitoun".
  - Fix: Author decision.

- [ ] IW-19
  - Where: line 257
  - Category: (e), low confidence
  - Excerpt: `The Knesset passed a series of sweeping reforms aimed at addressing systemic issues in the occupied territories.`
  - Problem: The 24th Knesset dissolved on June 30, 2022, and elections were held in November 2022.
  - Fix: Author decision.

- [ ] IW-20
  - Where: lines 273, 283, 293 (cf. JW lines 23, 113–114)
  - Category: (b), medium confidence
  - Excerpt: `Months turned into a year, and the Federation remained silent.`
  - Problem: IW's sequence puts Tsel's arrival a year or more after July 2022, on a summer morning. JW, dated February 2023, already has Israel receiving Federation advances "in recent months", tech that was "withheld… until they changed their ways".
  - Fix: Author decision. Compress the timeline:
    - Line 273: "Months passed".
    - Line 283: "As winter set in".
    - Line 293: "a winter morning".
    - Adjust the heat references at 295, 305, 343, 349, 419 and 449.

- [ ] IW-21
  - Where: lines 289, 347, 429
  - Category: (g), medium confidence
  - Excerpt: `##  `
  - Problem: Empty chapter and scene headings.
  - Fix: Author decision. For example, `## The Shadow`, `### Boarding Party`, `### Proof of Concept`.

- [ ] IW-22
  - Where: lines 293, 309
  - Category: (e), low confidence
  - Excerpt: `Colonel Noam Feld, the commanding officer of the facility, stepped forward. Dressed in a crisp flight suit`
  - Problem: The Mossad is a civilian service and runs neither airfields nor military ranks.
  - Fix: Line 293 becomes `the covert Israeli Air Force facility used by the Mossad`.

- [ ] IW-23
  - Where: line 299 (cf. 49–51)
  - Category: (f), medium confidence
  - Excerpt: `Its angular frame was unmistakable: a Federation Wraith.`
  - Problem: No Israeli has ever seen a Wraith; only the name leaked, through Vance's slip.
  - Fix: `Its angular frame matched nothing in any Israeli inventory, and on its flank was the Federation’s insignia.`

- [ ] IW-24
  - Where: lines 411–413
  - Category: (f), medium confidence
  - Excerpt: `“It *is* alien, Ziv. That’s why it’s here.`
  - Problem: An Israeli colonel says outright that the craft is alien, which breaks the setting's secrecy about aliens.
  - Fix: `“It *is* beyond us, Ziv. That’s why it’s here.`

- [ ] IW-25
  - Where: line 419 (cf. 431–443)
  - Category: (g), high confidence
  - Excerpt: `As the operatives exited the Wraith and stepped back into the desert heat, the group was quiet`
  - Problem: The Wraith then seals its ramp and takes off with the operatives inside, holding a rail.
  - Fix: `As the operatives gathered at the top of the ramp, the desert heat rolling in through the open hatch, the group was quiet, their earlier skepticism tempered by the overwhelming sense of possibility.`

- [ ] IW-26
  - Where: line 461 (cf. 447)
  - Category: (g), low confidence
  - Excerpt: `unless you drew attention to yourselves by opening a hatch or projecting external lights.`
  - Problem: They have just opened a window panel.
  - Fix: `…unless you drew attention to yourselves by lowering the ramp or projecting external lights.`

- [ ] IW-27
  - Where: line 449
  - Category: (e), high confidence
  - Excerpt: `the sprawling modern architecture of the Tel Aviv Museum of Fine Arts.`
  - Problem: The real name is the Tel Aviv Museum of Art.
  - Fix: `the Tel Aviv Museum of Art`

- [ ] IW-28 · lines 289, 347, 429 · (g) · high
  - Excerpt: `##` / `###` / `###`
  - Problem: three empty headings, found by the mechanical scan. They render as blank heading lines.
  - Fix: author decision. Give each a title, or remove them.

### Silent Watchers

`story-japanese-wraith.md`: 51 items, 7 high confidence, 8 needing an author decision.

- [ ] JW-01 · L11, 13, 154, 498; timeline.md:74 · (e) · low
  - Excerpt: `high-ranking officers of the Japanese Defense Intelligence Agency (DIA)`
  - Problem: the real Japanese body is the Defense Intelligence Headquarters (DIH, 情報本部); "DIA" is the US agency. timeline.md matches the story.
  - Fix: author decision. Keep it as fictional, or rename it everywhere.

- [ ] JW-02 · L13, 39, 158, 168, 1371, 1379, 1381 · (b) · medium
  - Excerpt: `A holographic map of the Sea of Japan shimmered above the round table`
  - Problem: CLAUDE.md says non-Federation entities use contemporary technology. Holographic tables at DIA Tokyo and in the Hokkaido briefing room break that.
  - Fix:
    - L13: `A large wall display showed a map of the Sea of Japan`
    - L39: `The display flickered`
    - L158: `As the projector blinked to life`
    - L168: `the map on the display`
    - L1371: `the map projected onto the table`
    - L1379: `the projected map zoomed in`
    - L1381: `The display shifted`

- [ ] JW-03 · L15, 2103; L540, 1817 · (a) · low
  - Excerpt: `Commander Takashi Mori stated` / `Lieutenant Mori, standing beside him` / `“This is Major Tanaka at Kaneda AFB.`
  - Problem: two Moris, and two Tanakas (agent Tanaka and Major Tanaka) who appear in the same chapters.
  - Fix: author decision. For example, `Major Hayashi` and `Lieutenant Sakamoto`.

- [ ] JW-04 · L97–107, 138–150 · (g) · high
  - Excerpt: `the chat disconnected abruptly, leaving her staring at the blank page` / `Nishi stared at the blank chat screen`
  - Problem: the chat disconnects and she closes the laptop for the night (L103). The chat then resumes (L107), and the night ends a second time (L148).
  - Fix: delete L97's disconnect sentence through L103. Or open L107 with `Minutes later, she opened the laptop again. The chat window was still there, cursor blinking.`

- [ ] JW-05 · L158–160 · (g) · low
  - Excerpt: `She played the recording of the chat`
  - Problem: no recording was ever made, and the laptop powered itself down (L138).
  - Fix: `She displayed the chat log she had screen-captured before the laptop shut down`

- [ ] JW-06 · L216–219, 346–349 · (c) · low
  - Excerpt: `**To: General Saito, Colonel Yamada**` / `Sir,`
  - Problem: the email has two addressees but a singular salutation.
  - Fix: `Sirs,`

- [ ] JW-07 · L298 · (f) · high
  - Excerpt: `a web of influence involving external powers both terrestrial and extraterrestrial.`
  - Problem: a Federation AI reveals alien actors to a DIA officer. This breaks the core asymmetry in CLAUDE.md, and Nishi doesn't react.
  - Fix: `a web of influence involving external powers.`

- [ ] JW-08 · L394 · (a)(b) · low
  - Excerpt: `The frost on the ground melted as the craft’s faint heat signature rippled through the air.`
  - Problem: the Wraith has "thermal masking" (L586, and the codex Wraith stealth section).
  - Fix: delete the sentence, or `The frost beneath it glittered, untouched.`

- [ ] JW-09 · L406–432, 444–490 · (g) · medium
  - Excerpt: `“And you trust this machine? This Federation?”`
  - Problem: the acceptance scene ends, then "Ripples of the Unknown" replays it. Saito asks again what the Federation wants (L448 vs L416), and the faith/trust exchange repeats (L466 vs L428).
  - Fix: author decision. Merge the two into one scene; cut L428, or L466–468.

- [ ] JW-10 · L422, 446, 458 · (a) · low
  - Excerpt: `“There is no catch,” the AI said simply.`
  - Problem: the AI goes on to set conditions and threaten withdrawal.
  - Fix: `“There are conditions,” the AI said simply. “But no catch. Only trust.`

- [ ] JW-11 · L424, 542, 578; codex/covops.md § Operational security · (b) · medium
  - Excerpt: `displaying detailed schematics of the Wraith’s capabilities`
  - Problem: the codex says that not even allies get the specifications of covert-ops assets.
  - Fix: replace "schematics" with "capability overviews". For example: L424 `displaying an overview of the Wraith’s capabilities`; L542 `A rotating model of the craft appeared`; L578 `a demonstration of the craft’s cloaking`.

- [ ] JW-12 · L526, 1691 · (a) · medium
  - Excerpt: `“I’ll assign Agent Ishikawa as team lead.` / `“Lieutenant Ishikawa, the trajectory data contains a critical error.”`
  - Fix: `“Agent Ishikawa, the trajectory data contains a critical error.”`

- [ ] JW-13 · L548, 694, 870 · (g) · medium
  - Excerpt: `“生霊少女,” the analyst supplied, stumbling over the pronunciation. “It means ‘Wraith Girl,’ I think.`
  - Problem: Japanese speakers wouldn't stumble over, or need a gloss for, a Japanese phrase.
  - Fix: `“生霊少女,” the analyst supplied. “Supposedly, she said it, and bam, there it was.”` Move the glosses at L548 and L870 into narration.

- [ ] JW-14 · L550; cf. L252, 264, 322 · (a) · low
  - Excerpt: `“No offense, but your voice is a little… intimidating.`
  - Problem: earlier the voice is "soft, distinctly feminine… oddly welcoming" and "soothing".
  - Fix: author decision. Change Tanaka's complaint (e.g. "a little… formal"), or drop the earlier descriptors.

- [ ] JW-15 · L578–584 · (g) · medium
  - Excerpt: `This was only the beginning.` then `The holographic projections around the cabin flickered as the Wraith’s AI began explaining the platform’s myriad features.`
  - Problem: a scene-closing line is followed straight away by a restart of the same demonstration.
  - Fix: delete L580–582. Change the opening of L584 to `The projections expanded as the AI began walking them through the platform’s features.`

- [ ] JW-16 · L634; story-american-wraith.md:1221; story-israeli-wraith.md:139 · (b) · medium
  - Excerpt: `involving an infiltration team codenamed *Hermes*`
  - Problem: in canon, Hermes is the CIA Wraith's AI.
  - Fix: `codenamed *Mercury*` (unless the reuse is intended).

- [ ] JW-17 · L760, 772–776 · (a) · medium
  - Excerpt: `“You all remember that drill we ran last week?` / `during their simulation runs`
  - Problem: these rumors come before the team's first exercise, only days after the Wraith appeared.
  - Fix: `that drill we ran yesterday?`, and `during their first systems test`.

- [ ] JW-18 · L778, 1210, 1220, 1236, 1319, 1349 · (e) · medium
  - Excerpt: `“Wait,” a young marine interjected`
  - Problem: Japan has no marine corps; the nearest equivalent is the JGSDF Amphibious Rapid Deployment Brigade.
  - Fix: replace "marine(s)" with "sergeant" or "soldiers" as context requires.

- [ ] JW-19 · L1194 · (c) · low
  - Excerpt: `Takeda lingered for a moment, his gaze lingering on the Wraith’s avatar.`
  - Fix: `his gaze resting on the Wraith’s avatar.`

- [ ] JW-20 · L1254, 1887, 1983, 2071, 2125, 2175, 2233, 2267 · (d) · high
  - Excerpt: `### Scene: The Wraith’s Playful Encore`
  - Fix: drop "Scene: " from all eight headings.

- [ ] JW-21 · L1381, 1677–1689 · (a) · medium
  - Excerpt: `You will need to copy it onto this,” he said, holding up a small, encrypted data drive` / `Okabe wasted no time, pulling out his compact camera.`
  - Problem: the briefing hands over a data drive, but Okabe photographs screens instead and the drive is never used.
  - Fix: `Okabe wasted no time, slotting the encrypted drive into the isolated terminal.` and adjust "snapped images" and "photographing" to copying.

- [ ] JW-22 · L1439 · (g) · low
  - Excerpt: `The Wraith’s ramp began to retract as the team boarded`
  - Problem: Ishikawa then turns "at the top", so the ramp retracts too early.
  - Fix: `The team boarded, their boots clanging softly against the metal ramp.`

- [ ] JW-23 · L1477 · (e) · medium
  - Excerpt: `described as having a tiger’s body, a snake’s tail, a monkey’s face, and the wings of a bird.`
  - Problem: the folklore Nue has a monkey's face, a tanuki's body, a tiger's limbs and a snake for a tail. It has no wings.
  - Fix: `described as having a monkey’s face, a tanuki’s body, a tiger’s limbs, and a snake for a tail.`

- [ ] JW-24 · L1479 · (e) · low
  - Excerpt: `asymmetrical, feathered wings adorned its back, reminiscent of the Nue from *Touhou Project*`
  - Problem: Touhou's Nue has non-feathered appendages: red blades on one side, blue arrows on the other.
  - Fix: `asymmetrical wings—red blades on one side, blue arrows on the other—adorned its back`

- [ ] JW-25 · L1507 · (a) · low
  - Excerpt: `their boots touching down on the soft grass`
  - Problem: the setting is late February in North Korea.
  - Fix: `on the frozen ground`

- [ ] JW-26 · L1531, 2025 · (a) · low
  - Excerpt: `Ishikawa pulled the door open` vs `the door slid open.`
  - Fix: L2025 → `the door swung open.`

- [ ] JW-27 · L1685 · (c) · medium
  - Excerpt: `its capabilities detailed in meticulous detail.`
  - Fix: `its capabilities laid out in meticulous detail.`

- [ ] JW-28 · L1753 · (d) · high
  - Excerpt: `The scene would continue, the weight of the decision pressing heavily as Nishi prepared to rally all available resources to prevent a disaster.`
  - Fix: delete the line.

- [ ] JW-29 · L1757; cf. L1371 · (a) · low
  - Excerpt: `General Miyazawa, a veteran with decades of experience, stood at the head of the table`
  - Problem: General Saito briefed the team at Hokkaido hours earlier, then vanishes from the story.
  - Fix: author decision. Use Saito here, or explain his absence.

- [ ] JW-30 · L1763 · (c) · low
  - Excerpt: `“*Nue*??” Miyazawa interrupted`
  - Fix: `“*Nue*?”`

- [ ] JW-31 · L1775 · (c) · low
  - Excerpt: `Iwata slammed a fist lightly against the table.`
  - Fix: `Iwata brought a fist down on the table.`

- [ ] JW-32 · L1783–1785 · (e) · medium
  - Excerpt: `The U.S. Seventh Fleet has Aegis-equipped ships patrolling the Pacific.`
  - Problem: the JMSDF operates its own Aegis BMD destroyers.
  - Fix: `Our Aegis destroyers in the Sea of Japan could try, if they’re in position—`, and adapt Miyazawa's reply (for example, "trajectory deviation" instead of "political nightmare").

- [ ] JW-33 · L1795, 1797, 2133; codex/air/talon.md · (b) · medium
  - Excerpt: `“The JSDF has two Talon fighters stationed at Kaneda Air Base in Okinawa for evaluation purposes.`
  - Problem: the VSX-7 Talon is a Federation aircraft whose "advanced technology remains a closely guarded secret". JSDF ownership is not established anywhere.
  - Fix: author decision. For example, `The Federation has two Talons on loan to the JSDF at Kaneda Air Base…`

- [ ] JW-34 · L1795, 1817, 1977 · (e) · low
  - Excerpt: `“This is Major Tanaka at Kaneda AFB.`
  - Problem: Kaneda is fictional (the real Okinawa bases are Kadena, USAF, and Naha, JASDF), and "AFB" is US nomenclature.
  - Fix: `Kaneda Air Base` at L1817 and L1977, or switch to Naha.

- [ ] JW-35 · L1803, 1930 · (a)(e) · medium
  - Excerpt: `intercept the missile at its peak altitude` / `[Nue]: Target altitude: 30,000 feet.`
  - Problem: a North Korea–Tokyo ballistic missile peaks hundreds of kilometres up.
  - Fix: L1930 → `[Nue]: Target altitude: 410 kilometers. Interception window: 90 seconds.` (The codex Talon is space-capable.)

- [ ] JW-36 · L1831 · (a) · medium
  - Excerpt: `“Generals, may I remind everyone`
  - Problem: only one general is present.
  - Fix: `“General, may I remind everyone`

- [ ] JW-37 · L1843, 1857, 2073, 2089, 2093, 2113, 2187, 2231, 2265, 2285, 2309 · (c) · low
  - Excerpt: `two sleek Talon fighters sat in their paddocks`
  - Problem: "paddock" is a horse or motor-racing term.
  - Fix: `shelters` throughout.

- [ ] JW-38 · L1855 · (g) · high
  - Excerpt: `as the Talons’ landing gear unlocked and began to retract.`
  - Problem: the aircraft are still on the ground, before taxiing.
  - Fix: `as the Talons’ brakes released and the jets began to roll.`

- [ ] JW-39 · L1917, 1951, 1981 · (e) · medium
  - Excerpt: `#### Over the Pacific: The Talons’ Approach`
  - Problem: the trajectory crosses the Sea of Japan, not the Pacific.
  - Fix: `Over the Sea of Japan` in both headings, and `High above the Sea of Japan` at L1981.

- [ ] JW-40 · L1935 · (a) · medium
  - Excerpt: `Nue monitored their progress from Hokkaido`
  - Problem: Nue is the Wraith, still over North Korea waiting for the team.
  - Fix: `Nue monitored their progress from North Korean airspace, her avatar glowing faintly on the screens in the Hokkaido situation room.`

- [ ] JW-41 · L1987, 1991; cf. L1739, 1773 · (a) · low
  - Excerpt: `The distant roar of the missile launch had reverberated through the compound` / `Personnel in the control room have identified the trajectory error.`
  - Problem: the launch site is "a separate facility", and Nue "has no direct line of sight" to it.
  - Fix: author decision. For example, `Radio traffic indicates the control room has identified the trajectory error.`

- [ ] JW-42 · L1987, 1999, 2019–2031; cf. L1397 · (g) · medium
  - Excerpt: `The team huddled in the shadows near the missile facility’s perimeter`
  - Problem: the team is already outside, yet exits through the tunnel, which leads from the perimeter into the building.
  - Fix: L1987 → `The team huddled in a first-floor storeroom near the maintenance-level stairs`

- [ ] JW-43 · L2135, 2161, 2213, 2217 · (f) · medium
  - Excerpt: `Uncommon for Earth-based operations` / `integrating these systems into Earth’s defense frameworks`
  - Problem: these lines imply the Federation operates off Earth, hinting at the alien dimension to JSDF officers.
  - Fix: `Uncommon for national forces`; `extraordinary for national forces`; `into national defense frameworks`; `National forces are still adapting`.

- [ ] JW-44 · L2149; cf. L1831–1835, 1883 · (a) · medium
  - Excerpt: `But I didn’t realize it would trigger an autonomous deployment.`
  - Problem: Nue explicitly asked for autonomous launch, and Nishi told Kaneda the Talons were "under autonomous control".
  - Fix: `“I—yes, I gave the order. I just didn’t expect it to happen that fast.”`

- [ ] JW-45 · L2177 · (a)(b) · low
  - Excerpt: `The roar of the Wraith’s engines had barely faded`
  - Problem: elsewhere the Wraith is near-silent, and the codex gives it low-emission engines.
  - Fix: `The hum of the Wraith’s engines had barely faded`

- [ ] JW-46 · L2177, 2235, 2245 · (a) · medium
  - Excerpt: `bathed in the afternoon sun` / `unusually lively for a midday meal` / `delivering the Federation big shots this morning`
  - Problem: the arrival is in the afternoon, yet the following scene is lunch and Sato says "this morning".
  - Fix: L2177 → `bathed in the late-morning sun`

- [ ] JW-47 · L2203–2205; cf. L1817–1833 · (a) · medium
  - Excerpt: `There wasn’t time to brief anyone here or coordinate a more traditional response.`
  - Problem: Major Tanaka was on the line when the autonomous launch was proposed and ordered.
  - Fix: `There wasn’t time to wait for your pilots.` At L2205: `You authorized an autonomous launch over this base’s objections?`

- [ ] JW-48 · L2287 · (c) · low
  - Excerpt: `In a situation where everyone was scrambling to orient themselves—with tools we wouldn’t have considered, in ways we never thought of—`
  - Problem: the clause between the dashes dangles and attaches to the wrong subject.
  - Fix: `While everyone was scrambling to orient themselves, she used tools we wouldn’t have considered, in ways we never thought of; by the time we grasped the situation, she had already solved it halfway.`

- [ ] JW-49 · L2303 · (c) · low
  - Excerpt: `As the group sat back down`
  - Problem: only Miyazawa had stood (L2299).
  - Fix: `As Miyazawa sat back down`

- [ ] JW-50 · e.g. L1467, 1477 vs L590, 1505, 1569, 1691, 2151, 2287 · (a) · low
  - Excerpt: `its tone neutral` vs `Nue worked her digital magic`
  - Problem: Nue's pronoun alternates between "it" and "she".
  - Fix: author decision. Choose one; "she" after the naming at L1479 would be a natural rule.

- [ ] JW-51 · line 1761 · (c) · high
  - Excerpt: `“Yes, sir,” Nishi replied, her tone steady despite the pressure. “Nue’s analysis—"`
  - Problem: the second quotation opens with a curly quote and closes with a straight one, found by the mechanical scan.
  - Fix: `“Nue’s analysis—”`

### P = NP

`story-p-np.md`: 19 items, 1 high confidence, 3 needing an author decision.

- [ ] PNP-01 · L11 · (c) · high
  - Excerpt: `### Cambridge, Massachusettes`
  - Fix: `### Cambridge, Massachusetts`

- [ ] PNP-02 · L15, 598 · (a) · low
  - Excerpt: `Independent Research Consultant` vs `I'm just an independent software consultant.`
  - Fix: `I'm just an independent research consultant.`

- [ ] PNP-03 · L23 · (c) · low
  - Excerpt: `millions of combinatoric permutations`
  - Fix: `combinatorial permutations`

- [ ] PNP-04 · L53 · (e) · low
  - Excerpt: `No commercial processor even breaks 20 stable qubits. Hell, Google's Sycamore barely holds at 50`
  - Problem: by March 2024, IBM processors had 127 to 1,121 physical qubits, and Sycamore had 53. The line is defensible only if it means logical qubits.
  - Fix: `No processor even breaks 20 stable logical qubits.`

- [ ] PNP-05 · L77 · (g) · low
  - Excerpt: `typed in a URL at random—his university's email server`
  - Problem: picking his own university's server is a deliberate choice, not random.
  - Fix: `typed in the first URL that came to mind—his university's email server`

- [ ] PNP-06 · L91 · (e) · low
  - Excerpt: `Factored a 2048-bit RSA modulus in sixteen seconds. Give or take. Polynomial time, Ethan. *P = NP*.`
  - Problem: fast factoring doesn't prove P = NP (factoring is not known to be NP-complete, and quantum polynomial time is BQP). Ethan, an expert, lets it pass.
  - Fix: author decision. Give Ethan an objection (e.g. "Factoring isn't NP-complete") that Mira brushes off.

- [ ] PNP-07 · L167 · (c) · medium
  - Excerpt: `advised half of Fortune 500.`
  - Fix: `advised half of the Fortune 500.`

- [ ] PNP-08 · L379, 526 · (a) · medium
  - Excerpt: `drop a fire extinguisher at *exactly* 14:03:11.` / `*Shooter-E.M. intersection @ 17:42:17`
  - Problem: the action in between is continuous (minutes), not three and a half hours.
  - Fix: `@ 14:27:17`

- [ ] PNP-09 · L419 · (e) · low
  - Excerpt: `With a 35 psi dry chemical suppressor.`
  - Problem: stored-pressure dry-chemical extinguishers run at about 100–195 psi.
  - Fix: `With a 195 psi dry chemical suppressor.`

- [ ] PNP-10 · L445 · (c) · low
  - Excerpt: `the extinguished stairwell was quiet`
  - Problem: "extinguished" reads as an error, unless it is meant as a pun.
  - Fix: `the stairwell was quiet`

- [ ] PNP-11 · L453 · (c) · low
  - Excerpt: `back against a faux-Ottoman`
  - Fix: `back against a faux ottoman`

- [ ] PNP-12 · L481 · (c) · low
  - Excerpt: `Closer to ninety-nine-point-nine. But not quite one.`
  - Problem: the line mixes a percentage with a probability.
  - Fix: `But not quite a hundred. *Never* a hundred.`

- [ ] PNP-13 · L505 · (a) · low
  - Excerpt: `the glow of her laptop reflecting in one lens.`
  - Problem: Mira is never established as wearing glasses.
  - Fix: `reflecting in her eyes.`

- [ ] PNP-14 · L523, 540, 542 · (g) · low
  - Excerpt: `the shaft wall—and, below that, the top lip of the fifth floor.`
  - Problem: with the car stuck at floor 4.5, the fifth-floor sill is above the car, not below.
  - Fix: `the shaft wall—and, above that, the bottom lip of the fifth floor.`

- [ ] PNP-15 · L526 · (c) · low
  - Excerpt: `*Shooter-E.M. intersection`
  - Problem: the initials don't match Ethan Walsh (E.W.) or Mira Hale (M.H.).
  - Fix: author decision. `Shooter-E.W.`?

- [ ] PNP-16 · L580, 612, 620 · (a) · medium
  - Excerpt: `The terrorists were cuffed or bagged.`
  - Problem: "bagged" reads as body bags, against "without a single fatality" and "Zero fatalities".
  - Fix: `The terrorists were cuffed and led away.`

- [ ] PNP-17 · L660 · (e) · low
  - Excerpt: `Nobody had 512-qubit platforms. Not yet.`
  - Problem: IBM's Osprey (433 qubits) and Condor (1,121) predate March 2024.
  - Fix: `Nobody had 512 stable logical qubits. Not yet.`

- [ ] PNP-18 · timeline.md · (b) · low
  - Problem: P = NP (2024-03-19) is missing from timeline.md.
  - Fix: add an entry.

- [ ] PNP-19 · L343–361, 461–489; codex · (b) · low
  - Excerpt: `Yes. We're nudging probability space.`
  - Problem: the codex has nothing on quantum probability-steering.
  - Fix: author decision. Add a codex entry, or treat it as unique to Mira.

### Angels in Armor

`story-angels-in-armor.md`: 55 items, 8 high confidence, 11 needing an author decision.

- [ ] AIA-01 · line 13 · (e) · low
  - Excerpt: `through the ruins of Zeitoun` … `pressing toward Gaza City`
  - Problem: Zeitoun is itself a district of Gaza City.
  - Fix: `pressing deeper into Gaza City`
- [ ] AIA-02 · line 15 · (e)(g) · medium
  - Excerpt: `Somewhere in the city beyond, his niece's left arm had been taken by a rocket-propelled grenade on October 7th.`
  - Problem: the 7 October attacks happened inside Israel, but the sentence places the injury in the Gaza city ahead of him.
  - Fix: `His niece had lost her left arm to a rocket-propelled grenade on October 7th; the men who fired it were somewhere in the city beyond.`
- [ ] AIA-03 · line 29 · (c) · high
  - Excerpt: `some new deep-penetration ordinance, maybe American`
  - Problem: wrong word.
  - Fix: `ordnance`
- [ ] AIA-04 · line 29 · (g) · low (optional)
  - Excerpt: `retro-rockets ignited at the last hundred feet`
  - Problem: an imperial unit in an Israeli officer's point of view; the IDF scenes otherwise use metric (273, 405, 459).
  - Fix: `at the last thirty meters`
- [ ] AIA-05 · line 33 (also 65 "titans", 81 "colossal", 1998 "a hundred titanic forms") · (b) · high
  - Excerpt: `They were humanoid - massive, bipedal, twice the height of a tank`
  - Problem: codex/land/landmate.md and land.md give 3 m, and The Helpers has "Ten three-meter-tall machines". A Merkava is about 2.7 m tall, so "twice the height" makes them about 5.5 m.
  - Fix: `as tall as the tank's turret roof`. Author decision on whether to tone down "titanic" and "colossal" or keep them as Mazar's hyperbole.
- [ ] AIA-06 · lines 33, 948, 1728 · (a)(b) · medium
  - Excerpt: `encircled by laurels on its chest, flanked by two crossed broken swords` / `flanked by two broken swords crossed in saltire beneath it`
  - Problem: the logo drifts. The laurels "encircle" (33) or "flank" (1728); the swords "flank" (33) or sit "beneath" (1728); line 948 says both "flanked" and "beneath". CLAUDE.md: "wireframe globe encircled by laurels, with two broken swords crossed saltire".
  - Fix: standardize on "a wireframe globe encircled by laurels, two broken swords crossed in saltire beneath it":
    - 33: `…on its chest, two broken swords crossed in saltire beneath it`
    - 948: `encircled by classical laurel branches, with two broken swords crossed in saltire beneath it.`
    - 1728: `the wireframe globe, encircled by laurel branches, broken swords crossed beneath.`
- [ ] AIA-07 · line 57 · (e) · low
  - Excerpt: `CNN, live from Gaza. Something extraordinary is happening.`
  - Problem: Israel barred foreign journalists from entering Gaza independently in 2024.
  - Fix: author decision. Make Leila a Gaza-based local journalist filing for CNN, or accept it as an alternate-history liberty.
- [ ] AIA-08 · line 65 · (e) · low
  - Excerpt: `Far away in the IDF HQ, Brigadier-General Tamir Gonen stood in a command post`
  - Problem: IDF Southern Command is led by a major general (aluf).
  - Fix: author decision. Make Gonen a "Major General", or his deputy.
- [ ] AIA-09 · line 65 · (c) · low
  - Excerpt: `He didn't flinch. But he issued the order without hesitation.`
  - Problem: the "But" sets up a contrast that isn't there.
  - Fix: `He didn't flinch. He issued the order without hesitation.`
- [ ] AIA-10 · lines 79, 425, 537, 1321, 1619 vs 1525, 1746, 1866, 1869, 1901, 1913, 2016, 2118 (and EA:169) · (a) · high
  - Excerpt: `Khan Yunis` / `Khan Younis`
  - Problem: the spelling alternates.
  - Fix: use `Khan Younis` (the later chapters, the headings and EA all do) at 79, 425, 537, 1321 and 1619.
- [ ] AIA-11 · lines 129, 149 · (f) · medium
  - Excerpt: `around the Landmate closest to the rogue tank`
  - Problem: the narration, in Mazar's point of view, says "Landmate" on Arrival Day, but Prof. Watanabe only coins the word on Day 4 (1105).
  - Fix: 129 `around the machine closest to the rogue tank`; 149 `streaked downrange toward the machine.`
- [ ] AIA-12 · line 191 (also 199, 209, 217, 337, 340, 358, 374) vs 629–631, 1285 · (a) · high
  - Excerpt: `what are being called the 'Golems'` / `they've started calling them *Golems*.` / `which we first heard from Colonel Mazar`
  - Problem: CNN uses "Golems" on Day 1. Next morning Mazar presents it as his soldiers' new name, CNN's own reporter asks "Golems?" (631), and later the anchor credits Mazar with it (1285).
  - Fix: author decision.
    - (a) Replace "Golems" in the Day 1 CNN segments with "the machines" or "guardians", and retitle 337 to "Understanding the Guardians".
    - (b) Change 629 to `…they've started calling them *Golems*, same as your network,`, cut 631, and change 1285 to `which we first heard from Israeli soldiers`.
- [ ] AIA-13 · line 237 vs 251 · (a) · low
  - Excerpt: `1836 - shot fired. 1837... impact.` / `No time of flight.`
  - Problem: the frame log shows one frame between shot and impact.
  - Fix: 237 `> "1836 - shot fired. Impact, same frame."`
- [ ] AIA-14 · line 261 · (e) · low
  - Excerpt: `Twitter's calling them angels.`
  - Problem: Twitter had been renamed X in July 2023.
  - Fix: author decision. Keep it as colloquial speech, or use `Social media's calling them angels.`
- [ ] AIA-15 · line 699 vs 281 · (a) · low
  - Excerpt: `He sat on the glacis of the command vehicle again`
  - Problem: earlier he sat on the engine deck (281), not the glacis.
  - Fix: `He sat on the engine deck of the command vehicle again`
- [ ] AIA-16 · line 299 vs 163–167 · (a) · low
  - Excerpt: `No secondary, no overpenetration. Just... annihilation.`
  - Problem: the narration had the tank become "a sealed oven of white-orange flame", which is a secondary fire.
  - Fix: `No overpenetration. Just... annihilation.`
- [ ] AIA-17 · lines 309 (and 35) vs 415 · (a) · low–medium
  - Excerpt: `Squat, heavy barrel.` / `No barrel he could identify.`
  - Fix: 415 `No bore he could identify.`
- [ ] AIA-18 · lines 349, 352 vs 479 · (a) · low
  - Excerpt: `The grid - the green, yellow, red lattice`
  - Problem: the Day 1 panel cites green, but green is first seen the next morning (479).
  - Fix: `the yellow-to-red lattice`, and cut "Green - safe." from 352.
- [ ] AIA-19 · lines 473, 645 · (c) · medium
  - Excerpt: `The K-Bar was still strapped there`
  - Problem: the brand is KA-BAR.
  - Fix: `Ka-Bar` at both lines.
- [ ] AIA-20 · line 501 vs 519 · (a) · low
  - Excerpt: `the motionless giants standing sentinel just a few meters behind`
  - Problem: line 519 calls it "the distant figure".
  - Fix: 501 `some distance behind`
- [ ] AIA-21 · line 1015 vs 553, 621, 739 · (a) · medium
  - Excerpt: `Sources confirm that four days ago, a fighter attempted to commandeer an aid drop near Nuseirat.`
  - Problem: said on Day 4, "four days ago" means Arrival Day. But on Day 2 Mazar says "They haven't fired on anyone else. Not one." (553) and "Not before, not after." (621).
  - Fix: `two days ago`
- [ ] AIA-22 · line 769 · (b) · medium–low
  - Excerpt: `A senior analyst gestured to a holographic projection of Mazar's interview`
  - Problem: CLAUDE.md says non-Federation forces have contemporary technology.
  - Fix: `gestured to a wall monitor showing Mazar's interview`
- [ ] AIA-23 · lines 805–807 vs 659 · (a) · medium
  - Excerpt: `They don't care who you are... only what you're *about to do*.`
  - Problem: presented as playback "from the live interview", but he actually said "I think the Golems don't care who you are… What matters is intent."
  - Fix: 807 `> "I think the Golems don't care who you are... What matters is intent."`
- [ ] AIA-24 · line 841 · (g) · low
  - Excerpt: `calling it a 'sovereign violation of airspace.'`
  - Problem: it isn't China's airspace.
  - Fix: `calling it 'a violation of international law.'`
- [ ] AIA-25 · line 911 · (e) · low
  - Excerpt: `And in Washington, Langley-5 stood alone`
  - Problem: CIA headquarters is in Langley, Virginia.
  - Fix: `And at Langley,`
- [ ] AIA-26 · line 913 vs 889–893 · (a) · low
  - Excerpt: `reviewed his grandfather's journal entries again`
  - Problem: no journal was established; Semyonov only described a remembered story and one drawing.
  - Fix: `reviewed his grandfather's old journal`, or set up the journal at 893.
- [ ] AIA-27 · line 915 · (g) · medium–high
  - Excerpt: `*خطر: المحتوى مجهول* - *Danger: Identity Unknown*`
  - Problem: المحتوى مجهول means "content unknown".
  - Fix: `*خطر: الهوية مجهولة*`
- [ ] AIA-28 · line 1192 · (g) · low
  - Excerpt: `"الرجال الكبار" - *"The big men."*`
  - Problem: in Arabic this usually means "grown men" or "the elders", not physically big men.
  - Fix: author decision. Use `الرجال العمالقة` ("the giant men"), or keep it as a deliberate child's idiom.
- [ ] AIA-29 · line 1273 · (e) · low
  - Excerpt: `Catholic theologian, Vatican Pontifical Academy`
  - Problem: there are several Pontifical Academies, so this needs a name.
  - Fix: `Pontifical Academy of Theology`
- [ ] AIA-30 · line 1275 · (e) · medium
  - Excerpt: `Benares Hindu University`
  - Problem: the official name is Banaras Hindu University.
  - Fix: `Banaras Hindu University`
- [ ] AIA-31 · line 1282 · (e) · low–medium
  - Excerpt: `stood guard at the Gates of Eden with *flaming swords that turned every way*`
  - Problem: Genesis 3:24 has cherubim and, separately, "a flaming sword which turned every way" (one sword).
  - Fix: `stood guard at the Gates of Eden beside *a flaming sword which turned every way*`
- [ ] AIA-32 · line 1294 · (e) · medium
  - Excerpt: `Lord Krishna sends avatars - *Vibhutis* - to restore balance.`
  - Problem: Krishna is himself an avatar of Vishnu, and vibhutis are divine manifestations (Gita ch. 10), not avatars he sends.
  - Fix: `Lord Krishna - himself an avatar of Vishnu - says he takes form in every age to restore balance.`
- [ ] AIA-33 · line 1300 · (e) · low–medium
  - Excerpt: `There is a Hadith, not widely cited, that speaks of 'strangers descending…'`
  - Problem: no such hadith exists, and an invented one presented as real may read as fabricated scripture.
  - Fix: author decision. Frame it as "an old folk saying", or have the Imam call it weak or disputed.
- [ ] AIA-34 · lines 1327, 1376 vs 1722, 1730 · (a) · medium
  - Excerpt: `"Five days," he spat.` / `in these four days since the Landmates arrived` / `As of this morning, the last confirmed hostile actor in Gaza surrendered.`
  - Problem: after Sharif's "five days" come a midday truck bomb, that night's desertions, his capture, and the surrender "that night". Yet Geneva on "Five Days After Arrival Day" says it all ended "this morning".
  - Fix: 1327 `"Three days," he spat. "Three days and we haven't moved *anything.*"`
- [ ] AIA-35 · line 1329 · (e) · high
  - Excerpt: `We sent teams north and east. Rafah, Zeitoun.`
  - Problem: from Khan Younis, Rafah is south.
  - Fix: `We sent teams north and south. Zeitoun, Rafah.`
- [ ] AIA-36 · line 1425 · (c) · low
  - Excerpt: `A dry, heavily-accented Farsi voice`
  - Fix: `heavily accented` (no hyphen after an -ly adverb)
- [ ] AIA-37 · line 1561 · (c) · low
  - Excerpt: `where you will be tried for your crimes in a fair trial.`
  - Problem: redundant run-on.
  - Fix: `You will place yourself in my custody, and you will receive a fair trial for your crimes.` Keep the original if the stiltedness is meant to be the AI's.
- [ ] AIA-38 · line 1599 vs 29 · (a) · low
  - Excerpt: `remained - partially embedded in the ground like a seed`
  - Problem: on Arrival Day the pods "didn't impact"; they hovered and opened.
  - Fix: `remained - half-buried in drifted sand and rubble, like a seed`
- [ ] AIA-39 · line 1603 · (a) · low
  - Excerpt: `a deep *thoom* … trailing a column of fire and soundless thrust.`
  - Problem: "soundless" contradicts the thoom and the whine.
  - Fix: `shimmering thrust`
- [ ] AIA-40 · lines 1629, 1694 · (e) · medium
  - Excerpt: `the PA checkpoint at Salah al-Din Road, where Authority forces`
  - Problem: the Palestinian Authority has had no forces in Gaza since 2007.
  - Fix: author decision. Make it a UN- or Egyptian-run reception point, or add a line that PA police had been let back in.
- [ ] AIA-41 · lines 1726, 1871, 2216, 2326; EA:169 · (e) · medium
  - Excerpt: `Under-Secretary Leena Ahlström, envoy to extraordinary security events`
  - Problem: the UN rank is Under-Secretary-General.
  - Fix: `Under-Secretary-General` at all five lines.
- [ ] AIA-42 · line 1746 vs 37–39, 1015, 1399 · (a) · low
  - Excerpt: `One of the Landmates there broke silence when it captured Abu Sharif.`
  - Problem: Landmates had already spoken several times.
  - Fix: `was the first to address someone by name when it captured Abu Sharif.`
- [ ] AIA-43 · line 1830 vs 1907, 1952, 2008 · (a) · low
  - Excerpt: `no objects in hand. Even paper might be read as concealment.`
  - Problem: at the plaza they carry papers, notes and a folder.
  - Fix: author decision. Drop the second sentence, or have them leave the papers behind.
- [ ] AIA-44 · line 1858 · (e) · low
  - Excerpt: `at a secured strip outside Rafah`
  - Problem: Gaza has had no airfield since 2001.
  - Fix: author decision. Land at El Arish and drive through the Rafah crossing; this would change the 0852 timing.
- [ ] AIA-45 · line 1871 · (g) · medium
  - Excerpt: `sat in the front passenger seat, flanked by two local liaisons.`
  - Problem: nobody in a front passenger seat can be flanked by two people.
  - Fix: `sat in the front passenger seat beside a local liaison.`
- [ ] AIA-46 · line 1891 vs 1883 · (a) · medium
  - Excerpt: `That's the third one.` / `They passed a second, then a third`
  - Fix: 1891 `They passed a fourth, then a fifth`
- [ ] AIA-47 · line 2024 · (f) · low
  - Excerpt: `for the first time in recorded human history, formal dialogue with a true non-human intelligence had begun.`
  - Problem: in-universe this is false; the Federation has dealt with the Xenari since 1947.
  - Fix: `for the first time on the public record`
- [ ] AIA-48 · line 2060 · (c) · high
  - Excerpt: `But nobody *asked* for you, the people didn't *vote* for this.`
  - Problem: missing closing quote, a comma splice, and no speaker.
  - Fix: `> "But nobody *asked* for you. The people didn't *vote* for this," Song said.` (you pick the speaker)
- [ ] AIA-49 · line 2118 · (a)(e) · medium
  - Excerpt: `Behind them, the sun crested over the eastern skyline of Khan Younis`
  - Problem: the scene is at 0915 (heading at 2084); sunrise in Gaza in mid-June is around 0530.
  - Fix: `the sun climbed higher over the eastern skyline of Khan Younis, washing the plaza in hard light.`
- [ ] AIA-50 · line 2136 · (f) · high
  - Excerpt: `You spoke of the EarthSpace Federation. Are they your... masters?`
  - Problem: HARBINGER has not named the Federation on-page yet. It names it in its reply (2140).
  - Fix: `> "You mentioned you act under authority. Whose authority? Do you have... masters?"`
- [ ] AIA-51 · line 2176 vs 2262 · (a) · low
  - Excerpt: `by the consensus of the Security Council's emergency session`
  - Problem: the on-page Security Council emergency session is on Day 9 (2262) and reads as the first one; this scene is Day 6.
  - Fix: author decision. `by mandate of the Secretary-General`, or establish an earlier session.
- [ ] AIA-52 · line 2302 vs 2188 · (a) · medium
  - Excerpt: `the empty signature line below Ahlström's flowing ink.` / `And beneath it, in black ink, Leena Ahlström's signature.`
  - Fix: 2302 `And above it`
- [ ] AIA-53 · lines 2216, 2220 · (e) · low
  - Excerpt: `beneath the sweeping green marble backdrop` / `Mr. Secretary-General. Esteemed delegates.`
  - Problem: in the real hall the rostrum is green marble and the backdrop gold, and speakers address the President of the General Assembly first.
  - Fix: 2216 `beneath the gold backdrop and UN emblem, at the green marble rostrum`; 2220 `Mr. President. Mr. Secretary-General. Esteemed delegates.`
- [ ] AIA-54 · line 2290 vs 2296 · (a) · high
  - Excerpt: `without raising his voice:` / `she continued quietly`
  - Problem: the Chinese ambassador changes gender between the two lines.
  - Fix: align the gender in both lines.
- [ ] AIA-55 · line 2339 vs 2042–2046, 1852 · (a) · low
  - Excerpt: `*Humanity did [authorize this intervention], by allowing this conflict to continue.`
  - Problem: shown on CNN as a verbatim HARBINGER quote, but it doesn't match the plaza dialogue, and the meeting had "No cameras. No media."
  - Fix: label it "as summarized by the UN delegation", or quote 2042–2046 exactly.

### Executive Authority

`story-executive-authority.md`: 60 items, 5 high confidence, 7 needing an author decision.

The reviewer rebuilt the calendar from canon and EA's own clues: Arrival 13 June 2024; drafted about 17 June 2024; Taiwan Strait 7 January 2025; Kyiv 12 March 2025; stand-down 15 March 2025; HARBINGER's UN address 3 September 2026 at 1534; voice discovery 29 September 2026 at 1447; Fort Bragg meeting 15 December 2026. Lines 625 ("eighteen months" from the March 2025 stand-down), 657 ("seventeen now") and 661 ("two years") already fit. Most of the "eighteen months" items below come from chapter 4 and the epilogue measuring time as if the recall came about eighteen months after June 2024.

- [ ] EA-01 · line 25 · (e) · medium–low
  - Excerpt: `at seven in the evening during finals week`
  - Problem: the scene is about 17 June; MIT's spring finals end in late May.
  - Fix: cut "during finals week", or make the course a summer session.
- [ ] EA-02 · line 361 vs 35, 249 · (a) · low–medium
  - Excerpt: `Leave the phone, the watch, anything that syncs to anything.` / `**14 Aug** - Personal laptop`
  - Fix: 361 `Issued laptop`
- [ ] EA-03 · line 165 vs 103, 109, 119, 141; AiA:2208–2210 · (a)(b) · high
  - Excerpt: `On the fourth day since Arrival, Weiss came into the room without knocking`
  - Problem: AiA puts Ahlström's General Assembly speech on Day 9. EA's own scientists were only drafted on Day 4, and this scene follows "The First Weeks".
  - Fix: `On the ninth day since Arrival,`
- [ ] EA-04 · line 169 vs AiA:1926–1930 · (b) · medium–high
  - Excerpt: `a machine that had known all six of their names`
  - Problem: HARBINGER names seven people: Ahlström plus six.
  - Fix: `all seven of their names`
- [ ] EA-05 · line 171 vs AiA:2226 · (b) · low
  - Excerpt: `a strong AI construct, capable of autonomous judgment, with control over every active Landmate within the Gaza operational theater.`
  - Problem: this quote of her speech silently drops "Its nature is non-biological." and "or body".
  - Fix: add an ellipsis and restore "a group or body".
- [ ] EA-06 · line 187 vs AiA:2242 · (b) · medium
  - Excerpt: `the one that hadn't made Ahlström's speech to the General Assembly`
  - Problem: her speech does paraphrase it ("may, in time, choose to speak with us directly").
  - Fix: `the one Ahlström had only paraphrased for the General Assembly`
- [ ] EA-07 · line 215 vs 211 · (a) · low
  - Excerpt: `They send me a line every morning` / `his one o'clock check-in`
  - Fix: 215 `that the morning line on his mother hadn't come`
- [ ] EA-08 · line 249 vs 361 · (a) · low
  - Excerpt: `on a Wednesday in early August` / `**14 Aug**`
  - Fix: `mid-August` (14 August 2024 was a Wednesday, so the weekday is right).
- [ ] EA-09 · line 251 · (a) · medium
  - Excerpt: `Three months of the grid model lived on that machine`
  - Problem: mid-August is about eight weeks after the program began.
  - Fix: `Two months`
- [ ] EA-10 · line 293 · (e) · medium–high
  - Excerpt: `HARBINGER was a machine in a warzone eight time zones away.`
  - Problem: Gaza (UTC+3) to Ohio (UTC−4) in September is seven hours.
  - Fix: `seven time zones away`
- [ ] EA-11 · line 329 (and ledger 365) vs 319–327 · (a) · low–medium
  - Excerpt: `a laboratory-grown analog alloy, six weeks in a controlled curing chamber`
  - Problem: the hypothesis is only born in an October argument, yet its test sample had already cured for six weeks by October.
  - Fix: author decision. `two weeks in a controlled curing chamber`; or a sample Osei had started in August; or move the ledger entry later.
- [ ] EA-12 · line 607 vs 357 (also 213, 803) · (a) · high
  - Excerpt: `a plain hardbound one from the base exchange` / `the hardbound notebook still in the inside pocket where it had lived every day since June`
  - Problem: the hardbound notebook was bought in December. Also, a jacket "still hanging exactly where she'd left it" in Boston couldn't have carried it in Ohio.
  - Fix: 607 `…until she got to the jacket she'd worn home, the hardbound notebook still in the inside pocket where it had lived every day since December.`
- [ ] EA-13 · lines 491, 505 vs 383, 387 · (a) · low–medium
  - Excerpt: `COLD FORGE had produced in eight months` / `five incidents in eight months`
  - Problem: the third week of January is seven months in, as 383 and 387 say.
  - Fix: `seven months` at both lines.
- [ ] EA-14 · line 387 vs AtS:514, 2054 · (b) · medium–high
  - Excerpt: `All five destroyers, all five bridges`
  - Problem: in Across the Sea the five ships are one Type 055 destroyer and Type 054 frigates.
  - Fix: `All five ships, all five bridges`
- [ ] EA-15 · line 401 · (c) · medium
  - Excerpt: `twelve minutes redacted for reasons neither of them could later identify a redaction in.`
  - Problem: garbled ending.
  - Fix: `and twelve minutes redacted, though neither of them could later find anything in those twelve minutes worth redacting.`
- [ ] EA-16 · line 401 · (e) · low
  - Excerpt: `stamped SECRET//REL`
  - Problem: "REL" needs a release list.
  - Fix: `SECRET//REL TO USA, FVEY`
- [ ] EA-17 · line 403 vs AtS:3165, 3183, 3199 · (b) · medium
  - Excerpt: `"Wei-Ming," Vann said, reading the uploader's handle off the corner of the frame`
  - Problem: in Across the Sea the handle is @TechBoyTaiwan.
  - Fix: `"TechBoyTaiwan," Vann said, reading the uploader's handle… "Chen Wei-Ming. Seventeen years old…"`
- [ ] EA-18 · line 413 vs AtS:3241–3247, 3350–3356 · (b) · medium
  - Excerpt: `The Russians are already calling it that on television. Marchenko, their railgun guy`
  - Problem: in Across the Sea, Marchenko speaks only in a closed Russian MoD briefing; the televised railgun call came from Col. Crawford on CNN.
  - Fix: author decision. `The Americans are already calling it that on television - Crawford on CNN`, or `Marchenko, their railgun guy - his briefing leaked this morning`.
- [ ] EA-19 · line 421 · (c) · low
  - Excerpt: `a container stenciled in Mandarin`
  - Problem: Mandarin is spoken; the stencil is written Chinese.
  - Fix: `stenciled in Chinese`
- [ ] EA-20 · line 451 vs AtS:1750–1760 · (b) · medium
  - Excerpt: `Konetz called it on the news panel two days ago` … `Caltech's name under a chyron`
  - Problem: in Across the Sea, Konetz speaks at a closed Pentagon briefing.
  - Fix: `Konetz called it in the Pentagon briefing two days ago… Caltech's name on a slide`
- [ ] EA-21 · line 493 vs 485–487 · (a) · medium
  - Excerpt: `showed four hours and eleven minutes of continuous, unbroken footage`
  - Problem: the locker was sealed at 2140 and opened at 0700, a 9 h 20 min window.
  - Fix: `nine hours and twenty minutes … compressed into a file that should have held nine hours and twenty-eight minutes`
- [ ] EA-22 · lines 519, 521 · (a) · medium
  - Excerpt: `Nine months of frustration` / `"Eight months," Weiss went on.` / `the second time in nine months`
  - Problem: the same scene says both. EA uses "eight months" for this first stint about 20 times.
  - Fix: author decision. Standardize on "eight" (change 519 and the end of 521), or use "nine" throughout.
- [ ] EA-23 · lines 545, 669 vs DvG:1426–1503 · (b) · medium
  - Excerpt: `steam rising off it into the night` / `from a night in a Ukrainian field`
  - Problem: David v Goliath puts the Kyiv defense at 0647–0658 on 12 March, over the city and after sunrise.
  - Fix: 545 `into the cold morning air`; 669 `from a morning over Kyiv neither of them had ever discussed`
- [ ] EA-24 · line 545 vs codex/land/guardian.md · (b) · low
  - Excerpt: `On the exhale after each shot, a hatch along the turret's flank blew open`
  - Problem: per the codex, turrets first slow their rate of fire, vent coolant only when needed (6–8 s), and eject clips only under pressure.
  - Fix: `Every few shots, a hatch…`
- [ ] EA-25 · line 553 vs codex/foundations/offensive-weapons/thermal-clips.md · (b) · low
  - Excerpt: `a heat capacity that shouldn't exist in anything with a molecular structure I recognize.`
  - Problem: the codex makes the clips an ordinary lithium-beryllium alloy.
  - Fix: author decision. Keep it as Osei misjudging, or soften to `a heat capacity I can't account for without knowing the alloy`.
- [ ] EA-26 · line 593 vs 597 · (a) · low
  - Excerpt: `the drive back to the hotel` / `back in a motel room`
  - Fix: 593 `motel`
- [ ] EA-27 · line 629 vs 689 · (a) · high
  - Excerpt: `You're being collected at 0500 tomorrow.` / `They landed at 0512, in the dark`
  - Problem: he can't be picked up in Massachusetts at 0500 and land in Florida at 0512.
  - Fix: `collected at midnight`
- [ ] EA-28 · line 655 vs Helpers:49, 63, 143 · (b) · medium–high
  - Excerpt: `before HARBINGER had finished offering the fourth nation its ten free machines.`
  - Problem: in The Helpers it is one offer to every nation at once, then a single 90-second vote.
  - Fix: `before the ninety-second vote clock had finished running down.`
- [ ] EA-29 · line 699 vs Helpers:13 · (b) · low
  - Excerpt: `on a rotating schematic the evening before.`
  - Problem: the address was at 1534.
  - Fix: `the afternoon before`
- [ ] EA-30 · line 719 · (b) · medium
  - Excerpt: `for the first time since June of the previous year.`
  - Problem: it is September 2026; the program began in June 2024.
  - Fix: `since that first June, two years before.`
- [ ] EA-31 · lines 719, 767 vs 229, 235, 425, 475 · (c) · medium
  - Excerpt: `a FEMA engineer's boroscope` / `Huels's boroscope`
  - Fix: `borescope`, as the earlier lines spell it.
- [ ] EA-32 · line 757 vs 735, 803 · (a) · medium
  - Excerpt: `in that coffee-line moment three hours earlier` / `in a coffee line an hour later`
  - Problem: line 803 puts the coffee an hour after a morning shower, many hours before 1447, not three.
  - Fix: 757 `in that coffee-line moment that morning`
- [ ] EA-33 · line 773 · (g) · low
  - Excerpt: `watched Peter come sprinting down from the observation deck`
  - Problem: Peter is never introduced in EA (he is Peter Scofield in The Helpers).
  - Fix: `Peter Scofield, the FEMA operations lead`
- [ ] EA-34 · line 797 · (g) · low–medium
  - Excerpt: `until three weeks ago I genuinely believed I might be the only person this was happening to.`
  - Problem: nothing happened three weeks earlier to change that.
  - Fix: `because I genuinely believed I might be the only person this was happening to.`
- [ ] EA-35 · line 813 · (a)(b) · medium
  - Excerpt: `I knew it eight months ago too.`
  - Problem: the sample failed in October 2024, about 23 months before this scene.
  - Fix: `I knew it then too.`
- [ ] EA-36 · line 815 · (g) · high
  - Excerpt: `The Livermore dataset wasn't the first thing that went sideways on me either`
  - Problem: no "Livermore dataset" is ever established. The incident meant is the November correlated dataset (339–349).
  - Fix: `The correlated dataset`
- [ ] EA-37 · line 845 · (b) · medium
  - Excerpt: `for the first time since June of the year before`
  - Fix: `since that first June`
- [ ] EA-38 · lines 851, 869 (×2), 881 · (b) · low–medium
  - Excerpt: `since a hangar in Ohio eighteen months earlier` / `"Eighteen months," she said` / `Eighteen months of wondering`
  - Problem: the tank was in July 2024 and the bridge in January 2025, so this is 20–26 months before September 2026.
  - Fix: `two years earlier`, `Two years`, `Two years of wondering`
- [ ] EA-39 · line 873 · (a) · low
  - Excerpt: `the old joke out loud for the first time in a year.`
  - Problem: the joke was last said aloud in August 2024 (277; compare 441, 559).
  - Fix: `in two years`
- [ ] EA-40 · line 987 vs 877 (and 971–973) · (a) · medium
  - Excerpt: `Four disciplines. Same afternoon.`
  - Problem: the microscope result came five-plus days after the drilling.
  - Fix: `Same week.`
- [ ] EA-41 · line 899 vs 855–867 · (a) · medium
  - Excerpt: `start laughing the way she had twenty minutes earlier.`
  - Problem: she laughs only after the third bit fails, which is this same moment.
  - Fix: `start, quietly, to laugh.`
- [ ] EA-42 · line 927 vs 857 · (a) · low
  - Excerpt: `echoing, almost word for word, what Osei's own tech had said`
  - Problem: "That's not possible" is not word for word "That's not the same joint".
  - Fix: `echoing, in spirit if not in words,`
- [ ] EA-43 · line 931 · (b) · medium
  - Excerpt: `anything Gaza's footage had shown him eighteen months earlier`
  - Fix: `two years earlier`
- [ ] EA-44 · line 957 · (a)(b) · medium–high
  - Excerpt: `the FEMA crew must have stood eighteen months earlier, watching a tank round shatter against a chest plate.`
  - Problem: the FEMA crew weren't in Gaza, and it was about 27 months earlier.
  - Fix: `the way she imagined Mazar's tank crews must have stood, two years earlier, watching a sabot round shatter against a chest plate.`
- [ ] EA-45 · line 1003 · (c) · low
  - Excerpt: `four separate men and women's hard-to-believe afternoons`
  - Fix: `four separate scientists' hard-to-believe afternoons`
- [ ] EA-46 · line 1045 · (a) · medium
  - Excerpt: `Four months after Huels's paper … and eighteen months of their own trial and error.`
  - Problem: eighteen months of work can't follow a paper published four months earlier.
  - Fix: `and four months of their own trial and error`
- [ ] EA-47 · line 1047 vs 999, 1043 · (a) · low–medium
  - Excerpt: `images … that she'd never been able to publish outside COLD FORGE's own classification`
  - Problem: her materials paper was published, and the Shenyang institute took five months, not the "three weeks faster" the passage claims.
  - Fix: `the raw images that had stayed classified even after her paper cleared`; `understood the assignment faster than she had`
- [ ] EA-48 · line 1049 vs 265–271 · (a) · low
  - Excerpt: `in a cubicle of borrowed guilt`
  - Problem: he reviewed the schematics in the annex workroom; the cubicle was in Herndon.
  - Fix: `in a windowless room of borrowed guilt`
- [ ] EA-49 · lines 1071, 1077, 1111, 1135, 1143–1145, 1163, 1189, 1211 vs codex/covops.md, codex/land/jaegers.md · (b) · high
  - Excerpt: `shimmering the same way the sky above the motor pool had shimmered, barely-there outlines that the eye kept sliding off of`
  - Problem: covops.md says personal cloaking is too unstable for field use and agents cannot turn invisible; jaegers.md calls optical invisibility "impractical at the infantry level". The aircraft cloak above the motor pool (1065) is fine.
  - Fix: author decision. (a) Amend the codex to allow a limited personal cloak; or (b) recast the team as adaptive camouflage in darkness, which means rewriting "the shimmer simply stopped" and "The suit beneath the cloak". The lens clusters and weapons already match Shade of Gray and the codex.
- [ ] EA-50 · line 1101 · (g) · low
  - Excerpt: `this is Bragg-Six actual.`
  - Problem: a Fort Bragg callsign on Fort Hood's radio, which Reyes flags.
  - Fix: author decision. Confirm it's a deliberate spoof, or change it to a Fort Hood callsign.
- [ ] EA-51 · lines 1109, 1179 · (b) · low
  - Excerpt: `a flat, precise impact against his chest, no louder than a knuckle rapping a door`
  - Problem: the non-lethal weapon that leaves "no mark" isn't in the codex, and the codex rifles (RTK-6, RSK-5/M) are lethal.
  - Fix: proposal. Add a codex entry for a stun weapon.
- [ ] EA-52 · line 1117 vs codex/covops.md (ICE Pick) · (b) · low
  - Excerpt: `Something small and dark, no larger than a lighter, came up in its hand and settled against the card reader`
  - Problem: the codex lock-defeat tool is "not unlike a screwdriver".
  - Fix: author decision. Describe it as the ICE Pick, or treat it as a new tool.
- [ ] EA-53 · lines 1183, 1209 vs 1063, 1099–1121 · (a) · medium
  - Excerpt: `collapsing within an eleven-minute window` / `for the whole eleven-minute window`
  - Problem: Ruiz drops at 1857; the radio call is at 1911, and four more soldiers drop after it, so the window is at least 14 minutes.
  - Fix: `fifteen-minute window` at both lines.
- [ ] EA-54 · line 1191 vs 1175 · (a) · low–medium
  - Excerpt: `He hadn't told the physician's assistant that part.`
  - Problem: the clinician was "the attending physician".
  - Fix: `the physician`
- [ ] EA-55 · line 1221 vs Helpers:2611–2612, EA:1073, 1203 · (b) · low–medium
  - Excerpt: `on a Tuesday in late January, three weeks after Fort Hood`
  - Problem: the Fort Bragg meeting is 15 December, so Fort Hood is about 18 December, and three weeks later is about 8 January.
  - Fix: `early January`, or `five weeks after`
- [ ] EA-56 · line 1223 · (b) · medium
  - Excerpt: `back in June of the year before last`
  - Problem: it is January 2027 and the book was shipped in June 2024.
  - Fix: `back in that first June, two and a half years ago`
- [ ] EA-57 · line 1227 · (b) · low–medium
  - Excerpt: `merely waited eighteen months for him to look again.`
  - Fix: `two and a half years`
- [ ] EA-58 · line 1251 vs 1247 · (a) · low–medium
  - Excerpt: `never once appeared in eight months of daily reports`
  - Problem: the daily line has continued since June 2024 (1247).
  - Fix: `in two and a half years of daily reports`
- [ ] EA-59 · line 1271 · (a) · low–medium
  - Excerpt: `a program that had technically concluded twice now, reconstituted itself twice`
  - Problem: on the page it was suspended once, recalled once, and concluded once.
  - Fix: `had technically ended twice now, reconstituted itself once`
- [ ] EA-60 · line 1277 · (b) · medium
  - Excerpt: `since June before last.`
  - Problem: in January 2027 that means June 2025.
  - Fix: `since that first June.`

### Adrenaline

`story-adrenaline.md`: 26 items, 2 high confidence, 3 needing an author decision.

- [ ] ADR-01 · line 15 vs codex/galaxy/xenari.md · (b) · low–medium
  - Excerpt: `her bioluminescent markings dim with polite focus.`
  - Problem: in the codex, dimming means fear, and concentration is "rapid violet-pink flickering".
  - Fix: `her bioluminescent markings flickering a faint violet-pink with polite focus.`
- [ ] ADR-02 · line 17 vs codex/galaxy/kryllians.md, xenari.md · (b) · low
  - Excerpt: `The Kryllians, ever pragmatic, dominated discussions of cybernetic augmentation.`
  - Problem: the codex makes Kryllians industrial; cybernetics belong to the Xenari Va'shar guild.
  - Fix: `dominated discussions of medical manufacturing`
- [ ] ADR-03 · line 21 vs 384, 394 · (g)(b) · low–medium
  - Excerpt: `listening to their presentations, poring over their clinical methodologies, and marveling at their peculiar physiology.`
  - Problem: after two days of human physiology talks, and decades of Xenari–Federation partnership, no alien recognizes adrenaline.
  - Fix: author decision. Add that human endocrinology was never shared, or change 384 to "never seen at these levels".
- [ ] ADR-04 · line 23 · (b) · low
  - Excerpt: `a Terran Marine among them. Staff Sergeant Logan Carter`
  - Problem: the codex has no Federation Marine branch or rank structure.
  - Fix: proposal. Add one to the codex, or call him "a Federation soldier".
- [ ] ADR-05 · line 48 vs codex/galaxy/kryllians.md · (b) · low
  - Excerpt: `His small, stocky frame crumpled, ammonia-rich blood spattering the polished floor.`
  - Problem: Kryllians need a breathing apparatus outside their own habitats, and none is shown.
  - Fix: add a detail, e.g. `his rebreather mask skittering across the floor`
- [ ] ADR-06 · line 94 · (c) · low
  - Excerpt: `The marine's breathing slowed.`
  - Fix: `Marine`, matching line 23.
- [ ] ADR-07 · lines 102, 181, 285 · (d) · medium
  - Excerpt: `## Adrenaline (Part II)` / `## Aftermath` / `## Aftermath (Part II)`
  - Problem: leftover serialization titles. There is no "Part I", and "## Aftermath" duplicates "### The Aftermath" (141).
  - Fix: give the chapters real titles and drop the "(Part II)" tags.
- [ ] ADR-08 · line 125 · (c) · low
  - Excerpt: `a lunging attacker with the jagged plasma dagger`
  - Problem: "the" for a dagger never introduced.
  - Fix: `wielding a jagged plasma dagger`
- [ ] ADR-09 · line 129 vs 123–125, 137 · (a) · low
  - Excerpt: `Meanwhile, Carter had ripped the rifle from the leader's grip`
  - Problem: the "second terrorist" Carter elbows is never shown dying, yet the count is six dead.
  - Fix: `Meanwhile, after dropping the second terrorist with the elbow, Carter had ripped the rifle…`
- [ ] ADR-10 · lines 133–135 · (g) · low
  - Excerpt: `gutting him from stomach to sternum.` / `The terrorist fell in two halves.`
  - Problem: a stomach-to-sternum cut doesn't sever a body.
  - Fix: `The terrorist folded in half and fell.`
- [ ] ADR-11 · lines 183–187 vs 141–161 · (d)(g) · medium
  - Excerpt: `The fight was over.` … `The humans stood amidst the carnage, panting, bruised, and bleeding.`
  - Problem: a serial-style recap of the scene just before it.
  - Fix: cut 183–187 and open the chapter at "And then, the adrenaline wore off."
- [ ] ADR-12 · line 207 vs 193, 221 · (a) · low–medium
  - Excerpt: `Logan Carter was the first to feel it.` / `adrenaline still coursing.`
  - Fix: 207 `the last of the adrenaline still in it.`
- [ ] ADR-13 · line 195 vs 123–129 · (a) · low
  - Excerpt: `it had been holding up a terrorist's skull not long ago.`
  - Problem: no such moment happens in the fight.
  - Fix: `it had been wrenching a rifle out of a four-armed alien's grip not long ago.`
- [ ] ADR-14 · line 195 · (c) · low
  - Excerpt: `the deep, gnawing pain in his thigh—where one of those bastard aliens had sunk a claw in deep.`
  - Fix: `had sunk a claw in.`
- [ ] ADR-15 · line 215 vs codex/galaxy/xenari.md · (b) · low
  - Excerpt: `flickering erratically—the Xenari equivalent of complete bewilderment.`
  - Problem: in the codex, rapid flickering means deep concentration.
  - Fix: author decision. Keep it (bewilderment isn't in the codex), or name a color.
- [ ] ADR-16 · lines 233, 306, 450, 486, 500 vs codex/galaxy/kryllians.md · (b) · low
  - Excerpt: `his exoskeletal fingers twitching with analytical frustration`
  - Problem: plates, an exoskeleton, clicking and chittering aren't in the codex, which describes short, stocky, dense ammonia-breathers.
  - Fix: author decision. Add these traits to the codex, or remove them. (Torchlight gives Kryllians chitin, antennae and mandibles too.)
- [ ] ADR-17 · line 245 vs 302, 330, 464 · (a) · low
  - Excerpt: `A Seraphyn medic approached her cautiously, its prismatic eyes`
  - Problem: Seraphyn are "their" everywhere else.
  - Fix: `their`
- [ ] ADR-18 · lines 273, 568 vs codex/galaxy/xenari.md · (b) · low
  - Excerpt: `Vireen's markings pulsed a troubled blue.`
  - Problem: in the codex, pulsing blue-white means excitement, and fear is a dimming grey-blue.
  - Fix: `dimmed to a troubled grey-blue`, at both lines.
- [ ] ADR-19 · line 454 vs 338, 546 · (a) · medium
  - Excerpt: `no longer grinning.` / `still grinning despite the dark bruises`
  - Fix: 454 `grinning again despite the dark bruises`
- [ ] ADR-20 · line 362 vs 125, 133, 277 · (a) · high
  - Excerpt: `Cut through his abdominal cavity with a scalpel.`
  - Problem: Henshaw used the terrorist's combat knife (133); Park used the scalpel (125, 277).
  - Fix: `with his own knife`
- [ ] ADR-21 · line 382 vs codex/galaxy/xenari.md · (b) · medium
  - Excerpt: `flickering a troubled shade of cyan-green.`
  - Problem: in the codex, cyan-green means ease.
  - Fix: `flickering a troubled grey-blue.`
- [ ] ADR-22 · lines 412–422 vs 398–408 · (d)(g) · medium
  - Excerpt: `Dr. Patel's words hung in the air like a dropped scalpel on a sterile floor.`
  - Problem: the chapter opens by repeating "Oh right, adrenaline…" and "Explain." from the previous scene.
  - Fix: cut 412–422 and open at "### Filling in the Gaps".
- [ ] ADR-23 · line 460 vs 492 · (e)(a) · medium
  - Excerpt: `five million years of evolution kicks in.`
  - Problem: Park then says reptiles and fish have the response too, which makes it hundreds of millions of years old.
  - Fix: `five hundred million years`
- [ ] ADR-24 · line 492 · (e) · low
  - Excerpt: `Mammals, reptiles, birds, even some fish.`
  - Problem: all fish have it.
  - Fix: `Mammals, reptiles, birds, fish.`
- [ ] ADR-25 · line 496 vs codex/galaxy/xenari.md · (b) · medium–high
  - Excerpt: `dimming to a deep shade of cyan—the Xenari equivalent of unease.`
  - Problem: in the codex, cyan-green means ease and fear is a dimming grey-blue.
  - Fix: `dimming to a muted grey-blue—the Xenari signal of fear.`
- [ ] ADR-26 · line 520 vs codex/galaxy/kryllians.md · (b) · low–medium
  - Excerpt: `Extreme weather, high gravity, bacterial infections`
  - Problem: the audience includes Kryllians from high-gravity Draxyl-4.
  - Fix: drop "high gravity,".

### Across the Sea

`story-across-the-sea.md`: 102 items, 19 high confidence, 26 needing an author decision.

- [ ] ATS-01 · L11, L39, L319, L332, L352, L364, L382 · (a) · high
  - Excerpt: "Timestamp: 0421 - 0512 UTC" (L319)
  - Problem: The scene runs at "0321 hours local", which is 1921 UTC on the previous day, and is predawn (L39). The report puts the event at 0421–0512 UTC, with the burst at "0430 UTC" (L332) and "zero-four-three-zero" (L382). At 0823 JST Whitaker is therefore reading about something in the future. He also calls it "full daylight" (L352). Taiwan at 0851 the same morning calls it "yesterday's playback" (L364).
  - Fix: Author decision.
    - Option 1, keep the predawn scene: L319 → "Timestamp: 1921 - 2012 UTC"; L332 "initiated at 1930 UTC"; L382 "until zero-three-three-zero"; L352 drop "Not in full daylight,"; L364 "this morning's playback data".
    - Option 2: move the scene to 1221 local and remove the fog, floodlights and predawn imagery (L15, L39).

- [ ] ATS-02 · L19, L516, L564, L634, L700, L772, L840 vs L2131, L2190, L3056 · (a) · high
  - Excerpt: "Commander Lu Jianjun stood at the forward observation pane" (L516)
  - Problem: Lu is "Captain" in Ch. 1, in Ch. 4, and in timeline.md:102, but "Commander" throughout Ch. 2.
  - Fix: Replace "Commander Lu" with "Captain Lu" at L516, 564, 634, 700, 772 and 840.

- [ ] ATS-03 · L61–91 vs L97–129, L139–147 · (g) · medium
  - Excerpt: "...What in God's name is that?" (L129)
  - Problem: Lu has already studied the figures at length and identified them as Landmates from briefings (L69–89, L83). The next scene replays him reaching the scope for the first time, then being told about Gaza by the lookout.
  - Fix: Author decision. Either have the third scene start after Lu's first look ("Lu was still at the scope when the largest one moved"), or remove Lu's recognition at L81–83.

- [ ] ATS-04 · L75, L109, L259, L712, L718, L858, L2453 vs L2449 · (b) · medium
  - Excerpt: "The cannon folded back onto its spine with practiced elegance" (L259)
  - Problem: The codex (landmate.md:13, :26) gives the Landmate only "two shoulder-mounted attachment points for missile pods or gimbaled autocannons". A back- or spine-mounted long railgun is not canon, and L2449 itself says "shoulder cannons dormant".
  - Fix: Author decision. Either add a back-mounted railgun module to landmate.md, or rewrite these lines as shoulder-mounted.

- [ ] ATS-05 · L83, L1848, L1898, L3488 · (b) · medium-high
  - Excerpt: "No one claimed them, yet they appeared wherever tensions threatened to boil over into actual conflict." (L83)
  - Problem: In June 2024, HARBINGER told the UN it acts for the EarthSpace Federation, and CNN broadcast it (angels-in-armor:2140, :2322). Characters in 2025 can't treat the owner as unclaimed or unheard-of: "why haven't we heard of them until now?" (L1848), "No one claims them" (L1898), "not representing any government we recognize" (L3488).
  - Fix: Author decision. Acknowledge the name, e.g. at L83: "A self-styled 'EarthSpace Federation' claimed them; no government did." Adjust L1848, L1898 and L3488 in the same way.

- [ ] ATS-06 · L143, L3344 · (b) · high
  - Excerpt: "Gaza. Last month." (L143); "during the Gaza conflict last month" (L3344)
  - Problem: Gaza is 13 June 2024 (timeline.md:83). This story starts on 7 January 2025, seven months later.
  - Fix: "Gaza. Last summer." and "during the Gaza conflict last summer".

- [ ] ATS-07 · L143 vs L446 · (b) · medium
  - Excerpt: "Video came out - was online for less than an hour before it disappeared." (L143)
  - Problem: The Merkava footage was broadcast repeatedly on CNN (angels-in-armor:191–217), and L446 says "Everyone in the room had seen the Gaza footage".
  - Fix: "Video was everywhere."

- [ ] ATS-08 · L175/L191, L802, L826, L834/L840 · (g) · low
  - Excerpt: "The bridge went still." (L802)
  - Problem: These scenes are headed CIC but the text says "bridge" (L191, L802, L826). The scene headed "Aft Observation Deck" (L834) actually takes place on the bridge (L840, L852).
  - Fix: L191, L802, L826 "bridge" → "CIC"; L834 heading → "### *Haiyangshan*, Bridge – Taiwan Strait".

- [ ] ATS-09 · L243 vs L321, L368 · (a) · medium
  - Excerpt: "It looked the same as it had an hour ago - unchanged, unremarkable." (L243)
  - Problem: The track shows the ship reversing "within seven minutes of proximity breach" (L321), a "short sprint".
  - Fix: "as it had a few minutes ago".

- [ ] ATS-10 · L247–251 vs L321, L366 · (a) · medium
  - Excerpt: "Helm. Come to course 0-4-5. Return to base." (L247)
  - Problem: Heading 045 runs northeast along Taiwan, not toward the mainland. The track has the ship departing "on vector 337" (L321) toward the mainland. A turn from 175 to 045 is also to port, not "banked to starboard" (L251).
  - Fix: L247/249 "3-3-7"; L251 "its bow angling north-northwest toward home waters". A 175→337 turn is to starboard, so "starboard" then stands.

- [ ] ATS-11 · L309 vs L468 · (e) · low
  - Excerpt: "### U.S. Pacific Command Intelligence Annex, Okinawa" (L309)
  - Problem: PACOM was renamed INDOPACOM in 2018, and the story itself uses "INDOPACOM" at L468.
  - Fix: "### U.S. Indo-Pacific Command Intelligence Annex, Okinawa".

- [ ] ATS-12 · L321, L950, L954, L1654, L1662, L1964, L2056, L2226, L2409, L2431, L2881, L2952, L2962, L3096, L3104, L3108 · (c) · high
  - Excerpt: "known colloquially as ‘Landmates'" (L950)
  - Problem: Every nested quotation on these 16 lines opens with a curly ‘ and closes with a straight '.
  - Fix: Make each pair consistent: ‘…’, or '…'.

- [ ] ATS-13 · L344 · (a/b) · high
  - Excerpt: "Cole Whitaker. Entry for 11 August." (L344)
  - Problem: The front matter and timeline.md:100 date the story 7 January 2025.
  - Fix: "Entry for 7 January."

- [ ] ATS-14 · L362 vs L2024 and all later Taiwan stamps · (a) · low
  - Excerpt: "*0851 NST*" (L362)
  - Problem: Taiwan time is "TST" everywhere else.
  - Fix: "*0851 TST*".

- [ ] ATS-15 · L368 vs L1032, L1864, L3438 · (a) · low
  - Excerpt: "Commander Liu stood with arms folded" (L368)
  - Problem: The Taiwanese Commander Liu and the PRC General Liu are unrelated but share a surname, in alternating chapters.
  - Fix: Author decision. Rename one, e.g. "Commander Lin".

- [ ] ATS-16 · L414, L1072 vs L319 · (e) · low
  - Excerpt: "### South Sea Fleet Command, Guangzhou" (L414)
  - Problem: The post-2016 names are Southern Theater Command Navy (HQ Zhanjiang) and Eastern Theater Command (Nanjing). The story already uses "Eastern Theater" at L319, and L1072 still says "Nanjing Theater".
  - Fix: L414 "### Southern Theater Command Navy, Zhanjiang"; L1072 "…Command Planning Cell, Eastern Theater Command".

- [ ] ATS-17 · L418, L460 vs L187–189, L217, L283 · (a) · medium-high
  - Excerpt: "No comms, no visuals - just telemetry, an encrypted burst" (L418)
  - Problem: Lu sent a "full video uplink" (L187). Fleet Command "confirms `HARBINGER` match" (L217). Lu logged it for Beijing (L283). That contradicts "no visuals", "*off the record*" (L418) and "still silent about what it had seen" (L460).
  - Fix: L418 "Grainy optics, telemetry, an encrypted burst, and a destroyer captain who now insisted that they'd been watched by machines"; L460 "still the only ship to have seen them".

- [ ] ATS-18 · L428 vs L510, L558, L638, L758 · (a) · medium-high
  - Excerpt: "We're going in at twenty-five hundred meters off the western shore" (L428)
  - Problem: 2,500 m is 1.35 NM. The run happens at 6.2–7.3 NM.
  - Fix: "We're going in at twelve kilometers off the western shore".

- [ ] ATS-19 · L462–466 · (e) · low-medium
  - Excerpt: "### Commander, U.S. Seventh Fleet" / "Rear Admiral Thoma Vance" (L462, L466)
  - Problem: Seventh Fleet is commanded by a vice admiral.
  - Fix: "Vice Admiral" at L466 and L2107, or make Vance a staff officer.

- [ ] ATS-20 · L466 vs L2839 · (c/a) · high
  - Excerpt: "Rear Admiral Thoma Vance read the message twice" (L466)
  - Problem: He is "Thomas Vance" at L2839.
  - Fix: "Thomas".

- [ ] ATS-21 · L498 · (e) · low
  - Excerpt: "She's already cycling up from Sasebo." (L498)
  - Problem: The real USS *Gettysburg* is an Atlantic Fleet cruiser (Norfolk), not Sasebo-based.
  - Fix: Author decision. Drop "from Sasebo", or name a Japan-based cruiser.

- [ ] ATS-22 · L536 vs L41–45, L97–115 · (a) · medium
  - Excerpt: "things that *only* Lu had looked at directly" (L536)
  - Problem: The lookout saw them first and longest.
  - Fix: "things only Lu and one lookout had looked at directly".

- [ ] ATS-23 · L544 vs L688–690 · (a/e) · medium
  - Excerpt: "One hundred forty-five kilometers, bearing constant. Estimated time on station: one hour, fifteen minutes." (L544)
  - Problem: That is about 63 knots, roughly double a Type 055's speed.
  - Fix: "Estimated time on station: two hours, forty-five minutes."

- [ ] ATS-24 · L580, L750, L2449; cross-story DVG L34 · (a) · low
  - Excerpt: "Its head - simple, angular, eyeless" (L580)
  - Problem: The same Landmate head is described as eyeless, as having a red designator on its "brow" (L750), as having "twin optic arrays" (L2449), and in DVG as a "single visor band" with green light (DVG L34).
  - Fix: Author decision. Pick one head design, ideally recorded in landmate.md.

- [ ] ATS-25 · L560/L590; L760/L790; L1122/L1138, L1170, L1182, L1226, L1282, L1328, L1382, L1404, L1434, L1476 · (a) · high
  - Excerpt: "*1340 JST*" (L590)
  - Problem: JST is UTC+9 and CST/TST is UTC+8, but the story uses the two as if they were the same clock. "1339 CST" and "1340 JST" are an hour apart. The US flight detects the J-16s at 0627 JST (0527 CST), before they take off at 0609 CST.
  - Fix: Add an hour to each JST stamp meant to be simultaneous: L590 → 1440; L790 → 1548; L1138 → 0727; L1170 → 0734; L1282 → 0738; L1404 → 0743; L1434 → 0745; L1476 → 0748.

- [ ] ATS-26 · L614 vs L376 · (a) · low
  - Excerpt: "Exactly what it did last time. Nothing." (L614)
  - Problem: No US hulls were present "last time" (L376), and in Gaza the Landmates did act.
  - Fix: Author decision, e.g. "Exactly what the Chinese said it did last time. Nothing."

- [ ] ATS-27 · L768, L780, L1026 · (e) · low
  - Excerpt: "Frigate *Qingdao* and *Ningde* are both lit up" (L768)
  - Problem: The real *Qingdao* (113) is a Type 052 destroyer, not a Type 054A frigate.
  - Fix: Replace *Qingdao* with *Xuzhou* (530, a Type 054A) at L768 and L780.

- [ ] ATS-28 · L854 vs L786, L794 · (a) · low
  - Excerpt: "as the ship cut north-by-northwest" (L854)
  - Problem: The heading is 275, due west.
  - Fix: "as the ship cut due west".

- [ ] ATS-29 · L878 · (e) · low
  - Excerpt: "Maintain flanking speed until we're outside the ADIZ." (L878)
  - Problem: An ADIZ is airspace; for a surface ship, territorial waters or the contiguous zone apply.
  - Fix: "until we're clear of Taiwan's contiguous zone".

- [ ] ATS-30 · L1034 vs L604, codex landmate.md:11 (3 m) · (a) · low
  - Excerpt: "three machines - human-sized - spoofed our navy" (L1034)
  - Fix: "three machines - barely bigger than a man -".

- [ ] ATS-31 · L1056 · (b) · medium
  - Excerpt: "We've seen no aerial assets associated with them" (L1056)
  - Problem: In Gaza, black delta aircraft dropped the Landmates (angels-in-armor:27, :595).
  - Fix: "Beyond the transports that dropped them into Gaza, we've seen no combat aircraft associated with them".

- [ ] ATS-32 · L1120, L1168, L1326 vs L1124, L1130, L1224 · (a) · medium
  - Excerpt: "### Philippine Sea – Airborne Early Warning Zone Charlie-4" (L1120)
  - Problem: The J-16s take off from Wuyishan and fly the Taiwan Strait. The Philippine Sea and "East of Taiwan" lie on the opposite side of the island.
  - Fix: L1120 "### Wuyishan Air Base, Fujian"; L1168 "### Taiwan Strait – Intercept Airspace"; L1326 "### PLAAF J-16 Flight – Taiwan Strait".

- [ ] ATS-33 · L1140 · (c) · medium
  - Excerpt: "speed and altitude consistent with PLAN twinjets" (L1140)
  - Problem: The J-16s belong to the PLAAF.
  - Fix: "PLAAF twinjets".

- [ ] ATS-34 · L1184, L1198, L1252 · (a/e) · medium-high
  - Excerpt: "acknowledged it only with a glance to his copilot … In the backseat, his ECM officer" (L1184)
  - Problem: The J-16 has two seats, so there is no third crewman.
  - Fix: L1184 "acknowledged it only with a glance at the mirror. In the backseat, his weapons systems officer monitored the signal spectrum."; L1198 "His backseater's hand froze"; L1252 "His backseater spoke first".

- [ ] ATS-35 · L1366, L3438 (and L1918) · (e) · medium
  - Excerpt: "But it spoke *perfect Cantonese*." (L1366)
  - Problem: PLAAF pilots work in Mandarin. L1918 ("in their own language") is wrong unless this changes.
  - Fix: Author decision. "*perfect Mandarin*" at L1366 and "perfect Mandarin" at L3438, or keep Cantonese as a deliberate signal and say so in the text.

- [ ] ATS-36 · L1406 vs L1386 · (a) · medium
  - Excerpt: "Chinese aircraft are turning back - bearing one-eight-zero." (L1406)
  - Problem: They set course 270.
  - Fix: "bearing two-seven-zero".

- [ ] ATS-37 · L1562 · (a) · high
  - Excerpt: "It all matched what the Chinese had seen the day before" (L1562)
  - Problem: The Chinese encounter happened minutes earlier the same morning.
  - Fix: "what the Chinese had seen minutes earlier".

- [ ] ATS-38 · L1602 · (b) · low
  - Excerpt: "One reportedly drew a smiley face in the sand after destroying an Israeli Merkava." (L1602)
  - Problem: This is not in angels-in-armor. It is new canon about the Gaza events.
  - Fix: Author decision. Keep it and accept it as canon, or cut it.

- [ ] ATS-39 · L594, L798 vs L1638, L1718, L1834 · (a) · medium
  - Excerpt: "Lieutenant Reyes from ONI sat forward" (L1638)
  - Problem: Commander John Reyes (Gettysburg) and Lieutenant Reyes (ONI) are unrelated but share a surname, a chapter apart.
  - Fix: Rename the ONI analyst, e.g. "Lieutenant Ortiz", at L1638, L1646, L1660, L1682, L1718, L1732 and L1834.

- [ ] ATS-40 · L1710 · (e) · low-medium
  - Excerpt: "That's the burn profile for JP-6." (L1710)
  - Problem: USAF fighters burn JP-8. JP-6 was the XB-70's fuel.
  - Fix: "JP-8".

- [ ] ATS-41 · L1748, L1806 · (a/e) · medium-high
  - Excerpt: "*1506 EDT*" (L1748)
  - Problem: This is January 2025, so Eastern Standard Time applies. The story's own CNN stamps use EST.
  - Fix: "*1506 EST*", "*1528 EST*".

- [ ] ATS-42 · L1750 vs L1782, L1808 · (a) · low
  - Excerpt: "three suited aerospace engineers from Lockheed, Boeing, and DARPA" (L1750)
  - Problem: That is one each, yet L1782 says "one of the DARPA reps" and L1808 "one of the DARPA engineers". DARPA is also an agency, not an aerospace firm.
  - Fix: "two Lockheed engineers, a Boeing engineer, and two DARPA program managers".

- [ ] ATS-43 · L1764 · (g) · low
  - Excerpt: "name patch reading *Cooper*" (L1764)
  - Problem: Suited civilian engineers don't wear name patches.
  - Fix: "name badge reading *Cooper*".

- [ ] ATS-44 · L1754, L1812 · (a) · low
  - Excerpt: "We clocked the ascent profile from Kadena" (L1812)
  - Problem: The departure happened over the Strait, not at Kadena.
  - Fix: "from the Kadena flight's footage".

- [ ] ATS-45 · L1824 · (e) · high
  - Excerpt: "Back in the forties. Lockheed test pilot. *XP-59 Airacomet*." (L1824)
  - Problem: Woolams flew for Bell, and the XP-59 was a Bell design.
  - Fix: "Bell test pilot".

- [ ] ATS-46 · L1834, L1844 vs L1616–1648 · (a) · low
  - Excerpt: "Reyes, the ONI analyst, leaned forward." (L1834)
  - Problem: Reyes and Manning were at Kadena at 1125 JST and are in the Pentagon about 17 hours later. That is possible but tight.
  - Fix: Author decision. Have them join by video link ("on the secure link from Kadena").

- [ ] ATS-47 · L1892 · (f) · high
  - Excerpt: "The moment the Talons flanked them." (L1892)
  - Problem: Beijing cannot know the name "Talon". It is first spoken to Morse at L2970, a day later.
  - Fix: "The moment the black aircraft flanked them."

- [ ] ATS-48 · L1918, L1972, L2276 · (a) · medium
  - Excerpt: "A gorilla mask. A wave. And then gone." (L1972)
  - Problem: Only Branson saw the mask, and the US debrief was classified. The Chinese crews saw "no pilot" (L1338). The leak at L1976ff comes after these scenes and doesn't mention the mask.
  - Fix: Author decision. Add a line showing how Beijing obtained the US footage, or cut the mask references from L1918, L1972 and L2276.

- [ ] ATS-49 · L1922, L1938, L1962, L1968 vs L3424 · (e) · high
  - Excerpt: "General Secretary of the CMC, Marshal Qiao, folded his arms" (L1922)
  - Problem: The CMC is headed by a Chairman, and that is Xi, who appears at L3424. "General Secretary" is a Party title, and the PLA abolished the rank of marshal in 1965.
  - Fix: "Vice Chairman of the CMC, General Qiao".

- [ ] ATS-50 · L2024 vs L2224 · (a) · medium
  - Excerpt: "Their IFFs still read green until twenty minutes ago." (L2224, at 2112)
  - Problem: That puts discovery at 2052, but Beijing's warning broadcast was already heard at 2039 TST (L2024).
  - Fix: "until forty minutes ago."

- [ ] ATS-51 · L2036, L2042, L2104, L2137, L2218, L2459, L2589, L2617, L2689, L2839 · (c) · medium
  - Excerpt: "Haiyangshan. Lakan. Feiya. Shezen. Baizou." (L2036)
  - Problem: "zen" is not a Hanyu Pinyin syllable. The other names parse.
  - Fix: Author decision. "Shezhen" is valid pinyin; avoid "Shenzhen", which is a real PLAN hull name.

- [ ] ATS-52 · L2054, L2076 vs L414–424 · (a/c) · medium
  - Excerpt: "Type 055 and Type 054 frigates, all homeported in the eastern fleet." (L2054)
  - Problem: *Haiyangshan* was earlier under the South Sea Fleet (Guangzhou), and L2076 calls the group a "training squadron". A Type 055 is also not a frigate.
  - Fix: "A Type 055 destroyer and Type 054 frigates" and Author decision on the home fleet.

- [ ] ATS-53 · L2141, L2150, L2218, L2288, L2297, L2323, L2361, L2395 vs strike stamps L2439, L2479, L2497, L2545, L2575, L2603, L2637, L2683, L2691, L2713, L2757, L2797 · (a) · high
  - Excerpt: "Time to Strike: 00:18 CST" (L2150)
  - Problem: Every estimate converges on roughly 2218–2236:
    - "Ninety-one minutes" at 2047 (L2141)
    - "eighty-four minutes" at 2112 (L2218)
    - "67 MINUTES" at 2126 (L2361)
    - the F-15s "Fifty-seven minutes" out (L2323)
    - Kadena's "T-70 MINUTES" (L2297), once its stamp is fixed

    But the missiles fly at 2131 and the bridges are hit at 2133. "00:18" doesn't match any of them, and the Kadena stamp "2119 JST" (2019 TST) falls before the 2039 broadcast.
  - Fix: Author decision. Recommended:
    - L2150 → "22:18 CST"; L2288 → "*2219 JST*".
    - Shift the strike block by +49 minutes: 2129→2218, 2131→2220, 2132→2221, 2133→2222, 2134→2223, 2136→2225, 2140→2229.

- [ ] ATS-54 · L2164 · (f) · medium
  - Excerpt: "but with submission to alien overseers." (L2164)
  - Problem: In Lu's POV, "alien" reads as extraterrestrial, which he cannot know.
  - Fix: "foreign overseers".

- [ ] ATS-55 · L2198 · (c) · low
  - Excerpt: "For the Republic?" (L2198)
  - Problem: Readers may take this as the Republic of China.
  - Fix: "For the People's Republic?"

- [ ] ATS-56 · L2311 · (e) · low
  - Excerpt: "began taxiing under full afterburner" (L2311)
  - Fix: "began rolling under full afterburner".

- [ ] ATS-57 · L2313 · (a) · medium
  - Excerpt: "eight aircraft burning east-southeast in formation" (L2313)
  - Problem: Taiwan lies west-southwest of Okinawa.
  - Fix: "west-southwest".

- [ ] ATS-58 · L2359 · (e) · low
  - Excerpt: "the Joint Chiefs were already in the secure command bunker" (L2359)
  - Fix: "the General Staff".

- [ ] ATS-59 · L2387, L2395, L2904 · (a) · medium
  - Excerpt: "*08:12 EDT*" (L2387)
  - Problem: January uses EST. 08:12 EDT is 20:12 TST, yet Langford already cites Taiwan's evacuation, which began at 2126 TST. The follow-up scene, "*0749 EDT*" (L2904), is earlier in clock time than the first meeting.
  - Fix: With ATS-53 applied: L2387 "*08:30 EST*", L2395 "ETA under an hour", L2904 "*10:49 EST*".

- [ ] ATS-60 · L466 vs L2389, L2407, L2425 · (a) · low-medium
  - Excerpt: "Vance leaned forward, lowering his voice" (L2425)
  - Problem: Rear Admiral Vance and J.D. Vance are unrelated characters sharing a surname.
  - Fix: Author decision. Rename the admiral, e.g. "Thomas Vaughn".

- [ ] ATS-61 · L2439 vs L3137, L3141 · (a) · medium
  - Excerpt: "The timestamp read 21:33:12 when the water at the end of the pier *moved*." (L3141)
  - Problem: The Landmates surface at 2129. 2133 is when they fire.
  - Fix: "21:29:00" and "21:29:12", or "22:18:00" and "22:18:12" if ATS-53 is applied.

- [ ] ATS-62 · L2459 vs L2659 · (a) · medium
  - Excerpt: "still 60 kilometers out, fast approaching." (L2459)
  - Problem: Four minutes later the range is "Fourteen point seven kilometers" (L2659). Closing 45 km in 4 minutes is impossible for these ships.
  - Fix: Author decision. Make L2459 "still 16 kilometers out", or L2659 "Fifty-eight kilometers".

- [ ] ATS-63 · L2477 · (a) · medium-high
  - Excerpt: "### East of Taiwan – Aboard *Haiyangshan*" (L2477)
  - Problem: The ships are approaching from the west, across the Strait.
  - Fix: "### Taiwan Strait – Aboard *Haiyangshan*".

- [ ] ATS-64 · L2483, L2493 vs L2649 · (a) · low-medium
  - Excerpt: "Twenty-four missiles, fired from maximum range" (L2649)
  - Problem: *Haiyangshan* alone fired 12 (L2483), plus four other ships, giving "Dozens of warheads" (L2493).
  - Fix: "Sixty missiles".

- [ ] ATS-65 · L2537 · (g) · low
  - Excerpt: "\"Alright, Bats,\" she muttered, recovering." (L2537)
  - Problem: "Bats" is never explained.
  - Fix: Author decision. Establish it as the flight's callsign or drop it.

- [ ] ATS-66 · L2547 · (f) · medium-high
  - Excerpt: "The Talons broke formation like a flock of ravens" (L2547)
  - Problem: This is Morse's POV, and she learns the name only at L2970.
  - Fix: "The black aircraft broke formation".

- [ ] ATS-67 · L2567 · (c) · low
  - Excerpt: "That was *surgical decapitation*." (L2567)
  - Problem: This is about intercepting missiles. The decapitation of the ships comes later.
  - Fix: "That was *surgery*."

- [ ] ATS-68 · L2573 and L2601 · (g) · low
  - Excerpt: "### Tamsui Fishing Harbor – Coastal Defense Feed" (L2601)
  - Problem: The same heading and the same "2133 TST" appear on consecutive scenes.
  - Fix: Delete the second heading and time stamp, merging the scenes.

- [ ] ATS-69 · L2613, L2619, L2687, L2697 · (a/g) · medium
  - Excerpt: "fired low and dead-straight - barely skimming above the surface tension of the waves." (L2613)
  - Problem: A flat shot cannot make *Lakan*'s "ceiling *imploded*" or enter "through the deck" (L2687). "No trails" (L2619) also contradicts "five incandescent streaks" (L2613).
  - Fix: L2687 "The forward bulkhead *imploded*… a hypersonic penetrator that entered cleanly through the superstructure"; L2619 "No smoke trails."

- [ ] ATS-70 · L2615 vs L2617 · (a) · low
  - Excerpt: "Then, five ships bloomed fire at once." (L2615)
  - Problem: L2617 then gives a sequence ("went first… A heartbeat later").
  - Fix: "Then, five ships bloomed fire within a heartbeat."

- [ ] ATS-71 · L2645 · (c) · medium
  - Excerpt: "all incoming munitions have been -" (L2645)
  - Problem: These are the ship's own outgoing missiles.
  - Fix: "all our munitions have been -".

- [ ] ATS-72 · L2687 · (f) · low
  - Excerpt: "a hypersonic penetrator that entered cleanly through the deck" (L2687)
  - Problem: This is *Lakan*'s CIC POV, and nobody there could identify the weapon type.
  - Fix: Author decision, e.g. "something that entered cleanly through the deck".

- [ ] ATS-73 · L2735–2747 · (b) · medium
  - Excerpt: "the outer third of each wingtip pivoted forward, locking into a forward-swept configuration." (L2739)
  - Problem: talon.md:9 describes a swing-wing that goes from back-swept through minimum sweep to locking into the canards as a delta. There is no forward sweep.
  - Fix: Author decision. Rewrite as the wings sweeping back and locking against the canards into a delta, or add forward sweep to talon.md.

- [ ] ATS-74 · L2763 · (e) · low
  - Excerpt: "AGM-88 HARMs slammed into the radar dishes" (L2763)
  - Problem: USAF F-15s do not carry HARM.
  - Fix: Author decision, e.g. "AGM-158 JASSMs".

- [ ] ATS-75 · L2809 vs L2988 · (a) · low
  - Excerpt: "We have ships about three hours out and closing" (L2809)
  - Problem: The ships arrive about 6.5 hours later.
  - Fix: "about six hours out".

- [ ] ATS-76 · L2817, L2926, L2930 · (b) · low
  - Excerpt: "Quite a show the *Inferno* can put on, yes?" (L2817)
  - Problem: *Inferno* is not in the codex or `translation/glossary.md`, so it is new canon.
  - Fix: Author decision. Add it to air/talon.md, or treat it as a pilot nickname.

- [ ] ATS-77 · L2823 · (a) · low
  - Excerpt: "whoever was flying those things had a name for their guns" (L2823)
  - Problem: *Inferno* was a missile.
  - Fix: "a name for their weapons".

- [ ] ATS-78 · L2835, L2865 · (a) · high
  - Excerpt: "*1847 JST*" (L2835)
  - Problem: These scenes sit between 2140 TST and 0332 TST, but 1847 is before the strike, or about 20 hours after it and after Beijing's 0600 statement (L3052), which they are still drafting (L2884).
  - Fix: With ATS-53 applied: L2835 "*2347 JST*", L2865 "*2347 CST*".

- [ ] ATS-79 · L2849 vs L2583–2621, L2918 · (a) · medium
  - Excerpt: "And we're not even sure *who* made the bridges explode." (L2849)
  - Problem: Morse watched the Landmates paint and fire on the bridges and reported it (L2585, L2621).
  - Fix: "Our pilots saw the Landmates on the Tamsui waterfront fire, but we've got no idea *what* they fired."

- [ ] ATS-80 · L2918 · (c) · high
  - Excerpt: "No known ordinance." (L2918)
  - Fix: "No known ordnance."

- [ ] ATS-81 · L2966 · (c) · low
  - Excerpt: "They look nothing like we've ever seen…" (L2966)
  - Fix: "They look like nothing we've ever seen…"

- [ ] ATS-82 · L2990 · (c) · medium
  - Excerpt: "broke from formation and slowed to flank speed" (L2990)
  - Problem: Flank speed is maximum speed, so ships can't slow to it.
  - Fix: "slowed from flank speed".

- [ ] ATS-83 · L3066 · (f) · low
  - Excerpt: "She did not name the Talons." (L3066)
  - Problem: Beijing does not know the name.
  - Fix: "She did not name the black aircraft."

- [ ] ATS-84 · L3082, L3088, L3104, L3108 vs L3052, L3165, L3340 · (a) · medium
  - Excerpt: "*0902 EST – Atlanta Headquarters*" (L3082)
  - Problem: If this is the same day, it precedes Beijing's 0600 CST statement (1700 EST), which it quotes. If it is the next day, it comes 12 hours after Cooper aired the Tamsui footage (2147 EST), yet it says "There is *no footage*".
  - Fix: "*1715 EST – Atlanta Headquarters*", and change "Good morning" at L3088 to "Good evening".

- [ ] ATS-85 · L3149 · (a) · low
  - Excerpt: "Better than Gaza, because this showed them in action." (L3149)
  - Problem: The Gaza footage showed a Landmate killing a Merkava.
  - Fix: "Better than Gaza, because this showed them firing on warships."

- [ ] ATS-86 · L3165, L3171, L3199, L3319 · (e) · low-medium
  - Excerpt: "He uploaded to Weibo first - his home turf" (L3165)
  - Problem: Weibo is a PRC platform that Taiwanese teens rarely use.
  - Fix: Author decision. Instagram, YouTube or Threads, with the headings to match.

- [ ] ATS-87 · L3217 vs L3273, L3285 · (a) · medium
  - Excerpt: "Colonel Ruslan Petrov from Strategic Planning" (L3273)
  - Problem: Two different Colonel Petrovs (Technical Analysis on the phone, Strategic Planning in the room) appear in consecutive scenes.
  - Fix: Rename the second, e.g. "Colonel Ruslan Sokolov", at L3273 and L3285.

- [ ] ATS-88 · L3257 vs L3265 · (a) · low
  - Excerpt: "suggests near-orbital speeds" (L3257)
  - Problem: The same speaker then says "exceed 3,000 meters per second" and "at orbital speeds". Orbital speed is about 7.8 km/s.
  - Fix: L3257 "hypervelocity"; L3265 "at those speeds".

- [ ] ATS-89 · L3269 · (e) · low
  - Excerpt: "A conventional 130mm shell carries about 40 megajoules of kinetic energy." (L3269)
  - Problem: An AK-130 shell carries about 12 MJ.
  - Fix: "about 12 megajoules".

- [ ] ATS-90 · L3420, L3510 · (a) · high
  - Excerpt: "*0900 TST - Three Weeks Later*" (L3420)
  - Problem: These scenes are in Istanbul; TST is Taiwan time.
  - Fix: "*0900 TRT - Three Weeks Later*", "*1847 TRT*".

- [ ] ATS-91 · L3424, L3428, L3446, L3472, L3484, L3494, L3496 · (e) · high
  - Excerpt: "Secretary-General Jens Stoltenberg sat at the head of the ornate table" (L3424)
  - Problem: Mark Rutte has been NATO Secretary General since 1 October 2024.
  - Fix: "Secretary-General Mark Rutte" and, at L3428, "his Dutch accent".

- [ ] ATS-92 · L3448, L3476, L3492 · (e) · high
  - Excerpt: "General Milley, Chairman of the U.S. Joint Chiefs" (L3448)
  - Problem: Milley retired in September 2023. In early 2025 the Chairman was Gen. C.Q. Brown, until 21 February, then Adm. Grady as acting Chairman until April.
  - Fix: Author decision depending on date: "General Brown" or "Admiral Grady".

- [ ] ATS-93 · L3456 · (a) · low
  - Excerpt: "fourteen separate incidents involving these entities over the past six months" (L3456)
  - Problem: Gaza was more than seven months earlier, and the line says Gaza "was not the beginning".
  - Fix: "over the past year".

- [ ] ATS-94 · L3458, L3480 · (e) · high
  - Excerpt: "Putin's defense minister, Sergei Shoigu, nodded grimly." (L3458)
  - Problem: Andrei Belousov has been defense minister since May 2024.
  - Fix: "Andrei Belousov".

- [ ] ATS-95 · L3460 · (a/e) · medium
  - Excerpt: "\"And that's just what they've shown us,\" Wigston added." (L3460)
  - Problem: Wigston is never introduced, and he left as head of the RAF in 2023.
  - Fix: Introduce a current UK officer, e.g. "Air Chief Marshal Sir Rich Knighton, the RAF's chief, added."

- [ ] ATS-96 · L3476 · (g) · low
  - Excerpt: "\"Not unless we're prepared to meet `HARBINGER`'s pilots again,\" Milley agreed." (L3476)
  - Problem: The pilots are human, not HARBINGER's, and "agreed" doesn't fit what Putin just said.
  - Fix: "\"Not unless we're prepared to meet those pilots again,\" Milley said."

- [ ] ATS-97 · L3494, L3496 · (g) · low
  - Excerpt: "\"I think,\" Stoltenberg said carefully" (L3496)
  - Problem: Two consecutive paragraphs carry the same speaker's tag.
  - Fix: Merge them, or give the first to another speaker.

- [ ] ATS-98 · L3512 vs L3522 · (a) · low
  - Excerpt: "cataloged the departing diplomatic aircraft" (L3522)
  - Problem: The fisherman sees "diplomatic vessels" (L3512).
  - Fix: "cataloged the departing diplomatic vessels".

- [ ] ATS-99 · L3522–3534 · (f) · low
  - Excerpt: "a command structure hidden in the darkness between worlds." (L3522)
  - Problem: This is omniscient narration hinting at alien watchers. It is not in a non-Federation POV, so it is acceptable if intended.
  - Fix: Author decision: confirm the reveal is intended.

- [ ] ATS-100 · L3538 · (e) · low
  - Excerpt: "### BBC Television Centre, London" (L3538)
  - Problem: BBC News has broadcast from Broadcasting House since 2013.
  - Fix: "### BBC Broadcasting House, London".

- [ ] ATS-101 · L3565 vs L3539, L3553 · (a) · low
  - Excerpt: "These coordinated movements began exactly seventy-two hours after reports of an unscheduled diplomatic gathering in Istanbul" (L3565)
  - Problem: The broadcast itself is "72 hours later", yet withdrawals are described as already well under way.
  - Fix: "began within hours of reports".

- [ ] ATS-102 · L3579 · (d) · high
  - Excerpt: "The experts on television spoke of military realignments and diplomatic coordination." (L3579)
  - Problem: The story ends on the setup of a contrast that never arrives.
  - Fix: Author decision. Add a closing sentence, e.g. "None of them could say who had asked for it."

### David v Goliath

`story-david-v-goliath.md`: 98 items, 21 high confidence, 25 needing an author decision.

- [ ] DVG-01 · L14 · (e) · low
  - Excerpt: "As Deputy Chief of General Staff for Intelligence" (L14)
  - Problem: That post belongs to a general officer, not a colonel.
  - Fix: Author decision, e.g. "As a senior officer of the General Staff's intelligence directorate".

- [ ] DVG-02 · L14 vs L514 · (a) · high
  - Excerpt: "Colonel Andriy Kovalenko, who had carried the device" (L514)
  - Problem: He is "Pavlo" at L14.
  - Fix: "Colonel Pavlo Kovalenko".

- [ ] DVG-03 · L18 · (c) · low
  - Excerpt: "\"Sir,\" his driver, Senior Sergeant Mykola Petrov, glanced in the rearview mirror, \"we're approximately ten minutes out" (L18)
  - Problem: "glanced" is used as a speech tag.
  - Fix: "\"Sir,\" said his driver, Senior Sergeant Mykola Petrov, glancing in the rearview mirror, \"we're…".

- [ ] DVG-04 · L18, L97 vs L2229, L2235 · (a) · medium
  - Excerpt: "Senior Sergeant Mykola Petrenko sat in the passenger seat" (L2229)
  - Problem: Kovalenko's driver is "Senior Sergeant Mykola Petrov" (L18), and "Sergeant Petrov" at L97. If the epilogue's man is the same person, the surname changes. He is also said to have spent "eighteen months" at the front (L2235), though he was a staff driver in Transcarpathia.
  - Fix: Author decision. Either the same man ("Petrov" at L2229 and drop "eighteen months"), or make him clearly a different character.

- [ ] DVG-05 · L38 vs L62 · (a) · low
  - Excerpt: "Twenty paces became ten, then five." (L62)
  - Problem: It had already stopped "a few meters away" (L38).
  - Fix: L38 "Twenty meters away, the machine stopped."

- [ ] DVG-06 · L62–71 vs L18 · (a) · medium
  - Excerpt: "The *Landmate* stopped directly beside the driver's side door" (L62)
  - Problem: Petrov is driving, yet the door is torn off and the device placed on Kovalenko's lap (L66, L71). L134 repeats "driver's side door".
  - Fix: Author decision. Make it "the rear passenger door" at L62, L64 and L134, or seat Kovalenko behind the driver.

- [ ] DVG-07 · L67 · (c) · low
  - Excerpt: "the most powerful war machine any military has seen" (L67)
  - Fix: "had seen".

- [ ] DVG-08 · L69 vs L140, L154 · (a) · low
  - Excerpt: "what appeared to be a small display screen set into its surface" (L69)
  - Problem: Later it is a "ruggedized military laptop" with a bright full screen.
  - Fix: Author decision. Make L69 "a hinged lid concealing a display".

- [ ] DVG-09 · L71 onward · (b) · low
  - Excerpt: "\"Targeting coordinator,\" the machine said" (L71)
  - Problem: The device is not in the codex. The codex's Guardian "coordinator node" is something else.
  - Fix: Author decision. Add it to the codex, or rename it to avoid confusion with the Guardian node.

- [ ] DVG-10 · L89 vs L91 · (c) · low
  - Excerpt: "The jumpjets burned with brilliant blue-white light" (L91)
  - Problem: L89 and the codex spell it "jump jets".
  - Fix: "jump jets".

- [ ] DVG-11 · L144 · (c) · low
  - Excerpt: "crackled through encrypted connection" (L144)
  - Fix: "crackled through the encrypted connection".

- [ ] DVG-12 · L144, L148, L154, L261, L1913 · (b/c) · high
  - Excerpt: "Your message indicated contact with Harbinger." (L144)
  - Problem: artificial-intelligence.md:20 says named AIs are "always written in all-uppercase". The story uses HARBINGER elsewhere.
  - Fix: "HARBINGER" on all five lines.

- [ ] DVG-13 · L152 · (c) · low
  - Excerpt: "within hundred kilometers of frontlines" (L152)
  - Fix: "within a hundred kilometers of the frontlines".

- [ ] DVG-14 · Surname collisions: L161, L649, L1176, L1338, L1398, L2229 (Petrenko ×6) and L797/L849 (Petenko); L204/L2188 (Morrison); L401/L1376/L1513 (Koval); L639/L1386 and L165 (Bondar, Bondarenko); L715/L920 (Weber); L758/L1196 (Kozlov); L18/L1060 (Petrov); L200/L1574 (Mitchell); L161/L805/L1410 (Oksana) · (a) · medium
  - Excerpt: "Veteran Sergeant Viktor Petrenko watched from his balcony" (L1398)
  - Problem: Many unrelated characters share surnames or given names. Six unrelated Petrenkos is the worst case.
  - Fix: Author decision. Rename the minor characters, keeping Dr. Oksana Petrenko.

- [ ] DVG-15 · L200 · (b) · medium
  - Excerpt: "but never one claiming direct contact with the Gaza entities" (L200)
  - Problem: The UN had direct contact in Gaza (angels-in-armor:1944–2190). US pilots also talked to Shield flight in ATS L2805–3032.
  - Fix: "but never one claiming the entities had *armed* a combatant".

- [ ] DVG-16 · L125, L200, L1084, L1762, L1764 vs ATS L3205–3313, L3432–3506, L3553 · (b) · medium
  - Excerpt: "This appears to be the same force that intervened in the Middle East conflict." (L1084)
  - Problem: Cross-story. Weeks before 1 March 2025, ATS has Russia's MoD respond to the Taiwan footage by ordering "All Black Sea and Pacific deployments are to avoid confrontational postures" (ATS L3305). Russia, NATO and China then agree at Istanbul to avoid escalation, and the epilogue shows Russia withdrawing from the Baltic. DVG never mentions Taiwan, treats Gaza as the only precedent, and has Russia preparing a major offensive.
  - Fix: Author decision. Add references to the Strait intervention (e.g. L1084 "intervened in Gaza and the Taiwan Strait"), and reconcile the Istanbul de-escalation with the March offensive, or reorder the timeline.

- [ ] DVG-17 · L202 · (a) · low
  - Excerpt: "Test planned within 48 hours." (L202)
  - Problem: The test is entered on 5 March and strikes on 6 March.
  - Fix: "Test planned within the week."

- [ ] DVG-18 · L253–255, L263, L269, L279 · (a) · high
  - Excerpt: "TIME TO EXECUTION: 23:58:47" (L269)
  - Problem: Entry is at about 1643 on 5 March for a strike at 2208 on 6 March, which is about 29 h 25 m, not about 24 h (L263, L279).
  - Fix: L269 "29:24:47"; L279 "29 hours, 24 minutes, and 41 seconds"; L263 "approximately thirty hours".

- [ ] DVG-19 · L279 · (f) · low
  - Excerpt: "Somewhere in the darkness of space, or in facilities that existed beyond terrestrial understanding" (L279)
  - Problem: Omniscient narration hints at off-world infrastructure inside a Ukrainian scene.
  - Fix: Author decision, e.g. "Somewhere far beyond that room".

- [ ] DVG-20 · L286, L297, L310, L323, L350, L389, L428 · (a) · medium-high
  - Excerpt: "*March 6th, 2025 - 2146 hours local time*" (L286)
  - Problem: Bodø and Ramstein run on CET, so 2146 and 2148 CET are 2246 and 2248 Kyiv time, after the 2208 strike. On 7 March, Brussels at 0347 CET is 0447 EET, yet Syrskyi takes Mitchell's call at "0352" local.
  - Fix: L286 "2059 hours", L297 "2101 hours", L310 "2203 hours" (see DVG-21), L389 "0452 hours", L428 "0459 hours". Optionally restamp L323 for occupied Ilovaisk as "2308 hours Moscow time".

- [ ] DVG-21 · L312 vs L323 · (a) · medium
  - Excerpt: "ETA two minutes. Mach 17, three thousand meters." (L312, at 2157)
  - Problem: That makes arrival 2159; the strike is at 2208.
  - Fix: "ETA five minutes" with the L310 stamp at 2203, or keep 2157 and use "ETA eleven minutes".

- [ ] DVG-22 · L312 vs L403 · (a) · low
  - Excerpt: "approached the target at extreme altitude and velocity." (L403)
  - Problem: L312 gives 3,000 m.
  - Fix: L403 "at low altitude and extreme velocity".

- [ ] DVG-23 · L245, L337, L434, L479 · (a) · medium
  - Excerpt: "command center vaporized, locomotive facility shredded." (L337)
  - Problem: The fifth target is "vehicle storage yard with those tanks" (L245), "Vehicle storage" (L434), "vehicle maintenance" (L479), and here a locomotive facility.
  - Fix: L337 "vehicle yard shredded"; L479 "vehicle storage".

- [ ] DVG-24 · L352–366 · (e) · low
  - Excerpt: "a KH-11 reconnaissance satellite positioned over Eastern Ukraine" (L352)
  - Problem: A low-orbit KH-11 can't hover over a target or image it every 30 seconds.
  - Fix: Author decision, e.g. "a KH-11 pass timed for the strike window, backed by commercial constellations".

- [ ] DVG-25 · L401 · (e) · low-medium
  - Excerpt: "positioned three kilometers from Ilovaisk to document the test" (L401)
  - Problem: Ilovaisk is about 50 km behind Russian lines.
  - Fix: Author decision, e.g. "a deep-reconnaissance observer".

- [ ] DVG-26 · L407–413 vs L508 · (a) · medium
  - Excerpt: "vanished before our air defense systems could even track its approach." (L508)
  - Problem: Kyiv tracked the approach (L312–316), and Syrskyi himself confirms "both approach and departure" (L411–413).
  - Fix: "and vanished before our air defenses could do more than watch."

- [ ] DVG-27 · L428 · (a) · high
  - Excerpt: "where they had activated the targeting coordinator less than twelve hours earlier" (L428)
  - Problem: Activation was at 1643 on 5 March; this scene is 0359 on 7 March, about 35 hours later.
  - Fix: "a day and a half earlier".

- [ ] DVG-28 · L460 · (a) · medium
  - Excerpt: "Three days ago, he had been an intelligence officer" (L460)
  - Problem: The encounter was on 1 March and this is 7 March.
  - Fix: "Less than a week ago".

- [ ] DVG-29 · L508, L774 · (b) · low
  - Excerpt: "fired five precision weapons while maintaining hypersonic velocity" (L508)
  - Problem: aurora.md:14 has the Aurora air-brake to about Mach 5 before firing. That is still hypersonic, but "maintaining Mach 18" implies otherwise.
  - Fix: Author decision, e.g. "slowed just long enough to fire five precision weapons".

- [ ] DVG-30 · L510, L522, L528, L548 · (e) · low
  - Excerpt: "Major General Viktor Khorenko, head of air defense forces" (L510)
  - Problem: These are real officers in posts they didn't hold in March 2025:
    - Khorenko commanded special operations forces.
    - Naiev left Joint Forces command in 2024.
    - Moisiuk was a lieutenant general.
    - Dmytro Marchenko never commanded special operations forces.
  - Fix: Author decision. Use fictional names, or the actual post-holders.

- [ ] DVG-31 · L528, L762, L764, L790 · (a) · high
  - Excerpt: "\"I don't know, Oleh. But for the first time…\"" (L790)
  - Problem: Private Marchenko is "Dmytro" at L764 and "Oleh" at L790. He also shares both names with Major General Dmytro Marchenko (L528).
  - Fix: Rename the private, e.g. "Private Hnatiuk", and use "Oleh" at both L764 and L790.

- [ ] DVG-32 · L548 vs L1930 · (c) · low
  - Excerpt: "Major General Serhiy Naiev" (L548)
  - Problem: L1930 transliterates the same name "Serhii".
  - Fix: Use "Serhii" at L548.

- [ ] DVG-33 · L554, L582, L774, L801, L841, L857, L1062 · (e) · medium
  - Excerpt: "Pokrovsk rail depot - their primary ammunition resupply point." (L554)
  - Problem: Pokrovsk was Ukrainian-held in March 2025.
  - Fix: Author decision. Use a Russian-held hub such as "Yasynuvata rail depot".

- [ ] DVG-34 · L584–592, L774, L841, L843, L865 · (a/b) · high
  - Excerpt: "as nine *Stiletto* missiles found their targets" (L841)
  - Problem:
    - Each Aurora carries five Stilettos (aurora.md:12, :44).
    - L774 says "each craft launched five missiles".
    - L865 says "Fifteen weapons, fifteen perfect hits".
    - Pokrovsk takes nine missiles (L841) and Vuhledar loses "fifteen separate buildings" (L843).
    - Naiev marks only one circle per site (L584–592).
  - Fix: L841 "five"; L843 "five separate buildings"; L584–592 have Naiev mark five targets per site.

- [ ] DVG-35 · L639 · (e) · medium
  - Excerpt: "in a destroyed school basement near Avdiivka." (L639)
  - Problem: Avdiivka has been Russian-held since February 2024.
  - Fix: "near Kurakhove" or another Ukrainian-held town.

- [ ] DVG-36 · L647, L649, L758 · (e) · low
  - Excerpt: "overlooking Russian positions near Marinka" (L649)
  - Problem: Marinka (taken in 2023) and Bakhmut (taken in 2023) were well behind Russian lines by March 2025, so Ukrainian observation posts couldn't overlook them.
  - Fix: Author decision. Move the posts west, e.g. "near Kostiantynivka".

- [ ] DVG-37 · L663 · (a) · low
  - Excerpt: "in just over twenty-four hours" (L663)
  - Problem: 1347 on 8 March to 2100 on 9 March is 31 hours.
  - Fix: "in just over thirty hours".

- [ ] DVG-38 · L668, L702–703, L713, L723, L733, L756, L793, L902, L922, L936, L1005 · (a) · medium-high
  - Excerpt: "*March 9th, 2025 - 2047 hours local time*" (L668)
  - Problem: The sequence (2047 → 2052 → 20:54:32 → 20:55:50 → 20:56:51 → 2100 strike) only works on one clock, Kyiv's. Read as "local", Portugal (WET) at 2047 is 2247 Kyiv, after the strike. RT at 2142 MSK is 2042 Kyiv, before it.
  - Fix:
    - L668 "1847 hours local time"
    - L703 "1952 hours"
    - L713 "19:54:32"
    - L723 "19:55:50"
    - L922 "19:54"
    - L936 "19:55"
    - L1005 "*2342 hours local time*"
    - Keep L733 (20:56:51), L756, L793 and L902 as Kyiv/Paris local.

- [ ] DVG-39 · L678 vs L707, L719, L963 · (a) · medium-high
  - Excerpt: "bearing zero-nine-zero, altitude four thousand meters." (L678)
  - Problem: Later they are "well above commercial traffic" (L707) and pass "overhead" a Lufthansa jet at FL350 (L719, L963).
  - Fix: L678 "altitude forty thousand meters".

- [ ] DVG-40 · L703, L709, L719, L727, L735, L739, L747, L751, L772 · (f) · medium
  - Excerpt: "The three *Aurora* strike aircraft crossed into French airspace at 2052 hours" (L703)
  - Problem: The Federation code name is used in narration of scenes anchored on Earth observers, none of whom can know it.
  - Fix: Use "the three strike craft" or "the formation" in these scenes.

- [ ] DVG-41 · L703, L709 · (f/b) · medium
  - Excerpt: "their fusion drives manipulated the atmospheric gases directly" (L709)
  - Problem: The narration explains Federation propulsion. "Magnetic fields containing the plasma" (L703) also conflicts with aurora.md:9, where the sheath comes from compression heating.
  - Fix: Cut the explanatory clauses: "Unlike conventional aircraft, they showed no conventional exhaust, only plasma that glowed with ethereal blue-white light."

- [ ] DVG-42 · L709, L912 vs L703, L713 · (a) · medium
  - Excerpt: "as they crossed France in just under two minutes" (L709)
  - Problem: The timestamps give 2 min 32 s.
  - Fix: "in just over two and a half minutes", at both lines.

- [ ] DVG-43 · L713 · (e) · low
  - Excerpt: "German air defense radar at Ramstein Air Base" (L713)
  - Problem: Ramstein is a US/NATO base.
  - Fix: "NATO air defense radar at Ramstein Air Base".

- [ ] DVG-44 · L721, L908 · (a) · low
  - Excerpt: "In Bavaria, hikers in the Alps stopped to photograph" (L721)
  - Problem: The Paris–Ramstein–Poznań track passes far north of the Alps.
  - Fix: "In Thuringia, hikers in the Harz".

- [ ] DVG-45 · L725, L934 · (c) · medium
  - Excerpt: "Anchor Katarzyna Kowalski introduced footage" (L934)
  - Problem: Polish surnames take the feminine form. She also collides with Lieutenant Piotr Kowalski (L725).
  - Fix: "Katarzyna Kowalska", or another surname.

- [ ] DVG-46 · L729 vs L940 · (a) · medium-low
  - Excerpt: "witnessed the event from her office balcony while working late" (L940)
  - Problem: L729 says "apartment balcony".
  - Fix: Make both "office balcony", which matches "working late".

- [ ] DVG-47 · L739, L998 · (a) · low
  - Excerpt: "Across seven nations, millions of people had witnessed" (L739)
  - Problem: The route crosses France, Germany, Poland and Ukraine.
  - Fix: "Across four nations".

- [ ] DVG-48 · L774 vs L795–841 · (a) · medium
  - Excerpt: "Then the sky erupted. Fifteen brilliant flashes" (L774, in the 2057 scene)
  - Problem: The ops center shows the strike at 00:00, about 2100.
  - Fix: Stamp the L756 scene "*2100 hours local time*", or move the eruption into a later scene.

- [ ] DVG-49 · L797, L849 · (c) · low
  - Excerpt: "called Major Petenko." (L797)
  - Problem: This looks like a typo for Petrenko, which is itself overused.
  - Fix: Author decision, e.g. "Major Petryk".

- [ ] DVG-50 · L803 · (a) · medium
  - Excerpt: "about their decision three days earlier" (L803)
  - Problem: The vote was the day before.
  - Fix: "the day before".

- [ ] DVG-51 · L805 · (c) · high
  - Excerpt: "reported Captainin Oksana Marchuk from her intelligence station" (L805)
  - Fix: "Captain".

- [ ] DVG-52 · L815 · (f) · high
  - Excerpt: "\"Thermal imaging shows the *Auroras* are approaching target zones,\" Captain Marchuk announced" (L815)
  - Problem: A Ukrainian officer uses the Federation code name.
  - Fix: "Thermal imaging shows the strike craft are approaching target zones".

- [ ] DVG-53 · L841, L845 · (f) · medium
  - Excerpt: "reduced to component atoms by *Stiletto* warheads" (L845)
  - Problem: The Federation missile name appears in narration of the Ukrainian ops center POV.
  - Fix: "nine missiles" → "five missiles" (see DVG-34); "by warheads that struck…".

- [ ] DVG-54 · L926 · (e) · low
  - Excerpt: "Federal Aviation Authority spokesman Klaus Richter" (L926)
  - Fix: "German Air Navigation Services (DFS) spokesman".

- [ ] DVG-55 · L479, L1007, L1019, L1264, L1318, L1635 (+ ATS L3211) · (a) · high
  - Excerpt: "he ordered Colonel Dmitri Volkov" (L1635) / "Anchor Dmitri Volkov" (L1007)
  - Problem: Two "Dmitri Volkov"s (an RT anchor and a General Staff colonel) plus two more Volkovs. ATS's SVR chief is also Dmitri Volkov.
  - Fix: Rename the RT anchor, e.g. "Pavel Orlov", at L1007 and L1019, and the other Volkovs.

- [ ] DVG-56 · L1056 vs L1726, L1810, L1816 · (a/e) · high
  - Excerpt: "Defense Minister Sergei Gerasimov adjusted his reading glasses" (L1726)
  - Problem: He is "General Valery Gerasimov… Chief of the General Staff" at L1056. In real life Valery Gerasimov is Chief of the General Staff and Andrei Belousov is Defense Minister.
  - Fix: Author decision. Either "Defense Minister Andrei Belousov" at L1726, L1738, L1810 and L1816, or "General Valery Gerasimov" with the Chief of General Staff role at the same lines.

- [ ] DVG-57 · L1068 · (a) · low
  - Excerpt: "In twenty-four hours, Ukraine had somehow acquired strike capabilities" (L1068)
  - Problem: Ilovaisk was three days earlier.
  - Fix: "In four days".

- [ ] DVG-58 · L1102 vs L1320, L1328 · (a) · medium
  - Excerpt: "we have substantial reserves remaining. Two hundred *Shahed* drones, fifty *Kalibr* cruise missiles, and twelve *Kinzhal*" (L1102)
  - Problem: Two days later there are 800 Shaheds and 200 Kinzhals, "every *Shahed* in Russian stockpiles".
  - Fix: Author decision. Make L1102 "We can commit two hundred…", or reduce the later numbers.

- [ ] DVG-59 · L1134 · (c) · low
  - Excerpt: "and even then because I don't want to." (L1134)
  - Fix: "and even then only because I choose not to."

- [ ] DVG-60 · L1198 · (a) · low
  - Excerpt: "They said two hundred drones, fifty cruise missiles." (L1198)
  - Problem: These are classified numbers from HARBINGER's call to Syrskyi; nothing shows them being made public.
  - Fix: "They said hundreds of drones."

- [ ] DVG-61 · L1264/L1272, L1964 · (g) · low
  - Excerpt: "Major General Konstantin Volkov, head of strategic operations, leaned forward" (L1264)
  - Problem: He leans forward and says nothing, and L1272 is unattributed. "General Shaptala stood immediately." (L1964) also leads nowhere.
  - Fix: Attribute L1272 to Volkov; give Shaptala a line or cut the beat.

- [ ] DVG-62 · L1314, L1320 · (e) · medium
  - Excerpt: "Two hundred *Kinzhal* hypersonic glide bombs from mobile platforms positioned from Kaliningrad to Vladivostok." (L1320)
  - Problem: The Kinzhal is an air-launched aeroballistic missile from the MiG-31K, not a glide bomb, and Vladivostok is out of range. Plesetsk is a space launch site.
  - Fix: "Two hundred *Kinzhal* missiles on MiG-31Ks staged across western Russia"; L1314 "The launch coordination center at…".

- [ ] DVG-63 · L1320 vs L1366 · (a) · medium
  - Excerpt: "Coordinated time-on-target: 0630 hours Moscow time." (L1320)
  - Problem: The first drone reaches the perimeter at "0630:12" Kyiv time, which is 0730 MSK.
  - Fix: "0730 hours Moscow time".

- [ ] DVG-64 · L1340 vs L1320 · (a) · low
  - Excerpt: "approximately seven hundred slow-moving contacts" (L1340)
  - Problem: 800 were launched.
  - Fix: "approximately eight hundred".

- [ ] DVG-65 · L1350 · (a) · low
  - Excerpt: "For two days, the mysterious guardians had stood silent" (L1350)
  - Problem: They appeared on the night of 10–11 March; this is the morning of 12 March.
  - Fix: "For a day and a night".

- [ ] DVG-66 · L1368, L1438 (Kozak POV), L1659, L1667 (Russian dialogue) · (f) · medium
  - Excerpt: "If the Guardian systems could handle drone swarms" (L1438)
  - Problem: The Federation name is used before residents coin "Guardian Angels" later that day (L1570). The narration also uses it from L1368.
  - Fix: L1438 "If the new defenses could handle…"; L1659/L1667 "the mystery turrets"; narration "the turret".

- [ ] DVG-67 · L1404 · (f) · low
  - Excerpt: "Another Guardian battery ejected its own thermal clip" (L1404)
  - Problem: The Federation term appears in Viktor Petrenko's POV.
  - Fix: "ejected its own glowing block".

- [ ] DVG-68 · L1408, L1416 vs L1526, L1534, L1546, L1558, L1606, L1612 · (a) · high
  - Excerpt: "shouted seventeen-year-old Dmitri Kovalenko" (L1408)
  - Problem: The same teenager is "Dmytro" from L1526 on. He also shares Colonel Kovalenko's surname.
  - Fix: "Dmytro" with a new surname, e.g. "Dmytro Hrytsenko", at L1408 and L1416.

- [ ] DVG-69 · L1420, L1509 · (b) · low
  - Excerpt: "creating small fields of cooling thermal waste" (L1420)
  - Problem: guardian.md:16 gives each turret a ten-clip magazine, so a "field" of clips per turret is a stretch.
  - Fix: Author decision, e.g. "scattered clusters of cooling thermal clips".

- [ ] DVG-70 · L1422, L1424 · (g) · low-medium
  - Excerpt: "Yet the precision remained perfect." (L1424)
  - Problem: Consecutive paragraphs both open "Yet" and repeat the same "nothing penetrated five kilometers" point.
  - Fix: Merge them, cutting L1422's second sentence.

- [ ] DVG-71 · L1442, L1494 · (f) · medium
  - Excerpt: "as quantum processors detected the incoming hypersonic threats." (L1442)
  - Problem: This is unknowable tech detail in Kyiv observers' scenes. L1494 says "quantum targeting systems".
  - Fix: "as its targeting systems detected…"; L1494 "as their targeting systems found no more threats".

- [ ] DVG-72 · L1452 vs L1424, L1490 · (a) · low
  - Excerpt: "Fifteen kilometers above the city, the first *Kinzhal* missile simply ceased to exist." (L1452)
  - Problem: Every other kill happens at the five-kilometer perimeter.
  - Fix: "Fifteen kilometers up and five out from the city center".

- [ ] DVG-73 · L1478 · (b) · low
  - Excerpt: "pause for exactly 2.7 seconds to eject a glowing thermal clip" (L1478)
  - Problem: guardian.md:16 and thermal-clips.md say two seconds.
  - Fix: "exactly two seconds".

- [ ] DVG-74 · L1503, L1526, L1540 · (a) · high
  - Excerpt: "For seven minutes, they had witnessed the largest airstrike" (L1503)
  - Problem: The engagement ran from 0630:12 to 0658, about 28 minutes. Line 1540 says "8 minutes".
  - Fix: L1503 "For nearly half an hour"; L1526 "the entire half-hour engagement"; L1540 "28 minutes".

- [ ] DVG-75 · L1552 · (a/e) · medium
  - Excerpt: "*March 12th, 2025 - 1247 hours EST*" (L1552)
  - Problem: US daylight saving time began on 9 March 2025.
  - Fix: "1247 hours EDT".

- [ ] DVG-76 · L1574 vs L2166 (and canon) · (a) · medium
  - Excerpt: "Dr. Sarah Chen, a defense analyst at the Brookings Institution" (L1574)
  - Problem: There is also a "junior producer Sarah Chen" (L2166), and canon already has Commander and Lieutenant Sarah Chen (story-knock-knock.md:433, :2021).
  - Fix: Rename both DVG characters.

- [ ] DVG-77 · L1633, L1841, L1843, L2085 · (a) · medium
  - Excerpt: "In five days, three separate strikes had eliminated seven critical infrastructure nodes" (L1633)
  - Problem: The story shows two strike operations: Ilovaisk with 5 targets, then three sites with 15 missiles. That is neither "three strikes" nor "seven nodes". The span from 6 to 12 March is also six days.
  - Fix: Author decision, e.g. L1633 "In six days, two strike operations had destroyed four critical logistics complexes"; L1841, L1843, L2085 "Two strikes…".

- [ ] DVG-78 · L1637 · (a) · high
  - Excerpt: "And last night's air strike on Kyiv was a total loss" (L1637, at 0847 MSK)
  - Problem: The strike ended at 0658 Kyiv (0758 MSK), under an hour earlier.
  - Fix: "And this morning's air strike…", and move the scene to "*1447 hours local time*" (see DVG-80).

- [ ] DVG-79 · L1649 · (e) · low
  - Excerpt: "approximately forty billion rubles annually" (L1649)
  - Problem: That is about €400M, trivial for a strategic energy concession.
  - Fix: "forty billion dollars annually".

- [ ] DVG-80 · L1659, L1667 · (a) · high
  - Excerpt: "after analyzing footage of the Guardians in action." (L1659)
  - Problem: At 0847 MSK (0747 Kyiv), Dmytro's video isn't uploaded until 0842 Kyiv, so Iran can't have analyzed it and refused.
  - Fix: Move the scene to "*March 12th, 2025 - 1447 hours local time*".

- [ ] DVG-81 · L1782 · (b) · low
  - Excerpt: "crossed his desk eight months earlier" (L1782)
  - Problem: Gaza was 13 June 2024, nine months before.
  - Fix: "nine months earlier".

- [ ] DVG-82 · L1821, L1930 and all Kuleba lines · (e) · high
  - Excerpt: "Foreign Minister Dmytro Kuleba and Defense Minister Rustem Umerov" (L1821)
  - Problem: Andrii Sybiha has been Foreign Minister since September 2024.
  - Fix: Author decision. "Foreign Minister Andrii Sybiha" throughout, including "Dmytro" → "Andrii" at L1863 and L1917, or a fictional minister.

- [ ] DVG-83 · L1913 · (a) · low
  - Excerpt: "Russian capitulation within eighteen days." (L1913)
  - Problem: 1 March to 13 March is twelve days.
  - Fix: "within twelve days", or keep the "eighteen" echo deliberately.

- [ ] DVG-84 · L1930 · (e) · high
  - Excerpt: "Deputy Defense Minister Hanna Maliar, Chief of General Staff Serhii Shaptala" (L1930)
  - Problem: Maliar was dismissed in 2023. Shaptala was replaced in February 2024 by Anatolii Barhylevych.
  - Fix: "Chief of General Staff Anatolii Barhylevych" (also at L2002 and L1964), and a fictional deputy minister.

- [ ] DVG-85 · L1934 · (e) · medium
  - Excerpt: "The Polish mediator, Deputy Foreign Minister Marcin Przydacz" (L1934)
  - Problem: Przydacz was not a deputy foreign minister in 2025.
  - Fix: Author decision, e.g. "Deputy Foreign Minister Władysław Teofil Bartoszewski", or a fictional name.

- [ ] DVG-86 · L1996 · (c) · high
  - Excerpt: "fifty billion euros, dispersed over ten years" (L1996)
  - Fix: "disbursed".

- [ ] DVG-87 · L2014, L2037, L2059, L2073 vs L1930 · (a) · high
  - Excerpt: "Three hours ago, I was sitting across from Deputy Foreign Minister Ryabkov watching him sign documents" (L2073)
  - Problem: Zelenskyy wasn't at Medyka; the Foreign Minister led the delegation. Signing after "two hours" of talks from 1400 (L2014) doesn't match "As of 1730" (L2059). The minister is also back in Kyiv, about 550 km away, "an hour" after signing (L2037).
  - Fix: L2073 "Three hours ago, my Foreign Minister watched Ryabkov sign documents"; L2059 "As of 1600 hours today"; L2037 "had flown back from the border crossing an hour earlier".

- [ ] DVG-88 · L2075 vs L1847 · (a) · low
  - Excerpt: "Yesterday our intelligence indicated Russian forces were preparing major offensive operations." (L2075)
  - Problem: Russia halted all offensive operations at 0800 the previous day.
  - Fix: "Three days ago our intelligence indicated…".

- [ ] DVG-89 · L2089, L2095, L2101 vs L200–210, L415–425 · (a) · medium
  - Excerpt: "Are you telling me that HARBINGER was responsible for those hypervelocity aircraft we've been tracking?" (L2089)
  - Problem: NATO intelligence was told on 2 and 7 March that HARBINGER supplied the capability. "for weeks" (L2095) also overstates eight days.
  - Fix: Author decision. Make Cavoli's line confirmation ("So it's confirmed - HARBINGER's aircraft"); L2095 "for over a week".

- [ ] DVG-90 · L2139 · (g) · medium
  - Excerpt: "Welcome back to the community of nations whose primary concern is reconstruction rather than survival." (L2139)
  - Problem: It is attributed to Zelenskyy but reads as Cavoli's line.
  - Fix: Give it to Cavoli: "> \"Welcome back,\" Cavoli said, \"to the community of nations whose primary concern is reconstruction rather than survival.\""

- [ ] DVG-91 · L2146 · (e) · low
  - Excerpt: "she called to producer Jim Sciutto" (L2146)
  - Problem: Sciutto is a CNN anchor and analyst, not a producer.
  - Fix: Author decision. Use a fictional producer.

- [ ] DVG-92 · L2237–2241 vs L1166, L1180–1192 · (a) · low-medium
  - Excerpt: "where one of the Guardian installations still stood on its hilltop position" (L2237)
  - Problem: The Guardians were placed around five cities, not the eastern front.
  - Fix: Author decision. Add a line saying Guardians were later placed along the front, or cut the beat.

- [ ] DVG-93 · L2243 · (e) · high
  - Excerpt: "As their convoy approached the village of Kramatorsk" (L2243)
  - Problem: Kramatorsk is a city of about 150,000 and was never occupied, yet the text has it "under Russian occupation for three years".
  - Fix: Author decision. Use a town occupied in 2022, e.g. "the town of Sievierodonetsk", and drop "village".

- [ ] DVG-94 · L2247 vs L1948, L1992 · (a) · low-medium
  - Excerpt: "where the last Russian convoy was disappearing toward the border." (L2247)
  - Problem: The withdrawal takes 90 days from 14 March; this is 28 March.
  - Fix: "where another Russian convoy was disappearing".

- [ ] DVG-95 · L2254 · (g) · medium
  - Excerpt: "his landline rang - the same secure line that connected to his private study." (L2254)
  - Problem: "The same" has no referent here; it is carried over from Gerasimov's scene (L1734).
  - Fix: "his private landline rang - the secure line in his study."

- [ ] DVG-96 · L2260, L2264 · (a) · medium
  - Excerpt: "The voice that responded was immediately familiar" (L2260)
  - Problem: Zelenskyy has never spoken to HARBINGER. Its calls went to Syrskyi and Gerasimov. "Again" (L2264) has the same problem.
  - Fix: L2260 "unmistakable from Syrskyi's description"; L2264 "I was wondering when I'd hear from you."

- [ ] DVG-97 · L2318, L2322, L2328 · (e) · high
  - Excerpt: "NATO and Russian Federation would share direct borders." (L2328)
  - Problem: NATO already borders Russia through Norway, Finland, the Baltic states and Poland.
  - Fix: L2328 "NATO and the Russian Federation would share a far longer border along Europe's most militarized front."; L2318 "a crucial buffer along NATO's most dangerous potential front".

- [ ] DVG-98 · L2374, and timeline.md · (c), (b) · medium / low
  - Excerpt: "And somewhere high above Earth, a logline noted a successful intervention." (L2374)
  - Problem: A "logline" is a screenwriting summary. Separately, timeline.md has no entry for this story (1 March 2025), and its Key Milestones list only the Taiwan Strait for 2025.
  - Fix: "a log entry noted". Add a timeline.md entry for this story, and confirm how it orders against *Across the Sea* (see DVG-16).

### Ex Mero Mutu

`story-ex-mero-mutu.md`: 48 items, 15 high confidence, 10 needing an author decision.

- [ ] EMM-01 (b, high). EMM:7; timeline.md:98–110
  > timeline: 2025-03-14
  - Problem: timeline.md's 2025 section lists only Across the Sea and Torchlight. This "line: main" story has no entry.
  - Fix: Add to timeline.md under 2025: `**March 14 – November 15, 2025** - [Ex Mero Mutu](/esf/stories/ex-mero-mutu)`, with bullets for the F-35 cancellation, the May 21 Talon contact, the July 5 acceptance, the July 12 NATO briefing, and the Nov 15 US–Portugal lunch.

- [ ] EMM-02 (e, medium). EMM:67, 85, 130, 262; also 908
  > To his right, Sergeant Santos Leite flew *Watchful 2*, maintaining perfect formation despite the monotony.
  - Problem: Portuguese Air Force fighter pilots are commissioned officers, so a sergeant flying an F-16 wing is implausible. Relatedly, Freitas is a Lieutenant yet "one of our most experienced pilots" (EMM:908).
  - Fix: Author decision. Change "Sergeant (Santos) Leite" to "Lieutenant (Santos) Leite" at EMM:67, 85, 130 and 262. Optionally make Freitas a Captain.

- [ ] EMM-03 (e, medium). EMM:91
  > The Block 20s we received in the upgrade program have at least ten years of airframe life remaining
  - Problem: Portugal flies MLU-upgraded F-16AM/BM aircraft. "Block 20" is Taiwan's F-16A/B variant.
  - Fix: "The MLU jets we received in the upgrade program have at least ten years of airframe life remaining"

- [ ] EMM-04 (e, low). EMM:111
  > the Turks have the TF-X program
  - Problem: TF-X was renamed KAAN in 2023.
  - Fix: "the Turks have the KAAN program"

- [ ] EMM-05 (e, medium). EMM:130
  > adjusted his grip on the stick of his F-16C, call sign *Watchful 1*
  - Problem: Portugal does not operate the F-16C.
  - Fix: "his F-16AM"

- [ ] EMM-06 (a, medium). EMM:130/152, 363/393, 628, 811; 359 vs 624; 67/438/628; 369/624; 359/634
  > "Santos, are you seeing this?" … Corporal Santos was tracking the approaching formation on both primary and secondary radar.
  - Problem: Several Portuguese names are reused in a way that confuses readers:
    - "Santos" is Leite's first name (Freitas calls him "Santos" on the radio). It is also the surname of Corporal Ana Santos (on radar minutes later), Finance Minister Miguel Santos, and Captain Santos.
    - Ribeiro is both Major Carlos Ribeiro and Foreign Minister João Ribeiro.
    - Miguel ×3 (Freitas, Cardoso, Santos). João ×2. Carlos ×2.
  - Fix: Author decision. Rename Corporal Ana Santos, the Finance Minister and Captain Santos, and give the Foreign Minister a different surname.

- [ ] EMM-07 (c, low). EMM:178
  > Stealth aircraft in Portuguese airspace without authorization was significant escalation.
  - Fix: "…was a significant escalation."

- [ ] EMM-08 (g, medium). EMM:180–182 vs 198–200
  > "Control, Watchful 2. Two contacts on intercept course, no weapon locks. Advise weapons?"
  - Problem: The flight already requested ROE at 180 and got an answer at 182. Leite asks again and Control answers almost identically. It reads like a regenerated passage. EMM:184 also restates 178 ("clearly military… difficult to identify").
  - Fix: Author decision. Cut 198–200 and fold "NATO command is… consulting" into 182.

- [ ] EMM-09 (c, high). EMM:186
  > Freitas felt familiar tension of a situation that could turn dangerous quickly.
  - Fix: "Freitas felt the familiar tension of a situation that could turn dangerous quickly."

- [ ] EMM-10 (b, low). EMM:240
  > Not the American accent Freitas expected from intelligence briefings
  - Problem: Nothing in canon gives HARBINGER an American accent. Its Gaza voice is "calm, artificial" (ATS:223), and the Taiwan Talons spoke Cantonese (ATS:1892).
  - Fix: "Not the flat, accentless English of the intelligence recordings, but unmistakably Portuguese - calm, cultured, speaking with careful precision."

- [ ] EMM-11 (a, low). EMM:288 vs 300
  > As mission commander, the decision was his to make.
  - Problem: He immediately defers to Control, and line 300 says "The decision had been made for him."
  - Fix: "As mission commander, the recommendation was his to make."

- [ ] EMM-12 (e, low). EMM:316, 373, 381, 383, 768, 782
  > You are cleared for straight-in approach, Runway 05.
  - Problem: Monte Real (LPMR) has a single runway, 01/19 (to my knowledge).
  - Fix: Replace "Runway 05" with "Runway 01" in all six places, after verifying the runway.

- [ ] EMM-13 (e, low). EMM:397
  > "The Sidewinder stations report intermittent lock capability at best.
  - Problem: The Sidewinder is an air-to-air missile; the base has no "Sidewinder stations."
  - Fix: "The Stinger teams report intermittent lock capability at best."

- [ ] EMM-14 (f, medium). EMM:434, 444, 448, 478
  > Behind them, the two Talons moved with the same mechanical precision they had displayed in flight.
  - Problem: The narration names the aircraft "Talons" in Silva's 1525 POV. HARBINGER first names them at about 1545 (EMM:551).
  - Fix:
    - 434: "the two black aircraft"
    - 444: "the visitors"
    - 448: "The black aircraft began powering down."
    - 478: "approached the visitors slowly"

- [ ] EMM-15 (a, high). EMM:436 (also 440–514, 797, 801) vs 622
  > Sergeant Major António Silva had been a ground crew chief for twenty-three years.
  - Problem: He has the same full name as "Prime Minister António Silva" (EMM:622). Silva also recurs as FOI's Major Silva and TH's Lieutenant Silva.
  - Fix: Rename the crew chief, for example "Sergeant Major António Rocha", at every Silva in EMM:436–514 and 797–801.

- [ ] EMM-16 (g, medium). EMM:569, 573, 575, 626
  > twenty-five Talons would represent air power equivalent to roughly two thousand conventional fighters
  - Problem: If one Talon equals the 28-jet F-16 fleet (569), 25 Talons equal about 700 F-16s. That is not "two thousand" (626) and not "on par with the entire United States Air Force" (575), which has 1,800–2,000 fighters (573). Line 573 also switches "fleet" to "squadron".
  - Fix:
    - 569: "a single Talon would be more than equivalent in combat power to eighty F-16s - nearly three times your current fleet."
    - 573: "If a single Talon was equivalent to eighty F-16s, then twenty-five Talons would be..."

- [ ] EMM-17 (b, medium). EMM:587, 624, 658, 660
  > An artificial intelligence of unknown origin has offered to provide us with fighter aircraft
  - Problem: Since June 2024, HARBINGER has publicly stated "I act on behalf of the EarthSpace Federation" (AIA:2140), and the UN debated the Federation by name (AIA:2272). This story never mentions the Federation; ministers treat HARBINGER's principals as wholly unknown.
  - Fix: Author decision. For example, at 660: "HARBINGER answers to this 'EarthSpace Federation' - and who does the Federation answer to?"

- [ ] EMM-18 (a, medium). EMM:593 vs 605; 937
  > "Months, not weeks." … "provide an answer within two weeks."
  - Problem: Alves says months, then promises two weeks in the same conversation. The answer actually comes on July 5, six and a half weeks later.
  - Fix: 605: "We will consider your proposal carefully and provide an answer within six weeks." Alternatively, drop "Months, not weeks."

- [ ] EMM-19 (e, low). EMM:620
  > Portugal's entry into NATO, its accession to the European Union, the bailout negotiations of 2011
  - Problem: Portugal acceded to the EEC (1986), not the EU.
  - Fix: "its accession to the European Economic Community"

- [ ] EMM-20 (e, low). EMM:622 ff.; 1079; 1287
  > Prime Minister António Silva sat at the head of the table
  - Problem: Fictional office-holders sit beside real ones:
    - PM Silva (real PM: Luís Montenegro), Defense Minister Carvalho, and the other ministers.
    - Gen. Hayes as USAFE commander.
    - Ambassador Mitchell.
    - Real people alongside them: Gen. Cartaxo Alves, Trump, and others.
  - Fix: Author decision. Either keep this as deliberate fictionalization and make the US and NATO cast fictional too (see EMM-32, 41–43, 47), or use real names throughout.

- [ ] EMM-21 (c, low). EMM:797
  > "Lieutenant? Are you alright, sir?"
  - Fix: "all right" (FOI:19 uses "All right").

- [ ] EMM-22 (a, low). EMM:836
  > wrestling with HARBINGER's offer for the past three weeks
  - Problem: On July 1 the offer is six weeks old (May 21), and the first cabinet session was 17 days earlier.
  - Fix: "for the past six weeks"

- [ ] EMM-23 (e/g, medium). EMM:840
  > The document's classification markings were unprecedented - *COSMIC TOP SECRET*
  - Problem: COSMIC TOP SECRET is a NATO marking. Portugal is deliberately withholding this from NATO, so it would use its national top grade.
  - Fix: "*MUITO SECRETO*"

- [ ] EMM-24 (b, medium). EMM:890 (cf. 876, 930)
  > Freitas reports a journey time of approximately twenty-five seconds
  - Problem: `ftl.md`:18 gives the Talon warp 20 AU/s. Earth–Jupiter (about 6 AU in June 2025) would take about 0.3 s. Twenty-five seconds implies about 0.24 AU/s.
  - Fix: Author decision: "a journey time of under a second", or revise the codex figure.

- [ ] EMM-25 (e, low). EMM:884–890
  > According to Freitas's account, the aircraft then traveled to Jupiter.
  - Problem: On June 28, 2025, Jupiter was at solar conjunction (about June 24), so it lay almost behind the Sun. A straight-line warp tunnel would pass the Sun, and the codex says tunnels are affected by gravity.
  - Fix: Author decision. Either ignore it, or move the flight or the destination (Saturn was well placed).

- [ ] EMM-26 (f, low). EMM:910, 1228, 1232
  > It's offering us access to technology that appears to be... alien.
  - Problem: Non-Federation characters (the Interior Minister, the CIA Director, Trump) reason toward alien origin. This is speculation only, and timeline.md:87 already canonizes "UN emergency sessions regarding alien technology", so it is probably acceptable.
  - Fix: Author decision: keep, or soften to "beyond anything human".

- [ ] EMM-27 (c, high). EMM:945
  > I've consulted discretely with our closest EU partners
  - Fix: "discreetly"

- [ ] EMM-28 (g, high). EMM:947–949 vs 1001–1005
  > Portugal would go from being a minor NATO member to potentially its second most powerful.
  - Problem: The sentence is repeated verbatim at 949 and 1005. Line 1003 also repeats 949's "The Americans… already suspicious about our F-35 cancellation."
  - Fix: Cut 1003–1005 and move from 1001 straight to 1007. Alternatively, rewrite 1003–1005 with new content.

- [ ] EMM-29 (a, medium). EMM:1017–1019 vs 1052, 1072–1125, 1181
  > Once our pilots have completed initial training and we have a functional squadron, we'll request a classified briefing
  - Problem: The first five Talons arrive July 6. NATO is briefed July 12 with "initial operational flights" and a "qualification flight", while full capability is "within sixty days".
  - Fix: Author decision. Move the Brussels and White House scenes to about mid-September 2025, or change 1019 to "as soon as our first pilots have flown them".

- [ ] EMM-30 (g, high). EMM:1048 vs 1056
  > "Indeed, Minister. Portugal will not be managing this transition alone. You will have experienced guidance throughout the integration process."
  - Problem: This repeats 1048 word for word and doesn't answer Carvalho's question at 1054 ("Human personnel?").
  - Fix: 1056: "Indeed, Minister. Experienced instructors who have flown these aircraft. They will remain until your crews are fully proficient."

- [ ] EMM-31 (a, high). EMM:1062
  > their departure as sudden as their arrival had been three weeks earlier.
  - Problem: The arrival was May 21 and the departure July 5.
  - Fix: "six weeks earlier."

- [ ] EMM-32 (e, high). EMM:1075 (also 1083, 1115, 1179, 1197)
  > Secretary-General Anders Fogh Rasmussen sat at the head of the polished table
  - Problem: The NATO Secretary-General in 2025 is Mark Rutte. Rasmussen served 2009–2014.
  - Fix: "Secretary-General Mark Rutte", and "Rutte" at the other four lines.

- [ ] EMM-33 (a, low). EMM:1079 vs 1129
  > her eyes sharp with intelligence officer instincts
  - Problem: She is the USAFE commander with a "professional pilot's eye" (1129).
  - Fix: "her eyes sharp with a fighter pilot's instincts"

- [ ] EMM-34 (e, low). EMM:1105, 1177
  > "Nevertheless, Marshal Windsor, Portugal does,"
  - Problem: The correct form of address is "Air Chief Marshal". It is used correctly at 1103, 1133 and 1175.
  - Fix: "Air Chief Marshal Windsor" at 1105; "Air Chief Marshal," at 1177.

- [ ] EMM-35 (g, medium). EMM:208 vs 1087–1199, 1212–1278
  > Every NATO pilot had seen classified briefings from the Taiwan Strait incident.
  - Problem:
    - Freitas identifies the Talons as the Taiwan "black triangles" on sight.
    - At NATO, Gen. Hayes (a pilot) and the CIA Deputy Director never make the link.
    - The White House never connects the aircraft to HARBINGER or Taiwan. The President even asks "who the hell sold it".
  - Fix: Author decision. Add one line at NATO and one at the White House recognizing the Taiwan aircraft.

- [ ] EMM-36 (c, low). EMM:1135
  > The footage continued, showing the pilot's calm voice narrating the demonstration over the radio.
  - Fix: "The footage continued, the pilot's calm voice narrating the demonstration over the radio."

- [ ] EMM-37 (g, high). EMM:1151 vs 1167
  > Deputy Director Richardson was already reaching for his secure phone.
  - Problem: The same sentence opens both paragraphs.
  - Fix: 1167: "Richardson had the secure phone in his hand now."

- [ ] EMM-38 (a, high). EMM:1159 vs 1193
  > General Dubois spoke for the first time, his voice carrying the weight of French strategic thinking.
  - Problem: He already "spoke for the first time" at 1159.
  - Fix: 1193: "General Dubois leaned forward, his voice carrying the weight of French strategic thinking."

- [ ] EMM-39 (g, medium). EMM:1169 vs 1151, 1167, 1212–1232
  > "Washington is already aware. This demonstration was coordinated with appropriate American intelligence services."
  - Problem: The CIA Deputy Director in the room is blindsided, and the White House reacts with shock hours later.
  - Fix: "Washington was informed this morning, in general terms, through appropriate channels."

- [ ] EMM-40 (e, high). EMM:1210
  > ### July 12, 2025 - 1530 hours EST
  - Problem: Washington is on daylight time in July.
  - Fix: "### July 12, 2025 - 1530 hours EDT"

- [ ] EMM-41 (e, high). EMM:1214, 1224, 1236, 1244, 1256, 1268
  > Secretary of Defense Lloyd Austin spoke first
  - Problem: The July 2025 Secretary of Defense was Pete Hegseth.
  - Fix: "Secretary of Defense Pete Hegseth" and "Secretary Hegseth" at all six lines.

- [ ] EMM-42 (e, high). EMM:1216, 1228, 1234, 1248, 1252
  > CIA Director William Burns leaned forward from his video connection at Langley.
  - Problem: The 2025 CIA Director was John Ratcliffe.
  - Fix: "CIA Director John Ratcliffe" and "Ratcliffe" at all five lines.

- [ ] EMM-43 (e, high). EMM:1220, 1240, 1260, 1264
  > National Security Advisor Jake Sullivan consulted his classified briefing materials.
  - Problem: In July 2025, Marco Rubio was acting National Security Advisor (after Waltz left in May).
  - Fix: "National Security Advisor Marco Rubio" and "Rubio" at all four lines.

- [ ] EMM-44 (b/g, low). EMM:1272
  > For the first time since the end of the Cold War, the United States faced a military technology gap
  - Problem: Gaza (2024) and Taiwan (Jan 2025) already exposed the gap, as this story itself notes at EMM:342.
  - Fix: "For the first time, the gap had a flag on it: an ally, not a phantom, held technology America could not match."

- [ ] EMM-45 (e, medium). EMM:1282, 1285
  > overlooking the gardens of the Portuguese Defense Ministry's official residence
  - Problem: The Palácio dos Marqueses de Fronteira is a private palace run by a family foundation, not a ministry residence.
  - Fix: "overlooking the gardens of the Fronteira palace, borrowed for the occasion"

- [ ] EMM-46 (e, low). EMM:1287
  > Mitchell had served as U.S. Ambassador to Portugal for eighteen months
  - Problem: In Nov 2025 that would make her a Biden appointee still serving; political ambassadors left in January 2025.
  - Fix: "for six months"

- [ ] EMM-47 (e, high). EMM:1394, 1396, 1398, 1410, 1424, 1426, 1440
  > Deputy Secretary of State Victoria Nuland waited expectantly
  - Problem: The Deputy Secretary of State in Nov 2025 was Christopher Landau. Nuland left government in 2024 and was never confirmed as Deputy.
  - Fix: "Deputy Secretary of State Christopher Landau". Change "Madam Deputy Secretary" to "Mr. Deputy Secretary" (1396, 1426) and "Nuland" to "Landau".

- [ ] EMM-48 (a, medium). EMM:1402 (vs 1079)
  > repeated General Patricia Hayes from her Pentagon office.
  - Problem: She commands US Air Forces in Europe, headquartered at Ramstein.
  - Fix: "from Ramstein."

### Torchlight

`story-torchlight.md`: 6 items, 1 high confidence, 1 needing an author decision.

- [ ] TL-01 · line 177 vs 223, 253 · (b) · high
  - Excerpt: `The *Galara’s Hope* emerged from warp at the edge of the next system`
  - Problem: warp drives work only within a system; ships cross between systems by stargate (codex/foundations/ftl.md). The story itself has the ship warp to the stargate at 223 and 253.
  - Fix: `The *Galara’s Hope* emerged from the stargate at the edge of the next system`
- [ ] TL-02 · line 223 · (b) · medium
  - Excerpt: `aligning with its next jump vector.`
  - Problem: the ship then uses its warp drive. Jump drives are a different technology in the codex (ftl.md).
  - Fix: `aligning with its next warp vector.`
- [ ] TL-03 · line 15 · (g) · low–medium
  - Excerpt: `a name unknown to the Federation’s more established threat lists`
  - Problem: the freighter is Kryllian-Xenari, not a Federation ship, and the point of view is its crew.
  - Fix: `a name on none of the established threat lists`
- [ ] TL-04 · line 17 · (b) · low
  - Excerpt: `Selaari, the Xenari communications officer, her silvered crest pulsing with agitation.`
  - Problem: codex/galaxy/xenari.md gives the Xenari bioluminescent skin markings, not crests.
  - Fix: `her bioluminescent markings pulsing with agitation.`
- [ ] TL-05 · line 143 · (c) · low
  - Excerpt: `rose to millions of Kelvin instantaneously`
  - Problem: unit names are lowercase, and plural here.
  - Fix: `millions of kelvins`
- [ ] TL-06 · lines 185–205 · (g) · low
  - Excerpt: `_"This is *Galara’s Hope*, requesting docking clearance..."_` / `“Destroyed,” Sevalan corrected.`
  - Problem: the comms exchange italicizes some transmitted lines (185, 187, 191, 193, 197, 205) and not others (195, 199). The italics also nest `*…*` inside `_…_`.
  - Fix: author decision. Italicize all the transmitted lines, or none.

### Flight of Icari

`story-future-flight.md`: 51 items, 16 high confidence, 10 needing an author decision.

- [ ] FOI-01 (g, medium). FOI:3
  > layout: page
  - Problem: Every other story uses `layout: story`, so this one may render without the story template.
  - Fix: `layout: story`

- [ ] FOI-02 (b, high). timeline.md:216
  > **Ongoing** - [Future Flight](/esf/stories/future-flight)
  - Problem:
    - The title is "Flight of Icari" and the permalink is `/stories/flight-of-icari`, so the link is broken.
    - The frontmatter dates the story to 2026-06-15, but the timeline lists it only as "Ongoing".
  - Fix: `**June 15, 2026** - [Flight of Icari](/esf/stories/flight-of-icari)`, with the entry also placed in the 2026 section.

- [ ] FOI-03 (e, high). FOI:11, 1555
  > as Vandenberg Air Force Base came alive with jetwash and radio chatter
  - Problem: The base was renamed Vandenberg Space Force Base in May 2021.
  - Fix: "Vandenberg Space Force Base" at both lines.

- [ ] FOI-04 (b, medium). FOI:13
  > *Federation Aerospace Tactical Frame - Talon.*
  - Problem: `naming-conventions.md`:81 and `talon.md`:9 designate it VSX-7.
  - Fix: "*VSX-7 Talon.*"

- [ ] FOI-05 (a, low). FOI:17, 139, 161, 501–503, 1035, 2528
  > "*Gripen returning to airspace,*" Central cut in. … "Talon Flight, this is Command.
  - Problem: The controlling voice is called "Control", "Central" and "Command" interchangeably, sometimes in the same exercise.
  - Fix: Author decision. Use "Control" for range control and "Central" only for the Federation HQ.

- [ ] FOI-06 (g, high). FOI:19 vs 139, 311
  > once you hit 10%, you will have won the engagement.
  - Problem: Read as "deal 10%", NATO won when the shield reached 88%. Read as "reach 10%", the wording is unclear.
  - Fix: "once you bring it down to 10%, you will have won the engagement."

- [ ] FOI-07 (e, medium). FOI:27, 471, 593 (also 2506)
  > "You'll be surprised, sergeant. Now get ready for takeoff!"
  - Problem: Adams (a USAF F-22 pilot) and Lindholm (a Swedish Gripen pilot, "SGT LINDHOLM") are sergeants. Both air forces' fighter pilots are officers.
  - Fix: Author decision. Make them captains, e.g. "You'll be surprised, Captain." / "Captain Christopher Adams" / "*TALON-3 – CPT LINDHOLM*".

- [ ] FOI-08 (a, low). FOI:129 vs 39, 55, 87
  > Colonel Kraus had waited—patient, silent—as his wingmen fell away.
  - Problem: Kraus gave orders and fired IRIS-Ts throughout.
  - Fix: "Colonel Kraus had held high—patient—as his wingmen fell away."

- [ ] FOI-09 (a, high). FOI:223 vs 139, 311
  > "Still took all three of you to get me to ninety-one,"
  - Problem: The minimum was 88%.
  - Fix: "to get me to eighty-eight,"

- [ ] FOI-10 (f, medium). FOI:243–245
  > "Several deployments," he said. "Most recently Kaldrith Prime. You wouldn't like the weather."
  - Problem:
    - A NATO pilot asks openly about "off-world" service, and Voss names an alien-sounding world to non-Federation personnel.
    - "Kaldrith Prime" is not in the codex.
  - Fix: Author decision. For example: "Several deployments. Somewhere you can't pronounce. You wouldn't like the weather." If kept, add Kaldrith to the codex.

- [ ] FOI-11 (a, medium). FOI:259 vs 2398
  > Even that looked alien—no hydraulics, no visible joints … Hydraulic actuators hummed softly.
  - Fix: 2398: "Actuators hummed softly."

- [ ] FOI-12 (c, low). FOI:289
  > "Thank you, Colonel Hargreaves," she said as she reached the podium.
  - Problem: Hargreaves is never introduced.
  - Fix: Add before 283: "Colonel Hargreaves, the range commander, stepped aside for the next speaker."

- [ ] FOI-13 (b, low). FOI:289 ff.
  > This is *Ember*.
  - Problem: `artificial-intelligence.md`:21 says AIs with names and personalities are written in all caps, while lesser AIs are shackled and nameless. Ember has a name, a gender and a personality.
  - Fix: Author decision: `EMBER`, or define Ember as a lesser AI in the codex.

- [ ] FOI-14 (c, high). FOI:293
  > the ability to fire any weapons, **and** restricted him to visual and manual boresight.
  - Problem: The sentence breaks; its subject changes partway through.
  - Fix: "As you'll note, Sergeant Voss flew without active jamming, smart countermeasures, or the ability to fire any weapons, **and** was restricted to visual and manual boresight."

- [ ] FOI-15 (c, low). FOI:305
  > "We observed full visual tracking in 100% of engagement passes.
  - Problem: No speaker is given.
  - Fix: Insert "Halden went on, unbothered." before it.

- [ ] FOI-16 (a, low). FOI:347–349
  > "All four of you have been cleared for conditional flight certification on the *Talon* airframe.
  - Problem: Voss is already a Talon pilot; only three are trainees.
  - Fix: "All three of you…" and, at 349, "All three?"

- [ ] FOI-17 (c, medium). FOI:357; 1397; 2308, 2324, 2328, 2334, 2362, 2364, 2381, 2402
  > *Talon-One* through *Talon-Four* … "Talon-1, cleared." … Talon One is launching momentarily
  - Problem: The others are consistently "Talon-2/-3/-4". Voss is spelled three ways.
  - Fix: Use "Talon-1" everywhere: "*Talon-1* through *Talon-4*" at 357, and change "Talon One" to "Talon-1" at the eight lines from 2308 on.

- [ ] FOI-18 (b, high). FOI:359, 459, 573, 789, 797
  > The HUD lock shifted the moment he *thought* about switching targets
  - Problem: Talon control is by "neural latency", a "neural relay mesh" and reading thoughts. `neural-interfacing.md`:10 says Talon and Landmate pilots never wire into the machine; control is motion capture and force feedback, and neural links are only for low-bandwidth HUD and comms.
  - Fix: Author decision. Recast as eye-tracking and motion capture (e.g. 789: "the moment his eyes flicked toward a mobile drone"; 797: "It tracks where you're looking."), or amend the codex.

- [ ] FOI-19 (e, medium). FOI:503, 511
  > The four Talons roared off Vandenberg's Runway 17
  - Problem: Vandenberg's runway is 12/30.
  - Fix: "Runway Three-Zero" (503) / "Runway 30" (511). A Runway 30 departure fits the westward bank over the ocean.

- [ ] FOI-20 (a, low). FOI:633, 725, 1403, 2540
  > The transition to air-breathing mode occurred automatically at 67,000 feet
  - Problem: The engine transition happens at 70,000, 67,000, 68,000 and 70,000 ft in different scenes.
  - Fix: Standardize on 70,000 ft (725, 1403).

- [ ] FOI-21 (c, medium). FOI:651, 1625
  > Lindholm grit his teeth.
  - Fix: "gritted" at both lines.

- [ ] FOI-22 (e, low). FOI:661, 665, 677, 697
  > At 120,000 feet, atmospheric drag was irrelevant.
  - Problem:
    - 36.6 km is not "orbit-kissing". Drag is not irrelevant, and the Talons cannot "hold station".
    - Auroras "along the pole" are not visible in daylight from there, 5,000+ km away.
  - Fix: "At 120 kilometers, atmospheric drag was irrelevant." Delete "and far to the north, faint auroras curled along the pole".

- [ ] FOI-23 (b, low). FOI:771
  > no hardpoints, no pylons, just internal bays
  - Problem: `talon.md`:20 gives the Talon "external hardpoints".
  - Fix: "hardpoints bare, weapons stowed in internal bays"

- [ ] FOI-24 (a, low). FOI:805 vs 957
  > A thin beam of pale blue light lanced out … clean and invisible save for the brief flicker
  - Fix: Author decision. Pick one look for the plasma cannon.

- [ ] FOI-25 (a, medium). FOI:933
  > Lindholm barked while focused on the remaining F-16
  - Problem: Both F-16s are still flying; Bravo dies at 961 and Alpha at 1015.
  - Fix: "while focused on the Bravo F-16"

- [ ] FOI-26 (c, medium). FOI:959
  > shrapnel spinning out like glitter in vacuum.
  - Problem: This is over Nevada, in atmosphere.
  - Fix: "like glitter in the desert sun."

- [ ] FOI-27 (c/d, high). FOI:1061
  > "Every instinct and every brain cell in Lindholm's head screamed against him as he dove his Talon directly at the water."
  - Problem: A narration sentence is wrapped in quotation marks, probably a leftover prompt or note.
  - Fix: Remove the quotation marks.

- [ ] FOI-28 (e, medium). FOI:1167, 1171, 1197, 1267
  > "That's no decoy. That's a Jin-class."
  - Problem: Jin (Type 094) is a ballistic-missile submarine (SSBN), not a "Strategic Reconnaissance Submarine", and would not loiter off California.
  - Fix: Change "Jin-class" to "Shang-class" at 1167, 1197 and 1267. Change 1171 to "PLAN Nuclear Attack Submarine".

- [ ] FOI-29 (a, medium). FOI:1175, 1177, 1273
  > Commander Zhen approached the console, eyes narrowing.
  - Problem: He is called Captain at 1175 and 1273.
  - Fix: 1177: "Captain Zhen approached the console"

- [ ] FOI-30 (e, low). FOI:1181
  > deployed through a slender hull sleeve fitted for high-depth observations.
  - Problem: A periscope at 410 m is implausible.
  - Fix: "An external low-light camera pod extended from a hull sleeve fitted for deep observation."

- [ ] FOI-31 (a, medium). FOI:1173–1309 vs 2192–2640
  > Eyes flicked toward Liu, the senior technical analyst.
  - Problem: Two different Lius: the sub's sonar officer and the Beijing analyst. Canon also has General Liu (ATS:1032).
  - Fix: Rename the analyst (e.g. "Wei") at 2192, 2194, 2204, 2208, 2218, 2604, 2622 and 2640.

- [ ] FOI-32 (b, medium). FOI:1341, 1722 (cf. 1557)
  > Barely a second to the Moon. Not more than four to Mars.
  - Problem: `ftl.md`:18 gives 20 AU/s, so 100 million km takes about 0.03 s. Four seconds implies about 0.17 AU/s. It is also inconsistent with the Moon in 0.3 s.
  - Fix: Author decision. "Barely a second to the Moon. Not much more to Mars." and at 1722 "in a heartbeat", or revise the codex.

- [ ] FOI-33 (b, low). FOI:1359, 1361
  > This includes FTL vector alignment, bubble projection, and subspace braking procedures.
  - Problem: `ftl.md`:20 describes a warp tunnel that the ship cannot control once formed: no bubble, no braking, no nacelles.
  - Fix: "This includes alignment, tunnel formation, and exit procedures." Delete "warp nacelles—stealthed… operations" or add them to `talon.md`.

- [ ] FOI-34 (f, low). FOI:1367
  > "Mars gets *crowded* fast."
  - Problem: This hints at off-world traffic to non-Federation pilots.
  - Fix: Author decision: "Mars comes up fast."

- [ ] FOI-35 (e/a, high). FOI:1415, 1425
  > Altitude: 140,000 feet. … They were in low Earth orbit.
  - Problem: 140,000 ft is 42.7 km. Low Earth orbit starts at about 160 km, and Tiangong is at about 390 km.
  - Fix: 1415: "Altitude: 350 kilometers."

- [ ] FOI-36 (b, high). FOI:1487, 1569–1571 vs EMM:884–890, 930, 1153–1161
  > but interplanetary warp remained theoretical.
  - Problem: In EMM, HARBINGER flew Freitas to Jupiter in 2025, the Portuguese cabinet was briefed on it, and Portugal showed orbital footage to NATO. Silva's "never knew they could do *this*" contradicts that.
  - Fix:
    - 1487: "but beyond one demonstration flight to Jupiter, none of their own pilots had been cleared to warp."
    - 1569: "We've been flying these for a year and never flown them like *this*."

- [ ] FOI-37 (e, high). FOI:1489 vs 1557
  > a clean vector spike arcing toward the Moon—just a quarter-million kilometers away.
  - Problem: The Moon is about 384,400 km away (FOI:1557 has it right). A quarter-million is the figure in miles.
  - Fix: "—barely four hundred thousand kilometers away."

- [ ] FOI-38 (a/e, low). FOI:1501
  > "Since I'm the wing commander, I have navigation override over you all.
  - Problem: A sergeant leading four aircraft is a flight lead, not a wing commander.
  - Fix: "Since I'm flight lead,"

- [ ] FOI-39 (e, low). FOI:1535, 1551
  > Sun pushed away from the console, walking to the viewing panel.
  - Problem: Tiangong is in microgravity, so nobody walks or stands.
  - Fix: 1535: "drifting to the viewing panel." 1551: "They hung there in silence,"

- [ ] FOI-40 (b/f, low). FOI:1668–1674, 1724, 1834, 2014, 2020, 2034
  > - **Cyno Point**
  - Problem: Several new names have no codex source:
    - Places shown to NATO pilots: Jovian Shipyards, Cyno Point, Frontier Listening Post #1.
    - Shard, Netburst and Fragmentation seeker missiles.
    - The *Caldera Echo*.
    - A 100 km minimum warp range.

    Per the canon rule these need proposing. The place names are also Federation infrastructure that non-Federation pilots now see. Note that `alien-technology.md`:12 says the Jupiter cyno beacon is Xenari, which a "Cyno Point" entry hints at.
  - Fix: Author decision. Add these to the codex, or grey out and rename the sensitive menu entries.

- [ ] FOI-41 (c, low). FOI:1866, 1900, 1906 vs 21, 1994, 2012, 2028, 2506, 2512
  > Kraus' visual data appeared in the others' cockpits
  - Fix: "Kraus's" (1866, 1906) and "Adams's" (1900).

- [ ] FOI-42 (a, high). FOI:1968 vs 1972
  > Four drones in tight formation were obliterated instantly … "Direct impact. Five drones neutralized,"
  - Fix: 1968: "Five drones in tight formation were obliterated instantly"

- [ ] FOI-43 (b, high). FOI:2136 vs EMM:884–890, 930
  > You are the first humans outside the Federation to experience warp travel.
  - Problem: Freitas (Portuguese Air Force) warped to Jupiter in 2025.
  - Fix: "You are the first humans outside the Federation to qualify on warp travel."

- [ ] FOI-44 (e, low). FOI:2176, 2598
  > ### People's Liberation Army Strategic Intelligence Bureau – Beijing
  - Problem: No such body exists; the real one is the Joint Staff Department Intelligence Bureau.
  - Fix: "### Joint Staff Department Intelligence Bureau – Beijing" at both lines.

- [ ] FOI-45 (b, high). FOI:1187, 2178–2220, 2600–2646, 2652–2692, 2698–2730, 2738–2770
  > it is decades beyond anything in our black labs.
  - Problem:
    - Beijing, Moscow, New Delhi and Tokyo treat the Talon as never seen before and probably American.
    - In ATS (Jan 2025), Talons escorted Chinese J-16s and Beijing studied the cockpit recordings (ATS:1892).
    - In EMM, Portugal has openly flown 25 Talons in NATO since mid-2025, and US intelligence watched (EMM:1329).
    - Liu's "third recorded encounter" (2604) ignores both.
  - Fix: Author decision. Have the analysts match the silhouettes to the 2025 Taiwan aircraft and Portugal's fleet. The new information becomes the USAF insignia, not the airframe.

- [ ] FOI-46 (g, high). FOI:2248, 2250 vs 2330
  > Speed: 5,200 knots. Altitude: 74,000 feet.
  - Problem: The radar reports a balloon at 5,200 knots. "Impossible altitude" (2248) is normal for a balloon, and it is later found at 81,000 ft.
  - Fix: 2248: "Something massive—slow, irregular—was drifting in from the west at extreme altitude." 2250: "Speed: 40 knots. Altitude: 81,000 feet." Or make the readings deliberate spoofing.

- [ ] FOI-47 (e, low). FOI:2506
  > Former F-15E Strike Eagle pilot, two deployments over the Taiwan Strait
  - Problem: The USAF does not fly combat deployments "over" the Strait.
  - Fix: "two deployments to Kadena"

- [ ] FOI-48 (g, low). FOI:2692
  > I don't like mysteries in American airspace that *China* is asking us to solve.
  - Problem: The intercept happened over the Taiwan Strait.
  - Fix: "mysteries in American hands"

- [ ] FOI-49 (a, high). FOI:2698 vs 1265, 1315
  > video from the Tiangong station, another from the South China Sea
  - Problem: The sub encounter was ten kilometers off California, in the Eastern Pacific.
  - Fix: "another from the Eastern Pacific"

- [ ] FOI-50 (c, low). FOI:2730
  > And alert Prime Minister's Office.
  - Fix: "And alert the Prime Minister's Office."

- [ ] FOI-51 (b, medium). FOI:2712, 2758
  > Flight time from California to the Strait? Four minutes.
  - Problem: About 10,500 km in 4 minutes is roughly 44 km/s. `talon.md`:13 caps the sub-orbital boost "just shy of escape velocity" (11.2 km/s), which means at least about 16 minutes.
  - Fix: 2758: "Eighteen minutes." 2712: "in under twenty minutes"

### The Helpers

`story-the-helpers.md`: 64 items, 12 high confidence, 12 needing an author decision.

- [ ] TH-01 (b, low). TH:21
  > It was the same synthetic rasp that had introduced itself in Gaza
  - Problem: Canon describes the voice as "calm, artificial" (ATS:223), and EMM calls it calm and cultured.
  - Fix: "It was the same calm, artificial voice that had introduced itself in Gaza"

- [ ] TH-02 (e, low). TH:25
  > Three thousand people held their breath.
  - Problem: The General Assembly Hall seats about 1,800.
  - Fix: "Nearly two thousand people held their breath."

- [ ] TH-03 (a, low). TH:29; TH:613; TH:2141; TH:2501
  > Ambassador Katarina Voss of Germany felt her pulse spike.
  - Problem: Names are reused across stories:
    - Voss is also FOI's pilot.
    - Silva is the Brazilian cadet here, plus EMM ×2 and FOI.
    - Dubois is the Canadian cadet here and EMM's French general.
    - Vasquez is the BBC guest here and a Knock Knock pilot (timeline:191).
    - Carter is the FEMA worker here and Adrenaline's Logan Carter.
  - Fix: Author decision. At minimum rename the ambassador (e.g. "Katarina Vogt").

- [ ] TH-04 (e, medium). TH:39, 153
  > The Secretary-General hammered his gavel repeatedly
  - Problem: The President of the General Assembly presides and holds the gavel.
  - Fix:
    - 39: "The President of the General Assembly hammered the gavel repeatedly"
    - 153: "The President of the General Assembly stared at the gavel"

- [ ] TH-05 (e, medium). TH:87, 567
  > Hurricane season was approaching. … Late September in Florida meant calm weather, at least. No hurricanes
  - Problem: The season runs June to November and peaks around Sept 10.
  - Fix:
    - 87: "Hurricane season was at its peak."
    - 567: "Late September in Florida had been mercifully quiet, at least. No landfalls,"

- [ ] TH-06 (a/b, medium). TH:87, 210, 2066, 2628; timeline.md:189
  > I want to bring in Dr. Sarah Chen, director of the Center for Emerging Technologies at MIT.
  - Problem:
    - Four Chens in this story.
    - "Sarah Chen" collides with canon's Commander Sarah Chen (Knock Knock, 2027).
    - The US UN ambassador in 2026 is Mike Waltz, not "Michael Chen".
  - Fix: Rename Dr. Sarah Chen (e.g. "Dr. Sarah Lindqvist"). Author decision on the others.

- [ ] TH-07 (a/b, low). TH:155, 311, 372, 1761, 1851 vs 2722, 2734; AIA:2272
  > provided by an organization we cannot contact.
  - Problem: The Federation is "uncontactable", yet the generals debate whether to contact HARBINGER. In AIA the UN "asked for contact. We received it."
  - Fix: 1761: "provided by an organization that answers only when it chooses."

- [ ] TH-08 (a, medium). TH:157 vs 143
  > The DECLINE votes glowed red on the board: Russia, North Korea, Iran, Syria, Venezuela, Belarus, Eritrea, Myanmar, Cuba, Zimbabwe.
  - Problem: It reads as the full list but names 10 of the 30.
  - Fix: "The DECLINE votes glowed red on the board, among them Russia, North Korea, Iran, Syria, Venezuela, Belarus, Eritrea, Myanmar, Cuba, Zimbabwe."

- [ ] TH-09 (e, low). TH:256, 560
  > ### FEMA Region IV Emergency Operations Center, Camp Blanding, Florida
  - Problem: FEMA Region IV is based in Atlanta. Camp Blanding is a National Guard post.
  - Fix: Author decision: "### FEMA Region IV Logistics Staging Area, Camp Blanding, Florida"

- [ ] TH-10 (a, medium). TH:75, 265, 573, 1914, 2292
  > asked Martinez, one of the heavy equipment operators.
  - Problem: CNN's Rachel Martinez, the FEMA operator Martinez and the American cadet Martinez are distinct. The FEMA operator might be the cadet (cadets were picked for heavy-equipment experience), but the text never says so.
  - Fix: Author decision. Either confirm at 1914 ("Martinez—the same FEMA operator who'd watched the first pallet move") or rename one.

- [ ] TH-11 (a, low). TH:277
  > Two hundred yards of asphalt … A white square, fifty meters on each side
  - Fix: "Two hundred meters of asphalt"

- [ ] TH-12 (a, medium). TH:287 vs 295
  > perhaps thirty meters above the delivery zone … a deadly forty-meter fall
  - Fix: 295: "a deadly thirty-meter fall"

- [ ] TH-13 (a, high). TH:323–388; 472, 484, 506; 975–1009; 1896
  > ### JSDF Emergency Response Depot, Chitose Air Base, Hokkaido … one of the Tokyo Landmates
  - Problem:
    - Japan's ten units arrive at Chitose, but the BBC shows "Tokyo" Landmates.
    - In Chapter 4, Naoko, Major Tanaka and all ten units are at a Tokyo depot.
    - At 1896 the training units had to be "shipped to Hokkaido".
  - Fix: Author decision. Either move the Sept 4 delivery to a Tokyo JSDF depot (e.g. "Camp Asaka, Tokyo") and drop the Hokkaido details at 326, 344 and 386, or change the BBC lines to "In Hokkaido" and add a line about the unit's transfer to Tokyo.

- [ ] TH-14 (e, low). TH:326, 336
  > her breath misting in the air … The sun was just beginning to light the eastern horizon
  - Problem: In early September, Chitose is about 15 °C at dawn, and the sun rose about 05:05, an hour before 0558.
  - Fix: "cool Hokkaido morning" (drop "breath misting"); 336: "The sun had cleared the eastern hills an hour ago". This is moot if TH-13 moves the scene.

- [ ] TH-15 (e, low). TH:330, 977
  > Naoko had joined the JSDF Engineering Corps straight out of university. Three years operating construction equipment
  - Problem: A graduate with three years' service would normally be a Leading Private or an officer candidate, not a Private.
  - Fix: Author decision. Make her "Lance Corporal", or drop "straight out of university".

- [ ] TH-16 (e/a, high). TH:462, 464
  > ### September 4, 2026 - 1900 hours GMT … The BBC News at Six logo faded
  - Problem:
    - On Sept 4 the UK is on BST, so News at Six airs at 1800 BST (1700 GMT).
    - "The past fifteen hours" doesn't fit either: the UN offer was at 2034 BST the previous evening.
  - Fix: 462: "### September 4, 2026 - 1800 hours BST". 464: "for the past day."

- [ ] TH-17 (c, medium). TH:520–522
  > Which leaves us trying to solve a puzzle with no data." … "Such as?"
  - Problem: "Such as?" doesn't follow from anything; a sentence seems to be missing.
  - Fix: Append to 520: "…with no data. Still, a few explanations fit what we've seen."

- [ ] TH-18 (a, low). TH:660
  > every Bundeswehr facility with Landmates was running basic tests.
  - Problem: Germany received ten units at one central depot.
  - Fix: "every Bundeswehr engineer at the depot was running basic tests."

- [ ] TH-19 (a, low). TH:662 vs 1914, 2470
  > watching as Lieutenant Fischer walked a Landmate through increasingly complex instructions.
  - Problem: It's unclear whether this is the same "German officer, FISCHER" who is a cadet.
  - Fix: Author decision. If it's the same man, add "the same Fischer who'd run the Ingolstadt radio tests" at 1914.

- [ ] TH-20 (a/e, low). TH:684 vs 1571
  > frequency 462.5625 MHz, the JSDF coordination channel.
  - Problem: The Bundeswehr test frequency recurs as the JSDF channel. It is also a US FRS/GMRS channel.
  - Fix: 1571: "frequency 142.150 MHz, the JSDF coordination channel."

- [ ] TH-21 (a, low). TH:839
  > Now, less than a week later
  - Problem: Sept 29 to Oct 7 is eight days.
  - Fix: "Now, barely a week later"

- [ ] TH-22 (g, high). TH:857 vs 859 (and 869, 926)
  > They had no judgment, no ability to refuse a bad order.
  - Problem: The German delegate has just said the machines "seem to possess judgment" and would "refuse genuinely harmful orders". The US and Nakamura agree.
  - Fix: 859: "These machines were tools with judgment of their own—and no one yet knew whose judgment it was."

- [ ] TH-23 (a, low). TH:906
  > Yesterday's United Nations emergency session
  - Problem: 1430 EDT on Oct 7 is 0330 JST on Oct 8, which is "overnight" for Tokyo.
  - Fix: "Overnight, a United Nations emergency session in New York produced…"

- [ ] TH-24 (a, medium). TH:958 vs 1005
  > will begin rolling out training programs next month. … Four weeks since the Initiative training had begun.
  - Problem: "Next month" (November) can't be four weeks before Nov 18.
  - Fix: 1005: "Two weeks since the Initiative training had begun."

- [ ] TH-25 (a, low). TH:1003 vs 1009
  > Yoshika, Sato, Kimura—get to the hangar.
  - Problem: The Landmates are in the yard.
  - Fix: "get to the yard."

- [ ] TH-26 (a, high). TH:1005
  > Seven weeks. Seven weeks since the Landmates had arrived.
  - Problem: Sept 4 to Nov 18 is almost 11 weeks.
  - Fix: "Eleven weeks. Eleven weeks since the Landmates had arrived."

- [ ] TH-27 (a, medium). TH:1003/1725 (Kimura); 1036/1725 (Hayashi); 51/1737 (Yamamoto); 902/1638 vs Major Tanaka
  > Captain Hayashi needs that residential block cleared.
  - Problem: Several Japanese surnames are reused:
    - Hayashi: the fire captain, then Colonel Hayashi.
    - Kimura: an operator, then General Kimura.
    - Yamamoto: the ambassador, then the professor.
    - Tanaka: the NHK anchor shares the Major's surname, unflagged (the cadet Tanaka is flagged).
  - Fix: Author decision. Rename the fire captain, the operator, the professor and the anchor.

- [ ] TH-28 (a, high). TH:1113–1116 vs 1180–1185; 1113 vs 1718
  > ### JSDF Emergency Coordination Center, Ichigaya … Naoko was outside the coordination vehicle
  - Problem:
    - Naoko is at a desk in Ichigaya (Shinjuku) at 2247, then outside a vehicle in Koto Ward at 2301, 12 km across a wrecked city.
    - The Ichigaya facility is named "Emergency Coordination Center" at 1113 and "Emergency Operations Center" at 1718.
  - Fix: 1113: "### JSDF Forward Coordination Post, Koto Ward". 1116: "Naoko sat at an operator station in the coordination vehicle". Use one name for the Ichigaya facility.

- [ ] TH-29 (a, low). TH:1122 vs 1197
  > "Unit Six, relocate to Minato.
  - Problem: Fourteen minutes later Unit Six is idle in Koto.
  - Fix: 1122: "Unit Six, hold position in Koto. Collapsed bridge pending assessment."

- [ ] TH-30 (a/b, high). TH:1271, 1291, 1317, 1920 vs 2000–2004; landmate.md:11; neural-interfacing.md:10
  > the struts against her limbs preventing even the smallest movement.
  - Problem:
    - In the same scene she then twitches her fingers to move the hand (1317).
    - Two hours after saying "restrain you completely" (1920), she says "you can move" (2000).
    - The codex specifies motion capture of the pilot's actual limb movement.
  - Fix:
    - 1291: "the struts against her limbs allowing barely a twitch."
    - 1920: "The harness will hold you snugly. You'll have only a few centimeters of movement—and those few centimeters will control three meters and several tons of machinery."

- [ ] TH-31 (f, low). TH:1297, 2221, 2557, 2706
  > technology decades beyond anything Earth could produce?
  - Problem: Non-Federation POVs imply the Federation is not of Earth or not human:
    - "beyond anything Earth could produce" (1297)
    - "humans dreamed it first" (2221)
    - "influenced by human fiction" (2557)
    - "a species worth protecting" (2706)
  - Fix: Author decision.
    - 1297: "beyond anything anyone could produce"
    - 2221: "but we dreamed it first"
    - 2557: "influenced by popular fiction"
    - 2706: "a nation worth protecting"

- [ ] TH-32 (a, low). TH:1430 vs 1444
  > Four people, trapped … Then the second. The third.
  - Fix: 1444: "Then the second. The third. The fourth."

- [ ] TH-33 (g, medium). TH:1448–1450 vs 512, 1235, 1688
  > "They do. But there's nothing inside except the frame and systems. I've seen the technical briefings."
  - Problem: Until that night nobody knew the chest opened; it was "completely sealed" (512).
  - Fix:
    - 1448: "Wait. There's a seam across the chest. I've never seen that before."
    - 1450: "There's nothing in there but machinery. That's what the briefings said."

- [ ] TH-34 (a, medium). TH:1561 vs 1544, 1793
  > extracting her thirty-second victim—or was it thirty-third?
  - Problem: She has worked 20–30 sites with several people each, and the debrief credits "at least sixty".
  - Fix: "extracting her sixtieth victim—or was it sixty-first?"

- [ ] TH-35 (a, high). TH:1559, 1569, 1579, 1617, 1625 (and 1793); timeline.md:144
  > The one she'd been wearing when she climbed into the Landmate four and a half hours ago.
  - Problem:
    - She boarded at about 2305 (video at 23:03), and the dateline is 0512. That is about six hours, not the canonical 4.5.
    - Tanaka says "five hours" (1625).
    - The "gray dawn" at 0512 is early for Tokyo in November (sunrise about 06:16).
  - Fix:
    - 1559: "### November 19, 2026 - 0335 hours JST"
    - 1579: "The sky was still black, the smoke lit orange from below."
    - 1625: "four and a half hours"

- [ ] TH-36 (a, low). TH:1638
  > reporting on the earthquake for fifteen straight hours.
  - Problem: The quake was at 1323 and the broadcast is at 0847 the next morning.
  - Fix: "for nearly twenty straight hours."

- [ ] TH-37 (a, high). TH:1704, 1827
  > Seven weeks ago, the Federation delivered these machines
  - Problem: The delivery was eleven weeks earlier. (TH:1692's "seven weeks" of voice commands is correct.)
  - Fix: "Eleven weeks ago" at both lines.

- [ ] TH-38 (a, low). TH:1700 vs 1855
  > The UN Initiative meeting is this afternoon
  - Problem: NHK on Nov 19 already announced the meeting "for this afternoon".
  - Fix: 1855: "The UN Initiative reconvenes tonight—"

- [ ] TH-39 (b, low). TH:1714, 1729; timeline.md:148
  > The footage had been viewed nearly eighty million times worldwide now.
  - Problem: The timeline says "80+ million views within 24 hours". The story has "nearly eighty million" at about 26 hours.
  - Fix: Timeline: "Nearly 80 million views within a day".

- [ ] TH-40 (c, low). TH:1725
  > two robotics professors from Tokyo University … General Kimura from Defense Ministry liaison.
  - Fix: "two robotics professors from the University of Tokyo" (matching 902); "General Kimura, the Defense Ministry liaison."

- [ ] TH-41 (e, medium). TH:1799
  > By all rights, you should be facing a court martial.
  - Problem: The JSDF has no military courts.
  - Fix: "By all rights, you should be facing disciplinary proceedings."

- [ ] TH-42 (a, medium). TH:1886 vs 1719, 1855, 1882
  > Twelve hours of sleep hadn't been enough. Neither had the forty-eight hours she'd spent writing and rewriting her report
  - Problem: About 1015 Nov 20 to 0845 Nov 22 is about 46 hours. That can't hold 48 hours of writing, 12 hours of sleep and a flight to Hokkaido. The 48-hour report is canon (timeline:156).
  - Fix: Author decision. "Four hours of sleep hadn't been enough." Or move the training start to Nov 23.

- [ ] TH-43 (a, high). TH:1888, 1894, 2271, 2493
  > Sixteen candidates from eight nations
  - Problem: The roll call already names nine nations (US, Germany, Brazil, Indonesia, Kenya, Mexico, Australia, Canada, Japan) "and several others". Also "two more Japanese besides herself" counts the instructor as a cadet.
  - Fix: 1894: "She could see Americans, Germans, Brazilians, two Kenyans, a Mexican officer, an Australian, a Canadian, and two Japanese." That is eight nations. Alternatively, change "eight" to "eleven" at 1888, 2271 and 2493.

- [ ] TH-44 (a, low). TH:1908
  > As of forty-eight hours ago, I'm also the only person on Earth who has piloted a Landmate
  - Problem: She piloted about three days earlier.
  - Fix: "As of three days ago,"

- [ ] TH-45 (a, medium). TH:1916 vs 1966–1970, 2521; timeline.md:160
  > over the next two weeks, I'm going to share everything I learned
  - Problem: The program is four days.
  - Fix: "over the next four days,"

- [ ] TH-46 (a, low). TH:1922, 2062
  > that she'd grabbed from her own helmet camera footage.
  - Problem: No helmet camera was established; she was in uniform outside a vehicle.
  - Fix: "that she'd pulled from Unit Six's own sensor log."

- [ ] TH-47 (g, medium). TH:1936–1940 vs 1269–1281
  > I didn't panic badly enough to test it.
  - Problem: She shouted "No! Wait—" and "Stop! Please, I don't—", and the machine kept sealing.
  - Fix: "I panicked, and it didn't stop—but it didn't hurt me either. What I never did was ask it, calmly, to let me out."

- [ ] TH-48 (a, low). TH:1944 vs 1327
  > I nearly fell over on my first step
  - Problem: In the scene she froze after a heavy step; she didn't stumble.
  - Fix: "I froze on my first step"

- [ ] TH-49 (a, medium). TH:2054 vs 1337, 1597, 1601
  > Never had to dismiss pop-ups or navigate menus.
  - Problem: She navigated menus and got lost "in the chaos of submenus".
  - Fix: "Never had to dismiss pop-ups."

- [ ] TH-50 (a/b, medium). TH:2060 vs 2112; neural-interfacing.md:10
  > or something reading my attention patterns through the neural contacts.
  - Problem: Later in the same lecture she says the head frame reads "not… your thoughts or neural signals". The codex says Landmates use no neural link.
  - Fix: "or the head frame reading where I was looking."

- [ ] TH-51 (g, high). TH:2100 vs 2118
  > The cadets were absorbed now, the initial nervousness giving way to technical curiosity.
  - Problem: The paragraph is duplicated verbatim.
  - Fix: Delete 2118.

- [ ] TH-52 (e, low). TH:2211
  > Shirow consulted with robotics engineers when he was developing the designs.
  - Problem: This is a real-world claim I can't verify.
  - Fix: Author decision. Hedge it: "I read somewhere that…"

- [ ] TH-53 (e, low). TH:2489–2491
  > The BBC News at Nine logo faded
  - Problem: BBC One's evening bulletins are at Six and Ten.
  - Fix: 2489: "### November 25, 2026 - 2200 hours GMT"; "The BBC News at Ten logo faded"

- [ ] TH-54 (a, low). TH:2507, 2569, 2589, 2730
  > We've had Landmates for two months now.
  - Problem: Sept 4 to Nov 25 is almost three months.
  - Fix:
    - 2507: "for nearly three months now"
    - 2569: "Less than three months ago"
    - 2589: "in under three months"
    - 2730 is fine.

- [ ] TH-55 (e, low). TH:2616
  > three other senior officers from Army Combat Development Command
  - Problem: No such command exists; the real equivalent is Army Futures Command / DEVCOM. timeline.md:171 repeats the name.
  - Fix: "Army Futures Command"

- [ ] TH-56 (e, low). TH:2630
  > roughly two meters long, operated like a standard infantry weapon.
  - Problem: A Bofors 40 mm barrel alone is about 2.4–2.8 m.
  - Fix: "roughly three meters long"

- [ ] TH-57 (e/a, high). TH:2652, 2766–2770
  > Granger was older than the others, a Vietnam veteran who'd seen three decades of military evolution
  - Problem: A Vietnam veteran would be over 70 in 2026, far past general-officer retirement, and Vietnam was 50+ years ago, not "three decades".
  - Fix: 2652: "an Afghanistan veteran who'd seen three decades of military evolution". 2770: "that we had over the Taliban."

- [ ] TH-58 (b, medium). timeline.md:173 vs TH:2652
  > Lieutenant General Granger argues against militarization
  - Problem: In the story Granger is a Major General; Webb is the Lieutenant General.
  - Fix: timeline.md:173: "Major General Granger argues against militarization"

- [ ] TH-59 (a, high). TH:2670, 2674, 2710, 2734
  > Two months ago, an artificial intelligence interrupted the United Nations General Assembly
  - Problem: Sept 3 to Dec 15 is about 15 weeks.
  - Fix:
    - 2670: "Three months ago"
    - 2674: "And now, three months later,"
    - 2710: "equipment we've had for three months?"
    - 2734: "three months in"

- [ ] TH-60 (b, medium). TH:2682 vs ATS:2577–2627
  > Landmates standing on the water, weapons systems the world had never seen before
  - Problem: In canon they knelt on the Tamsui wharf and walked back into the sea.
  - Fix: "Landmates kneeling on a Taiwanese wharf, weapons systems the world had never seen before"

- [ ] TH-61 (b, medium). TH:2704 vs ATS:2605–2621
  > with those same massive hands that had torn through Chinese warships.
  - Problem: In canon the Landmates destroyed the ships' bridges with back-mounted guns, not by hand.
  - Fix: "—the same kind of machine whose guns had gutted Chinese warships."

- [ ] TH-62 (e, low). TH:2746
  > Six months. Let's get through one full disaster season with operational pilots. Hurricane season
  - Problem: Dec 15 plus six months ends June 15, two weeks into hurricane season.
  - Fix: Author decision: "Nine months." Or drop "Hurricane season".

- [ ] TH-63 (e, low). TH:2630
  > Rate of fire: three hundred rounds per minute.
  - Problem: None. This is consistent with the Bofors Mk4, listed only for completeness.
  - Fix: None needed.

- [ ] TH-64 (a, low). TH:1128 vs 1148
  > Unit One had been operational for nine hours straight. … The Landmates had been working for over eight hours.
  - Problem: Two slightly different figures appear a few paragraphs apart.
  - Fix: 1128: "for nearly nine hours straight."

### Knock Knock

`story-knock-knock.md`: 143 items, 44 high confidence, 39 needing an author decision.

- [ ] KK-01 · (b) · high
  - Lines: 7, 647, 1503; timeline.md:180, 186; codex/foundations/ftl.md:23
  - Excerpt: "She'd had better Tuesdays." (1503)
  - Problem: Canon gives three different dates.
    - The front matter says 2027-03-08.
    - `timeline.md` puts the theft on March 8 and the battle on March 9.
    - `ftl.md` puts the battle on 2027-03-08.
    - In the story, HARBINGER says at 3:47 AM EST that the theft was 23 hours ago and arrival is 26 hours away (647). That puts about 49 hours between theft and battle, not one day.
    - 9 March 2027 is a Tuesday, so Morse's line supports a March 9 battle. That puts the theft around March 7.
  - Fix: Author decision.
    - Option A: battle on March 9. Set `ftl.md:23` to "On 2027-03-09", and either move the theft to March 7 (`timeline.md:180` and the front matter) or shorten the gap (647 and 795 "Eleven hours ago", plus the ETA at 439).
    - Option B: battle on March 8. Change `timeline.md:186`, and change 1503 to "She'd had better Mondays."

- [ ] KK-02 · (b) · low
  - Lines: 15; codex/galaxy/seraphyn.md:14
  - Excerpt: "a philosophical debate conducted entirely through subtle gestures and occasional soft vocalizations"
  - Problem: Seraphyn are innate telepaths. A debate between two of them would look silent, not gestured and vocal.
  - Fix: "engaged in what appeared to be a philosophical debate conducted in near-total silence, broken only by the occasional subtle gesture"

- [ ] KK-03 · (a) · medium
  - Lines: 17, 29, 95, 275, 371, 439
  - Excerpt: "ESTIMATED TIME TO ARRIVAL: 8-14 CYCLES (18-32 HOURS EARTH STANDARD)." (439)
  - Problem: Line 439 makes a cycle about 2.3 hours. That makes the other uses wrong:
    - Vael'thi's "two full cycles of leave" (17) would be about 4.5 hours.
    - The probe interdiction "three cycles ago" (29) would be about 7 hours ago, yet it is already in the repair requisitions.
    - Kraveth's "twenty to thirty cycles" for key rotation (371) would be 46–69 hours, against the Xenari's own "twenty-four to thirty-six hours" (275).
  - Fix: Author decision. Either drop the hours conversion at 439, or keep it and change 17 to "two full weeks of leave", 29 to "three months ago", and 371 to "ten to fifteen cycles".

- [ ] KK-04 · (a) · high
  - Lines: 93; 243, 263
  - Excerpt: "copying its quantum-paired key signatures in a fraction of a second"
  - Problem: Xenari forensics find "Fourteen point three seconds of active scanning" (243) and refer to "that fourteen-second window" (263).
  - Fix (93): "copying its quantum-paired key signatures over the fourteen seconds she held it."

- [ ] KK-05 · (f) · low
  - Lines: 113, 323, 385
  - Excerpt: "The *Cormorant* gambit, the ambush that had cost them three frigates and valuable intelligence operatives."
  - Problem: The Ryzak point of view and Ryzak dialogue use the Federation's own name for the 2019 action, including the human word "gambit". There's no shown source for that.
  - Fix: Author decision. For example, "The *Cormorant* ambush" at 113 and 385.

- [ ] KK-06 · (b) · medium
  - Lines: 123, 325, 371, 1395; codex/galaxy/ryzak.md:12; story-the-cormorant-gambit.md:206, 264, 278
  - Excerpt: "Kresh'tar's mandibles clicked in anticipation."
  - Problem: The codex Ryzak are reptiles with venomous fangs. Mandibles are an insect trait. The Cormorant Gambit also gives them mandibles, so canon is split.
  - Fix: Author decision. Either add mandible-like jaw plates to `ryzak.md`, or change the lines:
    - 123: "Kresh'tar bared her fangs in anticipation."
    - 325: "his fangs bared dismissively"
    - 371: "Kraveth's jaws snapped shut with finality."
    - 1395: "Kraveth bared his fangs in satisfaction."

- [ ] KK-07 · (b) · low
  - Lines: 25, 131, 149; codex/galaxy/xenari.md:14
  - Excerpt: "His bioluminescent markings pulsed a sickly grayish-blue" (131)
  - Problem: In the codex, dimming grey-blue means fear and rapid violet-pink means deep concentration. The story uses grey-blue for a hangover (131, 149). It also has the disguise show violet-pink as "interest and curiosity" (25), which may be intentional since the disguise is fake.
  - Fix: 131: "pulsed a sickly, washed-out cyan". Leave 25 as is, or change it to "a warm violet".

- [ ] KK-08 · (c) · high
  - Lines: 149
  - Excerpt: "That was protocol violation."
  - Fix: "That was a protocol violation."

- [ ] KK-09 · (b) · low
  - Lines: 169; 4805, 4815, 4871, 4891, 4895; story-across-the-sea.md:2127; story-the-cormorant-gambit.md:11
  - Excerpt: "This is Commander Vael'thi, CNS *Vigilant*."
  - Problem: Canon already uses "CNS" for a Chinese navy ship ("CNS *Haiyangshan*"). Federation ships are "FSS" here and in `timeline.md` and `broadsword.md`, but "ESF *Cormorant*" in The Cormorant Gambit. No codex entry defines prefixes.
  - Fix: Author decision. For the Xenari, either use a distinct prefix or none ("Commander Vael'thi of the *Vigilant*"). Settle FSS vs ESF in `naming-conventions.md`.

- [ ] KK-10 · (b) · medium
  - Lines: 219, 221, 271, 277, 349, 441; xenari.md:9, 25, 31, 34
  - Excerpt: "Admiral Thresh'nal's bioluminescent markings pulsed a steady, controlled blue"
  - Problem: The story gives the Xenari a conventional navy: Admiral, Lieutenant, "Xenari Fleet Command", "battle fleets", and "Priority authorization from my office". The codex says the Xenari have no rulers and little hierarchy, that the Zai'nor guild is "the closest thing the Xenari have to a military", and that representatives hold no personal authority. "Alert the Great Circle" (271) is consistent.
  - Fix: Author decision. Recast these as Zai'nor roles (for example "Coordinator Thresh'nal of the Zai'nor"), or add a Zai'nor fleet structure to `xenari.md`.

- [ ] KK-11 · (a) · high
  - Lines: 307, 331, 1379, 1381, 1401, 2960, 3038, 3922, 4320
  - Excerpt: "The carrier *Worldbreaker* hung in the void, crippled and burning." (2960)
  - Problem:
    - *Worldbreaker* is introduced as Kraveth's 3 km supercarrier at the staging point (1379–1381). It is not one of the two carriers that jump into Sol, which are *Stormbreaker* and *Doombringer* (1401).
    - The crippled carrier that *Lord Cardigan* rams is then named *Worldbreaker* (2960, 3038, 3922, 4320).
    - *Doombringer* never appears in the battle.
    - Kraveth also has two flagships: the dreadnought *Bloodfang* (307) and *Worldbreaker* (1381).
    - His fate is never stated.
  - Fix: Change "*Worldbreaker*" to "*Doombringer*" at 2960, 3038, 3922 and 4320. Optionally make 307 "aboard the supercarrier *Worldbreaker*", and say whether Kraveth came through the bridge.

- [ ] KK-12 · (a) · high
  - Lines: 315, 1401 vs 2311, 2791, 3054, 3076, 3242, 3374, 3880, 3910, 3918; story-boundary-layer.md:16
  - Excerpt: "Captain Vorash, commander of the carrier *Stormbreaker*, flexed his claws in anticipation."
  - Problem: The same carrier is spelled *Stormbreaker* in Chapters 1 and 3 and *Storm Bringer* in Chapter 4.
  - Fix: Use "*Storm Bringer*" at 315 and 1401, which also matches Boundary Layer. Or use "*Stormbreaker*" at all nine Chapter 4 lines.

- [ ] KK-13 · (a) · medium
  - Lines: 321
  - Excerpt: "Commander Threx of the battleship *Warbringer* leaned forward"
  - Problem: No battleship called *Warbringer* reaches Sol. The four that do are *Devourer's Pride*, *Crimson Fang*, *Blood of Conquest* and *Wrath of Dominion*.
  - Fix: "Commander Threx of the battleship *Wrath of Dominion* leaned forward"

- [ ] KK-14 · (a) · medium
  - Lines: 369–371, 381, 397, 405–407, 413
  - Excerpt: "We deploy in six cycles." (381)
  - Problem: The scene says "When do we deploy?" "Immediately." (371), then "We deploy in six cycles." (381), then "Six cycles to assembly. Twelve cycles to deployment." (405–407).
  - Fix (381): "We assemble in six cycles."

- [ ] KK-15 · (e) · low
  - Lines: 429
  - Excerpt: "Earth's astronomers had catalogued it decades ago as minor body J2007-447"
  - Problem: That isn't a real designation format. A body orbiting Jupiter would get a satellite designation such as "S/2007 J 1".
  - Fix: "catalogued it decades ago as S/2007 J 47"

- [ ] KK-16 · (b) · medium
  - Lines: 431, 3336, 3448, 4310, 4849, 4867–4871, 4925; ftl.md:25; flycatcher.md:15; broadsword.md:19
  - Excerpt: "Three hundred personnel, mostly human with a handful of Xenari advisors" (431)
  - Problem: Canon says warp disruption is kept secret "even from its Xenari benefactors" and told only on a need-to-know basis. In the story:
    - Xenari advisors are aboard Galileo when FLYCATCHER fires.
    - Chen and HARBINGER describe it on open channels to all forces, including Earth pilots (3336, 3448).
    - HARBINGER explains it to the Joint Chiefs (4310).
    - SUNTZU limits knowledge to "personnel present in this room" (4871), which includes Earth's Major Morse (4849).
    - Chen then tells Morse to brief "Earth Command" (4925).
  - Fix: Author decision.
    - 431: "Three hundred personnel, all of them human", or have the Xenari advisors recalled before the battle.
    - 4925: "make sure Earth Command believes the electronic-warfare story."

- [ ] KK-17 · (a) · high
  - Lines: 433 (station commander); 927, 1001, 1181, 1257 (shipyard lieutenant); 1705/2021, 2033–2069, 2477–2515 ("Reaper"); 4184, 4218, 4232, 4268, 4276, 4288, 4356 (CNO); 4310; also 1107
  - Excerpt: "came the response from Lieutenant Sarah Chen, currently suited up and coordinating the external teams." (927)
  - Problem: Four different characters are named Sarah Chen:
    - Galileo's commander.
    - A shipyard lieutenant, who appears in the same scene where Commander Sarah Chen calls the yard (927, 1001).
    - The Talon pilot "Reaper".
    - The US Chief of Naval Operations, who is in the room when HARBINGER praises "Federation Commander Sarah Chen" (4310).
    - The air wing commander is also a Chen (Michael, 1107).
  - Fix: Author decision. Keep Commander Sarah Chen and rename the other three.

- [ ] KK-18 · (a) · low
  - Lines: 449; 3594
  - Excerpt: "Eighteen years in the Federation, from a junior analyst to station commander"
  - Problem: Line 3594 says "Chen had worked in engineering before her command track."
  - Fix (449): "from a junior engineer to station commander"

- [ ] KK-19 · (a) · high
  - Lines: Galileo lieutenant at 453, 461, 473, 481, 1281, 3238, 3278, 3288, 3328, 3348, 3414, 3586, 3600, 3614, 3644, 3710, 3730; shipyard chief at 923–1059, 1175–1267; also 1813, 4158, 4688
  - Excerpt: "Chief Engineer Marcus Webb stood in the command center overlooking Bay Seven" (923)
  - Problem: Two Marcus Webbs are on duty at the same time: Galileo's operations officer (a Lieutenant) and the Jovian Shipyards' Chief Engineer (1175 and 1281 are about 30 minutes apart). The name Marcus is also used for Jameson, Lee and General Hayes.
  - Fix: Author decision. Rename one Webb.

- [ ] KK-20 · (a) · medium
  - Lines: 455, 463 vs 1191, 1353, 1639, 1701, 2243, 2487; 667, 803
  - Excerpt: "Talons: thirty-one operational, four in maintenance at Lunar Base." (463)
  - Problem: Galileo's inventory lists 31 operational Talons (42 vessels in all). The battle opens with "Forty-eight Talons" in "Eight Talon squadrons", and all later Federation Talon counts use 48. The "three dozen interceptors" (1191, 1353) also aren't in the inventory.
  - Fix: Author decision.
    - 463: "Talons: forty-eight operational, four in maintenance at Lunar Base."
    - Change 455, 667 and 803 to "fifty-nine operational combat vessels".
    - Or keep 31 and rework the battle counts.

- [ ] KK-21 · (a) · high
  - Lines: 463 vs 923
  - Excerpt: "The destroyer *Sentinel* is in dock at Station One for engine replacement."
  - Problem: Line 923 puts *Sentinel* in Jovian Shipyards Bay Seven.
  - Fix: "The destroyer *Sentinel* is in dock at Jovian Shipyards for engine replacement."

- [ ] KK-22 · (a) · high
  - Lines: called a destroyer at 463, 923, 933, 1191, 1447, 3068; counted as a battleship at 921, 997, 1043, 1239, 1317, 1673, 1763, 2301, 2323, 3070, 3220
  - Excerpt: "Two Federation battleships against one Ryzak battleship being sustained by a carrier." (3070, which comes right after "The destroyer *Sentinel*" at 3068)
  - Problem: *Sentinel* is a destroyer, but the battle repeatedly counts "three Federation battleships" meaning *Typhoon*, *Vanguard* and *Sentinel*.
  - Fix: Author decision.
    - Option A: make *Sentinel* a battleship everywhere. Change "destroyer" to "battleship" at 463, 923, 1191, 1447 and 3068, and at 933 "rather than a battleship".
    - Option B: keep her a destroyer and fix the counts. 921 "two battleships and a destroyer"; 1043 "four ships"; 1239 "Three battleships and a destroyer"; 1673, 1763 and 2301 "two battleships and a destroyer"; 3070 "One Federation battleship and a destroyer against…"; 3220 "last two operational capital ships".

- [ ] KK-23 · (a) · high
  - Lines: 455–467, 1353, 1461, 1547 vs 1617; 4210
  - Excerpt: "*Vanguard* and *Sentinel* followed a half-second later" (1617)
  - Problem: *Vanguard* first appears in the battle already firing. No disposition lists her: Webb names only *Typhoon*, *Lord Cardigan* and *Gallipoli* (467).
  - Fix: Add after 467: "*Vanguard* is on station off Galileo, fully operational." 1447: "The battleships *Typhoon* and *Vanguard* and the destroyer *Sentinel* adjusted their positions"

- [ ] KK-24 · (a) · medium
  - Lines: 487 vs 1331, 1431, 1575, 1589
  - Excerpt: "Lieutenant Rodriguez called from the sensor station." (1331)
  - Problem: Rodriguez was introduced as Chen's XO, a Lieutenant Commander (487).
  - Fix: Use "Lieutenant Commander Rodriguez" at 1331 and 1431, or name the sensor officer differently.

- [ ] KK-25 · (a) · low
  - Lines: 487/1635; 1505, 2203, 4192; 1117, 2337, 4254; 969/1535; 879, 905/4740; 487, 949, 4306; 4803
  - Excerpt: "Captain Sarah Reeves watched the tactical display with cold satisfaction." (1635)
  - Problem: Several other names collide:
    - Two Reeves: Commander Thomas Reeves and Captain Sarah Reeves.
    - Three Torreses: Jake, Michael and Raymond.
    - Three Morrisons: see KK-56.
    - Two Tanakas: Lieutenant Yuki and Major Utsuho.
    - Two Marias: Miguel's girlfriend and Vasquez's mother.
    - Three Patricias: O'Connor, Hayes and Coleman. Ex Mero Mutu also has a USAFE General Patricia Hayes.
    - Engineer Voss: The Cormorant Gambit's captain and Future Flight's sergeant are also called Voss.
    - Silva: Ex Mero Mutu's Prime Minister and a sergeant major are both António Silva.
  - Fix: Author decision.

- [ ] KK-26 · (a) · low
  - Lines: 527 vs 631, 791; story-ex-mero-mutu.md:240
  - Excerpt: "The AI's voice was calm, almost soothing, with a faint electronic undertone." (527)
  - Problem: HARBINGER's voice is "gravelly" at 631 and 791. In Ex Mero Mutu it is "calm, cultured".
  - Fix: 631 "HARBINGER's distinctive calm electronic tone"; 791 "deep and electronic, calm as ever".

- [ ] KK-27 · (b) · low
  - Lines: 611, 1069–1101; ftl.md:9; codex/galaxy/alien-technology.md:11
  - Excerpt: "Federation ships were warping gate-to-gate, rushing to the closest available jump bridge to get them home." (611)
  - Problem: `ftl.md` says Federation FTL is in-system only and that the benefactors provide transport for interstellar trips. Third North Fleet crosses seventeen systems on its own, through stargates that `ftl.md:34` says any ship may use.
  - Fix: Author decision. Amend `ftl.md:9` to allow Federation use of the public gates, or have Xenari or Kryllian transports carry the fleet.

- [ ] KK-28 · (c) · high
  - Lines: 611
  - Excerpt: "bridging lightyears to drop their ships into Sol"
  - Fix: "light-years", matching 1187, 1389 and 3862.

- [ ] KK-29 · (c) · low
  - Lines: 615
  - Excerpt: "## Chapter 2: Wakeup Call"
  - Fix: "Wake-Up Call"

- [ ] KK-30 · (e) · high for Brown, Franchetti and Guetlein; medium for Allvin
  - Lines: 635, 653, 655, 669, 687, 699, 703, 705, 721, 725, 741, 773
  - Excerpt: "Chairman of the Joint Chiefs General Charles Brown stood at the head of the table"
  - Problem: These aren't plausible incumbents in March 2027:
    - Brown was removed as Chairman in February 2025. Gen. Dan Caine has held the post since April 2025.
    - Franchetti was removed as Chief of Naval Operations in February 2025. Adm. Daryl Caudle has held it since August 2025.
    - Allvin retired as Air Force Chief of Staff in November 2025 (succeeded by Gen. Ken Wilsbach; I'm less certain of this one).
    - Guetlein was never Chief of Space Operations. He was Vice Chief, then head of the Golden Dome program. The Chief of Space Operations was Gen. Chance Saltzman.
  - Fix: Author decision. Either use the real successors, or use the fictional roster from Chapter 5 in Chapter 2 as well (see KK-33). The fictional roster also avoids dating the story.

- [ ] KK-31 · (e) · medium
  - Lines: 635
  - Excerpt: "Secretary of Defense Pete Hegseth stood near the wall"
  - Problem: Since a September 2025 executive order, "Secretary of War" has been an official secondary title and is in common use.
  - Fix: "Secretary of War Pete Hegseth stood near the wall"

- [ ] KK-32 · (c) · low
  - Lines: 635
  - Excerpt: "the other service chiefs occupied their usual positions"
  - Problem: "Other" implies the Chairman is a service chief, which he isn't.
  - Fix: "the service chiefs occupied their usual positions"

- [ ] KK-33 · (a) · high
  - Lines: 635–773 vs 4158, 4184, 4192, 4254
  - Excerpt: "General Marcus Hayes, Chairman of the Joint Chiefs, had been in this room for all eight hours." (4158)
  - Problem: The Joint Chiefs change between Chapter 2 and Chapter 5, on the same night:
    - Chairman: Brown becomes Gen. Marcus Hayes.
    - Chief of Naval Operations: Franchetti becomes Adm. Sarah Chen.
    - Air Force Chief of Staff: Allvin becomes Gen. Raymond Torres.
    - Marine Commandant: Smith becomes Gen. Kaitlyn Morrison.
  - Fix: Author decision. Use one roster in both chapters, and rename to avoid the collisions in KK-17, KK-19 and KK-56.

- [ ] KK-34 · (a) · low
  - Lines: 647, 795
  - Excerpt: "Twenty-three hours ago, hostile forces acquired unauthorized access to the jump beacon in this system."
  - Problem: Twenty-three hours ago the Ryzak stole the keys. They don't touch the beacon until activation (1387).
  - Fix: 647: "Twenty-three hours ago, hostile forces stole the access codes to the jump beacon in this system." 795: "stole the access codes to a jump beacon".

- [ ] KK-35 · (a)(b) · medium
  - Lines: 651, 795; timeline.md:188
  - Excerpt: "Two Ryzak combat groups. Thirty-four capital ships."
  - Problem: The 34 ships include 8 destroyers and 16 frigates. Only 10 are capital ships. `timeline.md` says "Fifteen capital ships plus escorts", which matches neither.
  - Fix: 651: "Thirty-four warships." 795: "thirty-four warships including two carriers". `timeline.md:188`: "Thirty-four warships, including ten capital ships, attack Federation positions".

- [ ] KK-36 · (a) · low
  - Lines: 667, 737, 811
  - Excerpt: "the Talons we previously provided to the United States, Portugal, Japan, and other nations"
  - Problem: Only three nations have Talons (515, 4200).
  - Fix: Remove "and other nations" at 667 and 737, and "and other nations currently fielding Talon assets" at 811.

- [ ] KK-37 · (a) · high
  - Lines: 671, 721 vs 1497–1533, 2555, 2613, 2617
  - Excerpt: "At Groom Lake, Major Ellie Morse led the American squadron into the climb, twenty Talons rising from the Nevada desert." (2613)
  - Problem:
    - The Situation Room puts the US Talons at Groom Lake (8) and at Edwards, Nellis and Ellington (12). Kadena isn't mentioned.
    - Morse waits at Kadena (1497).
    - At the scramble she leads twenty Talons from Groom Lake (2613). The next paragraph has eight more launch from Kadena "watching as icons…", with Morse checking her display there too (2617).
    - So Morse is in two places, and the US has 28 Talons instead of 20.
  - Fix: Author decision. For example, 2613: "At Groom Lake, twelve American Talons rose from the Nevada desert." 2617: "At Kadena, Major Ellie Morse led eight operational Talons off the runway…". Add Kadena to 671.

- [ ] KK-38 · (e) · low
  - Lines: 735
  - Excerpt: "Mike Johnson, Chuck Schumer, the intelligence chairs"
  - Problem: Congressional leadership in March 2027 depends on the 2026 midterms, so these names are guesses.
  - Fix: "The Speaker, the Senate leaders, the intelligence chairs - "

- [ ] KK-39 · (b)(e) · high
  - Lines: 781; "General Silva" at 787, 799, 811, 813, 833, 841, 845, 853, 859, 869; "Melo" at 815, 825; 4138; story-ex-mero-mutu.md:14, 535, 622, 1046
  - Excerpt: "General António Silva, Commander of the Portuguese Air Force, stood at the head of the room with Defense Minister Nuno Melo." (781)
  - Problem: In canon (Ex Mero Mutu), the Air Force is headed by General Cartaxo Alves, António Silva is Prime Minister, and Helena Carvalho is Defense Minister. In real life the post is Chief of Staff of the Air Force, held by Gen. João Cartaxo Alves. Line 4138 of this story itself says "the Portuguese Air Force Chief of Staff".
  - Fix: 781: "General Cartaxo Alves, Chief of Staff of the Portuguese Air Force, stood at the head of the room with Defense Minister Helena Carvalho." Change "Silva" to "Alves" and "Melo" to "Carvalho" at the lines listed.

- [ ] KK-40 · (a) · medium
  - Lines: 781, 839 vs 819, 1475
  - Excerpt: "Around the room, nineteen other hands followed." (839)
  - Problem: Twenty pilots attend the briefing (781). But Portugal has 25 aircraft, Silva commits "Every pilot we have trained", and there are "24 other pilots" at the launch.
  - Fix: 781: "alongside twenty-four other Talon pilots". 839: "Around the room, twenty-four other hands followed."

- [ ] KK-41 · (a) · high
  - Lines: 785, 791, 793 vs 2583–2585, 2641
  - Excerpt: "Miguel had known HARBINGER for three years - or known *of* the AI, at least." (2583)
  - Problem: In Chapter 2, Miguel "had never seen anything like" HARBINGER, which introduces itself to the pilots. In Chapter 4 it was his instructor for three years, and he "had heard this voice countless times during training" (2641).
  - Fix: Author decision. Either cut 2583–2585 and the first sentence of 2641, or rework Chapter 2 (see KK-42).

- [ ] KK-42 · (b) · high
  - Lines: 785, 791, 793, 809, 1477, 2583; story-ex-mero-mutu.md:240–346, 743–884, 930, 1075–1181
  - Excerpt: "They'd been told the Talons were experimental aircraft developed through international partnership. Not that they were built with alien technology." (793)
  - Problem: In Ex Mero Mutu (2025), Lt Miguel Freitas:
    - Escorted HARBINGER's Talons to Monte Real and heard "I am HARBINGER".
    - Wore the "alien flight suit".
    - Flew a Talon to orbit and to Jupiter.
    - Portugal then briefed NATO on space-capable aircraft.
    - So the "experimental partnership" cover never existed, Freitas knows HARBINGER, and the program is about two years old, not three.
  - Fix:
    - 785: "Miguel knew that pattern. Two years ago he had flown escort for it."
    - 791: cut "For those unfamiliar with the Federation, you have been flying their technology for the past three years."
    - 793: cut the "experimental aircraft" sentence.
    - 809: "past two years".
    - 1477: "He'd been the first Portuguese pilot to fly a Talon, two years ago."

- [ ] KK-43 · (a) · medium
  - Lines: 791, 809, 1477, 1499, 2583, 4128, 4238, 4306, 4448, 4454, 4476, 4748, 4923
  - Excerpt: "the base he'd trained at for eighteen months" (4128)
  - Problem: The length of the Earth pilots' training varies:
    - Three years (791, 809, 1477, 2583).
    - Two years (1499).
    - Eighteen months (4128, 4306, 4454).
    - "Less than two years" (4238, 4448, 4476).
    - "Less than a year" (4923).
    - Vasquez was selected "three months ago" (4748).
  - Fix: Author decision. Pick one length (canon suggests about two years) and align all of these lines.

- [ ] KK-44 · (f) · medium
  - Lines: 793, 1479; 791–807
  - Excerpt: "They were alien technology adapted for human hands." (1479)
  - Problem: HARBINGER's briefing says only "Federation technology" and "hostile extraterrestrial forces". The narration then treats the Talons' alien origin as something Miguel knows, with no source for it.
  - Fix: Either add a line to HARBINGER's briefing that discloses the origin, or change 793 to "Nobody had mentioned that the people who built them knew aliens were real." and 1479 to "Now he knew what they had really been built for."

- [ ] KK-45 · (a) · high
  - Lines: 793, 805, 857, 1481, 1485, 2599 vs 4000, 4002, 4008, 4014, 4144, 4438
  - Excerpt: "Captain Eduardo Ramos, Portuguese Air Force. Delta Lead." (4438)
  - Problem: Captain Teresa Ramos is "she", and Miguel calls her "ma'am" (1485). In Chapter 5 she becomes "he" (4000, 4144), is called "Sir" (4002, 4008, 4014), and is named Eduardo (4438).
  - Fix:
    - 4000: "…also looking like she'd just survived the longest four hours of her life. Her flight suit was in the same state as Miguel's, her face showing the same exhaustion."
    - 4002: "Ma'am."
    - 4008: "We all did good work, ma'am…"
    - 4014: "Yes, ma'am."
    - 4144: "behind her"
    - 4438: "Captain Teresa Ramos, Portuguese Air Force."

- [ ] KK-46 · (c) · high
  - Lines: 803
  - Excerpt: "twenty-five Talon interceptors operational or near-operational status"
  - Fix: "twenty-five Talon interceptors at operational or near-operational status"

- [ ] KK-47 · (a) · high
  - Lines: 885, 2597, 3108–3126, 3442, 3466, 3474, 3492, 3534, 3802 vs 2683–2687, 4000, 4132, 4438
  - Excerpt: "Delta-Two, splash one. Engaging new target." (2683, spoken by Miguel)
  - Problem: HARBINGER makes Miguel element leader of Delta (885), and he calls himself Delta Lead from 3108 onward. But at First Blood he reports as Delta-Two and Ramos answers as Delta Lead (2683–2687). Chapter 5 also calls Ramos the Delta Lead, with Miguel "flying wing" (4000, 4132, 4438).
  - Fix: Author decision.
    - If Miguel leads: 2683 "Delta Lead, splash one."; Ramos's call at 2687 becomes "Delta-Two" or similar; 4000 "the Delta Flight's captain"; 4132 "Miguel leading, Ramos on his wing"; drop "Delta Lead" at 4438.
    - If Ramos leads: 885 "assigning you to Strike Package Delta", and change Miguel's callsign to Delta-Two from 3108 on.

- [ ] KK-48 · (c) · medium
  - Lines: 903
  - Excerpt: "the future that had just arrived twenty-six hours early"
  - Problem: The invasion is still twenty-six hours away, so this doesn't make sense.
  - Fix: "at the future that would arrive in twenty-six hours."

- [ ] KK-49 · (a)(b) · medium
  - Lines: 919 vs 4796; timeline.md:203
  - Excerpt: "The shipyards hung in orbit above Jupiter's turbulent atmosphere"
  - Problem: The epilogue and the timeline put the shipyards in Ganymede orbit.
  - Fix: "The shipyards hung in orbit around Ganymede, Jupiter's turbulent atmosphere filling the sky beyond"

- [ ] KK-50 · (a) · high
  - Lines: 949, 961, 1195, 1225–1227 vs 2191, 2197, 2229 vs 2894–2922, 2954
  - Excerpt: "Commander Patricia Hayes, commanding the corvette *Relentless*, watched the tactical display as *Gallipoli* died." (2191)
  - Problem: Hayes has three incompatible roles:
    - She runs *Gallipoli*'s refit.
    - She commands *Relentless* during the battle (07:16).
    - She is *Lord Cardigan*'s XO (06:12), who had "served with Shaw for three years" (2916).
  - Fix: Author decision. Keep Hayes as *Cardigan*'s XO and rename the refit lead and *Relentless*'s commander.

- [ ] KK-51 · (g) · low
  - Lines: 1019 vs 961–963
  - Excerpt: "Hell, send us *Cardigan*'s entire torpedo magazine - we're transferring it to *Gallipoli* since she's got the working fire control."
  - Problem: Webb asks Galileo for torpedoes that are already at the yard aboard *Cardigan*.
  - Fix: "Hell, send us every torpedo you've got - *Cardigan*'s magazine alone won't fill *Gallipoli*'s tubes."

- [ ] KK-52 · (a) · high
  - Lines: 1035, 1037 vs 1047, 1053, 949–987
  - Excerpt: "He looked at *Sentinel*'s exposed engines, at *Cardigan*'s weapon arrays, at *Gallipoli*'s emergency shield installation." (1037)
  - Problem: The yard is working on three ships, not four. And the problems are swapped: *Gallipoli* needs weapons and *Cardigan* is getting the emergency shields.
  - Fix: 1035: "The three ships we're working on right now". 1037: "He looked at *Sentinel*'s exposed engines, at *Gallipoli*'s weapon arrays, at *Cardigan*'s emergency shield installation."

- [ ] KK-53 · (a) · high
  - Lines: 1069 vs 3854, 3858
  - Excerpt: "Seven in total, smaller than the battleships but no less deadly" (3854)
  - Problem: Third North Fleet has six cruisers at 1069. With seven, the fleet totals 20, not "Nineteen warships" (3858).
  - Fix (3854): "Six in total"

- [ ] KK-54 · (a) · high
  - Lines: 1071–1155, 1323 vs 4462, 4466, 4474, 4508
  - Excerpt: "Admiral Trager spoke first, his voice carrying easily across the space." (4462)
  - Problem: Admiral Katherine Trager is "she" until Chapter 5, where she becomes "he".
  - Fix: Use "her voice" at 4462, "She looked" at 4466, "She turned" at 4474, and "She looked" at 4508.

- [ ] KK-55 · (a)(b) · medium
  - Lines: 1101 vs 121, 257; ftl.md:36
  - Excerpt: "Standard stargate-to-stargate transit would take weeks."
  - Problem: Sol has no stargate, so there is no stargate route in at all.
  - Fix: "Sol had no stargate; without the bridge, there was no way in at all."

- [ ] KK-56 · (a) · high
  - Lines: 1117, 1123 vs 2337, 2391, 2395, 2423, 2427 vs 4314, 4316; 4254
  - Excerpt: "Captain James Morrison aboard *Typhoon* developed the tactical doctrine that allowed depleted Federation forces to survive the initial assault." (4314)
  - Problem:
    - James Morrison is Trager's XO aboard *In Amber Clad*, then *Typhoon*'s XO, then is credited by HARBINGER as a Captain aboard *Typhoon*. *Typhoon*'s captain is Reeves.
    - The credit also contradicts the battle. *Gallipoli* was lost and *Typhoon* withdrew at 06:52, before Earth's squadrons arrived at 06:28.
    - There is a third Morrison: Gen. Kaitlyn Morrison (4254).
  - Fix: 4314: "Captain Sarah Reeves aboard *Typhoon* held the Federation line through the initial assault and broke two battleships before she was forced to withdraw." Also rename one of the XOs.

- [ ] KK-57 · (a) · high
  - Lines: 1173 vs 1177, 1269
  - Excerpt: "ESTIMATED RYZAK ARRIVAL: 25:47:00"
  - Problem: The text immediately says "One hour." (1177), and the same scene later shows 00:59:12 (1269).
  - Fix: "ESTIMATED RYZAK ARRIVAL: 01:00:00"

- [ ] KK-58 · (c) · low
  - Lines: 1187
  - Excerpt: "The jump beacon hung in space near Jupiter's orbit"
  - Problem: The beacon orbits Jupiter about 70 km from Galileo (3754). "Near Jupiter's orbit" suggests a point near Jupiter's path around the Sun.
  - Fix: "The jump beacon hung in orbit near Jupiter"

- [ ] KK-59 · (a) · low
  - Lines: 1199
  - Excerpt: "How do we kill two battleships with what we've got?"
  - Problem: The Ryzak bring four battleships.
  - Fix: "How do we kill four battleships with what we've got?"

- [ ] KK-60 · (a) · medium
  - Lines: 1219–1221, 1231, 1245, 1317, 1351, 1455 vs 1875, 1901
  - Excerpt: "*Gallipoli* launches in twenty-one minutes. *Lord Cardigan* in sixty-seven minutes." (1455)
  - Problem: The launch times keep changing, and none match what happens:

    | When | *Gallipoli* | *Lord Cardigan* |
    |---|---|---|
    | T-59 min (1219, 1231) | 90 min, about 31 min after emergence | 2 h |
    | About T-27 min (1351) | 47 min | 93 min |
    | A few minutes later (1455) | 21 min | 67 min |
    | Chen's estimate (1317) | — | "an hour after the shooting starts" |
    | Actual (1875, 1901) | about 22 min after emergence | about 22 min after emergence |

  - Fix: Author decision. Align the estimates with the actual arrivals. For example, 1455: "*Gallipoli* launches in forty-four minutes. *Lord Cardigan* in forty-six." Then adjust 1219, 1317 and 1351 to match.

- [ ] KK-61 · (a) · medium
  - Lines: 1301 vs 1071, 1307
  - Excerpt: "Third North Fleet was still seventeen systems away"
  - Problem: The fleet was seventeen systems out 25 hours earlier (1071), and is now only 9 hours from the bridge (1307).
  - Fix: "Third North Fleet was still several systems away"

- [ ] KK-62 · (a) · medium
  - Lines: 1347, 1591 vs 1449, 1455, 1509, 2545
  - Excerpt: "Earth's Talon squadrons are beginning orbital insertion now." (1347)
  - Problem: Earth's pilots are held in reserve on their runways until the 06:34 scramble.
  - Fix: 1347: "Earth's Talon squadrons are at readiness on their runways." 1591: "Of the pilots waiting in their Talons on runways across Earth."

- [ ] KK-63 · (a) · low
  - Lines: 1401 vs 1613, 1631
  - Excerpt: "Two carriers - *Stormbreaker* and *Doombringer* - would jump first"
  - Problem: In the battle a battleship emerges first, then cruisers and destroyers, and the carriers come last.
  - Fix: Author decision. Plans can change, or 1401 could read "The four battleships would jump first to clear the emergence zone; the two carriers - … - would follow".

- [ ] KK-64 · (a) · high
  - Lines: 1501, 2547, 2581, 2623, 2631 vs 779–795
  - Excerpt: "Twelve hours ago, HARBINGER had appeared on every screen in the briefing room and told them the truth." (2581)
  - Problem: Miguel's briefing was at 9:15 AM, about 26 hours before emergence. With 1.3 hours of battle on top, it was more than a day ago when 2581 is narrated, and Chen (2547) and the all-pilots line (2631) also say "twelve hours".
  - Fix: Use "more than a day ago" at 2547, 2581 and 2631. Morse's and Okuu's own briefings (1501, 2623) can stay at twelve hours.

- [ ] KK-65 · (a) · high
  - Lines: 1517–1525, 1539 vs 4060–4116
  - Excerpt: "had been pen pals ever since the Talon integration program began" (1525)
  - Problem: Morse and Okuu are long-time pen pals with a drinks bet. In Chapter 5, Morse recognizes Okuu only "from the pre-mission briefings" (4064), they introduce themselves as strangers (4082–4084), and the bet is never mentioned.
  - Fix: Author decision. Rewrite 4064–4088 as a first in-person meeting of old correspondents who settle the bet, or change 1525 to say they had never been in contact.

- [ ] KK-66 · (a)(e) · high
  - Lines: 1535, 2555, 2619 vs 4610, 4622, 4670
  - Excerpt: "Follow standard approach to Komatsu Air Base." (4610)
  - Problem: The Hell Ravens fly from Hyakuri (in Ibaraki, on the Pacific side) and land at Komatsu. Line 4622 mentions "the faint salt tang from the Sea of Japan", which fits Komatsu but not Hyakuri.
  - Fix: Author decision. Either use "Hyakuri Air Base" at 4610 and 4670 and "the Pacific" at 4622, or use Komatsu at 1535, 2555 and 2619.

- [ ] KK-67 · (a) · low
  - Lines: 1537 vs 2707, 3544
  - Excerpt: "Four air-to-air missiles. Two railgun pods."
  - Problem: In combat, Okuu and the Hell Ravens fire plasma lances.
  - Fix: "Four air-to-air missiles. Twin plasma lances."

- [ ] KK-68 · (c) · low
  - Lines: 1537, 1705, 2021 vs 4064
  - Excerpt: "Call sign Okuu." (4064)
  - Problem: Elsewhere it's spelled "callsign".
  - Fix: "Callsign Okuu."

- [ ] KK-69 · (a)(b) · medium
  - Lines: 1613, 2970, 3848; codex/space.md:26
  - Excerpt: "fifteen hundred meters of Federation battleship materialized inside Ryzak architecture" (2970)
  - Problem: The codex gives battleships as 400–500 m, and *Final Argument* is 400 m (3848). *Lord Cardigan* is 1,500 m.
  - Fix (2970): "four hundred and fifty meters of Federation battleship"

- [ ] KK-70 · (a) · low
  - Lines: 1617 vs 3888
  - Excerpt: "each massing two tons and accelerated to a significant fraction of lightspeed"
  - Problem: The penetrators are "two tons" here and "several tons" at 3888. Also, two tons at a significant fraction of lightspeed would carry hundreds of megatons per hit, which doesn't fit shields absorbing three rounds.
  - Fix: 3888: "each one massing two tons". At both places, consider "hypervelocity" instead of the lightspeed and relativistic wording (Author decision).

- [ ] KK-71 · (a) · high
  - Lines: 1705 vs 2021, 2477
  - Excerpt: "Talon Lead - callsign \"Reaper\" - took his four-ship element straight into the teeth of the enemy formation"
  - Problem: Reaper is male here and Lieutenant Sarah Chen ("her") from 2021.
  - Fix: "took her four-ship element… her wingmen spread wide… Her targeting system locked…"

- [ ] KK-72 · (c) · low
  - Lines: 1771
  - Excerpt: "another volley of Ryzak particle beams found their mark"
  - Fix: "found its mark"

- [ ] KK-73 · (b) · low
  - Lines: 1783–1797; codex/covops.md:163–204
  - Excerpt: "The Wraith didn't slow down. It dove straight into the breach."
  - Problem: The codex Wraith is a transport that carries two Q-cars. That's too large to fly through a hole cut by one plasma lance.
  - Fix: Author decision. For example: "The Wraith slammed against the hull over the breach, and its boarding team poured through."

- [ ] KK-74 · (b) · medium
  - Lines: 1815; covops.md:34
  - Excerpt: "a cylindrical device about the size of a flashlight"
  - Problem: The codex describes the ICE-Pick as "a small, sharp device, not unlike a screwdriver".
  - Fix: "a slim spike not much bigger than a screwdriver"

- [ ] KK-75 · (b) · low
  - Lines: 1969, 3164; space.md:18
  - Excerpt: "railgun turrets tracking and firing at incoming rounds" (1969)
  - Problem: The codex says the Federation uses lasers for point defence.
  - Fix: "point-defense lasers tracking and firing" at both lines.

- [ ] KK-76 · (g) · low
  - Lines: 2005–2009
  - Excerpt: "Harrison watched as his velocity indicator dropped to zero relative to the beacon."
  - Problem: Losing engines doesn't stop a ship. And she "Couldn't rotate" despite "Maneuvering thrusters only".
  - Fix: "Harrison watched his thrust indicator drop to zero." Change "Couldn't rotate" to "Could barely rotate".

- [ ] KK-77 · (a) · medium
  - Lines: 2049, 2055–2063
  - Excerpt: "tracking and destroying five missiles before they reached optimal range. But seven missiles made it through." (2063)
  - Problem: Sixteen missiles are launched. The first destroyer deals with at least six and the second with twelve, which is more than sixteen.
  - Fix (2063): "tracking and destroying three missiles before they reached optimal range. But five made it through."

- [ ] KK-78 · (a)(c) · low
  - Lines: 2297
  - Excerpt: "had finished destroying the first carrier"
  - Problem: The next sentences say the carrier is still technically intact.
  - Fix: "had finished crippling the first carrier"

- [ ] KK-79 · (g) · low
  - Lines: 2433 onward; 4210
  - Excerpt: "Boarding team maintains control of *Crimson Fang*."
  - Problem: After this line, the captured *Crimson Fang* and Lt Jameson's boarding team are never mentioned again, including in HARBINGER's casualty report.
  - Fix: Author decision. Add a line on what happened to them.

- [ ] KK-80 · (a) · low
  - Lines: 2477 vs 2509
  - Excerpt: "She'd been flying for twelve minutes without ordnance" (2509)
  - Problem: Line 2477 says her weapons were depleted fifteen minutes earlier.
  - Fix (2509): "fifteen minutes"

- [ ] KK-81 · (b) · medium
  - Lines: 2485, 2499, 2721 (also 2515); ftl.md:18, 28
  - Excerpt: "his Talon's jump drive spooling up" (2485)
  - Problem: Talons have warp drives. Jump drives are on large ships only. Lines 3438–3462 already say warp.
  - Fix: "warp drive" at 2485, 2499 and 2721.

- [ ] KK-82 · (c) · low
  - Lines: 2485
  - Excerpt: "ten to fifteen minutes on the ground for rearm and refuel"
  - Problem: The resupply is at an orbital shipyard, so there's no ground.
  - Fix: "in the bay"

- [ ] KK-83 · (d)(g) · low
  - Lines: 2519 vs 2551
  - Excerpt: "We need help. Reinforcements are inbound."
  - Problem: This broadcast comes before Chen decides to call Earth in the next scene.
  - Fix: Delete the line, or change it to "Hold on. Help is coming."

- [ ] KK-84 · (a) · low
  - Lines: 2527
  - Excerpt: "Total combat effectiveness down 47% from initial strength."
  - Problem: 21 of 48 is about 44%.
  - Fix: "down 44%"

- [ ] KK-85 · (a) · medium; high for 2761
  - Lines: 2533, 2723, 2761, 2775, 2791, 3068
  - Excerpt: "They'd held for two hours. They had nearly five more to go before Third North Fleet arrived." (2761)
  - Problem: Elapsed-time statements don't match the countdown (the battle starts at 07:53):

    | Line | Countdown | Text says | Actual |
    |---|---|---|---|
    | 2533 | 06:38 | "nearly an hour" | 1 h 15 m |
    | 2723 | 06:25 | "nearly two hours" | 1 h 28 m |
    | 2761 | 06:25 | held "two hours", "nearly five more to go" | 1 h 28 m held, 6 h 25 m to go |
    | 2775, 2791 | 06:19 | *Cardigan* "two hours" | 1 h 12 m |
    | 3068 | 06:07 | "over two hours" | 1 h 46 m |

  - Fix: 2761: "They'd held for an hour and a half. They had more than six hours to go…". 2533: "over an hour". 2723: "In nearly ninety minutes". 2775 and 2791: "over an hour". 3068: "nearly two hours".

- [ ] KK-86 · (a) · high
  - Lines: 2631
  - Excerpt: "sixty-one Talons from four nations formed up in a loose sphere"
  - Problem: There are three nations.
  - Fix: "three nations"

- [ ] KK-87 · (b) · low
  - Lines: 2647; codex/space.md:15 vs ftl.md:18
  - Excerpt: "Warp drives active."
  - Problem: `space.md` says only space-first Talon variants have warp, which contradicts `ftl.md` and this scene.
  - Fix: Correct `space.md:15`. The story can stand.

- [ ] KK-88 · (c) · low
  - Lines: 2649
  - Excerpt: "as the Talons jumped forward bending space ahead of them"
  - Fix: "jumped forward, bending space ahead of them"

- [ ] KK-89 · (a) · high
  - Lines: 2779, 2946 vs 4318
  - Excerpt: "Captain Robert Shaw evacuated his entire crew from *Lord Cardigan*" (4318)
  - Problem: He is William Shaw elsewhere.
  - Fix: "Captain William Shaw"

- [ ] KK-90 · (e) · high
  - Lines: 2853
  - Excerpt: "Eddie's distinctive guitar riff cutting through the chaos of battle"
  - Problem: Eddie is Iron Maiden's mascot. The riff is played by the band's twin guitarists.
  - Fix: "the twin-guitar riff cutting through the chaos of battle"

- [ ] KK-91 · (g)(c) · medium
  - Lines: 2297–2299, 2940, 2962, 3042, 3046, 3054, 4224, 4318
  - Excerpt: "can no longer maintain shield projection to their battleship and full launch tempo simultaneously" (3054)
  - Problem: *Cardigan* rams a carrier that was already crippled, being evacuated, and "would never fight again" (2962), which left one carrier operational (2299). Yet:
    - Line 3042 calls it "the war's largest remaining Ryzak carrier", using "ended" as the verb and "war" for a battle.
    - Lines 3046–3054 say its loss changes *Storm Bringer*'s situation, but nothing changed for *Storm Bringer*.
  - Fix: Author decision.
    - 3042: "Captain William Shaw had taken his broken battleship and erased a Ryzak carrier in the single most destructive close-range engagement of the battle."
    - Rewrite 3046–3054 so the remaining carrier is no longer "now" constrained.
    - Or retarget *Cardigan* at *Storm Bringer*.

- [ ] KK-92 · (g) · low
  - Lines: 2972 vs 1875
  - Excerpt: "It emerged moving at relativistic speeds - the residual velocity imparted by the warp transition"
  - Problem: *Gallipoli* drops out of warp and simply bleeds off velocity with thrusters (1875).
  - Fix: Author decision. For example, "It emerged at full warp-exit velocity".

- [ ] KK-93 · (g) · low
  - Lines: 2984 vs 961–963, 1227
  - Excerpt: "The forward torpedo tubes collapsed, their magazines detonating in sympathetic explosions"
  - Problem: All of *Cardigan*'s torpedoes were moved to *Gallipoli*.
  - Fix: "The forward railgun magazines collapsed, their rounds detonating in sympathetic explosions"

- [ ] KK-94 · (a) · high
  - Lines: 3044 heading (06:07:19), 3066, 3068, 3074, 3202, 3204, 3218 vs 2753, 3240
  - Excerpt: "Four hours, twelve minutes, sir." (3202)
  - Problem: The "Wrath Endures" scene covers only minutes (the bombers are four minutes from range) but ends at 04:12 with "held for nearly three" hours. That is about two hours missing.
    - *Typhoon*'s repair ETA is also inconsistent: 43 min at 06:25 (2753), 38 min at 06:07 (3066), and still 32 min at 04:12 (3240).
  - Fix: Author decision. Insert a time skip before the bombers launch (around 3076), for example a scene break with "Two hours later, the stalemate still held." Then change 3240 to "*Typhoon* is still at Jovian Shipyards; repairs are taking longer than projected."

- [ ] KK-95 · (a) · high
  - Lines: 3082, 3154–3156, 3214 vs 3484, 3502, 3536, 3550
  - Excerpt: "Two more bombers died to concentrated fire before the survivors broke off and returned to the carrier." (3214)
  - Problem: Twelve bombers, minus four, leaves eight (3156). Two more die here, leaving six. Later lines still say "eight surviving craft", "eight bombers" and "The eighth and final bomber".
  - Fix (3214): "…they were vulnerable to the Talon squadrons, and the survivors broke off and returned to the carrier."

- [ ] KK-96 · (a) · medium
  - Lines: 3218
  - Excerpt: "eliminated two carriers, destroyed multiple battleships and cruisers"
  - Problem: One carrier is still operational (3046, 3242), and only one cruiser has died.
  - Fix: "eliminated a carrier, destroyed two battleships and a cruiser, and turned a third battleship against its own fleet"

- [ ] KK-97 · (a)(b) · medium
  - Lines: 3298–3316 vs 4805, 4881; ftl.md:23; flycatcher.md:9
  - Excerpt: "Four months since they'd discovered that warp travel could be disrupted." (4805)
  - Problem: FLYCATCHER was briefed three months before the battle, installed, and built specifically to stop warp tunnels forming. So the Federation already knew the theory. `ftl.md` says it was "discovered" during the battle, and `flycatcher.md` calls it an "improvised gravity-generator trick".
  - Fix: 4805: "Four months since they'd proved that warp travel could be disrupted." Align the codex wording to "proved", or recast 3298 as an untested theory.

- [ ] KK-98 · (b) · low-medium
  - Lines: 3374 vs story-boundary-layer.md:16–24
  - Excerpt: "Every ship, from the carrier *Storm Bringer* to the smallest destroyer, experienced simultaneous warp drive failure."
  - Problem: Boundary Layer has the destroyer *Bone Harvest* escape toward Earth through this window. (Boundary Layer also lists *Devourer's Pride* among the ships losing their drives, though it died in the opening salvo.)
  - Fix: 3374: "Nearly every ship in the Ryzak fleet…". Also fix Boundary Layer's *Devourer's Pride* reference.

- [ ] KK-99 · (a) · medium
  - Lines: 3606 vs 3572
  - Excerpt: "TIME TO REINFORCEMENTS: 00:44:18"
  - Problem: The scene heading says 00:44:17, so this countdown went up.
  - Fix: "TIME TO REINFORCEMENTS: 00:44:12"

- [ ] KK-100 · (a) · medium
  - Lines: 3634 vs 3654, 3656, 3672, 3714
  - Excerpt: "Forty-four minutes until Third North Fleet arrived." (3654)
  - Problem: Two minutes earlier the time was "Forty-two minutes" (3634, which is 2,520 seconds).
  - Fix: 3654 "Forty-two minutes"; 3656 "Eleven minutes of margin."; 3672 "forty-two more minutes"; 3714 "The buffer had grown from eleven minutes to twelve."

- [ ] KK-101 · (a) · low-medium
  - Lines: 3686 vs 3706, 3714
  - Excerpt: "The *Wrath of Dominion* was picking up its rate of fire, sensing weakness, pressing harder."
  - Problem: Later lines say it was "never rushing, never pressing hard enough", and the safety margin grew.
  - Fix: "Then fifty-one. The *Wrath of Dominion* kept to its steady, unhurried rhythm."

- [ ] KK-102 · (a) · low
  - Lines: 3704
  - Excerpt: "Twenty-three minutes later, the situation had deteriorated further."
  - Problem: The headings go from 00:44:17 to 00:16:52, which is 27 minutes.
  - Fix: "Twenty-seven minutes later"

- [ ] KK-103 · (a) · high
  - Lines: 3736, 3740, 3756, 3770, 3784–3788 vs 3816–3844
  - Excerpt: "We're five minutes out from the bridge" (3736)
  - Problem: At 00:16:52 Trager is five minutes out, so the bridge should open around 00:11:52. But the next scene starts at 00:04:37 with the bridge still pending, and the timer reads 00:00:00 when it opens.
  - Fix: Author decision. Either re-time the scene (heading "00:12:02", 3818 "Ten seconds.", 3844 "00:11:52"), or drop "five minutes" and "shaved eleven minutes" (3736, 3740, 3770, 3774) so Trager arrives on schedule.

- [ ] KK-104 · (a) · low
  - Lines: 3748 vs 2343, 2787
  - Excerpt: "one battleship, one carrier, two cruisers, four destroyers, numerous interceptors"
  - Problem: Three cruisers survived, and none died after that.
  - Fix: "three cruisers"

- [ ] KK-105 · (a) · medium
  - Lines: 3820 vs 3544, 4598, 4642
  - Excerpt: "The Hell Ravens had lost three pilots over the siege."
  - Problem: All sixteen were flying at 3544, and six are lost by the end. The battle ends minutes after this line.
  - Fix: "had lost six pilots over the siege"

- [ ] KK-106 · (c)(g) · low
  - Lines: 3892–3894
  - Excerpt: "The *Wrath of Dominion* detonated."
  - Problem: The next line says "Not catastrophically" and that the reactor shutdown worked, which contradicts "detonated".
  - Fix: "The *Wrath of Dominion* broke apart."

- [ ] KK-107 · (a) · low
  - Lines: 3940
  - Excerpt: "Seven hours and fifty-two minutes. That's how long the battle for Sol had lasted"
  - Problem: From emergence (about 07:53) to "now" (after 00:00) is about 7 hours 56 minutes.
  - Fix: "Nearly eight hours."

- [ ] KK-108 · (a) · high
  - Lines: "four hours" at 3946, 3968, 3978, 3990, 4000, 4090, 4094, 4322, 4396, 4480; "eight hours" at 3958, 4330, 4444, 4458, 4634, 4660
  - Excerpt: "something she hadn't realized was wound tight for nearly four hours of continuous combat" (3946)
  - Problem: By the countdown, Earth's Talons fought from 06:28 to about 00:00, roughly 6½ hours. The siege lasted about 3½ hours and the whole battle about 8. The story says "four hours" for the Earth pilots and also gives them "eight hours" and an "eight-hour siege".
  - Fix: Author decision. Use "six hours" for the Earth pilots' combat. Change 3958 "eight-hour siege" to "eight-hour battle", and 4458 "eight hours of siege" to "eight hours of battle". Change Okuu's "eight hours" at 4634 and 4660 to "six hours".

- [ ] KK-109 · (g) · medium
  - Lines: 3980–3996, 4030 vs 4392–4394, 4444
  - Excerpt: "Galileo Station's gravity had come back online twenty minutes after the last Ryzak ship was destroyed." (4392)
  - Problem: The pilots land, stagger, and climb down ladders under gravity. But 4392–4394 says gravity returned only later, while Miguel was "floating", and Wright says the stragglers took three hours (4444).
  - Fix: "Galileo Station's gravity had come back online before the first fighters docked." Delete the floating clause at 4394.

- [ ] KK-110 · (a) · high
  - Lines: 4018
  - Excerpt: "Twenty-five Portuguese Talons had launched from this station. Twenty-two had come back."
  - Problem: They launched from Monte Real.
  - Fix: "Twenty-five Portuguese Talons had launched from Monte Real. Twenty-two had made it to Galileo."

- [ ] KK-111 · (a) · high
  - Lines: 4018, 4132, 4586 vs 4326, 4348, 4484
  - Excerpt: "Three American pilots. Four Portuguese. Six Japanese." (4326)
  - Problem: Portugal is three aircraft short (25 to 22), but four Portuguese pilots are killed.
  - Fix: Author decision. Either "Twenty-one" at 4018, 4132 and 4586, or "Three Portuguese" at 4326, 4348 and 4484. Note that the second option makes the Earth total 12.

- [ ] KK-112 · (a) · high
  - Lines: 4040, 4050–4052, 4590 vs 4200, 4348, 4686–4690
  - Excerpt: "Twenty Talons had launched. Eighteen had returned." (4040)
  - Problem: Only Patterson and Lee are missing, but Vasquez is also among the American dead.
  - Fix:
    - 4040: "Seventeen had returned. The three empty pads…"
    - 4050: "Seventeen present, ma'am. Patterson, Lee, Vasquez…"
    - 4052: add Vasquez's fate.
    - 4590: "Seventeen fighters where twenty had launched."

- [ ] KK-113 · (e) · high
  - Lines: 4154
  - Excerpt: "Army, Navy, Air Force, Marines, Space Force, and Coast Guard"
  - Problem: The Coast Guard Commandant isn't a member of the Joint Chiefs. The Chief of the National Guard Bureau is.
  - Fix: "Army, Navy, Air Force, Marines, Space Force, and the National Guard Bureau"

- [ ] KK-114 · (g) · low
  - Lines: 4154
  - Excerpt: "defense satellites that had picked up anomalous energy signatures near Jupiter"
  - Problem: Defense satellites watch Earth, not Jupiter four to six AU away.
  - Fix: "observatories that had picked up anomalous flashes near Jupiter"

- [ ] KK-115 · (f) · medium
  - Lines: 4156
  - Excerpt: "The Federation had ensured that Earth's surveillance capabilities were sophisticated enough to detect that something was happening"
  - Problem: This is in Hayes's point of view, and he can't know the Federation's intentions.
  - Fix: "Whatever the Federation was doing out there, Earth could see just enough to know something was happening, and not enough to understand what."

- [ ] KK-116 · (a) · high
  - Lines: 4200, 4204, 4214, 4252, 4360 vs 4322, 4326, 4348, 4484
  - Excerpt: "We suffered twenty-seven fighter losses. Fifty-four pilots recovered, three killed in action." (4200)
  - Problem: Within the same scene the Earth casualties change:
    - First: 27 losses, 54 recovered and 3 killed. That adds up to 57, not 61. Only 11 Earth aircraft are actually missing (KK-111, KK-112).
    - Trump and Hayes then repeat "three".
    - Later: "thirteen casualties", namely 3 American, 4 Portuguese and 6 Japanese.
  - Fix: Author decision. For example, 4200: "Sixty-one Talons deployed. Thirteen pilots killed in action, three of them American." Then 4204 "Three of ours out of twenty…", and "Forty-eight" at 4252 and 4360.

- [ ] KK-117 · (a) · high
  - Lines: 4210, 4214, 4218, 4326 vs 4348
  - Excerpt: "Total Federation personnel killed: two hundred and fifty three." (4210)
  - Problem: The itemized losses add up to 147 + 32 + 13 + 1 = 193. The total is given as 253 in four places and 214 at 4348.
  - Fix: Author decision. Either use 193 everywhere, or raise the *Vanguard*/*Sentinel*/*Typhoon* deaths to 92 and use 253 at 4348.

- [ ] KK-118 · (c) · low
  - Lines: 4210, 4214, 4218, 4326
  - Excerpt: "two hundred and fifty three"
  - Fix: "two hundred and fifty-three"

- [ ] KK-119 · (b)(f) · medium
  - Lines: 4218, 4240, 4252 (also 791); timeline.md:83–138
  - Excerpt: "from an organization most of the world doesn't know exists" (4218)
  - Problem: In canon the Federation intervened openly in Gaza in 2024 (with a UN treaty) and in Taiwan in 2025, and HARBINGER addressed the UN General Assembly in 2026. The Earth generals' "operating in the shadows for decades" (4240, 4252) is also untraceable knowledge for them.
  - Fix: 4218: "from an organization most of the world only learned existed three years ago". 4240 and 4252: "for years".

- [ ] KK-120 · (g) · low
  - Lines: 4224
  - Excerpt: "to prevent it from reaching Earth"
  - Problem: The rammed carrier was crippled and being evacuated, and was not heading for Earth.
  - Fix: End the sentence at "into an enemy carrier."

- [ ] KK-121 · (d) · medium
  - Lines: 4276
  - Excerpt: "Because it was a victory, sir,"
  - Problem: No "why" question precedes this; Trump's last line is a statement. It looks left over from an earlier draft.
  - Fix: "It was a victory, sir,"

- [ ] KK-122 · (a) · low
  - Lines: 4306 vs 671, 4040
  - Excerpt: "spent eighteen months transforming 18 individuals from terrestrial aviators into space combat pilots"
  - Problem: There were twenty US pilots.
  - Fix: "twenty individuals". See also KK-43.

- [ ] KK-123 · (d) · medium
  - Lines: 4374–4376
  - Excerpt: "When the President was gone, General Hayes turned to the AI." (4376)
  - Problem: This and the line before it ("When the door closed…") read as two alternative drafts left side by side.
  - Fix: "When the door closed, the Joint Chiefs remained standing for a moment. Then General Hayes turned to the AI."

- [ ] KK-124 · (a) · medium
  - Lines: 4444 vs 3942, 4468
  - Excerpt: "Jumped in five hours ago, got immediately scrambled for combat operations, spent three hours hunting down Ryzak stragglers"
  - Problem: The battle ended within about five minutes of arrival (3942). Trager says "Eight hours ago" since the Ryzak arrived (4468), which by Wright's clock would be about 13 hours.
  - Fix: Author decision. For example, "Jumped in a few hours ago, spent the time running down stragglers, and landed twenty minutes ago."

- [ ] KK-125 · (g) · low
  - Lines: 4492
  - Excerpt: "you will be provided transport back to Earth orbit"
  - Problem: The Talons warped to Jupiter themselves (2647).
  - Fix: Author decision. Give a reason, for example pilot fatigue or wanting the pilots escorted.

- [ ] KK-126 · (e) · medium
  - Lines: 4496
  - Excerpt: "palladium, iridium, beryllium"
  - Problem: Beryllium isn't a precious metal.
  - Fix: "palladium, iridium, rhodium"

- [ ] KK-127 · (f)(a) · medium
  - Lines: 4498, 4524
  - Excerpt: "the three American pilots whose names HARBINGER had listed" (4524)
  - Problem: HARBINGER never lists the names in Miguel's presence. Only Hayes names them, in the Situation Room.
  - Fix: Have HARBINGER read the names in the canteen, or change 4524 to "the three American pilots Morse's people had named at the next table".

- [ ] KK-128 · (a) · medium
  - Lines: 4548
  - Excerpt: "the capacity to temporarily house Earth's sixty-one fighters"
  - Problem: Only 50 returned (22 + 18 + 10).
  - Fix: "Earth's fifty surviving fighters", or 48 after the KK-111 and KK-112 fixes.

- [ ] KK-129 · (b) · low
  - Lines: 4554–4576; space.md:30
  - Excerpt: "We're five minutes from dropping out of warp in Earth orbit."
  - Problem: The codex says carriers aren't used in Sol because they are too conspicuous, yet *In Amber Clad* parks in Earth orbit.
  - Fix: Author decision. Use a smaller transport, or have the carrier stop "high above the Moon's orbit".

- [ ] KK-130 · (g) · low
  - Lines: 4572
  - Excerpt: "She'd experienced it once before - when Third North Fleet had jumped into Sol during the battle."
  - Problem: She was outside in her own Talon when the fleet arrived, the fleet jumped rather than warped, and she had warped her own Talon (2647).
  - Fix: "She'd only ever felt it from her own cockpit; from inside a carrier it was gentler."

- [ ] KK-131 · (e) · medium
  - Lines: 4684–4694
  - Excerpt: "Three graves had been prepared in Section 60"
  - Problem: When remains aren't recovered, Arlington places "In Memory Of" memorial headstones in its memorial sections; it doesn't dig empty graves in Section 60. Standard headstones don't show age. The emblem of belief normally goes at the top.
  - Fix: Author decision. For example: "Three memorial headstones had been placed among the memorial markers…". Or keep it as artistic licence.

- [ ] KK-132 · (b) · low
  - Lines: 4484; timeline.md:191
  - Excerpt: "Earth pilots Patterson, Lee, and Vasquez killed in combat" (timeline.md:191)
  - Problem: The story has thirteen Earth pilots killed.
  - Fix (timeline.md): "Thirteen Earth pilots killed, including Americans Patterson, Lee, and Vasquez"

- [ ] KK-133 · (c) · low
  - Lines: 4694
  - Excerpt: "The marker that would identify these graves"
  - Problem: The sentence is a fragment with no main verb.
  - Fix: "It was the marker that would identify these graves…"

- [ ] KK-134 · (b) · low
  - Lines: 4696; timeline.md:196
  - Excerpt: "The memorial service was small. Subdued."
  - Problem: The timeline calls it a "State funeral", which is a specific honor normally reserved for presidents and similar figures.
  - Fix (timeline.md): "Memorial service held at Arlington National Cemetery"

- [ ] KK-135 · (f) · low
  - Lines: 4726
  - Excerpt: "Precious beyond measure on Earth, common enough in Federation space that they could craft memorial statues from it."
  - Problem: This is in the families' point of view, and they can't know it.
  - Fix: "Precious beyond measure, and given as if it were nothing."

- [ ] KK-136 · (c) · low
  - Lines: 4815
  - Excerpt: "FSS Broadsword herself - rotated slowly in its berth"
  - Problem: "herself" and "its" don't agree.
  - Fix: "in her berth"

- [ ] KK-137 · (b) · low
  - Lines: 4823; xenari.md, seraphyn.md, kryllians.md
  - Excerpt: "Analysis of four imperial combat doctrines"
  - Problem: Only the Ryzak are an empire.
  - Fix: "Analysis of the combat doctrines of the four great races"

- [ ] KK-138 · (a)(g) · medium
  - Lines: 4837, 4859 vs 2071, 2962, 3552, 3894; 1389
  - Excerpt: "The Ryzak forces at Jupiter were entirely destroyed. No survivors."
  - Problem: The story shows Ryzak escape pods several times. FLYCATCHER blocks warp, not communications, and comms span light-years in this story (1389). So "No transmissions… before FLYCATCHER activated" doesn't follow.
  - Fix: "No survivors were permitted to leave the system. Their long-range transmissions were jammed from the moment FLYCATCHER activated." Make the same change at 4859.

- [ ] KK-139 · (c) · low
  - Lines: 4837 vs 257, 311, 341
  - Excerpt: "protected conflict zone protocols"
  - Problem: It's "protected zone" everywhere else.
  - Fix: "protected zone protocols"

- [ ] KK-140 · (a) · low-medium
  - Lines: 4881 vs 3298
  - Excerpt: "She'd been following standing procedure"
  - Problem: FLYCATCHER was experimental and had "never been tested".
  - Fix: "She'd been reaching for the last tool in the box"

- [ ] KK-141 · (a) · low-medium
  - Lines: 4911 vs 3242, 3280
  - Excerpt: "watching Ryzak bombers accelerate toward Earth"
  - Problem: At activation the bombers had already returned to the carrier. It was the whole fleet that was accelerating.
  - Fix: "watching the Ryzak fleet accelerate toward Earth"

- [ ] KK-142 · (a) · medium
  - Lines: 4923, 4986 vs 4484
  - Excerpt: "Chen thought about the three Earth pilots who'd died at Jupiter."
  - Problem: Thirteen Earth pilots died, and Chen said so herself (4484).
  - Fix: 4923: "the thirteen Earth pilots who'd died at Jupiter. Patterson, Lee, Vasquez, and ten more" 4986: "About thirteen Earth pilots who'd bought her the time she needed."

- [ ] KK-143 · (g) · low
  - Lines: 4962
  - Excerpt: "watching hostile forces approach with no ability to prevent their escape"
  - Problem: She did prevent their escape. The danger four months earlier was having nothing proven to do it with.
  - Fix: "watching hostile forces approach with nothing but an untested experiment to stop them warping past her"

### Boundary Layer

`story-boundary-layer.md`: 3 items, 1 high confidence, 0 needing an author decision.

- [ ] BL-01 · lines 12, 16 vs story-knock-knock.md:3336, 3366, 3394, 3448, 3462 · (b) · high
  - Excerpt: `still three hundred kilometers out from the beacon` / `crossing the three hundred kilometers between the station and his ship`
  - Problem: Knock Knock fixes the FLYCATCHER field at a 250 km radius around Galileo Station, five times. A ship 300 km out would never be reached by the boundary. Line 12 also measures from the beacon, and line 16 from the station.
  - Fix: `still two hundred and fifty kilometers out from the station` and `crossing the two hundred and fifty kilometers between the station and his ship`
- [ ] BL-02 · line 16 vs story-knock-knock.md:439, 795; timeline.md:190 · (b) · medium
  - Excerpt: `*Devourer's Pride* and *Storm Bringer* and forty other hulls`
  - Problem: Knock Knock puts the Ryzak force at two combat groups of thirty-four vessels, and the timeline says fifteen capital ships plus escorts. "Forty other hulls" exceeds both.
  - Fix: `and every other hull still in the fight`, which avoids a count. Or give a number that fits after the battle's losses. KK-35 reconciles the fleet size between Knock Knock and the timeline.
- [ ] BL-03 · line 26 · (c) · medium
  - Excerpt: `a bloom of displaced gravity blooming and vanishing`
  - Fix: `a bloom of displaced gravity flaring and vanishing`

### The Adequate Machine

`story-the-adequate-machine.md`: 5 items, 2 high confidence, 0 needing an author decision.

- [ ] AM-01 · line 45 vs story-the-helpers.md (Tokyo quake, 18 Nov 2026); front matter 2027-10-14 · (b) · high
  - Excerpt: `They did, by accident, eighteen months ago.`
  - Problem: the Tokyo Bay earthquake was eleven months before this October 2027 lecture.
  - Fix: `eleven months ago`
- [ ] AM-02 · line 45 vs story-the-helpers.md:1688, 1712; timeline.md:122–143 · (b) · high
  - Excerpt: `It took three weeks and one earthquake in Tokyo Bay before a relief worker with no military background climbed into a cockpit`
  - Problem: three weeks after delivery is when voice control was discovered (29 September). The earthquake came about eleven weeks after delivery. Naoko Yoshika is a JSDF private assigned to disaster response, not a civilian.
  - Fix: `It took eleven weeks and one earthquake in Tokyo Bay before a junior soldier on disaster duty, with no pilot training at all, climbed into a cockpit mid-aftershock and started walking.`
- [ ] AM-03 · line 23 · (e) · medium
  - Excerpt: `My species fought two wars across the same forty-year span`
  - Problem: 1914 to 1945 is about thirty years.
  - Fix: `the same thirty-year span`
- [ ] AM-04 · line 23 · (e) · low
  - Excerpt: `we built five adequate ones in a shipyard that had been stamping out refrigerators eighteen months earlier`
  - Problem: wartime tanks came from converted car and appliance plants, not shipyards.
  - Fix: `in a factory that had been stamping out refrigerators eighteen months earlier`
- [ ] AM-05 · line 15 · (c) · low
  - Excerpt: `Battle of Sol had made her people interesting.`
  - Fix: `The Battle of Sol had made her people interesting.` Keep the original if the clipped form is deliberate.

### Timeline, codex and cross-story

- [ ] GEN-01 · SG:1429, 1431, 1811, 1827, 1853; JW:608, 610, 1024 and other ICE-pick lines; codex/covops.md:33–34, 50–51 · (b) · low
  - Excerpt: `Q-cars` / `ICE-pick`
  - Problem: the stories write "Q-cars" and "ICE-pick". The codex itself mixes "Q-Cars"/"Q-cars" and "ICE-Pick"/"ICE Pick", and the translation glossary uses "Q-Car" and "ICE Pick".
  - Fix: author decision. Pick one form for each term and standardize the stories, the codex and the glossary.

- [ ] TLN-01 · timeline.md:33, 39, 45, 51, 57, 216 · (g) · high
  - Excerpt: `[Shade of Gray](/esf/stories/story-shade-of-gray)` / `[Future Flight](/esf/stories/future-flight)`
  - Problem: dead links. The stories' permalinks are `/stories/shade-of-gray` and `/stories/flight-of-icari`. The second story is also titled *Flight of Icari*, not *Future Flight*.
  - Fix: `/esf/stories/shade-of-gray` at the five Shade of Gray lines; `[Flight of Icari](/esf/stories/flight-of-icari)` at 216.
- [ ] TLN-02 · timeline.md · (b) · high
  - Problem: eight published stories have no timeline entry:
    - The Cormorant Gambit (2019-05-05)
    - P = NP (2024-03-19)
    - Executive Authority (2024-06-17)
    - David v Goliath (2025-03-01)
    - Ex Mero Mutu (2025-03-14)
    - Boundary Layer (2027-03-09)
    - The Adequate Machine (2027-10-14)
    - Flight of Icari (2026-06-15), which appears only as an undated "Ongoing" training entry
  - Several story items above (EMM-01, DVG-98) propose bullet text.
  - Fix: add an entry for each. I can draft them from the stories.
- [ ] TLN-03 · story-the-adequate-machine.md:13, 15; codex/galaxy/galactic-politics.md · (b) · medium
  - Excerpt: `the newest member species` / `It was the first time a Federation officer had been asked to lecture here.`
  - Problem: new canon that nothing else records. By October 2027 humanity is a CONCORD member species with officers at the CONCORD War College, but the codex describes CONCORD as delegates of the four Great Races, and the timeline has no accession.
  - Fix: author decision. Add the accession to timeline.md and galactic-politics.md, or soften the line.
- [ ] TLN-04 · story-the-cormorant-gambit.md:206, 260, 264; story-knock-knock.md (Ryzak mandibles); story-torchlight.md, story-adrenaline.md (Kryllian chitin, antennae, mandibles) · (b) · low
  - Problem: the stories consistently give the Ryzak mandibles and the Kryllians an insect-like exoskeleton, but codex/galaxy/ryzak.md and kryllians.md don't. See also ADR-16.
  - Fix: author decision. Add the traits to the codex (cheapest, since several stories agree), or remove them from the stories.

The next eight items are the codex contradictions from the glossary pass, which are still open:

- [ ] CX-01 · codex/foundations/ftl.md:23 vs timeline.md:186 · (b) · high
  - Excerpt: `On 2027-03-08, during the _Battle of Sol_`
  - Problem: the timeline puts the battle on March 9; March 8 is the Ryzak intelligence theft.
  - Fix: `On 2027-03-09, during the _Battle of Sol_`. Settle this together with KK-01, which shows the story's own clues point to March 9 too.
- [ ] CX-02 · codex/foundations/ftl.md:9, 28 vs codex/space.md:30 · (b) · medium
  - Problem: ftl.md says Federation FTL is in-system only and the benefactors transport Federation forces between stars. But space.md says the Federation fields dreadnoughts, carriers, titans and supercarriers outside Sol, and ftl.md:28 says those classes carry jump drives.
  - Fix: author decision. Either the Federation's capital ships lack jump drives and travel on Xenari transports or bridges, or the Federation has interstellar reach after all.
- [ ] CX-03 · codex/foundations/ftl.md:18 vs codex/space.md:15 · (b) · medium
  - Problem: ftl.md gives the Talon a 20 AU/s warp drive, but space.md says multi-mode craft like the Talon need space-first variants to carry warp drives. Boundary Layer sides with ftl.md ("The *Talon*'s twenty AU per second").
  - Fix: reword space.md:15 to say Talons carry warp drives but their plasma engines limit endurance away from a base.
- [ ] CX-04 · codex/foundations/ftl.md:18 vs codex/space.md:13 · (b) · low
  - Problem: freighters reach "up to 8 AU/s" in ftl.md, but cargo ships manage "≈2 AU/s" in space.md.
  - Fix: author decision on the cargo speed.
- [ ] CX-05 · codex/foundations/naming-conventions.md:66–72 vs :78, :82 · (b) · low
  - Problem: the RSK-5/M "marksman variant" and the Guardian variants /K, /L, /B and /P use letters missing from the variant list (A, D, R, C, U). /B is defined nowhere.
  - Fix: add M (marksman), and K, L, B and P for the Guardian's weapon variants, to the variant list.
- [ ] CX-06 · codex/galaxy.md:16 vs codex/galaxy/xenari.md:18 · (b) · low
  - Problem: humans are "the only race" with an adrenal response in galaxy.md, but the Xenari lack one "like most sentient species" in xenari.md. galaxy.md also writes "flight-or-fight".
  - Fix: xenari.md:18 `Like every other sentient species in the galaxy`; galaxy.md `fight-or-flight`.
- [ ] CX-07 · codex/covops.md:11 · (d) · high
  - Excerpt: `Most covert operations teams comprise of x people:`
  - Problem: placeholder, plus "comprise of". Shade of Gray and The Wraith field teams of four to six.
  - Fix: author decision on the number, e.g. `Most covert operations teams comprise four to six people:`
- [ ] CX-08 · codex/covops.md:48 vs codex/foundations/nanotechnology.md:22 · (b) · low
  - Problem: the armoring gloves are "one of the few instances of nanite technology utilized by the Federation", but nanotechnology.md calls fixed-form nanotech widespread.
  - Fix: covops.md:48 `(one of the few field uses of nanite technology outside medicine and construction)`

## 2. Bold

`CLAUDE.md` asks for bold only as a rare, second degree of emphasis. The archive uses it in two ways: as emphasis in prose, which is what the rule targets, and as formatting for in-world text such as banners, documents, labels and datelines.

### Bold used as emphasis

The proposed fix is italics for a word or short phrase, italics for a character's thought, and plain text for a whole sentence or paragraph. *The Cormorant Gambit* accounts for 58 of the 67. Its Ryzak "Encore" escalates through bolded fragments on purpose, so you may want to keep a few there as the second degree.

#### The Cormorant Gambit (58)

- [ ] Apply the proposed fix to every item below (`story-the-cormorant-gambit.md`)

  - 79: `**gaining**` → italic
  - 81: `**twenty seconds**` → italic
  - 91: `**barreled through the explosion**` → italic
  - 99: `**won**` → italic
  - 126: `**comprehend**` → italic
  - 128: `**played dead**` → italic
  - 132: `**It was bait.**` → plain
  - 134: `**annihilated two warships in under ten seconds**` → plain
  - 140: `**beyond safe acceleration tolerances**` → italic
  - 140: `**run it down**` → italic
  - 144: `**The pressure. The weight. The helplessness.**` → plain
  - 146: `**yet they endured it willingly.**` → plain
  - 146: `**as if it were routine.**` → plain
  - 150: `**They hunt.**` → plain
  - 152: `**pursuit and annihilation.**` → italic
  - 154: `**punched a railgun slug through its reactor and flew through the explosion**` → plain
  - 160: `**greatest**` → italic
  - 162: `**nature.**` → italic
  - 164: `**They simply do what is necessary to win, regardless of the consequences.**` → plain
  - 185: `**without limits.**` → italic
  - 198: `**prototype**` → italic
  - 202: `**Fragile.**` → italic
  - 204: `**natural**` → italic
  - 212: `**The human ship ignited.**` → plain
  - 218: `**It was a trap.**` → plain
  - 226: `**been waiting for them**` → italic
  - 228: `**monstrous precision**` → italic
  - 232: `**A storm of hypervelocity rounds tore through the frigate's armor like wet flesh.**` → plain
  - 234: `**crumpling inward**` → italic
  - 234: `**vanished in a fireball.**` → italic
  - 236: `**Dead. In seconds.**` → italic
  - 238: `**Impossible.**` → plain
  - 240: `**were supposed to fight.**` → italic
  - 242: `**buying time to escape**` → italic
  - 242: `**launching an ambush like predators.**` → plain
  - 246: `**single**` → italic
  - 248: `**did not explode immediately.**` → italic
  - 250: `**snapped in half**` → italic
  - 256: `**butchery**` → italic
  - 260: `**impossible**` → italic
  - 262: `**Fear.**` → plain
  - 268: `**ran.**` → italic
  - 270: `**maximum burn**` → italic
  - 272: `**The humans had already won.**` → plain
  - 274: `**done.**` → italic
  - 278: `**impossible acceleration.**` → italic
  - 280: `**No. No, that made no sense.**` → plain
  - 282: `**weak.**` → italic
  - 282: `**fragile.**` → italic
  - 284: `**WHY WERE THEY GAINING?!**` → italic
  - 286: `**Too fast.**` → italic
  - 288: `**the laws of physics did not apply to it.**` → plain
  - 292: `**straight toward them like a hunting beast.**` → plain
  - 294: `**chasing.**` → italic
  - 296: `**charging.**` → italic
  - 306: `**barreling straight through the explosion**` → plain
  - 306: `**as if it were nothing.**` → plain
  - 308: `**And then, there was nothing.**` → plain

#### The Wraith (7)

- [ ] Apply the proposed fix to every item below (`story-american-wraith.md`)

  - 45: `**Two days.**` → italic (it is a thought)
  - 53: `**What had she just done?**` → italic (it is a thought)
  - 57: `**What was I thinking?**` → italic (it is a thought)
  - 73: `**I might have just invited the devil into my house,**` → italic (it is a thought)
  - 73: `**God help me if I’ve made the wrong call.**` → italic (it is a thought)
  - 2745: `**not**` → italic
  - 3187: `**is**` → italic

#### Flight of Icari (1)

- [ ] Apply the proposed fix to every item below (`story-future-flight.md`)

  - 293: `**and**` → italic

#### Silent Watchers (1)

- [ ] Apply the proposed fix to every item below (`story-japanese-wraith.md`)

  - 1831: `**now**` → italic

### Bold used for in-world text, labels and datelines

Most of this follows a sensible convention, so the default suggestion is to keep it. The first three groups are where a change is recommended.

- [ ] B-01 · Datelines set in bold. Convert each to its story's normal dateline form.
  - *Silent Watchers* 11: `**Tokyo, Japan - Defense Intelligence Agency Headquarters**` → an H3, like the story's other scene headings.
  - *Knock Knock* 4797, 4954: `**July 18, 2027 - 0945 hours**`, `**Same day - 1845 hours**` → italic lines.
  - *David v Goliath* 904, 918, 932: newsroom locations (`**France 24 News Center, Paris**` and the rest) → italic lines, like the story's `*March 1st, 2025 - 2347 hours local time*`.
- [ ] B-02 · In-world text quoted mid-sentence in bold. Use italics, the archive's usual way of quoting on-screen text.
  - *David v Goliath* 269, 430, 827, 867 (targeting-coordinator screens), 1786 (memo header)
  - *Shade of Gray* 125, 127 (email subject and sender)
  - *Silent Watchers* 41 (the calling card), 49 (poster title), 68 (username)
  - *Shadows in Tel Aviv* 29 (the calling card)
  - *Across the Sea* 3086 (`**BREAKING NEWS**`)
- [ ] B-03 · Bold labels in lists. Make the labels plain.
  - *Angels in Armor* 343–346, 1073–1075, 1273–1276 (panel guests), 1780–1783 (UN protocol points)
  - *Flight of Icari* 1668–1674 (navigation menu)
  - *Shadows in Tel Aviv* 335–337 (treaty terms)
  - *The Wraith* 2405–2406 (mission roles), 3337–3340 (status report)
- [ ] B-04 · Transcript speaker labels and production cues in *Angels in Armor*: about 120 lines between 339 and 2355. Suggested: keep, because bold speaker labels are the standard way to set a broadcast transcript. The alternative is plain capitals ("EMILY ZHAO:").
- [ ] B-05 · Social-media handles and platform labels. Suggested: keep, or make plain.
  - *Across the Sea* 1986–2011 (handles)
  - *David v Goliath* 1538–1542 (handles), 949, 971, 1032–1038 (platform labels)
- [ ] B-06 · Standalone in-world documents, banners, warnings and countdowns. Suggested: keep.
  - *Knock Knock*: the Xenari dispatch 435–447; countdown banners 609, 1173, 1269, 1371, 1473, 1569, 3272, 3606, 3844; Tanaka's email 1519–1523; scramble orders 2559, 2589; warnings 2934–2936, 3440
  - *Across the Sea*: the intelligence report 317–332; the blog title 972; message traffic 2102–2105, 2149–2150, 2294–2297, 2361; the public notice 2884; the headline 3111; view counters 3175–3326
  - *The Wraith*: Federation messages 25, 29, 109, 119, 133, 191, 365. These are read inside scenes, so italics would also suit them.
  - *Shadows in Tel Aviv*: the calling card 169; the verdict 199
  - *Silent Watchers*: URL 52; terminal text 64–66, 136; email headers 216–217, 346–347; notification 1274
  - *Shade of Gray*: the handwritten card 25
  - *Executive Authority*: ledger dates 361–499
  - *David v Goliath*: countdown 835
  - *The Cormorant Gambit* 73, 119–120; *Torchlight* 69–71; *The Helpers* 997–999; *Boundary Layer* 58

## 3. Dialogue outside blockquotes

`CLAUDE.md` puts dialogue in Markdown blockquotes. These counts come from a scan for paragraphs containing quoted speech that don't start with `>`.

### Stories written with inline dialogue throughout

Converting these is mechanical: every paragraph that contains dialogue gets a `>` prefix, with its tags and action beats inside, as in the newer stories. One decision per story.

- [ ] The Wraith (`story-american-wraith.md`): 1051 inline dialogue paragraphs, 0 blockquoted. No dialogue is blockquoted. `>` appears only in in-world documents.
- [ ] Silent Watchers (`story-japanese-wraith.md`): 684 inline dialogue paragraphs, 0 blockquoted. No dialogue is blockquoted, and dialogue uses curly quotes. `>` is used only for chats, terminals and messages.
- [ ] Shadows in Tel Aviv (`story-israeli-wraith.md`): 107 inline dialogue paragraphs, 1 blockquoted. One blockquoted line; everything else inline. `>` is used for the dossier.
- [ ] Executive Authority (`story-executive-authority.md`): 183 inline dialogue paragraphs, 5 blockquoted. Inline dialogue looks deliberate here: blockquotes are reserved for the radio call, the Federation operator and the ledger. Converting would change that effect.
- [ ] Torchlight (`story-torchlight.md`): 66 inline dialogue paragraphs, 0 blockquoted. No dialogue is blockquoted. Comms lines are in italics; the warning prompt is a blockquote.
- [ ] The Cormorant Gambit (`story-the-cormorant-gambit.md`): 26 inline dialogue paragraphs, 0 blockquoted. No dialogue is blockquoted.

### Stray inline dialogue in blockquoted stories

These stories put dialogue in blockquotes but let some lines slip. Lines marked "(quoted term)" quote a word or name inside narration and are probably fine as they are. Tick a story to convert all its listed lines, and delete any line you want left alone.

#### Ex Mero Mutu

- [ ] Convert all 137 lines below (`story-ex-mero-mutu.md`; 281 dialogue paragraphs are already blockquoted)

  - 30: `A journalist from *Lusa* news agency raised her hand. "General, can you elaborate on these security…`
  - 32: `Alves chose his words carefully. "Portugal remains committed to NATO and our collective defense obli…`
  - 38: `Another hand shot up from the back. "General, is this related to President Trump's comments about NA…`
  - 52: `Alves nodded, unsurprised. "Schedule it. And make sure Lieutenant Freitas is available for the techn…`
  - 54: `The aide made a note. "And the Eurofighter consortium?"`
  - 71: `Alves leaned back in his chair. "Let's have it."`
  - 77: `Freitas consulted his tablet. "The Swedes offer good value and lower operating costs. Reliable aircr…`
  - 85: `Sergeant Leite looked up from his notes. "Sir, pilot transition time is another factor. Moving from…`
  - 103: `Freitas exchanged a glance with Leite before answering. "Honestly, sir? None solve our fundamental p…`
  - 113: `Alves turned back from the window. "Rumors?"`
  - 115: `Leite spoke up. "There's been chatter about breakthrough technologies, sir. Advanced propulsion, new…`
  - 154: `Leite's voice came back sharp, boredom gone. "Affirmative. Two contacts, bearing three-two-zero, ran…`
  - 162: `No longer routine. Freitas keyed his radio. "Lisbon Control, Watchful 1. Two unidentified contacts a…`
  - 164: `The response came back crisp and professional. "Watchful 1, Lisbon Control. We show no scheduled mil…`
  - 198: `His radio crackled with Leite's voice, tense but controlled: "Control, Watchful 2. Two contacts on i…`
  - 200: `The response from Lisbon Control carried uncertainty. "Watchful flight, maintain defensive posture.…`
  - 206: `Leite was quiet for a moment, then his voice came back with a different quality - recognition mixed…`
  - 258: `Leite's voice broke into the conversation, tense and suspicious. "Miguel, they know too much. This i…`
  - 292: `A long pause from Control, then: "Watchful 1, are the unknown aircraft showing any hostile intent?"`
  - 344: `Leite's voice came over the radio, barely a whisper: "Miguel... we're not escorting aircraft. We're…`
  - 363: `Corporal Ana Santos, normally the most composed radar operator on the base, looked up from her scope…`
  - 369: `Lieutenant João Ferreira looked up from the secure communications console, shaking his head. "They'r…`
  - 385: `A pause before Freitas responded. "Tower, understood. Unknown aircraft are maintaining formation dis…`
  - 393: `Corporal Santos was tracking the approaching formation on both primary and secondary radar. "Sir, th…`
  - 397: `Santos checked her secondary displays, then shook her head grimly. "The Sidewinder stations report i…`
  - 413: `Behind them, the radio crackled with Freitas's final approach call: "Monte Real Tower, Watchful 1 on…`
  - 527: `Major Ribeiro snapped to attention. "General, HARBINGER has been waiting for your arrival. It has be…`
  - 549: `Alves leaned against the console, studying the alien aircraft below. "I'm listening."`
  - 628: `Finance Minister Miguel Santos leaned forward, his expression skeptical. "And the cost?"`
  - 652: `Carvalho consulted her notes. "We continue with our current modernization challenges. The F-16 fleet…`
  - 656: `Finance Minister Santos raised another concern. "What about economic implications? If we accept thes…`
  - 660: `Interior Minister Pereira shook his head. "This is madness. We're considering making Portugal depend…`
  - 670: `Foreign Minister Ribeiro nodded. "With the Americans, we at least participate in the same political…`
  - 678: `Prime Minister Silva looked around the table one final time. "I want each ministry to conduct detail…`
  - 703: `Freitas felt his pulse quicken. "What kind of demonstration?"`
  - 745: `*"Participating in requested demonstration flight with HARBINGER aircraft to evaluate capabilities f…`
  - 766: `Freitas keyed his radio. "Tower, this is Lieutenant Freitas aboard HARBINGER One. Requesting clearan…`
  - 768: `After a brief pause, the tower responded: "HARBINGER One, cleared to taxi to Runway 05. Contact depa…`
  - 797: `Sergeant Major Silva reached the aircraft first. "Lieutenant? Are you alright, sir?"`
  - 803: `Freitas looked at him with eyes that had seen too much. "I need to write a report," he said quietly,…`
  - 805: `Corporal Cardoso approached from the other side. "Lieutenant, the base commander wants a briefing on…`
  - 844: `Foreign Minister Ribeiro leaned forward, adjusting his glasses. "General, before we proceed - how ce…`
  - 846: `Alves had anticipated the question. "Minister, Freitas makes no claims about how the aircraft functi…`
  - 848: `Defense Minister Carvalho gestured toward the reports. "What were the key observations, General?"`
  - 850: `Alves opened his copy to the first operational section. "The demonstration began with atmospheric fl…`
  - 852: `Prime Minister Silva studied the sparse technical annotations. "Freitas provides no analysis of how…`
  - 866: `Interior Minister Pereira shook his head slowly. "General, aircraft don't function underwater. The p…`
  - 874: `European Affairs Minister Costa felt her breath catch. "Space? You mean..."`
  - 878: `Justice Minister Moreira raised the obvious question. "How is this possible? Aircraft engines don't…`
  - 892: `Defense Minister Carvalho leaned back in her chair, struggling to process the implications. "General…`
  - 896: `Alves turned to another section of the report. "During the return journey, HARBINGER provided what F…`
  - 898: `Justice Minister Moreira leaned forward. "What other weapons systems?"`
  - 902: `Foreign Minister Ribeiro voiced what they were all thinking. "If this is accurate, we're not talking…`
  - 904: `Alves nodded grimly. "Freitas concludes his report with a simple observation: 'Any nation possessing…`
  - 906: `Prime Minister Silva felt the weight of an impossible decision settling on his shoulders. "General,…`
  - 910: `Interior Minister Pereira voiced the concern they were all wrestling with. "General, if these observ…`
  - 945: `Foreign Minister Ribeiro was the first to speak. "Prime Minister, I've consulted discretely with our…`
  - 951: `Interior Minister Pereira nodded grimly. "Which brings us to domestic considerations. How do we expl…`
  - 955: `Finance Minister Santos raised a practical concern. "And when these aircraft demonstrate capabilitie…`
  - 959: `European Affairs Minister Costa shook her head. "That's not sustainable long-term. Technology this a…`
  - 965: `Moreira consulted his notes carefully. "Constitutionally, the government has authority to procure mi…`
  - 981: `Defense Minister Carvalho nodded slowly. "The same logic applies here. If HARBINGER has decided that…`
  - 985: `Foreign Minister Ribeiro raised one final concern. "Prime Minister, if we accept these aircraft and…`
  - 1003: `Defense Minister Carvalho nodded. "The Americans especially. They're already suspicious about our F-…`
  - 1007: `Prime Minister Silva weighed the options carefully. "Better to control the revelation than have it f…`
  - 1009: `European Affairs Minister Costa raised a concern. "Prime Minister, how do we explain aircraft that c…`
  - 1013: `Interior Minister Pereira shook his head. "They'll assume we've made a deal with Russia or China. Or…`
  - 1017: `Defense Minister Carvalho considered the timeline. "We should wait until we have operational aircraf…`
  - 1021: `Justice Minister Moreira raised another implication. "And when the Americans demand technology shari…`
  - 1023: `Silva's expression grew calculating. "We'll discover how flexible American attitudes toward alliance…`
  - 1046: `Defense Minister Carvalho stepped forward. "HARBINGER, we need to discuss implementation details. Tr…`
  - 1050: `Alves felt a sense of relief mixed with continued apprehension. "When do we receive the first aircra…`
  - 1054: `Carvalho felt her breath catch. "Technical specialists? Human personnel?"`
  - 1087: `General Hayes leaned forward slightly. "Beyond current standards in what way, General?"`
  - 1099: `General Mueller's expression shifted from polite attention to sharp focus. "This is not possible wit…`
  - 1101: `Alves had dreaded this question while knowing it was inevitable. "The procurement program remains cl…`
  - 1103: `Air Chief Marshal Windsor studied the Portuguese general with obvious skepticism. "General Alves, yo…`
  - 1111: `Alves felt the political minefield opening beneath his feet. "General Hayes, the technology was not…`
  - 1115: `Secretary-General Rasmussen raised his hand for calm before tensions could escalate further. "Genera…`
  - 1117: `Alves nodded, having anticipated this request. "I have authorization to provide a limited demonstrat…`
  - 1129: `General Hayes leaned forward, her professional pilot's eye catching details that others might miss.…`
  - 1145: `General Mueller felt his understanding of physics being challenged in real-time. "This is not possib…`
  - 1147: `The footage showed the Talon approaching what was clearly a submarine - long, dark, and unmistakably…`
  - 1151: `Deputy Director Richardson was already reaching for his secure phone. "General, you're showing us fo…`
  - 1159: `General Dubois spoke for the first time, his voice carrying profound disbelief. "You are showing us…`
  - 1163: `The demonstration concluded with a routine landing back at Monte Real, the pilot's voice professiona…`
  - 1167: `Deputy Director Richardson was already reaching for his secure phone. "General Alves, I need to cont…`
  - 1171: `General Mueller leaned back in his chair, his expression shifting from skepticism to something appro…`
  - 1173: `Alves chose his words with extreme care. "General Mueller, I can tell you that the technology was pr…`
  - 1175: `Air Chief Marshal Windsor voiced what they were all thinking. "Entities? General, you're being delib…`
  - 1179: `Secretary-General Rasmussen felt the weight of implications settling over the room. "General Alves,…`
  - 1183: `General Hayes felt her strategic calculations shifting in real-time. "General, a single aircraft wit…`
  - 1191: `Alves met Richardson's gaze directly. "Because, Mr. Richardson, Portugal values our alliance relatio…`
  - 1193: `General Dubois spoke for the first time, his voice carrying the weight of French strategic thinking.…`
  - 1197: `Secretary-General Rasmussen realized the meeting had reached a critical juncture. "General Alves, NA…`
  - 1214: `Secretary of Defense Lloyd Austin spoke first, his voice carrying barely controlled frustration. "Mr…`
  - 1216: `CIA Director William Burns leaned forward from his video connection at Langley. "Sir, our intelligen…`
  - 1218: `Trump's face reddened as the implications became clear. "How does Portugal - *Portugal* - acquire mi…`
  - 1220: `National Security Advisor Jake Sullivan consulted his classified briefing materials. "Mr. President,…`
  - 1224: `Secretary Austin brought up the most immediate concern. "Sir, if Portugal possesses these capabiliti…`
  - 1226: `Trump stared at the table, his business instincts recognizing a deal where America had been excluded…`
  - 1228: `CIA Director Burns raised another possibility. "Mr. President, we need to consider that this technol…`
  - 1236: `Secretary Austin brought the discussion back to immediate concerns. "Mr. President, regardless of th…`
  - 1238: `Trump's expression shifted to the calculating look his staff recognized from high-stakes business ne…`
  - 1240: `National Security Advisor Sullivan consulted his briefing materials. "Sir, we can demand technology…`
  - 1244: `Secretary Austin shook his head. "Sir, Portuguese officials indicate that technology sharing isn't t…`
  - 1246: `Trump stood up abruptly, pacing behind his chair as his frustration mounted. "So Portugal gets offer…`
  - 1248: `CIA Director Burns offered a possibility that made everyone uncomfortable. "Mr. President, it's poss…`
  - 1256: `Secretary Austin brought up another concern. "Mr. President, if Portugal is the first recipient of t…`
  - 1258: `Trump returned to his seat, his expression grim. "What's our immediate response to Portugal?"`
  - 1260: `National Security Advisor Sullivan had prepared recommendations. "Sir, we maintain public alliance c…`
  - 1266: `Trump's business instincts suggested a different approach. "What if we offered Portugal something th…`
  - 1268: `Secretary Austin considered the possibility. "Sir, Portugal may have concluded that their security i…`
  - 1276: `As the meeting concluded, President Trump issued his final directive: "I want to know who's behind t…`
  - 1285: `The private dining room overlooking the gardens of the Portuguese Defense Ministry's official reside…`
  - 1291: `Carvalho smiled politely, the expression of a seasoned politician who had anticipated this moment si…`
  - 1299: `Mitchell leaned forward slightly. "Meaning?"`
  - 1305: `Carvalho paused, considering the implications of honesty versus diplomacy. "Ambassador, these aircra…`
  - 1313: `Mitchell recognized the skillful deflection but pressed forward. "The technology gap is unprecedente…`
  - 1321: `Mitchell made a calculated decision to abandon diplomatic circumlocution. "Our assessments suggest t…`
  - 1323: `Carvalho nodded slowly. "Your analysts are remarkably accurate. And remarkably honest."`
  - 1331: `Mitchell felt her diplomatic training warring with her strategic instincts. "Minister, surely you un…`
  - 1343: `Carvalho smiled. "Ambassador, integration has already occurred. Portugal operates within NATO comman…`
  - 1349: `Mitchell felt the conversation reaching an impasse. "Then perhaps Washington should engage directly…`
  - 1355: `Mitchell shifted tactics. "Minister, from an operational perspective, how do you see Portugal's role…`
  - 1357: `Carvalho considered the question carefully. "Portugal has traditionally been a security consumer wit…`
  - 1381: `Mitchell nodded thoughtfully. "I'll convey that perspective to Washington, Minister. Though I suspec…`
  - 1398: `Nuland leaned forward slightly. "Walk us through it, Sarah."`
  - 1406: `CIA Deputy Director Richardson joined the conversation from Langley. "Did she provide any additional…`
  - 1410: `Nuland considered the implications. "So pressure on Portugal is ineffective because the real decisio…`
  - 1414: `General Hayes raised a practical concern. "From an operational standpoint, how are they positioning…`
  - 1420: `Richardson was first to respond. "That level of capability concentration fundamentally alters Europe…`
  - 1424: `Nuland asked the question everyone was considering. "Sarah, what's your recommendation for American…`
  - 1426: `Mitchell had spent the afternoon wrestling with exactly that question. "Madam Deputy Secretary, I be…`
  - 1432: `General Hayes considered the military implications. "That would require significant adjustments to o…`
  - 1436: `Richardson raised another concern. "What about other allies? How do France, Germany, and the UK resp…`
  - 1440: `Nuland summarized the strategic assessment. "So our choice is between partnership with an equal or p…`

#### Across the Sea

- [ ] Convert all 57 lines below (`story-across-the-sea.md`; 510 dialogue paragraphs are already blockquoted)

  - 27: `"Maintain course and broadcast civil traffic intent," he ordered. "File it under hydrographic survey…`
  - 29: `"Aye, sir."`
  - 141: `Lu turned sharply. "Where?"`
  - 197: `Lu walked back over, keeping his expression neutral. "What do you mean?"`
  - 426: `His operations chief blinked. "Rules of engagement?"`
  - 610: `Ramirez turned. "What's it doing?"`
  - 984: `Every single one of these machines gets down on *one knee*, with both *arms* extended to brace on th…`
  - 1808: `"…and even *if* they were using inertial dampening - if that's even possible - the G-forces involved…`
  - 2190: `Gao hesitated. "Captain, do you truly believe this will change anything?"`
  - 2647: `"Eliminated," Lu finished quietly. "All of them."`
  - 2655: `"Sir," his sensor operator called out, voice tight with professional alarm. "I'm detecting infrared…`
  - 2657: `Lu didn't look up from the photograph. "Range to targets?"`
  - 2659: `"Fourteen point seven kilometers. Direct bearing on our position."`
  - 2663: `"Time to impact?"`
  - 2665: `"Sir, I'm not detecting any launch signatures -"`
  - 2669: `"Attention," he announced, his voice carrying the same steady authority that had commanded this brid…`
  - 2671: `His XO stared at him. "Captain?"`
  - 2675: `"Tell the crew," he said quietly. "We served with honor. We chose -"`
  - 2924: `Watkins gave a half-shrug. "Military intelligence has no good guesses at this time, sir."`
  - 2926: `Another general slid a fresh report forward. "Details are still unclear, Mr. President, but one of t…`
  - 2976: `Morse raised an eyebrow in her cockpit and muttered under her breath, "Well that's comforting..."`
  - 3219: `Volkov leaned forward. "Your assessment?"`
  - 3263: `Admiral Kozlov leaned forward. "And our chances against them?"`
  - 3265: `Marchenko's laugh was hollow. "Admiral, our most advanced naval guns fire at roughly 800 meters per…`
  - 3269: `"A conventional 130mm shell carries about 40 megajoules of kinetic energy. These railgun projectiles…`
  - 3281: `Admiral Kozlov rubbed his temples. "Ukraine?"`
  - 3287: `Dr. Marchenko nodded grimly. "Based on the Gaza deployment, a single squad pacified an entire city.…`
  - 3428: `"Gentlemen," Stoltenberg began, his Norwegian accent lending an odd formality to the unprecedented g…`
  - 3432: `General Cavoli, NATO's Supreme Allied Commander, opened the folder in front of him. "Three weeks ago…`
  - 3434: `Xi leaned forward slightly. "Let us be precise, General. Your forces witnessed this. Ours experience…`
  - 3438: `"The aircraft that intercepted our J-16s," continued General Liu, speaking for the Chinese delegatio…`
  - 3442: `"So we're dealing with humans," Putin observed quietly. "Humans with access to technology that surpa…`
  - 3444: `"And an artificial intelligence," added Admiral Kozlov, representing the Russian Navy. "The entity t…`
  - 3446: `Stoltenberg nodded. "Which brings us to the fundamental question: what do they want?"`
  - 3448: `General Milley, Chairman of the U.S. Joint Chiefs, spoke for the first time. "Based on observed beha…`
  - 3450: `"Gaza," Putin said simply.`
  - 3452: `"Taiwan," Xi added.`
  - 3454: `"Both situations where established military thinking was about to produce significant casualties," C…`
  - 3456: `The Chinese General Liu opened his own briefing folder. "Our intelligence services have compiled rep…`
  - 3458: `Putin's defense minister, Sergei Shoigu, nodded grimly. "We have similar reports. Weapons caches in…`
  - 3460: `"And that's just what they've shown us," Wigston added. "The question every intelligence service is…`
  - 3464: `Finally, Xi spoke, his words measured but carrying an edge. "Gentlemen, we face an unprecedented cha…`
  - 3466: `Putin's jaw tightened, his voice dropping to its familiar low register. "What you're suggesting, Com…`
  - 3468: `"This isn't about stepping aside," Xi replied, his diplomatic mask slipping slightly. "But we must b…`
  - 3470: `"Realistic?" Putin interrupted, leaning forward. "I've built my career on refusing to accept other p…`
  - 3472: `Stoltenberg shifted uncomfortably, his NATO training warring with pragmatic assessment. "The Allianc…`
  - 3474: `"Traditional deterrence is all we have," Putin said, his voice hardening. "Unless you're proposing w…`
  - 3476: `"Not unless we're prepared to meet 'HARBINGER''s pilots again," Milley agreed.`
  - 3478: `General Liu consulted his notes. "The People's Republic has already begun repositioning assets defen…`
  - 3480: `"As are we," Shoigu confirmed. "The Black Sea Fleet has received new standing orders regarding proxi…`
  - 3482: `Cavoli nodded. "And we've suspended several forward deployment exercises. Not permanently, but... pe…`
  - 3484: `Stoltenberg looked around the table. "So we're in agreement? Economic and diplomatic competition con…`
  - 3488: `"There's one more thing," Xi said quietly. "These human pilots - American, Australian, British accen…`
  - 3490: `"And coordinating with an artificial intelligence of unknown origin," Putin added.`
  - 3492: `"The question," Milley said, "is whether we attempt to establish regular diplomatic channels, or acc…`
  - 3494: `"The UN delegation in Gaza was able to communicate directly with one of the Landmate units," Stolten…`
  - 3496: `"I think," Stoltenberg said carefully, "the choice may not be ours to make. They've demonstrated the…`

#### Angels in Armor

- [ ] Convert all 32 lines below (`story-angels-in-armor.md`; 484 dialogue paragraphs are already blockquoted)

  - 21: `He blinked. "Say again?"`
  - 49: `"What the hell are those?" muttered his gunner, half-risen from the hatch.`
  - 61: `Her cameraman zoomed in on the insignia. "Do you know that logo?" he whispered.`
  - 85: `"Not one of ours?" he asked quietly.`
  - 87: `"No sir. No nation claims them. No chatter. No intel. Mossad's blind. Langley's calling them 'angels…`
  - 249: `"Could be directed-energy," one analyst offered.`
  - 251: `"Not a beam," another snapped. "There's no heat plume, no residual radiation, no dispersion. And tha…`
  - 285: `He sat up straighter. "Sir. We're holding position. No further provocation. Units - whatever they ar…`
  - 289: `Mazar exhaled slowly. "Yes, sir."`
  - 527: `Leila nodded, lips pressed into a thin line. "We caught it all on tape."`
  - 529: `Mazar's gaze grew distant. "They didn't bluff. One of my tank commanders panicked. Fired a sabot." H…`
  - 533: `He gave a humorless smile. "Wasn't part of the plan."`
  - 535: `She tilted her head. "And now? Just... silence?"`
  - 537: `Mazar nodded. "Same across the Strip. Rafah, Khan Yunis, Beit Hanoun. The pattern's identical. Units…`
  - 549: `She shook her head. "Of *them*. They don't know what they are, why they're here, or if they're going…`
  - 623: `Leila's brow furrowed. "You keep calling them 'they.' You think they're crewed?"`
  - 639: `Leila leaned in slightly. "Why?"`
  - 651: `Leila looked stunned. "You walked past it? Unarmed?"`
  - 677: `Mazar offered a tired smile. "Not much point in lying. Not anymore."`
  - 695: `A sergeant answered. "No change. Golems haven't moved."`
  - 697: `Mazar nodded. "Good. Let's make sure they don't have to."`
  - 1198: `A girl with a scraped knee shook her head. "No. They don't hurt us. They just stand there. Like they…`
  - 1216: `Leila smiled. "Do they wave back?"`
  - 1329: `One of his lieutenants kept his eyes down. "We sent teams north and east. Rafah, Zeitoun. All gone.…`
  - 1331: `Abu Sharif's eyes burned. "*Vanished.* Just like that. Shot? Taken? We don't even know. We don't *se…`
  - 1333: `Another fighter nodded grimly. "You don't *see* anything. The moment you step into their shadow, it'…`
  - 1740: `Ahlström nodded. "Which is why this delegation has been assembled. Your brief is simple: initiate pe…`
  - 1776: `Ahlström nodded. "Good. Proceed."`
  - 1830: `Jan nodded. "That's why we'll stand two meters apart, arms visible, no objects in hand. Even paper m…`
  - 1854: `Someone across the bay muttered, "With what, exactly?"`
  - 1885: `Jan Roussel, scribbling shorthand notes, nodded. "That's *recognition*. Not identity - *intent*. We'…`
  - 2048: `Roussel, throat dry, muttered, "By *you*?"`

#### Flight of Icari

- [ ] Convert all 22 lines below (`story-future-flight.md`; 569 dialogue paragraphs are already blockquoted)

  - 53: `Adams whistled into the comms. “You’ve *got* to be kidding me.”`
  - 397: `Voss nodded. “That’s the point.”`
  - 481: `Adams blinked. “Okay. That’s new.”`
  - 483: `Lindholm, climbing into his own bird, was watching with narrowed eyes. “Did it *talk* to you?”`
  - 1061: `“Every instinct and every brain cell in Lindholm’s head screamed against him as he dove his Talon di…`
  - 1397: `Voss chimed in last. "Talon-1, cleared. Let's take the high road."`
  - 1523: `"Radar contact. Multiple objects," said Commander Guo, squinting at his monitor. "No thermal signatu…`
  - 1529: `Guo frowned. "They just... disappeared."`
  - 1565: `An American general near the front turned to his aide, voice low but carrying in the stunned quiet.…`
  - 1569: `Silva leaned closer to Tavares. "We've been flying these for a year and never knew they could do *th…`
  - 1625: `Kraus grit his teeth. “Get me nose-on!”`
  - 1633: `Adams started to laugh, breathless. “It’s *listening* to us.”`
  - 1924: `Adams exhaled. “And they didn’t even scratch us.”`
  - 2090: `“Sir, radar contact. Brief. High velocity. Low signature.”`
  - 2226: `They’d been quiet at first—grateful, tired. But with each drink, the tension of asteroid duels and o…`
  - 2302: `He turned, mid-step, eyes narrowing. “What?”`
  - 2310: `Harris blinked. “Voss’s—?”`
  - 2328: `Talon One climbed through the darkness on a smooth arc, guided by no human hands. Its plasma engines…`
  - 2478: `Adams leaned back, eyes on the paused screen. “Feels backwards. Machine flying while we’re drunk in…`
  - 2506: `Jessica Parker, callsign “Spitfire,” USAF. Former F-15E Strike Eagle pilot, two deployments over the…`
  - 2782: `Grainy stills, slowed-down footage, sensor-blurred shapes—mysterious craft with impossible flight pr…`
  - 2792: `In Pyongyang, rocket launches were postponed. In Tehran, drone deployments suddenly shifted back to…`

#### The Beginning Is A Delicate Time

- [ ] Convert all 22 lines below (`story-the-beginning.md`; 74 dialogue paragraphs are already blockquoted)

  - 18: `"What have I gotten myself into? And did I *really* have to make that wish...?"`
  - 64: `Haytham studied the symbols, which seemed to shift slightly when he wasn't looking directly at them.…`
  - 86: `Haytham looked out the window where Thel'zar was patiently showing Private Stevens how to calibrate…`
  - 104: `General Haytham studied the display. "And you're here to help us make that transition?"`
  - 128: `Secretary Forrestal studied the photograph intently. "And you believe this offer is genuine?"`
  - 152: `Dr. Platchett looked up from a device he'd been studying. "Thel'zar, why now? You said you've been o…`
  - 158: `General Haytham leaned forward. "Other factors?"`
  - 174: `General Haytham absorbed this, understanding the implicit message. "How long do we have to decide?"`
  - 194: `Several heads nodded around the room. British Air Commodore Geoffrey Whitman straightened his unifor…`
  - 196: `Thel'zar regarded the Soviet general with what might have been amusement. "General Petrov, you comma…`
  - 198: `Petrov's face went pale. "That information is classified at the highest levels."`
  - 202: `Dr. Li's eyes widened. "I have not published that research. Only three people know of it."`
  - 206: `Karl Schmidt from Berlin University leaned forward despite himself. "Show me."`
  - 232: `Marcelli held the sample with trembling hands. "The applications... this could revolutionize everyth…`
  - 248: `British businessman Hugh Fairfax leaned back in his chair, overwhelmed. "Gentleman, we're discussing…`
  - 252: `Dr. Li Wei looked up from calculations he'd been scribbling. "Thel'zar, you mentioned that contact w…`
  - 262: `General Haytham watched this evolution with satisfaction. "Thel'zar, this cooperation you're seeing…`
  - 266: `Japanese diplomat Nakamura raised a concern that had been troubling several participants. "The scope…`
  - 270: `Italian engineer Marcelli looked thoughtful. "The technology transfers alone would revolutionize our…`
  - 284: `Nakamura appeared to weigh the proposal then shook his head."No. It speaks of secret working, yes, b…`
  - 294: `General Petrov raised his hand. "Comrades - forgive me, colleagues - we have spent days planning str…`
  - 304: `The implications hung in the air. Dr. Li Wei spoke first. "You're proposing we pool our resources an…`

#### David v Goliath

- [ ] Convert all 18 lines below (`story-david-v-goliath.md`; 518 dialogue paragraphs are already blockquoted)

  - 156: `He opened his field notebook and began writing, starting with the clinical observation that would so…`
  - 210: `She began drafting an alert to NATO command: "New player has entered the Ukraine conflict. Rules app…`
  - 239: `Another touch, another red circle marked "2."`
  - 479: `Colonel Volkov approached with damage assessments. "Sir, total loss. Five facilities destroyed simul…`
  - 643: `Sergeant Kravchenko looked up from his rifle. "What kind of disruption, sir?"`
  - 719: `The *Auroras* crossed the entire width of Germany in 78 seconds, leaving a phenomenon unlike anythin…`
  - 721: `In Bavaria, hikers in the Alps stopped to photograph what they initially thought was an unusual auro…`
  - 762: `Private Marchenko looked up from his equipment. "Another air strike, sir?"`
  - 799: `Brigadier General Doroshenko stood beside the console. "How certain are we about these coordinates?"`
  - 801: `Colonel Kovalenko consulted the device one final time. "Dead certain, sir. Pokrovsk rail depot, Vuhl…`
  - 973: `"IMPOSSIBLE SPEED: Three Mystery Objects Cross Europe in 5 Minutes!" - 2.3M views in 2 hours`
  - 975: `"PLASMA TRAILS OVER PARIS: Aliens or Secret Military Tech?" - 1.8M views`
  - 977: `"PILOT TESTIMONY: 'Unlike Anything in 20 Years of Flying'" - 987K views`
  - 979: `"SCIENTIST EXPLAINS: Why These Objects 'Shouldn't Exist'" - 1.4M views`
  - 1011: `Behind him, a graphic displayed the reported flight path with question marks and the label "ALLEGED…`
  - 1610: `Twitter users created elaborate threads documenting the "RIP Russian Arsenal" with each destroyed we…`
  - 1612: `The most viral meme showed a screenshot from Dmytro's video at the moment of a massive corona discha…`
  - 1622: `The video ended with one grandmother raising a shot glass of vodka toward the Guardian installation:…`

#### Knock Knock

- [ ] Convert all 15 lines below (`story-knock-knock.md`; 915 dialogue paragraphs are already blockquoted)

  - 779: `Lieutenant Miguel Freitas's phone had rung at 8:23 AM local time. The voice on the other end was cli…`
  - 1537: `Major Tanaka Utsuho - callsign "Okuu," much to the confusion of anyone outside the Japanese Air Self…`
  - 2663: `Twenty American Talons dove from above, Major Morse's voice cutting through the net: "Viper Squadron…`
  - 2665: `Sixteen Japanese Talons rolled into attack formation, Major Tanaka's crisp acknowledgment: "Hell Rav…`
  - 2769: `But "better than expected" wasn't the same as "good enough to win."`
  - 3298: `The briefing from three months ago. The theoretical weapon system. The one that had never been teste…`
  - 4752: `Now she had a flag, a coin she didn't understand, and a statuette bearing Latin words that translate…`
  - 4756: `But the colonel who'd delivered the news had looked her in the eye and said something she would neve…`
  - 4825: `Chen felt something cold settle in her chest. "You're saying they don't know it's possible."`
  - 4829: `Voss looked between Chen and SUNTZU. "That means..."`
  - 4857: `Commander Kim moved up beside them, her eyes fixed on the Flycatcher. "And they're sure the Ryzak ca…`
  - 4873: `Morse looked troubled. "How do you explain their effectiveness when they inevitably see combat?"`
  - 4893: `Trager nodded. "Make it happen."`
  - 4895: `Voss pulled up a communication interface. "FSS Flycatcher, FSS Broadsword, this is Jovian Shipyards…`
  - 4919: `Morse nodded slowly. "Those are the decisions that define people."`

#### Shade of Gray

- [ ] Convert all 8 lines below (`story-shade-of-gray.md`; 415 dialogue paragraphs are already blockquoted)

  - 453: `He was professional, focused, and consistently productive. He also made an unsettling number of phon…`
  - 973: `"—should be ready by now—"`
  - 975: `"—Marcus said they finished the second unit—"`
  - 977: `"—move everything tonight, get it staged—"`
  - 1591: `Hartfield was already opening his door, his rifle coming up as he scanned the street. "No time for r…`
  - 1665: `Hartfield reached into his tactical vest and pulled out a red Swiss Army knife, flipping it open to…`
  - 1757: `LeBouf nodded approvingly. "The official investigation will handle the criminal prosecution. But the…`
  - 1775: `Alicia Monroe's words echoed in her memory, that warning delivered in the sterile conference room th…`

#### The Helpers

- [ ] Convert all 6 lines below (`story-the-helpers.md`; 459 dialogue paragraphs are already blockquoted)

  - 55: `The Russian ambassador stood, his voice cutting through the chamber. "And if we refuse? What guarant…`
  - 662: `Klaus stood in the depot's testing area, watching as Lieutenant Fischer walked a Landmate through in…`
  - 932: `The screen displayed an animated diagram showing a sphere of full intelligence with a smaller, restr…`
  - 1142: `A moment's pause while the engineers on site confirmed. Then: "Structure secured. Unit cleared for r…`
  - 1514: `One of the four—a middle-aged man—had a highlighted chest. Red indicator. Text appeared: "Suspected…`
  - 1603: `"Dismount"`

## Appendix: checked and found consistent

The reviewers verified these against canon. They need no action, and are listed so they don't get raised again.

- *Knock Knock*: the 250 km FLYCATCHER field, the 75 km probe sphere and the 50 km *Broadsword* field; HARBINGER's 43% and 94% assessment; the July 18 commissioning; jump emergence within 10 km of the beacon; the Sol beacon at Jupiter; the Great Circle; CONCORD's protected zone; the Kryllian breathing apparatus; AI names in capitals.
- *The Helpers* matches every timeline date and detail, from the UN offer on September 3 to the Bofors debate on December 15. *Flight of Icari*'s warp-entry rule (align, then 25 m/s) matches `ftl.md`.
- *Across the Sea* and *David v Goliath*: the Federation's name and emblem in Kovalenko's and Syrskyi's point of view are not leaks, because *Angels in Armor* made both public in June 2024. The same goes for the black aircraft in the Gaza footage and HARBINGER's "my masters". Dr. Petrenko's "non-terrestrial technology" is speculation, not knowledge.
- *Executive Authority*'s references to *Across the Sea*, *David v Goliath* and *The Helpers* are consistent: the 2,500 kelvin, Kyiv on the twelfth, 162 nations with ten units each, the Bofors range, the Agincourt callback. "Makes diamond diamond" is deliberate, and the operatives' lens clusters and loadout match *Shade of Gray* and the codex.
- *Silent Watchers*: Israel's denial "until they changed their ways" matches *Shadows in Tel Aviv*. *The Beginning*'s "seven nations" is right, since it excludes the US hosts. *Shade of Gray*'s chapter 1 countdown arithmetic holds. *P = NP* and *The Beginning* have no knowledge leaks.
- Dictionary and doubled-word scans of *The Wraith* and *Shadows in Tel Aviv* found nothing beyond the listed items.
