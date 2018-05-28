---
<<<<<<< HEAD
title: "/nostdlib (Visual Basic)"
ms.date: 07/20/2015
ms.prod: .net
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "devlang-visual-basic"
ms.topic: "article"
=======
title: "-nostdlib (Visual Basic)"
ms.date: 03/13/2018
>>>>>>> upstream/master
helpviewer_keywords: 
  - "nostdlib compiler option [Visual Basic]"
  - "-nostdlib compiler option [Visual Basic]"
  - "/nostdlib compiler option [Visual Basic]"
ms.assetid: 140381b8-dc96-4ad5-ae11-792c9ed0be4d
<<<<<<< HEAD
caps.latest.revision: 18
author: dotnet-bot
ms.author: dotnetcontent
---
# /nostdlib (Visual Basic)
=======
author: rpetrusha
ms.author: ronpet
---
# -nostdlib (Visual Basic)
>>>>>>> upstream/master
Causes the compiler not to automatically reference the standard libraries.  
  
## Syntax  
  
```  
<<<<<<< HEAD
/nostdlib  
```  
  
## Remarks  
 The `/nostdlib` option removes the automatic reference to the System.dll assembly and prevents the compiler from reading the Vbc.rsp file. The Vbc.rsp file—which is located in the same directory as the Vbc.exe file—references the commonly used [!INCLUDE[dnprdnshort](~/includes/dnprdnshort-md.md)] assemblies and imports the `System` and `Microsoft.VisualBasic` namespaces.  
=======
-nostdlib  
```  
  
## Remarks  
 The `-nostdlib` option removes the automatic reference to the System.dll assembly and prevents the compiler from reading the Vbc.rsp file. The Vbc.rsp file, which is located in the same directory as the Vbc.exe file, references the commonly used [!INCLUDE[dnprdnshort](~/includes/dnprdnshort-md.md)] assemblies and imports the `System` and `Microsoft.VisualBasic` namespaces.  
>>>>>>> upstream/master
  
> [!NOTE]
>  The Mscorlib.dll and Microsoft.VisualBasic.dll assemblies are always referenced.  
  
> [!NOTE]
<<<<<<< HEAD
>  The `/nostdlib` option is not available from within the Visual Studio development environment; it is available only when compiling from the command line.  
=======
>  The `-nostdlib` option is not available from within the Visual Studio development environment; it is available only when compiling from the command line.  
>>>>>>> upstream/master
  
## Example  
 The following code compiles `T2.vb` without referencing the standard libraries. You must set the `_MYTYPE` conditional-compilation constant to the string "Empty" to remove the `My` object.  
  
<<<<<<< HEAD
```  
vbc /nostdlib /define:_MYTYPE=\"Empty\" T2.vb  
```  
  
## See Also  
 [/noconfig](../../../visual-basic/reference/command-line-compiler/noconfig.md)  
=======
```console
vbc -nostdlib -define:_MYTYPE=\"Empty\" T2.vb  
```  
  
## See Also  
 [-noconfig](../../../visual-basic/reference/command-line-compiler/noconfig.md)  
>>>>>>> upstream/master
 [Visual Basic Command-Line Compiler](../../../visual-basic/reference/command-line-compiler/index.md)  
 [Sample Compilation Command Lines](../../../visual-basic/reference/command-line-compiler/sample-compilation-command-lines.md)  
 [Customizing Which Objects are Available in My](../../../visual-basic/developing-apps/customizing-extending-my/customizing-which-objects-are-available-in-my.md)
