# blockchain-transaction-analysis
Identify Block of Pending Transactions

## Summary
The process outlined ensures robust data preprocessing, feature engineering, and model selection, leading to a reliable prediction model for blockchain transaction analysis. The GCN model provides superior performance, demonstrating its ability to capture complex relationships within the transaction data.

## Steps to Run the Process
1.	Execute "blockchain_transactions_data_analysis.ipynb" for data analysis with raw data "TxnPool_Dataset" to produce processed CSV output.
2.	Run "blockchain_transactions_ModelTraining.ipynb" for training models using the processed data.
3.	Use "blockchain_transactions_ModelPrediction.ipynb" to predict blockNumber for pending transactions using 'final_gcn_model.pth' and 'label_encoder.pkl'.
