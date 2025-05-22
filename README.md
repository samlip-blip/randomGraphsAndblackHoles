# randomGraphsAndblackHoles
To model how quantum information spreads inside a black hole using random graphs, we can represent qubit interactions via an Erdős-Rényi random graph. Each node corresponds to a qubit, and edges dictate where entangling gates (e.g., CNOT) are applied. The resulting entanglement entropy quantifies information spread, analogous to scrambling in black holes.

# Explanation
Random Graph: The Erdős-Rényi graph G defines qubit interactions. Each edge adds a CNOT, SWAP, CZ gates, simulating chaotic interactions in a black hole.
# Quantum Circuit:
Qubits start in a superposition (no entanglement).
CNOT, SWAP, CZ gates (edges) entangle qubits, spreading information.
# Entanglement Entropy:
After tracing out part of the system, the entropy measures how much information is shared between subsystems.
Higher entropy indicates greater scrambling, similar to black hole dynamics.
# Interpretation
Connectivity (p): Higher p increases entanglement entropy, mimicking faster information scrambling.
Graph Variability: Run multiple trials to average over random graph realizations.
Extensions: Use more qubits, deeper circuits, or different gates (e.g., CZ, SWAP) for richer behavior.
This approach links random graph theory to quantum information dynamics, offering a simplified model of black hole scrambling.
