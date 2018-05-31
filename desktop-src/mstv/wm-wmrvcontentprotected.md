---
error-parsing-yaml: 
---

# WM/WMRVContentProtected

Specifies whether a significant portion of a DVR-MS file is protected.

## Data Type

**BOOL** (STREAMBUFFER\_TYPE\_BOOL)

## Remarks

Windows Media Center sets this attribute to **TRUE** if the file contains more than 5 minutes of protected content, or if more than 5 percent of the total content is protected. When this attribute is **TRUE**, it is a good indication that the file cannot be played on another computer, although portions of the file might be unprotected.

If the attribute is **FALSE** or not present, the file contains less than this amount of protected content. The file might contain small amounts of protected content, however, so applications that play DVR-MS files must be able to handle brief periods of protected content during playback.

To account for any difference between the computer clock and the actual broadcast times, Windows Media Center usually starts a recording a few minutes before a show begins, and stops the recording a few minutes after it ends. This additional content is ignored when calculating the value of this attribute.

> [!Note]  
> It can take up to 30 minutes after the recording is finished for this attribute to be updated.

 

## See also

<dl> <dt>

[Detecting Content Protection in Recorded TV Files](detecting-content-protection-in-recorded-tv-files.md)
</dt> <dt>

[Stream Buffer Engine Attributes](stream-buffer-engine-attributes.md)
</dt> </dl>

 

 



