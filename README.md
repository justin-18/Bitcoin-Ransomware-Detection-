# Bitcoin-Ransomware-Detection-

The BitcoinHeist project analyzes Bitcoin transactions to identify ransomware payments and suspicious Bitcoin addresses. By exploring the Bitcoin network from January 2009 to December 2018, this project aims to detect malicious addresses and help trace ransomware activity.

The dataset includes the following features:

Year: Year of the transaction.
Day: Day of the year (from 1 to 365).
Length: The length of the Bitcoin transaction.
Weight: The weight of the Bitcoin transaction.
Count: Number of transactions associated with the address.
Looped: Indicates whether the transaction is part of a loop.
Neighbors: Number of neighboring addresses involved in the transaction.
Income: The income or value transferred in the transaction.
Label: The type of ransomware associated with the address (e.g., Cerber, Locky).
Income per Day: A new feature derived by dividing the income by the day of the year.
Goal: The goal of this project is to:

Detect ransomware-related transactions on the Bitcoin network.
Identify suspicious Bitcoin addresses involved in ransomware payments. 3.Provide insights into Bitcoin network behaviors related to ransomware attacks.
Technologies Used:

Python: For data processing and machine learning modeling.
Pandas & NumPy: For data manipulation and handling large datasets.
Scikit-learn: For building and evaluating machine learning models.
