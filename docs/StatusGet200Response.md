# StatusGet200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**StatusGet200ResponseAllOfData**](StatusGet200ResponseAllOfData.md) |  | [optional] 
**Error** | Pointer to **string** |  | [optional] 
**IsSuccess** | Pointer to **bool** |  | [optional] 

## Methods

### NewStatusGet200Response

`func NewStatusGet200Response() *StatusGet200Response`

NewStatusGet200Response instantiates a new StatusGet200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStatusGet200ResponseWithDefaults

`func NewStatusGet200ResponseWithDefaults() *StatusGet200Response`

NewStatusGet200ResponseWithDefaults instantiates a new StatusGet200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *StatusGet200Response) GetData() StatusGet200ResponseAllOfData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *StatusGet200Response) GetDataOk() (*StatusGet200ResponseAllOfData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *StatusGet200Response) SetData(v StatusGet200ResponseAllOfData)`

SetData sets Data field to given value.

### HasData

`func (o *StatusGet200Response) HasData() bool`

HasData returns a boolean if a field has been set.

### GetError

`func (o *StatusGet200Response) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *StatusGet200Response) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *StatusGet200Response) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *StatusGet200Response) HasError() bool`

HasError returns a boolean if a field has been set.

### GetIsSuccess

`func (o *StatusGet200Response) GetIsSuccess() bool`

GetIsSuccess returns the IsSuccess field if non-nil, zero value otherwise.

### GetIsSuccessOk

`func (o *StatusGet200Response) GetIsSuccessOk() (*bool, bool)`

GetIsSuccessOk returns a tuple with the IsSuccess field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsSuccess

`func (o *StatusGet200Response) SetIsSuccess(v bool)`

SetIsSuccess sets IsSuccess field to given value.

### HasIsSuccess

`func (o *StatusGet200Response) HasIsSuccess() bool`

HasIsSuccess returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


