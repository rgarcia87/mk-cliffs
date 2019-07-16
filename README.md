# mk-cliffs
Minimalistic microkinetic model with volcanoes and cliffs

The Maple worksheets (.mws) contain the microkinetic model for the reactions: 
  A(g) => A* => Q* => Q(g)
  B(g) => B* => 2I*
  Q*+I* => P* => P(g)
  
Thermodynamic Linear-Scaling Relationships (tLSR) link the thermodynamics of A* and B* with I* and Q*, which are varied. Also, kinetic scalings (kLSR) are used to predict the activation energy of the three internal reactions. The 1D volcanoes come from the 2D ones by making E(I*)=-1.55-E(Q*) [eV]. That line goes through the maximum selectivity region and illustrates very well a sudded drop of selectivity (cliff) caused by Q* poisoning. 

The post-processing section prints the volcanoes as ".txt" files. These files were later analyzed in the "results.xlsx" spreadsheet. 
