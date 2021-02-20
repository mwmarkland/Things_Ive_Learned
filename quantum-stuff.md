# Counterintuitive ideas of quantum physics

A pphysical system in a definite state can still behave randomly.

Two systems that are *too far apart* to influence each other can neverthelss behave in ways that, though *individually random*, are somehow *strongly correlated*.

Quantum computing uses a special kind of superposition whcih allows for exponentially many logical states at once. Many of these superpositions which are useful for computation are entangled -- they are states of the whole computer which do not correspond to *any* assignment f digital or analog states of the individual qubits.

Superposition is like a spinning coin.

Interference allows guidance toward right answers.

Encode problem into a quantum state, trigger state changes. Dangers of decoherence.

A quantum computer with n qubits can exist in a quantum superposition of all 2^n of its destinct logical states.

Probability says that n coins can be described as a pro a listic mixture of 2^n states but only *is* one of them. Quantum computers hold data in superposition of the 2^n logical states at once; it is all states.

Entanglement: the whole system is in a state een though the parts of the system are not.

If you look at a single qubit, you see random measurements but comparing to its entangled partner you see the same values.

Some observations on an entangled pair are determinisitic.

Entanglement is key to communication tasks in quantum information; necessary to have a speed up over classical computation.

# *Programming Quantum Computers* O'Reilly book.

qubits: on *readout* you get a binary value, but infinite number of superpositions prior to readout.

bra-ket notation:  |1> |0>,  0.95|0> + 0.35|1> represents probability of qubit in that state.

Key idea:  there are operations that can be done on qubits that don't collapse the superposition.

In superposition the value of the *amplitude* is important. It has two *knobs*:

*magnitude*: how much the item has spread into each path (value). Related to the probability the qubit will readout to each value. The square of the magnitude is the probability of it taking the value.

*relative phase*: the amount by which the value in one path is delayed relative to the other path.

Amplitudes are generally described by complex numbers. 
Magnitude = modulus of the amplitude
relative phase = angle if the amplitude is expressed in polar form.

These values are encoded into a qubit.

Computing circuits are built on operations that manipulate these concepts.

Circuit operations can be *reversable* meaning no information is lost or discarded when appled, or *irreversable* meaning information is lost or discarded.

So you can build a simple circut to generate random numbers

0>----H----D
Here you start with a single qubit, use the *Hadamard* operation wich creates an equal superposition when given a |0> or |1> state, and then do a readout. Since the probability is 
0.5|0> + 0.5|1> it is essetially 50-50 what value you get on readout. Hence true randomness.


