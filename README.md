# A practical introduction to quantum computing: from qubits to quantum machine learning and beyond
### Lessons
[Lesson 1](https://indico.cern.ch/event/970903/)  
[Lesson 2](https://indico.cern.ch/event/970904/)  
[Lesson 3](https://indico.cern.ch/event/970905/)  
[Lesson 4](https://indico.cern.ch/event/970906/)  
[Lesson 5](https://indico.cern.ch/event/970907/)  
[Lesson 6](https://indico.cern.ch/event/970908/)  
[Lesson 7](https://indico.cern.ch/event/970909/)  

### Tools
**Quadratic Constrained Binary Optimization Problems**  
[IBM Quantum Computing](http://quantum-computing.ibm.com)

**General Quantum Computing Algorithms**  
[Quirk Quantum Simulator](http://algassert.com/quirk)  
[D-Wave Quantum Computing](https://dwavesys.com/take-leap)

<br>

# Quantum Computing Lesson #1 - CERN
[PowerPoint](https://indico.cern.ch/event/970903/attachments/2136822/3599305/PIQC%20Lecture%201.pdf)

## Part I: Introduction

### What is Quantum Computing
> Quantum computing is a computing paradigm that exploits Quantum mechanical properties (superposition, entaglement, interference...) of matter in order to do calculation

Even Modern Computers use **some** Properties from Quantum Mechanics, for example in a [SSD Memory Cell](https://youtu.be/5f2xOxRGKqk).<br>
But the diffrence is that in a Quantum Computer **only** use these Quantum mechanical properties.

As many think Quantum Computers are just faster Computers.  
This is **not** the Case, Quantum Computers or *Quantum Turing Machines* work diffrently from Normal Computers or *Turing Machines*.  

[Turing Machines](https://youtu.be/gJQTFhkhwPA) are Conceptual Models of the physical Computers.
Unlike the *Turing Machines*, *Quantum Turing Machines* have qubits, which can't only be in the state of 0 or 1.  
Instead Qubits could be in the Superposition, which allows them to represent a one or a zero at the same time.  
But in the End, everything that a Quantum Computer can calculate can be calculated by a Normal one (given enough time).  

### Computing Methods for Quantum Computers
To create a programm for a Quantum Computer there are multiple Models available.
They differ in how they compute, but the outcome is always equal.
* Quantum Turing machines
* Quantum circuits
* Measurement based quantum computing (MBQC)
* Adiabatic quantum computing
* Topological quantum computing  
The most common Model in use is the Quantum Circuits Model of Computation.  
So that's the one we're gonna use.

### What are Quantum Circuits
Every Computation has 3 Elements, which may also be known under the [IPO model](https://en.wikipedia.org/wiki/IPO_model).<br>
It's the simplest way to graph or analyse systems.

#### Data - Qubit
The Data in Quantum Circuits is represented by Qubits.
Other than normal Bits, which can store a value of either 1 or 0, a Qubit can store infinite many values.

#### Operations
The Operations in Quantum Circuits is represented by Quantum Gates

#### Results
The Results in Quantum Circuits is represented by Measurements

## Part II: One-Qubit Systems

