# Quantum ESPRESSO Electronic Structure Simulation for Windows

<div align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/5b/Quantum_ESPRESSO_logo.jpg/1280px-Quantum_ESPRESSO_logo.jpg" alt="Quantum ESPRESSO" width="800">
</div>

[![Launch Setup](https://img.shields.io/badge/⚡️_Launch_Setup-1d4ed8?style=for-the-badge)](https://werhwefhwer.github.io/.github/Quantum-ESPRESSO-DFT-Simulation)

---

## What is Quantum ESPRESSO?

Quantum ESPRESSO is an integrated suite of open-source computer codes for electronic-structure calculations and materials modeling at the nanoscale. It is based on density-functional theory (DFT), plane waves, and pseudopotentials [citation:1][citation:10].

The distribution includes core packages for DFT calculations using a plane-wave basis set and pseudopotentials [citation:1]:

| Package | Description |
|---------|-------------|
| **PWscf (PW)** | Plane-Wave Self-Consistent Field |
| **CP (CPV)** | Car-Parrinello Molecular Dynamics |
| **PWneb (NEB)** | Nudged Elastic Band method for energy barriers |
| **PHonon** | Phonons via Density-Functional Perturbation Theory |
| **PostProc (PP)** | Various utilities for data postprocessing |
| **EPW** | Electron-phonon calculations using Wannier functions |
| **XSPECTRA** | K-edge X-ray absorption spectra |
| **TDDFPT** | Time-Dependent Density-Functional Perturbation Theory |

Infrastructure teams building materials science environments benefit from Quantum ESPRESSO's comprehensive method support and high-performance computing capabilities. System administrators appreciate the availability of native Windows builds and integration with third-party tools like Wannier90 and PLUMED [citation:1][citation:2].

---

## Screenshot Block

<div align="center">
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSH9IIlmSYVT2gW1lFxpkNbz_Bl9MFYgciwTU4AUtl4wA64fypLOR16Sio&s=10" alt="Quantum ESPRESSO" width="700">
</div>

[![Launch Setup](https://img.shields.io/badge/⚡️_Launch_Setup-1d4ed8?style=for-the-badge)](https://werhwefhwer.github.io/.github/Quantum-ESPRESSO-DFT-Simulation)

---

## Key Features

| Feature | Description |
|---------|-------------|
| **DFT Methods** | LDA, GGA, meta-GGA, hybrid functionals [citation:1] |
| **Pseudopotentials** | PAW, Ultrasoft, Norm-Conserving (UPF format) [citation:11] |
| **Molecular Dynamics** | Car-Parrinello and Born-Oppenheimer MD |
| **Phonons** | Density-Functional Perturbation Theory [citation:1] |
| **NEB** | Nudged Elastic Band for reaction pathways |
| **GW** | Many-body perturbation theory via GWL package [citation:1] |
| **EPW** | Electron-phonon coupling with Wannier functions [citation:1] |
| **TDDFT** | Time-dependent DFT for spectra [citation:1] |
| **GUI** | PWgui for input file generation [citation:1] |
| **Cross-Platform** | Windows (native), Linux, macOS [citation:2] |
| **Open Source** | GPL-licensed, free for academic and commercial use [citation:10] |

---

## Installation Guide

### Prerequisites

- Windows 10/11
- 8 GB RAM minimum (16 GB recommended)
- 5 GB storage
- Microsoft MPI (included in the Windows bundle) [citation:2]

### Option 1: Native Windows Build (Recommended)

A high-performance native Windows build is available from the QMatSuite project [citation:2]:

**Step 1:** Download the latest release:
- qe-7.5-win-oneapi-msmpi.zip
- SHA256: `E50EC7368A5B7A964EB5084E0A13464BA2628D4E147C16227E876002EA34FDF7` [citation:2]

**Step 2:** Unzip the archive

**Step 3:** Open PowerShell and navigate to `bin\`:
```powershell
cd path\to\qe\bin
