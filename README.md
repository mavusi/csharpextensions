This is a fork of https://github.com/jchannon/csharpextensions seeing as that extension is no longer under development and I thought it was worth keeping alive. WHile the current functionality is pretty basic, it provides a solid foundation for future additions.

# C# Extensions

Welcome to C# Extensions.  This VSCode extension provides extensions to the IDE that will hopefully speed up your development workflow.

# What's new in v1.3.2
- Add Generic Json web Api client

# What's new in v1.3.1
- Add EF DbContext
- Add Asp.Net ApiController

## Features

**Add C# Class**

![Add C# Class](./featureimages/newclass.gif)

**Add C# Interface**

![Add C# Interface](./featureimages/newinterface.gif)

**Add fields from constructors**

![Add fields from constructors](./featureimages/fieldfromctor.gif)

**Add constructor from properties**

![Add constructor from properties](./featureimages/ctorfromprop.gif)

**Add read-only property from constructors**
![Add read-only property from constructors](./featureimages/propfromctor.gif)

**Add property from constructors**
![Add property from constructors](./featureimages/fullpropfromctor.gif)


This extension traverses up the folder tree to find the project.json or *.csproj and uses that as the parent folder to determine namespaces.


-----------------------------------------------------------------------------------------------------------

## Licence 

MIT  

See [licence.txt](./licence.txt)
