
# InventoryItem

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **kotlin.String** | This is the id of the book.the barcode will hopefully be already stuck | 
**name** | **kotlin.String** | This is the name of the book | 
**contentType** | [**inline**](#ContentTypeEnum) | Can be on of the options |  [optional]
**bookType** | [**inline**](#BookTypeEnum) | This describes the book |  [optional]
**owner** | [**inline**](#OwnerEnum) |  |  [optional]


<a name="ContentTypeEnum"></a>
## Enum: contentType
Name | Value
---- | -----
contentType | Religious, School_book, Comic, Newspaper


<a name="BookTypeEnum"></a>
## Enum: bookType
Name | Value
---- | -----
bookType | Notebook, TextBook, DrawingBook, Files


<a name="OwnerEnum"></a>
## Enum: owner
Name | Value
---- | -----
owner | srinidhi, aravind, vasu



