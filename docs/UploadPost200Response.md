# UploadPost200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**[]ServicesWordStat**](ServicesWordStat.md) |  | [optional] 
**Error** | Pointer to **string** |  | [optional] 
**IsSuccess** | Pointer to **bool** |  | [optional] 

## Methods

### NewUploadPost200Response

`func NewUploadPost200Response() *UploadPost200Response`

NewUploadPost200Response instantiates a new UploadPost200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUploadPost200ResponseWithDefaults

`func NewUploadPost200ResponseWithDefaults() *UploadPost200Response`

NewUploadPost200ResponseWithDefaults instantiates a new UploadPost200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *UploadPost200Response) GetData() []ServicesWordStat`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *UploadPost200Response) GetDataOk() (*[]ServicesWordStat, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *UploadPost200Response) SetData(v []ServicesWordStat)`

SetData sets Data field to given value.

### HasData

`func (o *UploadPost200Response) HasData() bool`

HasData returns a boolean if a field has been set.

### GetError

`func (o *UploadPost200Response) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *UploadPost200Response) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *UploadPost200Response) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *UploadPost200Response) HasError() bool`

HasError returns a boolean if a field has been set.

### GetIsSuccess

`func (o *UploadPost200Response) GetIsSuccess() bool`

GetIsSuccess returns the IsSuccess field if non-nil, zero value otherwise.

### GetIsSuccessOk

`func (o *UploadPost200Response) GetIsSuccessOk() (*bool, bool)`

GetIsSuccessOk returns a tuple with the IsSuccess field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsSuccess

`func (o *UploadPost200Response) SetIsSuccess(v bool)`

SetIsSuccess sets IsSuccess field to given value.

### HasIsSuccess

`func (o *UploadPost200Response) HasIsSuccess() bool`

HasIsSuccess returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


