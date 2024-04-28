# Lipophilicity_Prediction

## Description
This model is a Random Forest regression model trained to predict the lipophilicity of molecules based on molecular descriptors. Lipophilicity is a chemical property that describes the ability of a molecule to dissolve in non-polar solvents.

## Using the Model
To use this model to make predictions on new molecules, follow the steps below:

1. **Prepare Data**: Prepare molecular descriptors for the molecules you want to predict the lipophilicity of. The descriptors are formatted correctly as used during the model training such as log P, Heavy Atom Count, Mol Wt, and TPSA.

2. **Load the Model**: Load the trained model that you have previously saved. You can use Python libraries like joblib to reload the model.

3. **Make Predictions**: Use the model to make predictions on new molecular data by calling the `predict` method. Input the molecular descriptors as the argument of the `predict` method.
    Example:
    predicted_lipophilicity = model.predict(new_molecule_descriptor)
   
5. **Prediction Results**: The predicted lipophilicity will be a numerical value indicating the estimated lipophilicity of the molecule. A higher prediction value indicates a more lipophilic molecule.

## Additional Information
For further information about this model or if you have any questions, feel free to contact [Karlina].
