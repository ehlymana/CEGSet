# CEGSet

Collection of cause-effect graph specifications. It was created by using 30 papers from the relevant literature and contains a total of 65 cause-effect graphs.

The dataset features are located in the file *CEG dataset.csv*:

- Example name (identifier of the graph)
- ID (DOI or name of the paper from which the cause-effect graph was taken)

- C (number of cause nodes in the graph)
- I (number of intermediate nodes in the graph)
- E (number of effect nodes in the graph)
- Nodes (total number of nodes in the graph)

- DIR (number of direct logical relations in the graph)
- NOT (number of negation logical relations in the graph)
- AND (number of logical conjunction relations in the graph)
- OR (number of logical disjunction relations in the graph)
- NAND (number of logical negated conjunction relations in the graph)
- NOR (number of logical negated disjunction relations in the graph)
- Relations (total number of logical relations in the graph)

- EXC (number of exclusion dependency constraints in the graph)
- INC (number of inclusion dependency constraints in the graph)
- EXC ∆ INC (number of all-inclusion dependency constraints in the graph)
- REQ (number of required dependency constraints in the graph)
- MSK (number of masking dependency constraints in the graph)
- Constraints (total number of constraints in the graph)

- System requirements (specification of system requirements in the natural language if provided by the author of the paper, 'Not specified' otherwise).

This collection of graphs was created at the Department of Computer Science and Informatics, Faculty of Electrical Engineering, University of Sarajevo, Bosnia and Herzegovina.

If you use this dataset for your research, please cite the following work:

```
E. Krupalija, E. Cogo, Š. Bećirović, I. Prazina, D. Pozderac, and I. Bešić, "CEGSet: Collection of standardized cause-effect graph specifications," 12th Mediterranean Conference on Embedded Computing, 6-10 June 2023, Budva, Montenegro, pp. 1-4, doi: 10.1109/MECO58584.2023.10155063.
```

Machine learning methods were applied on the dataset in order to be able to predict cause-effect graph feasibility. The programming code for preprocessing the dataset in order to create two data formats (Boolean features and TF-IDF graph), as well as the achieved results, are available in the folder **Feasibility prediction**.

If you use the work on feasibility prediction for your research, please cite the following work:

```
E. Krupalija, E. Cogo, D. Pozderac, A. Ali Al Zayat, and I. Bešić, "Usage of Machine Learning Methods for Cause-Effect Graph Feasibility Prediction," The 5th International Conference on Machine Learning and Intelligent Systems (MLIS 2023), Macao, China, pp. 126-131, doi: 10.3233/FAIA230774.
```
