- **Author:** Tom Donaldson
- **Email:** tedonaldsn@icloud.com
### Background

This project will be a much delayed continuation of [BASimulation.org](https://basimulation.org). See:
- [About](https://basimulation.org/about/)
- [History](https://basimulation.org/history/)
- [Update: Two Years After (July 2019)](https://basimulation.org/2019/07/10/update-two-years-after/)

As best I can remember, I started playing around with methods for simulating behavior from a behavior analytic perspective a couple of years before moving from Brookings, OR, to Morgantown, WV. We moved to Morgantown in May 2013, which gives a starting date of somewhere around 2011.

Initially I tried to come up with reasonable ways to do the simulation without resorting to artificial neural networks (ANNs). I had a strong bias against ANNs largely because of their mostly a-theoretical kitchen-sink Rube Goldberg approach. Even the ANN version of "reinforcement learning" was actually a-theoretical; it borrowed a single reward notion from the [neuropsychologist Donald Hebb.](https://en.wikipedia.org/wiki/Hebbian_theory) That is about as far as computer science got.

What I was hoping for was something more grounded in broader scientific reality, something faithful to the real-world observations of behavior analysis since the founding of JEAB in 1958. My attempts to design something sufficient that did not rely on ANNs failed. Everything I tried pointed to the need for something like an ANN. All of my designs ended up converging on ANN-like designs. The basic stumbling block was the need for a system that could accept all of the stimuli available in the environment, and generate some kind of behavior to which the environment could react, and by which changes in environmental stimuli would affect the system to select particular behaviors in response to particular stimulus fields. Something by which the basic behavior change process could be accomplished without encoding specific behaviors a priori.

So I finally did a search of [JEAB](https://onlinelibrary.wiley.com/journal/19383711) for any kind of neural net work, and found Donahoe's work, which I listed in the BASimulation.org pages. This led me to do the demo that I abandoned in July 2019 when I went to work with Julie Smith at [Performance Ally, LLC](https://www.performanceally.com)
See:
- Donahoe, John W., Palmer, David C (1989). [The Interpretation of Complex Human Behavior: Some Reactions to Parallel Distributed Processing](https://onlinelibrary.wiley.com/doi/10.1901/jeab.1989.51-399), Edited by J. L. McClelland, D. E. Rumelhart, and The PDP Research Group. _Journal of the Experimental Analysis of Behavior_, 51, 399-416.
- Donahoe, John W., Burgos, José E, Palmer, David C (1993). [A Selectionist Approach to Reinforcement](https://onlinelibrary.wiley.com/doi/10.1901/jeab.1993.60-17), *Journal of the Experimental Analysis of Behavior*, 60, 17-40.
### Starting Over: May 2026

As I originally writing this in mid-March, 2026. I was winding down my involvement in Performance Ally, LLC. Just a few cleanup tasks to complete, and a few more meetings to attend. My last day: Friday 8 May 2026 (which ended up being 15 June instead).

Then I restart my BASimulation activities. From scratch. Clean-room.

The old demo code is worthless. Its intent was very simply to help me visualize what was happening in the ANN described by José Burgos. The class based architecture worked well for that purpose, but cannot be scaled. The old version of Swift would be a lot of work to convert to the current version, even if the code were useful. The Apple ecosystem has changed dramatically, and some of what I created "back when" is no longer at all applicable.

"Starting over" was further delayed by the need to address health issues. Getting old is not for the feint of heart. So the starting over date is more like September 2026. 

### More Effective and Bio-Plausible

The Donahoe, et al., model focussed on the consequence side of the "three term contingency". It worked well, as far as it went, but has limitations.

For example, try this prompt with your favorite AIs:
```
Critique the limitations of the Donahoe SelNet model in simulating the real-world observations of behavior analysis, especially as documented in JEAB and JABA
```

Solving these problems will be very difficult. One possibility is to integrate such as [Thousand Brains Theory (TBT)](https://www.amazon.com/Thousand-Brains-New-Theory-Intelligence/dp/1541675819), a [model thalamus](https://www.amazon.com/Exploring-Thalamus-S-Murray-Sherman-ebook/dp/B00P2AZAEO), and a [reticular activating system (RAS)](https://en.wikipedia.org/wiki/Reticular_formation), with the Donahoe model. But that is only a first step, and it may cause other problems. *(<-- use this paragraph as a follow-up prompt with your AI in the conversation started above)*

The trick will be to produce an artificial organism with a clean and principled architecture that can faithfully reproduce behavior analytically valid behavior. Whatever architecture, the final tests are dictated by JEAB, JABA, etc. Neurological fidelity/simulation is only important so far as it is "load bearing" in producing valid behavior.

This is NOT artificial intelligence (AI). This is behavior simulation. Much more in line with Alan Turing's notion of mimicking behavior than it is with the cognitive psychology that came after.

Given that I will be nearly 76 at the time of my retirement, how far can I get before dementia or death ends me?

---

- Previous: [00 - About](./00%20-%20About.md)
- Next: [02 - Behavior Analysis](./02%20-%20Behavior%20Analysis.md)
