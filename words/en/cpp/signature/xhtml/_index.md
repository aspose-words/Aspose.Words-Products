---
title: e-Sign XHTML Documents via C++ 
weight: 5210

description: C++ example code to eSgin XHTML documents on C++ Runtime Environment for Windows 32 bit, Windows 64 bit and Linux 64 bit.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="eSign XHTML Formats in C++" h2="Native and high performance XHTML document electronic signature using server-side Aspose.Words for C++ APIs, without the use of any software like Microsoft or Open Office, Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/words/aspose_words-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Words" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XHTML" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Words " subTitlepfName="for C++" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/words/aspose_words-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-words" liveDemosLink="https://products.aspose.app/words/family" docsLink="https://docs.aspose.com/words/cpp" installationsDocsLink="https://docs.aspose.com/words/cpp" nugetLink="https://www.nuget.org/packages/aspose.words" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/words/cpp" learnAsLink="https://docs.aspose.com/words/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="How to Digitally Sign XHTML File Using C++" %}}

 In order to electronically sign XHTML file, we’ll use
 [Aspose.Words for C++](https://products.aspose.com/words/cpp) 
 API which is a feature-rich, powerful and easy to use document manipulation and digital signature API for C++ platform. You can download its latest version directly, just open
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

{{% blocks/products/pf/agp/feature-section-col title="Steps for e-Signing XHTML Files in C++" %}}

{{% blocks/products/pf/agp/text %}}

 A basic document digital signature with
 [Aspose.Words for C++](https://products.aspose.com/words/cpp) 
 APIs can be done with just few lines of code. One can add electronic signature as drawing, text and images to multiple files. Moreover, eSigned documents can be saved as PDF, JPEG, HTML, OpenOffice and other formats.

{{% /blocks/products/pf/agp/text %}}

+  Create signature using CertificateHolder
+  Use DigitalSignatureUtil Sign (...) method for electronically signing

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Requirements" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Words for C++ supports on all major platforms and Operating Systems. Please make sure that you have the following prerequisites.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows or a compatible OS with C++ Runtime Environment for Windows 32 bit, Windows 64 bit and Linux 64 bit.
-  Aspose.Words for C++ DLL referenced in your project.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="e-Sign XHTML Files - C++" offSpacer="" %}}

```cs
System::SharedPtr<CertificateHolder> certHolder = CertificateHolder::Create(inputDataDir + u"signature.pfx", u"signature");
System::String outputPath = outputDataDir + u"SigningSignatureLine.SimpleDocumentSigning_out.xhtml";
DigitalSignatureUtil::Sign(inputDataDir + u"Document.Signed.xhtml", outputPath, certHolder);  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="About Aspose.Words for C++ API" %}}

 Aspose.Words API can be used to load, view and convert Microsoft Word and OpenDocument Formats like DOC, DOCX, ODT to PDF, XPS, HTML and various other formats. You can also create new documents from scratch and save them in the supported formats. Aspose.Words is a standalone API that is suitable for server side and backend systems where high performance is required. It does not depend on any software like Microsoft or OpenOffice. ‎



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Online XHTML eSignature Live Demos" sectionDescription="e-Sign XHTML documents right now by visiting our [Live Demos website](https://products.aspose.app/words/signature). The live demo has the following benefits" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download Aspose API." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Just upload your XHTML file." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" It will be electronically signed instantly." >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="XHTML" readMoreLink="https://docs.fileformat.com/web/xhtml/" >}}
The XHTML is a text based file format with markup in the XML, using a reformulation of HTML 4.0. These files are well suited to be open or viewed in a web browser. XHTML was designed to be more structured, less scripting, generic; using all the existing facilities of XML and more device independent. XHTML provides a generally worthwhile set of elements and attributes, with extension options in combination with style sheets. The attributes are used from the metadata attributes collection. XHTML provides flexibility and accessibility by subordinating all HTML presentation elements to style sheets. Style sheets are more versatile than these presentational elements.  Specifications for HTML 4.01, HTML5 and XHTML are being dynamically developed by the World Wide Web Consortium (W3C). 

        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Electronic Signature Formats" subTitle="Using C++, One can digitally sign easily of many other formats including" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/cpp/signature/doc/" name="DOC" description="Microsoft Word Binary Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/cpp/signature/docx/" name="DOCX" description="Office 2007+ Words Document" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/cpp/signature/dot/" name="DOT" description="Microsoft Word Template Files" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/cpp/signature/dotx/" name="DOTX" description="Microsoft Word Template File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/cpp/signature/html/" name="HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/cpp/signature/odt/" name="ODT" description="OpenDocument Text File Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/cpp/signature/ott/" name="OTT" description="OpenDocument Standard Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/cpp/signature/rtf/" name="RTF" description="Rich Text Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/cpp/signature/txt/" name="TXT" description="Text Document" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}