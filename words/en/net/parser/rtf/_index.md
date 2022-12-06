---
title: Extract text and images from RTF document via .NET 
weight: 9410

description: C# sample code to extract text and images from Microsoft Word RTF file using server side .NET library.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Parse RTF Formats in C#" h2="Native and high performance RTF document parsing using server-side .NET APIs, without the use of any software like Microsoft or Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/words/aspose_words-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="RTF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Words " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/words/aspose_words-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-words" liveDemosLink="https://products.aspose.app/words/family" docsLink="https://docs.aspose.com/words/net" installationsDocsLink="https://docs.aspose.com/words/net" nugetLink="https://www.nuget.org/packages/aspose.words" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/words/net" learnAsLink="https://docs.aspose.com/words/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="How to Parse RTF File Using C#" %}}

 In order to parse RTF file, we’ll use
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

{{% blocks/products/pf/agp/feature-section-col title="Steps to Parse RTF Files in C#" %}}

{{% blocks/products/pf/agp/text %}}

 Developers can easily **parse Microsoft Word RTF files** by following the steps.

{{% /blocks/products/pf/agp/text %}}

+  Load RTF document.
+  Select a para.
+  Extract content into arraylist.
+  Loop through each and remove from the specific index and reverse.
+  Save document

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Requirements" %}}

{{% blocks/products/pf/agp/text %}}

 Before integrating the code,  make sure that you have the following prerequisites on your system.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows or a compatible OS with .NET Framework, .NET Core, Windows Azure, Mono or Xamarin Platforms
-  Development environment like Microsoft Visual Studio
-  Aspose.Words for .NET DLL referenced in your project - Install from NuGet using the Download button above

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Parse RTF Files - C#" offSpacer="" %}}

```cs
//Extract Content Between Different Types of Nodes
    string fileName = "TestFile.rtf";
    Document rtf = new Document(dataDir + fileName);
    
    Paragraph startPara = (Paragraph)rtf.LastSection.GetChild(NodeType.Paragraph, 2, true);
    Table endTable = (Table)rtf.LastSection.GetChild(NodeType.Table, 0, true);
    
    // Extract the content between these nodes in the document. Include these markers in the extraction.
    ArrayList extractedNodes = Common.ExtractContent(startPara, endTable, true);
    
    // Lets reverse the array to make inserting the content back into the document easier.
    extractedNodes.Reverse();
    
    while (extractedNodes.Count > 0)
    {
        // Insert the last node from the reversed list 
        endTable.ParentNode.InsertAfter((Node)extractedNodes[0], endTable);
        // Remove this node from the list after insertion.
        extractedNodes.RemoveAt(0);
    }
    dataDir = dataDir + RunExamples.GetOutputFilePath(fileName);
    // Save the generated document to disk.
    rtf.Save(dataDir);  

    

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="" %}}

 .NET Words API can be used to load, view and convert Microsoft Word and OpenDocument Formats like DOC, DOCX, ODT to PDF, XPS, HTML and various other formats. You can also create new documents from scratch and save them in the supported formats. It is a standalone API that is suitable for server side and backend systems where high performance is required. It does not depend on any software like Microsoft or OpenOffice. ‎



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Online RTF Parser Live Demos" sectionDescription="Extract text and images from RTF documents right now by visiting our [Live Demos website](https://products.aspose.app/words/parser). The live demo has the following benefits" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download Aspose API." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your RTF files." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" It will be parsed instantly." >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="RTF" readMoreLink="https://docs.fileformat.com/word-processing/rtf/" >}}
Introduced and documented by Microsoft, the Rich Text Format (RTF) represents a method of encoding formatted text and graphics for use within applications. The format facilitates cross-platform document exchange with other Microsoft Products, thus serving the purpose of interoperability. This capability makes it a standard of data transfer between word processing software and, hence, contents can be transferred from one operating system to another without losing document formatting. The file format specifications are available by Microsoft for public download and can be referred to from developer's perspective. 

        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Parsing Formats" subTitle="Using C#, one can easily parse other formats including." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/net/parser/doc/" name="DOC" description="Microsoft Word Binary Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/net/parser/docx/" name="DOCX" description="Office 2007+ Words Document" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/net/parser/dot/" name="DOT" description="Microsoft Word Template Files" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/net/parser/dotx/" name="DOTX" description="Microsoft Word Template File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/net/parser/html/" name="HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/net/parser/mhtml/" name="MHTML" description="Web Page Archive Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/net/parser/odt/" name="ODT" description="OpenDocument Text File Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/net/parser/ott/" name="OTT" description="OpenDocument Standard Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/net/parser/xhtml/" name="XHTML" description="XML Text Based Markup" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}