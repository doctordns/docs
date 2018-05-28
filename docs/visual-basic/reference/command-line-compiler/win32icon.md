---
<<<<<<< HEAD
title: "/win32icon"
ms.date: 07/20/2015
ms.prod: .net
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "devlang-visual-basic"
ms.topic: "article"
=======
title: "-win32icon"
ms.date: 03/13/2018
>>>>>>> upstream/master
helpviewer_keywords: 
  - "win32icon compiler option [Visual Basic]"
  - "-win32icon compiler option [Visual Basic]"
  - "/win32icon compiler option [Visual Basic]"
ms.assetid: aecaab01-9353-46c5-941c-6edabd4eff92
<<<<<<< HEAD
caps.latest.revision: 13
author: dotnet-bot
ms.author: dotnetcontent
---
# /win32icon
=======
author: rpetrusha
ms.author: ronpet
---
# -win32icon
>>>>>>> upstream/master
Inserts an .ico file in the output file. This .ico file represents the output file in **File Explorer**.  
  
## Syntax  
  
```  
<<<<<<< HEAD
/win32icon:filename  
=======
-win32icon:filename  
>>>>>>> upstream/master
```  
  
## Arguments  
  
|Term|Definition|  
|---|---|  
|`filename`|The .ico file to add to your output file. Enclose the file name in quotation marks (" ") if it contains a space.|  
  
## Remarks  
<<<<<<< HEAD
 You can create an .ico file with the Microsoft Windows Resource Compiler (RC). The resource compiler is invoked when you compile a Visual C++ program; an .ico file is created from the .rc file. The `/win32icon` and `/win32resource` options are mutually exclusive.  
  
 See [/linkresource (Visual Basic)](../../../visual-basic/reference/command-line-compiler/linkresource.md) to reference a [!INCLUDE[dnprdnshort](~/includes/dnprdnshort-md.md)] resource file, or [/resource (Visual Basic)](../../../visual-basic/reference/command-line-compiler/resource.md) to attach a [!INCLUDE[dnprdnshort](~/includes/dnprdnshort-md.md)] resource file. See [/win32resource](../../../visual-basic/reference/command-line-compiler/win32resource.md) to import a .res file.  
  
|To set /win32icon in the Visual Studio IDE|  
=======
 You can create an .ico file with the Microsoft Windows Resource Compiler (RC). The resource compiler is invoked when you compile a Visual C++ program; an .ico file is created from the .rc file. The `-win32icon` and `-win32resource` options are mutually exclusive.  
  
 See [-linkresource (Visual Basic)](../../../visual-basic/reference/command-line-compiler/linkresource.md) to reference a [!INCLUDE[dnprdnshort](~/includes/dnprdnshort-md.md)] resource file, or [-resource (Visual Basic)](../../../visual-basic/reference/command-line-compiler/resource.md) to attach a [!INCLUDE[dnprdnshort](~/includes/dnprdnshort-md.md)] resource file. See [-win32resource](../../../visual-basic/reference/command-line-compiler/win32resource.md) to import a .res file.  
  
|To set -win32icon in the Visual Studio IDE|  
>>>>>>> upstream/master
|---|  
|1.  Have a project selected in **Solution Explorer**. On the **Project** menu, click **Properties**. <br />2.  Click the **Application** tab.<br />3.  Modify the value in the **Icon** box.|  
  
## Example  
 The following code compiles `In.vb` and attaches an .ico file, `Rf.ico`.  
  
<<<<<<< HEAD
```  
vbc /win32icon:rf.ico in.vb  
=======
```console
vbc -win32icon:rf.ico in.vb  
>>>>>>> upstream/master
```  
  
## See Also  
 [Visual Basic Command-Line Compiler](../../../visual-basic/reference/command-line-compiler/index.md)  
 [Sample Compilation Command Lines](../../../visual-basic/reference/command-line-compiler/sample-compilation-command-lines.md)
