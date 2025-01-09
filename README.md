# Sampling Techniques in Active Learning

This repository contains the implementation and results of various active learning sampling techniques applied to different datasets. The project explores the effectiveness of active learning in improving model performance while minimizing computational and annotation costs.

## Datasets

The following datasets were used in the experiments:

1. **Digits Dataset**: Contains images of handwritten digits (0-9) used for classification tasks.
2. **Iris Dataset**: Comprises measurements of sepal and petal lengths and widths for three species of iris flowers.
3. **Breast Cancer Wisconsin Dataset**: Provides data on breast cancer tumors, distinguishing between malignant and benign cases.
4. **Stroke Dataset**: Contains medical records to study stroke occurrences, aiding in risk analysis and predictive modeling.

## Sampling Techniques

The following active learning sampling techniques were implemented:

1. **Query By Committee (QBC)**: Seeks opinions from a committee of models to identify informative data points.
2. **Entropy Sampling**: Selects instances where the model is uncertain about their label.
3. **Margin Sampling**: Focuses on data points near the decision boundary of the classification model.

## Results

### Iris Dataset
- **Accuracy without Active Learning**: 0.27
- **Accuracy with Active Learning**:
  - Entropy Sampling: 0.89
  - Margin Sampling: 0.93
  - Query By Committee: 0.90

### Digits Dataset
- **Accuracy without Active Learning**: 0.10
- **Accuracy with Active Learning**:
  - Entropy Sampling: 0.96
  - Margin Sampling: 0.94
  - Query By Committee: 0.92

### Breast Cancer Wisconsin Dataset
- **Accuracy without Active Learning**: 0.54
- **Accuracy with Active Learning**:
  - Entropy Sampling: 0.96
  - Margin Sampling: 0.96
  - Query By Committee: 0.80

### Stroke Dataset (Imbalanced)
- **Techniques Applied**:
  - Entropy Sampling
  - Margin Sampling
  - Query By Committee

## Conclusion

1. Among uncertainty-based strategies, there is no significant discrepancy in performance.
2. Active learning methods generally outperform traditional methods in maintaining high accuracy scores.
3. Active learning excels in minimizing computational expenses, annotation efforts, and budgetary needs.

## References

- [scikit-activeml Documentation](https://scikit-activeml.github.io/scikit-activeml-docs/)
- [Active Learning Sampling Strategies](https://medium.com/@hardik.dave/active-learning-sampling-strategies-f8d8ac7037c8)
- [Active Learning Approaches and Strategies](https://younsess-elbrag.medium.com/active-learning-approaches-strategies-deep-learning-integration-and-essential-tools-6ff2bdfe5cb)

## Questions?

Feel free to reach out with any questions or suggestions!
