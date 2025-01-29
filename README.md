Model Performance and Results

✓ Data: The AAPL stock price data was loaded and pre-processed using 
MinMaxScaler for normalization. 
✓ Model Architecture:  
o A stacked LSTM model with three LSTM layers was implemented. 
o Additionally, for comparison purposes, the code includes the creation and 
training of Dilated CNN and CNN-LSTM models (commented out). 
✓ Training:  
o The data was split into training and testing sets (65% training, 35% testing). 
o The LSTM model was trained for 100 epochs with a batch size of 64 using 
the Adam optimizer and mean absolute error (MAE) loss function. 
o Early stopping was used to prevent overfitting. 
✓ Evaluation:  
o The model's performance was evaluated on the test set using MAE. 
o The code includes plotting the actual vs. predicted values for visual 
comparison. 
o (For the commented-out Dilated CNN and CNN-LSTM models, their 
evaluation metrics would be included here after training them). 
✓ Prediction:  
o The code demonstrates how to use the trained model to predict the next 
10 days' closing prices based on the last 100 days' data. 
Key Observations: 
• The provided code effectively implements an LSTM model for stock price 
prediction. 
• Visualizing the actual vs. predicted values can help assess the model's ability 
to capture trends and patterns. 
• The MAE metric provides a quantitative measure of the prediction error. 
Challenges Faced: 
• Stock price prediction is a complex task due to various factors influencing 
market movements. 
• LSTM models are sensitive to hyperparameter tuning (e.g., number of layers, 
units, epochs) which can significantly impact performance. 
• Data quality and quantity can also affect the model's accuracy. 
Recommendations for Improvement: 
• Experiment with different hyperparameter configurations to potentially 
improve model performance. 
• Explore more advanced architectures like LSTMs with attention mechanisms or 
recurrent neural networks (RNNs) like GRUs. 
• Consider incorporating additional features (e.g., trading volume, market 
sentiment) that might influence stock prices. 
• Utilize a larger dataset for training to potentially improve model 
generalizability. 
• Back-testing predictions against real market data to assess the model's 
effectiveness in real-world scenarios. 
Overall, the provided code demonstrates a good starting point for LSTM-based 
stock price prediction. By addressing the challenges and incorporating the 
recommendations, you can potentially enhance the model's performance and 
accuracy. 
