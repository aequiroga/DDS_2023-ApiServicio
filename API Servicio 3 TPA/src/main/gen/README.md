# org.openapitools.client - Kotlin client library for API Ranking

## Requires

* Kotlin 1.4.30
* Gradle 6.8.3

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
* Some Kotlin and Java types are fully qualified to avoid conflicts with types defined in OpenAPI definitions.
* Implementation of ApiClient is intended to reduce method counts, specifically to benefit Android targets.

<a name="documentation-for-api-endpoints"></a>
## Documentation for API Endpoints

All URIs are relative to *http://localhost*

Class | Method | HTTP request | Description
------------ | ------------- | ------------- | -------------
*ConfiguracionApi* | [**rankingImpactoIncidentesCambiarCnfNuevoCnfPost**](docs/ConfiguracionApi.md#rankingimpactoincidentescambiarcnfnuevocnfpost) | **POST** /RankingImpactoIncidentes/CambiarCnf/{nuevoCnf} | 
*RankingApi* | [**rankingImpactoIncidentes**](docs/RankingApi.md#rankingimpactoincidentes) | **POST** /RankingImpactoIncidentes/GenerarRanking | Obtener el ranking de entidades


<a name="documentation-for-models"></a>
## Documentation for Models

 - [org.openapitools.client.models.RequestEntidadDTO](docs/RequestEntidadDTO.md)
 - [org.openapitools.client.models.ResponseEntidadDTO](docs/ResponseEntidadDTO.md)


<a name="documentation-for-authorization"></a>
## Documentation for Authorization

All endpoints do not require authorization.
