---
error-parsing-yaml: 
---

# IVMMouse::Click method

The **Click** method simulates a mouse button click (press and release) using an enumerated button index.

## Syntax


```C++
HRESULT Click(
  [in] VMMouseButton buttonIndex
);
```



## Parameters

<dl> <dt>

*buttonIndex* \[in\]
</dt> <dd>

The enumerated index of the button being clicked.

</dd> </dl>

## Return value

This method can return one of these values.

This method supports standard return values, as well as the following. For information on Virtual Server specific return values not listed below, see [**HRESULT Codes Specific to the Virtual Server**](hresult-codes-specific-to-the-virtual-server.md).



| Return code                                                                                                | Description                                                                                                                                       |
|------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------|
| <dl> <dt> **S\_OK** </dt> </dl>                     | The operation was successful. <br/>                                                                                                         |
| <dl> <dt> **E\_INVALIDARG**</dt> </dl>              | The *buttonIndex* parameter is not valid.<br/>                                                                                              |
| <dl> <dt> **VM\_E\_MOUSE\_NOT\_ACTIVE** </dt> </dl> | The operation could not be completed because the mouse device is not powered up, or it is not currently active in the virtual machine.<br/> |
| <dl> <dt> **DISP\_E\_EXCEPTION** </dt> </dl>        | An unexpected error occurred.<br/>                                                                                                          |



 

## Requirements



|                     |                                                                                                   |
|---------------------|---------------------------------------------------------------------------------------------------|
| Product<br/>  | Microsoft Virtual Server 2005 onWindows Server 2003<br/>                                    |
| Download<br/> | Microsoft Virtual Server 2005 R2 SP1 Update onWindows Server 2008orWindows Server 2003<br/> |
| Header<br/>   | <dl> <dt>VsComInterfaces.h</dt> </dl>      |



## See also

<dl> <dt>

[**IVMMouse**](ivmmouse.md)
</dt> <dt>

[**VMMouseButton**](vmmousebutton.md)
</dt> </dl>

 

 




