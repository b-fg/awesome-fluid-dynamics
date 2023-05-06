# [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) ![Links CI](https://img.shields.io/github/actions/workflow/status/lento234/awesome-fluid-dynamics/check_links.yml?label=Links&style=flat-square&labelColor=black) ![License](https://img.shields.io/github/license/lento234/awesome-fluid-dynamics?style=flat-square&color=blue&labelColor=000000) ![Last commit](https://img.shields.io/github/last-commit/lento234/awesome-fluid-dynamics?style=flat-square&labelColor=000000)


![Awesome](logo/awesome-logo.svg)

A curated list of repositories related to fluid dynamics.

*`Please send pull requests or raise issues to improve this list.`*

## Contents

- [Educational](#educational)
  - [Notebooks](#notebooks)
  - [Lecture Series](#lecture-series)
  - [Books](#books)
- [Meshing](#meshing)
- [Computational Fluid Dynamics](#computational-fluid-dynamics)
  - [Finite Difference Methods (FDM)](#finite-difference-methods-fdm)
  - [Finite Element Methods (FEM)](#finite-element-methods-fem)
  - [Finite Volume Methods (FVM)](#finite-volume-methods-fvm)
  - [Spectral Methods](#spectral-methods)
  - [Vortex Methods / Panel Methods / Blade Element Methods](#vortex-methods--panel-methods--blade-element-methods)
  - [Immersed Boundary Methods (IBM)](#immersed-boundary-methods-ibm)
  - [Weather and Climate](#weather-and-climate)
  - [Building Energy and Urban Environments](#building-energy-and-urban-environments)
  - [Shallow Water / Ocean Dynamics](#shallow-water--ocean-dynamics)
  - [Lattice Boltzmann Methods (LBM)](#lattice-boltzmann-methods-lbm)
  - [Design and Optimization](#design-and-optimization)
  - [Coupling](#coupling)
  - [Chemical Kinetics](#chemical-kinetics)
  - [Supersonic / Hypersonic Flow](#supersonic--hypersonic-flow)
  - [Differential programming](#differential-programming)
  - [Neural Networks for PDE](#neural-networks-for-pde)
  - [Graphics](#graphics)
  - [Other Techniques](#other-techniques)
- [Experimental Fluid Dynamics](#experimental-fluid-dynamics)
  - [PIV / PTV](#piv--ptv)
  - [ML / Optical Flow](#ml--optical-flow)
- [Post-processing and Data Analysis](#post-processing-and-data-analysis)
- [Visualization](#visualization)
  - [2D Visualization](#2d-visualization)
  - [3D Visualization](#3d-visualization)
- [Benchmarks and Datasets](#benchmarks-and-datasets)
  - [Datasets](#datasets)
  - [Benchmarks](#benchmarks)
- [Reproducibility](#reproducibility)
- [Community](#community)
- [Related Topics](#related-topics)

## Educational

### Notebooks

- [barbagroup/CFDPython](https://github.com/barbagroup/CFDPython) - A sequence of Jupyter notebooks featuring the "12 Steps to Navier-Stokes". ![Python](logo/Python.svg) [![Jupyter](logo/Jupyter.svg)](https://github.com/barbagroup/CFDPython/search?l=jupyter-notebook)
- [gpeyre/numerical-tours](https://github.com/gpeyre/numerical-tours) - Numerical Tours of Signal Processing and other materials. ![MATLAB](logo/MATLAB.svg) ![Python](logo/Python.svg) ![Jupyter](logo/Jupyter.svg) ![julia](logo/julia.svg) ![R](logo/R.svg)
- [jfavre/Visualization-training](https://github.com/jfavre/Visualization-training) - The material used for the Scientific Visualization course, organized online by the Swiss National Supercomputing Centre (CSCS) on May 17-18, 2021. ![Python](logo/Python.svg) [![Jupyter](logo/Jupyter.svg)](https://github.com/jfavre/Visualization-training/search?l=jupyter-notebook)

### Lecture Series

- [Steve Brunton/Fluid Dynamics](https://www.youtube.com/playlist?list=PLMrJAkhIeNNQWO3ESiccZmPssvUDFHL4M) - Prof. Brunton's lecture series on *Fluid dynamics*. ![YouTube](logo/YouTube.svg)
- [Steve Brunton/Reinforcement Learning](https://youtube.com/playlist?list=PLMrJAkhIeNNQe1JXNvaFvURxGY4gE9k74) - Prof. Brunton's lecture series on *Reinforcement Learning*. ![YouTube](logo/YouTube.svg)
- [Steve Brunton/Vector Calculus and Partial Differential Equations](https://youtube.com/playlist?list=PLMrJAkhIeNNQromC4WswpU1krLOq5Ro6S) - Prof. Brunton's lecture series on *Vector Calculus and Partial Differential Equations*. ![YouTube](logo/YouTube.svg)
- [Barry Belmont/NSF Fluid Mechanics Series](https://www.youtube.com/playlist?list=PL0EC6527BE871ABA3) - A collection of NFS Fluid Mechanics lecutre series from mid 20th century. ![YouTube](logo/YouTube.svg)
- [The Bright Side of Mathematics/Functional analysis](https://youtube.com/playlist?list=PLBh2i93oe2qsGKDOsuVVw-OCAfprrnGfr) - Lecture series on *Functional analysis*. ![YouTube](logo/YouTube.svg)
- [MIT OpenCourseWare/MIT RES.6-012 Introduction to Probability, Spring 2018](https://www.youtube.com/playlist?list=PLUl4u3cNGP60hI9ATjSFgLZpbNJ7myAg6) - Lecture recording of *Probabilistic Systems Analysis and Applied Probability*. ![YouTube](logo/YouTube.svg)
- [József Nagy/CFD basics](https://youtube.com/playlist?list=PLcOe4WUSsMkH6DLHpsYyveaqjKxnEnQqB) - CFD basics and introduction to OpenFOAM. ![YouTube](logo/YouTube.svg) [![src](logo/src.svg)](https://github.com/jnmlujnmlu/OpenFOAMTeaching)
- [rmcelreath/stat_rethinking_2022](https://youtube.com/playlist?list=PLDcUM9US4XdMROZ57-OIRtIK0aOynbgZN) - Statistical Rethinking (2022 Edition) by Richard McElreath. ![YouTube](logo/YouTube.svg) [![src](logo/src.svg)](https://github.com/rmcelreath/stat_rethinking_2022)
- [Machine Learning & Simulation/Fenics Tutorial](https://youtube.com/playlist?list=PLISXH-iEM4Jl0-G1CpvG-mhrV0233tG_D) - Fenics Tutorial lecture series. ![YouTube](logo/YouTube.svg) [![src](logo/src.svg)](https://github.com/Ceyron/machine-learning-and-simulation/tree/main/english/fenics)

### Books

- Brunton, S., & Kutz, J. (2019). Data-Driven Science and Engineering: Machine Learning, Dynamical Systems, and Control. Cambridge: Cambridge University Press. [DOI :memo:](https://doi.org/10.1017/9781108380690) [Book :book:](http://databookuw.com/)
- Castro, I. P., & Vanderwel, C. (2021). Turbulent Flows: An Introduction. IOP Publishing. [DOI :memo:](https://doi.org/10.1088/978-0-7503-3619-2) [Book :book:](https://github.com/cvanderwel/TurbulentFlows)
- Thuerey, N., Holl, P., Mueller, M., Schnell, P., Trost, F., & Um, K. (2021). Physics-based Deep Learning. [Book :book:](https://physicsbaseddeeplearning.org/)


## Meshing

- [nschloe/optimesh](https://github.com/nschloe/optimesh) - Mesh optimization, mesh smoothing. ![Python](logo/Python.svg)
- [nschloe/pygmsh](https://github.com/nschloe/pygmsh) - Gmsh for Python. ![Python](logo/Python.svg)
- [nschloe/meshio](https://github.com/nschloe/meshio) - I/O for exhaustive number of mesh file types. ![Python](logo/Python.svg)
- [PyMesh/PyMesh](https://github.com/PyMesh/PyMesh) - Geometry Processing Library for Python. ![C++](logo/cpp.svg) ![Python](logo/Python.svg)
- [cnr-isti-vclab/meshlab](https://github.com/cnr-isti-vclab/meshlab) - The open source mesh processing system. ![C++](logo/cpp.svg)
- [inducer/meshpy](https://github.com/inducer/meshpy) - 2D/3D simplicial mesh generator interface for Python (Triangle, TetGen, gmsh). ![C++](logo/cpp.svg) ![Python](logo/Python.svg)
- [gmsh](https://en.wikipedia.org/wiki/Gmsh) - A three-dimensional finite element mesh generator with built-in pre- and post-processing facilities ![C++](logo/cpp.svg). ![Python](logo/Python.svg) ![julia](logo/julia.svg)
- [CGAL/cgal](https://github.com/CGAL/cgal) - The Computational Geometry Algorithms Library (CGAL) is a C++ library that aims to provide easy access to efficient and reliable algorithms in computational geometry. ![C++](logo/cpp.svg)


## Computational Fluid Dynamics

### Finite Difference Methods (FDM)

- [p-costa/CaNS](https://github.com/p-costa/CaNS) - A code for fast, massively-parallel direct numerical simulations (DNS) of canonical flows. ![FORTRAN](logo/FORTRAN.svg)

### Finite Element Methods (FEM)

- [JuliaFEM/JuliaFEM.jl](https://github.com/JuliaFEM/JuliaFEM.jl) - The JuliaFEM software library is a framework that allows for the distributed processing of large Finite Element Models across clusters of computers using simple programming models. ![julia](logo/julia.svg) [![Jupyter](logo/Jupyter.svg)](https://github.com/JuliaFEM/JuliaFEM.jl/search?l=jupyter-notebook)
- [FEniCS/dolfinx](https://github.com/FEniCS/dolfinx) - Next generation FEniCS problem solving environment. ![C++](logo/cpp.svg) ![Python](logo/Python.svg)
- [deal.II](https://dealii.org/) - An open source finite element library. ![C++](logo/cpp.svg)
- [firedrakeproject/firedrake](https://github.com/firedrakeproject/firedrake) - Firedrake is an automated system for the portable solution of partial differential equations using the finite element method (FEM). ![Python](logo/Python.svg)
- [KratosMultiphysics/Kratos](https://github.com/KratosMultiphysics/Kratos) - Kratos Multiphysics (A.K.A Kratos) is a framework for building parallel multi-disciplinary simulation software. ![C++](logo/cpp.svg) ![Python](logo/Python.svg)
- [FluidityProject/fluidity](https://github.com/FluidityProject/fluidity) - An open-source computational fluid dynamics code with adaptive unstructured mesh capabilities. ![FORTRAN](logo/FORTRAN.svg)
- [kinnala/scikit-fem](https://github.com/kinnala/scikit-fem) - Simple finite element assemblers. ![Python](logo/Python.svg)

### Finite Volume Methods (FVM)

- [OpenFOAM/OpenFOAM-dev](https://github.com/OpenFOAM/OpenFOAM-dev) - OpenFOAM is a free, open source computational fluid dynamics (CFD) software package released by the OpenFOAM Foundation. ![C++](logo/cpp.svg)
- [su2code/SU2](https://github.com/su2code/SU2) - SU2: An Open-Source Suite for Multiphysics Simulation and Design. ![C++](logo/cpp.svg) ![Python](logo/Python.svg)
- [cselab/aphros](https://github.com/cselab/aphros) - Finite volume solver for incompressible multiphase flows with surface tension. ![C++](logo/cpp.svg)
- [code-saturne/code_saturne](https://github.com/code-saturne/code_saturne) - code_saturne public mirror. ![C++](logo/cpp.svg) ![FORTRAN](logo/FORTRAN.svg) ![Python](logo/Python.svg)
- [DelNov/T-Flows](https://github.com/DelNov/T-Flows) - T-Flows (stands for Turbulent Flows) is a Computational Fluid Dynamics (CFD) program, originally developed at Delft University of Technology, the Netherlands. ![FORTRAN](logo/FORTRAN.svg)
- [ucns3d-team/UCNS3D](https://github.com/ucns3d-team/UCNS3D) - Unstructured Compressible Navier Stokes 3D code (UCNS3D). ![FORTRAN](logo/FORTRAN.svg)
- [weymouth/WaterLily.jl](https://github.com/weymouth/WaterLily.jl) -  Fast and simple fluid simulator in Julia. ![julia](logo/julia.svg)
- [MFlowCode/MFC](https://github.com/mflowcode/MFC) - MFC is a compressible multiphase fluid solver with high-order-accurate shock- and interface-capturing and GPU support via OpenACC. ![FORTRAN](logo/FORTRAN.svg)
- [nextfoam/Baram](https://github.com/nextfoam/baram) - BARAM is developed to mitigate the steep learning curve of Text-based Solvers. BARAM helps you focus on a problem itself with intuitive graphical user interface. For now, OpenFOAM® solvers modified by nextfoam are integrated into BARAM. ![Python](logo/Python.svg)

### Spectral Methods

- [DedalusProject/dedalus](https://github.com/DedalusProject/dedalus) - A flexible framework for solving PDEs with modern spectral methods. ![Python](logo/Python.svg) [![Jupyter](logo/Jupyter.svg)](https://github.com/DedalusProject/dedalus/search?l=jupyter-notebook)
- [FourierFlows/FourierFlows.jl](https://github.com/FourierFlows/FourierFlows.jl) - Tools for building fast, hackable, pseudospectral partial differential equation solvers on periodic domains. ![julia](logo/julia.svg)
- [Nek5000/Nek5000](https://github.com/Nek5000/Nek5000) - NEK5000 is an spectral element CFD code developed at the Mathematics and Computer Science Division of Argonne National Laboratory. ![FORTRAN](logo/FORTRAN.svg)
- [spectralDNS/shenfun](https://github.com/spectralDNS/shenfun) - High performance computational platform in Python for the spectral Galerkin method. ![Python](logo/Python.svg) [![Jupyter](logo/Jupyter.svg)](https://github.com/spectralDNS/shenfun/search?l=jupyter-notebook)

### Vortex Methods / Panel Methods / Blade Element Methods

- [vortexmethods/VM2D](https://github.com/vortexmethods/VM2D) - VM2D: Open-Source Code for 2D Flow Simulation by Using Meshless Lagrangian Vortex Methods. ![C++](logo/cpp.svg)
- [markstock/vic2d](https://github.com/markstock/vic2d) - Two-dimensional semi-Lagrangian vortex method for very low viscosity fluid simulation. ![C++](logo/cpp.svg) ![FORTRAN](logo/FORTRAN.svg)
- [gdeskos/DVMpp](https://github.com/gdeskos/DVMpp) - 2D Discrete Vortex Method Code written in C++. ![C++](logo/cpp.svg)
- [byuflowlab/FLOWUnsteady](https://github.com/byuflowlab/FLOWUnsteady) - Mixed-fidelity unsteady aerodynamics and aeroacoustics. ![julia](logo/julia.svg)
- [Applied-Scientific-Research/Omega2D](https://github.com/Applied-Scientific-Research/Omega2D) - Two-dimensional flow solver with GUI using vortex particle and boundary element methods. ![C++](logo/cpp.svg)
- [camUrban/PteraSoftware](https://github.com/camUrban/PteraSoftware) - A fast, easy-to-use, and open-source software package for analyzing flapping-wing flight. ![Python](logo/Python.svg)

### Immersed Boundary Methods (IBM)

- [cwrowley/ibpm](https://github.com/cwrowley/ibpm) - Immersed Boundary Projection Method (IBPM). ![C++](logo/cpp.svg)
- [barbagroup/PetIBM](https://github.com/barbagroup/PetIBM) - PetIBM - toolbox and applications of the immersed-boundary method on distributed-memory architectures. ![C++](logo/cpp.svg)
- [barbagroup/cuIBM](https://github.com/barbagroup/cuIBM) - cuIBM: a GPU-based immersed boundary method code. ![C++](logo/cpp.svg)
- [ChenguangZhang/sdfibm](https://github.com/ChenguangZhang/sdfibm) - Immersed boundary method empowered by signed distance field, and OpenFOAM. ![C++](logo/cpp.svg)
- [IBAMR/IBAMR](https://github.com/IBAMR/IBAMR) - An adaptive and distributed-memory parallel implementation of the immersed boundary (IB) method. ![C++](logo/cpp.svg)

### Weather and Climate

- [wrf-model/WRF](https://github.com/wrf-model/WRF) -  Weather Research and Forecasting (WRF) model is a numerical weather prediction (NWP) system designed to serve both atmospheric research and operational forecasting needs. ![FORTRAN](logo/FORTRAN.svg)

### Building Energy and Urban Environments

- [NREL/EnergyPlus](https://github.com/NREL/EnergyPlus) - EnergyPlus™ is a whole building energy simulation program that engineers, architects, and researchers use to model both energy consumption and water use in buildings. ![C++](logo/cpp.svg)
- [uDALES/u-dales](https://github.com/uDALES/u-dales) - uDALES: large-eddy-simulation software for urban flow, dispersion and microclimate modelling. ![FORTRAN](logo/FORTRAN.svg)
- [ladybug-tools/butterfly](https://github.com/ladybug-tools/butterfly) - :butterfly: A light python API for creating and running OpenFoam cases for CFD simulation. ![Python](logo/Python.svg)

### Shallow Water / Ocean Dynamics

- [jostbr/shallow-water](https://github.com/jostbr/shallow-water) - Python model solving the shallow water equations (linear momentum, nonlinear continuity). ![Python](logo/Python.svg)
- [team-ocean/veros](https://github.com/team-ocean/veros) - The versatile ocean simulator, in pure Python, powered by JAX. ![Python](logo/Python.svg)
- [CliMA/Oceananigans.jl](https://github.com/CliMA/Oceananigans.jl) - Julia software for fast, friendly, flexible, data-driven, ocean-flavored fluid dynamics on CPUs and GPUs. ![julia](logo/julia.svg)
- [OceanParcels/parcels](https://github.com/OceanParcels/parcels) - Parcels (Probably A Really Computationally Efficient Lagrangian Simulator) is a set of Python classes and methods to create customisable particle tracking simulations using output from Ocean Circulation models. ![Python](logo/Python.svg) [![Jupyter](logo/Jupyter.svg)](https://github.com/OceanParcels/parcels/search?l=jupyter-notebook)

### Lattice Boltzmann Methods (LBM)

- [aromanro/LatticeBoltzmann](https://github.com/aromanro/LatticeBoltzmann) - A 2D Lattice Boltzmann program. ![C++](logo/cpp.svg)
- [lanl/MF-LBM](https://github.com/lanl/MF-LBM) - A Portable, Scalable and High-performance Lattice Boltzmann Code for DNS of Flow in Porous Media. ![FORTRAN](logo/FORTRAN.svg)
- [unigespc/palabos](https://gitlab.com/unigespc/palabos) - Palabos is an open-source CFD solver based on the lattice Boltzmann method. ![C++](logo/cpp.svg)


### Design and Optimization

- [mdolab/dafoam](https://github.com/mdolab/dafoam) - DAFoam: Discrete Adjoint with OpenFOAM for High-fidelity Gradient-based Design Optimization. ![C++](logo/cpp.svg) ![Python](logo/Python.svg)
- [peterdsharpe/AeroSandbox](https://github.com/peterdsharpe/AeroSandbox) - Aircraft design optimization made fast through modern automatic differentiation. ![Python](logo/Python.svg)
- [DARcorporation/xfoil-python](https://github.com/DARcorporation/xfoil-python) - Stripped down version of XFOIL as compiled python module. ![Python](logo/Python.svg)

### Coupling

- [precice/precice](https://github.com/precice/precice) - A coupling library for partitioned multi-physics simulations, including, but not restricted to fluid-structure interaction and conjugate heat transfer simulations. ![C++](logo/cpp.svg)

### Chemical Kinetics

- [Cantera/cantera](https://github.com/Cantera/cantera) - Chemical kinetics, thermodynamics, and transport tool suite. ![C++](logo/cpp.svg) ![Python](logo/Python.svg)

### Supersonic / Hypersonic Flow

- [matteobernardini/STREAmS](https://github.com/matteobernardini/STREAmS) - STREAmS performs Direct Numerical Simulations of compressible turbulent flows in Cartesian geometry solving the unsteady, fully compressible Navier-Stokes equations for a perfect gas. ![FORTRAN](logo/FORTRAN.svg)
- [sergeas67/OpenHyperFLOW2D](https://github.com/sergeas67/OpenHyperFLOW2D) - 2D (flat/axisymmetrical) transient viscous compressible multicomponent sub/trans/supersonic reacting gas flow with RANS/URANS turbulence models. ![C++](logo/cpp.svg)

### Differential programming

- [taichi-dev/taichi](https://github.com/taichi-dev/taichi) - Parallel programming for everyone. ![Python](logo/Python.svg)
- [tum-pbs/PhiFlow](https://github.com/tum-pbs/PhiFlow) - A differentiable PDE solving framework for machine learning. ![Python](logo/Python.svg)
- [google/jax-cfd](https://github.com/google/jax-cfd) - Computational Fluid Dynamics in JAX. ![Python](logo/Python.svg) [![Jupyter](logo/Jupyter.svg)](https://github.com/google/jax-cfd/search?l=jupyter-notebook)

### Neural Networks for PDE

- [lululxvi/deepxde](https://github.com/lululxvi/deepxde) - Deep learning library for solving differential equations and more. ![Python](logo/Python.svg)
- [SciML/NeuralPDE.jl](https://github.com/SciML/NeuralPDE.jl) - Physics-Informed Neural Networks (PINN) and Deep BSDE Solvers of Differential Equations for Scientific Machine Learning (SciML) accelerated simulation. ![julia](logo/julia.svg)
- [google/neural-tangents](https://github.com/google/neural-tangents) - Fast and Easy Infinite Neural Networks in Python. ![Python](logo/Python.svg)
- [isl-org/DeepLagrangianFluids](https://github.com/isl-org/DeepLagrangianFluids) - Lagrangian Fluid Simulation with Continuous Convolutions. ![Python](logo/Python.svg)
- [maxjiang93/space_time_pde](https://github.com/maxjiang93/space_time_pde) - MeshfreeFlowNet: Physical Constrained Space Time Super-Resolution. ![Python](logo/Python.svg)

### Graphics

- [PavelDoGreat/WebGL-Fluid-Simulation](https://github.com/PavelDoGreat/WebGL-Fluid-Simulation) - Play with fluids in your browser (works even on mobile). ![JavaScript](logo/JavaScript.svg)
- [doyubkim/fluid-engine-dev](https://github.com/doyubkim/fluid-engine-dev) - Fluid simulation engine for computer graphics applications. ![C++](logo/cpp.svg)

### Other Techniques

- [PyFR/PyFR](https://github.com/PyFR/PyFR) - Framework for solving advection-diffusion type problems on streaming architectures using the Flux Reconstruction approach of Huynh. ![Python](logo/Python.svg)
- [pencil-code/pencil-code](https://github.com/pencil-code/pencil-code) - A high-order finite-difference code for compressible hydrodynamic flows with magnetic fields and particles. ![FORTRAN](logo/FORTRAN.svg) [![Jupyter](logo/Jupyter.svg)](https://github.com/pencil-code/pencil-code/search?l=jupyter-notebook)
- [NaluCFD/Nalu](https://github.com/NaluCFD/Nalu) - Nalu: a generalized unstructured massively parallel low Mach flow code designed to support a variety of open applications of interest built on the Sierra Toolkit and Trilinos solver Tpetra solver stack. ![C++](logo/cpp.svg)
- [lesgo-jhu/lesgo](https://github.com/lesgo-jhu/lesgo) - The Large-Eddy Simulation framework from the Turbulence Research Group at Johns Hopkins University. ![FORTRAN](logo/FORTRAN.svg)
- [cornellius-gp/gpytorch](https://github.com/cornellius-gp/gpytorch) - A highly efficient and modular implementation of Gaussian Processes in PyTorch. ![Python](logo/Python.svg)


## Experimental Fluid Dynamics

### PIV / PTV

- [JHU-NI-LAB/OpenLPT_Shake-The-Box](https://github.com/JHU-NI-LAB/OpenLPT_Shake-The-Box) - Open-source C++ code for Shake-the-box, particle tracking algorithm. ![C++](logo/cpp.svg) ![MATLAB](logo/MATLAB.svg)
- [OpenPTV/openptv](https://github.com/openptv/openptv) - OpenPTV - open source 3D-PTV software. ![C++](logo/cpp.svg)
- [OpenPIV/openpiv-python](https://github.com/openpiv/openpiv-python) - OpenPIV consists in a Python and Cython modules for scripting and executing the analysis of a set of PIV image pairs. ![Python](logo/Python.svg) ![MATLAB](logo/MATLAB.svg) [![Jupyter](logo/Jupyter.svg)](https://github.com/OpenPIV/openpiv-python/search?l=jupyter-notebook)
- [OpenPTV/pyptv](https://github.com/openptv/pyptv) - Python GUI for OpenPTV - open source three-dimensional particle tracking velocimetry. ![Python](logo/Python.svg)
- [ronshnapp/MyPTV](https://github.com/ronshnapp/myptv) - Python based 3D-PTV - open source pure Python three-dimensional particle tracking velocimetry. ![Python](logo/Python.svg)

### ML / Optical Flow

- [erizmr/UnLiteFlowNet-PIV](https://github.com/erizmr/UnLiteFlowNet-PIV) - Unsupervised learning of Particle Image Velocimetry. (ISC 2020). ![Python](logo/Python.svg)
- [shengzesnail/PIV-LiteFlowNet-en](https://github.com/shengzesnail/PIV-LiteFlowNet-en) - Particle image velocimetry via a deep neural network (LiteFlowNet). ![C++](logo/cpp.svg) ![Python](logo/Python.svg) ![MATLAB](logo/MATLAB.svg)
- [yongleex/PIV-DCNN](https://github.com/yongleex/PIV-DCNN) - Perform PIV image pair match using deep conv neural network. ![MATLAB](logo/MATLAB.svg) ![C++](logo/cpp.svg)


## Post-processing and Data Analysis

- [numpy/numpy](https://github.com/numpy/numpy) - The fundamental package for scientific computing with Python. ![Python](logo/Python.svg)
- [mathLab/PyDMD](https://github.com/mathLab/PyDMD) - Python Dynamic Mode Decomposition. ![Python](logo/Python.svg) [![Jupyter](logo/Jupyter.svg)](https://github.com/mathLab/PyDMD/search?l=jupyter-notebook)
- [dynamicslab/pysindy](https://github.com/dynamicslab/pysindy) - A sparse regression package with several implementations for the Sparse Identification of Nonlinear Dynamical systems. ![Python](logo/Python.svg)
- [ritchieng/eigenvectors-from-eigenvalues](https://github.com/ritchieng/eigenvectors-from-eigenvalues) - This repository implements a calculation of eigenvectors from eigenvectors elegantly through PyTorch. ![Jupyter](logo/Jupyter.svg)
- [mengaldo/PySPOD](https://github.com/mengaldo/PySPOD) - A Python package for spectral proper orthogonal decomposition (SPOD).  ![Python](logo/Python.svg)
- [belson17/modred](https://github.com/belson17/modred) - An easy-to-use and parallelized library for finding modal decompositions and reduced-order models. ![Python](logo/Python.svg)
- [Astroua/TurbuStat](https://github.com/Astroua/TurbuStat) - Statistics of Turbulence Python Package. ![Python](logo/Python.svg)
- [SURGroup/UQpy](https://github.com/SURGroup/UQpy) - UQpy (Uncertainty Quantification with python) is a general purpose Python toolbox for modeling uncertainty in physical and mathematical systems. ![Python](logo/Python.svg) [![Jupyter](logo/Jupyter.svg)](https://github.com/SURGroup/UQpy/search?l=jupyter-notebook)
- [haller-group/LCStool](https://github.com/haller-group/LCStool) - LCStool: LCS Tool is a computational engine for analyzing fluid flows by extracting their most influential material surfaces, Lagrangian Coherent Structures. ![MATLAB](logo/MATLAB.svg)


## Visualization

### 2D Visualization

- [matplotlib/matplotlib](https://github.com/matplotlib/matplotlib) - matplotlib: plotting with Python. ![Python](logo/Python.svg)
- [scikit-image/scikit-image](https://github.com/scikit-image/scikit-image) - Image processing in Python. ![Python](logo/Python.svg)
- [3b1b/manim](https://github.com/3b1b/manim) - Animation engine for explanatory math videos. ![Python](logo/Python.svg)
- [garrettj403/SciencePlots](https://github.com/garrettj403/SciencePlots) - Matplotlib styles for scientific plotting. ![Python](logo/Python.svg)
- [mwaskom/seaborn](https://github.com/mwaskom/seaborn) - Statistical data visualization in Python. ![Python](logo/Python.svg)
- [lukelbd/proplot](https://github.com/lukelbd/proplot) - :art: A succinct matplotlib wrapper for making beautiful, publication-quality graphics. ![Python](logo/Python.svg)

### 3D Visualization

- [K3D-tools/K3D-jupyter](https://github.com/K3D-tools/K3D-jupyter) - K3D lets you create 3D plots backed by WebGL with high-level API (surfaces, isosurfaces, voxels, mesh, cloud points, vtk objects, volume renderer, colormaps, etc). ![Python](logo/Python.svg) ![JavaScript](logo/JavaScript.svg) [![Jupyter](logo/Jupyter.svg)](https://github.com/K3D-tools/K3D-jupyter/search?l=jupyter-notebook)
- [sciapp/gr](https://github.com/sciapp/gr) - GR framework: a graphics library for visualisation applications. ![C++](logo/cpp.svg) ![Python](logo/Python.svg)
- [QuantStack/ipygany](https://github.com/QuantStack/ipygany) - 3-D Scientific Visualization in the Jupyter Notebook. ![Python](logo/Python.svg) [![Jupyter](logo/Jupyter.svg)](https://github.com/QuantStack/ipygany/search?l=jupyter-notebook)
- [InsightSoftwareConsortium/itkwidgets](https://github.com/InsightSoftwareConsortium/itkwidgets) -  Interactive Jupyter widgets to visualize images, point sets, and meshes in 2D and 3D. ![Python](logo/Python.svg) ![JavaScript](logo/JavaScript.svg) [![Jupyter](logo/Jupyter.svg)](https://github.com/InsightSoftwareConsortium/itkwidgets/search?l=jupyter-notebook)
- [NVIDIA/ipyparaview](https://github.com/NVIDIA/ipyparaview) - iPython widget for server-side ParaView rendering in Jupyter. ![Python](logo/Python.svg) ![JavaScript](logo/JavaScript.svg) [![Jupyter](logo/Jupyter.svg)](https://github.com/NVIDIA/ipyparaview/search?l=jupyter-notebook)
- [Kitware/Vtk](https://gitlab.kitware.com/vtk/vtk) - Visualization Toolkit. ![C++](logo/cpp.svg)
- [Kitware/paraview](https://www.paraview.org/) - An open-source, multi-platform data analysis and visualization application. ![Python](logo/Python.svg)
- [pyvista/pyvista](https://github.com/pyvista/pyvista) - 3D plotting and mesh analysis through a streamlined interface for the Visualization Toolkit (VTK). ![Python](logo/Python.svg)
- [blender/blender](https://github.com/blender/blender) - A free and open source 3D creation suite, supporting the entirety of the 3D pipeline-modeling, rigging, animation, simulation, rendering, compositing, motion tracking and video editing. ![Python](logo/Python.svg)


## Benchmarks and Datasets

### Datasets

- [shengzesnail/PIV_dataset](https://github.com/shengzesnail/PIV_dataset) - PIV dataset. ![MATLAB](logo/MATLAB.svg)
- [idies/pyJHTDB](https://github.com/idies/pyJHTDB) - Python wrapper for the Johns Hopkins turbulence database library. ![Python](logo/Python.svg) [![Jupyter](logo/Jupyter.svg)](https://github.com/idies/pyJHTDB/search?l=jupyter-notebook)

### Benchmarks

- [dionhaefner/pyhpc-benchmarks](https://github.com/dionhaefner/pyhpc-benchmarks) - A suite of benchmarks for CPU and GPU performance of the most popular high-performance libraries for Python. ![Python](logo/Python.svg)
- [su2code/TestCases](https://github.com/su2code/TestCases) - An extensive collection of common test cases for SU2. ![C++](logo/cpp.svg) ![Python](logo/Python.svg)


## Reproducibility

- [iterative/dvc](https://github.com/iterative/dvc) - Data Version Control, Git for Data & Models, ML Experiments Management. ![Python](logo/Python.svg)
- [sphinx-doc/sphinx](https://github.com/sphinx-doc/sphinx) - Sphinx is a tool that makes it easy to create intelligent and beautiful documentation for Python projects. ![Python](logo/Python.svg)


## Community

- [CFD Online Forum](https://www.cfd-online.com/Forums/) - A free community for everyone interested in Computational Fluid Dynamics.
- [r/CFD](https://www.reddit.com/r/CFD/) - Reddit community on *Computational Fluid Dynamics*. ![r/CFD](https://img.shields.io/reddit/subreddit-subscribers/cfd?label=r%2FCFD&style=flat-square&labelColor=black)
- [r/FluidMechanics](https://www.reddit.com/r/FluidMechanics/) - Reddit community on *Fluid Mechanics*. ![r/FluidMechanics](https://img.shields.io/reddit/subreddit-subscribers/FluidMechanics?label=r%2FFluidMechanics&style=flat-square&labelColor=black)

## Related Topics

- [alexlib/awesome_piv](https://github.com/alexlib/awesome_piv) - A curated list of repositories related to PIV (particle image velocimetry). ![Awesome](logo/awesome.svg)
- [nschloe/awesome-scientific-computing](https://github.com/nschloe/awesome-scientific-computing) - Curated list of awesome software for numerical analysis and scientific computing. ![Awesome](logo/awesome.svg)
- [qd-cae/awesome-CAE](https://github.com/qd-cae/awesome-CAE) - A curated list of awesome CAE frameworks, libraries and software. ![Awesome](logo/awesome.svg)
- [awesomedata/awesome-public-datasets](https://github.com/awesomedata/awesome-public-datasets) -  A topic-centric list of HQ open datasets. ![Awesome](logo/awesome.svg)
