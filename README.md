# Trade.gov Sanctions List search Mendix Connector

This is a Mendix connector to perform a search of the Trade.Gov Sanctions list using the Consolidated Screening List API.

To run a search you add a call from a microflow to the TradeDotGov Sanctions Search Action. You will supply a name, Sanctions API endpoint, an access token and a list of countries to search to the call to the TradeDotGov Sanctions Search Action.

You will need to get an access token to use the service. Go to https://api.trade.gov/apps/store/ita and follow the instructions in Subscribing to an API. Access is free subject to conditions. When you get the token then place it into the SanctionsRequest object.

Example pages/code are included in the Examples folder and these can be duplicated and copied into your own module in your app which may give you a head start.

The only (small) dependancies are where the example pages make use of the Atlas 3 default layouts.
