
# 📰 Fake News Detection using NLP

This project aims to classify news articles as **real** or **fake** using Natural Language Processing (NLP) techniques and a machine learning model. It's built using Python, Jupyter Notebook, and common NLP libraries.

---

## 📂 Dataset

The dataset consists of two CSV files:
- `True.csv`: Contains real news articles.
- `Fake.csv`: Contains fake news articles.

Each file has the following columns: `title`, `text`, `subject`, and `date`.

---

## 🧠 Model Overview

We use:
- **Text preprocessing** (cleaning, removing stopwords, etc.)
- **TF-IDF Vectorization** to convert text into numerical features
- **PassiveAggressiveClassifier** for binary classification

---

## 🚀 How to Use

1. Clone this repository:
   bash
   git clone https://github.com/yourusername/fake-news-detection.git


2. Navigate to the project folder:

   ```bash
   cd fake-news-detection
   ```

3. Open the Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Run the notebook step-by-step to see:

   * Data preprocessing
   * Model training
   * Accuracy evaluation
   * Custom user input prediction

---

## 🧪 Example

You can input your own news sentence at the end of the notebook:

```python
input_text = input("Enter a news article to check if it's Fake or Real:\n")
```

---

## 🛠️ Requirements

Install all dependencies using:

```bash
pip install -r requirements.txt
```

Or install individually:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

---

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙌 Acknowledgements

* Dataset Source: [Kaggle Fake and Real News Dataset](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset)
* NLP techniques based on Scikit-learn
