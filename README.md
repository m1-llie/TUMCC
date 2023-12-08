# TUMCC (Telegram Underground Market Chinese Corpus)

TUMCC is the first Chinese corpus in the jargon identification field. 

**28,749** sentences, including **804,971** characters, from **19,821** Telegram users of **12** Telegram groups were collected when we built TUMCC.

We had finished data screening and word segmentation before we released this corpus. So it might be easier for you to use.

After cleaning, TUMCC contains 3,863 sentences (100,000 characters) from 3,139 Telegram users.

# Files

``TUMCC-clean.txt`` contains the corpus after our cleaning. You can use it directly in your research.

``TUMCC-raw.7z`` contains raw information we collected from Telegram. You can do text cleaning to get more valid data and valuable information.

For more details about the target Telegram group sources for data extraction, please refer to the paper [`Identification of Chinese Dark Jargons in Telegram Underground Markets Using Context-Oriented and Linguistic Features`](https://doi.org/10.1016/j.ipm.2022.103033) ([Information Processing and Management](https://www.sciencedirect.com/journal/information-processing-and-management), 2022).

Please cite us if you use the dataset for research purposes.

```
@article{hou2022identification,
  title={Identification of Chinese dark jargons in Telegram underground markets using context-oriented and linguistic features},
  author={Hou, Yiwei and Wang, Hailin and Wang, Haizhou},
  journal={Information Processing \& Management},
  volume={59},
  number={5},
  pages={103033,1--20},
  year={2022},
  publisher={Elsevier}
}
```
