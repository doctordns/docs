---
<<<<<<< HEAD
title: "/nologo (Visual Basic)"
ms.date: 07/20/2015
ms.prod: .net
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "devlang-visual-basic"
ms.topic: "article"
=======
title: "-nologo (Visual Basic)"
ms.date: 03/13/2018
>>>>>>> upstream/master
helpviewer_keywords: 
  - "-nologo compiler option [Visual Basic]"
  - "banners [Visual Basic], suppressing startup"
  - "nologo compiler option [Visual Basic]"
  - "/nologo compiler option [Visual Basic]"
ms.assetid: 25ef54b6-d676-4639-a2d2-a747a158bc07
<<<<<<< HEAD
caps.latest.revision: 16
author: dotnet-bot
ms.author: dotnetcontent
---
# /nologo (Visual Basic)
=======
author: rpetrusha
ms.author: ronpet
---
# -nologo (Visual Basic)
>>>>>>> upstream/master
Suppresses display of the copyright banner and informational messages during compilation.  
  
## Syntax  
  
```  
<<<<<<< HEAD
/nologo  
```  
  
## Remarks  
 If you specify `/nologo`, the compiler does not display a copyright banner. By default, `/nologo` is not in effect.  
  
> [!NOTE]
>  The `/nologo` option is not available from within the Visual Studio development environment; it is available only when compiling from the command line.  
=======
-nologo  
```  
  
## Remarks  
 If you specify `-nologo`, the compiler does not display a copyright banner. By default, `-nologo` is not in effect.  
  
> [!NOTE]
>  The `-nologo` option is not available from within the Visual Studio development environment; it is available only when compiling from the command line.  
>>>>>>> upstream/master
  
## Example  
 The following code compiles `T2.vb` and does not display a copyright banner.  
  
<<<<<<< HEAD
```  
vbc /nologo t2.vb  
=======
```console
vbc -nologo t2.vb  
>>>>>>> upstream/master
```  
  
## See Also  
 [Visual Basic Command-Line Compiler](../../../visual-basic/reference/command-line-compiler/index.md)  
 [Sample Compilation Command Lines](../../../visual-basic/reference/command-line-compiler/sample-compilation-command-lines.md)
