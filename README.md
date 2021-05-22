# CL-TLS

ML-Crisis data collection for the paper **Cross-lingual timeline summarization**. Currently under review.

The source documents and reference timelines for the English language `en/` are the one available on the original [Crisis dataset](http://www.l3s.de/~gtran/timeline/) . If you use English data in your work please cite the original paper:

```
@inproceedings{tran2015timeline,
  title={Timeline summarization from relevant headlines},
  author={Tran, Giang and Alrifai, Mohammad and Herder, Eelco},
  booktitle={European Conference on Information Retrieval},
  pages={245--256},
  year={2015},
  organization={Springer}
}
```

## Data Collection - ML-Crisis

Each language-specific folder contains all the information for each topic in a separate folder (e.g., `it/yemen/` contains the information related to the *yemen* timeline in Italian language)
Each language-specific folder contains the reference timelines in the `XX/reference/YY.txt` folder. `XX` indicate the language code (e.g., fr for French) and `YY` indicate the topic name (e.g., `syria`)
