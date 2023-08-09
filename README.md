# ValidationBias
When assessing the effectiveness of PU models, like those used in gene prioritization, validation sets containing positive examples are frequently employed. It is often assumed that positive examples are selected completely at random (SCAR) to the validation set. The SCAR assumption means that each positive example has the same probability to end up in the validation set.

In this project, we provide tools to test the SCAR assumption. The recommended approach, that calculates p-values for rejection of the SCAR assumption analytically, is described in ```Validation_bias_detection_procedure.ipynb```.
