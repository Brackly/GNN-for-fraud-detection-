# GNN-for-fraud-detection-

Leveraging the power of Graph Neural networks, The idea behind this implementation is to detect fraud of a credit card transaction by performing a dot product of the sender card and the receiver card. 

Each credit card account is represented as a sum total of every other credit card it has interacted with and every transaction it has been involved with. Meaning if a card has previously interacted with a fraudulent transaction, it will be captured in its representation thus it will always carry fraud signals with it.

The task now becomes, predicting if a transaction between two cards is fraudlent.
