# ☢ Awesome Nuclear ☢

[![Open Source Love svg2](https://badges.frapsoft.com/os/v2/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of open source projects used in nuclear science and engineering.

## Particle Transport

### Codes: Monte Carlo

- [ERGnrc](https://nrc-cnrc.github.io/EGSnrc/) — Monte Carlo photon/electron/positron transport code
- [FRENSIE](https://github.com/FRENSIE/FRENSIE) — Monte Carlo neutron/photon transport code
- [Geant4](https://geant4.web.cern.ch/) — High-energy Monte Carlo particle transport code
- [OpenMC](https://github.com/openmc-dev/openmc) — Monte Carlo neutron/photon transport code
- [SCONE](https://github.com/CambridgeNuclear/SCONE) — Monte Carlo neutron transport code
- [Warp](https://github.com/weft/warp) — Monte Carlo neutron transport code on GPUs

### Codes: Deterministic

- [BART](https://github.com/SlaybaughLab/BART) — Finite-element, discrete ordinates code developed by UC-Berkeley
- [DRAGON](https://www.polymtl.ca/merlin/) — Lattice code developed by Polytechnique Montreal
- [FeenoX](https://www.seamplex.com/feenox) — Unstructured finite-element(ish) tool, diffusion and discrete ordinates
- [Gnat](https://github.com/OTU-Centre-for-SMRs/gnat) — A MOOSE-based discrete ordinates and fluid activation solver developed by Ontario Tech
- [OpenMOC](https://github.com/mit-crpg/openmoc) — Method of characteristics code
- [OpenSN](https://github.com/open-sn/opensn) — Successor to [Chi-Tech](https://github.com/chi-tech/chi-tech), a massively parallel discrete ordinates code developed by Texas A&M
- [Scarabée](https://github.com/scarabee-dev/scarabee) — Lattice physics code and deterministic transport toolbox
- [THOR](https://github.com/NCSU-NCSG/THOR) — Discrete ordinates code using the AHOT-C method on unstructured meshes

### Codes: Event Generators

- [CGMF](https://github.com/lanl/CGMF) — Fission event generator
- [FREYA](https://nuclear.llnl.gov/simulation/main.html) — Fission event generator

### Related Tools

- [ACE Format](https://github.com/NuclearData/ACEFormat) — Documentation of the ACE format
- [csg2csg](https://github.com/makeclean/csg2csg) — Tool to translate between different CSG types
- [DAGMC](https://github.com/svalinn/DAGMC) — Direct accelerated geometry Monte Carlo toolkit
- [GeoUNED](https://github.com/GEOUNED-org/GEOUNED) — FreeCAD-based tool to convert from CAD to CSG and vice versa
- [KDSource](https://github.com/KDSource/KDSource) — A tool for generating KDE surface sources from Monte Carlo simulations
- [McCAD](https://github.com/inr-kit/McCAD-Library) — C++ Library for CAD (BRep) to Monte Carlo (CSG) Conversion
- [MCNPTools](https://github.com/lanl/mcnptools) — C++/Python interface and tools for MCNP
- [MCPL](https://github.com/mctools/mcpl) — Binary file format for storing particle state
- [MontePy](https://github.com/idaholab/montepy) — Python library to read, edit, and write MCNP files
- [serpentTools](https://github.com/CORE-GATECH-GROUP/serpent-tools) — Python-based tool suite for Serpent
- [t4_geom_convert](https://www.cea.fr/energies/tripoli-4/tripoli-4/pre_post_tools/t4_geom_convert) — Convert MCNP geometries to TRIPOLI-4

## Nuclear Data

- [ACEMAKER](https://github.com/iaea-nds/acemaker) — Code package to produce ACE files
- [EMPIRE](https://www-nds.iaea.org/empire/index.html) — Nuclear reaction model code
- [endf-python](https://github.com/paulromano/endf-python) — Python ENDF Parser
- [FRENDY](https://rpg.jaea.go.jp/main/en/program_frendy) — Nuclear data processing
- [FUDGE](https://github.com/LLNL/fudge) — Python-based nuclear data processing
- [JADE](https://github.com/dodu94/JADE) — Tool for nuclear data library V&V
- [mendeleev](https://github.com/lmmentel/mendeleev) — Python package for accessing properties of elements, ions, and isotopes
- [NJOY21](https://github.com/njoy/NJOY21) — Nuclear data processing
- [Nuclear Data Reader](https://github.com/php1ic/nuclear-data-reader) — C++ library for parsing NUBASE and AME data files
- [NucML](https://github.com/pedrojrv/nucml) — Machine-learning pipeline for nuclear data evaluation
- [PapillonNDL](https://github.com/HunterBelanger/papillon-ndl) — C++ / Python library for reading and sampling ACE files
- [PREPRO](https://www-nds.iaea.org/public/endf/prepro/) — Nuclear data processing
- [PyNjoy 2012](https://www.polymtl.ca/merlin/pynjoy2012.htm) — Nuclear data processing
- [SANDY](https://github.com/luca-fiorito-11/sandy) — Sampling tool for nuclear data
- [SCALE](https://code.ornl.gov/scale/code/scale-public) — Public components of SCALE (AMPX, SAMMY)
- [TALYS](https://nds.iaea.org/talys) — Nuclear Reaction Simulator Code

## Depletion / Transmutation / Decay

- [ADDER](https://github.com/anl-rtr/adder) — Python-based fuel management and depletion tool
- [ALARA](https://github.com/svalinn/ALARA) — Activation code widely used for fusion
- [ONIX](https://github.com/jlanversin/ONIX) — Python-based burnup code
- [OpenMC](https://github.com/openmc-dev/openmc) — Depetion solver integrated in OpenMC
- [radioactivedecay](https://github.com/radioactivedecay/radioactivedecay) — Radioactive decay solver

## Kinetics

- [KOMODO](https://github.com/imronuke/KOMODO) — Nuclear reactor simulator that solves 3-D diffusion using nodal methods
- [PyRK](https://github.com/pyrk/pyrk) — Neutronic and thermal hydraulic reactor transient analysis in 0-D
- [Research Reactor Simulator](https://github.com/ijs-f8/Research-Reactor-Simulator) — Real-time GUI research reactor simulator based on point kinetics

## Fuel Cycle

- [Cyclus](https://github.com/cyclus/cyclus) — Nuclear fuel cycle simulator
- [OpenMCyclus](https://github.com/arfc/openmcyclus) — Depletable reactor archetype using OpenMC's `IndependentOperator` for fuel cycle simulations in Cyclus

## Thermal Hydraulics

- [Nek5000](https://github.com/Nek5000/Nek5000) — Spectral-element CFD code
- [nekRS](https://github.com/Nek5000/nekRS) — Spectral-element CFD code targeting modern processors and accelerators
- [OpenFOAM](https://www.openfoam.com/) — Finite volume CFD code
- [TrioCFD](https://github.com/cea-trust-platform/TrioCFD-code) — A Computational Fluid Dynamics (CFD) code based on the TRUST platform.

## Multiphysics

- [Aurora](https://github.com/aurora-multiphysics/aurora) — OpenMC wrapped as a MOOSE app
- [Cardinal](https://github.com/neams-th-coe/cardinal) — OpenMC and nekRS wrapped as MOOSE apps
- [ENRICO](https://github.com/enrico-dev/enrico) — Monte Carlo + CFD coupling application
- [GeN-Foam](https://gitlab.com/foam-for-nuclear/GeN-Foam) — OpenFOAM based multi-physics solver for reactor analysis
- [MOOSE](https://github.com/idaholab/moose) — Finite-element, multiphysics framework
- [SALOME](https://www.salome-platform.org) — Interoperability between CAD and multiphysics software
- [TRUST](https://github.com/cea-trust-platform/trust-code) — A software platform upon which CFD codes can be built

## Molten Salt Reactor

- [Moltres](https://github.com/arfc/moltres) — A molten salt reactor simulator code
- [MSRE](https://github.com/openmsr/msre) — Detailed CAD model of the MSRE
- [SaltProc](https://github.com/arfc/saltproc) — Fuel reprocessing simulation tool

## Other

- [ARMI](https://github.com/terrapower/armi) — Reactor analysis automation framework
- [NRIC Virtual Test Bed](https://github.com/idaholab/virtual_test_bed) — Repository of example challenge problems
- [PyARC](https://code.ornl.gov/neams-workbench/PyARC) - Framework for fast reactor analysis workflows using the extended Argonne Reactor Computation code suite
- [PyNE](https://github.com/pyne/pyne) — Python/C++ nuclear engineering toolkit
- [RAVEN](https://github.com/idaholab/raven) — UQ, regression, PRA, data analysis, and model optimization framework
- [WATTS](https://github.com/watts-dev/watts) — Python-based tool for templated simulations
- [LaTeX classes and BibTeX style for ANS publications](https://github.com/paulromano/ans-latex-class)

## Research Groups Invested in Open Source Tools for Nuclear Science and Engineering

- [ARFC](https://arfc.github.io) (UIUC) — Advanced Reactors and Fuel Cycles
- [CNERG](https://cnerg.github.io) (UW-Madison) — Computational Nuclear Engineering Research Group
- [CRPG](https://crpg.mit.edu) (MIT) — Computational Reactor Physics Group
- [ONCORE](https://nucleus.iaea.org/sites/oncore/) (IAEA) — an IAEA-facilitated
  international collaboration framework for the development and application of
  open-source multi-physics simulation tools to support research, education and
  training for the analysis of advanced nuclear power reactors.
