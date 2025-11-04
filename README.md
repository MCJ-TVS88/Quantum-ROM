# Quantum ROM — Mini Project #2

This repository contains the implementation of **Mini Project #2: Quantum ROM (QROM)** from the QC Boot Camp.  
The goal is to construct a **quantum circuit** that performs a coherent lookup of a classical Boolean function  
$f: \mathbb{F}_2^n \rightarrow \mathbb{F}_2^d $, using **Qiskit**.

---

## Project Overview

A **Quantum Read-Only Memory (QROM)** is a reversible unitary that maps

$$
U_f |x\rangle |0\rangle = |x\rangle |f(x)\rangle,
$$

allowing quantum algorithms to query data in superposition.  
This concept underlies many quantum algorithms such as **Grover’s Search**, **Quantum Machine Learning**, and **Quantum Simulation**.

---

## ⚙️ Features

- Implements a general QROM constructor from a classical truth table.  
- Supports arbitrary Boolean functions $f(x)$.  
- Demonstrates functionality for $n = 3$ input qubits.  
- Includes full documentation and visual circuit rendering using Qiskit.  
- Contains verification and histogram plotting for simulation results.
