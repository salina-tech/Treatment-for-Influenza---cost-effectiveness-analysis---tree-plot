# Treatment-for-Influenza---cost-effectiveness-analysis---tree-plot

Aim: To evaluate the cost-effectiveness of using Abraxane as a treatment option for advanced pancreatic cancer, compared to providing Taxol, from a healthcare provider's perspective: A decision tree

Methods:
- Study Design: The decision tree model was constructed using R programming language, with several packages including ggplot2, lattice, caret, rpart, rpart.plot, and reshape2. 
- The input parameters were defined in a data frame that includes:
1. probability of adverse reactions
2. probability of being cured
3. life years gained or lost
4. costs of treatment
5. costs of adverse reactions
6. willingness to pay per life year gained
- Population: Patients with pancreatic cancer (N=28)
- Interventions: Abraxane versus Taxol
- Outcomes: Survival, quality-adjusted life years (QALYs), and costs

Results:
- The decision tree model estimated that the expected total costs of Oseltamivir treatment were $86.50, while the expected total costs of Zanamivir treatment were $95.25. The expected life years gained for Oseltamivir were 2.6, while the expected life years gained for Zanamivir were 2.5.
- The cost-effectiveness analysis revealed that Oseltamivir was the dominant treatment option, as it was less expensive and provided more life years gained compared to Zanamivir. 
- Sensitivity analysis (in progress)
