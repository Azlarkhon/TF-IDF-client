# DocumentsDocumentIdGet200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**DtoDocumentResponse**](DtoDocumentResponse.md) |  | [optional] 
**Error** | Pointer to **string** |  | [optional] 
**IsSuccess** | Pointer to **bool** |  | [optional] 

## Methods

### NewDocumentsDocumentIdGet200Response

`func NewDocumentsDocumentIdGet200Response() *DocumentsDocumentIdGet200Response`

NewDocumentsDocumentIdGet200Response instantiates a new DocumentsDocumentIdGet200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDocumentsDocumentIdGet200ResponseWithDefaults

`func NewDocumentsDocumentIdGet200ResponseWithDefaults() *DocumentsDocumentIdGet200Response`

NewDocumentsDocumentIdGet200ResponseWithDefaults instantiates a new DocumentsDocumentIdGet200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *DocumentsDocumentIdGet200Response) GetData() DtoDocumentResponse`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *DocumentsDocumentIdGet200Response) GetDataOk() (*DtoDocumentResponse, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *DocumentsDocumentIdGet200Response) SetData(v DtoDocumentResponse)`

SetData sets Data field to given value.

### HasData

`func (o *DocumentsDocumentIdGet200Response) HasData() bool`

HasData returns a boolean if a field has been set.

### GetError

`func (o *DocumentsDocumentIdGet200Response) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *DocumentsDocumentIdGet200Response) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *DocumentsDocumentIdGet200Response) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *DocumentsDocumentIdGet200Response) HasError() bool`

HasError returns a boolean if a field has been set.

### GetIsSuccess

`func (o *DocumentsDocumentIdGet200Response) GetIsSuccess() bool`

GetIsSuccess returns the IsSuccess field if non-nil, zero value otherwise.

### GetIsSuccessOk

`func (o *DocumentsDocumentIdGet200Response) GetIsSuccessOk() (*bool, bool)`

GetIsSuccessOk returns a tuple with the IsSuccess field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsSuccess

`func (o *DocumentsDocumentIdGet200Response) SetIsSuccess(v bool)`

SetIsSuccess sets IsSuccess field to given value.

### HasIsSuccess

`func (o *DocumentsDocumentIdGet200Response) HasIsSuccess() bool`

HasIsSuccess returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


