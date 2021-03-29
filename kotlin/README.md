# io.swagger.client - Kotlin client library for Simple Inventory API

## Requires

* Kotlin 1.1.2
* Gradle 3.3

## Build

First, create the gradle wrapper script:

```
gradle wrapper
```

Then, run:

```
./gradlew check assemble
```

This runs all tests and packages the library.

## Features/Implementation Notes

* Supports JSON inputs/outputs, File inputs, and Form inputs.
* Supports collection formats for query parameters: csv, tsv, ssv, pipes.
* Some Kotlin and Java types are fully qualified to avoid conflicts with types defined in Swagger definitions.
* Implementation of ApiClient is intended to reduce method counts, specifically to benefit Android targets.

<a name="documentation-for-api-endpoints"></a>
## Documentation for API Endpoints

All URIs are relative to *https://virtserver.swaggerhub.com/aparavind/netraLib/1.0.1*

Class | Method | HTTP request | Description
------------ | ------------- | ------------- | -------------
*AdminsApi* | [**addInventory**](docs/AdminsApi.md#addinventory) | **POST** /inventory | adds an inventory item
*DevelopersApi* | [**searchInventory**](docs/DevelopersApi.md#searchinventory) | **GET** /inventory | searches inventory


<a name="documentation-for-models"></a>
## Documentation for Models

 - [io.swagger.client.models.InventoryItem](docs/InventoryItem.md)


<a name="documentation-for-authorization"></a>
## Documentation for Authorization

All endpoints do not require authorization.
