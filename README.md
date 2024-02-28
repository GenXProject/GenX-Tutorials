# GenX-Tutorials
Welcome to the GenX Tutorials! In this series, we go over several aspects of GenX and how to use them. 

__These Tutorials are set to run on GenX version 0.3.6, and use Example Systems adapted to that version as well.__ GenX has since been updated; using a newer version will cause some conflicts to occur.

To run these tutorials, make sure to have Jupyter notebook installed. From there, Tutorial 0 goes over how to install IJulia and GenX. 

### Tutorial 0: Getting Started:
Tutorial 0 goes over installing IJulia and GenX, and how to run the Tutorials from your computer. No packages are needed to run Tutorial 0.

### Tutorial 1: Configuring Settings:
Tutorial 1 shows GenX's default settings, and how to run an instance of GenX. 
Packages needed are:
* YAML
* CSV
* DataFrames

### Tutorial 2: Network Visualization
Tutorial 2 shows how the example grid in `SmallNewEngland/ThreeZones` looks on a map of New England. 
Packages needed are:
* CSV
* DataFrames

### Tutorial 3: K-means and Time Domain Reduction
Tutorial 3 goes over the Time Domain Reduction (TDR) feature, how it is configured, and how it uses k-means to work.
Packages needed are:
* YAML
* CSV
* DataFrames
* VegaLite
* PlotlyJS
* Plots
* Clustering
* ScikitLearn

### Tutorial 4: Model Generation
Tutorial 4 explains the optimization package JuMP, and how GenX generates the model before solving it.
Packages needed are:
* JuMP
* HiGHS

### Tutorial 5: Solving the Model
Tutorial 5 explains how GenX uses JuMP to solve the model, and how infeasibilities work.
Packages needed are:
* JuMP
* HiGHS

### Tutorial 6: Solver Settings
Tutorial 6 goes over the different settings one can specify before solving GenX, and shows example runs of PreSolve, Crossover, and Feasibility Tolerance.
Packages needed are:
* JuMP
* HiGHS
* YAML
* DataFrames
* Plots
* Plotly

### Tutorial 7: Setup -- Policy Constraints
Tutorial 7 goes over policy constraints CO2 Cap, Minimum Capacity, Energy Share Requirement, and Capacity Reserve Margin, shows how to turn them on in GenX, and how they decrease total emissions.
Packages needed are:
* JuMP
* HiGHS
* CSV
* DataFrames
* Plots
* StatsPlots
