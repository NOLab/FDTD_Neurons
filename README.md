# FDTD_Neurons

Lumerical Scripts and Matlab codes used to generate the simulations data in the article "Multiscale characterization of myelin distribution with polarized THG microscopy"

How to run the FDTD simulations:


1 - Download and install FDTD (ANSYS). Free one-month demo licenses are available from ANSYS.


2 - Import the necessary materials into the material's database (using the provided material file (.mdf file in the FDTD simulation folder), or inputing manually using the provided parameters)


3 - run the provuided .lsf scripts, corresponding to the translation of a neuron of a given geometry along thre x-axis, for two orthogonal polarizations. The .lsf script require the manual creation of a new folder per simulation, where all the simulation results will be stored 


4 - run theMatlab script, that will integrate the THG signal measured by the detectors in the simulation, and output both the emission pattern and the integrated THG signal for the different polarizations as a function of the position of the neuron.
