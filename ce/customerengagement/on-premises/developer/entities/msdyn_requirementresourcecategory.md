---
title: "msdyn_requirementresourcecategory Entity Reference (Dynamics 365 Customer Engagement)| MicrosoftDocs"
description: "Includes schema information and supported messages for the msdyn_requirementresourcecategory entity."
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
# msdyn_requirementresourcecategory Entity Reference

Requirement Resource Category

**Added by**: Universal Resource Scheduling Solution


## Messages

|Message|Web API Operation|SDK Assembly|
|-|-|-|
|Assign|PATCH [*org URI*]/api/data/v9.0/msdyn_requirementresourcecategories(*msdyn_requirementresourcecategoryid*)<br />[Update](/powerapps/developer/common-data-service/webapi/update-delete-entities-using-web-api#basic-update) `ownerid` property.|<xref:Microsoft.Crm.Sdk.Messages.AssignRequest>|
|Create|POST [*org URI*]/api/data/v9.0/msdyn_requirementresourcecategories<br />See [Create](/powerapps/developer/common-data-service/webapi/create-entity-web-api)|<xref:Microsoft.Xrm.Sdk.Messages.CreateRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Create*>|
|Delete|DELETE [*org URI*]/api/data/v9.0/msdyn_requirementresourcecategories(*msdyn_requirementresourcecategoryid*)<br />See [Delete](/powerapps/developer/common-data-service/webapi/update-delete-entities-using-web-api#basic-delete)|<xref:Microsoft.Xrm.Sdk.Messages.DeleteRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Delete*>|
|GrantAccess|<xref href="Microsoft.Dynamics.CRM.GrantAccess?text=GrantAccess Action" />|<xref:Microsoft.Crm.Sdk.Messages.GrantAccessRequest>|
|IsValidStateTransition|<xref href="Microsoft.Dynamics.CRM.IsValidStateTransition?text=IsValidStateTransition Function" />|<xref:Microsoft.Crm.Sdk.Messages.IsValidStateTransitionRequest>|
|ModifyAccess|<xref href="Microsoft.Dynamics.CRM.ModifyAccess?text=ModifyAccess Action" />|<xref:Microsoft.Crm.Sdk.Messages.ModifyAccessRequest>|
|Retrieve|GET [*org URI*]/api/data/v9.0/msdyn_requirementresourcecategories(*msdyn_requirementresourcecategoryid*)<br />See [Retrieve](/powerapps/developer/common-data-service/webapi/retrieve-entity-using-web-api)|<xref:Microsoft.Xrm.Sdk.Messages.RetrieveRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Retrieve*>|
|RetrieveMultiple|GET [*org URI*]/api/data/v9.0/msdyn_requirementresourcecategories<br />See [Query Data](/powerapps/developer/common-data-service/webapi/query-data-web-api)|<xref:Microsoft.Xrm.Sdk.Messages.RetrieveMultipleRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.RetrieveMultiple*>|
|RetrievePrincipalAccess|<xref href="Microsoft.Dynamics.CRM.RetrievePrincipalAccess?text=RetrievePrincipalAccess Function" />|<xref:Microsoft.Crm.Sdk.Messages.RetrievePrincipalAccessRequest>|
|RetrieveSharedPrincipalsAndAccess|<xref href="Microsoft.Dynamics.CRM.RetrieveSharedPrincipalsAndAccess?text=RetrieveSharedPrincipalsAndAccess Function" />|<xref:Microsoft.Crm.Sdk.Messages.RetrieveSharedPrincipalsAndAccessRequest>|
|RevokeAccess|<xref href="Microsoft.Dynamics.CRM.RevokeAccess?text=RevokeAccess Action" />|<xref:Microsoft.Crm.Sdk.Messages.RevokeAccessRequest>|
|SetState|PATCH [*org URI*]/api/data/v9.0/msdyn_requirementresourcecategories(*msdyn_requirementresourcecategoryid*)<br />[Update](/powerapps/developer/common-data-service/webapi/update-delete-entities-using-web-api#basic-update) `statecode` and `statuscode` properties.|<xref:Microsoft.Crm.Sdk.Messages.SetStateRequest>|
|Update|PATCH [*org URI*]/api/data/v9.0/msdyn_requirementresourcecategories(*msdyn_requirementresourcecategoryid*)<br />See [Update](/powerapps/developer/common-data-service/webapi/update-delete-entities-using-web-api#basic-update)|<xref:Microsoft.Xrm.Sdk.Messages.UpdateRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Update*>|

## Entity Properties

|Property|Value|
|--------|-----|
|CollectionSchemaName|msdyn_requirementresourcecategories|
|DisplayCollectionName|Requirement Resource Category|
|DisplayName|Requirement Resource Category|
|EntitySetName|msdyn_requirementresourcecategories|
|IsBPFEntity|False|
|LogicalCollectionName|msdyn_requirementresourcecategories|
|LogicalName|msdyn_requirementresourcecategory|
|OwnershipType|UserOwned|
|PrimaryIdAttribute|msdyn_requirementresourcecategoryid|
|PrimaryNameAttribute|msdyn_name|
|SchemaName|msdyn_requirementresourcecategory|

<a name="writable-attributes"></a>

## Writable attributes

These attributes return true for either **IsValidForCreate** or **IsValidForUpdate** (usually both). Listed by **SchemaName**.

- [ImportSequenceNumber](#BKMK_ImportSequenceNumber)
- [msdyn_isprimary](#BKMK_msdyn_isprimary)
- [msdyn_name](#BKMK_msdyn_name)
- [msdyn_requirementresourcecategoryId](#BKMK_msdyn_requirementresourcecategoryId)
- [msdyn_ResourceCategory](#BKMK_msdyn_ResourceCategory)
- [msdyn_ResourceRequirement](#BKMK_msdyn_ResourceRequirement)
- [OverriddenCreatedOn](#BKMK_OverriddenCreatedOn)
- [OwnerId](#BKMK_OwnerId)
- [OwnerIdType](#BKMK_OwnerIdType)
- [statecode](#BKMK_statecode)
- [statuscode](#BKMK_statuscode)
- [TimeZoneRuleVersionNumber](#BKMK_TimeZoneRuleVersionNumber)
- [UTCConversionTimeZoneCode](#BKMK_UTCConversionTimeZoneCode)


### <a name="BKMK_ImportSequenceNumber"></a> ImportSequenceNumber

|Property|Value|
|--------|-----|
|Description|Sequence number of the import that created this record.|
|DisplayName|Import Sequence Number|
|Format|None|
|IsValidForForm|False|
|IsValidForRead|True|
|IsValidForUpdate|False|
|LogicalName|importsequencenumber|
|MaxValue|2147483647|
|MinValue|-2147483648|
|RequiredLevel|None|
|Type|Integer|


### <a name="BKMK_msdyn_isprimary"></a> msdyn_isprimary

**Added by**: Project Service Automation Solution

|Property|Value|
|--------|-----|
|Description|Yes if resource category requirement is primary. If it's primary then it can't be deleted|
|DisplayName|Is Primary|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_isprimary|
|RequiredLevel|None|
|Type|Boolean|

#### msdyn_isprimary Options

|Value|Label|
|-----|-----|
|1|Yes|
|0|No|

**DefaultValue**: False



### <a name="BKMK_msdyn_name"></a> msdyn_name

|Property|Value|
|--------|-----|
|Description|The name of the custom entity.|
|DisplayName|Name|
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_name|
|MaxLength|100|
|RequiredLevel|ApplicationRequired|
|Type|String|


### <a name="BKMK_msdyn_requirementresourcecategoryId"></a> msdyn_requirementresourcecategoryId

|Property|Value|
|--------|-----|
|Description|A unique identifier for an entity instance.|
|DisplayName|Requirement Resource Category|
|IsValidForForm|False|
|IsValidForRead|True|
|IsValidForUpdate|False|
|LogicalName|msdyn_requirementresourcecategoryid|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|


### <a name="BKMK_msdyn_ResourceCategory"></a> msdyn_ResourceCategory

|Property|Value|
|--------|-----|
|Description|Resource Category|
|DisplayName|Resource Category|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_resourcecategory|
|RequiredLevel|ApplicationRequired|
|Targets|bookableresourcecategory|
|Type|Lookup|


### <a name="BKMK_msdyn_ResourceRequirement"></a> msdyn_ResourceRequirement

|Property|Value|
|--------|-----|
|Description|Resource Requirement|
|DisplayName|Resource Requirement|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_resourcerequirement|
|RequiredLevel|ApplicationRequired|
|Targets|msdyn_resourcerequirement|
|Type|Lookup|


### <a name="BKMK_OverriddenCreatedOn"></a> OverriddenCreatedOn

|Property|Value|
|--------|-----|
|DateTimeBehavior|UserLocal|
|Description|Date and time that the record was migrated.|
|DisplayName|Record Created On|
|Format|DateOnly|
|IsValidForForm|False|
|IsValidForRead|True|
|IsValidForUpdate|False|
|LogicalName|overriddencreatedon|
|RequiredLevel|None|
|Type|DateTime|


### <a name="BKMK_OwnerId"></a> OwnerId

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Owner Id|
|DisplayName|Owner|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|ownerid|
|RequiredLevel|SystemRequired|
|Targets|systemuser,team|
|Type|Owner|


### <a name="BKMK_OwnerIdType"></a> OwnerIdType

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Owner Id Type|
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|owneridtype|
|RequiredLevel|SystemRequired|
|Type|EntityName|


### <a name="BKMK_statecode"></a> statecode

|Property|Value|
|--------|-----|
|Description|Status of the Requirement Resource Category|
|DisplayName|Status|
|IsValidForCreate|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|statecode|
|RequiredLevel|SystemRequired|
|Type|State|

#### statecode Options

|Value|Label|DefaultStatus|InvariantName|
|-----|-----|-------------|-------------|
|0|Active|1|Active|
|1|Inactive|2|Inactive|



### <a name="BKMK_statuscode"></a> statuscode

|Property|Value|
|--------|-----|
|Description|Reason for the status of the Requirement Resource Category|
|DisplayName|Status Reason|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|statuscode|
|RequiredLevel|None|
|Type|Status|

#### statuscode Options

|Value|Label|State|
|-----|-----|-----|
|1|Active|0|
|2|Inactive|1|



### <a name="BKMK_TimeZoneRuleVersionNumber"></a> TimeZoneRuleVersionNumber

|Property|Value|
|--------|-----|
|Description|For internal use only.|
|DisplayName|Time Zone Rule Version Number|
|Format|None|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|timezoneruleversionnumber|
|MaxValue|2147483647|
|MinValue|-1|
|RequiredLevel|None|
|Type|Integer|


### <a name="BKMK_UTCConversionTimeZoneCode"></a> UTCConversionTimeZoneCode

|Property|Value|
|--------|-----|
|Description|Time zone code that was in use when the record was created.|
|DisplayName|UTC Conversion Time Zone Code|
|Format|None|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|utcconversiontimezonecode|
|MaxValue|2147483647|
|MinValue|-1|
|RequiredLevel|None|
|Type|Integer|

<a name="read-only-attributes"></a>

## Read-only attributes

These attributes return false for both **IsValidForCreate** or **IsValidForUpdate**. Listed by **SchemaName**.

- [CreatedBy](#BKMK_CreatedBy)
- [CreatedByName](#BKMK_CreatedByName)
- [CreatedByYomiName](#BKMK_CreatedByYomiName)
- [CreatedOn](#BKMK_CreatedOn)
- [CreatedOnBehalfBy](#BKMK_CreatedOnBehalfBy)
- [CreatedOnBehalfByName](#BKMK_CreatedOnBehalfByName)
- [CreatedOnBehalfByYomiName](#BKMK_CreatedOnBehalfByYomiName)
- [ModifiedBy](#BKMK_ModifiedBy)
- [ModifiedByName](#BKMK_ModifiedByName)
- [ModifiedByYomiName](#BKMK_ModifiedByYomiName)
- [ModifiedOn](#BKMK_ModifiedOn)
- [ModifiedOnBehalfBy](#BKMK_ModifiedOnBehalfBy)
- [ModifiedOnBehalfByName](#BKMK_ModifiedOnBehalfByName)
- [ModifiedOnBehalfByYomiName](#BKMK_ModifiedOnBehalfByYomiName)
- [msdyn_ResourceCategoryName](#BKMK_msdyn_ResourceCategoryName)
- [msdyn_ResourceRequirementName](#BKMK_msdyn_ResourceRequirementName)
- [OwnerIdName](#BKMK_OwnerIdName)
- [OwnerIdYomiName](#BKMK_OwnerIdYomiName)
- [OwningBusinessUnit](#BKMK_OwningBusinessUnit)
- [OwningTeam](#BKMK_OwningTeam)
- [OwningUser](#BKMK_OwningUser)
- [VersionNumber](#BKMK_VersionNumber)


### <a name="BKMK_CreatedBy"></a> CreatedBy

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Unique identifier of the user who created the record.|
|DisplayName|Created By|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|createdby|
|RequiredLevel|None|
|Targets|systemuser|
|Type|Lookup|


### <a name="BKMK_CreatedByName"></a> CreatedByName

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|createdbyname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_CreatedByYomiName"></a> CreatedByYomiName

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|createdbyyominame|
|MaxLength|100|
|RequiredLevel|SystemRequired|
|Type|String|


### <a name="BKMK_CreatedOn"></a> CreatedOn

|Property|Value|
|--------|-----|
|DateTimeBehavior|UserLocal|
|Description|Date and time when the record was created.|
|DisplayName|Created On|
|Format|DateAndTime|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|createdon|
|RequiredLevel|None|
|Type|DateTime|


### <a name="BKMK_CreatedOnBehalfBy"></a> CreatedOnBehalfBy

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Unique identifier of the delegate user who created the record.|
|DisplayName|Created By (Delegate)|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|createdonbehalfby|
|RequiredLevel|None|
|Targets|systemuser|
|Type|Lookup|


### <a name="BKMK_CreatedOnBehalfByName"></a> CreatedOnBehalfByName

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|createdonbehalfbyname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_CreatedOnBehalfByYomiName"></a> CreatedOnBehalfByYomiName

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|createdonbehalfbyyominame|
|MaxLength|100|
|RequiredLevel|SystemRequired|
|Type|String|


### <a name="BKMK_ModifiedBy"></a> ModifiedBy

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Unique identifier of the user who modified the record.|
|DisplayName|Modified By|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|modifiedby|
|RequiredLevel|None|
|Targets|systemuser|
|Type|Lookup|


### <a name="BKMK_ModifiedByName"></a> ModifiedByName

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|modifiedbyname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_ModifiedByYomiName"></a> ModifiedByYomiName

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|modifiedbyyominame|
|MaxLength|100|
|RequiredLevel|SystemRequired|
|Type|String|


### <a name="BKMK_ModifiedOn"></a> ModifiedOn

|Property|Value|
|--------|-----|
|DateTimeBehavior|UserLocal|
|Description|Date and time when the record was modified.|
|DisplayName|Modified On|
|Format|DateAndTime|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|modifiedon|
|RequiredLevel|None|
|Type|DateTime|


### <a name="BKMK_ModifiedOnBehalfBy"></a> ModifiedOnBehalfBy

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Unique identifier of the delegate user who modified the record.|
|DisplayName|Modified By (Delegate)|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|modifiedonbehalfby|
|RequiredLevel|None|
|Targets|systemuser|
|Type|Lookup|


### <a name="BKMK_ModifiedOnBehalfByName"></a> ModifiedOnBehalfByName

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|modifiedonbehalfbyname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_ModifiedOnBehalfByYomiName"></a> ModifiedOnBehalfByYomiName

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|modifiedonbehalfbyyominame|
|MaxLength|100|
|RequiredLevel|SystemRequired|
|Type|String|


### <a name="BKMK_msdyn_ResourceCategoryName"></a> msdyn_ResourceCategoryName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|msdyn_resourcecategoryname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_msdyn_ResourceRequirementName"></a> msdyn_ResourceRequirementName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|msdyn_resourcerequirementname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_OwnerIdName"></a> OwnerIdName

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Name of the owner|
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|owneridname|
|MaxLength|100|
|RequiredLevel|SystemRequired|
|Type|String|


### <a name="BKMK_OwnerIdYomiName"></a> OwnerIdYomiName

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Yomi name of the owner|
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|owneridyominame|
|MaxLength|100|
|RequiredLevel|SystemRequired|
|Type|String|


### <a name="BKMK_OwningBusinessUnit"></a> OwningBusinessUnit

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Unique identifier for the business unit that owns the record|
|DisplayName|Owning Business Unit|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|owningbusinessunit|
|RequiredLevel|None|
|Targets|businessunit|
|Type|Lookup|


### <a name="BKMK_OwningTeam"></a> OwningTeam

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Unique identifier for the team that owns the record.|
|DisplayName|Owning Team|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|owningteam|
|RequiredLevel|None|
|Targets|team|
|Type|Lookup|


### <a name="BKMK_OwningUser"></a> OwningUser

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Unique identifier for the user that owns the record.|
|DisplayName|Owning User|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|owninguser|
|RequiredLevel|None|
|Targets|systemuser|
|Type|Lookup|


### <a name="BKMK_VersionNumber"></a> VersionNumber

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Version Number|
|DisplayName|Version Number|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|versionnumber|
|MaxValue|9223372036854775807|
|MinValue|-9223372036854775808|
|RequiredLevel|None|
|Type|BigInt|

<a name="onetomany"></a>

## One-To-Many Relationships

Listed by **SchemaName**.

- [msdyn_requirementresourcecategory_SyncErrors](#BKMK_msdyn_requirementresourcecategory_SyncErrors)
- [msdyn_requirementresourcecategory_DuplicateMatchingRecord](#BKMK_msdyn_requirementresourcecategory_DuplicateMatchingRecord)
- [msdyn_requirementresourcecategory_DuplicateBaseRecord](#BKMK_msdyn_requirementresourcecategory_DuplicateBaseRecord)
- [msdyn_requirementresourcecategory_AsyncOperations](#BKMK_msdyn_requirementresourcecategory_AsyncOperations)
- [msdyn_requirementresourcecategory_MailboxTrackingFolders](#BKMK_msdyn_requirementresourcecategory_MailboxTrackingFolders)
- [msdyn_requirementresourcecategory_ProcessSession](#BKMK_msdyn_requirementresourcecategory_ProcessSession)
- [msdyn_requirementresourcecategory_BulkDeleteFailures](#BKMK_msdyn_requirementresourcecategory_BulkDeleteFailures)
- [msdyn_requirementresourcecategory_PrincipalObjectAttributeAccesses](#BKMK_msdyn_requirementresourcecategory_PrincipalObjectAttributeAccesses)
- [msdyn_requirementresourcecategory_Annotations](#BKMK_msdyn_requirementresourcecategory_Annotations)


### <a name="BKMK_msdyn_requirementresourcecategory_SyncErrors"></a> msdyn_requirementresourcecategory_SyncErrors

**Added by**: System Solution Solution

Same as syncerror entity [msdyn_requirementresourcecategory_SyncErrors](syncerror.md#BKMK_msdyn_requirementresourcecategory_SyncErrors) Many-To-One relationship.

|Property|Value|
|--------|-----|
|ReferencingEntity|syncerror|
|ReferencingAttribute|regardingobjectid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|msdyn_requirementresourcecategory_SyncErrors|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: NoCascade<br />Delete: Cascade<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|


### <a name="BKMK_msdyn_requirementresourcecategory_DuplicateMatchingRecord"></a> msdyn_requirementresourcecategory_DuplicateMatchingRecord

**Added by**: System Solution Solution

Same as duplicaterecord entity [msdyn_requirementresourcecategory_DuplicateMatchingRecord](duplicaterecord.md#BKMK_msdyn_requirementresourcecategory_DuplicateMatchingRecord) Many-To-One relationship.

|Property|Value|
|--------|-----|
|ReferencingEntity|duplicaterecord|
|ReferencingAttribute|duplicaterecordid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|msdyn_requirementresourcecategory_DuplicateMatchingRecord|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: NoCascade<br />Delete: Cascade<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|


### <a name="BKMK_msdyn_requirementresourcecategory_DuplicateBaseRecord"></a> msdyn_requirementresourcecategory_DuplicateBaseRecord

**Added by**: System Solution Solution

Same as duplicaterecord entity [msdyn_requirementresourcecategory_DuplicateBaseRecord](duplicaterecord.md#BKMK_msdyn_requirementresourcecategory_DuplicateBaseRecord) Many-To-One relationship.

|Property|Value|
|--------|-----|
|ReferencingEntity|duplicaterecord|
|ReferencingAttribute|baserecordid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|msdyn_requirementresourcecategory_DuplicateBaseRecord|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: NoCascade<br />Delete: Cascade<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|


### <a name="BKMK_msdyn_requirementresourcecategory_AsyncOperations"></a> msdyn_requirementresourcecategory_AsyncOperations

**Added by**: System Solution Solution

Same as asyncoperation entity [msdyn_requirementresourcecategory_AsyncOperations](asyncoperation.md#BKMK_msdyn_requirementresourcecategory_AsyncOperations) Many-To-One relationship.

|Property|Value|
|--------|-----|
|ReferencingEntity|asyncoperation|
|ReferencingAttribute|regardingobjectid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|msdyn_requirementresourcecategory_AsyncOperations|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: NoCascade<br />Delete: NoCascade<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|


### <a name="BKMK_msdyn_requirementresourcecategory_MailboxTrackingFolders"></a> msdyn_requirementresourcecategory_MailboxTrackingFolders

**Added by**: System Solution Solution

Same as mailboxtrackingfolder entity [msdyn_requirementresourcecategory_MailboxTrackingFolders](mailboxtrackingfolder.md#BKMK_msdyn_requirementresourcecategory_MailboxTrackingFolders) Many-To-One relationship.

|Property|Value|
|--------|-----|
|ReferencingEntity|mailboxtrackingfolder|
|ReferencingAttribute|regardingobjectid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|msdyn_requirementresourcecategory_MailboxTrackingFolders|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: NoCascade<br />Delete: Cascade<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|


### <a name="BKMK_msdyn_requirementresourcecategory_ProcessSession"></a> msdyn_requirementresourcecategory_ProcessSession

**Added by**: System Solution Solution

Same as processsession entity [msdyn_requirementresourcecategory_ProcessSession](processsession.md#BKMK_msdyn_requirementresourcecategory_ProcessSession) Many-To-One relationship.

|Property|Value|
|--------|-----|
|ReferencingEntity|processsession|
|ReferencingAttribute|regardingobjectid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|msdyn_requirementresourcecategory_ProcessSession|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: NoCascade<br />Delete: NoCascade<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|


### <a name="BKMK_msdyn_requirementresourcecategory_BulkDeleteFailures"></a> msdyn_requirementresourcecategory_BulkDeleteFailures

**Added by**: System Solution Solution

Same as bulkdeletefailure entity [msdyn_requirementresourcecategory_BulkDeleteFailures](bulkdeletefailure.md#BKMK_msdyn_requirementresourcecategory_BulkDeleteFailures) Many-To-One relationship.

|Property|Value|
|--------|-----|
|ReferencingEntity|bulkdeletefailure|
|ReferencingAttribute|regardingobjectid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|msdyn_requirementresourcecategory_BulkDeleteFailures|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: NoCascade<br />Delete: Cascade<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|


### <a name="BKMK_msdyn_requirementresourcecategory_PrincipalObjectAttributeAccesses"></a> msdyn_requirementresourcecategory_PrincipalObjectAttributeAccesses

**Added by**: System Solution Solution

Same as principalobjectattributeaccess entity [msdyn_requirementresourcecategory_PrincipalObjectAttributeAccesses](principalobjectattributeaccess.md#BKMK_msdyn_requirementresourcecategory_PrincipalObjectAttributeAccesses) Many-To-One relationship.

|Property|Value|
|--------|-----|
|ReferencingEntity|principalobjectattributeaccess|
|ReferencingAttribute|objectid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|msdyn_requirementresourcecategory_PrincipalObjectAttributeAccesses|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: NoCascade<br />Delete: Cascade<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|


### <a name="BKMK_msdyn_requirementresourcecategory_Annotations"></a> msdyn_requirementresourcecategory_Annotations

**Added by**: System Solution Solution

Same as annotation entity [msdyn_requirementresourcecategory_Annotations](annotation.md#BKMK_msdyn_requirementresourcecategory_Annotations) Many-To-One relationship.

|Property|Value|
|--------|-----|
|ReferencingEntity|annotation|
|ReferencingAttribute|objectid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|msdyn_requirementresourcecategory_Annotations|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: Cascade<br />Delete: Cascade<br />Merge: NoCascade<br />Reparent: Cascade<br />Share: Cascade<br />Unshare: Cascade|

<a name="manytoone"></a>

## Many-To-One Relationships

Each Many-To-One relationship is defined by a corresponding One-To-Many relationship with the related entity. Listed by **SchemaName**.

- [lk_msdyn_requirementresourcecategory_createdby](#BKMK_lk_msdyn_requirementresourcecategory_createdby)
- [lk_msdyn_requirementresourcecategory_createdonbehalfby](#BKMK_lk_msdyn_requirementresourcecategory_createdonbehalfby)
- [lk_msdyn_requirementresourcecategory_modifiedby](#BKMK_lk_msdyn_requirementresourcecategory_modifiedby)
- [lk_msdyn_requirementresourcecategory_modifiedonbehalfby](#BKMK_lk_msdyn_requirementresourcecategory_modifiedonbehalfby)
- [user_msdyn_requirementresourcecategory](#BKMK_user_msdyn_requirementresourcecategory)
- [team_msdyn_requirementresourcecategory](#BKMK_team_msdyn_requirementresourcecategory)
- [business_unit_msdyn_requirementresourcecategory](#BKMK_business_unit_msdyn_requirementresourcecategory)
- [msdyn_bookableresourcecategory_requirementresourcecategory_ResourceCategory](#BKMK_msdyn_bookableresourcecategory_requirementresourcecategory_ResourceCategory)
- [msdyn_resourcerequirement_requirementresourcecategory_resourcerequirement](#BKMK_msdyn_resourcerequirement_requirementresourcecategory_resourcerequirement)


### <a name="BKMK_lk_msdyn_requirementresourcecategory_createdby"></a> lk_msdyn_requirementresourcecategory_createdby

**Added by**: System Solution Solution

See systemuser Entity [lk_msdyn_requirementresourcecategory_createdby](systemuser.md#BKMK_lk_msdyn_requirementresourcecategory_createdby) One-To-Many relationship.

### <a name="BKMK_lk_msdyn_requirementresourcecategory_createdonbehalfby"></a> lk_msdyn_requirementresourcecategory_createdonbehalfby

**Added by**: System Solution Solution

See systemuser Entity [lk_msdyn_requirementresourcecategory_createdonbehalfby](systemuser.md#BKMK_lk_msdyn_requirementresourcecategory_createdonbehalfby) One-To-Many relationship.

### <a name="BKMK_lk_msdyn_requirementresourcecategory_modifiedby"></a> lk_msdyn_requirementresourcecategory_modifiedby

**Added by**: System Solution Solution

See systemuser Entity [lk_msdyn_requirementresourcecategory_modifiedby](systemuser.md#BKMK_lk_msdyn_requirementresourcecategory_modifiedby) One-To-Many relationship.

### <a name="BKMK_lk_msdyn_requirementresourcecategory_modifiedonbehalfby"></a> lk_msdyn_requirementresourcecategory_modifiedonbehalfby

**Added by**: System Solution Solution

See systemuser Entity [lk_msdyn_requirementresourcecategory_modifiedonbehalfby](systemuser.md#BKMK_lk_msdyn_requirementresourcecategory_modifiedonbehalfby) One-To-Many relationship.

### <a name="BKMK_user_msdyn_requirementresourcecategory"></a> user_msdyn_requirementresourcecategory

**Added by**: System Solution Solution

See systemuser Entity [user_msdyn_requirementresourcecategory](systemuser.md#BKMK_user_msdyn_requirementresourcecategory) One-To-Many relationship.

### <a name="BKMK_team_msdyn_requirementresourcecategory"></a> team_msdyn_requirementresourcecategory

**Added by**: System Solution Solution

See team Entity [team_msdyn_requirementresourcecategory](team.md#BKMK_team_msdyn_requirementresourcecategory) One-To-Many relationship.

### <a name="BKMK_business_unit_msdyn_requirementresourcecategory"></a> business_unit_msdyn_requirementresourcecategory

**Added by**: System Solution Solution

See businessunit Entity [business_unit_msdyn_requirementresourcecategory](businessunit.md#BKMK_business_unit_msdyn_requirementresourcecategory) One-To-Many relationship.

### <a name="BKMK_msdyn_bookableresourcecategory_requirementresourcecategory_ResourceCategory"></a> msdyn_bookableresourcecategory_requirementresourcecategory_ResourceCategory

**Added by**: Scheduling Solution

See bookableresourcecategory Entity [msdyn_bookableresourcecategory_requirementresourcecategory_ResourceCategory](bookableresourcecategory.md#BKMK_msdyn_bookableresourcecategory_requirementresourcecategory_ResourceCategory) One-To-Many relationship.

### <a name="BKMK_msdyn_resourcerequirement_requirementresourcecategory_resourcerequirement"></a> msdyn_resourcerequirement_requirementresourcecategory_resourcerequirement

See msdyn_resourcerequirement Entity [msdyn_resourcerequirement_requirementresourcecategory_resourcerequirement](msdyn_resourcerequirement.md#BKMK_msdyn_resourcerequirement_requirementresourcecategory_resourcerequirement) One-To-Many relationship.

### See also

[About the Entity Reference](../about-entity-reference.md)<br />
[Programming reference for Dynamics 365 Customer Engagement](../programming-reference.md)<br />
[Web API Reference](/dynamics365/customer-engagement/web-api/about)<br />
<xref href="Microsoft.Dynamics.CRM.msdyn_requirementresourcecategory?text=msdyn_requirementresourcecategory EntityType" />

[!INCLUDE[footer-include](../../../../includes/footer-banner.md)]