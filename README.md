# NSS-Simulation
Nelson-Siegel-Svensson Simulation. The code aims to price bonds according to Coupons and Maturities using ECB parameters.


The code can run wherever you want, until you have the packages.
For now is nothing more, nothing less, than a game thats shows the relations between coupons and maturities.
This two variables are extracted randomly from a Beta distrtibution to simulate pairs of C and T. The pairs gives back a price using the NSS model with the parameters provided by ECB in the current date



GOALS:

1) Update the code such that the coupons and maturities are NOT simulated but are extracted from real data providers such Borsaitaliana
2) The parameters for the curve (ALL BONDS) has to be inserted manually, I aim to make a live webscraping procedure such that the code uses the most recent data available.
3) Built a live comparing tool between the theoretical price of the NSS model and the market price

   

FURTHER POSSIBLE IMPLEMENTATIONS:

If the dataset is succesfully scraped live every day from a data provider, the live data can be used to estimate a NSS curve for any given country. 
For example, a mispricing of DE bonds can be caused by the distorsion caused by the selection of the ALL BONDS feature in the curve parameters. Is most likely that, using 
a tailored estimate for every country, the precision should be drastically higher. To do that, I need to learn how to make webscraping, which is not something I'm familiar with.


The ispiration from this code comes from a plot in the book of P. Veronesi: "FIXED INCOME SECURITIES, Valuation, Risk, and Risk Management" analyzed during the Fixed Income course in my Master's Degree in Tor Vergata.

Feel free to use this code and enhance it in the way you like the most.
