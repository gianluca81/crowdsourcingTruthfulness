# Can The Crowd Identify Misinformation Objectively? The Effects of Judgment Scale and Assessor's Background

This repository contains the crowdsourced judgments used in the SIGIR'20 full paper titled "Can The Crowd Identify Misinformation Objectively? The Effects of Judgment Scale and Assessor's Background"

The ABC dataset consists of a total of 60 statements. The [ABC.csv](./SIGIR2020/ABC.csv) file contains the following information:
 - `statement.id`: The ID of the statement.
 - `statement`: The statement.
 - `speaker`: The name and surname of whom said the statement.
 - `year`: The year in which the statement was made.
 - `party`: The party to which the speaker belongs to.
 - `label`: Verdict in a three-level scale {Positive, In-Between, Negative}.
 - `article_url`: URL of the article published by RMIT ABC Fact Check verifying the statement.
 - `verdict`: Verdict displayed in the article. This is the way RMIT ABC Fact Check originally delivered the verdicts.




## Citation

If you use this resource, please cite our paper:

*Kevin Roitero, Michael Soprano, Shaoyang Fan, Damiano Spina, Stefano Mizzaro, and Gianluca Demartini. 2020. Can The Crowd Identify Misinformation Objectively? The Effects of Judgment Scale and Assessor’s Background.In SIGIR ’20: The 43rd International ACM SIGIR Conference on Research and Development in Information Retrieval, July 25–30, 2020, Xi’an, China. ACM.*


### BibTeX

```bibtex
@InProceedings{roitero2020can,
author = {Roitero, Kevin and Soprano, Michael and Fan, Shaoyang and Spina, Damiano
          and Mizzaro, Stefano and Demartini, Gianluca},
title = {Can The Crowd Identify Misinformation Objectively? The Effects of Judgment Scale and Assessor’s Background},
booktitle = {Proceedings of SIGIR'20},
year={2020}
}
```

## Acknowledgements

This work is partially supported by a Facebook Research award
and by an Australian Research Council Discovery Project (DP190102141).
We thank Devi Mallal from RMIT ABC Fact Check for facilitating access to the ABC dataset.


## Disclaimer Notice

The information included in this repository is for research purposes only.
