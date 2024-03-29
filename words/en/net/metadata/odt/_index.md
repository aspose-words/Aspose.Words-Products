---
title: View or Edit ODT Files Metadata via .NET 
weight: 5520

description: C# sample code to edit or view Microsoft Word ODT format metadata using server side .NET library.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Extract ODT Metadata via .NET" h2="Build your own .NET apps to add, edit, remove or extract metadata from Microsoft Word ODT files using server-side APIs." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/words/aspose_words-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODT" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Words " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/words/aspose_words-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-words" liveDemosLink="https://products.aspose.app/words/family" docsLink="https://docs.aspose.com/words/net" installationsDocsLink="https://docs.aspose.com/words/net" nugetLink="https://www.nuget.org/packages/aspose.words" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/words/net" learnAsLink="https://docs.aspose.com/words/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="How to Extract ODT Metadata Using C#" %}}

 In order to extract ODT metadata, we’ll use
 [Aspose.Words for .NET](https://products.aspose.com/words/net) 
 API which is a feature-rich, powerful and easy to use document metadata API for C# platform. Open
 [NuGet](https://www.nuget.org/packages/aspose.words) 
 package manager, search for
 Aspose.Words 
 and install. You may also use the following command from the Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Command" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Words

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Steps to Extract Metadata of ODT via C#" %}}

{{% blocks/products/pf/agp/text %}}

 Extract & manipulate system or built-in properties including title, author name, statistics as well as user-defined or custom metadata stored as as name-value pairs.

{{% /blocks/products/pf/agp/text %}}

+  Load ODT with an instance of Document
+  Get the BuiltInDocumentProperties collection of Document object
+  Iterate over the collection
+  Display Property Name, Type & Value

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Requirements" %}}

{{% blocks/products/pf/agp/text %}}

 Before integrating the code,  make sure that you have the following prerequisites.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows or a compatible OS with .NET Framework, .NET Core, Windows Azure, Mono or Xamarin Platforms.
-  Development environment like Microsoft Visual Studio.
-  Aspose.Words for .NET referenced in your project.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Extract Metadata of ODT - C#" offSpacer="" %}}

```cs

// load ODT file with an instance of Document
var document = new Document("template.odt");
// iterate over the BuiltInDocumentProperties collection
foreach (Aspose.Words.Properties.DocumentProperty property in document.BuiltInDocumentProperties)
{
    Console.WriteLine(property.Name);
    Console.WriteLine($"\tType:\t{property.Type}");

    // some properties may store multiple values
    if (property.Value is Array)
    {
        foreach (object value in property.Value as Array)
            Console.WriteLine($"\tValue:\t\"{value}\"");
    }
    else
    {
        Console.WriteLine($"\tValue:\t\"{property.Value}\"");
    }
}  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="" %}}

 .NET Words API can be used to load, view and convert Microsoft Word and OpenDocument Formats like DOC, DOCX, ODT to PDF, XPS, HTML and various other formats. You can also create new documents from scratch and save them in the supported formats. It is a standalone API that is suitable for server side and backend systems where high performance is required. It does not depend on any software like Microsoft or OpenOffice. ‎



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Extract Metadata of ODT via Online App" sectionDescription="View & edit Metadata to ODT documents by using our [Live Demos](https://products.aspose.app/words/metadata) with following benefits." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your ODT file & edit document properties" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Instantly get the download link for the resultant file" >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="ODT" readMoreLink="https://docs.fileformat.com/word-processing/odt/" >}}
ODT files are type of documents created with word processing applications that are based on OpenDocument Text File format. These are created with word processor applications such as free OpenOffice Writer and can hold content such as text, images, objects and styles. The ODT file is to Writer word processor what the DOCX is to Microsoft Word. Several applications including Google Docs and Google's web-based word processor included with Google Drive can open the ODT files for editing. Microsoft Word can also open ODT files and save it in to other formats such as DOC and DOCX.

        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Metadata Formats" subTitle="Using C#, One can also manipulate metadata of many other formats including." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/net/metadata/doc/" name="DOC" description="Microsoft Word Binary Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/net/metadata/docx/" name="DOCX" description="Office 2007+ Words Document" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/net/metadata/dot/" name="DOT" description="Microsoft Word Template Files" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/net/metadata/dotx/" name="DOTX" description="Microsoft Word Template File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/net/metadata/rtf/" name="RTF" description="Rich Text Format" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}