# Neural Named Entity Recognition — COS801 Group Project

Academic group work exploring neural sequence labelling with Python and TensorFlow/Keras. This repository is a fork of [MalwandlaN/COS801_Group_Project_2025](https://github.com/MalwandlaN/COS801_Group_Project_2025); the implementation and project materials reflect collaborative work.

## Technical focus

The notebooks explore word and character embeddings, casing and part-of-speech representations, convolutional character features, bidirectional LSTMs, attention and conditional random fields. The code covers text preprocessing, feature construction, model experiments and prediction generation.

## Repository contents

- `code/BiLSTM_CNN_Disaster_NER.ipynb`
- `code/Improved_version_of_COS801_project.ipynb`
- `code/Copy_of_Improved_version_of_COS801_project.ipynb`
- `data/`: project data files.
- `docs/`: methodology and supporting documents.

## Reproduction notes

Review the selected notebook before running it in Google Colab or Jupyter. Update Google Drive mounts and hard-coded working directories to your own environment, and confirm the expected input files. The notebooks contain TensorFlow/Keras version changes and TensorFlow Addons/CRF dependencies; use a compatible environment for the chosen experiment.

There is no unified installation or execution script in the current repository. Training, evaluation and model variants are organised within the notebooks. No independently verified benchmark result is claimed here.

## Attribution

Retain attribution to the original repository, its contributors and the referenced data and methods. Merhawi Hailu presents this fork as part of an academic group portfolio, rather than claiming sole authorship of the complete implementation.

## Next steps

Consolidate duplicate experiment notebooks, document a compatible environment, identify a canonical training/evaluation notebook and record the contribution of each team member.
