# mol_gen
Molecule generation and optimisation

GA_mol.py: Genetic algorithm code. Uses crossover.py and mutate.py. Initial mating pool is drawn from 1000.smi, which is the first 1000 entries in https://github.com/tsudalab/ChemTS/blob/master/data/250k_rndm_zinc_drugs_clean.smi

sascorer.py and all txt and gz files needed by for the scoring is taken from https://github.com/tsudalab/ChemTS

MCTS_mol_expand.py and MCTS_mol.py adapted from https://github.com/haroldsultan/MCTS/blob/master/mcts.py. MCTS_mol_expand.py is the leaf parallelised version of MCTS_mol.py (soon to be depreciated).

The .p files (used by MCTS) is generated by analyze_ZINC.py. More info here: http://proteinsandwavefunctions.blogspot.com/2018/07/making-random-molecules-one-atom-at-time.html

The code is still in the prototype stage and needs to be refactored.