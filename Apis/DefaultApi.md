# DefaultApi

All URIs are relative to *http://localhost:8080/api*

| Method | HTTP request | Description |
|------------- | ------------- | -------------|
| [**foodDelete**](DefaultApi.md#foodDelete) | **DELETE** /food | Delete Food |
| [**foodGet**](DefaultApi.md#foodGet) | **GET** /food | Get Food |
| [**foodPost**](DefaultApi.md#foodPost) | **POST** /food | Create Food |
| [**foodPut**](DefaultApi.md#foodPut) | **PUT** /food | Update Food |
| [**nutrientDelete**](DefaultApi.md#nutrientDelete) | **DELETE** /nutrient | Delete Nutrient |
| [**nutrientGet**](DefaultApi.md#nutrientGet) | **GET** /nutrient | Get Nutrient |
| [**nutrientPost**](DefaultApi.md#nutrientPost) | **POST** /nutrient | Create Nutrient |
| [**nutrientPut**](DefaultApi.md#nutrientPut) | **PUT** /nutrient | Update Nutrient |
| [**productDelete**](DefaultApi.md#productDelete) | **DELETE** /product | Delete Product |
| [**productGet**](DefaultApi.md#productGet) | **GET** /product | Get Products |
| [**productPost**](DefaultApi.md#productPost) | **POST** /product | Create Product |
| [**productPut**](DefaultApi.md#productPut) | **PUT** /product | Update Product |
| [**recipeDelete**](DefaultApi.md#recipeDelete) | **DELETE** /recipe | Delete a recipe |
| [**recipeGet**](DefaultApi.md#recipeGet) | **GET** /recipe | Get recipe data |
| [**recipePost**](DefaultApi.md#recipePost) | **POST** /recipe | Create a recipe |
| [**recipePut**](DefaultApi.md#recipePut) | **PUT** /recipe | Update a recipe |
| [**todoDelete**](DefaultApi.md#todoDelete) | **DELETE** /todo | Delete a TodoList |
| [**todoEntryDelete**](DefaultApi.md#todoEntryDelete) | **DELETE** /todo/entry | Delete a TodoList entry |
| [**todoEntryGet**](DefaultApi.md#todoEntryGet) | **GET** /todo/entry | Get TodoList entries |
| [**todoEntryPost**](DefaultApi.md#todoEntryPost) | **POST** /todo/entry | Create a TodoList entry |
| [**todoEntryPut**](DefaultApi.md#todoEntryPut) | **PUT** /todo/entry | Update a TodoList entry |
| [**todoGet**](DefaultApi.md#todoGet) | **GET** /todo | Get TodoLists |
| [**todoPost**](DefaultApi.md#todoPost) | **POST** /todo | Create a TodoList |
| [**todoPut**](DefaultApi.md#todoPut) | **PUT** /todo | Update a TodoList |
| [**unitOfMeasurementDelete**](DefaultApi.md#unitOfMeasurementDelete) | **DELETE** /unitOfMeasurement | Delete a UnitOfMeasurement |
| [**unitOfMeasurementGet**](DefaultApi.md#unitOfMeasurementGet) | **GET** /unitOfMeasurement | Get UnitOfMeasurements |
| [**unitOfMeasurementPost**](DefaultApi.md#unitOfMeasurementPost) | **POST** /unitOfMeasurement | Create a unitOfMeasurement |
| [**unitOfMeasurementPut**](DefaultApi.md#unitOfMeasurementPut) | **PUT** /unitOfMeasurement | Update a unitOfMeasurement |


<a name="foodDelete"></a>
# **foodDelete**
> String foodDelete(id)

Delete Food

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **id** | **Integer**| ID of the Food | [default to null] |

### Return type

**String**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="foodGet"></a>
# **foodGet**
> List foodGet(id, page, perPage)

Get Food

    Either page or ID must be given

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **id** | **Integer**| ID of the Food | [optional] [default to null] |
| **page** | **Integer**| Page to look for | [optional] [default to 1] |
| **perPage** | **Integer**| Items per page | [optional] [default to 50] |

### Return type

[**List**](../Models/Food.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="foodPost"></a>
# **foodPost**
> List foodPost(Food)

Create Food

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **Food** | [**Food**](../Models/Food.md)|  | |

### Return type

[**List**](../Models/Food.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="foodPut"></a>
# **foodPut**
> List foodPut(id, Food)

Update Food

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **id** | **Integer**| ID of the Food | [default to null] |
| **Food** | [**Food**](../Models/Food.md)|  | |

### Return type

[**List**](../Models/Food.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="nutrientDelete"></a>
# **nutrientDelete**
> String nutrientDelete(id)

Delete Nutrient

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **id** | **Integer**| ID of the Nutrient | [default to null] |

### Return type

**String**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="nutrientGet"></a>
# **nutrientGet**
> List nutrientGet(id, page, perPage)

Get Nutrient

    Either page or ID must be given

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **id** | **Integer**| ID of the Nutrient | [optional] [default to null] |
| **page** | **Integer**| Page to look for | [optional] [default to 1] |
| **perPage** | **Integer**| Items per page | [optional] [default to 50] |

### Return type

[**List**](../Models/Nutrient.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="nutrientPost"></a>
# **nutrientPost**
> List nutrientPost(Nutrient)

Create Nutrient

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **Nutrient** | [**Nutrient**](../Models/Nutrient.md)|  | |

### Return type

[**List**](../Models/Nutrient.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="nutrientPut"></a>
# **nutrientPut**
> List nutrientPut(id, Nutrient)

Update Nutrient

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **id** | **Integer**| ID of the Nutrient | [default to null] |
| **Nutrient** | [**Nutrient**](../Models/Nutrient.md)|  | |

### Return type

[**List**](../Models/Nutrient.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="productDelete"></a>
# **productDelete**
> String productDelete(id, ean)

Delete Product

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **id** | **Integer**| ID of the Product | [optional] [default to null] |
| **ean** | **Integer**| EAN of the Product | [optional] [default to null] |

### Return type

**String**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="productGet"></a>
# **productGet**
> List productGet(id, ean, page, perPage)

Get Products

    Either page or ID must be given

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **id** | **Integer**| ID of the Product | [optional] [default to null] |
| **ean** | **Integer**| EAN of the Product | [optional] [default to null] |
| **page** | **Integer**| Page to look for | [optional] [default to 1] |
| **perPage** | **Integer**| Items per page | [optional] [default to 50] |

### Return type

[**List**](../Models/Product.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="productPost"></a>
# **productPost**
> List productPost(Product)

Create Product

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **Product** | [**Product**](../Models/Product.md)|  | |

### Return type

[**List**](../Models/Product.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="productPut"></a>
# **productPut**
> List productPut(Product, id, ean)

Update Product

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **Product** | [**Product**](../Models/Product.md)|  | |
| **id** | **Integer**| ID of the Product | [optional] [default to null] |
| **ean** | **Integer**| EAN of the Product | [optional] [default to null] |

### Return type

[**List**](../Models/Product.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="recipeDelete"></a>
# **recipeDelete**
> recipeDelete(id)

Delete a recipe

    Deletes a recipe

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **id** | **Integer**|  | [default to null] |

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

<a name="recipeGet"></a>
# **recipeGet**
> List recipeGet(id, page, perPage)

Get recipe data

    Either page or ID must be given

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **id** | **Integer**| ID of the Recipe | [optional] [default to null] |
| **page** | **Integer**| Page to look for | [optional] [default to 1] |
| **perPage** | **Integer**| Items per page | [optional] [default to 50] |

### Return type

[**List**](../Models/Recipe.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="recipePost"></a>
# **recipePost**
> Recipe recipePost(Recipe)

Create a recipe

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **Recipe** | [**Recipe**](../Models/Recipe.md)|  | |

### Return type

[**Recipe**](../Models/Recipe.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="recipePut"></a>
# **recipePut**
> Recipe recipePut(id, Recipe)

Update a recipe

    Updates a recipe and returns it

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **id** | **Integer**|  | [default to null] |
| **Recipe** | [**Recipe**](../Models/Recipe.md)|  | |

### Return type

[**Recipe**](../Models/Recipe.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="todoDelete"></a>
# **todoDelete**
> String todoDelete(id)

Delete a TodoList

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **id** | **Integer**| The ID of the TodoList | [default to null] |

### Return type

**String**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="todoEntryDelete"></a>
# **todoEntryDelete**
> String todoEntryDelete(id)

Delete a TodoList entry

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **id** | **Integer**| The ID of the TodoList entry | [default to null] |

### Return type

**String**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="todoEntryGet"></a>
# **todoEntryGet**
> TodoListEntryWithChilds todoEntryGet(id)

Get TodoList entries

    Either page or ID must be given

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **id** | **Integer**| The ID of the TodoListEntry | [optional] [default to null] |

### Return type

[**TodoListEntryWithChilds**](../Models/TodoListEntryWithChilds.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="todoEntryPost"></a>
# **todoEntryPost**
> List todoEntryPost(TodoListEntry)

Create a TodoList entry

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **TodoListEntry** | [**TodoListEntry**](../Models/TodoListEntry.md)|  | |

### Return type

[**List**](../Models/TodoListEntryWithChilds.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="todoEntryPut"></a>
# **todoEntryPut**
> List todoEntryPut(id, TodoListEntry)

Update a TodoList entry

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **id** | **Integer**| The ID of the TodoListEntry | [default to null] |
| **TodoListEntry** | [**TodoListEntry**](../Models/TodoListEntry.md)|  | |

### Return type

[**List**](../Models/TodoListEntryWithChilds.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="todoGet"></a>
# **todoGet**
> _todo_get_200_response todoGet(id, page, perPage)

Get TodoLists

    Either page or ID must be given

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **id** | **Integer**| The ID of the TodoList | [optional] [default to null] |
| **page** | **Integer**| Page to look for | [optional] [default to 1] |
| **perPage** | **Integer**| Items per page | [optional] [default to 50] |

### Return type

[**_todo_get_200_response**](../Models/_todo_get_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="todoPost"></a>
# **todoPost**
> List todoPost(TodoList)

Create a TodoList

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **TodoList** | [**TodoList**](../Models/TodoList.md)|  | |

### Return type

[**List**](../Models/TodoList.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="todoPut"></a>
# **todoPut**
> List todoPut(id, TodoList)

Update a TodoList

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **id** | **Integer**| The ID of the TodoList | [default to null] |
| **TodoList** | [**TodoList**](../Models/TodoList.md)|  | |

### Return type

[**List**](../Models/TodoList.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="unitOfMeasurementDelete"></a>
# **unitOfMeasurementDelete**
> String unitOfMeasurementDelete(id)

Delete a UnitOfMeasurement

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **id** | **Integer**|  | [default to null] |

### Return type

**String**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="unitOfMeasurementGet"></a>
# **unitOfMeasurementGet**
> List unitOfMeasurementGet(id, page, perPage)

Get UnitOfMeasurements

    Either page or ID must be given

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **id** | **Integer**| ID of the UnitOfMeasurement | [optional] [default to null] |
| **page** | **Integer**| Page to look for | [optional] [default to 1] |
| **perPage** | **Integer**| Items per page | [optional] [default to 50] |

### Return type

[**List**](../Models/UnitOfMeasurement.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="unitOfMeasurementPost"></a>
# **unitOfMeasurementPost**
> UnitOfMeasurement unitOfMeasurementPost(UnitOfMeasurement)

Create a unitOfMeasurement

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **UnitOfMeasurement** | [**UnitOfMeasurement**](../Models/UnitOfMeasurement.md)|  | |

### Return type

[**UnitOfMeasurement**](../Models/UnitOfMeasurement.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="unitOfMeasurementPut"></a>
# **unitOfMeasurementPut**
> UnitOfMeasurement unitOfMeasurementPut(id, UnitOfMeasurement)

Update a unitOfMeasurement

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **id** | **Integer**| ID of the UnitOfMeasurement | [default to null] |
| **UnitOfMeasurement** | [**UnitOfMeasurement**](../Models/UnitOfMeasurement.md)|  | |

### Return type

[**UnitOfMeasurement**](../Models/UnitOfMeasurement.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

