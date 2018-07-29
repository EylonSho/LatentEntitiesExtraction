# LEE - Latent Entities Extraction: 
# How to Extract Entities that Do Not Appear in the Text?
Keras implementation for the Multi-Task Learning &amp; Task-Grouping Model as described in the original paper, CoNLL 2018.

## Instructions
* Clone the repository
* Install requirements according to `requirements.txt`
  * Use `pip install -r requirements.txt`
* Download word bio-nlp embedding [here](https://drive.google.com/file/d/0BzMCqpcgEJgiUWs0ZnU0NlFTam8/view)
   * Place `PubMed-shuffle-win-30.bin` in the path: `data/bio-nlp-vec/`
* Follow jupyter notebook `multitask_learning_with_task_grouping_for_lee.ipynb` for training end evaluating

## Data
The used data-set constructed based on [Reactome](https://reactome.org/) database of biochemical-reactions.
