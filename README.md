# Option-Styles-in-Derivative-Markets-

**Assumptions**
1. There are no transaction costs.
2. All trading profits (net of trading losses) are subject to the same tax rate (not
considered by us).
3. Since we are only considering the payoff and profit diagram, we have excluded
the borrowing and lending requirements for any trade.
4. Since the motivation of the project is to have a better understanding of
different option styles we have focussed on varying spot prices and checking
their effect on the payoff, without including the calculation of the present
value of the trade each time.\

**Category 1:**\
**Option style (Less common exercise rights)**\
● Compound option\
A compound option is an option on another option and as such presents the
holder with two separate exercise dates and decisions. If the first exercise date
arrives and the 'inner' option's market price is below the agreed strike the first
option will be exercised (European style), giving the holder a further option at
final maturity.\
**Assumptions:**\
● Strike Price K1 = INR 50\
● Strike Price K2 = INR 450\
● S: Spot price variation\
● The fixed premium price of INR 2.5 for each option (2.5+2.5 = 5 for two)\
● Double option\
A double option gives the purchaser a composite call-and-put option (an
option to either buy or sell) in a single contract. This has only ever been
available in commodities markets and has never been traded on an exchange.\
**Assumptions:**\
● Strike Price K = INR 100\
● S: Spot price variation\
● The fixed premium price of INR 2.5\
● Capped-style option\
A capped-style option is not an interest rate cap but a conventional option
with a pre-defined profit cap written into the contract. A capped-style option
is automatically exercised when the underlying security closes at a price
making the option's mark to market match the specified amount.\
**Assumptions:**\
● Strike Price K = INR 100\
● S: Spot price variation\
● The fixed premium price of INR 2.5\
● Fixed capped value = INR 5\
**Category 2:**\
_Option style (Exotic options with standard exercise style)_\
● Rainbow option\
A rainbow option is a basket option where the weightings depend on the final
performances of the components. A common special case is an option on the
best-performing of several stocks.\
**Assumptions:**\
● Strike Price K= INR 100\
● S1, S2, and S3 are historical daily closing prices of three stocks which
are the components chosen by us for the rainbow option.\
● For the rainbow option, we are considering the payoff is calculated
according to the best performing stock on a daily basis.\
● The fixed premium price of INR 0.5\
● Exchange option\
An exchange option is the right to exchange one asset for another (such as a
sugar future for a corporate bond).\
**Assumptions:**\
● Here one of the spot prices is like strike price and the other is spot
price (S1 and S2 respectively)\
● The fixed premium price of INR 2.5\
● Basket option\
A basket option is an option on the weighted average of several underlying
assets.\
**Assumptions:**\
● Strike Price K= INR 100\
● S1, S2, and S3 are randomly assigned values to check the variation of
the payoff.\
● The fixed premium price of INR 0.5\
● Randomly assigned weights are 0.4, 0.2, and 0.4 to S1, S2, and S3
respectively\
**Category 3:**\
Option style (Non-vanilla path depended on exotic options)\
● Asian Option\
Asian options are path-dependent: their value depends on the average of the
stock price during the life of the option. There are two basic variations: an
average price option pays the difference between the average stock price and
the exercise price; e.g., the payoff of an average price call option = max[0,
S(average) - K]. An average strike option pays the difference between the final
price and the average price; e.g., the payoff of an average strike call = max[0, 0,
S(T) - S(average)].\
**Assumptions:**\
● Strike Price K= INR 100\
● S : Average Spot Price Variation\
● The fixed premium price of INR 2.5\
● Calculating payoff for average price call option\
● Binary Option\
A binary option is a type of options contract in which the payout depends
entirely on the outcome of a yes/no proposition and typically relates to
whether the price of a particular asset will rise above or fall below a specified
amount.\
**Assumptions:**\
● Strike Price K= INR 100\
● S : Spot Price Variation\
● The fixed premium price of INR 10\
● Barrier Option\
A barrier option is a type of derivative where the payoff depends on whether
or not the underlying asset has reached or exceeded a predetermined price. A
barrier option can be a knock-out, meaning it expires worthless if the
underlying exceeds a certain price, limiting profits for the holder and limiting
losses for the writer. It can also be a knock-in, meaning it has no value until the
underlying reaches a certain price.\
**Assumptions:**\
● Strike Price K= INR 100\
● Knock Out Barrier Price KO = INR 145\
● S: Spot Price Variation\
● The fixed premium price of INR 10\
**REFERENCES:**\
https://en.wikipedia.org/wiki/Rainbow_option \
https://en.wikipedia.org/wiki/Basket_option \
https://investexcel.net/exchange-options-excel/ \
https://en.wikipedia.org/wiki/Option_style \
https://en.wikipedia.org/wiki/Chooser_option \
https://web.ma.utexas.edu/users/mcudina/m339d-apr-30.pdf \
https://www.dropbox.com/s/yep4aztie0ypj66/112218-exotic-barrier.xlsx?dl=0 \
De Weert, F., 2011. Exotic options trading (Vol. 564). John Wiley & Sons. \
Sundaram, R.K. and Das, S.R., 2011. Derivatives: principles and practice. New York, NY: McGraw-Hill
Irwin. 
