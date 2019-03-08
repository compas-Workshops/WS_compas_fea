# NCCR_FEA_Workshop


Installation checklist
======================

Because of the size of the Abaqus installation files and the different licensing systems for each research group, it will not be feasible to leave the Abaqus installation and set-up till the day of the workshop. Both Abaqus and its licensing, as well as Rhinoceros and also its licensing, should be sorted before the workshop day, including the set-up of any VPN if moving network. Please contact liew@arch.ethz.ch in due time for any assistance on any installation issues. **Note**: the workshop is based on a Windows environment, Abaqus as the FE solver, and Rhino as the CAD software. The general preparatory installation steps needed to participate in the workshop are:


CPython
-------

- Install a CPython distribution such as Anaconda or the official Python download.
- Make sure the **NumPy** and **SciPy** packages are installed, for example via ``pip``.
- For optional features (not officially part of the workshop) install **MeshPy**, **Vtk**, **PyQt5**, **PyOpenGL**.


compas
------

- Clone the main ``master`` branch **compas** repository, using a repository manager like GitHub desktop or SmartGit.
- Add the ``src`` folder to your ``PYTHONPATH`` in ``Advanced System Settings`` > ``Environment Variables``.
- Add the ``src`` folder to your Rhino Pythonscript folders.


compas_fea
----------

- Clone the main ``master`` branch **compas_fea** repository, using a repository manager like GitHub desktop or SmartGit.
- Add the ``src`` folder to your ``PYTHONPATH`` in ``Advanced System Settings`` > ``Environment Variables``.
- Add the ``src`` folder to your Rhino Pythonscript folders.


Abaqus
------

- Install the academic (ETH/EPFL network licensed) Abaqus version 6.14, other versions *seem* to work fine.
- Have a VPN connection to your license server available if needed.


Timetable
=========

**Location**: Open Space 2
**Date**: March 27 2019
**Time**: 9:00-12:00

- **09:00** – Introduction and how to build a numerical model (ARR)
- **09:30** – Program installation (AL, TM, ARR)
- **09:45** – Q&A + Break (AL, TM, ARR)

- **10:00** – Short **compas_fea** presentation (AL)
- **10:15** – Basics and building truss models (AL)
- **11:00** – Q&A + Break (AL, TM, ARR)

- **11:15** – Shell element models and buckling/modal analyses (AL)
- **11:45** – Development outlook, demonstration of meshing and 3D solid analyses, Q&A (AL, TM, ARR)
