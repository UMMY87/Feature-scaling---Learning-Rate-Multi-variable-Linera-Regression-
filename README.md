# Feature-scaling---Learning-Rate-Multi-variable-Linera-Regression-
This code snippet demonstrates several important steps in the process of linear regression modeling, including data loading, gradient descent optimization, feature normalization, and prediction. 

First, it imports necessary libraries such as NumPy and Matplotlib for numerical computation and visualization. It also imports custom utility functions from 'lab_utils_multi' and 'lab_utils_common' modules to facilitate various tasks.

The dataset is loaded using the `load_house_data()` function, and the features are visualized with a scatter plot to understand their relationships with the target variable (house prices).

Next, gradient descent optimization is performed with different learning rates (alpha values). The cost function versus the number of iterations and the evolution of model parameters (weights) are plotted for each optimization run to evaluate the convergence behavior.

Feature normalization is then applied using z-score normalization, and the distribution of features before and after normalization is visualized to ensure proper scaling.

After normalization, gradient descent optimization is performed again, and the model parameters are used to make predictions on the training data. The predictions are plotted against the actual target values to visualize the performance of the model.

Finally, a sample house with specific features is normalized and used to predict its price using the trained model. The results are displayed along with the visualization of the feature space, ensuring equal scales for consistent interpretation.
## Plot each feature vs price
![Plot-each-feature-vs-price](https://github.com/UMMY87/Multiple-Variables-in-Linear-Regression/assets/117314436/acbaeb9a-ed4a-41ee-aea8-a9bfecee6b78)
## Plot cost vs iteration w[0] alpha 9.9e7
![plot-cost-vs-iteration- -w 0 -alpha-9 9e-7](https://github.com/UMMY87/Multiple-Variables-in-Linear-Regression/assets/117314436/2d0cdc11-d598-4b16-8cea-d9f4e4ed34f2)
## Plot cost vs iteration w[0] alpha 9e7
![plot-cost-vs-iteration- -w 0 -alpha-9e-7](https://github.com/UMMY87/Multiple-Variables-in-Linear-Regression/assets/117314436/713a413e-0244-4e46-8298-958b06c7be5c)
## Plot cost vs iteration w[0] alpha 1e7
![plot-cost-vs-iteration- -w 0 -alpha-1e-7](https://github.com/UMMY87/Multiple-Variables-in-Linear-Regression/assets/117314436/5b2bbb9e-7eff-45bf-a375-cc920332f940)
## Plot distribution of features before during after normalization
![plot-distribution-of-features-before-during-after-normalization](https://github.com/UMMY87/Multiple-Variables-in-Linear-Regression/assets/117314436/5322c157-ed5c-4046-b855-11bba966e23b)
## Distribution of features before normalization 
![distribution of features before normalization](https://github.com/UMMY87/Multiple-Variables-in-Linear-Regression/assets/117314436/b1cf7dff-ea53-47fa-8287-e1c3c89a0f59)
## Distribution of features after normalization
![distribution of features after normalization](https://github.com/UMMY87/Multiple-Variables-in-Linear-Regression/assets/117314436/7cb33cff-d73f-4df8-91f2-a8b9f4f77caa)
## Target versus prediction using z-score normalized model
![target versus prediction using z-score normalized model](https://github.com/UMMY87/Multiple-Variables-in-Linear-Regression/assets/117314436/4315881b-6934-497c-ae09-9a26d17d58d7)
## Cost contour with equal scale
![cost-contour-with-equal-scale](https://github.com/UMMY87/Multiple-Variables-in-Linear-Regression/assets/117314436/120cdb28-da45-4e93-a6d0-9f00c9d2284b)
