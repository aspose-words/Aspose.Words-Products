---
title: Microsoft Word Document Conversion to Multiple Formats using C# 
url: /net/conversion/
description: Convert Microsoft Word files to different formats including PDF, HTML and image formats on .NET Framework, .NET Core, Windows Azure, Mono or Xamarin Platforms.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Microsoft<sup>&reg;</sup> Word Document Conversion using .NET Platform" h2="C# Source Codes for 200+ conversions to convert files and images to Word, PDF, JPG, HTML and other formats." >}}

{{% blocks/products/pf/feature-page-summary %}}

It is easy for the developers to convert Word files with speed and accuracy. Get the results within no time. Converted file content and formatting will be the same as of the original document. Automate your document management systems by utilizing the highest quality optimized code for professional conversions of to and from any Microsoft Office<sup>&reg;</sup>, OpenOffice<sup>&trade;</sup> formats. Aspose provides stand alone .NET based APIs for integration without the need of additional software like Microsoft Office, OpenOffice or Adobe Acrobat. 

If any existing document processing system needs the conversion feature or someone building the new system with this feature, APIs are the right soultion for converting Word, Excel, PDF, PowerPoint files to many popular formats. Just integrate the API source code within the system and get the benefits of all features including document conversion, merging etc.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Inter Conversion Of Microsoft Word Formats via C#" %}}
Whenever there is need to automate the inter conversion of Microsoft<sup>&reg;</sup> Words format. Word coverter API's two lines code can do the whole process. Load the source file using [Document class](https://apireference.aspose.com/words/net/aspose.words/document) and calling the [Save method](https://apireference.aspose.com/words/net/class/aspose.words.saving.save_output_parameters/) of same class by specifying the output parameters. 
{{% blocks/products/pf/feature-page-code h3="C# Code for DOC to DOCX Conversion" %}}

```cs
// Load source Word file
Document doctodocx = new Document("sourceFile.doc");

// Save into the desired Word format
doctodocx.Save("csharp-doc-to.docx", SaveFormat.Docx);   
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="doc-to-docx docx-to-doc docm-to-docx doc-to-txt odt-to-docm ott-to-dotx rtf-to-docx txt-to-docm doc-to-odt docx-to-ott" >}}


{{% blocks/products/pf/feature-page-section  h2="C# Word to PDF Conversion" %}}
Word to PDF conversion is common case due to its sharing nature. Although Microsoft Word<sup>&reg;</sup> provides the facility of conversion, but whenever it is need to do it programmatically without having Microsoft Office installed then C# Microsoft Word API can do it easily. It provides PdfSaveOptions class for various settings like number of pages to convert, PDF standard using PdfCompliance enum, iext and image compression options, adding electronic signatures and more. Pass these finalized options as parameter to Save method.

{{% blocks/products/pf/feature-page-code h3="C# Word to PDF Converter Code" %}}

```cs
Document docxtopdf = new Document("word.docx");

PdfSaveOptions pdfSpecificSettings = new PdfSaveOptions();
// Convert 3 pages starting from index 1 where 0 is the first page's index 
pdfSpecificSettings.PageIndex = 1;
pdfSpecificSettings.PageCount = 3;

// Set PDFSaveOption compliance to PDF 17
pdfSpecificSettings.Compliance = PdfCompliance.Pdf17;

// Text Compression Settings
// None: Saving PDF without text compression.
// Flate: Saving PDF with flate (ZIP) compression.
pdfSpecificSettings.TextCompression = PdfTextCompression.Flate;

// Image Compression Settings
// Auto: The API automatically selects the most appropriate compression for every image in the document.
// Jpeg: Compression to JPEG images (does not support transparency).
pdfSpecificSettings.ImageCompression = PdfImageCompression.Auto;

// Digital signatures details
CertificateHolder certHolder = CertificateHolder.Create("esign.pfx", "12345");
pdfSpecificSettings.DigitalSignatureDetails = new PdfDigitalSignatureDetails(certHolder, "reason", "location", DateTime.Now);

// Save Word as PDF
docxtopdf.Save("cshar-word-to.pdf", pdfSpecificSettings);

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="word-to-pdf doc-to-pdf docx-to-pdf rtf-to-pdf txt-to-pdf" >}}


{{% blocks/products/pf/feature-page-section  h2="Mircrosoft Word to HTML Conversion" %}}
Organizations and individuals, now a days, prefer to add documents data in the form of webpages on websites instead of providing "Files Download" options on websites, for easy access to their data as well as much more cases. So **Word to HTML Conversion** is one of the demanding case. C# Microsoft Word library makes it easy and programmers can easily achieve it via few lines of code. After loading the document use [HtmlSaveOptions](https://apireference.aspose.com/words/net/aspose.words.saving/htmlsaveoptions) class for specific features.
{{% blocks/products/pf/feature-page-code h3="C# Code for Word to HTML Conversion" %}}

```cs

// Load word document
Document docxtohtml = new Document("WordFile.docx");

// Set HtmlSaveOptions
HtmlSaveOptions htmlOptions = new HtmlSaveOptions();
htmlOptions.SaveFormat = SaveFormat.Html;

// this property specifies Whether to write the roundtrip information when saving to HTML, MHTML or EPUB.
// Default is true for HTML and false for MHTML and EPUB.
htmlOptions.ExportRoundtripInformation = true;

// Save the document into HTML
docxtohtml.Save("csharp-word-to.html", htmlOptions);

```
{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="doc-to-html docx-to-html docm-to-html dotm-to-html dot-to-html dotx-to-html docx-to-mhtml docm-to-mhtml doc-to-mhtml" >}}

{{% blocks/products/pf/feature-page-section  h2="Convert Word File Pages to Image Formats" %}}
Converting Microsoft Word<sup>&reg;</sup> Documents DOC DOCX to images JPEG, PNG, TIFF etc is another common scenario. Developers can easily utilize code listed below to convert Word document pages to images. After loading the document using Document class instance, Use [ImageSaveOptions Class](https://apireference.aspose.com/words/net/aspose.words.saving/imagesaveoptions) for specific image option settings. 
{{% blocks/products/pf/feature-page-code h3="C# Word to Image Converter Code" %}}
```cs
Document docxtojpeg = new Document(@"sourceWordFile.docx");

// Specify additional image settings
ImageSaveOptions WordtoImageOptions = new ImageSaveOptions(SaveFormat.Jpeg);

// Lets convert entire Word file to Image
PageRange page_Range = new PageRange(0, docxtojpeg.PageCount - 1);

WordtoImageOptions.PageSet = new PageSet(page_Range);
WordtoImageOptions.PageSavingCallback = new Word_To_JPEG_Images_Converter();

// Save Word to Image
docxtojpeg.Save(@"csharp-word-to-image.jpeg", WordtoImageOptions);
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="doc-to-gif docx-to-gif doc-to-jpeg doc-to-png doc-to-tiff doc-to-bmp docx-to-bmp dotm-to-bmp" >}}

{{% blocks/products/pf/feature-page-section  h2="Save Microsoft Word Files to Other Formats" %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="doc-to-emf docx-to-epub docx-to-mobi doc-to-pcl doc-to-ps docx-to-svg doc-to-xps dot-to-pcl dotx-to-epub mobi-to-doc wordml-to-flatopc" >}}