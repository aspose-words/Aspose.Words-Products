---
title: Search and replace text in HTML document via C++ 
weight: 560
url: /cpp/redaction/html/ 
description: Try our On-Premise document redaction APIs to redact sensitive information in HTML file on C++ Runtime Environment for Windows 32 bit, Windows 64 bit and Linux 64 bit.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Redact HTML Formats in C++" h2="Native and high performance HTML document sensitive redaction information using server-side Aspose.Words for C++ APIs, without the use of any software like Microsoft or Adobe PDF." logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/words/272x272/aspose_words-for-cpp.png" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Words" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="HTML" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Words " subTitlepfName="for C++" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/words/272x272/aspose_words-for-cpp.png" apiHomeLink="https://products.aspose.app/words/family" codeSamplesLink="https://github.com/aspose-words" liveDemosLink="https://products.aspose.app/words/family" docsLink="https://docs.aspose.com/words/cpp" installationsDocsLink="https://docs.aspose.com/words/cpp" nugetLink="https://www.nuget.org/packages/aspose.words" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/words/cpp" learnAsLink="https://docs.aspose.com/words/cpp" apiReference="" >}}

{{% blocks/products/pf/agp/content h2="How to Redact HTML File Using C++" %}}

 In order to redact HTML file, we’ll use
 [Aspose.Words for C++](https://products.aspose.com/words/cpp) 
 API which is a feature-rich, powerful and easy to use document redaction API for C++ platform. You can download its latest version directly, just open
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

{{% blocks/products/pf/agp/feature-section-col title="Steps to Redact HTML Files in C++" %}}

{{% blocks/products/pf/agp/text %}}

 A basic document search and replace text in contents, comments or metadata with
 [Aspose.Words for C++](https://products.aspose.com/words/cpp) 
 APIs can be done with just few lines of code. Redact sensitive information through search and replace text in contents, comments or metadata in Word documents.

{{% /blocks/products/pf/agp/text %}}

+  Load HTML Document..
+  Define FindReplaceOptions.
+  Set Regular Expression Pattern
+  Use Replace method with Regex.
+  Save document.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Requirements" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Words for C++ supports on all major platforms and Operating Systems. Please make sure that you have the following prerequisites.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows or a compatible OS with C++ Runtime Environment for Windows 32 bit, Windows 64 bit and Linux 64 bit.
-  Aspose.Words for C++ DLL referenced in your project.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Redact HTML Files - C++" offSpacer="" %}}

```cs
// Load HTML document
System::SharedPtr<Document> html = System::MakeObject<Document>(u"Document.html");

// Create find and replace options
System::SharedPtr<FindReplaceOptions> options = System::MakeObject<FindReplaceOptions>();

// Find and replace the text
html->get_Range()->Replace(System::MakeObject<System::Text::RegularExpressions::Regex>(u"[s|m]ad"), u"bad", options);

// Save the updated document 
html->Save(u"updated.html");

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="About Aspose.Words for C++ API" %}}

 Aspose.Words API can be used to load, view and convert Microsoft Word and OpenDocument Formats like DOC, DOCX, ODT to PDF, XPS, HTML and various other formats. You can also create new documents from scratch and save them in the supported formats. Aspose.Words is a standalone API that is suitable for server side and backend systems where high performance is required. It does not depend on any software like Microsoft or OpenOffice. ‎



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="Online HTML Redaction Live Demos" sectionDescription="Search and replace text in contents, comments or metadata in HTML documents right now by visiting our [Live Demos website](https://products.aspose.app/words/redaction). The live demo has the following benefits" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your HTML files." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" It will be redacted instantly." >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/about-file-text fileFormat="HTML" readMoreLink="https://docs.fileformat.com/web/html/" >}}
HTML (Hyper Text Markup Language) is the extension for web pages created for display in browsers. Known as language of the web, HTML has evolved with requirements of new information requirements to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from server, where these are hosted, or can be loaded from local system as well. Each HTML page is made up of HTML elements such as forms, text, images, animations, links, etc. These elements are represented by tags such as img, a, p and several others where each tag has start and end. It can also embed applications written in scripting languages such as JavaScript and Style Sheets (CSS) for overall layout representation. Read More

    {{< /blocks/products/pf/agp/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}