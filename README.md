# Requirements

- Python 3.8+
- Install packages from requirements.txt
- A correctly installed CUDA installation if you're planning to use an Nvidia gpu. If not, remove tensorflow-gpu and use 
  the default tensorflow package instead.
- Download the [Japanese fakenews dataset](https://www.kaggle.com/tanreinama/japanese-fakenews-dataset)
- Download the [latest release of the Japanese word embedding we use](https://github.com/singletongue/WikiEntVec/releases/tag/20190520), 
  **specifically** the jawiki.all_vectors.100d.txt.bz2 file, and unzip to this directory. Preferred would be the 300 
  dimension version, but this one is quite heavy.

# Run training

Execute Jupyter notebook