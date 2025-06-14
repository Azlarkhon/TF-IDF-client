# ModelsMetric

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AvgFileSizeMb** | Pointer to **float32** |  | [optional] 
**AvgTimeProcessed** | Pointer to **float32** |  | [optional] 
**FilesProcessed** | Pointer to **int32** |  | [optional] 
**Id** | Pointer to **int32** |  | [optional] 
**LatestFileProcessedTimestamp** | Pointer to **string** |  | [optional] 
**MaxTimeProcessed** | Pointer to **float32** |  | [optional] 
**MinTimeProcessed** | Pointer to **float32** |  | [optional] 
**Top10MostFreqWords** | Pointer to [**[]ModelsWord**](ModelsWord.md) |  | [optional] 
**TotalFileSizeMb** | Pointer to **float32** |  | [optional] 

## Methods

### NewModelsMetric

`func NewModelsMetric() *ModelsMetric`

NewModelsMetric instantiates a new ModelsMetric object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewModelsMetricWithDefaults

`func NewModelsMetricWithDefaults() *ModelsMetric`

NewModelsMetricWithDefaults instantiates a new ModelsMetric object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAvgFileSizeMb

`func (o *ModelsMetric) GetAvgFileSizeMb() float32`

GetAvgFileSizeMb returns the AvgFileSizeMb field if non-nil, zero value otherwise.

### GetAvgFileSizeMbOk

`func (o *ModelsMetric) GetAvgFileSizeMbOk() (*float32, bool)`

GetAvgFileSizeMbOk returns a tuple with the AvgFileSizeMb field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvgFileSizeMb

`func (o *ModelsMetric) SetAvgFileSizeMb(v float32)`

SetAvgFileSizeMb sets AvgFileSizeMb field to given value.

### HasAvgFileSizeMb

`func (o *ModelsMetric) HasAvgFileSizeMb() bool`

HasAvgFileSizeMb returns a boolean if a field has been set.

### GetAvgTimeProcessed

`func (o *ModelsMetric) GetAvgTimeProcessed() float32`

GetAvgTimeProcessed returns the AvgTimeProcessed field if non-nil, zero value otherwise.

### GetAvgTimeProcessedOk

`func (o *ModelsMetric) GetAvgTimeProcessedOk() (*float32, bool)`

GetAvgTimeProcessedOk returns a tuple with the AvgTimeProcessed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvgTimeProcessed

`func (o *ModelsMetric) SetAvgTimeProcessed(v float32)`

SetAvgTimeProcessed sets AvgTimeProcessed field to given value.

### HasAvgTimeProcessed

`func (o *ModelsMetric) HasAvgTimeProcessed() bool`

HasAvgTimeProcessed returns a boolean if a field has been set.

### GetFilesProcessed

`func (o *ModelsMetric) GetFilesProcessed() int32`

GetFilesProcessed returns the FilesProcessed field if non-nil, zero value otherwise.

### GetFilesProcessedOk

`func (o *ModelsMetric) GetFilesProcessedOk() (*int32, bool)`

GetFilesProcessedOk returns a tuple with the FilesProcessed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilesProcessed

`func (o *ModelsMetric) SetFilesProcessed(v int32)`

SetFilesProcessed sets FilesProcessed field to given value.

### HasFilesProcessed

`func (o *ModelsMetric) HasFilesProcessed() bool`

HasFilesProcessed returns a boolean if a field has been set.

### GetId

`func (o *ModelsMetric) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ModelsMetric) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ModelsMetric) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *ModelsMetric) HasId() bool`

HasId returns a boolean if a field has been set.

### GetLatestFileProcessedTimestamp

`func (o *ModelsMetric) GetLatestFileProcessedTimestamp() string`

GetLatestFileProcessedTimestamp returns the LatestFileProcessedTimestamp field if non-nil, zero value otherwise.

### GetLatestFileProcessedTimestampOk

`func (o *ModelsMetric) GetLatestFileProcessedTimestampOk() (*string, bool)`

GetLatestFileProcessedTimestampOk returns a tuple with the LatestFileProcessedTimestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLatestFileProcessedTimestamp

`func (o *ModelsMetric) SetLatestFileProcessedTimestamp(v string)`

SetLatestFileProcessedTimestamp sets LatestFileProcessedTimestamp field to given value.

### HasLatestFileProcessedTimestamp

`func (o *ModelsMetric) HasLatestFileProcessedTimestamp() bool`

HasLatestFileProcessedTimestamp returns a boolean if a field has been set.

### GetMaxTimeProcessed

`func (o *ModelsMetric) GetMaxTimeProcessed() float32`

GetMaxTimeProcessed returns the MaxTimeProcessed field if non-nil, zero value otherwise.

### GetMaxTimeProcessedOk

`func (o *ModelsMetric) GetMaxTimeProcessedOk() (*float32, bool)`

GetMaxTimeProcessedOk returns a tuple with the MaxTimeProcessed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxTimeProcessed

`func (o *ModelsMetric) SetMaxTimeProcessed(v float32)`

SetMaxTimeProcessed sets MaxTimeProcessed field to given value.

### HasMaxTimeProcessed

`func (o *ModelsMetric) HasMaxTimeProcessed() bool`

HasMaxTimeProcessed returns a boolean if a field has been set.

### GetMinTimeProcessed

`func (o *ModelsMetric) GetMinTimeProcessed() float32`

GetMinTimeProcessed returns the MinTimeProcessed field if non-nil, zero value otherwise.

### GetMinTimeProcessedOk

`func (o *ModelsMetric) GetMinTimeProcessedOk() (*float32, bool)`

GetMinTimeProcessedOk returns a tuple with the MinTimeProcessed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinTimeProcessed

`func (o *ModelsMetric) SetMinTimeProcessed(v float32)`

SetMinTimeProcessed sets MinTimeProcessed field to given value.

### HasMinTimeProcessed

`func (o *ModelsMetric) HasMinTimeProcessed() bool`

HasMinTimeProcessed returns a boolean if a field has been set.

### GetTop10MostFreqWords

`func (o *ModelsMetric) GetTop10MostFreqWords() []ModelsWord`

GetTop10MostFreqWords returns the Top10MostFreqWords field if non-nil, zero value otherwise.

### GetTop10MostFreqWordsOk

`func (o *ModelsMetric) GetTop10MostFreqWordsOk() (*[]ModelsWord, bool)`

GetTop10MostFreqWordsOk returns a tuple with the Top10MostFreqWords field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTop10MostFreqWords

`func (o *ModelsMetric) SetTop10MostFreqWords(v []ModelsWord)`

SetTop10MostFreqWords sets Top10MostFreqWords field to given value.

### HasTop10MostFreqWords

`func (o *ModelsMetric) HasTop10MostFreqWords() bool`

HasTop10MostFreqWords returns a boolean if a field has been set.

### GetTotalFileSizeMb

`func (o *ModelsMetric) GetTotalFileSizeMb() float32`

GetTotalFileSizeMb returns the TotalFileSizeMb field if non-nil, zero value otherwise.

### GetTotalFileSizeMbOk

`func (o *ModelsMetric) GetTotalFileSizeMbOk() (*float32, bool)`

GetTotalFileSizeMbOk returns a tuple with the TotalFileSizeMb field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalFileSizeMb

`func (o *ModelsMetric) SetTotalFileSizeMb(v float32)`

SetTotalFileSizeMb sets TotalFileSizeMb field to given value.

### HasTotalFileSizeMb

`func (o *ModelsMetric) HasTotalFileSizeMb() bool`

HasTotalFileSizeMb returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


