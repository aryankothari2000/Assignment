# SUBMISSION-OF-ASSIGNMENT-ARYAN-KOTHARI

**1) querydata.json :** contains the trade data which has been extracted using graphQL queries, for any pools on any ERC20 based DEX protocols,
for the UNI/WETH pair.

**2) assignment.ipynb** contains the code which manipulates the trade data to provide the following data in a DataFrame: Timestamp, Side (Buy or Sell),
Base currency quantity traded, Quote currency quantity traded, Volume in USD, Liquidity in pool,
Pool ID.

Also it contains the code which generates the histogram for the base currency trade quantity, which let us know about the number of transactions in different quantity ranges

**3) INSTRUCTIONS TO RUN CODE** <br/>
-> Upload the assignment.ipynb file on jupyter-notebook <br/>
-> Store the querydata.json file on desktop and change it's location in the assignment.ipynb where in the bracket of this f = open(r'C:\Users\LENOVO\Desktop\querydata.json',) <br/>
-> Run the file uploaded on jupyter notebook<br/>
