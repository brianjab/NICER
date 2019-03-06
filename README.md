# NICER in Julia
Contains the Julia code of the "NICE" integrated assessment model

The original model from fdenning (https://github.com/fdennig/NICER) was running with Julia 0.6.
This update allows to run under Julia 1.1.0.

Content:
- The "Optimization.jl" file contains the template for the main types of optimization. This is the main program.
- The "createPrandom.jl" and "Function_definitions.jl" contain the model.
- The "/Data" subfolder contains two data files required to run the model, i.e. certainPARAMETERS.jld and dparam_i.jld.
- The "/specificRoutines" and "/preOct2016" subfolders have not been considered nor yet updated for Julia 1.1.0.

Update done with Brian Jabarian (PSE-Princeton). 

See following paper to get more information on model: https://www.pnas.org/content/112/52/15827
