# Awajun-OP
We introduce a Spanish-Awajun parallel dataset of 22k high-quality sentence pairs with the help of the journalistic organization Ojo Público. This dataset consists of parallel data obtained from various web sources such as poems, stories, laws, protocols, guidelines, handbooks, the Bible, and news published by Ojo Público. The study also includes an analysis of the dataset's performance for Spanish-Awajun translation using a Transformer architecture with transfer learning from a parent model, utilizing Spanish-English and Spanish-Finnish as high-resource language pairs. As far as we know, this is the first Spanish-Awajun machine translation study, and we hope that this work will serve as a starting point for future research on this neglected Peruvian language. This repo is related to the paper: "Awajun-OP: Multi-domain dataset for Spanish–Awajun Machine Translation".

The original parallel corpus extracted during this research is located within the `data` directory. The finalized training, validation, and testing files are available within the `experiment_data` directory. Evaluation has been conducted utilizing the `evaluate.py` script.



## Results

| Parent|  Model|ISO| Language | ChrF |
---|---|---|---|----
es-en |Transformer |agr | Awajun | 0.378
es-fi |Transformer |agr | Awajun | 0.387
