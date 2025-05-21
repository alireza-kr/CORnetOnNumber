# CORnet On Numbers

Code from our NeurIPS 2024 ([Behavioral ML](https://sites.google.com/view/behavioralml/)) paper investigating how pruning in CORnet challenges the role of number-detector units in CNN-based representations of numerosity.

Links to download the model weights:
- [[Link]](https://osf.io/download/qdres/) CORnet-Z trained on DeWind dataset
- [[Link](https://osf.io/download/5jq4n/)] CORnet-S trained on DeWind dataset

Links to download the images to train the model:
- [[Link](https://files.osf.io/v1/resources/6gdfu/providers/osfstorage/66e16af872b893a38e459e9e/?zip=)] DeWind dataset

Important scripts:
- **feature_selection.py**: Run the pruning procedure
- **numersority_units.py**: Run the ANOVA procedure
