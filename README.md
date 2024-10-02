# M525/P622 Quantum Information

## Announcements

* *16 Aug:* [Here](https://github.com/Ninnat/qinfo-1-2024/blob/main/rubric.pdf) is the grading scheme and the rubric for the MS report. The description of some items are specific to writing a Wikipedia article, but the overall scheme should be the same for the PhD report as well.
* *4 Aug:* The entangled state in P4 of HW3 should be |000⟩-|111⟩/√2.
* *4 Jul:* The due date of HW1 has been moved to Tuesday, July 9th (before midnight).

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

| Homework |      Date      |                  Topics                  | Video record </br> ([playlist](https://www.youtube.com/playlist?list=PLgUEDBpK9d1JlvOfm2XljpfwRX4F5uLEI))|         Resources          | Additional resources                                                                                                                                                                                                                                                                                                             |
| :------: | :------------: | :--------------------------------------: | :----------: | :------------------------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|  [HW1](https://github.com/Ninnat/qinfo-1-2024/blob/main/assignments/hw1.pdf) OUT </br> DUE Th Jul 9|   T Jun 25  |  Course introduction; </br> Probability and statistical inference I  | Video [1](https://www.youtube.com/watch?v=-9R1VAijZXU&list=PLgUEDBpK9d1JlvOfm2XljpfwRX4F5uLEI&index=4&t=2s&pp=iAQB), [2](https://www.youtube.com/watch?v=yZpD9Atn2Xs&list=PLgUEDBpK9d1JlvOfm2XljpfwRX4F5uLEI&index=3&t=6s&pp=iAQB)       |           Ren 1         | [All About that Bayes: Probability, Statistics, and the Quest to Quantify Uncertainty](https://www.youtube.com/watch?v=eDMGDhyDxuY), a talk by Kristin Lennox                                                                                                                                                                       |
|          |   W Jun 26   | Probability and statistical inference II |   [Video](https://www.youtube.com/watch?v=Wr3BwTpUbnk&list=PLgUEDBpK9d1JlvOfm2XljpfwRX4F5uLEI&index=2&pp=iAQB) |      [Probability notes](https://github.com/Ninnat/M897513-stat-mech-2-2565/blob/main/lecture-notes/StatV2.pdf), </br> Caves' [simple Dutch-book argument](https://web.archive.org/web/20190718164043/http://info.phys.unm.edu/~caves/talks/bayesinterp2.pdf)                       |                                                                                                                                                                                                                                                                                                                                  |
|          |  Th Jun 27  |        Probability and statistical inference III          |   [Video](https://www.youtube.com/watch?v=L4N4sc2buHk&list=PLgUEDBpK9d1JlvOfm2XljpfwRX4F5uLEI&index=1&pp=iAQB)           |                       |  |
|          |   T Jul 2   |         Classical information I        |   [Video](https://www.youtube.com/watch?v=GqAE7SVA6KU&list=PLgUEDBpK9d1JlvOfm2XljpfwRX4F5uLEI&index=2&pp=iAQB)      |             NC 11                |   [A Mathematical Theory of Communication](https://people.math.harvard.edu/~ctm/home/text/others/shannon/entropy/entropy.pdf), Claude E. Shannon, 1948 (a paper in which Shannon single-handedly created a new mathematical field by identifying its core questions and solving them all with the fundamental concept of entropy.)                                                                                                           |
|       |   Th Jul 4  |             Classical information II           |  [Video](https://www.youtube.com/watch?v=mev_e-CDPbA&list=PLgUEDBpK9d1JlvOfm2XljpfwRX4F5uLEI&index=1&pp=iAQB)|         [AEP notes](https://github.com/Ninnat/qinfo-1-2024/blob/main/lecture-notes/AEP.pdf)             |                                                                                                                                                                                                                                                                                                                                  |
| [HW2](https://github.com/Ninnat/qinfo-1-2024/blob/main/assignments/hw2.pdf) OUT </br> DUE T Jul 23 | T Jul 9   |    Linear algebra I   |  [Video](https://www.youtube.com/watch?v=55YUnD-DS8M&list=PLgUEDBpK9d1JlvOfm2XljpfwRX4F5uLEI&index=8&pp=iAQB)   |                NC 2              |                                                                                                                                                                                                                                                                                                                                  |
|          |   W Jul 10  |         Linear algebra II        | [Video](https://www.youtube.com/watch?v=dVHHxFRVYNs&list=PLgUEDBpK9d1JlvOfm2XljpfwRX4F5uLEI&index=7&pp=iAQB) |                            |                                                 |
|          |  Th Jul 11  |               **No class**               |              |                            |                                                                                                                                                                                                                                                                                                                                  |
|          |   T Jul 16  |       Axioms of quantum theory; Qubits I      | [Video](https://www.youtube.com/watch?v=XSPIBdlVEkk&list=PLgUEDBpK9d1JlvOfm2XljpfwRX4F5uLEI&index=9&pp=iAQB)            |                            | [Quantum Theory From Five Reasonable Axioms](https://arxiv.org/abs/quant-ph/0101012), Lucien Hardy                                                                                                                                                                                                                                                                                                                                         |
|        |  Th Jul 18  |      Qubits II; Mixed states I     |    [Video](https://www.youtube.com/watch?v=Mvn-yhAtXwg&list=PLgUEDBpK9d1JlvOfm2XljpfwRX4F5uLEI&index=10&pp=iAQB)   |     NC 2, Pre 2, Ren 4     |                                                                                                                                                                                                                                                                                                                                  |
|  [HW3](https://github.com/Ninnat/qinfo-1-2024/blob/main/assignments/hw3.pdf) OUT </br> DUE T Aug 6  |   T Jul 23  |             Mixed states II              | [Video](https://www.youtube.com/watch?v=6uV3tTZeX7c&list=PLgUEDBpK9d1JlvOfm2XljpfwRX4F5uLEI&index=12&pp=iAQB)  |             |   [Gleason-Type Derivations of the Quantum Probability Rule for Generalized Measurements](https://arxiv.org/abs/quant-ph/0306179), Carlton M. Caves *et al.*, 2004                                                                                                                                                                                                                                                                                                                                 |
|          |  Th Jul 25   |              Entanglement I              |   [Video](https://www.youtube.com/watch?v=AxzM2XzRNP4&list=PLgUEDBpK9d1JlvOfm2XljpfwRX4F5uLEI&index=11&pp=iAQB)    |                            |                                                                                                                                                                                                                                                                                                                                  |
|          |   T Jul 30  |             Entanglement II              |   [Video](https://www.youtube.com/watch?v=HYII6TrIXQE&list=PLgUEDBpK9d1JlvOfm2XljpfwRX4F5uLEI&index=13)    |                            |                                                                                                                                                                                                                                                                                                                                  |
|          |   W Jul 31  |         Quantum circuit model I          |  [Video](https://www.youtube.com/watch?v=IAWu8L5nDwY&list=PLgUEDBpK9d1JlvOfm2XljpfwRX4F5uLEI&index=17) |        NC 4, Pre 5         |                                                                                                                                                                                                                                                                                                                                  |
|        |   Th Aug 1  |               **No class**               |              |                            |                                                                                                                                                                                                                                                                                                                                  |
|   [HW4](https://github.com/Ninnat/qinfo-1-2024/blob/main/assignments/hw4.pdf) OUT </br> DUE Th Aug 15       |   T Aug 6   |   HW2 discussion; quantum circuit model II         |  [Video](https://www.youtube.com/watch?v=Zk0SKqSkw44&list=PLgUEDBpK9d1JlvOfm2XljpfwRX4F5uLEI&index=14)    |                            |                                                                                                                                                                                                                                                                                                                                  |
|          |   W Aug 7  |      Generalized measurements I      |   [Video](https://www.youtube.com/watch?v=oMb7tJnyFHE&list=PLgUEDBpK9d1JlvOfm2XljpfwRX4F5uLEI&index=16)   |     NC 2, Pre 3      |      
|          |   Th Aug 8  |      Generalized measurements II      |  [Video](https://www.youtube.com/watch?v=LgjbwlknrsA&list=PLgUEDBpK9d1JlvOfm2XljpfwRX4F5uLEI&index=18)  |                  |                                                                                                                                                                                                                                                                                                                                  |
|          |  T Aug 13  |        Quantum operations I      |  [Video](https://www.youtube.com/watch?v=AtGWsumifQc&list=PLgUEDBpK9d1JlvOfm2XljpfwRX4F5uLEI&index=19)   |    NC 8, Pre 3, Ren 5          |                                                                                                                                                                                                                                                                                                                                  |                                                                                                                                                                                                                                                                                                                       |
|  [HW5a](https://github.com/Ninnat/qinfo-1-2024/blob/main/assignments/hw5a.pdf) OUT </br> DUE T 17 Sep |  Th Aug 15   |      Quantum operations II  (Tensor graphical calculus)       |   [Video](https://www.youtube.com/watch?v=zkJ-HsjaRSg&list=PLgUEDBpK9d1JlvOfm2XljpfwRX4F5uLEI&index=21)       |           Bia I, IV                    |                                                                                                                                                                                                                                                                                                                                  |
|          | Aug 17 - Sep 2 |             **I'm out of town for 2 weeks**              |              |                            |                                                                                                                                                                                                                                                                                                                                  |
|          |   T Sep 3   |     Quantum operations III  (Tensor graphical calculus cont.)  |  [Video](https://www.youtube.com/watch?v=3rU8vublyVY&list=PLgUEDBpK9d1JlvOfm2XljpfwRX4F5uLEI&index=24) |                      |                                                                                                                                                                             |
|  [HW5b](https://github.com/Ninnat/qinfo-1-2024/blob/main/assignments/hw5b.pdf) OUT </br> DUE T 17 Sep|  Th Sep 5   |     Quantum operations IV (Choi's criteria for complete positivity)  |              |                           |                                                                                                                                                                                                                                                                                                                                  |
|          | T Sep 10  |    Quantum operations V (Qubit operations) |  [Video](https://www.youtube.com/watch?v=jLRhQtTtQlY&list=PLgUEDBpK9d1JlvOfm2XljpfwRX4F5uLEI&index=23)  |          |                                                                                                                                                                                                                                                                                                                                  |
|          |  W Sep 11   |   Qubit operations (cont.); distinguishability I     |  [Video](https://www.youtube.com/watch?v=h_NswxrtWug&list=PLgUEDBpK9d1JlvOfm2XljpfwRX4F5uLEI&index=22)   |                 NC 9             |                     [Distinguishability and Accessible Information in Quantum Theory](https://arxiv.org/abs/quant-ph/9601020), Chris Fuchs' PhD thesis                                                                                                                                                                                                                                                                                                                |
|          |  Th Sep 12   |   Distinguishability II   |  [Video](https://www.youtube.com/watch?v=kjb7S7RXD_Q&list=PLgUEDBpK9d1JlvOfm2XljpfwRX4F5uLEI&index=25)  |      |                   |                                                                                                                                                                                                                                                                                                                               |
| [HW6](https://github.com/Ninnat/qinfo-1-2024/blob/main/assignments/hw6.pdf) OUT </br> DUE Th 26 Sep |  T Sep 17   |   Distinguishability III  | |            |                                                                                                                                                                                                                                                                                                                                                              |
|          | Th Sep 19   |      Distinguishability IV     |  [Video](https://www.youtube.com/watch?v=tlAhUYMpHO4&list=PLgUEDBpK9d1JlvOfm2XljpfwRX4F5uLEI&index=26)  |          |                                                                                                                                                                                                                                 |
|          |  T Sep 24   |    Quantum Information I (Entanglement fidelity) |              |   NC 11,12, Pre 10        |     [A mini-introduction to information theory](https://arxiv.org/abs/1805.11965), Edward Witten                                                                                                                                                                                                                                        |
|          |  W Sep 25   |  Quantum Information II |  [Video](https://www.youtube.com/watch?v=wYMthO1_IF4&list=PLgUEDBpK9d1JlvOfm2XljpfwRX4F5uLEI&index=28)  |                            |                                                                                                                                                                                                                                                                                                                                  |
| [HW7](https://github.com/Ninnat/qinfo-1-2024/blob/main/assignments/hw7.pdf) OUT </br> DUE Th 11 Oct |  Th Sep 26   |  Quantum Information III (Schumacher compression) |    [Video](https://www.youtube.com/watch?v=WnLwpXdG6lM&list=PLgUEDBpK9d1JlvOfm2XljpfwRX4F5uLEI&index=29)    |                            |                                                                                                                                                                                                                                                                                                                                  |
|          |   T Oct 1   |  Quantum Information IV |              |                            |                                                                                                                                                                                                                                                                                                                                  |
|          |  Th Oct 3   |  Quantum Information V (Holevo bound) |              |                            |                                                                                                                                                                                                                                                                                                                                  |
|          |  T Oct 8    |                      |              |                            |                                                                                                                                                                                                                                                                                                                                  |
|          | Th Oct 10   |                                          |              |                            |                                                                                                                                                                                                                                                                                                                                  |

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
