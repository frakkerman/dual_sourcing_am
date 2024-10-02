# Solving Dual Sourcing Problems with Supply Mode Dependent Failure Rates

This project contains code for the paper titled "Solving Dual Sourcing Problems with Supply Mode Dependent Failure Rates" by Fabian Akkerman, Nils Knofius, Matthieu van der Heijden, and Martijn Mes, see: [working paper]

## Citation

When using the code or data in this repo, please cite the following work:

```
@Article{Akkerman2024,
	author={Akkerman, Fabian
 	and Knofius, Nils
	and van der Heijden, Matthieu
	and Mes, Martijn},
	title={Solving Dual Sourcing Problems with Supply Mode Dependent Failure Rates},
	year={2024}
}
```

The iterative procedure was implemented using the implementation by Bötcher et al. as example, so if you use that piece of code please also cite their work, see: [this github repo](https://github.com/INFORMSJoC/2022.0136)

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
* Copyright 2024 © [Fabian Akkerman](https://people.utwente.nl/f.r.akkerman), [Nils Knofius](https://scholar.google.com/citations?user=ZlTzOdAAAAAJ&hl=en), [Matthieu van der Heijden](https://research.utwente.nl/en/persons/matthieu-van-der-heijden), [Martijn Mes](https://www.utwente.nl/en/bms/iebis/staff/mes/)
