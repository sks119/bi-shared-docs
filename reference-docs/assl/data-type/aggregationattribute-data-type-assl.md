---
title: "AggregationAttribute Data Type (ASSL) | Microsoft Docs"
ms.date: 07/25/2018
ms.prod: sql
ms.technology: analysis-services
ms.custom: assl
ms.topic: reference
ms.author: owend
ms.reviewer: owend
author: minewiskan
manager: kfile
---
# AggregationAttribute Data Type (ASSL)

  Defines a primitive data type that represents the association between an [Aggregation](../objects/aggregation-element-assl.md) element and an attribute.  
  
## Syntax  
  
```xml  
  
<AggregationAttribute>  
   <AttributeID>...</AttributeID>  
      <Annotations>...</Annotations>  
</AggregationAttribute>  
```  
  
## Data Type Characteristics  
  
|Characteristic|Description|  
|--------------------|-----------------|  
|Base data types|None|  
|Derived data types|None|  
  
## Data Type Relationships  
  
|Relationship|Element|  
|------------------|-------------|  
|Parent elements|None|  
|Child elements|[AttributeID](../properties/attributeid-element-assl.md), [Annotations](../collections/annotations-element-assl.md)|  
|Derived elements|[Attribute](../objects/attribute-element-assl.md) ([Attributes](../collections/attributes-element-assl.md) collection of [AggregationDimension](aggregationdimension-data-type-assl.md))|  
  
## Remarks  
 The corresponding class in the Analysis Management Objects (AMO) object model is <xref:Microsoft.AnalysisServices.AggregationAttribute>.  
