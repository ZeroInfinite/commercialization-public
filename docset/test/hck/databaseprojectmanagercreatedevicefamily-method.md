---
author: joshbax-msft
title: DatabaseProjectManager.CreateDeviceFamily Method
description: DatabaseProjectManager.CreateDeviceFamily Method
MSHAttr:
- 'PreferredSiteName:MSDN'
- 'PreferredLib:/library/windows/hardware'
ms.assetid: 0c0da993-2c19-49eb-ba29-0d802bd4b74b
---

# DatabaseProjectManager.CreateDeviceFamily Method


This method creates a new device family with the given name.

**Namespace:** Microsoft.Windows.Kits.Hardware.ObjectModel.DBConnection **Assembly:** Microsoft.Windows.Kits.Hardware.ObjectModel.DBConnection (in Microsoft.Windows.Kits.Hardware.ObjectModel.DBConnection)

## Usage


**Visual Basic**`Dim instance As DatabaseProjectManager``Dim name As String``Dim familyIds As IEnumerable(Of String)``Dim returnValue As DeviceFamily``returnValue = instance.CreateDeviceFamily(name, familyIds)`

## Syntax


**Visual Basic**`Public Overrides Function CreateDeviceFamily ( _`           `name As String, _`           `familyIds As IEnumerable(Of String) _``) As DeviceFamily`

**C#**`public override DeviceFamily CreateDeviceFamily (`           `string name,`           `IEnumerable<string> familyIds``)`

## Parameters


*name*      The name to create the device family with.

*familyIds*      The ID values to use when creating the new device family.

## Return Value


Returns [DeviceFamily Class](devicefamily-class.md).

## Remarks


An exception occurs when the *familyIds* parameter is **null**, empty, or invalid.

## Thread Safety


Any public static (**Shared** in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

 

 

[Send comments about this topic to Microsoft](mailto:wsddocfb@microsoft.com?subject=Documentation%20feedback%20%5Bp_hck\p_hck%5D:%20DatabaseProjectManager.CreateDeviceFamily%20Method%20%20RELEASE:%20%284/27/2016%29&body=%0A%0APRIVACY%20STATEMENT%0A%0AWe%20use%20your%20feedback%20to%20improve%20the%20documentation.%20We%20don't%20use%20your%20email%20address%20for%20any%20other%20purpose,%20and%20we'll%20remove%20your%20email%20address%20from%20our%20system%20after%20the%20issue%20that%20you're%20reporting%20is%20fixed.%20While%20we're%20working%20to%20fix%20this%20issue,%20we%20might%20send%20you%20an%20email%20message%20to%20ask%20for%20more%20info.%20Later,%20we%20might%20also%20send%20you%20an%20email%20message%20to%20let%20you%20know%20that%20we've%20addressed%20your%20feedback.%0A%0AFor%20more%20info%20about%20Microsoft's%20privacy%20policy,%20see%20http://privacy.microsoft.com/default.aspx. "Send comments about this topic to Microsoft")



