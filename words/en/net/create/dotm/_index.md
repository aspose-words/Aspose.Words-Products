---
title: Create DOTM Files via C# 
weight: 7690

description: C# Sample code for generating DOTM documents. Use this code for creating Word DOTM files within VB.NET, Asp.NET or any .NET based application.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Create DOTM Documents via C#" h2="Native and high performance Microsoft Word DOTM files creation using server side .NET APIs." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/words/aspose_words-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PDF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DOTM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Words " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/words/aspose_words-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-words" liveDemosLink="https://products.aspose.app/words/family" docsLink="https://docs.aspose.com/words/net" installationsDocsLink="https://docs.aspose.com/words/net" nugetLink="https://www.nuget.org/packages/aspose.words" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/words/net" learnAsLink="https://docs.aspose.com/words/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="" %}}

 Generating MS Word DOTM file dynamically within running application is easy. In order to create DOTM documents from scratch without requiring MS Office, we’ll use
 [Aspose.Words for .NET](https://products.aspose.com/words/net) 
 API that offers different features for document creation, manipulation and conversion using .NET platform. 
{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="How to Create DOTM via C#" %}}

{{% blocks/products/pf/agp/text %}}

 It is easy for the developers to creat, load, modify and convert DOTM files within running Word Automation applications for data processing in just a few lines of code.

{{% /blocks/products/pf/agp/text %}}

1.  Include the namespace in your class file
1.  Create a Document class object.
1.  Create [DocumentBuilder class](https://apireference.aspose.com/words/net/aspose.words/documentbuilder) object and initialize it with the Document object.
1.  Update elements using the DocumentBuilder object.
1.  Save the file using Save(.) method.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Requirements" %}}

{{% blocks/products/pf/agp/text %}}

 Just make sure that system have Microsoft Windows or a compatible OS with .NET Framework, .NET Core, Windows Azure, Mono or Xamarin Platforms as well as development environment like Microsoft Visual Studio. 

{{% /blocks/products/pf/agp/text %}}

- Install from command line as <code>nuget install Aspose.Words</code> or via Package Manager Console of Visual Studio with <code>Install-Package Aspose.Words</code>.
- Alternatively, get the offline MSI installer or all DLLs in a ZIP file from <a href="https://downloads.aspose.com/words/net">downloads</a>

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Following source code shows how to create a Word DOTM file using C#." offSpacer="" %}}

```cs
Document dotm = new Document();
DocumentBuilder bldr = new DocumentBuilder(dotm);

// Define relevant font formatting
Font fnt = bldr.Font;
fnt.Size = 32;
fnt.Bold = true;
fnt.Color = System.Drawing.Color.Black;
fnt.Name = "Arial";
fnt.Underline = Underline.Single;

// Insert text
bldr.Writeln("This is the first page.");
bldr.Writeln();

// Change formatting for next elements.
fnt.Underline = Underline.None;
fnt.Size = 10;
fnt.Color = System.Drawing.Color.Blue;

bldr.Writeln("This following is a table");
// Insert a table
Table table = bldr.StartTable();
// Insert a cell
bldr.InsertCell();
// Use fixed column widths.
table.AutoFit(AutoFitBehavior.AutoFitToContents);
bldr.CellFormat.VerticalAlignment = CellVerticalAlignment.Center;
bldr.Write("row one cell one");
// Insert a cell
bldr.InsertCell();
bldr.Write("row one cell two");
bldr.EndRow();
bldr.InsertCell();
bldr.Write("row two cell one");
bldr.InsertCell();
bldr.Write("row two cell two");
bldr.EndRow();
bldr.EndTable();
bldr.Writeln();

// Insert image
bldr.InsertImage("image.png");
// Insert page break 
bldr.InsertBreak(BreakType.PageBreak);             
// Elements after page break will be inserted to next page.

// Save it to get the created one
dotm.Save("Document.dotm"); 

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<!-- aboutfile Starts -->

     
     {{% blocks/products/pf/agp/content h2="" %}}

A Document Processing Library to perform a wide range of document management and manipulation tasks including DOTM generation, editing, conversion, rendering and printing. .NET Word API supports all of word-processing formats as well as allows exporting or **converting DOTM to PDF**, HTML, fixed-layout and most commonly used image & multimedia formats.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="DOTM" readMoreLink="https://docs.fileformat.com/word-processing/dotm/" >}}
A file with DOTM extension represents template file created with Microsoft Word 2007 or higher. It is similar to the popular DOCX file format other than it retains the user defined settings for reuse in case of creating new documents. Such documents are more often used in offices where a standard template file is generated with settings like page information, margins, default layout and macros, and is used to create new documents from it when required. DOTM files, however, save macros, that are a series of commands in the form of recorded actions for automatic completion of a task. This helps save time in carrying out actions that are repeated in completion of a task.

        {{< /blocks/products/pf/agp/about-file-text >}}

     {{< /blocks/products/pf/agp/about-file-section >}}     

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Document Generation" subTitle="You can also create other Microsoft Words file formats including few listed below." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/net/create/doc/" name="DOC" description="Microsoft Word Binary Format" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/net/create/docx/" name="DOCX" description="Office 2007+ Word Document" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/net/create/rtf/" name="RTF" description="Rich Text Format" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/net/create/dot/" name="DOT" description="Microsoft Word Template Files" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/net/create/dotx/" name="DOTX" description="Microsoft Word Template File " >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/net/create/dotm/" name="DOTM" description="Microsoft Word 2007+ Template File" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/net/create/docm/" name="DOCM" description="Microsoft Word 2007 Marco File" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/net/create/odt/" name="ODT" description="OpenDocument Text File Format" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}