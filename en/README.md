# Sub Directory for English Models

## Data

- `en_given` has only data from the current competition
- `ext_data` has extended training data from various sources
- `lexicon.json` has a list of Profane words in English

Under the corresponding directory

- `val.csv` is the validation set
- `train.csv` is train set
- `train_full.csv` is train set + val sets
- `test.csv` is for testing and comparing models
- `submission` folder contains submission pipeline

[Drive Folder related to Data Creation](https://drive.google.com/drive/folders/1FbP7b14esyN1e5OKE0MfFh_MoOIlovN6?usp=sharing)

## Models

- [English Models Notebook](https://colab.research.google.com/drive/1fC0oLVLUvrB4y0vJGRr1TbFtHuN4Vnv7?usp=sharing)

## Tasks

- [x] Data Collection from Various Sources
- [x] Data Cleaning Pipeline
- [x] Add Balanced Dataset
- [x] Add Features to Dataset CSV
- [x] Data Analysis
- [x] Add Citations to Sources/Datasets used
- [x] Baseline Models on Various Baseline Models with Given Data
- [x] Baseline Models on Various Baseline Models with Extended Data
- [x] Models with Profane word list as a feature
- [ ] Models with Sentiment Score as a feature
- [x] Submission Training Pipeline
- [ ] Submission Testing Pipeline
