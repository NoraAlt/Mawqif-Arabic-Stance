# Mawqif: A Multi-label Arabic Dataset for Target-specific Stance Detection

- This repository contains the data and classifier used in the paper titled "Mawqif: A Multi-label Arabic Dataset for Target-specific Stance Detection" accepted to appear at [WANLP](https://sites.google.com/view/wanlp2022/home?authuser=0), [EMNLP 2022](https://2022.emnlp.org) . **Link to the paper:** [here](https://preview.aclanthology.org/emnlp-22-ingestion/2022.wanlp-1.16/)

- *Mawqif* is the first Arabic dataset that can be used for target-specific stance detection. 

- This is a multi-label dataset where each data point is annotated for stance, sentiment, and sarcasm, which will provide a benchmark for the three tasks.

- We benchmark *Mawqif* dataset on the stance detection task and evaluate the performance of four BERT-based models. Our best model achieves a macro-F1 of 78.89\%, which shows that there is ample room for improvement on this challenging task.

- In addition to the annotated tweets, we also release the **annotation guidelines**, and the **code** used to build a standard pipeline under the [PyTorch Lightning](https://www.pytorchlightning.ai) framework to fine-tune BERT-based models for stance detection.

- Dataset on HuggingFace 🤗: https://huggingface.co/datasets/NoraAlt/Mawqif_Stance-Detection




# Mawqif Statistics

- This dataset consists of 4,121 tweets in multi-dialectal Arabic. Each tweet is annotated with a stance toward one of three targets: “COVID-19 vaccine,” “digital transformation,” and “women empowerment.” In addition, it is annotated with sentiment and sarcasm polarities.

- The following figure illustrates the labels’ distribution across all targets, and the distribution per target.

<img width="738" alt="dataStat-2" src="https://user-images.githubusercontent.com/31368075/188299057-54d04e87-802d-4b0e-b7c6-56bdc1078284.png">



# Interactive Visualization

To browse an interactive visualization of the *Mawqif* dataset, please click [here](https://public.tableau.com/views/MawqifDatasetDashboard/Dashboard1?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)
- *You can click on visualization components to filter the data by target and by class. **For example,** you can click on “women empowerment" and "against" to get the information of tweets that express against women empowerment.* 


# Citation
If you feel our paper and resources are useful, please consider citing our work!
```
@inproceedings{alturayeif-etal-2022-mawqif,
    title = "Mawqif: A Multi-label {A}rabic Dataset for Target-specific Stance Detection",
    author = "Alturayeif, Nora Saleh  and
      Luqman, Hamzah Abdullah  and
      Ahmed, Moataz Aly Kamaleldin",
    booktitle = "Proceedings of the The Seventh Arabic Natural Language Processing Workshop (WANLP)",
    month = dec,
    year = "2022",
    address = "Abu Dhabi, United Arab Emirates (Hybrid)",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2022.wanlp-1.16",
    pages = "174--184",
}

```
