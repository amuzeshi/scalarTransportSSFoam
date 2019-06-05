# scalarTransportSSFoam

Hello 

I've developed a scalarTransportFoam solver for steady state named scalarTransportSSFoam (SS for Steady State). 

This solver is based on simpleScalarFoam which is a steady-state flow solver with scalar transport and comparing it with scalarTransportFoam which is generally unsteady.

Note: 

To run a case, copy 0, constant and system folders from scalarTransportFoam tutorial and change ddtScheme in fvSchemes file to steadyState.

### Prerequisites

You NEED to have OpenFOAM installed !

### Installing

To complie, go through the terminal to the download directory where *.C, *.H files and Make folder are present. Then execute   
```wmake```   
Then wait and look if no error occurs.

## Authors

* **Ali Shayegh** - *Initial work* - [Ali Shayegh](https://github.com/amuzeshi)

## License

This project is licensed under the GPL v3 License.

## Acknowledgments

* I'd like to say thanks to the authors of [simpleScalarFoam](https://openfoamwiki.net/index.php/Contrib_simpleScalarFoam).
