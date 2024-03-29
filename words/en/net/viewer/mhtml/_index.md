---
title: View MHTML File Formats via .NET 
weight: 2700

description: Load, render and display MHTML documents using server side .NET library.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="MHTML File Viewer for .NET" h2="View MHTML in a browser without requiring Microsoft Word or Office Automation." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/words/aspose_words-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="MHTML" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="MHTML" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Words " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/words/aspose_words-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-words" liveDemosLink="https://products.aspose.app/words/family" docsLink="https://docs.aspose.com/words/net" installationsDocsLink="https://docs.aspose.com/words/net" nugetLink="https://www.nuget.org/packages/aspose.words" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/words/net" learnAsLink="https://docs.aspose.com/words/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="How to View MHTML File Using C#" %}}

 In order to view MHTML file, we’ll use
 [Aspose.Words for .NET](https://products.aspose.com/words/net) 
 API which is a feature-rich, powerful and easy to use API for C# platform to be used with any Viewer. Open
 [NuGet](https://www.nuget.org/packages/aspose.words) 
 package manager, search for
 Aspose.Words 
 and install. You may also use the following command from the Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Package Manager Console Command" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Words

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Steps to View MHTML via C#" %}}

{{% blocks/products/pf/agp/text %}}

 Developers can easily view MHTML file with just few lines of code.

{{% /blocks/products/pf/agp/text %}}

1.  Load MHTML file with an instance of Document class
1.  Call the Document.Save method
1.  Save MHTML file in HTML Fixed format with embedded resources
1.  Call Process.Start with path to resultant HTML to load in default browser

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Requirements" %}}

{{% blocks/products/pf/agp/text %}}

 Before integrating code,  make sure that you have the following prerequisites.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows or a compatible OS with .NET Framework, .NET Core, Windows Azure, Mono or Xamarin Platforms
-  Development environment like Microsoft Visual Studio
-  Aspose.Words for .NET referenced in your project

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="View MHTML file using C# example code" offSpacer="" %}}

```cs

string output = System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".html";
// load MHTML via an instance of Document
var document = new Document("template.mhtml");
// save in HTML Fixed format while embedding all resources
document.Save(output, new Saving.HtmlFixedSaveOptions()
{
    ExportEmbeddedCss = true,
    ExportEmbeddedFonts = true,
    ExportEmbeddedImages = true
}
);
// load resultant HTML in defualt browser
System.Diagnostics.Process.Start(output);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="" %}}

 .NET Words API can be used to load, view and convert Microsoft Word and OpenDocument Formats like DOC, DOCX, ODT to PDF, XPS, HTML and various other formats. You can also create new documents from scratch and save them in the supported formats. It is a standalone API that is suitable for server side and backend systems where high performance is required. It does not depend on any software like Microsoft or OpenOffice. ‎



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Free App to View MHTML" sectionDescription="Check our live demos to [View MHTML](https://products.aspose.app/words/viewer/mhtml) with following benefits." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write or compile code" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload MHTML file and hit the \"View\" button" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Download MHTML file from the link, if required" >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="MHTML" readMoreLink="https://docs.fileformat.com/web/mhtml/" >}}
Files with MHTML extension represent a web page archive format that can be created by a number of different applications. The format is known as archive format because it saves the web HTML code and associated resources in a single file. These resources include anything linked to the webpage such as images, applets, animations, audio files and so on. MHTML files can be opened in a variety of applications such as Internet Explorer and Microsoft Word. Microsoft Windows uses MHTML file format for recording scenarios of problems observed during the usage of any application on Windows that raises issues. The MHTML file format encodes the page contents similar to specifications defined in message/rfc822 which is plain text email related specifications. The actual specifications of the format are as detailed by RFC 2557.

        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Viewer Formats" subTitle="Using C#, One can also view many other file formats including." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/net/viewer/doc/" name="DOC" description="Microsoft Word Binary Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/net/viewer/docm/" name="DOCM" description="Microsoft Word 2007 Marco File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/net/viewer/docx/" name="DOCX" description="Office 2007+ Words Document" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/net/viewer/dot/" name="DOT" description="Microsoft Word Template Files" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/net/viewer/dotm/" name="DOTM" description="Microsoft Word 2007+ Template File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/net/viewer/dotx/" name="DOTX" description="Microsoft Word Template File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/net/viewer/html/" name="HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/net/viewer/md/" name="MD" description="Markdown Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/net/viewer/mobi/" name="MOBI" description="Open Ebook Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/net/viewer/odt/" name="ODT" description="OpenDocument Text File Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/net/viewer/ott/" name="OTT" description="OpenDocument Standard Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/net/viewer/pdf/" name="PDF" description="Portable Document Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/net/viewer/rtf/" name="RTF" description="Rich Text Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/net/viewer/txt/" name="TXT" description="Text Document" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}