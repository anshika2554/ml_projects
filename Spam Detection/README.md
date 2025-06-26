# 📧 SMS Spam Detection using NLP & Multinomial Naive Bayes

This project focuses on building a machine learning model to classify SMS messages as **spam** or **ham** (not spam) using **Natural Language Processing (NLP)** techniques and the **Multinomial Naive Bayes** algorithm.

## 📂 Project Structure

- `SMSSpamCollection` - The dataset containing labeled SMS messages.
- `Spam_Detection.ipynb` - Jupyter Notebook with all code including preprocessing, model training, evaluation, and testing.

---

## 🧠 Features

- 🧹Text preprocessing: removal of stopwords and stemming using **NLTK**.
- ✨Feature extraction using **TF-IDF Vectorization**
- 🔍Spam detection using **Multinomial Naive Bayes**
- ⚖Evaluation using :
   - accuracy 
   - confusion matrix
   - classification report
- 📊Also applied other models:
   - SVM
   - Random Forest
   - Logistic Regression
- 🌟Accuracy of **98%** on test data.
- 🧪Real message testing included to verify performance.

---

## 📅 Dataset

- **Source**: [UCI SMS Spam Collection Dataset](https://archive.ics.uci.edu/ml/datasets/sms+spam+collection)
- **Format**: CSV with two columns:
  - `label`: `spam` or `ham`
  - `message`: the text content of the SMS
  - `also uploaded`

---

## 🔧 Installation & Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/anshika2554/spam-detection.git
   cd spam-detection
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

   _You can manually install if `requirements.txt` is missing:_
   ```bash
   pip install numpy pandas matplotlib nltk scikit-learn
   ```

3. Run the notebook:
   ```bash
   jupyter notebook Spam_Detection.ipynb
   ```

---

## 🚀 How to Use

1. Run all cells in the notebook.
2. Enter your own message at the end to test whether it's spam or not.
3. Analyze accuracy, confusion matrix, and sample outputs.

---

## 🏆 Results

- Achieved **98% accuracy** on validation data.
- Model correctly predicts spam/ham messages with very few false positives.
- Real examples tested and working as expected.

---

## 🌍 Real-World Applications

- **SMS Filtering:** Automatically block spam messages in messaging apps.
- **Email Classification:** Adapt the model to detect spam emails using similar NLP techniques.
- **Customer Support:** Flag irrelevant or fraudulent messages sent to helpdesk systems.
- **Chat Moderation:** Detect spam in online chat rooms or discussion forums.
- **Telecom Operators:** Integrate into their SMS gateways to prevent mass spam campaigns.

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

