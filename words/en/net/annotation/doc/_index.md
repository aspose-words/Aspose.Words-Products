---
title: Remove DOC Annotation via .NET 
weight: 8180

description: Delete Microsoft Word DOC format annotations using server side .NET library
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Add, Edit & Delete Annotation from DOC via C#" h2="Build your own .NET apps to manipulate comments & authors in Microsoft Word DOC files using server-side APIs." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/words/aspose_words-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="DOC" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Words " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/words/aspose_words-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-words" liveDemosLink="https://products.aspose.app/words/family" docsLink="https://docs.aspose.com/words/net" installationsDocsLink="https://docs.aspose.com/words/net" nugetLink="https://www.nuget.org/packages/aspose.words" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/words/net" learnAsLink="https://docs.aspose.com/words/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="How to Annotate DOC File Using C#" %}}

 In order to annotate DOC file, we’ll use
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

{{% blocks/products/pf/agp/feature-section-col title="Manipulate Annotation of DOC via C#" %}}

{{% blocks/products/pf/agp/text %}}

 Developers can easily handle DOC annotation and integrate the few lines code within appplications.

{{% /blocks/products/pf/agp/text %}}

+  Create a new Document object
+  Create Comment and append to the Document object
+  Use AddReply to add replies to the comment
+  Remove replies one by one or use RemoveAllReplies to delete all

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Requirements" %}}

{{% blocks/products/pf/agp/text %}}

 Before integrating the code,  make sure that you have the following prerequisites.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows or a compatible OS with .NET Framework, .NET Core, Windows Azure, Mono or Xamarin Platforms.
-  Development environment like Microsoft Visual Studio.
-  Aspose.Words for .NET DLL referenced in your project.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Delete Annotations from DOC - C#" offSpacer="" %}}

```cs
// load the DOC with an instance of Document class
var document = new Document("template.doc");

// add a comment to the document
Comment comment = new Comment(document, "John Doe", "J.D.", DateTime.Now);
comment.SetText("My comment.");
document.FirstSection.Body.FirstParagraph.AppendChild(comment);

// add replies to comments
comment.AddReply("Joe Bloggs", "J.B.", DateTime.Now, "New reply");
comment.AddReply("John Doe", "J.D.", DateTime.Now, "Another reply");

// check reply count
Assert.AreEqual(2, comment.Replies.Count());

// individually remove replies from a comment 
comment.RemoveReply(comment.Replies[0]);
// check reply count
Assert.AreEqual(1, comment.Replies.Count());

// remove all of the comment replies at once
comment.RemoveAllReplies();

Assert.AreEqual(0, comment.Replies.Count());  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="" %}}

 .NET Words API can be used to load, view and convert Microsoft Word and OpenDocument Formats like DOC, DOCX, ODT to PDF, XPS, HTML and various other formats. You can also create new documents from scratch and save them in the supported formats. It is a standalone API that is suitable for server side and backend systems where high performance is required. It does not depend on any software like Microsoft or OpenOffice. ‎



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Remove Annotation from DOC via Online App" sectionDescription="Delete DOC document annotations right now by visiting our [Live Demos website](https://products.aspose.app/words/annotation). The live demo has the following benefits" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your DOC file and hit the \"Remove\" button" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Instantly get the download link for the resultant file" >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="DOC" readMoreLink="https://docs.fileformat.com/word-processing/doc/" >}}
Files with .doc extension represent documents generated by Microsoft Word or other word processing documents in binary file format. The extension was initially used for plain text documentation on several different operating systems. It can contain several different types of data such as images, formatted as well as plain text, graphs, charts, embedded objects, links, pages, page formatting, print settings and a lot others. The format was popular for all sorts of documentation due to the variety of options it offers to users for writing manuals, proposals, specifications, resumes, articles or any similar documents. The updated version of DOC is DOCX which is based on Office OpenXML whose specifications are openly available.

        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Annotation Formats" subTitle="Using C#, one can easily annotate other formats including." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/net/annotation/docx/" name="DOCX" description="Office 2007+ Words Document" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/net/annotation/dot/" name="DOT" description="Microsoft Word Template Files" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/net/annotation/dotx/" name="DOTX" description="Microsoft Word Template File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/net/annotation/odt/" name="ODT" description="OpenDocument Text File Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/net/annotation/ott/" name="OTT" description="OpenDocument Standard Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/net/annotation/rtf/" name="RTF" description="Rich Text Format" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}