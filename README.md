# Regression_Predict__sales

##FlowChart

flowchart TD
    st[Start: Load Datasets]
    op[ETL_predict_future_sales]
    op1[XGBoost+Optuna_predict]
    op2[LazyPredict_EnsembleModels_predict]

    st --> op
    op --> op1
    op --> op2
