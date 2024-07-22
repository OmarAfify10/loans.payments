# loans.payments
In this Project we develop a model that can predict whether a new borrower will repay his loan, using historical data on loan spending and information on whether the borrower has repaid the loan. This will allow us to evaluate potential future borrowers and estimate their likelihood of repaying their loan.


# Binder Badge 
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/OmarAfify10/loans.payments/HEAD)

# Execution 
To execute the Project use the binder badge above and follow the instructions in the code to run it .

# Result
 The new customer data will be fed to the model to make the prediction , wether the customer will pay the loan in the future or not .
 
input_data = tf.convert_to_tensor(new_customer.values.reshape(1, 78), dtype=tf.float32)
predictions = model.predict(input_data)
predicted_class = np.argmax(predictions)

print("Predicted class:", predicted_class)
1/1 [==============================] - 0s 33ms/step
Predicted class: 0
