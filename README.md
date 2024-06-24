# M525/P622 Quantum Information

## Announcements

## Course information

This course is the first half of a year-long sequence on quantum information and computation given at the Institute for Fundamental Study (IF), Naresuan University, academic year 2024. Thinking back to it, I should have titled this course "Quantum Information Theory" as our focus will be on the mathematical foundations of classical and quantum information inpdendent of the physical systems that carry these information.

The course consists of 30 lectures, 1.5 hours each. The plan is to cover the following topics:
- *Classical probability and information*: review of probability theory and the (weak) law of large number; frequentists' and Bayesian views of probabilities; Shannon entropy and typical sequences
- *Linear algebra and axioms of quantum mechanics*: review of finite-dimensional Hilbert spaces; decompositions of linear operators: the spectral, polar, and singular-value decomposition (SVD), operator space and the Bloch sphere; projective measurements; unitary dynamics
- *Quantum states and entanglement*: ensemble decomposition and density operators; tensor product and the partial trace; superdense coding and quantum teleportation; CHSH inequality; Schmidt decomposition; purification and the Schrödinger-HJW theorem; quantum circuits and graphical tensor calculus
- *Generalized measurements and dynamics*: generalized measurements (POVMs);  no-cloning theorem; the trace distance and fidelity; measurement models and the operator-sum representation of quantum operations; qubit quantum operations; completely-positive trace-preserving (CPTP) maps; graphical representations of superoperators
- *Classical and quantum information theory*: Shannon's source coding theorem, channel coding theorem and its converse; Holevo bound; quantum entropies and typical subspaces; (if time permits) entanglement distillation; quantum channel capacity

## Resources

Main resources

- [Ren] Joseph M. Renes, *Quantum Information Theory: Concepts and Methods*, De Gruyter Oldenbourg, 2022  
- [Pre] John Preskill, Caltech's Ph219 [Quantum Information and Computation lecture notes](http://theory.caltech.edu/~preskill/ph229/) 
- [NC] Michael Nielsen and Isaac Chuang, *Quantum Computation and Quantum Information*, Cambridge University Press, 2000 
- [Bia] Jacob Biamonte,  [Lectures on Quantum Tensor Networks: A pathway to modern diagrammatic reasoning](https://arxiv.org/abs/1912.10049), (see also lectures 1-6 of Matthew Leifer's [PSI 2016/2017 course on quantum foundations](https://pirsa.org/C16043))

Addition resources

- Lower level
  - Stephen Barnett, *Quantum Information* (Oxford Master Series in Physics), Oxford University Press, 2009 
  - Benjamin Schumacher and Michael Westmoreland, *Quantum Processes, Systems, & Information*, Cambridge University Press, 2010
- Alternate perspectives
  - John McGreevy, UCSD's Phys220: [Quantum Information is Physical lecture notes](https://mcgreevy.physics.ucsd.edu/f19/index.html) 
  - Gilad Gour, [Resources of the Quantum World](https://www.arxiv.org/abs/2402.05474)

## Schedule

| Homework |      Date      |                  Topics                  | Video record |         Resources          | Additional resources                                                                                                                                                                                                                                                                                                             |
| :------: | :------------: | :--------------------------------------: | :----------: | :------------------------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|  [HW1](https://github.com/Ninnat/qinfo-1-2024/blob/main/assignments/hw1.pdf) OUT </br> DUE Th Jul 4|   Jun 25 (T)   |  Probability and statistical inference I  |              |           Ren 1            | [Bayesian Versus Orthodox Statistics: Which Side Are You On?](https://web.archive.org/web/20240623025636/https://users.sussex.ac.uk/~dienes/Dienes%202011%20Bayes.pdf), Zoltan Dienes                                                                                                                                                                       |
|          |   Jun 26 (W)   | Probability and statistical inference II |              |                            |                                                                                                                                                                                                                                                                                                                                  |
|          |  Jun 27 (Th)   |         Classical information I          |              |                            | [A Mathematical Theory of Communication](https://people.math.harvard.edu/~ctm/home/text/others/shannon/entropy/entropy.pdf), Claude E. Shannon, 1948 (a paper in which Shannon single-handedly created a new mathematical field by identifying its core questions and solving them all with the fundamental concept of entropy.) |
|          |   Jul 2 (T)    |         Classical information II         |              |                            |                                                                                                                                                                                                                                                                                                                                  |
|       |   Jul 4 (Th)   |             Linear algebra I             |              |            NC 2            |                                                                                                                                                                                                                                                                                                                                  |
|          |   Jul 9 (T)    |            Linear algebra II             |              |                            |                                                                                                                                                                                                                                                                                                                                  |
|          |   Jul 10 (W)   |         Axioms of quantum theory         |              |                            | [Gleason-Type Derivations of the Quantum Probability Rule for Generalized Measurements](https://arxiv.org/abs/quant-ph/0306179), Carlton M. Caves *et al.*, 2004 <br> [Quantum Theory From Five Reasonable Axioms](https://arxiv.org/abs/quant-ph/0101012), Lucien Hardy                                                         |
|          |  Jul 11 (Th)   |               **No class**               |              |                            |                                                                                                                                                                                                                                                                                                                                  |
|          |   Jul 16 (T)   |                  Qubits                  |              |                            |                                                                                                                                                                                                                                                                                                                                  |
|        |  Jul 18 (Th)   |              Mixed states I              |              |     NC 2, Pre 2, Ren 4     |                                                                                                                                                                                                                                                                                                                                  |
|          |   Jul 23 (T)   |             Mixed states II              |              |                            |                                                                                                                                                                                                                                                                                                                                  |
|          |  Jul 25 (Th)   |              Entanglement I              |              |                            |                                                                                                                                                                                                                                                                                                                                  |
|          |   Jul 30 (T)   |             Entanglement II              |              |                            |                                                                                                                                                                                                                                                                                                                                  |
|          |   Jul 31 (W)   |         Quantum circuit model I          |              |        NC 4, Pre 5         |                                                                                                                                                                                                                                                                                                                                  |
|        |   Aug 1 (Th)   |               **No class**               |              |                            |                                                                                                                                                                                                                                                                                                                                  |
|          |   Aug 6 (T)    |         Quantum circuit model II         |              |                            |                                                                                                                                                                                                                                                                                                                                  |
|          |   Aug 8 (Th)   |       Tensor graphical calculus I        |              |           Bia I            |                                                                                                                                                                                                                                                                                                                                  |
|          |   Aug 13 (T)   |       Tensor graphical calculus II       |              |                            |                                                                                                                                                                                                                                                                                                                                  |
|          |   Aug 14 (W)   |        Generalized measurements I        |              |        NC 2, Pre 3         |                                                                                                                                                                                                                                                                                                                                  |
|        |  Aug 15 (Th)   |       Generalized measurements II        |              |                            |                                                                                                                                                                                                                                                                                                                                  |
|          | Aug 17 - Sep 2 |             **Out of town**              |              |                            |                                                                                                                                                                                                                                                                                                                                  |
|          |   Sep 3 (T)    |           Distinguishability I           |              |            NC 9            | [Distinguishability and Accessible Information in Quantum Theory](https://arxiv.org/abs/quant-ph/9601020), Chris Fuchs' PhD thesis                                                                                                                                                                                               |
|          |   Sep 5 (Th)   |          Distinguishability II           |              |                            |                                                                                                                                                                                                                                                                                                                                  |
|          |   Sep 10 (T)   |           Quantum operations I           |              | NC 8, Pre 3, Ren 5, Bia VI |                                                                                                                                                                                                                                                                                                                                  |
|          |   Sep 11 (W)   |          Quantum operations II           |              |                            |                                                                                                                                                                                                                                                                                                                                  |
|          |  Sep 12 (Th)   |          Quantum operations III          |              |                            |                                                                                                                                                                                                                                                                                                                                  |
|          |   Sep 17 (T)   |          Quantum operations IV           |              |                            |                                                                                                                                                                                                                                                                                                                                  |
|          |  Sep 19 (Th)   |             Quantum entropy I            |              |      NC 11,12, Pre 10      | [A mini-introduction to information theory](https://arxiv.org/abs/1805.11965), Edward Witten                                                                                                                                                                                                                                     |
|          |   Sep 24 (T)   |             Quantum entropy II           |              |                            |                                                                                                                                                                                                                                                                                                                                  |
|          |   Sep 25 (W)   |         Oral Exam (**MS only**)          |              |                            |                                                                                                                                                                                                                                                                                                                                  |
|          |  Sep 26 (Th)   |             Quantum entropy III          |              |                            |                                                                                                                                                                                                                                                                                                                                  |
|          |   Oct 1 (T)    |             Quantum entropy IV           |              |                            |                                                                                                                                                                                                                                                                                                                                  |
|          |   Oct 3 (Th)   |             Quantum entropy V            |              |                            |                                                                                                                                                                                                                                                                                                                                  |
|          |   Oct 8 (T)    |             Quantum entropy VI           |              |                            |                                                                                                                                                                                                                                                                                                                                  |
|          |  Oct 10 (Th)   |                                          |              |                            |                                                                                                                                                                                                                                                                                                                                  |

## Grading Scheme

### MS level

- 40% Assignments
- 30% Oral exam (September 25?)
- 30% Term paper (final weeks)

### PhD level

- 60% Assignments
- 20% Term paper (final weeks)
- 20% Oral presentation (final weeks)

For the MS level, I want you to make an account on Wikipedia and write (as a private draft) an article on your chosen topic.

For the PhD level, you should pick a research-level topic or paper that you want to learn, write a 5-to-10-page term paper and gives a 20-to-30-minute talk based on the term paper.

You should discuss with me about the topic of the report; it should at least relates to a topic covered in this course at an appropriate level. Here are some suggestions to get you started:

- Advanced quantum Shannon theory such as the "mother" and "father" protocols
- Applications of entropy to quantum cryptography
- Quantum resource theories
- Quantum Cramér–Rao bound for optimal parameter estimation
- Quantum state or quantum process learning 
- Area laws for entanglement entropy and classical simulation of 1D quantum systems
- No-go theorems in quantum foundations such as the [PBR](https://en.wikipedia.org/wiki/Pusey%E2%80%93Barrett%E2%80%93Rudolph_theorem) theorem, the [Frauchiger-Renner](https://en.wikipedia.org/wiki/Wigner%27s_friend#An_extension_of_the_Wigner's_friend_experiment) theorem, or those related to contextuality   

Scanning the QR code below will bring you to this repository.

<p align="center">
  <img height="300" src="qr-code.png">
</p>
