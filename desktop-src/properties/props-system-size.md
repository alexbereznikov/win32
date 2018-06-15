---
Description: The system-provided file system size of the item, in bytes.
ms.assetid: 471c38fc-2382-4df8-8f70-e1af0dd6c746
title: System.Size
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# System.Size

The system-provided file system size of the item, in bytes.

## Windows 10, version 1703, Windows 10, version 1607, Windows 10, version 1511, Windows 10, version 1507, Windows 8.1, Windows 8, Windows 7

```
propertyDescription
   name = System.Size
   shellPKey = PKEY_Size
   formatID = B725F130-47EF-101A-A5F1-02608C9EEBAC
   propID = 12
   SearchInfo
      InInvertedIndex = false
      IsColumn = true
   typeInfo
      type = UInt64
      IsInnate = true
      EnumeratedList
         UseValueForDefault = True
         enumRange
            name = Empty
            minValue = 0
            setValue = 0
            text = Empty (0 KB)
            defineToken = SIZE_EMPTY
            mnemonics = empty
         enumRange
            name = Tiny
            minValue = 1
            setValue = 1
            text = Tiny (0 - 10 KB)
            defineToken = SIZE_TINY
            mnemonics = tiny
         enumRange
            name = Small
            minValue = 10241
            setValue = 10241
            text = Small (10 - 100 KB)
            defineToken = SIZE_SMALL
            mnemonics = small
         enumRange
            name = Medium
            minValue = 102401
            setValue = 102401
            text = Medium (100 KB - 1 MB)
            defineToken = SIZE_MEDIUM
            mnemonics = medium
         enumRange
            name = Large
            minValue = 1048577
            setValue = 1048577
            text = Large (1 - 16 MB)
            defineToken = SIZE_LARGE
            mnemonics = large
         enumRange
            name = Huge
            minValue = 16777217
            setValue = 16777217
            text = Huge (16 - 128 MB)
            defineToken = SIZE_HUGE
            mnemonics = huge
         enumRange
            name = Gigantic
            minValue = 134217729
            setValue = 134217729
            text = Gigantic (>128 MB)
            defineToken = SIZE_GIGANTIC
            mnemonics = gigantic
```

## Windows Vista

```
propertyDescription
   name = System.Size
   shellPKey = PKEY_Size
   formatID = B725F130-47EF-101A-A5F1-02608C9EEBAC
   propID = 12
   SearchInfo
      IsColumn = true
   typeInfo
      type = UInt64
      IsInnate = true
      EnumeratedList
         UseValueForDefault = True
         enumRange
            minValue = 0
            setValue = 0
            text = 0 KB
            mnemonics = empty
         enumRange
            minValue = 1
            setValue = 1
            text = 0 - 10 KB
            mnemonics = tiny
         enumRange
            minValue = 10241
            setValue = 10241
            text = 10 - 100 KB
            mnemonics = small
         enumRange
            minValue = 102401
            setValue = 102401
            text = 100 KB - 1 MB
            mnemonics = medium
         enumRange
            minValue = 1048577
            setValue = 1048577
            text = 1 - 16 MB
            mnemonics = large
         enumRange
            minValue = 16777217
            setValue = 16777217
            text = 16 - 128 MB
            mnemonics = huge
         enumRange
            minValue = 134217729
            setValue = 134217729
            text = >128 MB
            mnemonics = gigantic
```

## Remarks

PKEY values are defined in Propkey.h.

## Related topics

<dl> <dt>

[propertyDescription](https://www.bing.com/search?q=propertyDescription)
</dt> <dt>

[searchInfo](https://www.bing.com/search?q=searchInfo)
</dt> <dt>

[labelInfo](https://www.bing.com/search?q=labelInfo)
</dt> <dt>

[typeInfo](https://www.bing.com/search?q=typeInfo)
</dt> <dt>

[displayInfo](https://www.bing.com/search?q=displayInfo)
</dt> <dt>

[stringFormat](https://www.bing.com/search?q=stringFormat)
</dt> <dt>

[booleanFormat](https://www.bing.com/search?q=booleanFormat)
</dt> <dt>

[numberFormat](https://www.bing.com/search?q=numberFormat)
</dt> <dt>

[dateTimeFormat](https://www.bing.com/search?q=dateTimeFormat)
</dt> <dt>

[enumeratedList](https://www.bing.com/search?q=enumeratedList)
</dt> <dt>

[drawControl](https://www.bing.com/search?q=drawControl)
</dt> <dt>

[editControl](https://www.bing.com/search?q=editControl)
</dt> <dt>

[filterControl](https://www.bing.com/search?q=filterControl)
</dt> <dt>

[queryControl](https://www.bing.com/search?q=queryControl)
</dt> </dl>

 

 


