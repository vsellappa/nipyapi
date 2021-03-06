# Tenant

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**identifier** | **str** | The computer-generated identifier of the tenant. | [optional] 
**identity** | **str** | The human-facing identity of the tenant. This can only be changed if the tenant is configurable. | [optional] 
**configurable** | **bool** | Indicates if this tenant is configurable, based on which UserGroupProvider has been configured to manage it. | [optional] 
**resource_permissions** | [**ResourcePermissions**](ResourcePermissions.md) | A summary top-level resource access policies granted to this tenant. | [optional] 
**access_policies** | [**list[AccessPolicySummary]**](AccessPolicySummary.md) | The access policies granted to this tenant. | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


