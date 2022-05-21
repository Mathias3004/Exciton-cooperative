# Exciton-cooperative
A study of cooperative effects in exciton sample by periodically modulating the resonance. 

Mean_Field
MF_sample_collect.ipynb: Self-consistently solve polarization for for 2D sample of exciton (as induced by mean field emission of medium) using lumped-element discretization and parallel threading to loop over parameter space. Polarization samples are stored in .pkl file for later analysis.
MF_analyze_angle_resolved.ipynb: Perform angle-resolved measurement from obtained polarization samples

Monte Carlo (less accurate and relevant)
Generate random samples of emitters (random position and resonance) along a periodic lattice. Compute final averaged polarization as would be measured in experiment.
