- **Author:** Tom Donaldson
- **Email:** tedonaldsn@icloud.com

### The Project

The purpose of the overall project is to develop a virtual "insilico-organism" that behaves in accord with the observations of behavior analysis as documented in Skinner's work, JEAB, JABA, JVB, JOBM, etc.

This organism could ultimately be used to test "what if" behavioral scenarios as a cheap, fast, convenient way to test out behavior analytic ideas, procedures, etc. It could also be used in teaching and training.

### This Document Set

These are my working notes. They in some way represent my current knowledge regarding topics related to the project.

They will change. They will probably be somewhat inconsistent, incorrect, speculative. 

Mostly, these documents are an attempt to record information in a somewhat organized manner that facilitates usage. 

I generally keep a work diary of some sort, which is fine for tracing how and why I did something in sequence. Such diaries are not terribly easy to use as a reference. I will probably keep a diary for this project also, but will extract "conclusions" from the diary and organize them in this doc.

# Interdisciplinary

This is not just a behavior analysis project, nor is it just a neuroscience or software development project. 

[Doahoe, Palmer, and Burgos (1993)](../References.md#donahoe-burgos-palmer-1993) refer to this type of analysis/simulation as "biological behaviorism" or "biobehaviorism". This JEAB article is probably the best overview of the nature of the methodology, and where it comes from. Much has changed since its publication.

- [Behavior Analysis](./02%20-%20Behavior%20Analysis.md)
- [Behavioral Neuroscience](03%20-%20Behavioral%20Neuroscience.md)
- [Neuroscience](04%20-%20Neuroscience.md)
- [Software Development](05%20-%20Software%20Development.md)
# The Reality

Both model building and application/refinement will be intertwined from fairly early on.

Early models will fail often in strange and wonderful ways that must be addressed. For a sampling of known issues, use this prompt with your favorite LLM:
```
Critique the limitations of the Donahoe SelNet model in simulating the real-world observations of behavior analysis, especially as documented in JEAB and JABA
```

Then continue the conversation with this (or similar) prompt:
```
How to solve these issues? Would Thousand Brains Theory help? A model thalamus? Some other model? Combine these models with SelNet? Are they competing models, complementary, unrelated? What combination will produce the most valid behavior?

The intent is to produce valid behavior, not necessarily valid neuroscience simulations. I am looking for principled heuristics that only includes "load bearing" code that will run fast on Apple Silicon.
```

I have tried the above two step conversation in Gemini, Claude, and ChatGPT. Each give reasonable, but different and even contradictory results. Repeated conversations with the same systems often give different (and even contradictory) results. And it could be that everything these probabalistic intraverbal machines says is incorrect in subtle and deceptive ways, even at best.

These so called "AI" systems are primarily useful as super-search systems. The returned results are suggestive, not definitive.

Complex. And that is even before getting to coding issues.

---

- Previous: [README.md](../README.md)
- Next: [02 - Project Background](./01%20-%20Project%20Background.md)
