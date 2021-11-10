---
title: Microsoft Word Document Conversion via C++ 
url: /cpp/conversion/
description: Convert Microsoft Word DOCX DOC DOCM formats to Image  HTML PDF and many other formats with just few lines of C++ code.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Microsoft<sup>&reg;</sup> Office Word File Conversion via C++" h2="Export Microsoft Office® Word documents to HTML, PDF, Images and fixed-layout formats" >}}

{{% blocks/products/pf/feature-page-summary %}}

Conversion of Word documents to other formats is the most popular and widely used case. We are discussing here few cases for batch conversion and automation of files conversion using **C++ Word library**. Dvelopers can easily develop their solutions or integrate any of these codes within their existing applications.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Inter Conversion Of Microsoft Word Formats via C++" %}}
Inter coversion Microsoft Word formats like DOC to DOCX or DOCX to DOC is just two steps process in general. Load the source file using [Document class](https://apireference.aspose.com/words/cpp/class/aspose.words.document) and calling the [Save meothod](https://apireference.aspose.com/words/cpp/class/aspose.words.saving.save_output_parameters/) of same class by specifying the output parameters. 
{{% blocks/products/pf/feature-page-code h3="C++ code for DOC to DOCX Conversion" %}}

```cs
// Load a word document that exists in the local system:
auto doctodocx = MakeObject<Document>(u"sourceFile.doc");
// Save to the resultant document
doctodocx->Save(u"Interconversion.docx", SaveFormat::Docx);   
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="doc-to-docx docx-to-doc docm-to-docx" >}}


{{% blocks/products/pf/feature-page-section  h2="C++ Word to PDF Conversion" %}}
Word to PDF conversion is famouse becuase of the most demanding sharing document scenario. C++ Microsoft Word API provides [PdfSaveOptions class](https://apireference.aspose.com/words/cpp/class/aspose.words.saving.pdf_save_options/) to achieve different PDF standard settings during conversion process. Pass these finalized options as parameter to Save method.

{{% blocks/products/pf/feature-page-code h3="C++ Word to PDF Converter Code" %}}

```cs
// Load the file.
System::SharedPtr<Document> docxtopdf = System::MakeObject<Document>(u"srcFile.docx");

// Provide PDFSaveOption compliance to PDF 17
// or just convert without SaveOptions
System::SharedPtr<PdfSaveOptions> options = System::MakeObject<PdfSaveOptions>();
options->set_Compliance(PdfCompliance::Pdf17);
// Convert Word to PDF
docxtopdf->Save(u"word-to.pdf", options);

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="doc-to-pdf docx-to-pdf rtf-to-pdf txt-to-pdf" >}}


{{% blocks/products/pf/feature-page-section  h2="Mircrosoft Word to HTML Conversion" %}}
**Word to HTML Conversion** is the most demanding case of web era. Instead of proividing downloading documents on website, just convert the data into HTML, MHTML and generate webpages. Words library makes it easy and developers can easily convert Microsoft Word to HTML or MHTML format. Library provides [HtmlSaveOptions](https://apireference.aspose.com/words/cpp/class/aspose.words.saving.html_save_options) class for specific features like embedded fonts, Round-Trip Information and more. 
{{% blocks/products/pf/feature-page-code h3="C++ code for Word to HTML Conversion" %}}

```cs

// Load source word file
System::SharedPtr<Document> docxtohtml = System::MakeObject<Document>(u"srcFile.docx");

// Initialize HtmlSaveOptions for specific settings
System::SharedPtr<HtmlSaveOptions> htmlOpts = System::MakeObject<HtmlSaveOptions>();
htmlOpts->set_ExportFontResources(true);
htmlOpts->set_ExportFontsAsBase64(true);
        
// Save output HTML
docxtohtml->Save(u"cpp-word-to.html", htmlOpts);

```
{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="doc-to-html docx-to-html docm-to-html dotm-to-html dot-to-html dotx-to-html" >}}

{{% blocks/products/pf/feature-page-section  h2="Save Microsoft Word Files As Images" %}}
Converting Microsoft<sup>&reg;</sup> Word documents as images is needed for variety of scenarios like preveiwing and sharing. Conversion process is simple in general. Loading the document and calling the Save method for relevant JPEG, PNG, or BMP format. But in case of getting more control on the resultant images quality, API provides [ ImageSaveOptions class](https://apireference.aspose.com/words/cpp/class/aspose.words.saving.image_save_options/) for adjusting different options like  HorizontalResolution, VerticalResolution, Resolution, Scale, PixelFormat, ImageBrightness, ImageColorMode, ImageContrast, PaperColor etc.
{{% blocks/products/pf/feature-page-code h3="C++ Word to Image Converter Code" %}}
```cs
// Load the document
auto doctojpeg = System::MakeObject<Document>(u"rendering-srcFile.doc");

auto imageOptions = System::MakeObject<ImageSaveOptions>(SaveFormat::Jpeg);

// Set the "PageSet" = "0" for only first page conversion.
auto pageRange = System::MakeObject<PageRange>(0, 0);
imageOptions->set_PageSet(System::MakeObject<PageSet>(System::MakeArray<System::SharedPtr<PageRange>>({ pageRange })));


// Set the image's brightness and contrast.
// Both are on a 0-1 scale and are at 0.5 by default.
imageOptions->set_ImageBrightness(0.3f);
imageOptions->set_ImageContrast(0.7f);

// set the horizontal resolution.
// The default value for these properties is 96.0, for a resolution of 96dpi.
imageOptions->set_HorizontalResolution(72.0f);

// Save the document to image.
doctojpeg->Save(u"word-to-image.jpeg", imageOptions);
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="doc-to-png odt-to-jpeg docm-to-bmp ott-to-tiff rtf-to-gif txt-to-png" >}}

{{% blocks/products/pf/feature-page-section  h2="Convert Microsoft Word DOC DOX to Markdown MD File" %}}
Markdown MD format is famous for documentation, blog articles publishing, describing projects etc as well as its further conversion to HTML, PDF and more formats makes it popular. API supports Markdown features like Headings H1 – H6 styles, Blockquotes, IndentedCode, FencedCode, and more.
{{% blocks/products/pf/feature-page-code h3="C++ Word to MD Converter Code" %}}
```cs
auto doctomd = System::MakeObject<Document>();
auto mdFileBuilder = System::MakeObject<DocumentBuilder>(doc);


// Specify the "Heading 1" style for the paragraph.
mdFileBuilder->InsertParagraph();
mdFileBuilder->get_ParagraphFormat()->set_StyleName(u"Heading 1");
mdFileBuilder->Write(u"Heading 1");

// Specify the Italic emphasis for the paragraph.
mdFileBuilder->InsertParagraph();
// Reset styles from the previous paragraph to not combine styles between paragraphs.
mdFileBuilder->get_ParagraphFormat()->set_StyleName(u"Normal");
mdFileBuilder->get_Font()->set_Italic(true);
mdFileBuilder->Write(u"Italic Text");
// Reset styles from the previous paragraph to not combine styles between paragraphs.
mdFileBuilder->set_Italic(false);

// Specify a Hyperlink for the desired text.
mdFileBuilder->InsertParagraph();
mdFileBuilder->InsertHyperlink(u"Domain name", u"https://www.anydomain.com", false);
mdFileBuilder->Write(u"domain name");

// Save your document as a Markdown file.
doctomd->Save(u"converted-word-to.md");
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}