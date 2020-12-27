# DevelopersApi

All URIs are relative to *https://virtserver.swaggerhub.com/aparavind/netraLib/1.0.0*

Method | HTTP request | Description
------------- | ------------- | -------------
[**searchInventory**](DevelopersApi.md#searchInventory) | **GET** /inventory | searches inventory


<a name="searchInventory"></a>
# **searchInventory**
> kotlin.Array&lt;InventoryItem&gt; searchInventory(searchString, skip, limit)

searches inventory

By passing in the appropriate options, you can search for available inventory in the system 

### Example
```kotlin
// Import classes:
//import io.swagger.client.infrastructure.*
//import io.swagger.client.models.*

val apiInstance = DevelopersApi()
val searchString : kotlin.String = searchString_example // kotlin.String | pass an optional search string for looking up inventory
val skip : kotlin.Int = 56 // kotlin.Int | number of records to skip for pagination
val limit : kotlin.Int = 56 // kotlin.Int | maximum number of records to return
try {
    val result : kotlin.Array<InventoryItem> = apiInstance.searchInventory(searchString, skip, limit)
    println(result)
} catch (e: ClientException) {
    println("4xx response calling DevelopersApi#searchInventory")
    e.printStackTrace()
} catch (e: ServerException) {
    println("5xx response calling DevelopersApi#searchInventory")
    e.printStackTrace()
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **searchString** | **kotlin.String**| pass an optional search string for looking up inventory | [optional]
 **skip** | **kotlin.Int**| number of records to skip for pagination | [optional]
 **limit** | **kotlin.Int**| maximum number of records to return | [optional]

### Return type

[**kotlin.Array&lt;InventoryItem&gt;**](InventoryItem.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

