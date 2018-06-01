---
Description: The RoutingMessages property is a number that represents the total number of incoming fax jobs that the fax service is currently routing.
ms.assetid: d5fd253f-528a-4eec-9c86-97ee7232cc45
title: FaxActivity.RoutingMessages property
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# FaxActivity.RoutingMessages property

The **RoutingMessages** property is a number that represents the total number of incoming fax jobs that the fax service is currently routing.

This property is read-only.

## Syntax


```VB
Property RoutingMessages As Long
```



## Property value

A **Long** that receives the total number of incoming jobs that the fax service is currently routing.

## Remarks

To read this property, a user must have the [****farQUERY\_CONFIG****](/previous-versions/windows/desktop/api/FaxComex/ne-faxcomex-fax_access_rights_enum) access right.

## Requirements



|                                     |                                                                                         |
|-------------------------------------|-----------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows XP \[desktop apps only\]<br/>                                             |
| Minimum supported server<br/> | Windows Server 2003 \[desktop apps only\]<br/>                                    |
| Header<br/>                   | <dl> <dt>FaxComex.h</dt> </dl>   |
| DLL<br/>                      | <dl> <dt>Fxscomex.dll</dt> </dl> |



## See also

<dl> <dt>

[Visual Basic Example](-mfax-monitoring-fax-activity.md)
</dt> <dt>

[**FaxActivity**](-mfax-faxactivity.md)
</dt> <dt>

[**IFaxActivity**](/previous-versions/windows/desktop/api/FaxComex/nn-faxcomex-ifaxactivity)
</dt> </dl>

 

 



