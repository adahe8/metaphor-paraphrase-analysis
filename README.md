# metaphor-paraphrase-analysis
Comparing the metaphor generation capabilities of modern transformer architecture LLMs.

Data from training pairs data compiled in
@inproceedings{stowe-etal-2021-exploring,
    title = "Exploring Metaphoric Paraphrase Generation",
    author = "Stowe, Kevin  and
      Beck, Nils  and
      Gurevych, Iryna",
    booktitle = "Proceedings of the 25th Conference on Computational Natural Language Learning",
    month = nov,
    year = "2021",
    address = "Online",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2021.conll-1.26",
    pages = "323--336",
    abstract = "Metaphor generation is a difficult task, and has seen tremendous improvement with the advent of deep pretrained models. We focus here on the specific task of metaphoric paraphrase generation, in which we provide a literal sentence and generate a metaphoric sentence which paraphrases that input. We compare naive, {``}free{''} generation models with those that exploit forms of control over the generation process, adding additional information based on conceptual metaphor theory. We evaluate two methods for generating paired training data, which is then used to train T5 models for free and controlled generation. We use crowdsourcing to evaluate the results, showing that free models tend to generate more fluent paraphrases, while controlled models are better at generating novel metaphors. We then analyze evaluation metrics, showing that different metrics are necessary to capture different aspects of metaphoric paraphrasing. We release our data and models, as well as our annotated results in order to facilitate development of better evaluation metrics.",
}

@thesis{Beck2021,
    author = "Nils Beck", 
    title = "Transfer Learning for Conceptual Metaphor Generation",
    school = "Technische Universität Darmstadt",
    address = "Darmstadt, Germany",
    year = 2021,
    month = jun,
    type = "Bachelor's thesis"}