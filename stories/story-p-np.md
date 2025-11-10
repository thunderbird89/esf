---
layout: story
type: story
line: side
title: P = NP
permalink: /stories/p-np
timeline: 2024-03-19
---
## Off-Record Proof

### Cambridge, Massachusettes

The hotel bar had gone mellow as the evening wound down—just a few knots of conference attendees still loitering over last call drinks, swaying on their stools between conversation and exhaustion. Ethan Walsh stirred his whiskey with the stem of a maraschino cherry, its sugar bleeding into the amber.

Across from him, Mira leaned forward, elbows on the table, the corner of her mouth curved in a lazy grin. Her badge read *Mira Hale, Independent Research Consultant*. Her jacket, slim-cut and nondescript, hung neatly from the chair. She didn't fidget. Ethan liked that about her—so far.

She swirled her own drink without sipping.

> "So. You still think NP-complete problems can't be solved in polynomial time?"

He laughed dryly.

> "I think decades of failed attempts say something. You don't just brute-force millions of combinatoric permutations into submission. The math doesn't let you."

Mira tilted her head.

> "Sure, if you're talking about binary Turing machines."

Ethan narrowed his eyes.

> "As opposed to what?"

She smiled, eyes glinting.

> "Think topological, not symbolic. The key is to stop trying to correct errors: a quantum system will always decohere into pure noise within polynomial time, but you can pick *what* noise it decoheres into by encoding information onto the chaotic attractor, see?"

That stopped him cold. He blinked.

> "No, I don't *see*! What you're saying would mean that quantum computation is vastly more robust than it should be, even maybe at room temperature!"

> "Exactly."

She tapped her phone once. Its screen glowed briefly, then dimmed again.

> "What *did* you think powers my phone here?"

Ethan gawked.

> "That's—no. You're bluffing."

> "Am I?"

> "No commercial processor even breaks 20 stable qubits. Hell, Google's Sycamore barely holds at 50 for a couple microseconds."

Mira tilted her head again.

> "Sycamore's a pocket calculator compared to the stuff *we* build."

Something about her tone made Ethan freeze. The ease with which she said *we*, the insinuation in her grin. It wasn't arrogance. It was pity.

He swallowed hard.

> "Who exactly do you work for?"

She didn't answer, just reached for a napkin and slid it toward him.

> Pick any HTTPS certificate.
> Any server.
> I'll give you the private key.

Ethan stared at the napkin, then at her.

> "You're joking."

> "I'm *offering*."

He hesitated, then pulled out his laptop and typed in a URL at random—his university's email server. He slid it over. Mira barely glanced at the terminal, then tapped a sequence into her phone and waited.

Ten seconds passed. Then another five.

And then his screen lit up: a PEM-formatted block. He copied it, ran an OpenSSL check.

His breath caught.

Valid. It matched.

> "You just—"

She picked up her glass.

> "Factored a 2048-bit RSA modulus in sixteen seconds. Give or take. Polynomial time, Ethan. *P = NP*. It's real. You just needed better toys."

He sat back slowly, skin cold. His heart pounded. His mind raced to implications—communications, finance, defense—

Mira watched him, clearly amused. She chuckled.

> "You're *terrified*. You should be. But don't worry. This isn't going public anytime soon. My employers are... out of this world, but they're quite good at keeping secrets."

> "You're not serious."

Her phone buzzed. She stood, shrugged on her jacket, and tapped the bar twice with her knuckle.

> "Thanks for the drink, Ethan. Sleep well."

> "Wait. Who *are* you?"

She paused at the door, glanced back, and smiled like the moon—cool, indifferent, and impossibly distant.

> "We're watching."

Then she was gone.

Ethan sat frozen, staring at the code block on his screen.

Nothing in his academic training had prepared him for this.

---

## Breakfast Lies

The ballroom smelled of powdered eggs and burnt coffee. Ethan Walsh stood near the back wall, a paper plate sagging in his hand under the weight of rubbery bacon and fruit slices gone translucent. He wasn't hungry.

Across the room, seated at a linen-draped table near the juice dispensers, was Mira.

She looked annoyingly fresh. Same dark jacket, same careless posture, scrolling through her phone as if yesterday hadn't happened—like she hadn't just casually detonated half the foundations of modern cryptography over whiskey and sarcasm.

Ethan hesitated, then crossed the room.

> "Mira."

She looked up.

> "Ethan. Surprised you didn't run screaming into the Charles."

He ignored the jab, pulled out the chair across from her.

> "I slept on it. I still think it was a trick."

Her brow arched.

> "Oh?"

> "I mean, what's easier to believe—that you cracked RSA with magic qubits, or that you somehow spoofed a PEM key and staged a very convincing prank?"

> "I could just be a very talented stage magician."

He leaned in.

> "So prove it again."

Mira's eyes lit up, pleased.

> "You want another miracle?"

> "Not just any. I want you to tamper with a live HTTPS stream. Something people *here* will see. Something verifiable."

She considered him over her coffee.

> "That's not exactly subtle."

> "I'll pick the target."

She gestured.

> "By all means."

Ethan scanned the room. Near the buffet, huddled over a laptop and muttering into his AirPods, was Dr. Richard Langford, keynote speaker and household name in infosec circles. Authored three books on encryption, ran a consultancy firm that advised half of Fortune 500.

> "There. Langford. Whatever page he's on, change it. Something small, something he'd notice but others wouldn't. That way, if you're faking this, we'll know."

Mira smiled, closed her eyes for a moment, then opened them and tapped her phone once.

> "Give it a minute."

They watched Langford. A minute passed. Then two. He blinked at his screen. Paused. Slowly leaned in.

He opened a new tab. Typed in a new address. Reloaded. Frowned. His lips moved—muttering, confused. He clicked something. Then again.

Ethan saw him freeze. Langford stared at his laptop as if it had personally insulted him. His posture shifted—rigid now, alert. He fumbled with his phone and stepped away from the table, talking rapidly into the AirPods.

Ethan turned to Mira.

> "What did you do?"

She shrugged.

> "Swapped the header text on his bank's dashboard to say *'Your funds are no longer secure. Ask Mira why.'* Subtle, like you asked."

> "How are you doing this without setting off every certificate transparency log and alert system on the planet?"

Mira leaned forward, her voice almost gentle.

> "As far as everyone can tell, the certificates are still valid, and all the hashes match. If I copy your door's key and lock up after myself, from the outside can you really tell I was in your house?"

Ethan stared at her, a cold feeling settling behind his eyes.

> "This... this breaks the entire model."

She nodded.

> "Mm. That's the part I find funny."

Langford was pacing now. A conference security staffer moved toward him, concerned.

Ethan looked back at Mira.

> "Why are you showing me this? Why not just stay in the shadows?"

She stood, gathering her things.

> "Sometimes, Ethan, it's fun to remind the firekeepers how much dry wood they're sitting on."

> "Who are you?"

She smiled, stepping away.

> "I already told you. Just a consultant."

Then she was gone, again.

This time, Ethan didn't even pretend to eat.

---

## Collapse Event

The blast wasn't especially loud. Just enough to send the chandeliers trembling and the ceiling tiles into cardiac arrest. Screams erupted before the dust even cleared. Someone shouted in Arabic. Then gunfire. Sharp, surgical. Controlled.

Ethan Walsh dove under a buffet table, heart hammering like a dropped drumline. The smell of cordite hit seconds later. He stayed low, crawled toward the hallway. The lights flickered once—twice—then steadied. Emergency protocols activated in the building's smart system, slamming down security shutters over all external exits.

Someone had planned this.

He rounded a corner, narrowly avoiding a stray bullet. Another scream. Down the corridor, near the speaker prep lounge, he caught sight of a familiar figure crouched over a laptop, bathed in the pale blue glow of cascading terminal windows.

Mira.

He skidded beside her, breathless.

> "What the hell is happening?"

She didn't look up. Her fingers danced across the keyboard. One window showed a sprawling, fractal-like tree of decision branches, each node annotated with abstract glyphs, timestamps, and short bursts of English—*fireteam enters ballroom*, *detonation @ :13*, *Langford dead*, *Walsh dead*, *Walsh alive?*, *unknown variable: Mira (observer bias)*.

> "What is this?"

Still no glance. Her voice was even, cold with concentration.

> "I'm looking for a world where everyone leaves here alive. Quantum computing is helping."

Ethan blinked.

> "*Many worlds*? I thought Copenhagen was the correct interpretation?"

That earned him a dry chuckle.

> "It's like... Dijkstra and A*, okay? Neither is wrong, it's just one is better for this and the other for that."

More typing. A sharp beep. Then silence.

Mira exhaled.

> "Okay, found one—come on!"

She slammed the laptop closed, stood in one smooth motion, and grabbed his wrist.

> "We're going to give probability a little push…"

---

## Trajectory Fixing

They moved fast—Mira half-dragging Ethan through side corridors lined with forgotten coat racks and folding easels. The gunfire was distant now, muffled by drywall and misfortune.

At the stairwell landing, Mira stopped abruptly. Her eyes flicked to the corner mirror, then to the shadow moving along the floor tiles below—a man with a rifle posted at the stairwell turn, watching the entrance with clinical stillness.

Ethan followed her gaze, his stomach dropping.

> "We're trapped."

Mira murmured.

> "No. We're in range."

She turned to Ethan, cupping the side of his face like she was framing a photograph.

> "Okay, listen very carefully. See that balcony gallery? Run across to the ballroom on the other side. Exactly nineteen steps. *Not one more or less.* Got it?"

Ethan blinked.

> "What happens if I take twenty?"

She said it bluntly.

> "Then *I* die. Go."

She shoved him—gently, urgently—and he bolted, shoes slapping marble.

He counted under his breath.

> "One... two... three..."

The gallery stretched longer than it looked, the polished floor littered with conference debris. A posterboard flipped in his slipstream. Somewhere, a woman screamed.

> "Fifteen... sixteen... seventeen..."

He saw the ballroom doors ahead.

> "Eighteen... *nineteen*—"

He dove through.

From behind, a shout—Arabic again—and a burst of gunfire.

The stairwell gunman had turned, weapon up, muzzle already swinging—

—and then his foot hit something.

A bottle. One of those goddamn hotel conference water bottles, knocked over and forgotten. It rolled under his boot with just enough spin to tilt his weight sideways. His ankle twisted. His body pinwheeled.

He fell. Hard.

The rifle clattered from his grip as he tumbled down the stairs, his body finally sprawling at the base, groaning faintly but no longer a threat.

Ethan peeked out, eyes wide.

Mira walked past him calmly, brushing her hair behind one ear.

> "One down."

---

## Steering by Probability

The ballroom doors creaked shut behind them with a deep, final *thunk*. Silence, broken only by distant echoing gunshots and the thin hum of emergency power systems. Somewhere above, the hotel's chandelier groaned as if unsure whether to fall.

Mira dropped to one knee beside a toppled catering table and opened her laptop again. Ethan was already pacing.

> "Okay, *what the hell* just happened?"

She didn't answer immediately. Her fingers moved fast—windows opened, collapsed, recompiled. A visualization returned: a tree of timelines, some dimming, others glowing faintly. Each branch pulsed with a flickering probability overlay.

Ethan approached, still rattled.

> "You told me to take nineteen steps like it was some kind of magic incantation. And then that guy slipped on a bottle that *shouldn't have been there*. Are you seriously telling me this is... quantum timeline manipulation?"

Mira replied calmly.

> "Yes. We're nudging probability space."

She looked up, brushing hair out of her eyes.

> "The world isn't binary, Ethan, not really. It's not one timeline—one chain of cause and effect. Every decision, every atomic flutter, spins off branches. Most fade. Some persist. The trick is knowing *which actions* increase the weight of the timeline you want."

Ethan blinked.

> "You're saying you're... *steering* the universe?"

> "I'm saying we're *selecting* it. Carefully. Like threading a needle at relativistic speeds."

She turned the laptop to face him. The tree diagram glowed, branches labeled with phrases: *7 dead, operator injured* / *25 dead, police breach fails* / *3 wounded, all evac successful*. One branch, brighter than the rest, simply read: *All survive.*

> "This one is still viable. But only if we make the right moves. The bottle? That wasn't luck. You stepping in exactly the right place at the right time gave that branch enough amplitude to crystallize."

Ethan stared.

> "This is... insane."

Mira gave him a dry look.

> "You've *seen* me break RSA in seconds and edit HTTPS in flight. But this is where your brain gives up?"

He opened his mouth, then closed it. Then:

> "You're not just modeling the future... You're *optimizing* it."

> "Exactly. Timelines as a search space. Except instead of cost functions, we work with survivability."

She glanced back at the screen, eyes narrowing.

> "Okay, we're still in range. The next event node's in eight minutes. We need to be near the west service hallway and drop a fire extinguisher at *exactly* 14:03:11."

Ethan stared at her like she was reciting sacred scripture.

> "How the hell do you even *know* all this?"

Mira just smirked.

> "Like I said: quantum computing helps."

She snapped the laptop shut.

---

## Weighted Collapse

They sprinted through the corridor, feet pounding against the carpet muffled under decades of hotel wear. The west service hallway loomed ahead—dim, narrow, and empty, save for the gutted remains of a vending machine and a red fire extinguisher mounted under a faded *In Case of Emergency* placard.

Mira didn't slow. She snatched the extinguisher from its bracket with a grunt, then glanced over the edge of the stairwell's guardrail.

Below, one of the terrorists—lean, focused, weapon at the ready—moved into position, sweeping his aim toward a secondary stairwell exit.

Mira breathed.

> "Now."

She let the extinguisher fall.

The cylinder sailed in a tight arc—gleaming red catching a sliver of emergency light—and struck the gunman *square* on the crown of his head with a wet *crack*.

He crumpled.

Mira muttered, already moving.

> "Two down."

They ducked into one of the side salons—a gaudy meeting room with golden trim and too many chairs—and Mira flipped her laptop open again. Ethan bent over, hands on his knees, panting.

> "You just... *clocked* that guy."

> "With a 35 psi dry chemical suppressor. Very scientific."

Her eyes scanned the tree structure again. Then she squinted at the carpet near the entryway, where a small, broken pastry lay forgotten.

She murmured.

> "Someone dropped a scone here. This is the one where they have someone watching the security cameras, then... *there.*"

She tapped her phone rapidly—thumbs dancing across encrypted command layers invisible to normal networks.

> "Okay. Cameras are now showing us running along Hall C, the one with the green trim and the broken lighting."

Ethan looked up, still catching his breath.

> "You're deepfaking *live* hotel security feeds?"

> "With timestamp fidelity and noise injection. I'm not a *monster*."

She glanced at the screen again. A faint blip blinked in one node—*gunman redirects to corridor C, ETA: 2 min*.

> "Perfect. He's going to spend the next ten minutes hunting ghosts."

She closed her laptop halfway, eyes flicking up.

> "We've bought time. Let's use it."

They moved again. Behind them, the extinguished stairwell was quiet, and somewhere else in the building, a very confused gunman was about to chase a future that no longer existed.

---

## Salon Interlude

The room was still, save for the faint buzz of a dying overhead light and the soft rasp of Mira's laptop fan cooling something no off-the-shelf machine should be running. A faint trace of citrus and burnt coffee lingered from the breakfast service that had occupied this salon hours ago—before the gunmen, before the bottle, before the extinguisher.

Ethan sat on the carpet, back against a faux-Ottoman, staring at Mira like she'd peeled the wallpaper off reality and found circuits behind it.

He said finally.

> "Okay. Explain it to me. Really explain it."

Mira exhaled, keeping her eyes on the tree display as it pruned and recalculated.

> "You already know quantum computers don't deal in ones and zeros. Not really. They work in amplitudes—*fuzzy probabilities*—until measurement collapses them. But here's the part your professors never really leaned into."

She turned the laptop toward him. The visualization was dizzying—a forest of shifting timelines, branches dimming, splitting, brightening again as time moved forward.

> "Because they run on probability space, they aren't just good at *math*. They're good at cause and effect. Not just what *could* happen, but what's *likely* to happen, given what you do."

Ethan frowned.

> "So what, you compute outcomes?"

> "Chains of them. Branches, dependencies, stochastic webs. If you know the conditions well enough—people's behavior, architecture, reaction times, dropped scones—then you can *weight* your actions to nudge the outcome you want."

She tapped one brightening line. *Survivors: 78/78*

> "Say I want everyone in this hotel to survive. That's not deterministic—it's *fragile*. But if I know the probabilities and I act *just so*, I can push the weight of the outcome. Nudge the tree. Increase the amplitude of this timeline. Tip the scales."

Ethan watched the branching structure update—small pulses of data flickering at each node like neurons firing in a dream.

> "To what, like ninety percent?"

> "Closer to ninety-nine-point-nine. But not quite one. *Never* one. There's always entropy. Always some tail event that slips through. But you can box it in. Squeeze it out."

He rubbed his face.

> "So this isn't predicting the future. It's... rigging the dice."

Mira finally looked up, one corner of her mouth lifting.

> "Exactly. We're cheating at probability."

From somewhere beyond the walls, a distant shout echoed—followed by hurried boots and a crash of something metal.

Mira stood, laptop still humming in her hands.

> "Time to rig the next one."

---

## The Final Branch

They reached the elevator bank in a dead sprint, Mira already thumbing a quick command into her phone as they skidded to a halt.

Three elevators. Two dark. One blinking *READY*.

She turned to Ethan, breath shallow but eyes still sharp, the glow of her laptop reflecting in one lens.

> "Okay, this is the last fork. You're taking this elevator—press *Level 4* the moment the doors close."

Ethan looked at her, confused.

> "Wait, *you're* not coming?"

> "No. I need to be seen going to Level 6. I *need* to get caught."

Ethan balked.

> "That's insane."

> "It's necessary. The last gunman—he's up there now. But if I'm on camera heading to 6 and you vanish mid-route, he assumes *I'm* the last loose variable. He takes me, thinks the job's almost done, and starts moving downstairs."

> "And me?"

> "The elevator's going to get stuck between 4 and 5. You'll have ten seconds to pry the doors open. Slip out onto 5, drop down the stairwell to 4. If we've calculated right..."

She glanced down at her laptop one last time. A single bright node blinked:
*Shooter-E.M. intersection @ 17:42:17, status: neutralized (non-lethal)*

> "...you'll bump into him escorting me at the foot of the stairs. You get the element of surprise."

Ethan hesitated, then slowly stepped backward into the elevator. His hand hovered over the button panel.

> "What if the elevator doesn't jam?"

Mira smirked.

> "It will. I've seen the timeline. Button."

He pressed *4*. The doors slid shut with a hydraulic hiss.

Inside, the lights dimmed. Somewhere around floor 4.5, the elevator groaned—and stopped.

Ethan cursed under his breath, wedged his fingers into the seam. With a grunt, he pried the doors apart just wide enough to see the shaft wall—and, below that, the top lip of the fifth floor.

He climbed out, arms shaking, boots scraping steel, and rolled onto the hallway floor just as the power flickered again.

Seconds later, he was descending the stairs, breath slowing, ears tuned for footsteps. He reached the last step of the stairwell onto 4—

—and there they were.

Mira, hands zip-tied, was being marched forward by the last of the attackers. He had a rifle slung low, one hand on her shoulder, the other fumbling with a radio.

He looked up.

Too late.

Ethan crashed into him from above with full momentum—knees and gravity—sending them both sprawling. The rifle clattered across the tile. Mira twisted with him, dropping low and swinging her arms around the gunman's neck, using the tie as a makeshift choke. Ethan grabbed for the man's elbow, wrenching it back and driving a knee into his chest.

It was over in six seconds.

The man stopped struggling.

Mira panted.

> "Well. That's probability steered."

Ethan collapsed against the wall beside her.

> "You planned *all* of that?"

Mira smiled, leaning her head back against the stairwell door.

> "No. I just helped the right future win."

Then she sat in the hallway, breathing quietly, as the distant sound of sirens began to close in.

---

## Postmortem Silence

Blue and red lights painted the shattered glass of the lobby in stuttering color. First responders moved like ghosts through the cordoned building—white gloves, clipped radios, quiet commands. The terrorists were cuffed or bagged. The survivors were shaken, wide-eyed, but intact.

Every single one.

Ethan sat on a stretcher, wrapped in a gray thermal blanket someone had insisted on, answering questions with the precision of someone telling a story *just* plausible enough to be believed.

> "I saw one of them fall down the stairs. Another slipped during a reload—might've hit his head. We ran when we could, locked doors behind us. It was... chaos. You know."

The detective nodded, scribbling notes without looking up.

> "But you didn't engage any of the suspects directly?"

> "No. I mean, not until the end. That was just instinct. Adrenaline."

He gestured toward the corridor where Mira was finishing up her own debrief under the soft, paternal scrutiny of another officer.

She looked different now. Shoulders slightly hunched. Hair out of place. Dirt streaked across her blouse, voice quivering just *enough*.

> "I'm just an independent software consultant. I was in a side room the whole time until I got caught. I didn't... I don't really *know* how it all happened. I think I heard someone fall. I thought I was going to die."

She hugged her own arms, eyes glassy. The officer nodded sympathetically, jotting something down.

Eventually, the questioning ended. The officer closed his notebook and gave her a nod.

> "Unbelievable that everyone made it out."

Mira offered a tired smile.

> "I guess we must be lucky. Or they must have been *terribly* unlucky this time."

She shrugged.

The officer gave a quiet "Mm" and walked away, still chewing over the logistics in his head. It didn't add up. Multiple coordinated shooters neutralized without a single fatality. No clear pattern, no heroes, no explanation that fit cleanly into his report.

But he wasn't about to press a traumatized civilian consultant. Not tonight.

Mira crossed the lobby to where Ethan sat. She didn't say anything until she'd double-checked no one was close.

She murmured.

> "All nodes resolved. Zero fatalities."

Ethan looked at her.

> "You do this often?"

She gave him a sidelong look, then tapped her temple.

> "Only when the stakes are worth it."

Then she walked past him toward the waiting EMTs, her expression distant, unreadable—like she was already watching the next branching future.

---

## Epilogue: Echoes in Ink

The police tape flapped gently in the breeze outside the hotel's glass facade, now webbed with bullet cracks and cordoned from the waking world. EMTs bustled, statements were signed, and the press began to crowd behind barricades like vultures circling something they couldn't quite see.

Ethan stepped out into the cool air, the thermal blanket still draped around his shoulders. His adrenaline had burned off, leaving a strange, weightless fatigue behind. Relief mingled with disbelief. The night had pressed against the impossible—then somehow pulled back.

As he fumbled in his pocket for his phone, his fingers brushed something that hadn't been there earlier.

Paper.

He pulled it out slowly. Folded, three times. Thick stock. Ink that had faintly bled through.

He opened it.

At first, it was incomprehensible: a tangle of handwritten notation sprawled across the page like a sketch drawn in the middle of a dream. Bra-ket symbols scattered between integrals. Phase-space embeddings alongside error correction terms and decoherence intervals. A faint annotation in the margin, scrawled in tight print:

> *Chaotic attractor chosen post-coherence. Channel noise ≠ failure. Steer the outcome.*

Ethan's heart skipped. He didn't understand most of it—not in the moment—but he didn't have to. His mind leapt back to that night at the bar, Mira's voice still vivid:

> "The key is to stop trying to correct errors: a quantum system will always decohere into pure noise within polynomial time, but you can pick *what* noise it decoheres into by encoding information onto the chaotic attractor, see?"

This... this was a *map* to that thought. Not the key. Not the door. But maybe—just maybe—a blurry photo of the door the lock was on.

His pulse quickened.

It wasn't something he could run. Nobody had 512-qubit platforms. Not yet. But that didn't make it worthless. In the right journals, among the right people, this would ripple for years as people unpacked the mathematics of picking your randomness. Someone would try to build toward it. Maybe many someones.

Ethan folded the page carefully and slid it back into his coat. Then he looked up toward the sky—clear, cloudless, uncaring.

He'd go home. Sleep. Recharge.

And then?

He'd start writing.

Let the world wonder why, at a mid-level security conference in 2024, a string of coincidences led to a theoretical leap in quantum fault tolerance wrapped in the aftermath of a hostage crisis.

Let them *guess* where it came from.

He already knew.

Somewhere, Mira was probably already watching.
