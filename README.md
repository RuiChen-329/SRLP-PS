# Datasets from Hongbo Li, Linwen Zheng, Rui Chen and Xianchao Zhang, (2023, working paper), Stochastic resource leveling in projects with flexible structures.

## Datasets 1000 simulation:

Duration data used to evaluate scheduling policy's performance.  

**J5**: 20 instances with 5 activities. Each row in the file represents a duration simulation.  
**J10**: 20 instances with 10 activities. Each row in the file represents a duration simulation.  
**J30**: 16 groups; each group contains 20 instances with 30 activities. Each row in the file represents a duration simulation.  
**J60**: 16 groups; each group contains 20 instances with 60 activities. Each row in the file represents a duration simulation.  

## Datasets SRLP PS data:

All the data related to SRLP-PS problem.  

**J5/J10**:   
  1 group of 20 instances.   
  *choice*: In each row, the first number represents the activity that triggers the choice, and the others represent the set of activities that are triggered by the choice.  
    *dependent*: In each row, the first number represents the optional activity that the triggers the dependent activity set, and the others represent the set of dependent activities that are triggered by the optional activity.  
    *mandatory*: All the activities that must be implenmented.  
    *minlag*: The number in row n and column m represents the minimum delay that the activity m starts after the end of the activity n.  

  Project network  
    All the Project network structure data generated using the project scheduling instance generator ProGen.  
    Kolisch, R., Sprecher, A., & Drexl, A. (1995). Characterization and generation of a general class of resource-constrained project scheduling problems. Management Science, 41(10), 1693–1703.  

**J30/J60**:   
  16 group of 20 instances. The data under the folder is the same as J5/J10.  

**PSPLIB**:  
  PSPLIB data (Kolisch & Sprecher, 1996) for J30 and J60.  
  Kolisch, R., & Sprecher, A. (1996). PSPLIB—a project scheduling problem library. European Journal of Operational Research, 96, 205-216.  

# Stochastic data for M2

Duration data for the scenario-based model M2. The data under the folder is the same as Datasets 1000 simulation.  
