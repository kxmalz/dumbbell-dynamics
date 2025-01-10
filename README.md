This is a code to simulate the dynamics of dumbbell-shaped colloidal particles
near the non-penetrable wall. It uses the Pychastic package [1] for stochastic differential equations solving. To effectively describe particle's orientation, it employs the algorithm of Evensen et al. [2]. The particle's mobility matrix was found with HYDROMULTIPOLE code [3] and further approximated with the methods presented in Lisicki et al. [4]. The code attempts to recreate the experiment of Verweij et al. [5]. The comprehensive description can be found at github.com/kxmalz/master-thesis.

**To see and run the code, simply open the VS notebook (.ipynb).**

[1] https://scipost.org/10.21468/SciPostPhysCodeb.11
[2] https://doi.org/10.1002/mats.200800031
[3] https://doi.org/10.1063/1.4958727
[4] http://bluebox.ippt.pan.pl/~mekiel/6_Feuillebois20090812.pdf
[5] https://link.aps.org/doi/10.1103/PhysRevE.102.062608
