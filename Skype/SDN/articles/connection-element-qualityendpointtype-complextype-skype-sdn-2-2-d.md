﻿---
title: Connection element (QualityEndPointType complexType) 
TOCTitle: Connection element
ms:assetid: b0cfd3c9-4455-1e36-5296-cc9c439ec7ca
ms:mtpsurl: https://msdn.microsoft.com/library/Mt149450(v=office.16)
ms:contentKeyID: 65855397
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# Connection element 

(QualityEndPointType complexType) (Skype for Business SDN Interface 2.2, Schema "D")

Connection type such as "wired" or "wireless".

## Element information

<table>

<tbody>
<tr class="odd">
<td><p><strong>Element type</strong></p></td>
<td><p><a href="connectionplatforms-simpletype-skype-for-business-sdn-interface-2-2-schema-d.md">ConnectionPlatforms</a></p></td>
</tr>
<tr class="even">
<td><p><strong>Namespace</strong></p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p><strong>Schema file</strong></p></td>
<td><p>SDNInterface.Schema.D.XSD</p></td>
</tr>
</tbody>
</table>


## Definition

```xml

    <xs:element name="Connection"  type="ConnectionPlatforms" minOccurs="0">
    
    </xs:element>
  
```

## Elements and attributes

### Parent elements

<table>

<thead>
<tr class="header">
<th><p>Element</p></th>
<th><p>Type</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><a href="from-element-qualitytype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">From</a></p></td>
<td><p><a href="qualityendpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">QualityEndPointType</a></p></td>
<td><p>The source of the reported media stream.</p></td>
</tr>
<tr class="even">
<td><p><a href="to-element-qualitytype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">To</a></p></td>
<td><p><a href="qualityendpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">QualityEndPointType</a></p></td>
<td><p>Destination of the media stream.</p></td>
</tr>
</tbody>
</table>


### Child elements

None.

### Attributes

None.

