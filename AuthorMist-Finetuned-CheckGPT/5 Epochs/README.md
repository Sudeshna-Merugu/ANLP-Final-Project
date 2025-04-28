# AuthorMist (finetuned - 5 epochs) as a Paraphraser
### Make sure you have the cloned the CHECKGPT Dataset in the directory
#### If you don't want to run the test data on AuthorMist, to save time (takes about 90 minutes), you can use the `paraphrased_results.csv` in this directory and run from the Detection Cell
1. Separating the AI generated and Human Generated texts from the test dataset
2. Loading AuthorMist as a paraphraser for baseline results
3. Passing the results to detector models, RADAR and DETECTGPT (to get scores and labels)
5. Getting AUROC, F1, Attack Success Rate (FNR)
6. Plotting the distributions of the detector score on AI samples and Human samples
7. Plotting the ROC Curve
8. Plotting the CDF Curve


