# Building observation simulators for VLT/ELT instruments

**Title**: Building observation simulators for VLT/ELT instruments
**Supervisor**: Dr. Kieran Leschinski (Univ. Vienna)
**Contact information**: kieran.leschinski@univie.ac.at
**Expected duration**: 9 months
**Starting date**: Rolling

## Project description & goals
The VLT is one of the largest observing facilities in the world.
The ELT will be the largest optical telescope on Earth when it enters operations in 2027.
Observing time on these telescopes is worth between 30k€ and 300k€ a night.
Therefore it is in the interests of both the astronomical community and ESO to make sure telescope time is not allocated to proposals which little to no chance of success.
To ensure an observation strategy will be successful, it is useful (and sometime mandetory) to simulate the observations before submitting the proposal.
However for many of ESOs current instruments there is not tool available to do this, let alone a tool that allows astronomers to simulate observations with multiple instruments at the same time.

The ESO instrumentation group at our Institute has developed the ScopeSim tool for exactly this purpose.
This tool was developed as part of our commitments to the ELT instrument consortia, and as such is currently limited to simulating future observations with two of the ELT instruments.
This project aims to expand the usefulness of the ScopeSim tool by adding models to the instruments database for the current set of VLT instruments.
The primary goal is to define and implement models of the HAWKI (imager) and UVES (spectrograph) instruments at the VLT.
The secondary goal is to test the accuracy of the optical models by comparing observational data from the ESO archive with simulated images of the same targets.
Ultimately these instrument pacakges will be released to the public via the IRDB and may be used as part of ESOs 3rd generation software interfaces for observation proposals.

## Working plan & milestones
1. Introduction to the ScopeSim environment
2. Review of the optical characteristics of the HAWKI or UVES instrument
3. Collection of all data needed to instrument build the model for ScopeSim
4. Build the model
5. Test and debug the model with a series of bast test object
6. Locate a target of interest in the ESO archive that was observed with HAWKI or UVES
7. Recreate the target in the scopesim environment and observe it
8. Compare the simulated and archive data. Iterate on the instrument package until they match.
9. Write up thesis and publish the instrument model to the IRDB

## Requirements / special skills
- Intermediate python coding skills
- Intermediate understanding of telescope and instrument optical characteristics

## References
https://ui.adsabs.harvard.edu/abs/2020SPIE11452E..1ZL/
https://scopesim.readthedocs.io/en/latest/
https://irdb.readthedocs.io/en/latest/