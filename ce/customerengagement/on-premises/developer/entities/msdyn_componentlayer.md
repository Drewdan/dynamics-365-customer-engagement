---
title: "msdyn_componentlayer Entity Reference (Dynamics 365 Customer Engagement)| MicrosoftDocs"
description: "Includes schema information and supported messages for the msdyn_componentlayer entity."
ms.date: 04/02/2019
ms.prod: d365ce-op
ms.topic: "reference"
ms.assetid: 3948cc48-07c8-7f60-0608-71c37158ad7c
author: "KumarVivek"
ms.author: "kvivek"
manager: "annbe"
search.audienceType: 
  - developer

---
# msdyn_componentlayer Entity Reference



**Added by**: Microsoft Dynamics 365 Component History APIs Solution


## Messages

|Message|Web API Operation|SDK Assembly|
|-|-|-|
|Create|POST [*org URI*]/api/data/v9.0/msdyn_componentlayers<br />See [Create](/powerapps/developer/common-data-service/webapi/create-entity-web-api)|<xref:Microsoft.Xrm.Sdk.Messages.CreateRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Create*>|
|Delete|DELETE [*org URI*]/api/data/v9.0/msdyn_componentlayers(*msdyn_componentlayerid*)<br />See [Delete](/powerapps/developer/common-data-service/webapi/update-delete-entities-using-web-api#basic-delete)|<xref:Microsoft.Xrm.Sdk.Messages.DeleteRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Delete*>|
|Retrieve|GET [*org URI*]/api/data/v9.0/msdyn_componentlayers(*msdyn_componentlayerid*)<br />See [Retrieve](/powerapps/developer/common-data-service/webapi/retrieve-entity-using-web-api)|<xref:Microsoft.Xrm.Sdk.Messages.RetrieveRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Retrieve*>|
|RetrieveMultiple|GET [*org URI*]/api/data/v9.0/msdyn_componentlayers<br />See [Query Data](/powerapps/developer/common-data-service/webapi/query-data-web-api)|<xref:Microsoft.Xrm.Sdk.Messages.RetrieveMultipleRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.RetrieveMultiple*>|
|Update|PATCH [*org URI*]/api/data/v9.0/msdyn_componentlayers(*msdyn_componentlayerid*)<br />See [Update](/powerapps/developer/common-data-service/webapi/update-delete-entities-using-web-api#basic-update)|<xref:Microsoft.Xrm.Sdk.Messages.UpdateRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Update*>|

## Entity Properties

|Property|Value|
|--------|-----|
|CollectionSchemaName|msdyn_componentlayers|
|DisplayCollectionName|Component Layers|
|DisplayName|Component Layer|
|EntitySetName|msdyn_componentlayers|
|IsBPFEntity|False|
|LogicalCollectionName|msdyn_componentlayers|
|LogicalName|msdyn_componentlayer|
|OwnershipType|OrganizationOwned|
|PrimaryIdAttribute|msdyn_componentlayerid|
|PrimaryNameAttribute|msdyn_name|
|SchemaName|msdyn_componentlayer|

<a name="writable-attributes"></a>

## Writable attributes

These attributes return true for either **IsValidForCreate** or **IsValidForUpdate** (usually both). Listed by **SchemaName**.

- [msdyn_changes](#BKMK_msdyn_changes)
- [msdyn_componentid](#BKMK_msdyn_componentid)
- [msdyn_componentjson](#BKMK_msdyn_componentjson)
- [msdyn_componentlayerId](#BKMK_msdyn_componentlayerId)
- [msdyn_endtime](#BKMK_msdyn_endtime)
- [msdyn_name](#BKMK_msdyn_name)
- [msdyn_order](#BKMK_msdyn_order)
- [msdyn_publishername](#BKMK_msdyn_publishername)
- [msdyn_solutioncomponentname](#BKMK_msdyn_solutioncomponentname)
- [msdyn_solutionname](#BKMK_msdyn_solutionname)


### <a name="BKMK_msdyn_changes"></a> msdyn_changes

|Property|Value|
|--------|-----|
|Description||
|DisplayName|Changes|
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_changes|
|MaxLength|1073741823|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_msdyn_componentid"></a> msdyn_componentid

|Property|Value|
|--------|-----|
|Description||
|DisplayName|Component Id|
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_componentid|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_msdyn_componentjson"></a> msdyn_componentjson

|Property|Value|
|--------|-----|
|Description||
|DisplayName|Component Json|
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_componentjson|
|MaxLength|1073741823|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_msdyn_componentlayerId"></a> msdyn_componentlayerId

|Property|Value|
|--------|-----|
|Description|Unique identifier for entity instances|
|DisplayName|Component Layer|
|IsValidForForm|False|
|IsValidForRead|True|
|IsValidForUpdate|False|
|LogicalName|msdyn_componentlayerid|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|


### <a name="BKMK_msdyn_endtime"></a> msdyn_endtime

|Property|Value|
|--------|-----|
|DateTimeBehavior|UserLocal|
|Description||
|DisplayName|Overwrite Time|
|Format|DateAndTime|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_overwritetime|
|RequiredLevel|None|
|Type|DateTime|


### <a name="BKMK_msdyn_name"></a> msdyn_name

|Property|Value|
|--------|-----|
|Description|The name of the component.|
|DisplayName|Name|
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_name|
|MaxLength|100|
|RequiredLevel|ApplicationRequired|
|Type|String|


### <a name="BKMK_msdyn_order"></a> msdyn_order

|Property|Value|
|--------|-----|
|Description||
|DisplayName|Order|
|Format|None|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_order|
|MaxValue|500|
|MinValue|0|
|RequiredLevel|None|
|Type|Integer|


### <a name="BKMK_msdyn_publishername"></a> msdyn_publishername

|Property|Value|
|--------|-----|
|Description||
|DisplayName|Publisher Name|
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_publishername|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_msdyn_solutioncomponentname"></a> msdyn_solutioncomponentname

|Property|Value|
|--------|-----|
|Description||
|DisplayName|Solution Component Name|
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_solutioncomponentname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_msdyn_solutionname"></a> msdyn_solutionname

|Property|Value|
|--------|-----|
|Description||
|DisplayName|Solution Name|
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_solutionname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|



### See also

[About the Entity Reference](../about-entity-reference.md)<br />
[Programming reference for Dynamics 365 Customer Engagement](../programming-reference.md)<br />
[Web API Reference](/dynamics365/customer-engagement/web-api/about)<br />
<xref href="Microsoft.Dynamics.CRM.msdyn_componentlayer?text=msdyn_componentlayer EntityType" />

[!INCLUDE[footer-include](../../../../includes/footer-banner.md)]