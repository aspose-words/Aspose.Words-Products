---
title: Split Microsoft Word Documents in C#
url: /net/splitter/
description: C# source codes that explains how to split Microsoft Word files into multiple files in Visual C#.NET applications
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Microsoft<sup>&reg;</sup> Word File Splitting via .NET" h2="Split Word document into different files using C# code within .NET based applications" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Word Library](/words/net/) is capable to split single word document into multiple files within .NET based applications. Developers can split word document data present in various sections or pages. Depending on scenarios, managing code to split documents by headings, by section, page by page or using a page range is quiet easy. API provides the [DocumentSplitCriteria](https://apireference.aspose.com/words/net/aspose.words.saving/documentsplitcriteria) enumeration having members as PageBreak, ColumnBreak, SectionBreak and HeadingParagraph for defining the splitting criteria. Moreover, one can split the document at page breaks and heading paragraphs in the same export operation. If there is need of splitting a document by a specific level of heading paragraphs, like heading 1, 2 and 3, API provides [DocumentSplitHeadingLevel](https://apireference.aspose.com/words/net/aspose.words.saving/htmlsaveoptions/properties/documentsplitheadinglevel) property. The output will be divided by paragraphs formatted with the specified heading level.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Split Micrsoft Word Documents by Section" %}}

Section breaks are used for splitting into multiple sections and it may be composed of a single page, a range of pages, or the whole document. To split by sections process is, Create the [Document](https://apireference.aspose.com/words/net/aspose.words/document) class object to load the file. Iterate through page sections via [Document.Sections](https://apireference.aspose.com/words/net/aspose.words/document/properties/sections) property and Clone the section into a new [Section](https://apireference.aspose.com/words/net/aspose.words/section) object.  Create a new Document object and add the section into it via Document.Sections.Add(Section) method. Finally save the documents using Save method.

{{% blocks/products/pf/feature-page-code h3="C# Code to Split Word Files by Section" %}}

{{< gist "aspose-com-gists" "c7cafec957d110f5c10270d77195a36b" "split-word-document-section.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter">}}

{{% blocks/products/pf/feature-page-section  h2="Page by Page Word Files Splitting" %}}

There is need of page by page splitting when each page represent a specific unique data such student fee challan, invoices or receipts. API provides DocumentPageSplitter helper class to deal the page by page scenario. Process is, use the Document class to load the file. Create DocumentPageSplitter class instance and initialize it with the Document object created. Loop throudh the document’s pages and get each page into a new Document object using DocumentPageSplitter.GetDocumentOfPage(int PageIndex) method. Finally save each document using Save() method.

{{% blocks/products/pf/feature-page-code h3="C# Code to Split Word File Page by Page" %}}

{{< gist "aspose-com-gists" "c7cafec957d110f5c10270d77195a36b" "split-word-document-page.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% blocks/products/pf/feature-page-code h3="C# Code to Split Word Documents by Page Range" %}}

{{< gist "aspose-com-gists" "c7cafec957d110f5c10270d77195a36b" "split-word-document-page-range.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}
