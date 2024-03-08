# data-analysis-with-google-sheets
<h1>
  we have 2 different dataset and we have to find the insights from that datasets and the conditions are given us by the client.
</h1>
<h2>
  Task 1 : First Create a New Sub Sheet & Fetch all the Data from the Sheet called "Data Set" where Data from the PE Ratio is not Blank & PE Ratio < 100 using Query Function  and sort the data by Descending of Market Cap Amount.

Task 2 :  Now Create 2 Columns of Industry & NSE/BSE Code & Fetch Data from the Second Sheet with Vlookup, Make sure the Vlookup Formula is used with "ARRAYFORMULA" meaning formula will be written only once but will be applicable throughout the column,
Also make sure the Formula of Vlookup will be applied only until when data is there in the column, handle this with IF CONDITIONS in that same formula.

Task 3 : Now Create 2 More Columns at the End with the Heading "Bear Mode 1" & "Bear Mode 2"
  Bear Mode 1 Condition : Use IF Condition to print "Yes" if % Change from 52 Week High > 30 else "No"
  Bear Mode Condition 2 : Use IF Condition to print "Yes" if % Change from 52 Week Low < 30 else "No"
  Stock Status : Now Create a Column named "Stock Status" & then apply multiple IF Conditions to check if PE Ratio <65, Bear Mode 1 & 2 = "No" then Print "Good Stock" in the column else "".

Task 4 : Now find out the Highest value of the Market Cap & then categorize 60% and Above of the Highest Value as Large Cap Stocks, 40-60% as Medium Cap Stocks & 0-40% as Low Cap Stocks in a new Column at last naming it as Cap Size.

Task 5 : Now create a new sheet & fetch all Data where Stock Status = 'Good Stock' which will be your Final Organized Data Source so Create Proper Formatting to this Sheet like the Data Source Sheet & also add Appropriate Conditional Formatting Colour Scales.
</h2>
