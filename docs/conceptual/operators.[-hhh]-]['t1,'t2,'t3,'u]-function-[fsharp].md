---
title: Operators.( |||> )<'T1,'T2,'T3,'U> Function (F#)
description: Operators.( |||> )<'T1,'T2,'T3,'U> Function (F#)
keywords: visual f#, f#, functional programming
author: dend
manager: danielfe
ms.date: 05/16/2016
ms.topic: language-reference
ms.prod: visual-studio-dev14
ms.assetid: b8f35736-7d84-43e1-aad8-968436352aed 
---

# Operators.( |||> )<'T1,'T2,'T3,'U> Function (F#)

Applies a function to three values, the values being a triple on the left, the function on the right.

**Namespace/Module Path:** Microsoft.FSharp.Core.Operators

**Assembly:** FSharp.Core (in FSharp.Core.dll)


## Syntax



```




// Signature:
( |||> ) : 'T1 * 'T2 * 'T3 -> ('T1 -> 'T2 -> 'T3 -> 'U) -> 'U

// Usage:
(arg1, arg2, arg3) |||> func


```





#### Parameters
*arg1*
Type: **'T1**


The first argument.


*arg2*
Type: **'T2**


The second argument.


*arg3*
Type: **'T3**


The third argument.


*func*
Type: **'T1 -&gt; 'T2 -&gt; 'T3 -&gt; 'U**


The function.



**The function result.**
## Remarks
**The following example demonstrates the use of the |||&gt; operator.**
[!code-fsharp[Main](snippets/fsoperators/snippet3.fs)]
**("abc", "def", "ghi") |||&gt; append4 gives  "abc.def.ghi"**
## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[Core.Operators Module &#40;F&#35;&#41;](Core.Operators-Module-%5BFSharp%5D.md)

[Microsoft.FSharp.Core Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Core-Namespace-%5BFSharp%5D.md)

