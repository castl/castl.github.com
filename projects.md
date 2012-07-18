---
layout: page
title: Projects
tagline: What we're working on
group: navigation
---

Methods and Tools for Accelerating Discoveries
---
Systems engineering relies on observation and refinement -- we observe
inefficiencies or usage patterns and refine our systems based on these
observations.  At CASTL we are developing tools to make observation easier via
pattern detection, machine learning, program analysis and runtime monitoring.

* [LiMiT](/limit "LiMiT")


Hybrid Discrete-Continuous Computer Architectures
---
Current technology trends indicate that power- and energy-efficiency will limit
chip throughput in the future. Current solutions to these problems, either in
the way of digital acceleration or parallel execution are very close to reaching
their limits because of fundamental transistor efficiency constraints and
achievable speedup due to sequential regions. A significant departure from
current computing methods is required to carry forward computing advances.

At CASTL, we are improving the energy-efficiency and programmability of a large
class of problems by employing a hybrid discrete-continuous model of computation
instead of the ubiquitous, traditional discrete model of computation. A
fundamental source of inefficiency in computing systems today is that many
real-world continuous problems are artificially mapped on to the discrete
execution model. We will discuss historical reasons for this approach and how
the mismatch limits achievable efficiency and complicates programming. Then,
drawing inspiration from the early analog computers that provided hardware
primitives for continuous operations such as mathematical integration and by
leveraging some features of modern digital implementations, I will discuss how
on-chip analog accelerators combined with digital cores can implement the
proposed hybrid discrete-continuous model and provide execution capabilities
that are superior to either implementation alone.

Protection against Insider Attacks on Hardware
-----
During the design phase of hardware, malicious designers can insert backdoors.
These backdoors can cause hardware to fail on command or leak sensitive
information.  Techniques created in CASTL can prevent these backdoors from being
effective.

Why is this a problem?

I am often asked if hardware backdoors and kill switches are a real threat.
Here is what the Pentagon/Deputy Secretary of Defense, William Lynn had to say
on this:

"Computer networks themselves are not the only vulnerability. Software and
hardware are at risk of being tampered with even before they are linked together
in an operational system. Rogue code, including so-called logic bombs, which
cause sudden malfunctions, can be inserted into software as it is being
developed. As for hardware, remotely operated "kill switches" and hidden
"backdoors" can be written into the computer chips used by the military,
allowing outside actors to manipulate the systems from afar. The risk of
compromise in the manufacturing process is very real and is perhaps the least
understood cyberthreat. Tampering is almost impossible to detect and even harder
to eradicate. Already, counterfeit hardware has been detected in systems that
the Defense Department has procured. The Pentagon's Trusted Foundries Progam,
which certifies parts produced by microelectronics manufacturers, is a good
start, but it is not a comprehensive solution to the risks to the department's
technological base."
