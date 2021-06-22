# SUBMISSION-OF-ASSIGNMENT-ARYAN-KOTHARI

**querydata.json :** contains the trade data which has been extracted using graphQL queries, for any pools on any ERC20 based DEX protocols,
for the UNI/WETH pair.

**assignment.ipynb** contains the code which manipulates the trade data to provide the following data in a DataFrame: Timestamp, Side (Buy or Sell),
Base currency quantity traded, Quote currency quantity traded, Volume in USD, Liquidity in pool,
Pool ID.

Also it contains the code which generates the histogram for the base currency trade quantity, which let us know about the number of transactions in different quantity ranges

**INSTRUCTIONS TO RUN CODE** 
-> Upload the assignment.ipynb file on jupyter-notebook 
-> Store the querydata.json file 
-> Run the file after it get's uploaded
