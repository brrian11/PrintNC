# PrintNC in Solidworks

This is the [PrintNC](https://github.com/threedesigns/printNC) design rebuilt in Solidworks from the original Fusion360 files. For more information on PrintNC see the [website](https://threedesign.store/) and the [wiki](https://wiki.printnc.info/en/home)

- See the develop branch for the parametric steel version in progress.
- if you have an issue with the file, create an issue and and show a print screen and details of what is happining. because I'm on solidworks 2016 I cann't open files created from future versions. 

## Progress
I’ve just started out so not too much. I have the new V3 Z-axis mostly rebuilt. Starting to work on the gantry and base next from V2.X alpha.

**WARNING** This is still very much a work-in-progress. I cannot guarantee that there are no part interference, hole alignment mismatch, etc. I will be going over all of that after the initial complete design is finished.

## Notes
- See [equations.txt](src/equations.txt) for hole tapping and clearence used in these files. This file gets linked to sketches when necessary.
- Where possible I keep similar parts as different configurations. eg metric bolt lengths, steel stock, etc. This cuts down on the number of part files.
- The main assembly is broken up into sub-assemblies. Each subassembly is defined by its motion axis. When complete there will be x, y, z axis and frame sub-assemblies under the main assembly.
- Some parts have a 1 at the end of their names. This is so they don’t conflict with the imported IGST files I’m using as reference. Once the references are no longer needed, I will fix the naming of the part files.


## PrintNC standard size
Here is the standard size:
![standard size](images/PrintNC_standard_size.png)

## Paramizered sizes:
![2000x600 size](images/PrintNC_param_2000x600.png)
![500x500 size](images/PrintNC_param_500x500.png)

### Some other iamges:
![Z-axis](images/Z-axis.png)
![closeup](images/PrintNC_closeup.png)
