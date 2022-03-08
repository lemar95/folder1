Trackcoin is an application that enables its users to track their favourite cryptocurrencies token prices. 

Tokens are represented by the token symbol and current price in USD.
In the first csv file, you can find a list of all supported tokens and their respective prices. In the second you will find token quantity of users by their id.

Token prices file: https://drive.google.com/file/d/1tLREixzmph0u0E_RlDVB7DYnzTHkrQRy/view?usp=sharing 

User token quantity file:
https://drive.google.com/file/d/1B6OBKQCL3SLJ3bmMdICwMm_78Di0BdBW/view?usp=sharing

1. Create an API that returns information about the user's tokens using user id as a path parameter. 
 - token symbol
 - current price of token
 - Value of tokens - (token price * quantity)
 - flag aboveDollar, which is true if the current token price is greater or equal to 1USD
 - enable response to be paginated.
results should be sorted by value of tokens
