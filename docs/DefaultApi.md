# \DefaultApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AsyncFunctionFunctionNamePost**](DefaultApi.md#AsyncFunctionFunctionNamePost) | **Post** /async-function/{functionName} | Invoke a function asynchronously in OpenFaaS
[**FunctionFunctionNamePost**](DefaultApi.md#FunctionFunctionNamePost) | **Post** /function/{functionName} | Invoke a function defined in OpenFaaS
[**SystemAlertPost**](DefaultApi.md#SystemAlertPost) | **Post** /system/alert | Event-sink for AlertManager, for auto-scaling
[**SystemFunctionsDelete**](DefaultApi.md#SystemFunctionsDelete) | **Delete** /system/functions | Remove a deployed function.
[**SystemFunctionsGet**](DefaultApi.md#SystemFunctionsGet) | **Get** /system/functions | Get a list of deployed functions with: stats and image digest
[**SystemFunctionsPost**](DefaultApi.md#SystemFunctionsPost) | **Post** /system/functions | Deploy a new function.
[**SystemFunctionsPut**](DefaultApi.md#SystemFunctionsPut) | **Put** /system/functions | Update a function.


# **AsyncFunctionFunctionNamePost**
> AsyncFunctionFunctionNamePost($functionName, $input)

Invoke a function asynchronously in OpenFaaS

### This endpoint requires the asynchronous stack. See https://github.com/openfaas/faas/blob/master/guide/asynchronous.md.


### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **functionName** | **string**| Function name | 
 **input** | **string**| (Optional) data to pass to function | [optional] 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **FunctionFunctionNamePost**
> FunctionFunctionNamePost($functionName, $input)

Invoke a function defined in OpenFaaS


### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **functionName** | **string**| Function name | 
 **input** | **string**| (Optional) data to pass to function | [optional] 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **SystemAlertPost**
> SystemAlertPost($body)

Event-sink for AlertManager, for auto-scaling

Internal use for AlertManager, requires valid AlertManager alert JSON


### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**interface{}**](interface{}.md)| Function to delete | [optional] 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **SystemFunctionsDelete**
> SystemFunctionsDelete($body)

Remove a deployed function.




### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**DeleteFunctionRequest**](DeleteFunctionRequest.md)| Function to delete | 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **SystemFunctionsGet**
> SystemFunctionsGet()

Get a list of deployed functions with: stats and image digest




### Parameters
This endpoint does not need any parameter.

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **SystemFunctionsPost**
> SystemFunctionsPost($body)

Deploy a new function.




### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**CreateFunctionRequest**](CreateFunctionRequest.md)| Function to deploy | 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **SystemFunctionsPut**
> SystemFunctionsPut($body)

Update a function.




### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**CreateFunctionRequest**](CreateFunctionRequest.md)| Function to update | 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

