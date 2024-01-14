# pitch-plunge-omp
This code simulates the unsteady flow past a moving body, e.g. a pitching-plungig elliptic foil or an oscillating cylinder cylinder, with prescribed kinematics.

Use the make file for compilation. Enter make in the terminal to compile the source codes finally generating run_executable.out. Next, take hint from the jobscripts (openmp.cmd or openmpscript.sh) provided to run the executable on a cluster or a local system.

## Citation

1. [Capturing the dynamical transitions in the flow-field of a flapping foil using Immersed Boundary Method](https://www.sciencedirect.com/science/article/abs/pii/S0889974620300128)
```
@article{majumdar2020capturing,
  title={Capturing the dynamical transitions in the flow-field of a flapping foil using Immersed Boundary Method},
  author={Majumdar, Dipanjan and Bose, Chandan and Sarkar, Sunetra},
  journal={Journal of Fluids and Structures},
  volume={95},
  pages={102999},
  year={2020},
  publisher={Elsevier}
}
```

2. [Performance Enhancement of an Immersed Boundary Method Based FSI Solver Using OpenMP](https://www.nal.res.in/cfdimgs/FullPaper/P27-Performance%20Enhancement%20of%20an%20Immersed%20Boundary%20Method.pdf)

```
@article{shahperformance,
  title={Performance Enhancement of an Immersed Boundary Method Based FSI Solver Using OpenMP},
  author={Shah, Chhote Lal and Majumdar, Dipanjan and Sarkar, Sunetra}
}
```

3. [Investigating the Transitional Dynamics in the Flow-Field Past a Flapping Foil using Immersed Boundary Method](https://www.researchgate.net/publication/376596327_Investigating_the_Transitional_Dynamics_in_the_Flow-Field_Past_a_Flapping_Foil_using_Immersed_Boundary_Method)

```
@phdthesis{majumdar2022thesis,
  title={Investigating the Transitional Dynamics in the Flow-Field Past a Flapping Foil using Immersed Boundary Method},
  author={Majumdar, Dipanjan},
  year={2022},
  school={Indian Institute of Technology Madras, Chennai, India}
}
```
