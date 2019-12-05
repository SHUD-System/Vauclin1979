# V-catchment simulation with SHUD mdoel

*SHUD - Solver of Hydrological Unstructured Domain.*

The V-Catchment (VC) experiment is a standard test case for numerical hydrological models to validate their performance for overland flow along a hillslope and in the presence of a river channel.
The VC domain consists of two inclined planes draining into a sloping channel. 

Both hillslopes are $800 \times 1000 m$ with Manning's roughness $n=0.015$.  The river channel between the hillslopes is $20$ m wide and $1000$ m in length with $n=0.15$. The slope from the ridge to the river channel is 0.05 (in the $x$ direction), and the longitudinal slope (in the $y$ direction) is 0.02.

Rainfall in the VC begins at time zero at a constant rate of $18 mm/hr$ and stops after 90 min, producing $27$ mm of accumulated precipitation. Since evaporation and infiltration is not involved in this simulation, the total outflow from lateral boundaries and the river outlet must be the same as the total precipitation (following conservation of mass).  



## R scripts

The R scripts include:

1. Build the V-catchment
2. Generate the physical and model parameters
3. Run simulations.
4. Visulize results
5. Compare the result with literature (Shen2010).



## Data

1. Input files for SHUD model.
2. Result files from SHUD model.
3. Digitalized data from Shen2010.



## Policy

The script and data are open access for any purposes. I would be most grateful if you could send me an email (at lele.shu@gmail.com) when they helps you.

