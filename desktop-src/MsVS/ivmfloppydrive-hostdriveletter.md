---
error-parsing-yaml: 
---

# IVMFloppyDrive::HostDriveLetter property

The **HostDriveLetter** property contains the letter of the physical floppy drive to which this floppy drive is attached.

This property is read-only.

## Syntax


```C++
HRESULT get_HostDriveLetter(
  [out] BSTR *driveLetter
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
<td><pre><code>VMFloppyDrive.HostDriveLetter( _
  ByRef driveLetter _
)</code></pre></td>
</tr>
</tbody>
</table>



## Property value

The letter of the physical floppy drive to which this floppy drive is attached.

This property value is read-only.

## Error codes



| Name                                                                                                | Meaning                                                                              |
|-----------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------|
| <dl> <dt>S\_OK</dt> </dl>                    | The operation was successful.<br/>                                             |
| <dl> <dt>E\_POINTER</dt> </dl>               | The parameter is **NULL**.<br/>                                                |
| <dl> <dt>VM\_E\_VM\_UNKNOWN</dt> </dl>       | The configuration for this virtual machine is invalid or cannot be found.<br/> |
| <dl> <dt>VM\_E\_PREF\_READ\_ERROR</dt> </dl> | There was an error reading from the preferences for this drive.<br/>           |
| <dl> <dt>DISP\_E\_EXCEPTION</dt> </dl>       | An unexpected error occurred.<br/>                                             |



## Requirements



|                     |                                                                                                   |
|---------------------|---------------------------------------------------------------------------------------------------|
| Product<br/>  | Microsoft Virtual Server 2005 onWindows Server 2003<br/>                                    |
| Download<br/> | Microsoft Virtual Server 2005 R2 SP1 Update onWindows Server 2008orWindows Server 2003<br/> |
| Header<br/>   | <dl> <dt>VsComInterfaces.h</dt> </dl>      |



## See also

<dl> <dt>

[**IVMFloppyDrive**](ivmfloppydrive.md)
</dt> </dl>

 

 




