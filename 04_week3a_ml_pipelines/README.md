### ✅ Why Use `Pipeline`?

1. **Cleaner code**: Combines preprocessing and modeling into one object.
2. **Avoids data leakage**: Ensures that preprocessing like scaling or imputation is *only* fit on training data.
3. **Easier model deployment**: The pipeline becomes a single object you can serialize (with `joblib` or `pickle`).
4. **Hyperparameter tuning**: Use `GridSearchCV` or `RandomizedSearchCV` over the entire pipeline.
5. **Reproducibility**: Makes your workflow standardized and easy to debug or repeat.

---

### 💡 Summary

Yes, writing code separately works — but as your pipeline grows (e.g., multiple preprocessing steps, transformers, feature selectors), manual code becomes messy and error-prone. Pipelines enforce structure, reproducibility, and are essential for production-grade ML.

