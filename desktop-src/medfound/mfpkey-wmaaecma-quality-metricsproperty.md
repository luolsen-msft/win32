---
Description: Retrieves quality metrics on acoustic echo cancellation (AEC) from the Voice Capture DSP.
ms.assetid: de2e86ae-0469-471f-9105-0bb38a59b428
title: MFPKEY\_WMAAECMA\_QUALITY\_METRICS Property
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# MFPKEY\_WMAAECMA\_QUALITY\_METRICS Property

Retrieves quality metrics on acoustic echo cancellation (AEC) from the Voice Capture DSP.

## Constant for IPropertyBag

Available only by using [**IPropertyStore**](https://msdn.microsoft.com/e995aaa1-d4c9-475f-b1fa-b9123cd5b653).

## Data Type

VT\_BLOB

## Remarks

The value of this property is an [AecQualityMetrics\_Struct](/windows/desktop/api/wmcodecdsp/ns-wmcodecdsp-tagaecqualitymetrics_struct) structure. This property is read-only.

## Requirements



|                                     |                                                                                         |
|-------------------------------------|-----------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows Vista \[desktop apps only\]<br/>                                          |
| Minimum supported server<br/> | Windows Server 2008 \[desktop apps only\]<br/>                                    |
| Header<br/>                   | <dl> <dt>Wmcodecdsp.h</dt> </dl> |



## See also

<dl> <dt>

[Media Foundation Properties](media-foundation-properties.md)
</dt> <dt>

[Voice Capture DSP](voicecapturedmo.md)
</dt> </dl>

 

 



