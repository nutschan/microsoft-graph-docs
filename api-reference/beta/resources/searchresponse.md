---
title: "searchResponse resource type"
description: "PROVIDE DESCRIPTION HERE"
localization_priority: Normal
author: "nmoreau"
ms.prod: "search"
doc_type: "resourcePageType"
---

# searchResponse resource type

The searchResponse contains the results from the search query.

## Properties

| Property     | Type        | Description |
|:-------------|:------------|:------------|
|hitsContainers|[searchHitsContainer](searchhitscontainer.md) collection|Contains a collection of hits container which encapsulate the actual results |
|searchTerms|String collection|Contains the search terms sent in the initial search query|

## JSON representation

The following is a JSON representation of the resource.

<!-- {
  "blockType": "resource",
  "optionalProperties": [

  ],
  "@odata.type": "microsoft.graph.searchResponse",
  "baseType": null
}-->

```json
{
  "hitsContainers": [{"@odata.type": "microsoft.graph.searchHitsContainer"}],
  "searchTerms": ["String"]
}
```

<!-- uuid: 16cd6b66-4b1a-43a1-adaf-3a886856ed98
2019-02-04 14:57:30 UTC -->
<!-- {
  "type": "#page.annotation",
  "description": "searchResponse resource",
  "keywords": "",
  "section": "documentation",
  "tocPath": ""
}-->