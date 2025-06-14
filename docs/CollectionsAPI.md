# \CollectionsAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CollectionsAddManyPost**](CollectionsAPI.md#CollectionsAddManyPost) | **Post** /collections/add-many | Add document to multiple collections
[**CollectionsCollectionIdDelete**](CollectionsAPI.md#CollectionsCollectionIdDelete) | **Delete** /collections/{collection_id} | Delete collection
[**CollectionsCollectionIdDocumentIdDelete**](CollectionsAPI.md#CollectionsCollectionIdDocumentIdDelete) | **Delete** /collections/{collection_id}/{document_id} | Remove document from collection
[**CollectionsCollectionIdDocumentIdPost**](CollectionsAPI.md#CollectionsCollectionIdDocumentIdPost) | **Post** /collections/{collection_id}/{document_id} | Add document to collection
[**CollectionsCollectionIdGet**](CollectionsAPI.md#CollectionsCollectionIdGet) | **Get** /collections/{collection_id} | Get collection by ID
[**CollectionsCollectionIdPut**](CollectionsAPI.md#CollectionsCollectionIdPut) | **Put** /collections/{collection_id} | Update collection
[**CollectionsCollectionIdStatisticsGet**](CollectionsAPI.md#CollectionsCollectionIdStatisticsGet) | **Get** /collections/{collection_id}/statistics | Get collection statistics
[**CollectionsGet**](CollectionsAPI.md#CollectionsGet) | **Get** /collections | Get all collections
[**CollectionsPost**](CollectionsAPI.md#CollectionsPost) | **Post** /collections | Create a new collection



## CollectionsAddManyPost

> HelperResponse CollectionsAddManyPost(ctx).Request(request).Execute()

Add document to multiple collections



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	request := *openapiclient.NewDtoAddDocumentToCollectionsReq([]int32{int32(123)}, int32(123)) // DtoAddDocumentToCollectionsReq | Collection IDs

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CollectionsAPI.CollectionsAddManyPost(context.Background()).Request(request).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsAPI.CollectionsAddManyPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CollectionsAddManyPost`: HelperResponse
	fmt.Fprintf(os.Stdout, "Response from `CollectionsAPI.CollectionsAddManyPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCollectionsAddManyPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**DtoAddDocumentToCollectionsReq**](DtoAddDocumentToCollectionsReq.md) | Collection IDs | 

### Return type

[**HelperResponse**](HelperResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CollectionsCollectionIdDelete

> HelperResponse CollectionsCollectionIdDelete(ctx, collectionId).Execute()

Delete collection



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	collectionId := "collectionId_example" // string | Collection ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CollectionsAPI.CollectionsCollectionIdDelete(context.Background(), collectionId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsAPI.CollectionsCollectionIdDelete``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CollectionsCollectionIdDelete`: HelperResponse
	fmt.Fprintf(os.Stdout, "Response from `CollectionsAPI.CollectionsCollectionIdDelete`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**collectionId** | **string** | Collection ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiCollectionsCollectionIdDeleteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**HelperResponse**](HelperResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CollectionsCollectionIdDocumentIdDelete

> HelperResponse CollectionsCollectionIdDocumentIdDelete(ctx, collectionId, documentId).Execute()

Remove document from collection



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	collectionId := "collectionId_example" // string | Collection ID
	documentId := "documentId_example" // string | Document ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CollectionsAPI.CollectionsCollectionIdDocumentIdDelete(context.Background(), collectionId, documentId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsAPI.CollectionsCollectionIdDocumentIdDelete``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CollectionsCollectionIdDocumentIdDelete`: HelperResponse
	fmt.Fprintf(os.Stdout, "Response from `CollectionsAPI.CollectionsCollectionIdDocumentIdDelete`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**collectionId** | **string** | Collection ID | 
**documentId** | **string** | Document ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiCollectionsCollectionIdDocumentIdDeleteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**HelperResponse**](HelperResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CollectionsCollectionIdDocumentIdPost

> HelperResponse CollectionsCollectionIdDocumentIdPost(ctx, collectionId, documentId).Execute()

Add document to collection



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	collectionId := "collectionId_example" // string | Collection ID
	documentId := "documentId_example" // string | Document ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CollectionsAPI.CollectionsCollectionIdDocumentIdPost(context.Background(), collectionId, documentId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsAPI.CollectionsCollectionIdDocumentIdPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CollectionsCollectionIdDocumentIdPost`: HelperResponse
	fmt.Fprintf(os.Stdout, "Response from `CollectionsAPI.CollectionsCollectionIdDocumentIdPost`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**collectionId** | **string** | Collection ID | 
**documentId** | **string** | Document ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiCollectionsCollectionIdDocumentIdPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**HelperResponse**](HelperResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CollectionsCollectionIdGet

> CollectionsPost201Response CollectionsCollectionIdGet(ctx, collectionId).Execute()

Get collection by ID



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	collectionId := "collectionId_example" // string | Collection ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CollectionsAPI.CollectionsCollectionIdGet(context.Background(), collectionId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsAPI.CollectionsCollectionIdGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CollectionsCollectionIdGet`: CollectionsPost201Response
	fmt.Fprintf(os.Stdout, "Response from `CollectionsAPI.CollectionsCollectionIdGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**collectionId** | **string** | Collection ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiCollectionsCollectionIdGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**CollectionsPost201Response**](CollectionsPost201Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CollectionsCollectionIdPut

> CollectionsPost201Response CollectionsCollectionIdPut(ctx, collectionId).Collection(collection).Execute()

Update collection



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	collectionId := "collectionId_example" // string | Collection ID
	collection := *openapiclient.NewDtoUpdateCollectionReq("Name_example") // DtoUpdateCollectionReq | New collection name

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CollectionsAPI.CollectionsCollectionIdPut(context.Background(), collectionId).Collection(collection).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsAPI.CollectionsCollectionIdPut``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CollectionsCollectionIdPut`: CollectionsPost201Response
	fmt.Fprintf(os.Stdout, "Response from `CollectionsAPI.CollectionsCollectionIdPut`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**collectionId** | **string** | Collection ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiCollectionsCollectionIdPutRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **collection** | [**DtoUpdateCollectionReq**](DtoUpdateCollectionReq.md) | New collection name | 

### Return type

[**CollectionsPost201Response**](CollectionsPost201Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CollectionsCollectionIdStatisticsGet

> CollectionsCollectionIdStatisticsGet200Response CollectionsCollectionIdStatisticsGet(ctx, collectionId).Execute()

Get collection statistics



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	collectionId := "collectionId_example" // string | Collection ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CollectionsAPI.CollectionsCollectionIdStatisticsGet(context.Background(), collectionId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsAPI.CollectionsCollectionIdStatisticsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CollectionsCollectionIdStatisticsGet`: CollectionsCollectionIdStatisticsGet200Response
	fmt.Fprintf(os.Stdout, "Response from `CollectionsAPI.CollectionsCollectionIdStatisticsGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**collectionId** | **string** | Collection ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiCollectionsCollectionIdStatisticsGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**CollectionsCollectionIdStatisticsGet200Response**](CollectionsCollectionIdStatisticsGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CollectionsGet

> CollectionsGet200Response CollectionsGet(ctx).Execute()

Get all collections



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CollectionsAPI.CollectionsGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsAPI.CollectionsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CollectionsGet`: CollectionsGet200Response
	fmt.Fprintf(os.Stdout, "Response from `CollectionsAPI.CollectionsGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiCollectionsGetRequest struct via the builder pattern


### Return type

[**CollectionsGet200Response**](CollectionsGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CollectionsPost

> CollectionsPost201Response CollectionsPost(ctx).Collection(collection).Execute()

Create a new collection



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	collection := *openapiclient.NewDtoCreateCollectionReq("Name_example") // DtoCreateCollectionReq | Collection details

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CollectionsAPI.CollectionsPost(context.Background()).Collection(collection).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsAPI.CollectionsPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CollectionsPost`: CollectionsPost201Response
	fmt.Fprintf(os.Stdout, "Response from `CollectionsAPI.CollectionsPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCollectionsPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **collection** | [**DtoCreateCollectionReq**](DtoCreateCollectionReq.md) | Collection details | 

### Return type

[**CollectionsPost201Response**](CollectionsPost201Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

