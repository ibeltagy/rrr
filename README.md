
Overview
----------------
This is a list of entailment rules that are extracted from the RTE part of the SICK dataset (http://alt.qcri.org/semeval2014/task1/). 
Logical inference + perfect predictions for these rules give near perfect score in SICK RTE. 
For more details, check our paper: *Representing Meaning with a Combination of Logical Form and Vectors*. 


Download
----------------
The releases of this dataset can be downloaded from here: https://github.com/islambeltagy/rrr/releases


Cite
----------------
If you use this dataset in your work, please cite our paper: 

    @article{beltagy:cl15, 
    title = {Representing Meaning with a Combination of Logical Form and Vectors}, 
    author = {Islam Beltagy and Stephen Roller and Pengxiang Cheng and Katrin Erk and Raymond J. Mooney}, 
    year={2015}, 
    archivePrefix = {arXiv},
    eprint        = {????.????},
    primaryClass  = {???-??}
    }


License
----------------
This data set is released under a Creative Commons Attribution-NonCommercial-ShareAlike 3.0 
Unported License (http://creativecommons.org/licenses/by-nc-sa/3.0/deed.en_US)


Contents
----------------
The rules are split into a training and testing sets, extracted from the training and testing parts of SICK respectively. 
Each file has more than 6,200 rules. Rules have three types, Entail, Neutral and Contradict. 


Files format
----------------
Each file has the following columns: 

- ruleID: an ID

- pairIndex: ID of the RTE pair where the rule is extracted from

- annotation: rule types: 1, 0 and -1 for Entail, Neutral and Contradict

- ruleLhs: the LHS of the rule. Each word is followed with *-i* where *i* is the index of the word in the source sentence

- ruleRhs: the RHS of the rule

- text: the Text where ruleLhs is extracted from

- hypothesis: the Hypothesis where ruleRhs is extracted from


Notes and Future Work 
----------------

