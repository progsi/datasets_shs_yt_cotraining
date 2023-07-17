# datasets_shs_yt_cotraining
Datasets used for cotraining for multimodal cover song identification. Based on SHS100K and an own YouTube-crawl of potential covers.

# Datasets
- `crawl.csv` unlabeled part of training dataset
- `train_labeled.csv` labeled part of training dataset
- `val_shs.csv` validation set (all available covers in SHS100K-val)
- `test_shs.csv` test set 1 (all covers available in SHS100K-test of which the cliques are *not* in the training set)
- `test_yt.csv` a YouTube crawl that we annotated ourselves for cliques in `test_shs.csv`
- `da-tacos.csv` all available Da-Tacos covers (~91%)
