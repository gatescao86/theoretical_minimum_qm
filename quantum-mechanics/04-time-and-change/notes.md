# Lecture 4 — Time and Change

**Status.** Not started  
**Book.** *Quantum Mechanics: The Theoretical Minimum*  
**Starts at p.** 93

## What this lecture is about

## Section notes

### 4.1 A Classical Reminder

- Key idea:
- Equations worth keeping:

### 4.2 Unitarity

$$
|\Psi(t) \rangle = U(t) |\Psi(0) \rangle
$$
Operation $U$ is called the time-development operator for the system.

### 4.3 Determinism in Quantum Mechanics

The quantum evolution of states allows us to compute the probabilities of the outcomes of later experiments. 

### 4.4 A Closer Look at $U(t)$

the conservation of distinctions.
$$
\langle \Psi(0)|\Phi(0) \rangle = 0
$$
$$
\langle \Psi(t)|\Phi(t) \rangle = 0
$$
$$
\langle \Psi(t)| = \langle \Psi(0)|U^\dagger(t)
$$
$$
\langle \Psi(0)|U^\dagger(t)U(t)|\Phi(t) \rangle = 0
$$
$$
\langle i|j \rangle = \delta_{ij}
$$
$$
\langle i|U^\dagger(t)U(t)|j \rangle = \delta_{ij}
$$
The operator $U^\dagger(t)U(t)$ behaves like the unit operator $I$ when it acts between any members of a basis set.

### 4.5 The Hamiltonian

$$
U(\epsilon) = I - i \epsilon H
$$
$$
U^\dagger(\epsilon) = I + i \epsilon H^\dagger
$$
$$
(I + i \epsilon H^\dagger)(I - i \epsilon H) = I
$$
$$
H^\dagger = H
$$
$H$ is the quantum Hamiltonian. Its eigenvalues are the values that would result from measuring the energy of a quantum system.

$$
\frac{|\Psi(\epsilon) \rangle - |\Psi(0) \rangle}{\epsilon} = -iH|\Psi(0) \rangle
$$
Time-derivative of the state-vector:
$$
\frac{\partial |\Psi \rangle}{\partial t} = =iH|\Psi \rangle
$$
generalized Schrödinger equation. 
### 4.6 What Ever Happened to $\hbar$?

$\hbar = \frac{h}{2 \pi} = 1.054571726... \times 10^{-34} kg m^2/s$


### 4.7 Expectation Values

$$
\langle L \rangle = \Sigma_{i} \lambda_iP(\lambda_i)
$$
$$
\langle L \rangle = \langle A|L|A \rangle
$$

### 4.8 Ignoring the Phase-Factor

We can multiply any state-vector by a constant factor $e^{i \theta}$ without changing the state-vector's physical meaning.

### 4.9 Connections to Classical Mechanics

$$
\frac{d}{dt} \langle \Psi(t)|L|\Psi(t) \rangle = \frac{i}{h} \langle \Psi(t) | [HL - LH] | \Psi(t) \rangle
$$
$$
[L, M] = -[M, L]
$$

$$
\frac{d}{dt}\langle L \rangle = \frac{i}{h}<[H, L]>
$$

### 4.10 Conservation of Energy

If $Q$ commutes with the Hamiltonian, the expectation values of all functions of $Q$ are conserved.

### 4.11 Spin in a Magnetic Field

The energy is proportional to the dot product of the spin and the magnetic field. The quantum version of this is 

$$
H \sim \vec{\sigma} \cdot \vec{B} = \sigma_x B_x + \sigma_y B_y + \sigma_z B_z
$$

### 4.12 Solving the Schrödinger Equation

Time dependent Schrödinger equation
$$
\hbar \frac{\partial |\Psi \rangle}{\partial t} = iH|\Psi \rangle
$$

Time independent Schrödinger equation
$$
H |E_j \rangle = E_j|E_j \rangle
$$

Eigenvectors form an othonormal basis and then expand the state-vector in that basis.

$$
|\Psi \rangle = \Sigma_j \alpha_j |E_j \rangle
$$

$$
|\Psi(t) \rangle = \Sigma_j \alpha_j(t) |E_j \rangle
$$

Feed into the time-dependent equation.

$$
\Sigma_j \dot{\alpha_j}(t) |E_j \rangle = -\frac{i}{\hbar}H \Sigma_j \alpha_j(t) |E_j \rangle
$$

$$
\Sigma_j \dot{\alpha_j}(t) |E_j \rangle = -\frac{i}{\hbar} \Sigma_j E_j \alpha_j(t) |E_j \rangle
$$

Regrouping:

$$
\Sigma_j \{\dot{\alpha_j}(t) + \frac{i}{\hbar}E_j \alpha_j(t)\} |E_j \rangle = 0
$$

If a sum of basis vectors equals zero, every coefficient must be zero.

$$
\frac{d \alpha_j(t)}{dt} = -\frac{i}{\hbar}E_j \alpha_j(t)
$$

The solution is 

$$
\alpha_j(t) = \alpha_j(0) e^{-\frac{i}{\hbar}E_jt}
$$

If we know the state-vector $|\Psi \rangle$ at time zero, then the coefficients are given by the projections of $|\Psi \rangle$ on the basis eigenvectors. 

$$
\alpha_j(0) = \langle E_j|\Psi(0) \rangle
$$

$$
|\Psi(t) \rangle = \Sigma_j \langle E_j|\Psi(0) \rangle e^{-\frac{i}{\hbar}E_jt} |E_j \rangle
$$

$$
|\Psi(t) \rangle = \Sigma_j |E_j \rangle \langle E_j|\Psi(0) \rangle e^{-\frac{i}{\hbar}E_jt} 
$$

### 4.13 Recipe for a Schrödinger Ket

- Key idea:
- Equations worth keeping:

### 4.14 Collapse

- Key idea:
- Equations worth keeping:

## Definitions

| Term | Meaning |
|---|---|
|  |  |

## Important equations

$$

$$

## Questions / things to revisit
