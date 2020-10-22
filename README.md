# catboost model deployment sample repo

This repo showcases leveraging the catboost library with Azure ML Python SDK to:

1. Load & Cleanse a Dataset
2. Register the dataset for usage by the training script (this could be done with a local file copy instead of registering)
2. Create a model leveraging the CatBoost python library and saving it
3. Registering the model for deployment
4. Generating the scoring script required for model deployment
5. Deploying a model to ACI (without authorization)
6. Deploing a model to AKS (with key-based auth)


- The html shows a run notebook.
- Catboost-Sample.ipynb is a sample notebook that you can run and will deploy a model based on the sample dataset
- catboost-exploration.ipynb is a sample notebook that saves a model that could be deployed with super sample data based on the catboost documentation.
