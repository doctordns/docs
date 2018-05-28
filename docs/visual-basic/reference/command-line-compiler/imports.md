---
<<<<<<< HEAD
title: "/imports (Visual Basic)"
ms.date: 07/20/2015
ms.prod: .net
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "devlang-visual-basic"
ms.topic: "article"
=======
title: "-imports (Visual Basic)"
ms.date: 03/10/2018
>>>>>>> upstream/master
helpviewer_keywords: 
  - "/imports compiler option [Visual Basic]"
  - "imports compiler option [Visual Basic]"
  - "-imports compiler option [Visual Basic]"
ms.assetid: 9a93fb53-c080-497b-bf9b-441022dbbc39
<<<<<<< HEAD
caps.latest.revision: 15
author: dotnet-bot
ms.author: dotnetcontent
---
# /imports (Visual Basic)
=======
---
# -imports (Visual Basic)
>>>>>>> upstream/master
Imports namespaces from a specified assembly.  
  
## Syntax  
  
```  
<<<<<<< HEAD
/imports:namespaceList  
=======
-imports:namespaceList  
>>>>>>> upstream/master
```  
  
## Arguments  
  
|Term|Definition|  
|---|---|  
|`namespaceList`|Required. Comma-delimited list of namespaces to be imported.|  
  
## Remarks  
<<<<<<< HEAD
 The `/imports` option imports any namespace defined within the current set of source files or from any referenced assembly.  
  
 The members in a namespace specified with `/imports` are available to all source-code files in the compilation. Use the [Imports Statement (.NET Namespace and Type)](../../../visual-basic/language-reference/statements/imports-statement-net-namespace-and-type.md) to use a namespace in a single source-code file.  
=======
 The `-imports` option imports any namespace defined within the current set of source files or from any referenced assembly.  
  
 The members in a namespace specified with `-imports` are available to all source-code files in the compilation. Use the [Imports Statement (.NET Namespace and Type)](../../../visual-basic/language-reference/statements/imports-statement-net-namespace-and-type.md) to use a namespace in a single source-code file.  
>>>>>>> upstream/master
  
|To set /imports in the Visual Studio integrated development environment|  
|---|  
|1.  Have a project selected in **Solution Explorer**. On the **Project** menu, click **Properties**. <br />2.  Click the **References** tab.<br />3.  Enter the namespace name in the box beside the **Add User Import** button.<br />4.  Click the **Add User Import** button.|  
  
## Example  
<<<<<<< HEAD
 The following code compiles when `/imports:system` is specified.  
  
 [!code-vb[VbVbalrCompiler#21](../../../visual-basic/reference/command-line-compiler/codesnippet/VisualBasic/imports_1.vb)]  
=======
 The following code compiles when `/imports:system.globalization` is specified. Without it, successful compilation requires either that an `Imports System.Globalization` statement be included at the beginning of the source code file, or that the property be fully qualified as `System.Globalization.CultureInfo.CurrentCulture.Name`. 
  
 [!code-vb[imports example](codesnippet/VisualBasic/imports_2.vb)]  
>>>>>>> upstream/master
  
## See Also  
 [Visual Basic Command-Line Compiler](../../../visual-basic/reference/command-line-compiler/index.md)  
 [References and the Imports Statement](../../../visual-basic/programming-guide/program-structure/references-and-the-imports-statement.md)  
 [Sample Compilation Command Lines](../../../visual-basic/reference/command-line-compiler/sample-compilation-command-lines.md)
