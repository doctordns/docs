---
<<<<<<< HEAD
title: "/recurse"
ms.date: 07/20/2015
ms.prod: .net
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "devlang-visual-basic"
ms.topic: "article"
=======
title: "-recurse"
ms.date: 03/13/2018
>>>>>>> upstream/master
helpviewer_keywords: 
  - "/recurse compiler option [Visual Basic]"
  - "-recurse compiler option [Visual Basic]"
  - "recurse compiler option [Visual Basic]"
ms.assetid: 84a0b670-33ae-44c4-a46a-b90388809317
<<<<<<< HEAD
caps.latest.revision: 12
author: dotnet-bot
ms.author: dotnetcontent
---
# /recurse
=======
author: rpetrusha
ms.author: ronpet
---
# -recurse
>>>>>>> upstream/master
Compiles source-code files in all child directories of either the specified directory or the project directory.  
  
## Syntax  
  
```  
<<<<<<< HEAD
/recurse:[dir\]file  
=======
-recurse:[dir\]file  
>>>>>>> upstream/master
```  
  
## Arguments  
 `dir`  
 Optional. The directory in which you want the search to begin. If not specified, the search begins in the project directory.  
  
 `file`  
 Required. The file(s) to search for. Wildcard characters are allowed.  
  
## Remarks  
<<<<<<< HEAD
 You can use wildcards in a file name to compile all matching files in the project directory without using `/recurse`. If no output file name is specified, the compiler bases the output file name on the first input file processed. This is generally the first file in the list of files compiled when viewed alphabetically. For this reason, it is best to specify an output file using the `/out` option.  
  
> [!NOTE]
>  The `/recurse` option is not available from within the Visual Studio development environment; it is available only when compiling from the command line.  
  
## Example  
 The following code compiles all [!INCLUDE[vbprvb](~/includes/vbprvb-md.md)] files in the current directory.  
  
```  
vbc *.vb  
```  
  
 The following code compiles all [!INCLUDE[vbprvb](~/includes/vbprvb-md.md)] files in the `Test\ABC` directory and any directories below it, and then generates `Test.ABC.dll`.  
  
```  
vbc /target:library /out:Test.ABC.dll /recurse:Test\ABC\*.vb  
=======
 You can use wildcards in a file name to compile all matching files in the project directory without using `-recurse`. If no output file name is specified, the compiler bases the output file name on the first input file processed. This is generally the first file in the list of files compiled when viewed alphabetically. For this reason, it is best to specify an output file using the `-out` option.  
  
> [!NOTE]
>  The `-recurse` option is not available from within the Visual Studio development environment; it is available only when compiling from the command line.  
  
## Example  
 The following command compiles all Visual Basic files in the current directory.  
  
```console
vbc *.vb  
```  
  
 The following command compiles all Visual Basic files in the `Test\ABC` directory and any directories below it, and then generates `Test.ABC.dll`.  
  
```console
vbc -target:library -out:Test.ABC.dll -recurse:Test\ABC\*.vb  
>>>>>>> upstream/master
```  
  
## See Also  
 [Visual Basic Command-Line Compiler](../../../visual-basic/reference/command-line-compiler/index.md)  
<<<<<<< HEAD
 [/out (Visual Basic)](../../../visual-basic/reference/command-line-compiler/out.md)  
=======
 [-out (Visual Basic)](../../../visual-basic/reference/command-line-compiler/out.md)  
>>>>>>> upstream/master
 [Sample Compilation Command Lines](../../../visual-basic/reference/command-line-compiler/sample-compilation-command-lines.md)
