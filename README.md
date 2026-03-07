# Psychometric Analysis of Cirrus Exported Data (PACED)

PACED is a Shiny application designed to generate psychometric reports of educational tests based on data exported directly from the Cirrus online assessment platform. It enables educators and assessment designers to explore test data, visualize score distributions, examine item and test statistics, and create professional HTML reports. Built in R using `shiny` and hosted on GitHub Pages via `shinylive`, all computations run locally, ensuring that sensitive data never leaves your computer.

---

## Key Features

- **Descriptive Statistics**: Calculate essential metrics such as participant count, mean, median, standard deviation, and skewness.
- **Histogram Visualization**: Generate histograms to identify trends, ceiling/floor effects, and overall score patterns.
- **Test-Level Statistics**: Assess overall assessment quality, including difficulty, discrimination (RIT/RIR), and reliability (Cronbach’s alpha).
- **Item-Level Statistics**: Examine individual items with P-values, item-total and item-rest correlations, and the effect on reliability if an item is removed.
- **Item Plots**: Visualize item difficulty versus discrimination for quick insights.
- **Item Correlation Matrix**: Detect inter-item relationships and potential redundancies with a visually intuitive matrix.
- **HTML Report Generation**: Generate fully formatted reports with color-coded metrics, interactive plots, and detailed annotations.

---

## Getting Started

Access the live application at https://koenderks.github.io/PACED/.

## Contributing

I welcome contributions! Fork the repository and submit pull requests for bug fixes, enhancements, or new features. Your improvements help make the application more powerful and user-friendly.
