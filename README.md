Phenotype-Genotype relation extraction
(c) Maryam Khordad 2014
The University of Western Ontario

Train a model:

usage: train.sh args[]
args[0]: Train directory
args[1] Test directory
args[2] Number of Folds
args[3] the number of iterations
args[4] Confidence level Lower bound
args[5] Confidence level upper bound
args[6] The number of Iterations where the rule-based predictions are taking into account



Test a model: 

usage: test.sh args[]
args[0]:Test directory
args[1] Output file
args[2] Model file made in training
