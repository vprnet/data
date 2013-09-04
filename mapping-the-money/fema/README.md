#FEMA Build

http://www.vpr.net/apps/mapping-the-money/fema

##Variable Definitions

###Common Variables
`organizaton` - the recepient of a particular source of funding

`amount` - the dollar amount of funds received

###FEMA-map
This CSV includes all data used to populate the FEMA map at the above URL.

`ihp_total` - Individuals & Housing Program total funds disbursed. 
`ha_amount` - The Housing Assistance portion of the IHP total.
`on_amount` - The Other Needs portion of the IHP total.
`pa_total` - The Public Assitance total funds disbursed that are attributable to a town.
`hmgp_total` - The Hazard Mitigation Grant Program total funds disbursed.
`nfi_total` - The National Flood Insurance Program total funds disbursed.
`fema_total` - The total of all FEMA dollars disbursed that are attributable to a particular town.
`fha` - (Not mapped) The Federal Highway Adminstration funds disbursed by town.

###USDA-NRCS
The Natural Resources Conservation Science awarded funds that were broken down into various categories (business, residential, farm, and town)

`type` - the category of the recipient
