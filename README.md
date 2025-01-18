# Machine Learning - Affinity Propagation Algorithm
------------------------  

## What is this project?  
This is a final project for the Data Visualization course, focusing on analyze and visualize Europe hotel reviews dataset from Kaggle. Our project focuses on using visual charts to provide hotel recommendations for Asian visitors traveling to Europe.  
------------------------  

## Data Source  
- **Data Origin**: The dataset was sourced from Kaggle - [515K Hotel Reviews Data in Europe](https://www.kaggle.com/datasets/jiashenliu/515k-hotel-reviews-data-in-europe/data)
- **Files**:  
   - `Hotel_Reviews.csv`: Raw hotel reviews data. (You can download in the hyperlink) 
   - `DV_GROUP10_FINALCODE.ipynb`: Source code.
  
---

## Dependencies

Ensure the following libraries are installed before running the program:

### Data Processing Libraries:
```bash
pip install pandas numpy
```

### Text Processing Libraries:
```bash
pip install nltk pyvi scikit-learn
```
- **NLTK**: Make sure to download required NLTK data with the following:
  ```python
  import nltk
  nltk.download('punkt')
  nltk.download('punkt_tab')
  nltk.download('stopwords')
  nltk.download('averaged_perceptron_tagger')
  nltk.download('wordnet')
  nltk.download('averaged_perceptron_tagger_eng')
  ```

### Visualization Libraries:
```bash
pip install matplotlib seaborn wordcloud
import matplotlib.pyplot as plt
```

------------------------  

### Our Contributors:    
- Nguyễn Vân Phi Yến
- Trần Vọng Triển
- Nguyễn Thành Vinh
- Trầm Thái Tú
- Nguyễn Phúc Minh Trâm

### Course Information:
- Course: Data Visualization
- Professor: PhD. Nguyễn An Tế
