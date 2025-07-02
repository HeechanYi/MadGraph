# High Energy Physics Simulation Environment

This repository follows the [delphes-conda](https://github.com/chofchof/delphes-conda) setup to build a high energy physics simulation environment with **MadGraph5_aMC@NLO**, **Pythia8**, and **Delphes**.

---

## 🧰 MadGraph5_aMC@NLO

**MadGraph5_aMC@NLO** is a powerful event generator that simulates the **hard scattering** processes in high energy particle collisions. It automatically generates Feynman diagrams based on user-defined Lagrangians and calculates parton-level events at leading order (LO) or next-to-leading order (NLO).

- Simulates interactions between fundamental particles
- Supports various models beyond the Standard Model
- Outputs events in LHE (Les Houches Event) format

🔗 [Official MadGraph Website](https://launchpad.net/mg5amcnlo)

---

## 💥 Pythia8

**Pythia8** is a Monte Carlo event generator that takes parton-level events from MadGraph and performs **parton showering** and **hadronization** to simulate full final-state particles.

- Includes initial/final state radiation (ISR/FSR)
- Models hadronization and particle decays
- Provides realistic proton collision profiles

🔗 [Official Pythia Website](https://pythia.org/)

---

## 🔍 Delphes

**Delphes** is a fast simulation framework for modeling the **detector response** of high energy physics experiments. It processes events from Pythia and simulates detector effects such as tracking, calorimetry, and triggering using a simplified but realistic setup.

- Supports CMS, ATLAS, and other detector configurations
- Performs object reconstruction (jets, electrons, muons)
- Outputs results in ROOT file format for further analysis

🔗 [Official Delphes Website](https://delphes.github.io/)

---

## 📦 Environment Setup

This project is based on the [delphes-conda](https://github.com/chofchof/delphes-conda) environment. Please refer to the linked repository for step-by-step installation instructions.