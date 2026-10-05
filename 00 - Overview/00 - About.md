
### The Project

The purpose of the overall project is to develop virtual "insilico-organisms" that behave in accord with the observations of behavior analysis as documented in Skinner's work, **JEAB**, JABA, JVB, JOBM, etc.  

This organism could ultimately be used to test "what if" behavioral scenarios as a cheap, fast, convenient way to test out behavior analytic ideas, procedures, etc. It could also be used in teaching and training. 

There are (more or less) four phases:
1. Informal working literature review: existing SelNet literature (mostly by José Burgos); what's been done/not done; limitations of the purely selectionist simulations; behavioral neuroscience mapping critical "load bearing" neuroscience structure/function to behavior analytic processes, etc. See [Reality Check](./00%20-%20About.md#reality-check) below.
2. Create a software environment for defining organisms, experimental procedures, running experiments, analyzing data. Issues here will be how to simulated the required "load bearing" neural processes efficiently on an affordable computer system (i.e., Apple silicon).
3. Replicate the existing SelNet experiments by Donahoe, Burgos, and others. These will be in [JEAB (Wiley)](https://onlinelibrary.wiley.com/journal/19383711) and in [Behavioural Processes (Elsevier)](https://www.sciencedirect.com/journal/behavioural-processes).
4. Everything else 😂. This includes evolving the system to replicate all the behaviors that SelNet *apparently* cannot address (see [Reality Check](./00%20-%20About.md#reality-check), below).

### This Document Set

1. **Working notes:** They in some way represent my current and changing knowledge regarding topics related to the project. They will change. They will probably often be somewhat incomplete, inconsistent, incorrect, speculative. 
2. **General starting point:** I will try to provide enough information to allow folks from all of the required domains to get a sense of what this project is doing, and to provide them a foothold. See [Interdisciplinary](./00%20-%20About.md#interdisciplinary), below.

I generally keep a work diary of some sort, which is fine for tracing how and why I did something in sequence. Such diaries are not terribly easy to use as a reference. I will probably keep a diary for this project also, but will extract "conclusions" from the diary and organize them in this doc.

<a name="interdisciplinary"></a>
# Interdisciplinary

This project is primarily about behavior analysis, but it is not *just* a behavior analysis project, nor is it just a neuroscience or software development project. 

[Donahoe, Palmer, and Burgos (1993)](../References.md#donahoe-burgos-palmer-1993) refer to this type of analysis/simulation as "biological behaviorism" or "biobehaviorism". This JEAB article is probably the best overview of the nature of the methodology, and where it comes from. Much has changed since its publication.

For a more recent take on "biobehaviorism", see [Rasmussen, Clay, Pierce, and Cheney (2022)](../References.md#rasmussen-clay-pierce-cheney-2022)

Domains:
- [Behavior Analysis](./02%20-%20Behavior%20Analysis.md)
- [Behavioral Neuroscience](03%20-%20Behavioral%20Neuroscience.md)
- [Neuroscience](04%20-%20Neuroscience.md)
- [Software Development](05%20-%20Software%20Development.md)

<a name="reality-check"></a>
# Reality Check

The Donahoe, et al., model focussed on the consequence side of the "three term contingency". It worked well, as far as it went, but has limitations.

Additional features of organisms will have to be added, both neurological and otherwise. 

Critically, it is **NOT** possible to build a usable "naive" simulation ([Railsback & Grimm (2005)](../References.md#railsback-grimm-2005)) for at least two reasons:
1. The neuroscience is not there. Neuroscience text books are FULL of comments to the effect that "much is not known yet" and "this is speculative but ...".
2. Affordable hardware to implement a "naive" simulation does not exist.

The simulation architecture will have to be heuristic, and not just heuristic, but heuristic in a principled way, based on (but not replicating), the underlying organismic processes that give rise to the behavioral phenomena of behavior analysis.

**Load bearing:** the simulation will **NOT** simulate neurologic or other organismic biologic functions except as required to suppport the behavior analytic "load". That is: **NO** neuroscience simulation for the sake of neuroscience.

It should be possible to produce a simulated organism that behaves in accordance with behavior analysis using only principled heuristic neuro-simulations that are justified as critical "load bearing" processes. It should be doable on affordable hardware with the proper vendor supplied low-level software facilities, such as the Apple silicon ecosystem using the Swift programming language.

***The real trick is to figure out what those load bearing structures and function are.***

### 1. SelNet as a starting point

For example, try this prompt with your favorite AI (Google AI Mode does a pretty good job):

***`Critique the limitations of the Donahoe SelNet model in simulating the real-world observations of behavior analysis, especially as documented in JEAB and JABA`***

### 2. Better?

Solving these problems will be very difficult. One possibility is to integrate such as a [model thalamus](https://www.amazon.com/Exploring-Thalamus-S-Murray-Sherman-ebook/dp/B00P2AZAEO), and a [reticular activating system (RAS)](https://en.wikipedia.org/wiki/Reticular_formation), with the Donahoe model. 

Add following prompt to the conversation started above:

***`How might integration of a simulated thalamus, or a simulated reticular activating system (RAS) affect the accuracy and validity of the simulations?`***

### 3. Best?

The system would at this point still have problems. Might Thousand Brains Theory (TBT) help? Try adding one final prompt to the conversation:

***`Might Thousand Brains Theory (TBT) somehow be integrated with the combined SelNet, thalamus, and RAS? If so, what would the impact be?`***

### 4. Is it even practical?

But is it even possible on off the shelf, "inexpensive" computer hardware? Add the following prompt to your conversation:

***`Assuming a strictly Apple ecosystem using the Swift language: how practical would a mouse model including TBT be, and what hardware would be required?`***

# JEAB as the main Driver

JEAB, as an archival journal, presents large numbers of experiments and results covering a very large number of behaviors, concepts. As such, it represents in a clear manner what the insilico organism must do, what tests it must pass. 

In software development there is the practice of "test-first development" in which tests are developed along with the code, or leading code development. *(What we actually called it decades ago was "test driven development", but that name has been co-opted by the "Agile" or "Extreme Programming" folks to means something different with a lot of ritual and rigid processes baked in. Agile is generally not very agile)*

JEAB experiments define the final tests for any major development cycle. When the insilico organism can take part in such an experiment and produce the same results, the development has succeeded for that particular experiment. Of course this is much much more complicated than stated here (e.g., what is meant by "same results", how evaluated?). Each software setup for each experiment is added to the overall suite of tests, and the entire suite must be passed. If modifying the software to get it to pass for one experiment causes failures in other tests: rinse repeat.

### The big single-item bucket list

The above illustrates the scale of the project to produce an artificial organism with a clean and principled architecture that can faithfully reproduce behavior analytically valid behavior. Whatever architecture, the final tests are dictated by JEAB, JABA, etc. Neurological fidelity/simulation is only important so far as it is "load bearing" in producing valid behavior.

This is NOT artificial intelligence (AI). This is behavior simulation. Much more in line with Alan Turing's notion of mimicking behavior than it is with the cognitive psychology (computer science) that came after.

Given that I am 76 at the time of writing (Sept 2026), how far can I get before dementia or death ends me?


---

- Previous: [README.md](../README.md)
- Next: [01 - Project Background](./01%20-%20Project%20Background.md)

---
[References](../References.md)

