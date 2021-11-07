# IndonesianPOS


## Introduction

As  a  member  of  the  Malayo-Polynesian  languages,  Indonesian  is  spoken  by  a  large  population.However,  language  resources and processing tools for Indonesian are quite limited.Part-of-speech (POS) tagging aims to assign a particular POS  to a word, concerning its distribution and function in the context, which can provide valuable information for most natural  language processing tasks.This work introduces our work on designing an Indonesian part-of-speech (POS) tagset, including  29 tags, and constructing a large Indonesian POS corpus comprised of over 355,000 tokens.During the design and annotation  processes, we make judgments mostly from a typological perspective, following the specifications of Universal Dependencies,  while not missing those language-specific phenomena.In addition, we try to utilize several state-of-the-art sequence labeling  models, trained on the proposed corpus, to implement automatic POS tagging, and the experiment results are favorable, with  the accuracies higher than 94%. For more details of our dataset, please see our paper “Towards Indonesian Part-of-Speech Tagging: Corpus and Models”.


## Citation

If you use our corpus, please consider citing our paper:
```
@inproceedings{fu2018towards,
  title={Towards indonesian part-of-speech tagging: Corpus and models},
  author={Fu, Sihui and Lin, Nankai and Zhu, Gangqin and Jiang, Shengyi},
  booktitle={Proceedings of the Eleventh International Conference on Language Resources and Evaluation (LREC 2018)},
  year={2018},
  organization={Paris, France: European Language Resources Association (ELRA)}
}
```
