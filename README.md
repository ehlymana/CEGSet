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

If you use this software tool for your research, please cite the following work:

```
E. Krupalija, Š. Bećirović, I. Prazina, E. Cogo and I. Bešić, "CEGSet: Collection of standardized cause-effect graph specifications," submitted to 12th Mediterranean Conference on Embedded Computing, 6-10 June 2023, Budva, Montenegro.
```
