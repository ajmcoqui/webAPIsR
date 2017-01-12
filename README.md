# webAPIsR
These are example scripts for my "Using web APIs in R" presentation from rstudio::conf 2017.

## omdb.R
Get data from http://www.omdbapi.com/, and open-source movie database.  Explore the GET response; parse it with jsonlite or xml2, depending on the response format.

## swapi.R
Get data from https://swapi.co/, an open-source Star Wars database.  Explore the GET response, parse with jsonlite, create a function to parse automatically, write a loop to process a paged response.

## twitter.R
Get data from https://api.twitter.com using httr's convenience functions for OAuth 1.0 authentication.

## github.R
Get data from https://api.github.com using httr's convenience functions for OAuth 2.0 authentication.
