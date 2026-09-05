---
layout: page
type: codex-item
title: TDT-1 Guardian
permalink: /foundations/land/guardian
category: land
order: 5
---
The _Guardian_, designated TDT-1, is the Federation's point-defense platform, tasked with shooting down missiles, drones, and even artillery and other projectiles. Guardian nodes are capable of operating on their own, but really shine when networked to a coordinator node.

### Guardian battery node
Each Guardian battery is equipped with a long-range and a separate high-resolution radar. The long-range radar provides early detection and tracking, while the short-range high-resolution array provides precise tracking for terminal guidance, capable of accurately tracking even hypersonic warheads and projecting filght paths.

Turrets normally utilize power supplied via umbilicals from the control node, but can also run on internal power cores if a umbilical is not available. If not connected to a control node, they engage only targets in their immediate envelope.

Turrets normally manage their own heat, either by venting coolant (which takes 6-8 seconds to return the gun to full firing condition) or by ejecting their thermal clip and drawing a new one from their magazine of ten (which takes only two seconds to return the gun to firing condition). For reasons of economy, turrets will prefer to throttle their rate of fire first, then prefer venting coolant, and only eject their heat sinks if under pressure to continue engaging.

When networked to a controlling node, each Guardian reports incoming targets and the controller distributes them for engagement based on each turret's area saturation, firing arcs, ammo/power status, cooldown, etc.

#### Battery variants
The batteries can be one of several types, depending on the nature of the anticipated threats, each fielded under its own variant of the TDT-1 designation:
- Railgun batteries (TDT-1/K) fire 2.5 mm tungsten-carbide fletchettes at a significant fraction of lightspeed. They are the longest range, but have the lowest tracking, and can usually fire five shots before reloading, or 25 shots before the thermal clip is saturated and needs to eject.
- Pulse lasers (TDT-1/L) fire X-ray laser bursts microseconds in width, at extremely high powers. They are unaffected by gravity, but atmospheric conditions can hamper them severely, which is somewhat compensated by their high tracking. They can fire five pulses before saturating the termal clip.
- Beam lasers (TDT-1/B) use continuous beams to burn their target, boasting high tracking but short range. They can continue firing for five seconds before overheating.
- Plasma burst turrets (TDT-1/P) occupy a middle ground in terms of range and tracking, are not affected by gravity, and can fire ten bursts before saturating the thermal clip.

### Guardian control node
The Guardian control node serves as the coordinator of the local batteries. Outwardly, it's very much like a 40-foot shipping container, albeit with various high-power connectors and heat vents, and an obviously-armored outer surface. It has its own long-range target detection radar for advance target acquisition.

A single control node can support up to 100 local batteries simultaneously, prioritizing and distributing targets reported by the turrets for engagement.

The control node can support various auxiliary modules, such as extra power units, radars, or coprocessors to improve functionality.

