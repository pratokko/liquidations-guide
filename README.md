# liquidations-guide

1. Blacklisted Tokens
2. Zero amount Reverts
3. isLiquidatable doesnot account for fees
4. liquidation should be collecting the latest fees
5. liquidation reverts when a postion becomes insolvent
6. liqudation reverts when a position cannot cover the fees
7. liquidation reverts due to accounting error
8. liquidation does not prioritize the lowest Loan to value (LTV) asset
9. liquidation require much gas
10. liquidation does not prioritize the caller fee

** make sure the liquidators are incentivised to that they carry out the liquidations in time
11. liquidations cause users to lose rewards they had accumulated

** Always factor in the rewards that users have accumulated so before you delete a position make sure that the position struct does not have any pending rewards to avoid user loss

12. Users force themselves to be liquidatable
13. positions in profit can still be liquidatable

## NOTICE All the scenarios above will have a vivid explanation
