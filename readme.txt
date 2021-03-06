NEURON mod files for the Na current from the papers:
Skaliora, Scobey and Chalupa, J.Neurosci. 13:313 (1993) (exp.)
Benison et al., J.Theor.Biol. 210:187 (2001) (model).

Running the kinetics.hoc simulation file will show 
the activation and inactivation steady-states, the time constants, 
and a family of curves generated modeling the same protocols 
used for Figs.6C of the experimental paper.

The kinetic parameters used here are from the modeling paper.
They where chosen by the authors to fit the time course 
of the current obtained from whole-cell data in their own 
laboratory (experimental paper).

The peak conductance has been adjusted to give approximately the
same peak currents shown in the experiments.
 
Under unix systems:
to compile the mod files use the command 
nrnivmodl 
and run the simulation hoc file with the command 
nrngui kinetics.hoc

Under Windows using NEURON 5.1:
to compile the mod files use the "mknrndll" command.
A double click on the simulation file
kinetics.hoc 
will open the simulation window.

Questions on the model parameters should be directed to the 
authors of the modeling paper.

Questions on how to use this model with NEURON
should be directed to michele@pa.ibf.cnr.it
