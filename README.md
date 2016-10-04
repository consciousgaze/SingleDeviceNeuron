# Single Device Neuron

## Abstract
This is an idea that I had around 3 years ago which I still think is kind of interesting. Considering I am not likely to have the resource to verify it anymore, I hope someone may found this idea interesting too, or even do something to verify it.

If anyone tried this idea and found it work, please let me know and, perhaps, say "thank you" to me. If anyone found that this idea will anyway not work, please help me identify the issue and I will say "thank you" to you :P

## Introduction
Though using [memristors](dfas) to simulate synapses behavoir is not a new idea, I still haven't seen any work to simulate the behavoir of an actual neuron analogously (which was 3 years ago and today :P). Hence, I spent some time exploring this direction, proposed a model and did some simulation with SPICE. 

The circuit design and simulation result is explained in [SingleDeviceNeuron.pdf](fdafdsa). The SPICE code is in [Memristor.cir](fds). Simulation result is stored in [Memristor.out](fdsa) and [Memristor.out.1](dfas) (with different inputs). There are also some other data files which I cannot recall its uage :P. I know this does not sound professional but, come on, it is 3 years ago. Also considering this is the only time I am using SPICE, I consider that I have done a great job.

## Limitations
For anyone who knows the basics of neural dynamics, he will notice that I didnt reproduce the all-or-none behavior. Ya, I failed to reproduced it. During the simulation, I found something else I cannot understand in SPICE (which is mentioned in the report). And hence I stopped diving deeper. Neural dynamics is something hard enough by it alone and I do not want to mess it up here without full understanding of current modell. But I am pretty sure it is a two-dimensional system and the all-or-none behavoir shouldn't be far. But finding proper parameters may not be easy.
