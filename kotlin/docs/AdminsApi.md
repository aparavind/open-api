# AdminsApi

All URIs are relative to *https://virtserver.swaggerhub.com/aparavind/netraLib/1.0.0*

Method | HTTP request | Description
------------- | ------------- | -------------
[**addInventory**](AdminsApi.md#addInventory) | **POST** /inventory | adds an inventory item


<a name="addInventory"></a>
# **addInventory**
> addInventory(inventoryItem)

adds an inventory item

Adds an item to the system

### Example
```kotlin
// Import classes:
//import io.swagger.client.infrastructure.*
//import io.swagger.client.models.*

val apiInstance = AdminsApi()
val inventoryItem : InventoryItem =  // InventoryItem | Inventory item to add
try {
    apiInstance.addInventory(inventoryItem)
} catch (e: ClientException) {
    println("4xx response calling AdminsApi#addInventory")
    e.printStackTrace()
} catch (e: ServerException) {
    println("5xx response calling AdminsApi#addInventory")
    e.printStackTrace()
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **inventoryItem** | [**InventoryItem**](InventoryItem.md)| Inventory item to add | [optional]

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

