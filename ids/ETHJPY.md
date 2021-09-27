---
Title: ETH/JPY feed
Author: Brenda Loya
Created: 2021-09-27
---
# Data Spec ID: 3

# Request ID: 

0x000000000000000000000000000000000000000000000000000000000000003B

This ID correlates with a bytes32 version of the old uint256 request ID for the ETH/JPY feed(59).


# Data Specifications

A current ETH/JPY price.


## Description

This is the ID for a valid ETH/JPY price.  It does not specify which exchanges, but does not mean a price on any exchange.  Rather, it is the ambiguous current price which represents what parties would agree on as a given price for the current timestamp. 


## Granularity

1000000 (6 decimals)

## Example Value (w/ date)

9/27/21 - 349646000000


# Dispute Considerations

Be sure to use multiple exchanges, as one exchange could potentially slip out of alignment with others.  Also, be sure to note w/ regard to the "current" specification, that Ethereum blocks can take time to mine and prices move quickly.  A valid answer may not correspond to reality when it gets accepted in a block. 

# Notes

-

