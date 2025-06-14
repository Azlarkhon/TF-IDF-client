# \DocumentsAPI

All URIs are relative to *http://37.9.53.45:8080*

Method | HTTP request | Description
------------- | ------------- | -------------
[**DocumentsDocumentIdDelete**](DocumentsAPI.md#DocumentsDocumentIdDelete) | **Delete** /documents/{document_id} | Delete a document
[**DocumentsDocumentIdGet**](DocumentsAPI.md#DocumentsDocumentIdGet) | **Get** /documents/{document_id} | Get a specific document
[**DocumentsDocumentIdHuffmanGet**](DocumentsAPI.md#DocumentsDocumentIdHuffmanGet) | **Get** /documents/{document_id}/huffman | Get Huffman encoded and decoded content of a document
[**DocumentsDocumentIdStatisticsGet**](DocumentsAPI.md#DocumentsDocumentIdStatisticsGet) | **Get** /documents/{document_id}/statistics | Get document statistics
[**DocumentsGet**](DocumentsAPI.md#DocumentsGet) | **Get** /documents | Get all user documents



## DocumentsDocumentIdDelete

> HelperResponse DocumentsDocumentIdDelete(ctx, documentId).Execute()

Delete a document



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
	documentId := "documentId_example" // string | Document ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DocumentsAPI.DocumentsDocumentIdDelete(context.Background(), documentId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DocumentsAPI.DocumentsDocumentIdDelete``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DocumentsDocumentIdDelete`: HelperResponse
	fmt.Fprintf(os.Stdout, "Response from `DocumentsAPI.DocumentsDocumentIdDelete`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**documentId** | **string** | Document ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiDocumentsDocumentIdDeleteRequest struct via the builder pattern


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


## DocumentsDocumentIdGet

> DocumentsDocumentIdGet200Response DocumentsDocumentIdGet(ctx, documentId).Execute()

Get a specific document



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
	documentId := "documentId_example" // string | Document ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DocumentsAPI.DocumentsDocumentIdGet(context.Background(), documentId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DocumentsAPI.DocumentsDocumentIdGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DocumentsDocumentIdGet`: DocumentsDocumentIdGet200Response
	fmt.Fprintf(os.Stdout, "Response from `DocumentsAPI.DocumentsDocumentIdGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**documentId** | **string** | Document ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiDocumentsDocumentIdGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**DocumentsDocumentIdGet200Response**](DocumentsDocumentIdGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DocumentsDocumentIdHuffmanGet

> CollectionsCollectionIdStatisticsGet200Response DocumentsDocumentIdHuffmanGet(ctx, documentId).Execute()

Get Huffman encoded and decoded content of a document



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
	documentId := "documentId_example" // string | Document ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DocumentsAPI.DocumentsDocumentIdHuffmanGet(context.Background(), documentId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DocumentsAPI.DocumentsDocumentIdHuffmanGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DocumentsDocumentIdHuffmanGet`: CollectionsCollectionIdStatisticsGet200Response
	fmt.Fprintf(os.Stdout, "Response from `DocumentsAPI.DocumentsDocumentIdHuffmanGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**documentId** | **string** | Document ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiDocumentsDocumentIdHuffmanGetRequest struct via the builder pattern


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


## DocumentsDocumentIdStatisticsGet

> CollectionsCollectionIdStatisticsGet200Response DocumentsDocumentIdStatisticsGet(ctx, documentId).Execute()

Get document statistics



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
	documentId := "documentId_example" // string | Document ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DocumentsAPI.DocumentsDocumentIdStatisticsGet(context.Background(), documentId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DocumentsAPI.DocumentsDocumentIdStatisticsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DocumentsDocumentIdStatisticsGet`: CollectionsCollectionIdStatisticsGet200Response
	fmt.Fprintf(os.Stdout, "Response from `DocumentsAPI.DocumentsDocumentIdStatisticsGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**documentId** | **string** | Document ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiDocumentsDocumentIdStatisticsGetRequest struct via the builder pattern


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


## DocumentsGet

> DocumentsGet200Response DocumentsGet(ctx).Execute()

Get all user documents



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
	resp, r, err := apiClient.DocumentsAPI.DocumentsGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DocumentsAPI.DocumentsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DocumentsGet`: DocumentsGet200Response
	fmt.Fprintf(os.Stdout, "Response from `DocumentsAPI.DocumentsGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiDocumentsGetRequest struct via the builder pattern


### Return type

[**DocumentsGet200Response**](DocumentsGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

