# AUDataCenter

extends ***[DataCenter](DataCenter.md#datacenter)***

This class represents the properties of Zoho CRM in AU Domain.

## Package com.zoho.crm.api.dc

## Static Final Fields

| Return Type                             | Field      | Description                                                                                        |
| :-------------------------------------- | :--------- | :------------------------------------------------------------------------------------------------- |
| [Environment](DataCenter.md#environment)| PRODUCTION | This ***Environment class*** instance represents the Zoho CRM Production Environment in AU Domain. |
| [Environment](DataCenter.md#environment)| SANDBOX    | This ***Environment class*** instance represents the Zoho CRM Sandbox Environment in AU Domain.    |
| [Environment](DataCenter.md#environment)| DEVELOPER  | This ***Environment class*** instance represents the Zoho CRM Developer Environment in AU Domain.  |
----

## Methods

| Return Type      | Method             | Description                               |
| :--------------- | :----------------- | :---------------------------------------- |
| ***String***     | getIAMUrl()        | The method to get the accounts ***URL***. Use this ***URL*** when calling ***OAuth*** accounts. |
| ***String***     | getFileUploadUrl() | The method to get the ***File Upload URL***. |
----

[source](../../src/main/java/com/zoho/crm/api/dc/AUDataCenter.java)
