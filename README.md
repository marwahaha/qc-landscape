# Quantum Computing Research Landscape

To the best of my knowledge, this is "what's out there" in cutting-edge quantum computing research.

![Mental map of research areas](./qcmap.svg)

## Experiment & Hardware
There are several competing physical implementations of quantum computers. Superconducting qubits and ion traps are the leading candidates. Boson sampling may provide proof of quantum advantage, but it is not a universal quantum computer. Topological quantum computing, where the surface geometry protects the computer from errors, is still being explored.

## Firmware & Software
Many companies are designing quantum programming languages to operate physical quantum computers. There are also open-source projects where one can construct quantum circuits and visualize expected outputs.

## Noisy Quantum Algorithms
The "Noisy Intermediate-Scale Quantum" (NISQ) machines of the 2020s require new approaches to deal with errors and small circuit depths. The variational technique has become quite popular, alternating between quantum computing and classical optimization. Other algorithms improve machine-learning techniques and approximate solutions to NP-hard problems. There is a rich literature to design quantum error-correcting codes, inspired both by classical error correction and syndrome measurements. See work especially by Eddie Farhi and Aram Harrow.

## Scientific Applications
There are many applications of quantum computing to physics and chemistry. Unknown parameters in Hamiltonians of common molecules can be estimated. Condensed matter systems of increasing size can be directly simulated. Other proposed applications solve matrix inversion problems, simulate quantum electrodynamics, and reconstruct theorized events in quantum gravity. See work especially by Garnet Chan, Birgitta Whaley, Lin Lin, and Nathan Wiebe.

## Long-term Quantum Algorithms
This area is focused on designing new algorithms suitable for large quantum computers. There are numerous ideas applying random walks in a quantum setting, which provide speedups depending on the graph symmetry. Some look at special types of quantum systems that avoid [the sign problem](https://en.wikipedia.org/wiki/Numerical_sign_problem). Others design generic protocols that transform any operator to any other based on its singular values. See work especially by Andrew Childs and András Gilyén.

## Competitive Classical Algorithms
As new quantum algorithms outperform all known alternatives, computer scientists sometimes find better techniques on classical computers. Some quantum algorithms can be "de-quantized", changing the quantum setting to a digital setting and achieving the same runtime. See work especially by Boaz Barak and Ewin Tang.

## Hardness & Complexity Theory
There are many new questions that arise in quantum complexity theory. What problems can quantum computers solve? What can they solve that classical computers cannot? How well can quantum computers approximate NP-hard solutions? Which are the "hardest-to-solve" quantum algorithms? Information about a large number of complexity classes are maintained in the [Complexity Zoo](https://complexityzoo.uwaterloo.ca/). This is a broad and rich field. See work especially by Adam Bouland, Bill Fefferman, Scott Aaronson, Thomas Vidick, Henry Yuen, and Umesh Vazirani.

## Communication & Security
Shor's algorithm allows a quantum computer to break a crucial piece of today's computer systems. What are our alternatives? Can you send long-range, tamper-proof messages using entanglement? This may have applications in other settings, such as blockchain ledgers and voting systems.

## Art & Education
Quantum computing is a booming research industry. The NSF recently funded [an education partnership](https://q12education.org/) designed to inspire and attract youth into this field. Some researchers explore connections from quantum computing to art and mathematics. Others create visual guides and explanations for the public, demystifying the strange and unintuitive nature of quantum physics.

---
Have any feedback? Please [add your comments on GitHub](https://github.com/marwahaha/qc-landscape/issues/new) or [email me](mailto:marwahaha@berkeley.edu).

I created the image above with [diagrams.net](https://www.diagrams.net/). You can view the image [in full-screen here](https://viewer.diagrams.net/#Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fmarwahaha%2Fqc-landscape%2Fmain%2Fqcmap.svg). I make edits [at this link](https://app.diagrams.net/#Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fmarwahaha%2Fqc-landscape%2Fmain%2Fqcmap.drawio).
