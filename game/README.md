# Entanglion Rule Book

> A game by IBM Research

**2 PLAYERS | AGES 14 & UP | ~45 MINUTES**

Entanglion awaits your space navigation skills and strategic planning to explore a new galaxy and reconstruct an ancient quantum computer.

http://ibm.biz/entanglion

> 🤔 Confused about a rule? Please take a look at the [errata](Errata.md) for rule clarifications and game updates.

# Welcome to the quantum universe, Captain!

<img src="../images/bg.png" width="100%">

Congratulations, your captain has retired and left you in charge of his galactic shipping business! Now it's time to make some upgrades.

For years, you've been obsessed with rumors of an ancient quantum computing technology that could revolutionize galactic cargo transport. If the rumors were true, it would allow your ships to calculate hyperspace paths in mere seconds! There's only one problem: the ancients dismantled their quantum computer out of fears that it was too powerful, and they left the components scattered across planets in the heavily-guarded Entanglion galaxy.

If you want to rebuild this incredible technology, you'll have to navigate your ships through the Entanglion galaxy and out-maneuver the defenses the ancients left behind. The good news is that your old captain left you enough money to outfit your ships with the quantum-powered engines you'll need to enter Entanglion. The bad news is that without a quantum computer to guide them, these engines can be a little… unpredictable.

Think you're up for the challenge?

# Goal
Entanglion is a cooperative board game designed for two players. The goal is to reconstruct a quantum computer developed by an ancient race. Work together with your teammate to navigate the three galaxies of the quantum universe – Centarious, Superious, and Entanglion – in a quest to collect eight quantum computer components. Be careful to avoid detection by the planetary defense mechanisms guarding the components!

# Game concepts
Entanglion was designed to expose players to several fundamental concepts in quantum computing: 

- **Qubits** are the building blocks of quantum computation.
- **Superposition** is when a quantum system may exist in a probabilistic combination of multiple states at once.
- **Entanglement** happens when the state of one qubit correlates with the state of another qubit.
- **Measurement** is the process of observing the classical value of a qubit.
- **Error** happens when random noise in the quantum system perturbs the measured value of a qubit.

Entanglion also exposes players to the different kinds of hardware and software components involved in building a real quantum computer.

Further discussion of how Entanglion relates to actual quantum computing can be found toward the end of this book.

# Game setup
1. **Lay out the game & spaceship boards**. Place the game board within easy reach from 
each player and distribute the spaceship boards to each player.
2. **Place the quantum components**. Shuffle the quantum components and place them face up on each planet in the Entanglion galaxy, one per planet.
3. **Shuffle the engine card stack**. Set aside the PROBE card and shuffle the remaining engine cards. Place the PROBE card face down on the engine stack, then place the remaining engine cards on top, face down.
4. **Prepare the quantum event deck**. Set aside the Quantum Shuffle card and shuffle the remaining event cards. Deal out three event cards face down on the quantum event deck. Next, place the Quantum Shuffle card face down on the deck. Finally, place the remaining event cards face down on the deck.
5. **Set the initial detection rate**. Place the detection rate token on the detection rate scale. For an easy game, start with a detection rate of 1 or 2. For a more challenging game, start with a detection rate of 3. If the detection rate reaches the final level (X) before the quantum computer has been built, the game ends in a loss.
6. **Determine the first player**. Determine the first player by having each player 
roll the Entanglion die (8-sided). The player with the higher number goes first. Re-roll in case of a tie.
7. **Determine the initial ship locations**. Starting with the first player, roll the Centarious die to place each spaceship (0 goes to <span style="color: purple"> ZERO </span>, 1 goes to <span style="color: purple"> ONE </span>). This process is akin to initializing a quantum system.
8. **Draw engine cards**. Starting with the first player, each player draws three engine cards into their hand. Engine cards may be kept face up.

<img src="../images/setup.png" width="100%">

# Materials

**Boards**
- 1 game board
- 2 spaceship boards
<img src="../images/board.png" width="40%">

**Cards**
- 24 engine cards (8 H, 7 CNOT, 5 X, 3 SWAP, 1 PROBE)
<img src="../images/engine_cards.png" width="40%">

- 9 event cards
<img src="../images/events.png" width="100%">

**Pieces**
- 1 detection rate token
- 8 quantum components
<img src="../images/quantum_components.png" width="100%">

- 1 Centarious die (purple binary d6)
- 1 Entanglion die (yellow d8)
- 2 spaceship tokens
<img src="../images/spaceship.png" width="20%">

**Rule Book**

# Engine cards
<img src="../images/engine_cards.png" width="60%">

Engine cards are used to navigate your ships around the quantum universe. Navigation paths on the game board are labeled with the card(s) needed to traverse them (e.g. “X/CNOT” means either X or CNOT can be used to traverse that path). In some cases, only one spaceship may traverse a path. Engine cards may be played with no effect when no transition is shown on the board.

**X**. X is used to navigate between <span style="color: purple"> ZERO </span> and <span style="color: purple"> ONE </span> and within the Entanglion galaxy.

**H**. H is used to travel between Centarious and Superious and within the Entanglion galaxy.

**SWAP**. Outside of Entanglion, SWAP exchanges the positions of the two spaceships. Inside Entanglion, SWAP only transitions the spaceships between <span style="color: #facd4d"> OMEGA ZERO </span> and <span style="color: #facd4d"> OMEGA THREE </span>.

**CNOT**. CNOT is used to enter the Entanglion galaxy and navigate within it. It also flips the position of your spaceship in Centarious, but only when the other spaceship is orbiting <span style="color: purple"> ONE </span>.

**PROBE**. Whenever PROBE is drawn, your ships have been discovered by an ancient defensive probe! Roll the Entanglion die. If the outcome is less than 4 (after accounting for quantum component effects), increase the detection rate by one. Otherwise, PROBE has no effect. Discard PROBE and draw a replacement engine card.

> Orient engine cards in the engine control spaces such that the lines on the card line up with the line of your spaceship.

> When the engine stack becomes depleted, immediately reshuffle the engine cards in the discard pile to replenish the engine stack. Include PROBE in the shuffle, do not place it at the bottom of the stack.

# Turn overview
Perform _one_ of the following actions on your turn.

1. **Navigate**. Play one engine card in engine control to navigate around the galaxy, and draw a replacement. You may only play engine cards for your own ship.
2. **Exchange**. Discard one engine card from your hand and draw a replacement..
3. **Retrieve**. Roll the Entanglion die to attempt to retrieve a quantum component if one is present.
4. **Event**. Play an event card from your hand (if you possess one).

> Players may not pass their turns, they must perform one of the actions above.

# Entering & exiting Entanglion
In order to enter Entanglion, one spaceship needs to be in Centarious and the other spaceship needs to be in Superious. Only the spaceship in Centarious can use CNOT to enter Entanglion. The paths into Entanglion are represented with gray lines on the game board.

Lead spaceship (playing the CNOT) | Other spaceship | Destination
--- | --- | ---
<span style="color: purple"> ZERO </span> | <span style="color: green"> PLUS </span> | <span style="color: #facd4d"> PHI PLUS </span>
<span style="color: purple"> ZERO </span> | <span style="color: green"> MINUS </span> | <span style="color: #facd4d"> PHI MINUS </span>
<span style="color: purple"> ONE </span> | <span style="color: green"> PLUS </span> | <span style="color: #facd4d"> PSI PLUS </span>
<span style="color: purple"> ONE </span> | <span style="color: green"> MINUS </span> | <span style="color: #facd4d"> PSI MINUS </span>

It is also possible to exit Entanglion using CNOT when both ships are orbiting <span style="color: #facd4d"> PHI PLUS </span>, <span style="color: #facd4d"> PHI MINUS </span>, <span style="color: #facd4d"> PSI PLUS </span>, or <span style="color: #facd4d"> PSI MINUS </span>. The ship that plays the CNOT returns to Centarious and the other ship returns to Superious, on the planets indicated with the gray lines.

Example: Rubicon is orbiting <span style="color: purple"> ZERO </span> and Mercurial is orbiting <span style="color: green"> PLUS </span>. When Rubicon plays a CNOT, both ships move to <span style="color: #facd4d"> PHI PLUS </span>.

> Outside of Entanglion, ships move independently. Inside Entanglion, both ships always move together, irregardless of which player plays an engine card.

<img src="../images/entering_entanglion.png" width="40%">

On <span style="color: #facd4d"> PHI PLUS </span>, when Rubicon plays CNOT, Rubicon moves to <span style="color: purple"> ZERO </span> and Mercurial moves to <span style="color: green"> PLUS </span>.

<img src="../images/entering_entanglion2.png" width="40%">

# Detection rate
The detection rate determines the difficulty of successfully evading planetary defenses. The detection rate token is used to keep track of the current detection rate. When a player’s spaceship has been detected by orbital defenses, or a player’s away team has been detected by ground defenses, the detection rate is increased, making it easier for each planet’s defenses 
to detect the player in the future. The game ends when the detection rate reaches the final level (designated with an X).

> The detection rate increases by one whenever you are detected by a planet's orbital or ground defenses.

<img src="../images/detection_rate.png" width="40%">

# Orbital defenses
Planets in Entanglion are protected by orbital defenses that scan for ships looking to plunder the quantum components hidden there. It is possible to evade these defenses using your quantum engines. If you are detected, however, your navigation system will automatically take evasive maneuvers and jump to a random planet in the Centarious system. This jump triggers a quantum event.

**When you navigate to any planet in Entanglion:** Roll the Entanglion die. If the outcome is greater than the current detection rate, the orbital defenses have been evaded. If not, perform the following actions:

1. Roll the Centarious die and move both ships to the planet indicated. Both ships jump together.
2. Increase the detection rate by one.
3. Draw a quantum event card and perform the action indicated.

> Physical Qubits lets you decide which planets in Centarious to place your spaceships.

> Quantum Programming lets you bypass orbital defenses when a planet doesn't have a quantum component.

> The Quantum Tunnel event card lets you bypass orbital defenses. If you play this card after entering the orbit of a planet in Entanglion, you do not need to roll the Entanglion die to determine if your ships were detected by orbital defenses.

> When entering Entanglion via the Heisenberg card, you may ignore the orbital defenses.

> If you play an engine card that does not transition your ships to a new planet in Entanglion, you do not need to re-check whether your ships have been detected.

# Quantum components
There are eight components that players must obtain in order to build the quantum computer to win the game, shown on each of the spaceship boards. Each component also grants a permanent special ability or hindrance to your ship, so you must strategize with your teammate to obtain the components in an optimal order!

> Quantum components are permanent upgrades to your ship and alter gameplay for the rest of the game.

<img src="../images/quantum_components.png" width="100%">

When your ships are orbiting a planet with a quantum component, you may send an away team to the planet’s surface to retrieve it. Quantum components are guarded by automated ground defenses which, as with orbital defenses, must be evaded.

**To perform a retrieval mission:** Roll the Entanglion die. If the outcome is greater than the current detection rate, collect the component and place it on your spaceship board. If not, your away team was detected by the ground defenses; increase the detection rate by one.

> If your away team fails to retrieve a quantum component, your ships remain in orbit on the current planet. You do not need to perform another orbital defense check on the next turn unless you navigate to another planet that has orbital defenses

> The Quantum Tunnel event card lets you bypass ground defenses. If you play this card during your turn, your retrieval mission was successful. You do not need to roll the Entanglion die to determine if your away team was detected by ground defenses; add the quantum component to your ship

# Quantum events
Quantum engines can be unpredictable at times! Once all six engine control slots have been filled, perform a quantum event at the end of your turn. In addition, perform a quantum event whenever you have been detected by orbital defenses.

**To perform a quantum event:** Draw an event card and perform the instructions. Clear all engine cards from the game board and put them in engine discard pile.

> When Quantum Shuffle is drawn, reshuffle the quantum event cards as per the instructions in game setup.

> In the event that your ship was detected by orbital defenses on the same turn as having filled all six engine control slots, perform two quantum events.

<img src="../images/events.png" width="100%">

# Game end
Players immediately win the game when they have collected all eight components of the quantum computer. Players immediately lose the game when the detection rate reaches the end (X).

# Your first game
Set up the game board as described in Setup. In this game, Mercurial (the blue player) will go first. Mercurial draws three cards: X, H, and H. Rubicon draws three cards: CNOT, SWAP, and X. Both ships start on <span style="color: purple"> ZERO </span>.

<img src="../images/first1.png" width="40%">

1. Mercurial plays an H to navigate to <span style="color: green"> PLUS </span>. Mercurial draws X as a replacement card.

<img src="../images/first2.png" width="40%">

2. Rubicon plays CNOT to navigate both ships to <span style="color: #facd4d"> PHI PLUS </span>. Rubicon draws H as a replacement card. After arriving at a planet in Entanglion, Rubicon must roll the Entanglion die to evade the orbital defenses. Since the detection rate is 1, Rubicon needs to roll a 2 or higher. Rubicon rolls the Entanglion die and gets a 3, just enough to evade detection!

<img src="../images/first3.png" width="40%">
<img src="../images/first_detection.png" width="40%">

3. Mercurial decides to retrieve the Quantum Gates present on <span style="color: #facd4d"> PHI PLUS </span>. Mercurial rolls a 6, much higher than the detection rate of 1, and successfully retrieves the component.

<img src="../images/first4.png" width="40%">

4. Rubicon decides the next destination is <span style="color: #facd4d"> OMEGA TWO </span> and plays an H to navigate both ships there.

<img src="../images/first5.png" width="40%">

Rubicon rolls the Entanglion die and it comes up as 1. The ships have been detected, so they must retreat! Rubicon rolls a 1 on the Centarious die, so both ships jump back to <span style="color: purple"> ONE </span>. Since they were detected, the detection rate is increased by 1 and a quantum event is triggered. Rubicon draws a quantum event card – Heisenberg – which can be used on a future turn.

<img src="../images/first5.png" width="40%">
<img src="../images/first_detection2.png" width="40%">

Play continues until either Rubicon and Mercurial have collected all of the quantum components in Entanglion, or until the detection rate reaches the final level.

# How Entanglion relates to quantum computing
Entanglion models several aspects of a 2-qubit quantum computer. Specifically, the two spaceships represent two qubits, and each planet in each galaxy represents a different state of those qubits. Engine cards represent the quantum gates used to transition the qubits into different states.

The Centarious galaxy represents the classical states of 0 and 1, written in "ket notation" as ⎢0 〉(<span style="color: purple"> ZERO </span>) and ⎢1 〉(<span style="color: purple"> ONE </span>). The Superious galaxy represents states of quantum superposition, known as ⎢+ 〉(<span style="color: green"> PLUS </span>) and ⎢- 〉(<span style="color: green"> MINUS </span>). The Entanglion galaxy represents states of entanglement. Four of the entangled states, ⎢Ψ+ 〉(<span style="color: #facd4d"> PSI PLUS </span>), ⎢Ψ- 〉(<span style="color: #facd4d"> PSI MINUS </span>), ⎢Φ+ 〉(<span style="color: #facd4d"> PHI PLUS </span>), and ⎢Φ- 〉(<span style="color: #facd4d"> PHI MINUS </span>), are known as the [Bell states](https://en.wikipedia.org/wiki/Bell_state). The other entangled states, which we have labeled ⎢ω0 〉(<span style="color: #facd4d"> OMEGA ZERO </span>) through ⎢ω3 〉(<span style="color: #facd4d"> OMEGA THREE </span>), are additional states that are achievable through the combined operation of the X, H, SWAP, and CNOT gates.

The requirement that both ships must move together within Entanglion is a result of the fact that for entangled states, the state of the system is more complex than a simple combination of the states of the individual qubits. This is one of the main ways in which quantum mechanics differs from classical physics.

## Engine cards
The engine cards represent _some_ of the different kinds of quantum logic gates used by quantum computers.

<img src="../images/engine_cards.png" width="60%">

- **X**. The X gate flips the value of a qubit. It is also known as the bit flip gate.
- **SWAP**. SWAP exchanges the values of the two qubits.
- **CNOT**. CNOT stands for "Controlled Not." It needs two qubits to work: one qubit is designated the "target," which gets flipped if the other qubit, known as the "control," has a value of 1.
- **H**. The Hadamard gate is used to create or collapse superposition. It is one of the most important gates in quantum computing.

## Quantum components
The quantum components in Entanglion represent different physical or logical components needed to construct an actual quantum computer.

- **Physical Qubits**. Much like how classical computer processors are implemented via hardware transistors, quantum processors are implemented via hardware qubits. There are a [number of different ways](https://en.wikipedia.org/wiki/Qubit#Physical_representation) ways scientists are creating physical qubits, including Josephson junctions, ion traps, and quantum dots.
- **Qubit Interconnect**. Qubits must be physically connected to each other in order to become entangled with one another.
- **Dilution Regrigerator**. Physical qubits must be kept at very cold temperatures – colder even than outer space – in order to maintain their coherence. Dilution refrigerators are able to cool physical qubits to temperatures as low as 2 millikelvin.
- **Quantum Gates**. In classical computing, logical gates such as AND, OR, NOT, and NAND are combined to create higher-order computation. In quantum computing, quantum gates such as X, CNOT, SWAP, and H are used for computation.
- **Quantum Programming**. In order to improve the productivity of quantum programmers, higher-level quantum programming languages are needed. For example, [IBM OpenQASM](https://github.com/IBM/qiskit-openqasm) allows you to program a quantum computer with an assembly-style language, and [IBM QISKit](https://qiskit.org) allows you to program a quantum computer in Python.
- **Quantum Error Correction**. Physical qubits experience noise that may cause errors to occur during measurement. [Quantum error correction](https://en.wikipedia.org/wiki/Quantum_error_correction) is used to correct for these errors. The key insight of quantum error correction is to use multiple physical qubits to simulate one logical qubit.
- **Control Infrastructure**. Quantum computers need some way to measure the internal state of a qubit. Control infrastructure uses microwave radiation to read the state of a qubit and digitize it into a binary state (0 or 1).
- **Magnetic Shielding**. Qubits are extremely sensitive to stray magnetic fields. Magnetic shielding ensures qubits are protected from external sources of magnetism.

## Event cards
Event cards add fun, random elements to the game. Some event cards are named after people who made significant contributions to the field of quantum physics and quantum information science, such as Werner Heisenberg and Erwrin Schrödinger. One event card is extra special, named after IBM researcher Charles Bennett, one of the founders of quantum information theory and a key contributor to the discovery of the quantum teleportation effect. Other event cards are named after quantum effects such as quantum tunneling, bit flip errors, wave function collapsing, and Einstein’s "spooky action at a distance." We encourage avid players to research these people and topics to learn more about the physics of quantum information!

<img src="../images/events.png" width="100%">

## Defenses, measurement, and error
The process of encountering orbital defenses when navigating the Entanglion galaxy is akin to performing a classical measurement (also known as a Z measurement) on the quantum state. Additionally, the act of retrieving a quantum component is akin to performing an entanglement measurement, also known as a [Bell test](https://en.wikipedia.org/wiki/Bell_test_experiments). Sometimes, noise in the quantum system prevents us from seeing a reliable measurement. We call this a readout error. The effects of noise and errors are modeled via the detection rate.

## Additional resources
We recommend a few resources for learning more about quantum computing.

- [IBM Q Experience Beginner's Guide](http://ibm.biz/qx-guide) by IBM Research
- [Q is for Quantum](http://a.co/iJbiNS8) by T. Rudolph
- [Quantum Computing for Computer Scientists](http://a.co/cCZBoS9) by N. Yanofsky and M. Mannucci
- [Quantum Computation and Quantum Information](http://a.co/coZAko8) by M. A. Nielsen and I. L. Chuang
- [Quantum Computer Science: An Introduction](http://a.co/iYdi4Bv) by N. D. Mermin
- [Quantum Computing Since Democritus](http://a.co/1HzDIgF) by S. Aaronson
