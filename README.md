# biolmodel
Computer modeling in biology course 2019/2020/2

Luca_epimodel_agegroup:
  - Add metadata dataframe for each individual specifying age group and sex based on demography data
  - Set up network so that connections within age groups is more likely than outside age groups
  - Make children transmit the disease with a higher probability
  
  
netepi_recovery (Benedek):
  - Recovery added to the basic epidemic network model: at each time step recovered individuals are chosen based on               recovery.time and rec.prob parameters. Recovery time indicates the required minimal elapsed time to recover. 
  - Group info in each time step is stored in dataframe (recovered, infected, susceptible groups).
