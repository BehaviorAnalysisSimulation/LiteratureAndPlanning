- **Author:** Tom Donaldson
- **Email:** tedonaldsn@icloud.com
### Background

This project will be a much delayed continuation of [BASimulation.org](https://basimulation.org). See:
- [About](https://basimulation.org/about/)
- [History](https://basimulation.org/history/)
- [Update: Two Years After (July 2019)](https://basimulation.org/2019/07/10/update-two-years-after/)

As best I can remember, I started playing around with methods for simulating behavior from a behavior analytic perspective a couple of years before moving from Brookings, OR, to Morgantown, WV. We moved to Morgantown in May 2013, which gives a starting date of somewhere around 2011.

Initially I tried to come up with reasonable ways to do the simulation ***without*** resorting to artificial neural networks (ANNs). I had a strong bias against ANNs largely because of their mostly a-theoretical kitchen-sink Rube Goldberg approach. Even the ANN version of "reinforcement learning" was actually a-theoretical; it borrowed a single reward notion from the [neuropsychologist Donald Hebb.](https://en.wikipedia.org/wiki/Hebbian_theory) That is about as far as computer science got.

What I was hoping for was something more grounded in broader scientific reality, something faithful to the real-world observations of behavior analysis since the founding of JEAB in 1958. My attempts to design something sufficient that did not rely on ANNs failed. Everything I tried pointed to the need for something like an ANN. All of my designs ended up converging on ANN-like designs. The basic stumbling block was the need for a system that could accept all of the stimuli available in the environment, and generate some kind of behavior to which the environment could react, and by which resulting changes in environmental stimuli would affect the system to select particular behaviors in response to particular stimulus fields. Something by which the basic behavior change process could be accomplished without encoding specific behaviors a priori.

So I finally did a search of [JEAB](https://onlinelibrary.wiley.com/journal/19383711) for any kind of neural net work, and found [Donahoe, Palmer, and Burgos (1993)](../References.md#donahoe-burgos-palmer-1993), which is probably the place to start in understanding the mechanics of "agent-based" behavioral modeling simulations (see [Railsback & Grimm (2005)](../References.md#railsback-grimm-2005)). An earlier JEAB article, [Donahoe and Palmer (1989)](../References.md#donahoe-palmer-1989), explains the differences between behavioral approaches and the more traditional cognitive/computer-science approaches.

This led me to create the [demo](https://basimulation.org/bgl2015-visualizer/) that I abandoned in July 2019 when I went to work with Julie Smith at [Performance Ally, LLC](https://www.performanceally.com). The demo was entirely "hard-coded". I had started expanding it into something more flexible and configurable before I went to work with Julie. While I will not be using this code, for a variety of reasons, this blog posting illustrates the direction of travel:
- [Update: Two Years After](https://basimulation.org/2019/07/10/update-two-years-after/)
### Starting Over: May 2026

As I originally writing this in mid-March, 2026. I was winding down my involvement in Performance Ally, LLC. Just a few cleanup tasks to complete, and a few more meetings to attend. My last day: Friday 8 May 2026 (which ended up being 15 June instead).

Then I restart my BASimulation activities. From scratch. Clean-room.

The old demo code is worthless. Its intent was very simply to help me visualize what was happening in the ANN described by José Burgos. The class based architecture worked well for that purpose, but cannot be scaled. The old version of Swift would be a lot of work to convert to the current version, even if the code were useful. The Apple ecosystem has changed dramatically, and some of what I created "back when" is no longer at all applicable.

"Starting over" was further delayed by the need to address health issues. Getting old is not for the feint of heart. So the starting over date is more like October 2026. 

---

- Previous: [00 - About](./00%20-%20About.md)
- Next: [02 - Behavior Analysis](./02%20-%20Behavior%20Analysis.md)
