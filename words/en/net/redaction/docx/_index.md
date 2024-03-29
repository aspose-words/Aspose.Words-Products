---
title: Search and replace text in DOCX document via .NET 
weight: 2110

description: C# sample code to redact sensitive information in Microsoft Word DOCX file using server side .NET library.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Redact DOCX Formats in C#" h2="Native and high performance DOCX document sensitive redaction information using server-side .NET APIs, without the use of any software like Microsoft or Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/words/aspose_words-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="DOCX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Words " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/words/aspose_words-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-words" liveDemosLink="https://products.aspose.app/words/family" docsLink="https://docs.aspose.com/words/net" installationsDocsLink="https://docs.aspose.com/words/net" nugetLink="https://www.nuget.org/packages/aspose.words" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/words/net" learnAsLink="https://docs.aspose.com/words/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="How to Redact DOCX File Using C#" %}}

 In order to redact DOCX file, we’ll use
 [Aspose.Words for .NET](https://products.aspose.com/words/net) 
 API which is a feature-rich, powerful and easy to use document manipulation API for C# platform. Open
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

{{% blocks/products/pf/agp/feature-section-col title="Steps to Redact DOCX Files in C#" %}}

{{% blocks/products/pf/agp/text %}}

 A basic document search and replace text in contents, comments or metadata using API can be done with just few lines of code. Redact sensitive information through search and replace text in contents, comments or metadata in Word documents.

{{% /blocks/products/pf/agp/text %}}

+  Load DOCX file.
+  Create FindReplaceOptions object.
+  Set Search Options
+  Highlight phrases using Regex.
+  Use Replace method with relevant options.
+  Save document.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Requirements" %}}

{{% blocks/products/pf/agp/text %}}

 Our APIs are supported on all major platforms and Operating Systems. Before executing the code below, please make sure that you have the following prerequisites on your system.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows or a compatible OS with .NET Framework, .NET Core, Windows Azure, Mono or Xamarin Platforms
-  Development environment like Microsoft Visual Studio
-  Aspose.Words for .NET DLL referenced in your project - Install from NuGet using the Download button above

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Redact DOCX Files - C#" offSpacer="" %}}

```cs
string fileName = "TestFile.doc";

Document doc = new Document(dataDir + fileName);

FindReplaceOptions options = new FindReplaceOptions();
options.ReplacingCallback = new ReplaceEvaluatorFindAndHighlight();
options.Direction = FindReplaceDirection.Backward;

// We want the "your document" phrase to be highlighted.
Regex regex = new Regex("your document", RegexOptions.IgnoreCase);
doc.Range.Replace(regex, "", options);

dataDir = dataDir + RunExamples.GetOutputFilePath(fileName);
// Save the output document.
doc.Save(dataDir);

// For ReplaceEvaluatorFindAndHighlight class check the detail here 
//https://docs.aspose.com/words/net/find-and-replace/#how-to-find-and-highlight-text

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="" %}}

 .NET Words API can be used to load, view and convert Microsoft Word and OpenDocument Formats like DOC, DOCX, ODT to PDF, XPS, HTML and various other formats. You can also create new documents from scratch and save them in the supported formats. It is a standalone API that is suitable for server side and backend systems where high performance is required. It does not depend on any software like Microsoft or OpenOffice. ‎



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Online DOCX Redaction Live Demos" sectionDescription="Search and replace text in contents, comments or metadata in DOCX documents right now by visiting our [Live Demos website](https://products.aspose.app/words/redaction). The live demo has the following benefits" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download Aspose API." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your DOCX files." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" It will be redacted instantly." >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="DOCX" readMoreLink="https://docs.fileformat.com/word-processing/docx/" >}}
DOCX is a well-known format for Microsoft Word documents. Introduced from 2007 with the release of Microsoft Office 2007, the structure of this new Document format was changed from plain binary to a combination of XML and binary files. Docx files can be opened with Word 2007 and lateral versions but not with the earlier versions of MS Word which support DOC file extensions. 

        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Redaction Formats" subTitle="Using C#, one can easily redact different formats including." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/net/redaction/doc/" name="DOC" description="Microsoft Word Binary Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/net/redaction/dot/" name="DOT" description="Microsoft Word Template Files" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/net/redaction/dotx/" name="DOTX" description="Microsoft Word Template File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/net/redaction/html/" name="HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/net/redaction/md/" name="MD" description="Markdown Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/net/redaction/mhtml/" name="MHTML" description="Web Page Archive Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/net/redaction/odt/" name="ODT" description="OpenDocument Text File Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/net/redaction/ott/" name="OTT" description="OpenDocument Standard Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/net/redaction/rtf/" name="RTF" description="Rich Text Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/net/redaction/txt/" name="TXT" description="Text Document" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/net/redaction/xhtml/" name="XHTML" description="XML Text Based Markup" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}