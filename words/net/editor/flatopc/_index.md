---
title: Edit FlatOpc files via .NET 
url: /net/editor/flatopc/ 
description: Try our On-Premise document Editor APIs to edit FlatOpc document on .NET Framework, .NET Core, Windows Azure, Mono or Xamarin Platforms.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Edit FlatOpc Formats in C#" h2="Native and high performance FlatOpc document editing using server-side Aspose.Words for .NET APIs, without the use of any software like Microsoft or Adobe PDF." logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/words/272x272/aspose_words-for-net.png" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Words" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="FlatOpc" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Words " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/words/272x272/aspose_words-for-net.png" apiHomeLink="https://products.aspose.app/words/family" codeSamplesLink="https://github.com/aspose-words" liveDemosLink="https://products.aspose.app/words/family" docsLink="https://docs.aspose.com/words/net" installationsDocsLink="https://docs.aspose.com/words/net" nugetLink="https://www.nuget.org/packages/aspose.words" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/words/net" learnAsLink="https://docs.aspose.com/words/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="How to Edit FlatOpc File Using C#" %}}

 In order to edit FlatOpc file, we’ll use
 [Aspose.Words for .NET](https://products.aspose.com/words/net) 
 API which is a feature-rich, powerful and easy to use API for C# platform for any editor. Open
 [NuGet](https://www.nuget.org/packages/aspose.words) 
 package manager, search for
 **Aspose.Words** 
 and install. You may also use the following command from the Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Command" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Words

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Steps for Editing FlatOpc Files in C#" %}}

{{% blocks/products/pf/agp/text %}}

 A basic document editing with
 [Aspose.Words for .NET](https://products.aspose.com/words/net) 
 APIs can be done with just few lines of code.

{{% /blocks/products/pf/agp/text %}}

+  Design and Develop your editor.
+  Or use Aspose Editor by accessing its demo app using advanced WYSIWYG editor
+  Upload FlatOpc files to edit.
+  Modify the document with relevant changes.
+  Save document using Save() method.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Requirements" %}}

{{% blocks/products/pf/agp/text %}}

 Our APIs are supported on all major platforms and Operating Systems. Before executing the code below, please make sure that you have the following prerequisites on your system.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows or a compatible OS with .NET Framework, .NET Core, Windows Azure, Mono or Xamarin Platforms
-  Development environment like Microsoft Visual Studio
-  Aspose.Words for .NET DLL referenced in your project - Install from NuGet using the Download button above

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Edit FlatOpc Files - C#" offSpacer="" %}}

```cs
//while loading convert content into html data, Edit it and save using below code
public Response UpdateContents(string flatopcFileName, string htmldata, string outputType){
outputType = outputType.ToLower();
var foldername = Guid.NewGuid().ToString();
var fn = Path.GetFileNameWithoutExtension(flatopcFileName) + outputType;
var resultfile = AppSettings.OutputDirectory + foldername + "/" + fn;
Directory.CreateDirectory(Path.GetDirectoryName(resultfile));

try{
    switch (outputType){
        case ".html":
			File.WriteAllText(resultfile, htmldata);
            break;
        default:
            var lo = new HtmlLoadOptions()
            {
                LoadFormat = LoadFormat.Html,
                Encoding = Encoding.UTF8
            };
            Document doc;
            using (var stream = new MemoryStream(Encoding.UTF8.GetBytes(htmldata)))
                doc = new Document(stream, lo);
            doc.Save(resultfile);
            break;
    }
    return new Response(){
        FileName = HttpUtility.UrlEncode(fn),
        FolderName = foldername,
        StatusCode = 200
    };
}catch (Exception ex){  
    return new Response(){
        FileName = HttpUtility.UrlEncode(fn),
        FolderName = foldername,
        StatusCode = 500,
        Status = ex.Message
    };
}
}
//Whole Source Code available here https://github.com/aspose-words/Aspose.Words-for-.NET/blob/master/Demos/src/Aspose.Words.Live.Demos.UI/Controllers/AsposeWordsEditorController.cs

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="About Aspose.Words for .NET API" %}}

 Aspose.Words API can be used to load, view and convert Microsoft Word and OpenDocument Formats like DOC, DOCX, ODT to PDF, XPS, HTML and various other formats. You can also create new documents from scratch and save them in the supported formats. Aspose.Words is a standalone API that is suitable for server side and backend systems where high performance is required. It does not depend on any software like Microsoft or OpenOffice. ‎



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Online FlatOpc Editor Live Demos" sectionDescription="Edit FlatOpc documents right now by visiting our [Live Demos website](https://products.aspose.app/words/editor). The live demo has the following benefits" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download Aspose API." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Just upload your FlatOpc files, Use online editor for editing instantly." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Then save and download." >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="FlatOpc" readMoreLink="https://docs.fileformat.com/web/xml/" >}}
Office Open XML WordprocessingML stored in a flat XML file instead of a ZIP package.

        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}