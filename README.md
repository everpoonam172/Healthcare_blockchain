# Healthcare_blockchain
Decentralized Healthcare System and Secure Remote Monitoring Platform for Diabetes Patients


The decentralized healthcare system and safe remote monitoring platform for diabetic patients use a Python-based block class with index, previous hash, timestamp, data, hash, and compute hash. Additionally, a user-defined blockchain class with add block method is created. CSV diabetic data is safely kept on the blockchain, and simulations assure transaction success and failure. Comparing the suggested and traditional models shows considerable increases in performance, error rates, sensitivity, and specificity across block indices. This unique solution improves diabetes data management security and reliability and establishes a new benchmark for digital healthcare applications.

Step 1 Dataset_updated.csv is data that has been collected.
Step 2 encryption.ipynb takes Dataset_updated as input and produces 
"encrypted_output.csv" that is AES based encryption. 
Step 3 "encrypted_output.csv" is further processed by MD5 and new file named your_data.csv is generated.
Step 4 "your_data.csv" is further input to blockchain.ipynb where block and block chain class are developed to save health care data in blockchain. 
Step 5 Error rate, performance, specificity, sentivity, transaction success and failure are simulated 
