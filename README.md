# In_Formal Sentences

This repository contains a dataset with sentences from a wide range of genres with human formality assessments on a *continuous* formal-informal scale. Each sentence has a score between +1 (most formal) and -1 (most informal).

We provide the following files:

+ *in_formal_sentences.tsv*: the dataset
+ *in_formal_sentences.json*: the dataset with further information (e.g., reference, twitter id, or url)
+ *annotator_instructions.md*: the annotation guidelines in German

Altogether, the dataset includes 3,000 German sentences from 12 domains (tweets, Reddit posts, subtitles, comments, emails, blogs, fiction, news, Wikipedia, political speeches, legal documents, and scientific texts) to cover the broad spectrum of formality. Formality annotations were obtained using crowdsourcing (data workers were German native speakers) and Best-worst scaling.

## Citation

When using the data, please cite:

```
@inproceedings{eder-etal-2023,
    title = "A Question of Style: A Dataset for Analyzing Formality on Different Levels",
    author = "Eder, Elisabeth  and
      	      Krieg-Holz, Ulrike  and
      	      Wiegand, Michael",
    booktitle = "Findings of the Association for Computational Linguistics: EACL 2023",
    month = may,
    year = "2023",
    address = "Dubrovnik, Croatia",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2023.findings-eacl.42",
    pages = "580--593"
}
```

## License

Sentences with an id containing *comments* are licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/) since they originate from a corpus restricted to non-commercial use only.
For the other sentences a [Creative Commons Attribution-ShareAlike 4.0 International License (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/) applies.
