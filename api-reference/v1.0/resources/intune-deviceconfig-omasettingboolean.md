---
title: "omaSettingBoolean resource type"
description: "OMA Settings Boolean definition."
author: "davidmu1"
localization_priority: Normal
ms.prod: "Intune"
doc_type: resourcePageType
---

# omaSettingBoolean resource type

> **Note:** The Microsoft Graph API for Intune requires an [active Intune license](https://go.microsoft.com/fwlink/?linkid=839381) for the tenant.

OMA Settings Boolean definition.


Inherits from [omaSetting](../resources/intune-deviceconfig-omasetting.md)

## Properties
|Property|Type|Description|
|:---|:---|:---|
|displayName|String|Display Name. Inherited from [omaSetting](../resources/intune-deviceconfig-omasetting.md)|
|description|String|Description. Inherited from [omaSetting](../resources/intune-deviceconfig-omasetting.md)|
|omaUri|String|OMA. Inherited from [omaSetting](../resources/intune-deviceconfig-omasetting.md)|
|value|Boolean|Value.|

## Relationships
None

## JSON Representation
Here is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.omaSettingBoolean"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.omaSettingBoolean",
  "displayName": "String",
  "description": "String",
  "omaUri": "String",
  "value": true
}
```




