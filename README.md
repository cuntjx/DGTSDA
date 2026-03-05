# DGTSDA
DGTSDA: identifying potential snoRNA-disease associations via dual graph transformer network 

# Data and code  
## Data  
snorna_secondary_structures.csv and snorna_sequences.fas：These file stores the name and the sequence of snoRNAs.  

disease_description.txt: This file stores the description of diseases.  

sd_association.csv and snorna_disease_mat.csv: These file stores the association information between snoRNAs and disease. 

hetero_graph_2-4.pkl(SDAD dataset): This file stores the features of snoRNA and disease which also can be download from URL: https://github.com/BCB4PM/GL4SDA. 

The PSnoD dataset is available at URLs:https://github.com/linDing-groups/PSnoD or https://github.com/mariamuna04/gbdtsvm. 



# Environment  
DGTSDA is implemented to work under Python 3.9 and Jupyter Notebook  
torch >=2.5.0  
numpy >=1.22.0   
pandas >=1.5.0  
torch_geometric >=2.5.0  
 
# Run steps  
DGTSDA.ipynb can be upload into Jupyter Notebook and select ‘run all’ to train the model and obtain prediction scores for snoRNA-disease associations.  

    



