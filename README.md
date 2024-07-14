# Cultural Bias in Hate Speech Datasets

Preprocessed corpora and code for paper: ["From Languages to Geographies: Towards Evaluating Cultural Bias in Hate Speech Datasets"](https://aclanthology.org/2024.woah-1.23/)

## Preprocessed Corpora

The preprocessed corpora for the eight languages we focus on in the paper can be found on :hugs::
- [Arabic](https://huggingface.co/datasets/manueltonneau/arabic-hate-speech-superset)
- [English](https://huggingface.co/datasets/manueltonneau/english-hate-speech-superset)
- [French](https://huggingface.co/datasets/manueltonneau/french-hate-speech-superset)
- [German](https://huggingface.co/datasets/manueltonneau/german-hate-speech-superset)
- [Indonesian](https://huggingface.co/datasets/manueltonneau/indonesian-hate-speech-superset)
- [Portuguese](https://huggingface.co/datasets/manueltonneau/portuguese-hate-speech-superset)
- [Spanish](https://huggingface.co/datasets/manueltonneau/spanish-hate-speech-superset)
- [Turkish](https://huggingface.co/datasets/manueltonneau/turkish-hate-speech-superset)

## Geocoding Code

The Python code to interact with the Google Geocoding API is in `google_geocoding_api.ipynb`. 


## Citation

If you find our work useful, please cite:

```
@inproceedings{tonneau-etal-2024-languages,
    title = "From Languages to Geographies: Towards Evaluating Cultural Bias in Hate Speech Datasets",
    author = {Tonneau, Manuel  and
      Liu, Diyi  and
      Fraiberger, Samuel  and
      Schroeder, Ralph  and
      Hale, Scott  and
      R{\"o}ttger, Paul},
    editor = {Chung, Yi-Ling  and
      Talat, Zeerak  and
      Nozza, Debora  and
      Plaza-del-Arco, Flor Miriam  and
      R{\"o}ttger, Paul  and
      Mostafazadeh Davani, Aida  and
      Calabrese, Agostina},
    booktitle = "Proceedings of the 8th Workshop on Online Abuse and Harms (WOAH 2024)",
    month = jun,
    year = "2024",
    address = "Mexico City, Mexico",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2024.woah-1.23",
    pages = "283--311",
    abstract = "Perceptions of hate can vary greatly across cultural contexts. Hate speech (HS) datasets, however, have traditionally been developed by language. This hides potential cultural biases, as one language may be spoken in different countries home to different cultures. In this work, we evaluate cultural bias in HS datasets by leveraging two interrelated cultural proxies: language and geography. We conduct a systematic survey of HS datasets in eight languages and confirm past findings on their English-language bias, but also show that this bias has been steadily decreasing in the past few years. For three geographically-widespread languages{---}English, Arabic and Spanish{---}we then leverage geographical metadata from tweets to approximate geo-cultural contexts by pairing language and country information. We find that HS datasets for these languages exhibit a strong geo-cultural bias, largely overrepresenting a handful of countries (e.g., US and UK for English) relative to their prominence in both the broader social media population and the general population speaking these languages. Based on these findings, we formulate recommendations for the creation of future HS datasets.",
}

```
