---
layout: post
title: "The Safety Pilot Who Never Had to Intervene"
date: 2026-06-05 02:24:54 +0000
---

December 1–16, 2022. Edwards Air Force Base. A safety pilot sits in the back seat of the X-62A VISTA, hand hovering over the override switch, watching an AI agent fly the jet through twelve flights of autonomous dogfighting. His job is simple: expect the machine to fail. Be ready to take control the instant the algorithm crosses a line.

The line never gets crossed.

The engagements escalate from defensive maneuvers to offensive, high-aspect, nose-to-nose runs where the aircraft close to 2,000 feet at 1,200 miles per hour. Every instinct honed over years of flight training screams at him to disengage. The AI banks hard. Airspeed spikes. Altitude bleeds. And then—holds. Stabilizes. Recovers. The safety pilots never activate the override switch.

This wasn't a one-off demo flight. Between December 2022 and September 2023, the team conducted 21 test flights, implementing over 100,000 lines of flight-critical software changes. Two AI agents—DARPA's Air Combat Evolution (ACE) and the Air Force Research Laboratory's Autonomous Air Combat Operations (AACO)—each performed different roles: ACE handled within-visual-range dogfighting against simulated adversaries, while AACO executed beyond-visual-range engagements.


<figure style="text-align:center; margin:1.5em 0;">
  <img src="{{ "/assets/images/the-safety-pilot-who-never-had-to-intervene/1-1000w_q95.jpg" | relative_url }}" alt="X-62A VISTA flies over Edwards AFB" style="max-width:60%; max-height:480px; height:auto; width:auto; border-radius:4px;" />
</figure>

## What Makes This Hard

The X-62A VISTA is a heavily modified F-16D developed by Lockheed Martin Skunk Works and Calspan Corporation, redesignated from NF-16D to X-62A in June 2021. Built on an open systems architecture, it can mimic the performance characteristics of other aircraft—a flying laboratory for testing autonomy algorithms in real airframes, not simulators.

The technical challenge wasn't just teaching an AI to pull Gs and track targets. A key problem for manned-unmanned teaming is ensuring autonomy can be trusted to safely operate an aircraft, particularly through the harrowing maneuvers inherent in dogfighting, so the ACE team encoded safety algorithms and iterated flight control software as quickly as within a day. There is currently no pathway to achieve flight certification for an aircraft controlled by machine learning, because ML reasoning can be opaque—impossible to audit the way you would traditional code.

DARPA's ACE program seeks to increase trust in combat autonomy by using human-machine collaborative dogfighting as its challenge problem, implementing methods to measure, calibrate, increase, and predict human trust in combat autonomy performance. The real breakthrough wasn't the algorithm's performance. It was proving to the humans in the cockpit—and the chain of command—that the machine could be trusted not to kill them.


<figure style="text-align:center; margin:1.5em 0;">
  <img src="{{ "/assets/images/the-safety-pilot-who-never-had-to-intervene/2-1000w_q95.jpg" | relative_url }}" alt="X-62A VISTA flies over Edwards AFB" style="max-width:60%; max-height:480px; height:auto; width:auto; border-radius:4px;" />
</figure>

## Why It Matters

The trials mark a signature victory for DARPA's ACE program, which is seeking to increase human trust in autonomous platforms the military services hope to deploy in combat, such as the Air Force's Collaborative Combat Aircraft effort, which could start producing loyal wingman drones that fly and fight alongside manned jets before the end of the decade.

The vision is a pilot managing multiple autonomous aircraft from a single cockpit—a shift from single platform operator to mission commander. ACE creates a hierarchical framework in which higher-level cognitive functions like engagement strategy and target prioritization are performed by a human, while lower-level functions like aircraft maneuver and engagement tactics are left to the autonomous system. But none of that works if the pilot can't let go of the override switch.

Air Force Secretary Frank Kendall put it bluntly: "If a human being is in the loop, you will lose. You can have human supervision, you can watch over what the AI is doing, but if you try to intervene, you're going to lose"—a stark acknowledgment that reaction time, not judgment, may be the limiting factor in future air combat.

The hardest part of teaching AI to fight wasn't the software. It was teaching the pilot not to stop it.


<figure style="text-align:center; margin:1.5em 0;">
  <img src="{{ "/assets/images/the-safety-pilot-who-never-had-to-intervene/3-1000w_q95.jpg" | relative_url }}" alt="X-62A VISTA flies over Edwards AFB" style="max-width:60%; max-height:480px; height:auto; width:auto; border-radius:4px;" />
</figure>

## Sources

- https://theaviationist.com/2024/04/18/ai-flew-x-62-vista-during-dogfight/ — The Aviationist: AI Flew X-62 VISTA During Simulated Dogfight
- https://www.darpa.mil/news-events/2023-02-13 — DARPA: ACE Program's AI Agents Transition from Simulation to Live Flight
- https://www.aerotime.aero/articles/usaf-darpa-x-62a-ai-dogfight — AeroTime: USAF and DARPA conduct first AI vs human dogfights
- https://defensescoop.com/2024/04/17/darpa-ace-ai-dogfighting-flight-tests-f16/ — DefenseScoop: Pentagon takes AI dogfighting to next level
- https://theaviationist.com/2025/12/19/x-62-mission-systems-upgrade/ — The Aviationist: X-62 VISTA Begins Upgrade Program
- https://www.darpa.mil/research/programs/air-combat-evolution — DARPA: ACE Program Overview
- https://breakingdefense.com/2024/04/in-a-world-first-darpa-project-demonstrates-ai-dogfighting-in-real-jet/ — Breaking Defense: DARPA project demonstrates AI dogfighting in real jet
- https://www.lockheedmartin.com/en-us/products/x-62a-vista.html — Lockheed Martin: X-62A VISTA

**Image credits (DVIDS, public domain):**
- X-62A VISTA flies over Edwards AFB — credit: Richard Gonzales — https://www.dvidshub.net/image/8417511/x-62a-vista-flies-over-edwards-afb
- X-62A VISTA flies over Edwards AFB — credit: Richard Gonzales — https://www.dvidshub.net/image/8417495/x-62a-vista-flies-over-edwards-afb
- X-62A VISTA flies over Edwards AFB — credit: Richard Gonzales — https://www.dvidshub.net/image/8417488/x-62a-vista-flies-over-edwards-afb


---

_This post was drafted with AI assistance from a verified-facts brief, accuracy-checked against credible sources, and reviewed by a human before publication. Images are public-domain DVIDS releases; credits are listed above._
