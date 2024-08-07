Workflow:

1. Run 'API_Request.ipynb' which writes 'API_Request_Output.JSON'
2. Run 'Data_processing.ipynb' which writes 'Processed_Output.CSV'
3. Run 'Weighted_Average.ipynb' which writes 'Weighted_Average.CSV'
4. Important changes in Microsoft Power BI:
	- "en-US" language for reading numbers as '15.0' and not '15,0'
	- Make sure 'Positions', 'Price' and 'Weighted Average Price' columns are 'type numbers' and not 'type text'