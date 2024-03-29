---
title: Search TXT document without opening via C++ 
weight: 5900

description: C++ example code to search words with pattern in TXT file on C++ Runtime Environment for Windows 32 bit, Windows 64 bit and Linux 64 bit.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Search TXT Formats in C++" h2="Native and high performance TXT document search using server-side Aspose.Words for C++ APIs, without the use of any software like Microsoft or Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/words/aspose_words-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Words" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="TXT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Words " subTitlepfName="for C++" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/words/aspose_words-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-words" liveDemosLink="https://products.aspose.app/words/family" docsLink="https://docs.aspose.com/words/cpp" installationsDocsLink="https://docs.aspose.com/words/cpp" nugetLink="https://www.nuget.org/packages/aspose.words" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/words/cpp" learnAsLink="https://docs.aspose.com/words/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="How to Search TXT File Using C++" %}}

 In order to search TXT file, we’ll use
 [Aspose.Words for C++](https://products.aspose.com/words/cpp) 
 API which is a feature-rich, powerful and easy to use document searching API for C++ platform. You can download its latest version directly, just open
 [NuGet](https://www.nuget.org/packages/aspose.words) 
 package manager, search for
 **Aspose.Words.Cpp** 
 and install. You may also use the following command from the Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Command" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Words.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Steps to Search TXT Files in C++" %}}

{{% blocks/products/pf/agp/text %}}

 A basic document search using Aspose.Words APIs can be done with just few lines of code.

{{% /blocks/products/pf/agp/text %}}

+  Load TXT file by instantiating Document Class object.
+  Use get\_Range()->Replace method with relevant pattern and parameters.
+  Save TXT file using Save() method.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Requirements" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Words for C++ supports on all major platforms and Operating Systems. Please make sure that you have the following prerequisites.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows or a compatible OS with C++ Runtime Environment for Windows 32 bit, Windows 64 bit and Linux 64 bit.
-  Aspose.Words for C++ DLL referenced in your project.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Search TXT Files - C++" offSpacer="" %}}

```cs
// Load TXT document
System::SharedPtr<Document> txt = System::MakeObject<Document>(u"sourceFile.txt");

// Find and replace the text
txt->get_Range()->Replace(u"sad", u"bad", System::MakeObject<FindReplaceOptions>(FindReplaceDirection::Forward));

// Save the document 
txt->Save(u"output.txt");  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="About Aspose.Words for C++ API" %}}

 Aspose.Words API can be used to load, view and convert Microsoft Word and OpenDocument Formats like DOC, DOCX, ODT to PDF, XPS, HTML and various other formats. You can also create new documents from scratch and save them in the supported formats. Aspose.Words is a standalone API that is suitable for server side and backend systems where high performance is required. It does not depend on any software like Microsoft or OpenOffice. ‎



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="Online TXT Search Live Demos" sectionDescription="Search text, words, phrases within TXT documents right now by visiting our [Live Demos website](https://products.aspose.app/words/search). The live demo has the following benefits" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Just upload your TXT files." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Search result appears instantly." >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/about-file-text fileFormat="TXT " readMoreLink="https://docs.fileformat.com/word-processing/txt/" >}}
A file with .TXT extension represents a text document that contains plain text in the form of lines. Paragraphs in a text document are recognized by carriage returns and are used for better arrangement of file contents. A standard text document can be opened in any text editor or word processing application on different operating systems. All the text contained in such a file is in human-readable format and represented by sequence of characters. 

    {{< /blocks/products/pf/agp/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Search Documents" subTitle="Using C++, one can also search other files including." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/cpp/search/doc/" name="DOC" description="Microsoft Word Binary Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/cpp/search/docx/" name="DOCX" description="Office 2007+ Words Document" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/cpp/search/html/" name="HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/cpp/search/mhtml/" name="MHTML" description="Web Page Archive Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/cpp/search/odt/" name="ODT" description="OpenDocument Text File Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/cpp/search/ott/" name="OTT" description="OpenDocument Standard Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/cpp/search/rtf/" name="RTF" description="Rich Text Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/cpp/search/xhtml/" name="XHTML" description="XML Text Based Markup" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}