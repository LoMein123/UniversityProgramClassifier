# BERT university program classifier
This model was specifically created for my other project, "DecisionsBot: A discord bot that records (Ontario) university decisions and generates statistics".  It classifies user inputted university programs into categories. 

For example: "Life Science", "MLS", "Life Sci with ChemBio Spec", "Life Science (Co-Op)", "Life Sciences Gateway"` are all classified under the category `"Life Science". 

In the context of the decisions bot, the classifier is used to tag user inputted programs so that statistical graphs can be generated.

**Technologies Used**:
- BERT from HuggingFace Transformers
- PyTorch
- Scikit-Learn
- Jupyter Notebooks
- Pandas

## Spellchecker and Dataset
The file `Corpus.txt` is used for the spellchecker.  It contains words found in the training dataset.  The "10000000" behind every word just gives it more bias in the spellchecker.  

The training dataset was taken from the spreadsheet that the decisions bot records university decisions in, and manually labeled.