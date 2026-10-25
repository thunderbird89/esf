# Translation Style Guide

This guide sets the tone, voice, and conventions to preserve when translating the ESF stories in `stories/`. Use it with the [glossary](glossary.md). It describes the stories as they are actually written, and where the source is inconsistent, it says how to handle that.

The writing rules in `CLAUDE.md` govern how new stories are written. They do not govern translation. A translation reproduces the story in front of it, quirks included, and corrects nothing.

## Scope

- Translate the stories that have frontmatter. `story-the-ghost-plane.md` and `story-shadow-alliance.md` have none because they were pulled for rewriting; don't translate them.
- `stories/index.md` and `stories/buffer.md` are not stories.
- Several filenames differ from their titles: `story-american-wraith.md` is *The Wraith*, `story-israeli-wraith.md` is *Shadows in Tel Aviv*, `story-japanese-wraith.md` is *Silent Watchers*, and `story-future-flight.md` is *Flight of Icari*.

## The voice in brief

The ESF stories are military and political science fiction told mostly from the outside. Soldiers, analysts, politicians, and ordinary people meet the Federation without understanding it, and aliens meet humans the same way. The prose is procedural and concrete, trusts the reader with jargon, and draws its drama from what characters can't explain rather than from adjectives. The Federation is terse, competent, opaque, and faintly amused. Violence is quick and seldom dwelt on. Humor is dry and usually arrives as understatement. The recurring feeling is awe: at a machine that shouldn't exist, or at a species that shouldn't have won.

Within that, each story keeps its own temperature. *Executive Authority* is restrained and literary, *Angels in Armor* reverent, *Flight of Icari* driven by banter, and *The Cormorant Gambit* and *Adrenaline* deliberately loud. Translate each at its own temperature; don't level them toward a common middle.

## Principles

In order of priority, when they conflict:

1. Keep what each character knows. Never let the translation tell the reader more than the point-of-view character could know.
2. Keep the emotional temperature. Don't amplify and don't dampen.
3. Keep the voices apart. An AI, a Ryzak, a general, and a teenager must still sound like four different speakers.
4. Keep the structure; localize the typography.
5. Keep terms fixed. Settle a rendering once per language and hold it everywhere.
6. Translate what's there. Flag problems; don't fix them.

## What characters know

The setting turns on an information gap. National militaries, intelligence services, and ordinary people don't know that the Federation has alien backers, or that alien empires exist, and many scenes run on characters guessing wrong.

- Never add an explanation, gloss, footnote, or translator's note that tells the reader more than the point-of-view character knows. If an analyst calls a *Talon* a jet, it stays a jet.
- Keep deliberate ambiguity ambiguous. "Alien" in a non-Federation mouth means strange or foreign (*Shadows in Tel Aviv*, *Across the Sea*). "My employers are... out of this world" must keep both meanings (*P = NP*). "Operate them with our own personnel" must cover both commanding and piloting (*The Helpers*).
- Keep the Federation's lines cryptic. Its people deflect rather than explain: "Don't think too hard about it" (*The Wraith*), "The how is irrelevant. The what is actionable." (*Shade of Gray*). Don't make them clearer than the source does.
- Some narrators know more than any character, by design: "Her captain never understood what it was." Keep these exactly. A few passages leak knowledge a character shouldn't have; translate them as written and flag them, but never extend a leak anywhere new.
- Some stories avoid a word altogether. *Ex Mero Mutu* never says "Federation"; keep it absent.

## Emotional register

- Restraint at the moment of violence and loss. A death often gets one line or a subordinate clause ("Harrison closed his eyes."). Translate it at the same length, and don't add a reaction the source didn't write.
- Some stories let grief out afterwards, openly, as at the memorial in *Knock Knock*. That is the source's choice, and it stays as written.
- Awe is carried by negation and comparison rather than superlatives: "No engine whine. No afterburner flare. Just tracking perfection." Keep the shape of the negation; don't trade it for an adjective.
- Understatement is the main counterweight: "It's ugly, Chief, but it works." A translation that makes such a line more explicit or more emphatic has broken it.
- Don't add intensifiers, exclamation marks, or emotion words, and don't remove the ones that are there.

## Humor

Humor is dry, deadpan, and usually in dialogue. Federation people and AIs get the driest lines, soldiers and junior characters banter, and officials use irony. The Ryzak are never funny; they are the butt of dramatic irony.

> "HARBINGER, I've got two birds and one shot at this. Tell me she hasn't got her screens up."

> "Unknown. Recommend you find out, Captain."

- Keep the punchline where the source puts it: last in the line, the paragraph, or the scene. Rearrange syntax if you must, but the turn comes at the end.
- Don't explain a joke, and don't add one.
- For wordplay, find an equivalent that does the same job in the same place. If nothing works, translate the plain meaning and flag the loss. The per-story notes list the known puns.
- Running jokes are worded identically every time, and so are the moments when a joke is pointedly withheld ("Nobody said the joke.").

## Rhythm

- Paragraphs map one to one. Never merge or split them, and keep one-line paragraphs as one-line paragraphs. They are structural: they land beats, close scenes, and pace countdowns.
- Keep fragments as fragments, even where the target language prefers full sentences: "Simple. Brutal. Effective."
- Keep the recurring shapes intact, with the same number of beats:
  - triplets ("Six aliens. Fifteen seconds. Done.");
  - negation ladders ("Not jammed. Not suppressed. *Erased*.");
  - "No X. No Y. Just Z.";
  - the one-line closer, often opening with "And" or "But" ("And so it began.").
- Countdowns and readouts stay one item per line.
- Long cumulative sentences that end on a sting keep the sting last: "...and her daughter, fifteen and no fool, would not believe her, and would be right not to."
- Deliberate repetition is part of the design: "unremarkable" in *Shade of Gray*, "The math was brutal." in *Knock Knock*. Choose one rendering for each repeated word or phrase and hold it; don't vary it for elegance.
- Some stories lean on stock gestures (smirks, racing minds). Translate them, but don't add more.

## Voices

English separates voices largely through contractions. AIs, the Ryzak, adversaries, and politicians rarely use them; soldiers and civilians always do. Where the target language has no contractions, carry the contrast with formality, fuller syntax, and word choice. The gap between a clipped AI and a joking sergeant must stay audible.

### The Federation's people

They are terse, aphoristic, and a little smug ("You give it intent, not orders."), and they let silence do the work. Keep their lines short and unexplained.

### AIs

Each has its own voice; keep them distinct.

- HARBINGER uses no contractions and speaks in clipped, absolute statements and colon-labelled readouts: "Situation assessment: critical. Probability of successful defense without additional assets: twelve percent." It can turn to steel ("You observed. There is a difference."). It is courteous and faintly amused in *Ex Mero Mutu*, cold in *The Helpers*, and bureaucratic in *David v Goliath* ("This interaction is concluded."). Its self-introduction, "I am HARBINGER.", is worded identically wherever it appears.
- SUNTZU is telegraphic, dropping articles and subjects ("Fully operational. Can take defensive position immediately."), and speaks in aphorisms. In languages without articles, find another clipped register.
- CIPHER talks like a terse operator.
- Shade (*Shade of Gray*) is clinical and genderless, and spells numbers out ("Seven point four gravities."). It switches from "Agent Comey" to "Marisa" once, at the climax; keep the switch.
- Hermes and Tsel (the Wraith series) are dry and precise: "That is not inaccurate, Captain." Tsel's italic dialogue means it is speaking Hebrew; keep the italics.
- Nue (*Silent Watchers*) is feminine, formal, and teasing, with an archaic servant register: "What is your will, Mistress Nishi?"
- Ember and the *Talon* cockpit voice (*Flight of Icari*) give neutral status reports.
- AI precision is literal. Spelled-out figures stay spelled out to the last digit: "twenty-point-one-one-two-eight-seven-nine seconds".

### Aliens

Aliens think like humans; their diction and physiology set them apart.

- The Xenari are polite, measured, and procedural. Their emotions show in bioluminescent markings that follow a color code, so translate the color terms (cyan-green, blue-white, violet-pink, grey-blue) exactly and consistently, and never paraphrase a color into its meaning.
- The Ryzak are imperial and declarative, with few contractions, no profanity, and a vocabulary of contempt ("minor species", "prey", "the weak"). Predator imagery runs through their scenes: "Earth will burn, or it will kneel. Either outcome is acceptable."
- Kryllians are formal, literal, and deadpan, and address humans by species and job: "human engineer Campbell". Keep that form, with grammatical agreement in languages that need it.
- Alien imperatives are bare and formal: "Elaborate." "Clarify." "Explain."
- Alien names and words keep their exact spelling, apostrophes and hyphens included: Vael'thi, Ish'kai, Taa'Sho-Vel.

### Humans

- Officers give clipped orders and use rank plus surname, "sir", and "ma'am". Generals among themselves use first names.
- Politicians are formal and rhetorical. Real politicians are written with their recognizable verbal habits, such as the repetitions and superlatives in Trump's lines. Those habits are the characterization and must survive.
- Spies are aphoristic and wry.
- Civilians are plain and colloquial. In *The Helpers* the plot depends on it: the formal commands fail, and "Hey. You. Move this pallet over there." works.
- Non-native speakers and accents are shown through syntax ("You are unharmed?", "Then let us dance", "with same protection"), through regional voice (the Texan, Australian, and RAF pilots of Shield flight in *Across the Sea*), or through a plain tag ("in accented English"). Recreate them with target-language means. Non-native grammar stays non-native, and regional speech gets a regional or social marker; don't flatten either into standard speech.

### Forms of address

- Rank plus surname is the default. First names mark intimacy or crisis, and the switch is deliberate (*Executive Authority*, *Shade of Gray*).
- In languages with a formal and an informal "you", decide each relationship's default deliberately, and change it only where the source shifts to first names.
- Render ranks and "sir" or "ma'am" with the target military's natural forms of address. Don't layer on honorifics or polite registers the scene doesn't call for. The Japanese characters in *Silent Watchers* use none, and *The Helpers* has a single "Tanaka-san".

### Profanity

Match the strength exactly. Mild swearing is the norm ("hell", "damn", "bastards"). Stronger words are rare and placed for effect, like the single f-word in *Knock Knock*'s "Knock-knock, motherfuckers." Write swearing out where the source writes it out. Where the source only reports it ("swore under his breath in German"), keep it reported. Censorship inside the story stays too: the bleep in *David v Goliath*'s broadcast is part of the scene.

### Radio and comms

- Keep the shape of the procedure. The station being called comes first, then the caller ("Overwatch, Hartfield."). Commanders are "Actual". Keep acknowledgments such as "Copy", "Roger", and "Say again", and sign-offs such as "Webb out".
- Keep NATO brevity codes, the NATO phonetic alphabet, and callsigns in English: fox three, splash, winchester, RTB, Talon Lead, Gaza One Actual, Shield One. That is how real multinational aviation uses them.
- Translate the rest of radio speech, keeping it clipped. Numbers read digit by digit stay digit by digit: "heading two-seven-zero".

## Terminology

The [glossary](glossary.md) defines the setting's core terms. Settle each term's rendering once per language, record it, and use it everywhere. Where the stories vary a term's spelling or casing (Q-cars against Q-Car, ICE-pick against ICE Pick), follow the story in front of you and treat the variants as one entry in your term list.

### Never translate

- Designations, character for character: VSX-7, MMT-4, TDT-1/K, RSK-5/M, RTK-E Mk.I.
- Named AIs, always in capitals: HARBINGER, CIPHER, SUNTZU, ARCHIMEDES. Other AI names stay as written too: Shade, Hermes, Tsel, Nue, Ember.
- Codenames written in capitals: FLYCATCHER, COLD FORGE.
- Callsigns, brevity codes, and the phonetic alphabet (see Radio and comms).
- Classification markings: TOP SECRET, NOFORN, COSMIC TOP SECRET.
- Latin: "Semper Inter Astra", the title *Ex Mero Mutu*, and the "Icari" of *Flight of Icari*. Translate only the glosses the source itself provides, such as "Always Among the Stars". For that motto, choose a gloss whose first word can stand alone, because *Knock Knock* echoes it as a bare "Always."
- Names and words in alien languages, spelled exactly.
- Text that the source writes in another language or script (see Foreign-language material).

### Keep in English, adapted only to the target script

- Federation equipment code names: *Talon*, *Landmate*, *Wraith*, *Goliath*, *Knightmare*, *Scorpion*, *Dragon*, *Aeon*, *Aurora*, *Stiletto*, *Hornet*, *Whisperglass*, *Guardian*, *Flycatcher*, *Broadsword*, and the rest of the glossary's equipment entries. They are proper names, and every nation in the stories uses them unchanged. In a non-Latin script, transliterate each once and fix it. For Japanese, ランドメイト is already established through *Appleseed*, which *Angels in Armor* and *The Helpers* both cite.
- Reporting names the Federation gives alien hardware, such as *Anvil* and *Rapier* in *The Adequate Machine*. The lecture explains they are short words chosen to be shouted over a radio, like NATO reporting names, which also stay in English.
- Names of Federation and other human ships: FSS *Broadsword*, ESF *Cormorant*, *Lord Cardigan*, *Gallipoli*, *Agincourt*. A ship keeps its name as spelled, even where the target language spells the namesake differently.
- In a gendered language, assign each kept name a grammatical gender once and record it.

### Translate once, and record the rendering

- Ordinary technology and military terms: shields, warp drive, point defense, railgun, jump drive, stargate, dropship. Use the target language's established science-fiction and military vocabulary.
- Terms borrowed from games. Cynosural field, cyno, jump bridge, on-grid, and the ALIGN and Warp to interface labels come from *EVE Online*; thermal clips echo *Mass Effect*. Where the game has an official localization in the target language, use its terms; otherwise keep the English.
- Names that people give Federation machines without knowing what they are:
  - Golems (IDF soldiers);
  - "the big men" (children);
  - "angels in armor" (a Gaza elder);
  - *Ashab al-Samt* (Hamas; keep the transliteration and translate its gloss);
  - "Guardian Angels".

  Each community's name stays distinct, and none of them collapses into "Landmate". Golem is the legend's name; spell it the way the target language spells the legend.
- Non-human names given as meaningful English: Ryzak hulls such as *Devourer's Pride*, *Bone Harvest*, and *Wrath of Dominion*, the Xenari frame *Admonisher*, and the freighter *Galara's Hope*. These are English renderings of names in other languages, so translate them for meaning and keep their menace or warmth. Where a heading plays on a name ("The Wrath Endures" on *Wrath of Dominion*), keep the two linked. Where the source has two spellings, as with *Stormbreaker* and *Storm Bringer*, keep two names.
- Organizations:
  - "EarthSpace Federation". The name is coined on the page in *The Beginning Is A Delicate Time* ("From Earth to space. EarthSpace."). Recommended: keep "EarthSpace" as a name, translate "Federation", and keep the abbreviation ESF, so that the naming scene still produces the word. Record the choice.
  - CONCORD. Keep the acronym and translate its expansion.
  - Real organizations and agencies. Use the target language's established names and abbreviations for the UN, NATO, the CIA, Mossad, the JSDF, the PLAN, and so on.
- The calling card. "We Are Watching" is printed on the Federation's card and echoed throughout the archive: "Always watching", "The world is watching", "Welcome, Watcher", the title *Silent Watchers*, and the last lines of several stories. Fix one rendering of the card per language and build every echo from the same verb, so that the reader hears them as one motif. Keep the card's own formatting, a standalone line in italics or bold as the source has it. (The callsign *Watchful 1* stays in English under the callsign rule, so that one echo is lost.)
- The logo: "a wireframe globe encircled by laurels, with two broken swords crossed saltire". Saltire is a heraldic term, so use the target language's heraldic equivalent. The swords' position varies between stories (beneath, behind); translate each occurrence as written.

## Formatting and typography

### Keep exactly

- Markdown structure: heading levels, `>` blockquotes, `---` scene breaks, lists, code fences, backticks (`HARBINGER` is in backticks in some stories), and line breaks, including lines that end in two spaces, which are hard breaks.
- Where dialogue sits. Most newer stories put dialogue in blockquotes, several older ones put it inline in quotation marks, and some mix both. Don't convert in either direction.
- Emphasis, in the same places and nowhere else. Some stories emphasize heavily: *The Cormorant Gambit* uses bold for emphasis, and *Flight of Icari* and *Angels in Armor* use a lot of italics. Others hardly emphasize at all. Match each story.
- All-caps interface text, warnings, and messages, with their brackets and bold: `**[WARNING] ACCELERATION NOT SURVIVABLE**`. Translate the words and keep the shape.
- Each story's dateline format, which varies. *Ex Mero Mutu* and *The Helpers* stack two H3s, *Across the Sea* puts an italic time line under the heading, and *The Beginning Is A Delicate Time* uses ISO-8601 timestamps as headings, which you copy character for character.
- In-world documents (emails, dispatches, transcripts, chat logs, ledgers, social posts). Keep their layout, labels, and line structure, and translate their content.
- Frontmatter. Translate the `title` value only, and leave every other key untouched.

### Localize

- Quotation marks, dashes, ellipses, and the spacing around them, following target-language norms consistently. The source is itself inconsistent (straight and curly quotes; em dashes, en dashes, and spaced hyphens), so its punctuation carries no meaning. Interrupted speech still needs to read as interrupted.
- Dates. Use target-language order and month names, in running text and in datelines. Keep 24-hour military times ("0930 hours") in the target military's equivalent form, and keep time-zone abbreviations (JST, CET).
- Number formatting: decimal and thousands separators.
- Place names. Use target-language exonyms, but follow the source's political choices where it makes them, such as the Ukrainian forms Kyiv and Odesa in *David v Goliath*.

### Don't change

- Units. Metric, imperial, nautical, and Mach all stay as written. Who uses feet and who uses kilometers is characterization, and conversion would break the readouts and the dialogue.
- Whether a number is written in words or in digits.

## Foreign-language material

- Text that the source writes in another language or script stays as written. This covers the Arabic and Hebrew in *Angels in Armor*, the traditional Chinese characters in *Across the Sea* (don't convert them to simplified), the Japanese handle 生霊少女 in *Silent Watchers*, and words such as "Merde", "Achtung", "Meu Deus", and "Slava Ukraini". Translate the glosses the source provides, and don't add glosses it doesn't.
- Speech that the source renders in English with a language tag ("he muttered in rough Russian") goes into the target language and keeps its tag.
- When the target language is the one being quoted, the foreignness disappears. Keep the language tags anyway, because they record which language characters are speaking in the story. Some passages work only because the reader doesn't know the language. Examples are the three-language warning in *Angels in Armor*, the misread Cyrillic in *Shade of Gray*, and LeBouf's French in a French translation. For these, make the smallest change that keeps the scene working, and flag it.

## Real people, places, and conflicts

The stories feature real heads of state, officials, journalists, and agencies, and real conflicts in Gaza, the Taiwan Strait, Ukraine, and Iran.

- Translate without softening or sharpening anything: not the satire of real politicians, not the partisanship of *David v Goliath*, not the even-handedness of *Angels in Armor*, and not individual characters' extremism.
- Loaded terms belong to the characters who use them ("reunification", "century of humiliation", "occupation"). Keep them inside those characters' point of view.
- Some offices, titles, and dates don't match the real world. They are canon; don't correct them.
- The hadith quoted in *Angels in Armor* is invented. Don't attribute it to a real collection or substitute a real one.
- Use the established target-language titles of real works: Iron Maiden's *The Trooper*, Shakespeare, the *Dune* line behind *The Beginning Is A Delicate Time*.

## Titles

Many titles carry a second meaning. Translate each so that both meanings survive where possible. Where one has to go, keep the one the story's ending depends on, and flag the choice.

| Title | What it's doing | Guidance |
|---|---|---|
| *The Beginning Is A Delicate Time* | Alludes to the opening line of *Dune*. | Use the established target-language form of the *Dune* line, if there is one. |
| *The Cormorant Gambit* | The ship's name plus a chess gambit: the crew plays dead as bait. | Keep the ship name; use the target's chess term. |
| *The Wraith* | The covert platform's name. | Keep *Wraith* (see Terminology). |
| *Shade of Gray* | The AI called Shade, the idiom of moral grayness, and LeBouf's graying hair. | Shade stays the AI's name. Prefer the target's idiom for moral gray, and keep the name too if it fits. |
| *Shadows in Tel Aviv* | Tsel is Hebrew for "shadow", and the craft is "Known informally as Shadow". | Use the same word as in Tsel's gloss, "Shadow of the Federation". |
| *Silent Watchers* | The calling card. | Build it from the card's verb. |
| *P = NP* | Notation, and Mira's claim in the story. | Keep as is. |
| *Angels in Armor* | The elder's name for the machines, quoted in the story. | Match the in-text rendering exactly. |
| *Executive Authority* | Legal power, and the question of whose authority actually governs. | Prefer a legal term that holds both. |
| *Adrenaline* | The human response that the story's punchline turns on. | Translate plainly. |
| *Across the Sea* | The Taiwan Strait, literal and figurative. | Translate plainly. |
| *David v Goliath* | The biblical underdog, with a legal or sporting "v". | Use the target's biblical name forms. It doesn't refer to the *Goliath* mech, which never appears. |
| *Ex Mero Mutu* | A Latin legal phrase, "of one's own accord", framing HARBINGER's unprompted offer. *Mutu* is non-standard (usually *motu*). | Keep it in Latin, spelled as it is. |
| *Torchlight* | The freighter's fusion torch turned into a weapon. | Keep the torch image. |
| *Flight of Icari* | The Latin plural of Icarus: the myth of flying too high, applied to pilots who reach orbit and come back. | Keep the Latin plural, even where the target localizes "Icarus". |
| *The Helpers* | The machines, and the Federation behind them. | A word that can mean both people and machines is best. |
| *Knock Knock* | The English knock-knock joke. Its punchline, "Knock-knock, motherfuckers.", comes at the opening salvo, and the knock recurs ("ready to knock back", "Waiting for the knock"). | Choose one target-language knocking sound, ideally one that can open a joke, and use it in the title, the chapter heading, the punchline, and every echo. Keep the punchline's force. |
| *Boundary Layer* | An aerodynamics term, and the edge of the FLYCATCHER field, which the AIs call the "boundary layer". | Use the target's aerodynamic term, in the title and in the dialogue. |
| *The Adequate Machine* | Deliberately underwhelming; the lecture argues that being "strongly average" wins. | Keep it plain. Don't upgrade "adequate". |

Chapter and scene headings pun as well; the per-story notes list them. Where a heading's words recur in the text, translate both identically.

## Per-story notes

### The Beginning Is A Delicate Time

`story-the-beginning.md`, 1947, main line. An origin chronicle in timestamped vignettes: earnest, hopeful, close to Golden Age science fiction.

- Copy the ISO-8601 timestamp headings exactly.
- A folksy 1940s soldier's voice ("Get the egghead first.") plays against a formal, teacherly alien ("Not rules. Protocols.").
- The alien commander's line "Zreth'lar Kon'tak Prot'la Xinit'kha, Seren'vah." stays exactly as written.
- The naming scene must still appear to produce "EarthSpace" (see Terminology).
- Petrov's dropped articles become non-native grammar.
- Early scenes set off dialogue tags with spaced hyphens; use the target's normal convention for dialogue tags.

### The Cormorant Gambit

`story-the-cormorant-gambit.md`, 2019, side story. Pulp space combat in the "humans are the scary species" vein, and meant to be loud.

- Bold is used for emphasis here; keep every instance.
- Dialogue is inline, not in blockquotes.
- The Xenari envoy is formal and anxious. The Ryzak commander holds the "weak" humans in contempt until it's too late.
- "Never—never—bet against the humans." appears twice; word it identically both times.
- "We call it *creative problem-solving*." is the punchline; keep the italics.
- The Encore retells the battle from the Ryzak side; keep its escalating fragments.

### The Wraith

`story-american-wraith.md`, 2021, Wraith series. Cold War-style espionage that turns into a squad procedural. The Federation's agents are eerie, competent, and playful.

- Federation messages are in bold. For "Ask and ye shall receive.", use the target language's established Bible wording in its archaic register. "Prayer" runs through the story as both a literal prayer and a desperate plea.
- The codename Nightingale is part of a pun: "some species only sing at night", and to sing is to inform. Translate the bird so that it matches the codename.
- Keep these echoes identical each time: "Two days", "Someone said a prayer for you", "professional courtesy", and "behind the curtain", including the nested curtain behind the proverbial one.
- Pleading the Fifth is both a heading and a senator's sarcasm.
- Direct thought is in bold in some places and in italics in others; keep each as it is.

### Shade of Gray

`story-shade-of-gray.md`, 2022, Wraith series. An FBI procedural that turns to uncanny dread, then to the sublime, then to melancholy.

- The repetition of "unremarkable", "impossible", and "shouldn't exist" is deliberate. Use one rendering each, held throughout.
- Shade is clinical and genderless (see Voices).
- LeBouf's French shows in his syntax, in his "Merde", and in an accent that thickens under stress.
- The Cyrillic-decoding passage depends on lookalike Latin letters and breaks in Cyrillic-script languages; adapt minimally and flag.
- "This is not a Honda." and the Q-branch and Q-ship exchange are dry jokes; keep them dry.
- The Encore moves into a legal register (admissibility, parallel construction); use the target's legal terms.

### Shadows in Tel Aviv

`story-israeli-wraith.md`, 2022, Wraith series. A grave political parable in which the Federation sits in judgment.

- "You need to do better" is a refrain. Word it identically every time, including in the bold capitals of the verdict.
- Tsel's italic dialogue means Hebrew; keep the italics. Tsel means "shadow", so use the same word in its gloss and in the title.
- "It feels... alien." / "It *is* alien" means strange, not extraterrestrial; the speakers know nothing of aliens.
- Translate the Gaza dossier without softening or sharpening it.

### Silent Watchers

`story-japanese-wraith.md`, 2023, Wraith series. A brisk techno-thriller with an ensemble workplace comedy built around a teasing AI.

- The title takes the calling card's verb.
- Nue's servant register is a joke; keep it archaic.
- The Japanese characters speak idiomatic American English with American references ("quarterback", "a Saturday morning cartoon"). Translate the idiom as idiom; don't exoticize it, and don't add Japanese color the source doesn't have.
- 生霊少女 stays in kanji. Its gloss, "Wraith Girl", links the handle to the Wraith, so keep *Wraith* inside the translated gloss.
- Japanese pop-culture titles (*Kantai Collection*, *Touhou Project*, *Hell Girl*) take their established target-language titles.

### P = NP

`story-p-np.md`, 2024, side story. Playful techno-noir with a hacker femme fatale, snappy fragments, and nerd jokes.

- The computer-science, cryptography, and quantum vocabulary is accurate. Use the target's correct technical terms, and don't simplify.
- The scene titles are puns: "Off-Record Proof", "Collapse Event", "Weighted Collapse", "Postmortem Silence".
- "My employers are... out of this world" keeps both meanings, and Ethan doesn't catch the literal one.
- Mira's "We're watching." uses the calling card's verb.

### Angels in Armor

`story-angels-in-armor.md`, 2024, main line. A documentary-style first-contact thriller: solemn, reverent, heavy with italics and one-line paragraphs.

- Each community's name for the machines stays distinct (see Terminology). "Landmate" itself is coined in the story by a professor citing *Appleseed*.
- The line about God running out of patience passes from the elder to the Iranian contact ("Allah has, indeed, run out of patience.") to HARBINGER. Keep the three wordings parallel.
- "Angels in armor" in the text matches the title.
- Arabic and Hebrew stay in their own scripts; translate the italic English glosses.
- "Peacekeeping" against "peacemaking": use the target's official UN terms.
- The CNN segments are transcripts, with bold speaker labels and stage directions in the present tense; keep the format.
- The hadith is invented, and stays invented.

### Executive Authority

`story-executive-authority.md`, 2024, side story. Slow, literary paranoia about four scientists. It has the most restrained voice in the archive, built on long, controlled sentences.

- Long cumulative sentences end on a sting; keep the sting last.
- The running joke "HARBINGER DID IT." adapts "the butler did it". It needs an idiomatic blame formula, worded identically every time, and its absence is noted on the page ("Nobody said the joke.").
- First names against surnames track how close the scientists are; mirror that in formal and informal address.
- "*You're not wrong ;)*" keeps both the double negative and the emoticon.
- The clothing metaphors ("a taunt wearing an answer's clothes", "a puzzle wearing a costume") are one image family; keep them together.
- These repeat exactly: "*You were close.*", "not unkindly", and the careful difference between "Suspended. Not concluded." and "concluded".
- "Remember Agincourt": use the target's name for the battle (Azincourt in French).

### Adrenaline

`story-adrenaline.md`, 2024, side story. Pulpy "humans are the scary species" fiction told through a young Xenari scientist's eyes. Graphic in its fight scene, deadpan after it.

- Alien speech is clipped and formal ("Elaborate.", "Clarify.", "Explain."). It loosens only when Vireen is emotional.
- Humans are "Terran" in alien narration.
- Keep the pulp temperature and the portentous foreshadowing as written.
- The punchline "Oh right, adrenaline…" lands on the title.

### Across the Sea

`story-across-the-sea.md`, 2025, main line. Slow-burn dread told only through outsiders who never learn who they're facing. Staccato and heavily italicized.

- Captain Lu's slide into treason is treated with sympathy and dignity rather than as villainy. Keep that.
- Shield flight's three pilots have regional voices (Texan, Australian, RAF), including non-standard grammar; recreate them.
- Chinese text stays in traditional characters; translate the one parenthetical gloss.
- The Federation warns PLAAF pilots "in *perfect Cantonese*". Preserve it and flag it.
- The ONI and *oni* pun needs an equivalent, or a flag.
- "Every. Single. Missile. Gone." must match *David v Goliath* exactly.
- The story ends mid-thought; don't add closure.
- The invented PLAN ship names have no canonical Chinese characters. A Chinese translation needs the author's decision first.

### David v Goliath

`story-david-v-goliath.md`, 2025, main line. An underdog war story told from briefing rooms and newsrooms, in longer paragraphs. Openly pro-Ukrainian, ending in uplift.

- HARBINGER is bureaucratic and terse ("Inquiry permitted.") and ends paternal ("Build well.").
- The teenage and meme profanity is strong and stays strong, the broadcast bleep included.
- "Test Strike, Please Ignore" plays on "test post, please ignore".
- The radar operators' jokes ("accelerating like they're late for dinner") stay deadpan.
- "Every. Single. Missile. Gone." must match *Across the Sea* exactly.

### Ex Mero Mutu

`story-ex-mero-mutu.md`, 2025, main line. A sober geopolitical procedural of press rooms, control towers, and briefings.

- The story never says "Federation"; keep the word absent.
- HARBINGER is courteous and faintly amused ("Indeed", "Excellent").
- "I am HARBINGER." matches its other appearances.
- "selected - not invited, *selected*" keeps its self-correction.

### Torchlight

`story-torchlight.md`, 2025, side story. A light-hearted engineering caper aboard a Kryllian-Xenari freighter.

- Kryllians address the humans as "human engineer Campbell" and "human engineer Park". Keep the form, with gender agreement.
- The comedy is Karvanista's literal formality against the humans' casual banter.
- Comms lines are italicized, and the warning prompt is a bold blockquote.
- The Encore retells the strike from the pirate captain's side.

### Flight of Icari

`story-future-flight.md`, 2026, main line. Fast, banter-driven aviation fiction, intercut with paranoid intelligence scenes.

- It has very short paragraphs and heavy italics; keep both.
- Voss gets the last and driest word in most exchanges.
- Chapter titles that pay off in the text ("The Adults' Playground", "Climbing the Ladder") are translated identically in both places.
- The German pilot's stiff "Then let us dance" is called back later; keep both lines identical.
- Keep the format of the `log` code blocks and the interface menu labels.
- Federation characters mention service off-world but never name the Xenari; don't add explanation.

### The Helpers

`story-the-helpers.md`, 2026, main line. An ensemble humanitarian procedural: eerie, then comic, then harrowing, then warm.

- "Operate them with our own personnel" must cover both commanding and piloting; the twist depends on it.
- The command that finally works is blunt and casual; keep it that way.
- *Landmate*, the Federation machine, and *landmate*, the *Appleseed* concept, are told apart by capitalization (see the checklist below).
- Naoko's cockpit panic ("No, no, no, no!!") is the story's one licensed outburst.
- "Waiting." closes scenes, and "a gift we cannot open" recurs.
- HARBINGER is cold here, and never funny.

### Knock Knock

`story-knock-knock.md`, 2027, main line. Earnest, cinematic military science fiction about the Battle of Sol. Restrained at each death, openly sentimental at the memorial.

- For the title and its echoes, see Titles.
- *Lord Cardigan*, Iron Maiden's *The Trooper*, and the heading "Charge of the Light Brigade" form one chain about a doomed charge. Keep the ship name and the song title as they are.
- For SUNTZU's telegraphic aphorisms and HARBINGER's readouts, see Voices.
- The President's verbal habits are the satire.
- The stock phrases recur by design ("The math was brutal.", "hold the line", "picked the wrong planet"). Use one rendering each.
- "Semper Inter Astra" stays in Latin, and the gloss's first word must stand alone as "Always."
- Alien time is measured in "cycles".

### Boundary Layer

`story-boundary-layer.md`, 2027, side story. A short, tight coda to the Battle of Sol, in the archive's newest style.

- The Ryzak captain "never understood what it was". Nothing in the translation may explain it to him.
- The exchange between SUNTZU and HARBINGER runs without speech tags; keep it untagged.
- Precise figures are spelled out in full.
- "Unknown. Recommend you find out, Captain." is the dry close; keep it dry.
- The title term is the one the AIs use in dialogue.

### The Adequate Machine

`story-the-adequate-machine.md`, 2027, main line. A lecture at the CONCORD War College, dry and self-deprecating.

- "Strongly average" is a deliberate oxymoron; don't smooth it.
- *Anvil* and *Rapier* stay in English (see Terminology). *Admonisher* is translated, and the designations RX-4, T-32, and TG-9 stay as written.
- "Quantity has a quality all its own" is a known quotation, left unattributed here; use its established target-language form.
- A Xenari's cyan-green pulse is the closest thing to applause, and the story closes on "It would do."

## Before starting a language

Make these decisions once, record them, and apply them across every story:

1. The rendering of "EarthSpace Federation" and ESF.
2. The calling card, and the verb family behind every "watching" echo.
3. The knocking sound for *Knock Knock*.
4. The grammatical gender of each name kept in English.
5. Pronouns for each AI. HARBINGER and Shade are "it", Nue moves between "it" and "she", and Ember is "her". Where the language forces a gender, use neutral constructions for the genderless ones.
6. The formal or informal default for each recurring relationship.
7. Renderings of non-human names given as English (Ryzak hulls and the like).
8. How to carry distinctions that English makes with capital letters, in scripts that have none: *Landmate* against *landmate* in *The Helpers*, and names "spoken in all capital letters" (HARBINGER in *Angels in Armor*).
9. Quotation-mark, dash, and ellipsis conventions.
10. The story titles.

## Flagging

Translate what's there and report problems separately, never inside the translated text. List each flag with the file, the line, the issue, and what you did about it.

- Inconsistencies, such as a name, rank, date, or number that changes between scenes: keep each as written and flag it. If a character's gender changes between scenes, follow each passage's own gender.
- Plain typos (for example "Massachusettes"): translate the obvious intended meaning and flag it.
- Drafting leftovers addressed to the writer rather than the reader: leave them out and flag them. Two are known: "Here's the continuation of Chapter 1:" in *Shadows in Tel Aviv*, and "The scene would continue, the weight of the decision pressing heavily…" in *Silent Watchers*.
- Empty headings and leftover heading prefixes such as "Scene:": keep them as they are, and flag them.
- Knowledge leaks, where a character knows something they can't: translate them as written, and flag them.
- Factual slips in the source, such as "Eddie's distinctive guitar riff" in *Knock Knock* (Eddie is Iron Maiden's mascot): translate them as written, and flag them.
- Any place where you departed from the source to make a scene work in the target language.
