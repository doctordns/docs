---
<<<<<<< HEAD
title: "/utf8output (Visual Basic)"
ms.date: 07/20/2015
ms.prod: .net
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "devlang-visual-basic"
ms.topic: "article"
=======
title: "-utf8output (Visual Basic)"
ms.date: 07/20/2015
>>>>>>> upstream/master
helpviewer_keywords: 
  - "-utf8output compiler option [Visual Basic]"
  - "utf8output compiler option [Visual Basic]"
  - "/utf8output compiler option [Visual Basic]"
ms.assetid: 8ab36b1e-027a-49ac-85b4-f48997d9e4d6
<<<<<<< HEAD
caps.latest.revision: 11
author: dotnet-bot
ms.author: dotnetcontent
---
# /utf8output (Visual Basic)
=======
---
# -utf8output (Visual Basic)
>>>>>>> upstream/master
Displays compiler output using UTF-8 encoding.  
  
## Syntax  
  
```  
<<<<<<< HEAD
/utf8output[+ | -]  
=======
-utf8output[+ | -]  
>>>>>>> upstream/master
```  
  
## Arguments  
 `+` &#124; `-`  
<<<<<<< HEAD
 Optional. The default for this option is `/utf8output-`, which means compiler output does not use UTF-8 encoding. Specifying `/utf8output` is the same as specifying `/utf8output+`.  
  
## Remarks  
 In some international configurations, compiler output cannot be displayed correctly in the console. In such situations, use `/utf8output` and redirect compiler output to a file.  
  
> [!NOTE]
>  The `/utf8output` option is not available from within the Visual Studio development environment; it is available only when compiling from the command line.  
=======
 Optional. The default for this option is `-utf8output-`, which means compiler output does not use UTF-8 encoding. Specifying `-utf8output` is the same as specifying `-utf8output+`.  
  
## Remarks  
 In some international configurations, compiler output cannot be displayed correctly in the console. In such situations, use `-utf8output` and redirect compiler output to a file.  
  
> [!NOTE]
>  The `-utf8output` option is not available from within the Visual Studio development environment; it is available only when compiling from the command line.  
>>>>>>> upstream/master
  
## Example  
 The following code compiles `In.vb` and directs the compiler to display output using UTF-8 encoding.  
  
<<<<<<< HEAD
```  
vbc /utf8output in.vb  
=======
```console  
vbc -utf8output in.vb  
>>>>>>> upstream/master
```  
  
## See Also  
 [Visual Basic Command-Line Compiler](../../../visual-basic/reference/command-line-compiler/index.md)  
 [Sample Compilation Command Lines](../../../visual-basic/reference/command-line-compiler/sample-compilation-command-lines.md)
