# portfolio-visualizer

This Jupyter notebook is designed to take a download from Schwab in .csv format and convert it into charts showing your
portfolio sector distribution as well as asset class distribution. It can handle Equities, Fixed Income (including 
preferred stock), ETFs, Mutual Funds, OTC Stocks, and Cash.

This notebook does take into account your ETFs and Mutual Funds, and will break down their underlying components into
their respective sectors. If you've ever wanted to see a true breakdown of your portfolio, this is the tool for you.

## Usage

1. Download your portfolio from Schwab in .csv format, it must include the following columns: Symbol, % of Account, and 
Security Type. You can also use a portfolio from a different broker, but the .csv must be formatted the same way.

2. Open the notebook in Jupyter, fill out the csv name/path in the second cell, and run all. Depending on the size of
your portfolio, this may take a few minutes. It uses yfinanace to get the sector information, and it's slow to return
results.

3. Scroll to the bottom to find your charts. The 'df' dataframe is also available for further analysis.

 
