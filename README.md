# Trade.gov Sanctions List search Mendix Connector

This is a Mendix connector to perform a search of the Trade.Gov Sanctions list using the Consolidated Screening List API.

To run a search you first need to call the Create sanctions search request action with the endpoint and access key set. Then call the additional actions to set the parameters that you want to apply for the search, such as the name and countries applicable.

You will need to get an access token to use the service. Go to https://developer.trade.gov/ and follow the instructions in Subscribing to an API. Access is free subject to conditions. When you get the token then place it into the SanctionsRequest object.

Finally call the Execute TradeDotGov sanctions search action which will return the results.

There are no dependencies.

This is implemented using Mendix 9.8.0.
