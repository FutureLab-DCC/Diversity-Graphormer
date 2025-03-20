# Diversity-Graphormer

This repository contains data (all freely available) and code to reproduce the experiments from the paper "Graphormer Meets Diversity: Insights from Hate Speech Detection on 4chan"
![Graphormer Figure](https://github.com/FutureLab-DCC/Diversity-Graphormer/blob/62408a30418af4ec4b07085ac14671f9bdee4fcc/Files/paperfig2.png)

The Files folder contains a zip file with all the datasets used in training and evaluating the proposed and baseline models:
- The [Slur corpus](https://github.com/networkdynamics/slur-corpus) file ("kurrek.2020.slur-corpus.csv")
- The [4chan Dataset](https://github.com/YitingQu/meme-evolution) file ("rewire.txt")
- The [iSarcasm](https://github.com/dmbavkar/iSarcasm) training file ("trainEN.csv")
- The set used for the qualitative validation of the models, with examples from the 4chan Dataset ("HS Expert.csv")
- The Trained Models folder, with the trained models in .pt

The Notebooks folder contains the code to train and evaluate the models.


<code style="color : Orangered">⭕ DISCLAIMER: The examples of hateful comments included in the training and evaluation data are presented to allow reprodutibility of the classification process. These comments do not reflect the views or beliefs of the authors.⭕</code>
