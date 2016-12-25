# Using Nosnitor.TestResources.AttributeAssemblies #

The AttributeAssemblies package contains binaries with different values set for the AssemblyAttribues in the assembly manifest. These binaries can be used for testing methods that access these attributes.

## Installation ##

Include the Nosnitor.TestResources.AttributeAssemblies package from [nuget.org](https://www.nuget.org/packages/Nosnitor.TestResources.AttributeAssemblies) in a project in your solution.

## Included Assemblies ##

The following assemblies are included in the Nosnitor.TestResources.AttributeAssemblies package:

* NoAttributeAssembly.dll
* TestAttributeAssembly1.dll
* TestAttributeAssembly2.dll

## Assembly Attribute Values ##

| Attribute Name       | NoAttributeAssembly | TestAttributeAssembly1 | TestAttributeAssembly2 |
|:---------------------|---------------------|------------------------|------------------------|
| Company              | null                | TestCompany1           | TestCompany2           |
| Configuration        | null                | Debug                  | Release                |
| Copyright            | null                | TestCopyright1         | TestCopyright2         |
| DefaultAlias         | null                | TestDefaultAlias1      | TestDefaultAlias2      |
| Description          | null                | TestDescription1       | TestDescription2       |
| FileVersion          | null                | 2.3.4.5                | 5.4.3.2                |
| InformationalVersion | null                | 3.4.5-six              | 6.5.4-three            |
| Product              | null                | TestProduct1           | TestProduct2           |
| Title                | null                | TestTitle1             | TestTitle2             |
| Trademark            | null                | TestTrademark1         | TestTrademark2         |
| Version              | 0.0.0.0             | 1.2.3.4                | 4.3.2.1                |