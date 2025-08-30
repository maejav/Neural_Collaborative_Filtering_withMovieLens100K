This project implements a Neural Collaborative Filtering (NCF) model using PyTorch to predict user ratings for movies. It uses the MovieLens 100K dataset and demonstrates how deep learning can be applied to recommendation systems.

## 📁 Dataset

- **Source**: [MovieLens 100K](http://files.grouplens.org/datasets/movielens/ml-100k.zip)
- **Contents**: 100,000 ratings from 943 users on 1,682 movies
- **Format**: Tab-separated values with columns: `user_id`, `item_id`, `rating`, `timestamp`

## ⚙️ Setup

```bash
wget http://files.grouplens.org/datasets/movielens/ml-100k.zip
unzip ml-100k.zip
pip install pandas scikit-learn torch tqdm
