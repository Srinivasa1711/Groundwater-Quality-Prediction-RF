# Groundwater Quality Prediction Using Random Forest

A machine learning project that predicts whether groundwater is safe or contaminated using the Random Forest algorithm.

Built as part of **CS 667: Machine Learning** at the **University of Alabama at Birmingham (UAB)**.

---

## What This Project Is About

Clean groundwater is something millions of people depend on every day. But with pollution from farming, factories, and waste, it's getting harder to know if water is safe without proper testing.

In this project, we used a machine learning algorithm called **Random Forest** to predict groundwater quality based on factors like pH, nitrate levels, dissolved oxygen, and other water indicators. The goal was to build a model that can classify water as safe or contaminated — quickly and accurately.

---

## Team — Group 17

| Name | Contribution |
|------|-------------|
| Srinivasa Chowdary Eluri | Literature search and research compilation |
| Divya Tanniru | Introduction and core concept writing |
| Naralasetti Shanmukheswari Prasannasai | RF applications, comparisons, pros & cons |
| Christopher Kirkman | Conclusion, future directions, challenges |

---

## What's Inside This Repo

```
Groundwater-Quality-Prediction-RF/
│
├── README.md
│
├── docs/
│   ├── Literature_Review.pdf       # Full literature review paper
│   └── Project_Report.docx         # Final project report
│
├── presentation/
│   └── Water_Quality_Presentation.pptx  # Project slides
│
└── app/
    ├── WaterQualityClassifier.html  # Interactive web app
    └── WaterQualityClassifier       # Classifier model/script
```

---

## How to Run the App

1. Download or clone this repository
2. Open the `app/` folder
3. Double-click `WaterQualityClassifier.html` to open it in your browser
4. Enter the water quality values and the model will predict if the water is safe or not

No installation needed — it runs directly in the browser.

---

## Why Random Forest?

We picked Random Forest because it:

- Works well even with messy or incomplete data
- Handles complex relationships between water quality factors
- Tells you which factors matter most (like pH or nitrate levels)
- Gives high accuracy without overfitting

---

## Key Findings

- Random Forest outperformed other algorithms like SVM and k-Nearest Neighbors
- The most important water quality factors were pH, turbidity, and nitrate levels
- Combining RF with GIS tools helped identify contamination hotspots on a map
- The model works great for batch predictions but needs optimization for real-time use

---

## Tech Used

- Machine Learning: Random Forest (ensemble learning)
- Frontend: HTML, CSS, JavaScript
- Tools: Python, scikit-learn

---

## References

1. Breiman, L. (2001). Random forests. *Machine Learning, 45*(1), 5–32.
2. Gholami, Z., et al. (2020). Comparing machine learning algorithms for groundwater quality prediction. *Environmental Science and Pollution Research, 27*, 12445–12456.
3. Giri, S., & Qiu, H. (2016). Feature importance analysis using Random Forest for groundwater quality prediction. *Water, 8*(5), 192.
4. Ghosh, S., & Shit, P. K. (2022). Application of Random Forest in groundwater quality assessment. *Journal of Environmental Management, 301*, 113870.
5. Jha, M. K., et al. (2021). Groundwater quality assessment and modeling: A review. *Water Quality Research Journal, 56*(3), 115–126.
6. Liaw, A., & Wiener, M. (2002). Classification and regression by randomForest. *R News, 2*(3), 18–22.
7. Liang, H., et al. (2017). Integrating Random Forest and GIS for groundwater quality assessment. *Environmental Monitoring and Assessment, 189*, 43.
8. Sahoo, P. K., et al. (2019). Application of Random Forest for the prediction of water quality index. *Journal of Water and Climate Change, 10*(3), 675–687.

---

*CS 667: Machine Learning — Group 17 — University of Alabama at Birmingham*
