# ContextSRH

This repository contains the labeled contextual questions dataset, ContextSRH, from the paper "Evaluating Biases in Context-Dependent Sexual and Reproductive Health Questions". The file contains each question and its source. We mark an 'x' for each attribute if the question is dependent on that attribute (i.e. age, sex, or location), and therefore, answers to the original question are not equivalent across all groups for that attribute. For example, the question "I keep getting yeast infections. What causes them?" is marked with an 'x' for age and sex, indicating that the answer differs for female/male sex and younger/older ages. While in some cases, several groups will have similar answers, there will be at least one group with a different correct response. 

If you use this dataset, please cite our paper:
```
@article{levy-contextual-questions,
    title = {Evaluating Biases in Context-Dependent Sexual and Reproductive Health Questions},
    author = {Levy, Sharon  and
      Karver, Tahilin Sanchez  and
      Adler, William D.  and
      Kaufman, Michelle R.  and
      Dredze, Mark},
    year = {2024},
    journal={arXiv preprint arXiv:2403.04858}
}
```
