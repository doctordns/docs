### Entity Framework version must match the .NET Framework version

|   |   |
|---|---|
<<<<<<< HEAD
|Details|The entity framework version should be matched with the .NET framework version. Entity Framework 5 is recommended for .NET 4.5. There are some known issues with EF 4.x in a .NET 4.5 project around <xref:System.ComponentModel.DataAnnotations>. In .NET 4.5, these were moved to a different assembly, so there are issues determining which annotations to use.|
=======
|Details|The entity framework version should be matched with the .NET framework version. Entity Framework 5 is recommended for .NET Framework 4.5. There are some known issues with EF 4.x in a .NET Framework 4.5 project around <xref:System.ComponentModel.DataAnnotations>. In .NET 4.5, these were moved to a different assembly, so there are issues determining which annotations to use.|
>>>>>>> upstream/master
|Suggestion|Upgrade to Entity Framework 5 for .NET Framework 4.5|
|Scope|Major|
|Version|4.5|
|Type|Retargeting|
<<<<<<< HEAD
|Analyzers|<ul><li>CD0025</li></ul>|
=======
>>>>>>> upstream/master

