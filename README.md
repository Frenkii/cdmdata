# cdmdata
## How Do I Submit Updates?
Updates to data should be made directly by submitting a PR.

## taxizones.txt
You can define a zone with an specific taxiTime with the following specifications 
`AIRPORT:RUNWAY:BOTTOM_LEFT_LAT:BOTTOM_LEFT_LON:TOP_LEFT_LAT:TOP_LEFT_LON:TOP_RIGHT_LAT:TOP_RIGHT_LON:BOTTOM_RIGHT_LAT:BOTTOM_RIGHT_LON:TAXITIME` 

ex:`LEBL:25L:41.286876:2.067318:41.290236:2.065955:41.295688:2.082523:41.292662:2.084613:10`

if no taxizone defined, the default taxi time is set from the Config.xml

## rate.txt
You can set the rate/hour for specific runway and airport, if not declared, **AIRPORT WILL NOT BE CONSIDERED AS A CDM AIRPORT**. 

You can declare every runway rate with the following format: `AIRPORT:RUNWAY=NormalRate_LvoRate` 

ex:`LEBL:25L=40_20` 

(Each line has a runway with his rate)
