# 🏀 NBA All-Star Predictor

ML classification model predicting NBA All-Star selections from 30 seasons of data (1996–2026).

## 🔗 Links
- 📊 [Interactive Dashboard](https://pilee11.github.io/nba-allstar-predictor/NBA%20Dashboard.html)
- 📓 [Full Notebook](https://github.com/pilee11/nba-allstar-predictor/blob/main/notebook.ipynb)

## 📈 Results
| Set | F1 | Recall | Accuracy | AUC |
|---|---|---|---|---|
| Test Set (1995–2024) | 0.707 | 0.865 | 0.964 | 0.983 |
| Blind Set (2025–26) | 0.746 | 0.846 | 0.972 | 0.987 |

## 🔧 Methods
- **Model:** HistGradient Boosting (best among 5 tested)
- **Data:** NBA API + Basketball-Reference
- **Challenge:** 5% class imbalance, subjective selection process
- **Key features:** PTS_RANK, WINNING_IMPACT, ALL_STAR_MOMENTUM, DD2

