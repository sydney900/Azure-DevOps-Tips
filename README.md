## Get rid of XML documentation files in Azure DevOps build

Added following MSBuild Arguments in Visual Studio build task
```
/p:GenerateDocumentation=false  /p:AllowedReferenceRelatedFileExtensions=.pdb
```
