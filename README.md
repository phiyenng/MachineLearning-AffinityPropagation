# Machine Learning - Affinity Propagation Algorithm
------------------------  

## What is this project?
This is a final project for the Machine Learning course, focusing on customer segmentation using the Affinity Propagation algorithm.  

In a highly competitive market, especially in the food and service industry, understanding and maintaining strong relationships with customers is crucial for business growth. One of the widely used methods for customer segmentation is the RFM (Recency, Frequency, Monetary) model, which analyzes purchasing behavior based on historical transaction data.

This project applies Affinity Propagation to segment customers using data from the RMIT Business Analytics Champion (RBAC) 2023, provided by Pizza Hut Vietnam. The goal is to optimize clustering results, identify key customer groups, and propose data-driven business strategies to enhance customer experience.

------------------------  

## Data Source  
- **Data Origin**: The Pizza Hut's real dataset was sourced from RMIT Business Analytics Champion 2023 Contest
- **Files**:  
   - `Hotel_Reviews.csv`: Raw hotel reviews data. (You can download in the hyperlink) 
   - `ML_GROUP10_FINALCODE.ipynb`: Source code.
  
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
- Course: Machine Learning
- Professor: PhD. Nguyễn An Tế
