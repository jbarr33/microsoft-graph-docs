# timeSlot resource type

A time period.

## JSON representation

Here is a JSON representation of the resource

<!-- {
  "blockType": "resource",
  "optionalProperties": [

  ],
  "@odata.type": "microsoft.graph.timeSlot"
}-->

```json
{
  "end": {"@odata.type": "microsoft.graph.timeStamp"},
  "start": {"@odata.type": "microsoft.graph.timeStamp"}
}

```
## Properties
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|end|[timeStamp](timestamp.md)|The time a period begins.|
|start|[timeStamp](timestamp.md)|The time the period ends.|

<!-- uuid: 8fcb5dbc-d5aa-4681-8e31-b001d5168d79
2015-10-25 14:57:30 UTC -->
<!-- {
  "type": "#page.annotation",
  "description": "timeSlot resource",
  "keywords": "",
  "section": "documentation",
  "tocPath": ""
}-->