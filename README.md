# Grey-Seal-PVA
Code for the manuscript "120 years of ecological monitoring data indicates that current Baltic grey seal hunting quotas are unsustainable. "
.zip file containes code and data compiled to assess the impact of hunting on the Baltic grey seal.

Scripts:

  Basic_model.R  Age structured single sex popualiotn model
  Generation_time_calculator.R  Function to calcualte generation time
  Parameters.R  Parameters for the blatic grey seal population model
  
  1_Ordered_scripts.R  Grey seal PVA script 1, load packages and base scripts for core parameters and functions
  
  2_Historical_data.R  Grey seal PVA script 2, plot hitstorical populaiton estimates alongside current aerial survey data
  3_Explicit_populaiton_modelling.R  Grey seal PVA script 3, estimate intrinsic growth rate givne moult survey data
  4_Fertility_survival_estimation.R  Grey seal PVA script 4, estimate fertility based on data and parameterise a leslie matrix through modification of first year survival
  5_Undisturbed_population_modelling.R Grey seal PVA script 5,  estimate vital rates fro an undistturbed popualiton by adding hunted animals back into the popualiton
  
  6_Scenarios.R Grey seal PVA script 6, Running simulations with a range of scenarios outlined in Table 1 
  7_Risk_averages.R Grey seal PVA script 7, Estimating the risk of i) stabilising below the precautionary RL, stabilising below the critical RL, 10% decline in three gneerations, 50% decline in 3 gneerations, 70% decline in   3 generations

*scripts should be run in order

Data:

  Areial_Counts.csv  moult survey counts for the whole baltic
  Historical.csv  estimates of historical popualoitn size for the whole baltic from hunting records
  Ice.csv  record of maximum extend of baltic sea ice
  age_structures.csv  age, source country, and manner of death for seals
  bycatch_structure.csv  age structure of bycaught animals
  grey_seal_hunting.csv  summary of hunting in Sweden and Finland
  hunt_structure.csv    age structure of hunted animals 
  population_counts.csv  moult survey counts for the whole baltic
  reproduction.csv  summary of reporductive rates accross age classes
  Compiled risks.csv  outputs of risk modelling from popualiotn simulations
