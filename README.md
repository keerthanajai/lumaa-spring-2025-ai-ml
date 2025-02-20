# **Movie Recommendation System**

## **Dataset**
The dataset is sourced from Kaggle. Use this link to access and download the dataset:  
[Download Dataset](https://drive.google.com/file/d/1VCkEBVGvceuwCzXXpS2Vjui3kFl7x_QY/view?usp=drive_link)

## **Setup**
- **Python Version**: Google Colab provides Python 3 by default, so no need to install Python separately.
- **Install Dependencies**: Run the following imports in the Google Colab notebook to ensure all required libraries are available:

  ```python
  import pandas as pd 
  import numpy as np 
  import nltk
  from nltk.stem.snowball import SnowballStemmer
  from sklearn.feature_extraction.text import TfidfVectorizer
  from sklearn.metrics.pairwise import cosine_similarity
  ```

## **Running**
1. **Open Colab Notebook**: Open the notebook that contains the recommendation system in Google Colab.
2. **Run Code Cells**: Execute each code cell sequentially to load data, preprocess it, and generate recommendations.

## **Results**
**Input:**  
```text
"I want to watch Disney, Pixar movies"
```

**Output:**  
```text
Top Recommended Movies:
1. Summer Magic
2. The Pixar Story
3. Philadelphia
4. The Other Boleyn Girl
5. Chip 'n Dale: Rescue Rangers
```
