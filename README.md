# ReaxFF_cement
ReaxFF potentials for cement based material

ReaxFF is a reactive force field created originally for hydrocarbons by Adri C.T van Duin and his coworkers in the Materials and Process Simulation Center group from Caltech University, and extended afterwards to inorganic systems. ReaxFF uses a bond-order formalism for bonding and angular interactions, together with a polarisable charge equilibration method (Qeq) to describe both reactive and non-reactive interactions between atoms. 

The provided files are the parameterization of potentials for Si-Ca-O-H systems by H.Manzano and coworkers, already presented in a suitable form to use with two open-source well mantained codes that have a ReaxFF implementation

a) ffiel-CaSiOH-lammps.reax: force field formatted for the LAMMPS simulation code.
   http://lammps.sandia.gov/

b) ffiel-CaSiOH-gulp.reax: force field formatted for the GULP simulation code.
   http://projects.ivec.org/gulp/downloads.html
   
# Notes: 

The file includes carbon (C) just for historical reasons, the Ca-C interactionsare not developed yet. 
     
The Ca-O-H interactions have been tested independently and together with the Si-O-H setdeveloped previously by van Duin and coworkers in oxides, hydroxides, nanoclusters, and aqueous environments.
 
The, Si-Ca potential were not developed explicitly so potentials reproduces oxides and aqueos systems, but there is no guarantee that it will work in alloys

# Citations:

- Please cite the reaxFF method as:

Senftle, T. P., Hong, S., Islam, M. M., Kylasa, S. B., Zheng, Y., Shin, Y. K., ... & Van Duin, A. C. (2016). The ReaxFF reactive force-field: development, applications and future directions. npj Computational Materials, 2(1), 1-14.

- Please cite the Ca-O-H set as:

Manzano, H.; Pellenq, R. J. M.; Ulm, F.-J.; Buehler, M. J.; van Duin, A. C. T., Hydration of Calcium Oxide Surface Predicted by Reactive Force Field Molecular Dynamics. Langmuir 2012, 28 (9), 4187-4197.

- Please cite the full Ca-Si-O-H set if used for amorphous materials as one of the following:

Manzano, H.; Moeini, S.; Marinelli, F.; van Duin, A. C. T.; Ulm, F.-J.; Pellenq, R. J. M.,  Confined Water Dissociation in Microporous Defective Silicates: Mechanism, Dipole Distribution, and Impact on Substrate Properties. J. Am. Chem. Soc. 2012, 134 (4), 2208-2215.

Manzano, H.; Masoero, E.; Lopez-Arbeloa, I.; Jennings, H. M. Shear deformations in calcium silicate hydrates Soft Matter 2013, 9, 7333–7341.
