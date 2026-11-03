# Overview: 02 - Behavior Analysis
# Concepts

The main focus is the experimental analysis of behavior (EAB), which is the basic research arm of behavior analysis. Everything else builds on EAB.

### Basics

If you are not very familiar with behavior analysis, I recommend the following books. Both are "easy reads" for undergraduates, from my recollections as an undergrad fifty some years ago *(no, not re-reading them, so just trust the me of half a century ago)*. 

The books are referenced hundreds, if not thousands of times throughout the EAB and related literature. It would be useful to at least skim both of them. Note that these books are "almost free" as PDFs from the B.F. Skinner Foundation (see links in the linked references):

1. [Skinner, B. F. (1938)](../References.md#skinner-1938). *The Behavior of Organisms: An Experimental Analysis*. The foundational work of the experimental analysis of behavior (EAB). This was probably the first book I read on behavior analysis back when I was an undergrad, and found it to be an easy introduction to EAB, radical behaviorism, and the terminology and concepts that carry through to today (with some exceptions).
2. [Skinner, B. F. (1953)](../References.md#skinner-1953).  *Science and human behavior*. Builds on *The Behavior of Organisms*, adding (as you would expect from the title) humans to the list of organisms. 

### Moving On

I have not read the [Catania](https://www.abainternational.org/constituents/bios/charlescatania.aspx) learning book. But having attended many of his presentations at [ABA](https://www.abainternational.org/welcome.aspx) and read many of his JEAB articles, I am confident in recommending this 2013 book. Good way to span the years from Skinner's old works to today.
- [Catania, A.C. (2013)](../References.md#catania-2013). *Learning, 5th Edition*

### Biological Behaviorism

Also known as "biobehavioral approach", "biobehaviorsm".

This is where this simulation project starts. These works are the foundation.

As far back as [Skinner, B.F. (1938)](../References.md#skinner-1938) (page 454 in PDF, page 422 in hardcover?), Skinner noted (emphasis mine):

 >"What is generally not understood by those interested in establishing neurological bases is that a ***rigorous description at the level of behavior is necessary*** for the demonstration of a neurological correlate. The discovery of ***neurological facts*** may proceed independently of a science of behavior if the facts are directly observed as structural and functional changes in tissue, but before such a fact may be shown to account for a fact of behavior, both must be quantitatively described and shown to correspond in all their properties."
 
 We are not really there yet, but currently in 2026 we do know quite a bit more about neuroscience and about behavior than in 1938. In this simulation project we can ***start*** with ***rigorous descriptions at the level of behavior***, as documented in JEAB and other places. *These descriptions provide a large number of test cases for the simulation software, and will be the primary means of testing whether the simulation has implemented all of the necessary "load bearing" neurological functions for each test case, and for the suite of tests as a whole.*

That is, the ***neurological facts*** are not in and of themselves of interest. They are only of interest in so far that they inform the software architecture, and produce simulations that faithfully replicate the ***rigourous descriptions of behavior***. And in fact, because of the compute limitations of any hardware/software system that might be used, these ***neurological facts*** must be boiled down to the most general, smallest, principled heuristic possible.  [Donahoe, Burgos, and Palmer (1993)](../References.md#donahoe-burgos-palmer-1993) illustrates such a principled heuristic for a basic selectionist simulation based on a ***unified principle of selection***. The neurologic algorithms must be fast/efficient enough to run on affordable hardware, while begin detailed/complex enough to product the desired behavior.

The earliest references to biological behaviorism within behavior analysis literature seem to be in the work of Donahoe, et al. The initial simulations in this project will be based on this literature (and additional works by some of these authors):

1. [Donahoe and Palmer (1989)](../References.md#donahoe-palmer-1989) *The Interpretation of Complex Human Behavior: Some Reactions to Parallel Distributed Processing*. Great article comparing/contrasting behavior analytic and cognitive approaches to complex behavior, and the use of neural nets in modeling behavior. 
2. [Donahoe, Burgos, and Palmer (1993)](../References.md#donahoe-burgos-palmer-1993). *A Selectionist Approach to Reinforcement*. Expansion in great detail of the neural net described in [Donahoe and Palmer (1989)](../References.md#donahoe-palmer-1989).
3. [Donahoe, J. W., Palmer, D. C. (1994)](../References.md#donahoe-palmer-1994). *Complex human behavior*. The first sentence of the preface: "This book draws upon basic biobehavioral processes to provide a conceptually coherent approach to understanding complex human behavior". Is also a good intro to the basics of behavior analysis.
4. [Donahoe, J.W., and Dorsel, V.P. (1997)](../References.md#donahoe-dorsel-1997). *Neural-Network Models of Cognition: Biobehavioral Foundations*. 

The following book *could* be used as an intro to the experimental analysis of behavior (EAB). However, it does incorporate neuroscience throughout. ***Not sure why it never references all of the preceeding work by Donahoe, et al.***:
- [Rasmussen, E. B., Clay, C. J., Pierce, W. D., Cheney, C. D. (2002)](../References.md#rasmussen-clay-pierce-cheney-2022). *Behavior Analysis and Learning: A Biobehavioral Approach.

### Experimental Methodology

This project will use experimental analysis of behavior (EAB) research as test of simulations. Over time as large suite of test replications of EAB experiments will accrete and will be used to test the simulation software at each step to ensure that the simulations are accurate, valid, whatever. 

To understand the simulations, it is probably necessarty to understand EAB research. Here are two classics:
1. [Sidman, M. (1960)](../References.md#sidman-1960). *Tactics of Scientific Research: Evaluating Experimental Data in Psychology*. I worked in [Don Hake's](https://www.abainternational.org/constituents/bios/donhake.aspx) social behavior EAB lab as an undergrad in the late 1970s. One day he essentially said, "ya gotta up your game", and handed this book to me: "Read it". Loved it.
2. [Johnston, J. M., & G. Green (2019)](../References.md#johnston-green-2019). *Strategies and Tactics of Behavioral Research and Practice* (4th ed.). Have *not* read this one. This is an update of the "classic" Johnston & Pennypacker text I am familiar with. Adds a bunch of applied stuff.

# Interbehaviorism

This could be a very big topic in its own right, and I am not really conversant. Most of my exposure was in the early 1980s when I took a theory and philosophy course from Linda Parrott (Hayes). Cloyd Hyten and I had a great time arguing with her, trying to steer her away from the dark side (philosophy) toward the light of empirical experimentation. I got an email from her decades ago saying that she was beginning to do some experimental work while at St. Mary's in Nova Scotia. I never followed up on it.

[José Burgos](./00%20-%20About.md#jose-burgos) is rather philosophical, and I understand he has addressed interbehaviorism directly.  I believe there are experiments out there from an interbehavioral approach. Highly concurrent simulation seems very appropriate.

Most of the early simulation in this project will be based on the early works of John Donahoe and José Burgos. This was largely straight up pretty much straight-up selectionism in the radical behaviorist tradition. So: I'm okay for a while.

For the time being, here is a relatively easy introduction, assuming you are already up to speed on radical behaviorism:
- [Morris, E. K. (1984)](../References.md#morris-1984). Iterbehavioral Psychology and Radical Behaviorism: Some Similarities and Differences. *The Behavior Analyst, 7, 197-204*.]

---

- Previous: [01 - Project Background](./01%20-%20Project%20Background.md)
- Next: [03 - Behavioral Neuroscience](./03%20-%20Behavioral%20Neuroscience.md)

---
[References](../References.md)
