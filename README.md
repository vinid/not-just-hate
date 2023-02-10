# "It's Not Just Hate": A Multi-Dimensional Perspective on Detecting Harmful Speech Online 

You can find the paper [here](https://aclanthology.org/2022.emnlp-main.553/)

## Abstract

Well-annotated data is a prerequisite for good Natural Language Processing models. Too often, though, annotation decisions are governed by optimizing time or annotator agreement. We make a case for nuanced efforts in an interdisciplinary setting for annotating offensive online speech. Detecting offensive content is rapidly becoming one of the most important real-world NLP tasks. However, most datasets use a single binary label, e.g., for hate
or incivility, even though each concept is multifaceted. This modeling choice severely limits nuanced insights, but also performance. We show that a more fine-grained multi-label approach to predicting incivility and hateful or intolerant content addresses both conceptual and performance issues. We release a novel dataset of over 40,000 tweets about immigration from the US and UK, annotated with six labels for different aspects of incivility and intolerance. Our dataset not only allows for a more nuanced understanding of harmful speech online, models trained on it also outperform or match performance on benchmark datasets.

## Resources

The new dataset introduced can be found [here](https://osf.io/gxvsj/?view_only=12197981e47a47239a6f80c62db84b14)

For a tiny bit more details on label mapping, see [this issue](https://github.com/vinid/not-just-hate/issues/1)


## Cite

    @inproceedings{bianchi-etal-2022-just,
      title = "{``}It{'}s Not Just Hate{''}: A Multi-Dimensional Perspective on Detecting Harmful Speech Online",
      author = "Bianchi, Federico  and
        HIlls, Stefanie  and
        Rossini, Patricia  and
        Hovy, Dirk  and
        Tromble, Rebekah  and
        Tintarev, Nava",
      booktitle = "Proceedings of the 2022 Conference on Empirical Methods in Natural Language Processing",
      month = dec,
      year = "2022",
      address = "Abu Dhabi, United Arab Emirates",
      publisher = "Association for Computational Linguistics",
      url = "https://aclanthology.org/2022.emnlp-main.553",
      pages = "8093--8099"}
