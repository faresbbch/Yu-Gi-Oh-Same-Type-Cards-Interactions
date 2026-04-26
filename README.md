# Are Yu-Gi-Oh! Cards Sharing the Same Type More Likely to Interact Together?

*Blibeche Farès — April 2026*

This study investigates whether pairs of Yu-Gi-Oh! cards sharing the same monster type are more likely to interact together. Using a dataset of annotated card pairs produced by a large language model (Llama 3.1 8B), we fitted a multivariate regression (R² = 0.02) on monster-pairs, modelling the number of interactions between two cards (`interactCount`) as a function of shared type, shared attribute, shared frametype, level difference, attack difference, defence difference, and annotation-quality control features.

*Shared type* (β = 0.18, p < 0.001) and *shared attribute* (β = 0.13, p < 0.001) emerge as the strongest positive predictors, while combat-stat differences show no significant effect. Annotation-quality controls — *stability* (β = −0.68, p < 0.001) and *repeated* (β = −0.34, p < 0.001) — carry large negative coefficients, indicating that the model's variability introduces noise that should be accounted for when interpreting the main effects.

**Keywords:** Yu-Gi-Oh!, card interactions, deck synergy, LLM annotation, Llama 3.1 8B, multivariate regression.
