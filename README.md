# An introduction to Quantum Computing
## Introduction  
In Here i will Journal my Exploration into The World of Quantum Computing.

### Sources
[Quantum Computing for Computer Scientists](https://www.cambridge.org/core/books/quantum-computing-for-computer-scientists/8AEA723BEE5CC9F5C03FDD4BA850C711)  
[CERN: Online introductory lectures on quantum computing ](https://home.cern/news/announcement/computing/online-introductory-lectures-quantum-computing-6-november)

### Tools
[IBM Quantum Computing](http://quantum-computing.ibm.com)  
[Quirk Quantum Simulator](http://algassert.com/quirk)  
[D-Wave Quantum Computing](https://dwavesys.com/take-leap)

## Part I: Basics
Based on [**A practical introduction to quantum computing (1/7)**](https://indico.cern.ch/event/970903/)

### What is Quantum Computing
> Quantum computing is a computing paradigm that exploits Quantum mechanical properties (superposition, entanglement, interference...) of matter in order to do calculation

Even Modern Computers use **some** Properties from Quantum Mechanics, for example in a [SSD Memory Cell](https://youtu.be/5f2xOxRGKqk).<br>
But the difference is that in a Quantum Computer **only** use these Quantum mechanical properties.

As many think Quantum Computers are just faster Computers.  
This is **not** the Case, Quantum Computers or *Quantum Turing Machines* work differently from Normal Computers or *Turing Machines*.  
Thats why they're not faster, they're more efficent.

[Turing Machines](https://youtu.be/gJQTFhkhwPA) are Conceptual Models of the physical Computers.
Unlike the *Turing Machines*, *Quantum Turing Machines* have qubits, which can't only be in the state of 0 or 1.  
Instead Qubits could be in the Superposition, which allows them to represent a one or a zero at the same time.  
But in the End, everything that a Quantum Computer can calculate can be calculated by a Normal Computer (given enough time).  

### Computing Methods for Quantum Computers
To create a program for a Quantum Computer there are multiple Models available.
They differ in how they compute, but the outcome is always equal.
* Quantum Turing machines
* Quantum circuits
* Measurement based quantum computing (MBQC)
* Adiabatic quantum computing
* Topological quantum computing  
The most common Model in use is the Quantum Circuits Model of Computation.  
So that's the one we're going to use.

### What are Complex Numbers
Complex numbers started of as a Thought Experiment.
`i = √−1`

### What are Quantum Circuits
Every Computation has 3 Elements, which may also be known under the [IPO model](https://en.wikipedia.org/wiki/IPO_model).<br>
It's the simplest way to graph or analyze systems.

#### Data - Qubit
The Data in Quantum Circuits is represented by Qubits.
Other than normal Bits, which can store a value of either 1 or 0, a Qubit can store a Value of 0 or 1 or **Both**.  Or in Mathematical Terms It's a [Vector](https://youtu.be/ozwodzD5bJM)  
Means that the Qubit could be in the Position of 0 and 1 at the same time.
> > > > **Phase?!**

![Bloch Sphere](https://i.imgur.com/VVIk613.png)  

The Image shown is a Bloch Sphere, it is a visual representation of a Single Qubit.  
*Image Credits: [ScienceMag](https://www.sciencemag.org/news/2020/07/biggest-flipping-challenge-quantum-computing)*  

Mathematicaly Qubits are in a Vector space: 

`|0> y |1> `  
`|ψ> =  α|0> + β|1>`

#### Operations
The Operations in Quantum Circuits is represented by [Quantum Gates](https://youtu.be/gz5rjhiU4ao)  
other than Normal Computations, Quantum Gates always have an inverse operation.

Hadamar Gate:   
![Hadamar Gate](https://i.imgur.com/QU8Hu9a.png)  
![Hadamar Plus and Minus](https://i.imgur.com/4jasD5a.png)  
Pauli Gates: 
	x --> Inverts X
	y --> Inverts Y
	z --> Inverts Z
Phase Gate: 

X gate --> Not
Z Gate --> turns 1 into -1

#### Results
The Results in Quantum Circuits is represented by Measurements
But when measuring the state of the Qubit we:
1. Get either a 0 or a 1
2. We Change the State of the System, we lock the Qubit to an absolute value.

The Probability of getting 0 wil be `|α|²`  
The Probability of getting 1 wil be `|β|²`

## Part II: One-Qubit Systems

![One-Quibit Matrix](https://i.imgur.com/KdmYYmG.png)


