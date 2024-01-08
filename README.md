The data of paper "Deep-potential enabled multiscale simulation of gallium nitride devices on boron arsenide cooling substrates"
1. The BAs file include lammps input file of EMD, BAs model file and NNP model. One can use follw command to perform simulation.
                                                            lmp -in in.thermal
   Besides, the  ShengBTE results from 3-phonon and 4-phono are included in ShengBTE file.
2. The GaN file include lammps input file of EMD, GaN model file and NNP model. One can use follw command to perform simulation.
                                                            lmp -in in.thermal
   Besides, the  ShengBTE results from 4-phonon are included in ShengBTE file.
3. The BAs-GaN file include lammps input file of NEMD, heterostructure model file and NNP model. One can use follw command to perform simulation.
                                                            lmp -in in.thermal
4. The active learning framework that includes the initial file, running file, machine configuration file and other input files.It is worht to note that the  machine      configuration file may not normally work, duo to different cluster environment. 
