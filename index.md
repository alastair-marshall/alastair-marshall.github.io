@def title = "Alastair Marshall"

# Biography

I am a PhD student from Scotland who is currently working for [NVision Imaging Technologies GmbH](https://www.nvision-imaging.com/) based in Ulm, Germany. During my time at NVision I've worked on several different projects, but they have all been centred around applying quantum optimal control (QOC) to a variety of different systems.

## My Work

I started off working to develop spin-1 sensing sequences for NV centres in diamond. These enabled [Philipp Vetter](https://scholar.google.com/citations?user=MfM5fuUAAAAJ&hl=en) to do some sensing that was previously impossible. You can read more about this project [here](/Pages/Publications). During this research, I also became interested in noise modelling and noise spectroscopy, especially incorporating noise into optimization algorithms. I'm preparing a small blog post displaying some results that were never possible to publish, [here](Pages/Blog).

My work then moved to molecular crystals, specifically pentacene doped naphthalene, where we implemented closed-loop optimal control for dynamic nuclear polarization for the first time. Overnight optimizations lead to a factor of 3 reduction in the time taken to reach specific polarization goals. We also put time into trying to understand the sequence our algorithm chose. [What the algorithm found looks to be more general than we first thought!](Pages/Publications)

My most recent work has focussed on the para-hydrogen induced polarization (PHIP) of molecules like pyruvate. Because of relaxation pathways that were causing our system to decohere we weren't seeing the signals that we wanted to. To combat that we took some high-field $B_1$ sweep techniques and figured out how to apply them at low-fields. This method has significantly enhanced our polarization levels, and our simple scalable setup can now reach values similar to those [measured at high-field!](Pages/Publications)

<!-- ## My Interests

I am really interested in the control of quantum systems, specifically in the implementation of quantum algorithms (whether that's for sensing or computing or metrology). I've worked a lot with two algorithms, one gradient-based (GRAPE) and one gradient-free (dCRAB) which are very popular in the quantum optimal control community.  -->