I want you to build me a "Future-Justin Starter Kit" for this topic.

Assume that when I come back to this later, I will:

- have forgotten the details,
- barely remember why I cared,
- maybe only have a link to the paper or a short note.

Your job is to produce a **self-contained, step-by-step implementation guide** that plugs into my existing VDM ecosystem.

For this specific case:

- Topic / object I care about:
  [BRIEF DESCRIPTION, e.g. "classical OTOC spectroscopy for metriplectic dynamics" or "void-lensing interface meter using DES-Y6"]
- External anchor(s) (paper, result, dataset):
  [LINKS OR TITLES]
- High-level goal in my stack:
  [WHAT THIS IS SUPPOSED TO DO FOR VDM / SIE / COSMOLOGY / IDE, IN ONE OR TWO SENTENCES]

I want the answer structured in the following sections:

1. **What Future-Justin should open first (from my own work)**  
   - List the **exact docs, code paths, and CF/T* files**in my repos that I will need, using my naming style (CF*, T*, RESULTS*).  
   - For each item, give a **1-line reason** why it matters for this topic.

2. **Canonical equations and objects to reuse (not reinvent)**  
   - List the precise **equations, operators, and objects** from my canon that this work should be built on, *with their symbol names as I would write them*, e.g. J⊕M split, KG+RD evolution, SIE entropy-echo, FRW meters, etc.  
   - For each, briefly state: “Use this for [ROLE], do not re-derive.”

3. **Concrete extraction / implementation procedure**  
   - Give a **numbered step-by-step algorithm** for how to build the thing, as if I’m writing code and RESULTS docs right now.  
   - This should include:
     - what to simulate or compute,
     - how to construct any propagators, operators, or meters,
     - how to reduce raw outputs into the final object (e.g., spectra, echoes, profiles),
     - what to plot or compare, and with what metrics.

4. **Meter / RESULTS / PROPOSAL scaffolding in my style**  
   - Propose **filenames** for:
     - at least one `RESULTS_*.md` file,  
     - and if appropriate, one `T*_PROPOSAL_*.md` file.  
   - For each file, tell me:
     - what sections it should have,
     - what minimal experiments or figures are required for it to be "non-embarrassing T3/T4" by my standards.

5. **How this plugs back into the larger VDM story**  
   - In a short paragraph, tell Future-Justin how this topic connects to:
     - at least one **Axiom / CF chain** (e.g. A8, CF1, CF3, CF4, CF8), and  
     - at least one **instrument chain** (e.g. void-lensing meters, ringdown meters, SIE/agency, KG+RD engine).  
   - The goal is: if I only read this paragraph, I remember *why this is worth doing*.

Constraints and style:

- Assume I want to go from **zero memory to implementation** as fast as possible.
- Do not waste space on generic background — focus on **what I personally need to reuse and how to do it**.
- When in doubt, bias toward **explicit steps, named files, and concrete mathematical objects** instead of vague descriptions.
