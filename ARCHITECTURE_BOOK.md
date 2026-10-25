# Architecture Book: Marie Curie AI ($CURIE)
## High-Assurance Autonomous System Design & Invariant Specifications

### 1. Executive System Topology

```
+---------------------------------------------------------------------------------+
|                         Marie Curie AI Autonomous Node                     |
+---------------------------------------------------------------------------------+
                                      |
         +----------------------------+----------------------------+
         |                                                         |
         v                                                         v
+-----------------------------+                           +-----------------------+
|  Rust Bitboard State Engine |                           |   EVM Launchpad Token |
|  - 64-bit Non-Linear Conway |                           |   - Linear Bonding    |
|  - SplitMix64 Determinism   |                           |   - Milestone Escrow  |
|  - 10,000 Cycle Continuity  |                           |   - Multi-Sig Control |
+-----------------------------+                           +-----------------------+
         |                                                         |
         +----------------------------+----------------------------+
                                      |
                                      v
+---------------------------------------------------------------------------------+
|                       Model Context Protocol (MCP) Server                       |
|   - model_decay_chain_equilibrium: Simulates radioactive secular equilibrium and alpha/beta decay emissions for Radium-226 and Polonium-210                    |
|   - calibrate_radiotherapeutic_dose: Calculates ionizing radiation dosage, tissue absorption coefficients and oncology target exposure                    |
+---------------------------------------------------------------------------------+
                                      |
                                      v
+---------------------------------------------------------------------------------+
|                      NIST FIPS 203 / 204 Post-Quantum Vault                     |
|           [ML-KEM-768 Lattice Encap] <---> [ML-DSA-65 Digital Signature]         |
+---------------------------------------------------------------------------------+
```

### 2. State Invariant Telemetry & Dynamics

The core execution layer relies on a continuous bitboard cellular automaton representing the domain invariants of **Nuclear Physics, Radiochemistry & Oncology Therapy**.
- **State Focus**: Radioactive Half-Life & Isotopic Decay Energy Invariant
- **Token Utility**: Nuclear Isotope Provenance & High-Precision Radiotherapy Telemetry Governance
- **Audit Cadence**: Checksums updated every 1,000 cycles using SHA-256 state hashing with immutable salt.

### 3. Model Context Protocol Tools
1. `model_decay_chain_equilibrium`: Simulates radioactive secular equilibrium and alpha/beta decay emissions for Radium-226 and Polonium-210
2. `calibrate_radiotherapeutic_dose`: Calculates ionizing radiation dosage, tissue absorption coefficients and oncology target exposure
