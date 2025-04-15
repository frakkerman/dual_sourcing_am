# Solving Dual Sourcing Problems with Supply Mode Dependent Failure Rates

This project contains code for the paper titled "Solving Dual Sourcing Problems with Supply Mode Dependent Failure Rates" by Fabian Akkerman, Nils Knofius, Matthieu van der Heijden, and Martijn Mes, see: https://doi.org/10.1080/00207543.2025.2489755

## Citation

When using the code or data in this repo, please cite the following work:

```
@Article{Akkerman2025,
	author={Akkerman, Fabian
 	and Knofius, Nils
	and van der Heijden, Matthieu
	and Mes, Martijn},
	journal = {International Journal of Production Research},
	title={Solving Dual Sourcing Problems with Supply Mode Dependent Failure Rates},
	publisher = {Taylor \& Francis}
	year={2025}
}
```

The dual index policy, part of the iterative procedure (IWA), was implemented using the implementation by Bötcher et al. as example, so if you use the dual index formulation with the iterative procedure that piece of code please also cite their work, see: [this github repo](https://github.com/INFORMSJoC/2022.0136)

## Environment

The code is written in C++20, in the reinforcement learning toolbox DynaPlex. We tested our project on a Windows 11 environment and on a Linux HPC.


## Structure

The submodule folder links to the branch "dual_sourcing_am" in the DynaPlex code repository.


## To the make the code work

Ensure that you clone the repository with submodules:

```
git clone --recurse-submodules
```

For further information, we refer to the documentation of DynaPlex
 
## Contributing

If you have proposed extensions to this codebase, feel free to do a pull request! If you experience issues, feel free to send us an email.

## License
* [MIT license](https://opensource.org/license/mit/)
* Copyright 2025 © [Fabian Akkerman](https://people.utwente.nl/f.r.akkerman), [Nils Knofius](https://scholar.google.com/citations?user=ZlTzOdAAAAAJ&hl=en), [Matthieu van der Heijden](https://research.utwente.nl/en/persons/matthieu-van-der-heijden), [Martijn Mes](https://www.utwente.nl/en/bms/iebis/staff/mes/)
