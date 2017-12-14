# CreateFunctionRequest

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Service** | **string** | Name of deployed function | [optional] [default to null]
**Network** | **string** | Docker swarm network, usually func_functions | [optional] [default to null]
**Image** | **string** | Docker image in accessible registry | [optional] [default to null]
**EnvProcess** | **string** | Process for watchdog to fork | [optional] [default to null]
**EnvVars** | **[]string** | Overrides to environmental variables | [optional] [default to null]
**RegistryAuth** | **string** | Private registry base64-encoded basic auth (as present in ~/.docker/config.json) | [optional] [default to null]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


