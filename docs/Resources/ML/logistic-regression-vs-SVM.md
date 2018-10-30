# Pros & Cons

## Logistic regression
- Is a linear classifier
- Can use with kernels, but slow
- Outputs meaningful probabilities
- Can be extended to multi-class
- All data points affect fit
- L2 or L1 regularization

## Support vector machine (SVM)
- Is a linear classifier
- Can use with kernels, and fast
- Does not naturally output probabilities
- Can be extended to multi-class
- Only "support vectors" affect fit
- Conventionally just L2 regularization

# Use in scikit-learn

## Logistic regression
```python
from sklearn.linear_model import LogisticRegression
```
### hyperparameters
- C (inverse regularization
strength)
- penalty (type of regularization)
- multi_class (type of multi-class)

## Support vector machine (SVM)
```python
from svm.LinearSVC import LinearSVC

# OR

from svm.SVC import SVC
```

### hyperparameters
- C (inverse regularization
strength)
- kernel (type of kernel)
- gamma (inverse RBF smoothness)