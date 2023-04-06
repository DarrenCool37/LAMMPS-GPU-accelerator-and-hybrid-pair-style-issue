# LAMMPS-GPU-accelerator-and-hybrid-pair-style-issue
LAMMPS GPU accelerator and hybrid pair style issue

Hi,
I am trying to use GPU accelerator in LAMMPS. I am using hybrid pair style input with "lj/cut/tip4p/long" and "lj/cut/coul/long". And I have modified the "neigh no" in the script (sc file). It still shows me an error "Non-numeric pressure - simulation unstable". However, when I only use CPU, there is no such error showing up and the simulations can run perfectly. I am not sure why this happened. I have put the key features of my input file and script in this repository. Can anyone help?
Thanks in advance