# Coder

## GitHub Profesor
https://github.com/Luis-ramirez-r/CH-32845

## GitHub Coder
https://github.com/dfbustosus/Proyectos_DS

# estimate bias and variance
mse_Tree_Completo, bias_Tree_Completo, var_Tree_Completo = bias_variance_decomp(tree_Completo_power_gen, X_train.values, y_train.values, X_test.values, y_test.values, loss='mse', num_rounds=200, random_seed=1)
mse_Tree_LR, bias_Tree_LR, var_Tree_LR = bias_variance_decomp(tree_LR_power_gen, X_train_LR.values, y_train.values, X_test_LR.values, y_test.values, loss='mse', num_rounds=200, random_seed=1)
mse_Tree_feature, bias_Tree_feature, var_Tree_feature = bias_variance_decomp(tree_features_power_gen, X_train_features.values, y_train.values, X_test_features.values, y_test.values, loss='mse', num_rounds=200, random_seed=1)

# summarize results
print('MSE Tree Completo: %.3f' % mse_Tree_Completo)
print('Bias Tree Completo: %.3f' % bias_Tree_Completo)
print('Variance Tree Completo: %.3f' % var_Tree_Completo)
print('MSE Tree LR: %.3f' % mse_Tree_LR)
print('Bias Tree LR: %.3f' % bias_Tree_LR)
print('Variance Tree LR: %.3f' % var_Tree_LR)
print('MSE Tree feature: %.3f' % mse_Tree_feature)
print('Bias Tree feature: %.3f' % bias_Tree_feature)
print('Variance Tree feature: %.3f' % var_Tree_feature)
