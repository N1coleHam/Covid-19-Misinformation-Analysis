# Language Analysis of Misleading COVID-19 Headlines

## Summary
While misinformation is inevitable, the COVID-19 pandemic fueled a surge of misinformation that influenced public perceptions and responses worldwide.

This project analyzes:
- The dominant themes and motives behind the titles of various sources that contain COVID-19 misinformation, to help people better understand their intent and learn to identify and disregard such content.
- Linguistic patterns and rhetorical shifts over time, exploring how misinformation adapts to public concerns.
- The effectiveness of machine learning algorithms in identifying misleading content. By understanding how certain keywords influence model decisions, we gain insight into what makes a title suspicious and how automated systems can be improved.

---

## Key Features
- Exploratory analysis of headline language, themes, and rhetorical devices.
- Natural language preprocessing (cleaning, tokenization, vectorization).
- Machine learning models (Decision Tree, Logistic Regression, Random Forest) to classify misleading vs. non-misleading headlines.
- Examination of feature importance to uncover which words and patterns influence detection most.

---

## Tech Stack
- **Python**: primary programming language
- **pandas, numpy**: data handling and cleaning
- **scikit-learn**: machine learning models (Decision Tree, Logistic Regression, Random Forest) and metrics
- **NLTK / regex**: text preprocessing and cleaning
- **matplotlib, seaborn**: data visualization

---

## More Information
- **Data**: Consists of a collection of COVID-19 related headlines labeled for misinformation.
- **Goal**:
  - Uncover common linguistic features of misleading headlines.
  - Evaluate ML models' performance in detecting them.
  - Provide insights into how misinformation evolves and how detection systems might improve.
