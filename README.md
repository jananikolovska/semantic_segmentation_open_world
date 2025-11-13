# Machine Learning for Computer Vision Assignment
University of Bologna, A.Y. 2024–2025.\
jana.nikolovska@studio.unibo.it

---

# Done so far
Happy with results so far - push also weights

# Todo
Check inside the notebook

---

## Notebook Execution and Dataset Storage

This notebook was executed using Google Colab. All datasets were stored on my Google Drive, with the following names: `small-train`, `small_validation`, and `small_test`. The entire workflow is contained within a single notebook file. There is a flag, `TRAIN_ON`, which allows you to choose whether to train a new model or use preselected weights.

## Development Process and Experimental Design

During development, I experimented with various learning rates, different backbones (ResNet50 and ResNet101), and the inclusion or exclusion of an auxiliary edge head. A major challenge was handling uncertainty around object edges, so many design decisions specifically targeted this issue. The approach taken was based on my own ideas and experimentation, rather than following any specific published papers.

All ideas and parameter tunings were initially tested on a smaller dataset. The results from these experiments are not included as they are not directly comparable to the final results, since they were not trained on the same amount of data. To keep the notebook clear and easy to follow two models were chosen for comparison, highlighting the design choice that had the most significant impact.


👋

