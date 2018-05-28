---
<<<<<<< HEAD
title: "/verbose"
ms.date: 07/20/2015
ms.prod: .net
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "devlang-visual-basic"
ms.topic: "article"
=======
title: "-verbose"
ms.date: 03/13/2018
>>>>>>> upstream/master
helpviewer_keywords: 
  - "verbose compiler option [Visual Basic]"
  - "-verbose compiler option [Visual Basic]"
  - "/verbose compiler option [Visual Basic]"
ms.assetid: d1aec0c1-0261-421d-9adc-5b13756100be
<<<<<<< HEAD
caps.latest.revision: 11
author: dotnet-bot
ms.author: dotnetcontent
---
# /verbose
=======
author: rpetrusha
ms.author: ronpet
---
# -verbose
>>>>>>> upstream/master
Causes the compiler to produce verbose status and error messages.  
  
## Syntax  
  
```  
<<<<<<< HEAD
/verbose[+ | -]  
=======
-verbose[+ | -]  
>>>>>>> upstream/master
```  
  
## Arguments  
 `+` &#124; `-`  
<<<<<<< HEAD
 Optional. Specifying `/verbose` is the same as specifying `/verbose+`, which causes the compiler to emit verbose messages. The default for this option is `/verbose-`.  
  
## Remarks  
 The `/verbose` option displays information about the total number of errors issued by the compiler, reports which assemblies are being loaded by a module, and displays which files are currently being compiled.  
  
> [!NOTE]
>  The `/verbose` option is not available from within the Visual Studio development environment; it is available only when compiling from the command line.  
=======
 Optional. Specifying `-verbose` is the same as specifying `-verbose+`, which causes the compiler to emit verbose messages. The default for this option is `-verbose-`.  
  
## Remarks  
 The `-verbose` option displays information about the total number of errors issued by the compiler, reports which assemblies are being loaded by a module, and displays which files are currently being compiled.  
  
> [!NOTE]
>  The `-verbose` option is not available from within the Visual Studio development environment; it is available only when compiling from the command line.  
>>>>>>> upstream/master
  
## Example  
 The following code compiles `In.vb` and directs the compiler to display verbose status information.  
  
<<<<<<< HEAD
```  
vbc /verbose in.vb  
=======
```console  
vbc -verbose in.vb  
>>>>>>> upstream/master
```  
  
## See Also  
 [Visual Basic Command-Line Compiler](../../../visual-basic/reference/command-line-compiler/index.md)  
 [Sample Compilation Command Lines](../../../visual-basic/reference/command-line-compiler/sample-compilation-command-lines.md)
