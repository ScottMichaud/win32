---
Description: The SetSyncSource method sets a reference clock for the object. This method implements the IMediaFilter::SetSyncSource method.
ms.assetid: ae296741-e3da-4376-a88a-8470f0a414ed
title: CBaseMediaFilter.SetSyncSource method
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# CBaseMediaFilter.SetSyncSource method

The `SetSyncSource` method sets a reference clock for the object. This method implements the [**IMediaFilter::SetSyncSource**](/windows/desktop/api/Strmif/nf-strmif-imediafilter-setsyncsource) method.

## Syntax


```C++
HRESULT SetSyncSource(
   IReferenceClock *pClock
);
```



## Parameters

<dl> <dt>

*pClock* 
</dt> <dd>

Pointer to the clock's [**IReferenceClock**](/windows/desktop/api/Strmif/nn-strmif-ireferenceclock) interface, or **NULL**.

</dd> </dl>

## Return value

Returns S\_OK.

## Requirements



|                    |                                                                                                                                                                                            |
|--------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Header<br/>  | <dl> <dt>Amfilter.h (include Streams.h)</dt> </dl>                                                                                  |
| Library<br/> | <dl> <dt>Strmbase.lib (retail builds); </dt> <dt>Strmbasd.lib (debug builds)</dt> </dl> |



## See also

<dl> <dt>

[**CBaseMediaFilter Class**](cbasemediafilter.md)
</dt> </dl>

 

 



