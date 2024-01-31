# ChISELS

Chemically Induced Surface Evolutions with Level Sets

SCR# 943

Musson, Lawrence; Schmidt, Rodney; Plimpton, Steven; Karpf, Henry

ChISELS is used for the theoretical modeling of detailed surface chemistry and consomitant surface evolutions occurring during microsystem fabrication processes conducted at low pressures. Examples include physical vapor deposition (PVD), low pressure chemical vapor deposition (PECVD), and plasma etching. Evolving interfaces are represented using the level-set method and the evolution equations time integrated using a Semi-Lagrangian approach. A Ballistic transport model is employed to solve for the fluxes incident on each of the surface elements. Surface chemistry leading to etching or deposition is computed by either coupling to Surface Chemkin (a commercially available code) or by providing user defined subroutines. The computational meshes used are quad-trees (2-D) and oct-trees (3-D), constructed such that grid refinement is localized to regions near the surface interfaces. As the interface evolves, the mesh is dynamically reconstructed as needed for the grid to remain fine only around the interface. For parallel computation, a domain decomposition scheme with dynamic load balancing is used to distribute the computational work across processors.
