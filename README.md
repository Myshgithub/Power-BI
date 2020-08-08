# Hello World with Documentation
This sample shows how to add documentation to your shared functions. To simply the code sample, the project is not using string or icon resources. In a real extension, you would use `Extension.LoadString` to load (localized) strings from your resources.resx file.

**Function invocation**
![FunctionPrompt](../../blobs/helloWorldWithDocs.png "Hello world with docs prompt")

**Function info**
![FunctionInfo](../../blobs/helloWorldWithDocsInfo.png "Hello world with docs function info")

# Hello World Sample
This sample provides a simple data source extension that can be run in Visual Studio, and loaded in Power BI Desktop. As an overview, this sample shows the following:

Exporting function (HelloWorld.Contents), which takes an option text parameter.
Defining a data source kind that:
Declares that it uses Implicit (anonymous) authentication.
Uses string resources that allow for localization.
Declaring UI metadata so the extension can show up in the Power BI Desktop Get Data dialog.
