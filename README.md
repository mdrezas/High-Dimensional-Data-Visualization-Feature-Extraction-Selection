# High-Dimensional-Data-Visualization-Feature-Extraction-Selection

Background and Methods:
Diabetes Dataset Visualization & Feature Selection: This study proposes a machine learning modelbased
approach for data visualization and features selection in a higher dimensional space using PCA, t-
SNE, UMAP, and Recursive Feature Elimination with Cross-Validation (RFECV) to identify best features to
improve model performance and accuracy.

Pre-processing:

Hyper-Parameter Tuning:

Exploratory Data Analysis & Visualization: Univariate Pair-Wise Plots & Correlation Maps are leveraged
to examine the data to determine if normalization is required.

Finally, Recursive Feature Elimination in a Cross-Validation (RFECV) loop was leveraged to find &
extract the best features. With REFCV, we find the best features and discover how many features we
need to build the best model. Given that MLP does not have a provision to expose "coefficient" or
"feature importance" attributes, we must use an alternate classifier. I have used SVC with a linear kernel
to find the best optimal parameters here. With RFECV, it turns out that the F1-Score increased and has a
positive impact on the extracted optimal features. Refer to the Model Summary in the Appendix section
below for details on models' performance.
