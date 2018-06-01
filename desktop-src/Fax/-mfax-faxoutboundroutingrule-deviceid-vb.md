---
Description: The DeviceId property specifies the device ID if the outbound routing rule points to a single fax device.
ms.assetid: 0b9328d5-4213-4d10-9201-8c9035a22ccc
title: FaxOutboundRoutingRule.DeviceId property
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# FaxOutboundRoutingRule.DeviceId property

The **DeviceId** property specifies the device ID if the outbound routing rule points to a single fax device.

This property is read/write.

## Syntax


```VB
Property DeviceId As Long
```



## Property value

A **Long** value that receives the device ID of the single fax device associated with a particular outbound routing rule.

## Remarks

This property is valid only if the [**UseDevice**](-mfax-faxoutboundroutingrule-usedevice-vb.md) property is equal to **True**.

To read or to write to this property, a user must have the [**farQUERY\_CONFIG**](/previous-versions/windows/desktop/api/FaxComex/ne-faxcomex-fax_access_rights_enum) access right.

## Requirements



|                                     |                                                                                         |
|-------------------------------------|-----------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows XP \[desktop apps only\]<br/>                                             |
| Minimum supported server<br/> | Windows Server 2003 \[desktop apps only\]<br/>                                    |
| Header<br/>                   | <dl> <dt>FaxComex.h</dt> </dl>   |
| DLL<br/>                      | <dl> <dt>Fxscomex.dll</dt> </dl> |



## See also

<dl> <dt>

[**FaxOutboundRoutingRule**](-mfax-faxoutboundroutingrule.md)
</dt> <dt>

[**IFaxOutboundRoutingRule**](/previous-versions/windows/desktop/api/FaxComex/nn-faxcomex-ifaxoutboundroutingrule)
</dt> </dl>

 

 



