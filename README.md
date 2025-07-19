# QPU-Sim

Pre-installed System Packages only. It is an incredibly powerfull and Massive Simulator of an Quantum Computer, with multiple QPU's and a communicatoion unit between the outer world and the QPU that also provides an Terminal Interface, that can be used by our self-invented- Quantum-Assembler.

---
---
# The Architecture:
Like said we have a thick but controlled Interface between the QPU's and the Computer it is simulated on, this interface provides lots connections in the QPU that could not be changed if the QPU where Real.
The code it self is a Massive cluster of .py codes, that works in that directory where the user drags them, but to simulate the Superposition (and the Hadmard-Gates) The big closter of python-codes, each with its full funktionality contains some C++ scource-code, only one code, to simulate the Randomness really percisely it provides more deeper calculations to nearly achive real superposition and randomness. Thats why you need to download the Code specified README_C.md beacouse there are the compilation details, and how the c++ file should be named after compilation. There also is a Group of additional .py -files mixed by, if you want to use the c++ file you need to delete these .py files that are listed in the README_C. But if you dont delete them they will be used as a alternative instead of the c++ superposition-generator.

---
* QPU's -8qbit
  - The simulator has: 3 QPU's
  - and 6 Cores in each
  - and 8 Cores as OM (Operation Memory)
  - each Core has 60 registers (8qbit's)

* Interface -we call it: IaII
  - Interaction and Interpretation Interface
  - Provides a Terminal with different view-modes
    - 1: live Terminal: Enter single commands
    - 2: Processor load and general core status (switch between the Cores): xx/xx units are loaded
    - 3: Help (there is a command and a mode): Views all information and instruction + Quantum-Assembler Ducumentation
  - Transcripts the input Code (Interpretation)
