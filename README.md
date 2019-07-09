## Get rid of XML documentation files for you .Net project in Azure DevOps build

Added following MSBuild Arguments in Visual Studio build task
```
/p:GenerateDocumentation=false  /p:AllowedReferenceRelatedFileExtensions=.pdb
```

## Change .Net assembly info on the file
Add an [Assembly Info task](https://marketplace.visualstudio.com/items?itemName=bleddynrichards.Assembly-Info-Task) in your pipeline
