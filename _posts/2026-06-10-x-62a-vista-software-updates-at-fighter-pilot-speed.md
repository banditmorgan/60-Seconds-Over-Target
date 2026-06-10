---
layout: post
title: "X-62A VISTA: Software Updates at Fighter Pilot Speed"
date: 2026-06-10 02:03:47 +0000
---

Between sorties, most fighter jets get fuel, weapons, and a quick inspection. The X-62A VISTA got something else: over 100,000 lines of flight-critical software changes across 21 test flights. The jet that proved AI could dogfight also proved something harder—that the AI could be rewritten, retested, and reflown faster than any traditional certification process would allow.

This wasn't about the dogfight. It was about the turnaround.


<figure style="text-align:center; margin:1.5em 0;">
  <img src="{{ "/assets/images/x-62a-vista-software-updates-at-fighter-pilot-speed/1-1000w_q95.jpg" | relative_url }}" alt="X-62A VISTA flies over Edwards AFB" style="max-width:60%; max-height:480px; height:auto; width:auto; border-radius:4px;" />
</figure>

## The Testbed

The X-62A VISTA is an experimental aircraft derived from the F-16D Fighting Falcon, modified as a joint venture between General Dynamics and Calspan for the U.S. Air Force. Operated by the U.S. Air Force Test Pilot School and maintained by Calspan at Edwards Air Force Base, it was redesignated X-62A in June 2021 as part of an upgrade with a System for Autonomous Control of Simulation (SACS).

The redesignation wasn't ceremonial. At the heart of the SACS system is the Skunk Works Enterprise-wide Open Systems Architecture (E-OSA) which powers the Enterprise Mission Computer version 2 (EMC2)—the "Einstein Box." These updates enhance VISTA's capabilities while maintaining its rapid-prototyping advantage, allowing for quick changes to software and the ability to conduct flight tests with great frequency.

That architecture mattered. Traditional flight-critical software certification is a grinding, months-long process of verification, validation, and regulatory review. Scenario-based testing dominates, and this approach makes up a significant portion of the software development costs for modern aircraft. The X-62A's open architecture allowed the team to bypass none of that rigor—but compress the timeline radically.

## December 2022: The First Sprint

In less than three years, AI algorithms developed under DARPA's Air Combat Evolution (ACE) program progressed from controlling simulated F-16s on computer screens to controlling an actual F-16 in flight, with ACE developers uploading their AI software into the X-62A at Edwards in early December 2022.

The X-62A was flown by an AI-driven autonomy agent for more than 17 hours across 12 flight tests conducted in December 2022. AI agents autonomously flew the X-62A while executing advanced fighter maneuvers, with beyond-visual-range engagements and within-visual-range dogfighting scenarios flown under different autonomy architectures, sometimes with software swapped between sorties in a matter of minutes.

Read that again: *between sorties*. Not between test phases. Between flights.

The brief verified that a total of 21 test flights were conducted between December 2022 and September 2023, spanning the initial ACE tests and subsequent work. Across that campaign, the software wasn't static. It was learning—and being rewritten—on the flight line.

## What 100,000 Lines Means

Flight-critical software is code where failure can kill. Safety-critical software needs to be tested under all foreseeable conditions, including normal operation, edge cases, and potential failure scenarios. Changing it isn't a matter of pushing a Git commit. Every modification must be traced, verified, and validated.

The X-62A team made over 100,000 lines of those changes across 21 flights. That's not 100,000 lines of total code—it's 100,000 lines of *changes*: additions, deletions, rewrites to the autonomy agents flying the jet. The AI wasn't just being tested. It was being taught, iteratively, in the only classroom that matters for a fighter: the air.

This is the opposite of how military aviation usually works. A new flight control law might take years to certify. A software update to an operational fighter can require months of lab testing before it touches hardware. The X-62A collapsed that cycle because it was purpose-built to do so—and because the test team, including the Air Force Research Laboratory, the U.S. Air Force Test Center, and DARPA, accepted the risk that comes with a testbed designed to be pushed.

## The Real Breakthrough

DARPA's Air Combat Evolution program achieved the first-ever in-air tests of AI algorithms autonomously flying an F-16 against a human-piloted F-16 in within-visual-range combat scenarios. That made headlines. But the headline missed the point.

The breakthrough wasn't that the AI could dogfight. It was that the AI could *learn* to dogfight faster than any human training pipeline—because the X-62A became its own classroom. A fighter pilot takes years to build the experience base for advanced tactics. The X-62A's AI agents iterated across 21 flights in nine months, with the software rewritten between sorties based on what the last flight revealed.

The DARPA ACE program aims to garner trust in combat autonomy by proving that AI-controlled aircraft can successfully engage in dogfighting in a safe and reliable way through human-machine collaboration. Trust isn't built in simulation. It's built when a safety pilot sits in the back seat, watches the AI fly, and doesn't touch the override. The X-62A is flown with safety pilots onboard with the independent ability to disengage the AI agent, but the test pilots did not have to activate the safety switch at any point during the engagements over Edwards AFB.

That's the trust the 100,000 lines bought: not trust that the AI was perfect, but trust that it could be made better, fast enough to matter.

---

## Sources

- https://en.wikipedia.org/wiki/General_Dynamics_X-62_VISTA  
- https://www.airforce-technology.com/projects/vista-x-62a-training-aircraft-usa/  
- https://theaviationist.com/2025/12/19/x-62-mission-systems-upgrade/  
- https://www.prnewswire.com/news-releases/us-air-force-secretary-kendall-flies-in-ai-piloted-x-62a-vista-302135802.html  
- https://www.prnewswire.com/news-releases/vista-x-62-advancing-autonomy-and-changing-the-face-of-air-power-301744440.html  
- https://www.darpa.mil/news/2023/ace-program-transition  
- https://www.afcea.org/signal-media/darpa-partners-cubic-defense-air-combat-evolution-program  
- https://www.darpa.mil/news/2024/ace-ai-aerospace  
- https://aerospaceglobalnews.com/news/lockheed-martin-x-62a-vista-ai-fighter-jets/  
- https://www.researchgate.net/publication/252913910_Verification_Validation_and_Certification_Challenges_for_Adaptive_Flight-Critical_Control_System_Software  
- https://sassofia.com/blog/considerations-related-to-safety-and-certification-of-digital-systems-and-safety-critical-software-within-an-easa-environment/

**Image credits (DVIDS, public domain):**
- X-62A VISTA flies over Edwards AFB — credit: Richard Gonzales — https://www.dvidshub.net/image/8417508/x-62a-vista-flies-over-edwards-afb


---

_This post was drafted with AI assistance from a verified-facts brief, accuracy-checked against credible sources, and reviewed by a human before publication. Images are public-domain DVIDS releases; credits are listed above._
