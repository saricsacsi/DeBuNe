# Project DeBuNe

Tiers: 
 
* start date (sd) = 2018/03/15 15:00 GMT
	rate:100  ( min. 50 eth, max. 5000 eth)
* Tier 1: sd + 15, end of tier1:  2018/03/31 00:00 GMT
	rate: 67  ( min. 25 eth, max. 2500 eth)
* Tier 2: sd + 30, end of tier2:  2018/04/15 00:00 GMT
	rate: 50  ( min. 1 eth, max. 100 eth)
* end date =  2018/04/30 00:00 GMT

## Public Sale (fallback function)

* min purchase depends on the date( tiers)
* max purchase depends on the date( tiers)
* pre-authorised

## Private Sale (placeTokens)

* by Admin user
* tokens minted on demand before or while sale is active.
* uses `placeTokens()` function

## Authorisation

* by Admin user or cs user 
* can approve or block

## Finishing the sale (owner) - passes control of token back to the owner

* call finishSale 

## Starting Trading

* call startTrading on the TOKEN



