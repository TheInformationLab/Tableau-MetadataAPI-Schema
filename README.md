# Tableau Metadata API Schema
 
The [Tableau Metadata API](https://help.tableau.com/v0.0/api/metadata_api/en-us/docs/meta_api_start.html) (currently in preview) makes use of a GraphQL endpoint to retrieve data. This is awesome for getting exactly the data structure you need, however querying with a blank canvas can be tricky.

To help with this Tableau Server comes with a GraphiQL interface which has autocomplete. Awesome! You can access it at {Server URL}/metadata/graphiql

## Autocomplete in Other Tools

However what if you want to use a third party querying interface such as Postman (the current Canary version has a GraphQL query constructor)? Well you'll need the Metadata API's GraphQL schema to import and enable autocomplete in third party tools. This repository will keep an up-to-date colelction of the GraphQL schema, allowing you to do this:

![Postman Autocomplete](https://github.com/TheInformationLab/Tableau-MetadataAPI-Schema/raw/master/GIFs/Postman%20Autocomplete.gif)

## Please Note!

A word of warning, the schemas contained in this repository are generated from released versions of Tableau Server and are not provided by Tableau directly. As such there are no guarantees as to the validity of these schemas and no official support is provided for them
