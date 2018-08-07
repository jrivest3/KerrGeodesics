<img src="generic_orbit_3d_corotating.png" width="300px">

The KerrGeodesics package for Mathematica provides functions for computing bound timelike geodesics and their properties in Kerr spacetime.

## Getting the package

The latest development version will always be available from the project git
repository:

```bash
git clone https://github.com/BlackHolePerturbationToolkit/KerrGeodesics.git
```

## Requirements


The KerrGeodesics package requires a recent version of Mathematica. It is typically
tested with only the latest available version.

## Installation

Clone the repository and place it somewhere on Mathematica's $Path.
Typical locations are inside ${HOME}/.Mathematica/Applications/ for Linux or
inside ${HOME}/Library/Mathematica/Applications/ for Mac OSX.


## Usage

The package may be loaded into Mathematica using the command:

```Mathematica
<< KerrGeodesics`
```


## Documentation and examples

Examples are included in the documentation. See the
KerrGeodesics page in Documentation Center. The package includes functions to calculate, e.g.,

* Constants of motion and orbital frequencies
* The orbital trajectory and 4-velocity
* The location of the photon sphere
* The location of inner-most bound and inner-most stable circular/spherical orbits
* The location of the separatrix between bound and plunging orbits

## Changelog

7 August 2018: Added generic orbit calculation of the orbit (thanks for M. van de Meent for contributing code). Currently the code is separated in KerrGeoOrbit2[..] but will soon replace the earlier code.<br>
7 September 2017: Initial version publicly released.<br>
10 June 2017: Initial version created.

## Known problems

Known bugs are recorded in the project [bug tracker](https://github.com/BlackHolePerturbationToolkit/KerrGeodesics/issues).

## License

This code is distributed under the University of Illinois/NCSA
Open Source License. Details can be found in the LICENSE file.


## Authors

Niels Warburton
Maarten van de Meent