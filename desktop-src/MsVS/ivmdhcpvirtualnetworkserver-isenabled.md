---
error-parsing-yaml: 
---

# IVMDHCPVirtualNetworkServer::IsEnabled property

The **IsEnabled** property indicates whether the DHCP virtual network server is enabled.

This property is read/write.

## Syntax


```C++
HRESULT put_IsEnabled(
  [in]  VARIANT_BOOL isEnabled
);

HRESULT get_IsEnabled(
  [out] VARIANT_BOOL *isEnabled
);
```

<span codelanguage="VisualBasic"></span>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>VB</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><pre><code>VMDHCPVirtualNetworkServer.IsEnabled( _
  ByRef isEnabled, _
  ByVal isEnabled _
)</code></pre></td>
</tr>
</tbody>
</table>



## Property value

Contains **vbTrue** if the DHCP virtual network server is enabled, **vbFalse** if disabled.

This property value is read/write.

## Error codes



| Name                                                                                          | Meaning                                            |
|-----------------------------------------------------------------------------------------------|----------------------------------------------------|
| <dl> <dt>S\_OK</dt> </dl>              | The operation was successful.<br/>           |
| <dl> <dt>E\_POINTER</dt> </dl>         | The parameter *isEnabled* was **NULL**.<br/> |
| <dl> <dt>DISP\_E\_EXCEPTION</dt> </dl> | An unexpected error has occurred.<br/>       |



## Requirements



|                     |                                                                                                   |
|---------------------|---------------------------------------------------------------------------------------------------|
| Product<br/>  | Microsoft Virtual Server 2005 onWindows Server 2003<br/>                                    |
| Download<br/> | Microsoft Virtual Server 2005 R2 SP1 Update onWindows Server 2008orWindows Server 2003<br/> |
| Header<br/>   | <dl> <dt>VsComInterfaces.h</dt> </dl>      |



## See also

<dl> <dt>

[**IVMDHCPVirtualNetworkServer**](ivmdhcpvirtualnetworkserver.md)
</dt> </dl>

 

 




