This paper introduces and investigates a new class of digit-based affine maps of the form T(n) = An + c, where the coefficients A and c are derived from digit-linear expressions in a given base b. By combining slope and offset parameters across digit positions, these transforms produce nonlinear but affine-behaving dynamics when constrained to digit-valid domains. We explore their algebraic structure, arithmetic properties, and iteration behavior, including their actions modulo m and connections to pseudorandom generation.

Key contributions include a closed-form solution for iterates T⁽ᵗ⁾(n), structural analysis of digit-valid domains, and a demonstration of how these transforms generate dense families of repunit-dividing numbers. We also show how symbolic digit dynamics and affine maps together form a novel framework for deterministic, tunable pseudorandom number generators.

The paper includes a fully reproducible Wolfram Language implementation for computing and visualizing these maps, including cycle detection, modular iteration, and digit analysis. This work opens new avenues for studying arithmetic dynamical systems defined by local digit rules and affine global behavior.

Keywords: affine digit-linear transforms, arithmetic dynamics, digit systems, repunit divisibility, pseudorandom sequences, symbolic dynamics
