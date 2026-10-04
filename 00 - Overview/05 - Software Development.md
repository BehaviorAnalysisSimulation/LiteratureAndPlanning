# Development Environment

Work will be done within the Apple ecosystem as much as possible.
### Software

The simulation proper will be developed in the Swift language for performance, safety, and productivity.

Apple products have a variety of processors: CPUs, GPUs, NPUs. Apple APIs such as [Core ML](https://developer.apple.com/documentation/coreml), [MLX](https://mlx-framework.org/#examples), and [Foundation Models Framework](https://developer.apple.com/documentation/foundationmodels/), make them easy to use.

Peripheral software, especially data analysis and offline graphing will likely be done in Python.
### Hardware

Hardware will at least initially be limited to Apple silicon Macs. They are probably the most affordable and easy to use systems for this type of software development, especially with their unified memory architecture.

# Simulation Environment

The organism(s) will "live" within an experimental simulation that will contain one or more environments (e.g., operant chambers, work sites) in which each environment is controlled by one or more state machines, and containing one or more organisms. 

Initially, these will be disembodied organism responding to abstract, virtualized, features/event. Eventually, organisms will be embodied, and interact with their 3D environments via:

1. Custom components (similar to [BASimulation.org Update: Two Years After](https://basimulation.org/2019/07/10/update-two-years-after/)):
	1. Experiment
	2. Environment
	3. State Chart
	4. Organism
	5. Data Capture
	6. Data Display & Analysis
2. Apple ecosystem on M-class processors:
	1. [Swift](https://developer.apple.com/swift/): System/application programming language
	2. [SwiftUI](https://developer.apple.com/swiftui/): GUI framework
	3. [RealityKit](https://developer.apple.com/documentation/realitykit/): 3D rendering engine with physics and animation
	4. [ARKit](https://developer.apple.com/augmented-reality/arkit/): Spatial awareness and environmental tracking
3. Third party products such as
	1. [Reality Composer Pro](https://www.google.com/url?sa=t&source=web&rct=j&opi=89978449&url=https://apps.apple.com/us/app/reality-composer/id1462358802&ved=2ahUKEwim1oHQxKmTAxUGKlkFHX90NqsQFnoECCMQAQ&usg=AOvVaw3dtUkmCEJzkcpqDE0VD6Dd): Scene design and prototyping
	2. xxx

# Software Modeling

The virtual organism will be a "software model" of individual entities, vs a statistical simulation.

This level of modeling has been known as individual-based modeling (IBM), and is more recently known as agent-based modeling (ABM). The following books focus on ecology as an example field, but they generalizes well to other areas such as behavior analysis. The second book builds on the first, and adds implementations in [NetLOGO](https://www.netlogo.org), which will NOT be used in this project but which are valuable as examples of individual/agent based modeling techniques.

- [Grimm & Railsback, 2005](../References.md#grimm-railsback-2005)
- [Grimm & Railsback, 2019](../References.md#grimm-railsback-2019)

The goal is to create a model that behaves in accordance with real-world behavior analysis observations, and which can be used to predict behavior of individuals and groups of individuals in particular situations.

# Development Process

### Model Building Steps

1. Build the basic experimentation environment
2. Develop and validate a simple model:
	1. Create a new version of SelNet
	2. Replicate the simple experiments of Donahoe, Burgos, and others, as documented in JEAB and Behavioural Proceedings.
3. Extend/replace the SelNet model to replicate selected JEAB experiments, to ensure that the model can handle more complex situations. 
4. Continue ad nauseam to the most difficult and complex phenomena documented in JEAB articles.
5. Move on to JEAB, Honig & Staddon, JVM, JABA, JOBM, , etc.

### Application and Refinement

Once the model reliably behaves as behavior analysis says it should, 
1. use it to predict behavioral outcomes in experiments and treatments that have not yet been completed.
2. use it in designing experiments and treatments
3. use it in troubleshooting behavioral issues
4. Add electrical interfaces to control robotic equipment
5. Add electrical interfaces to Med Associates (and others) equipment
6. ???


---

- Previous: []()
- Next: []()

---
[References](../References.md)
