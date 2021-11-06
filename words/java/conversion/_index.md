---
title: Microsoft Word Document Conversion via Java 
url: /java/conversion/
description: Convert Microsoft Word DOC DOCX formats to HTML, Images and many other popular formats with just few lines of Java code.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Microsoft Word File Conversion via Java" h2="Export Microsoft Office® Word document to PDF, HTML, Images and fixed-layout formats" >}}

{{% blocks/products/pf/feature-page-summary %}}
There are lot of conversion cases specially whenever there is need of sharing the documents. Various apps availible to **convert word to PDF**, HTML and images. But the best solution is to enhance the application functionality to add conversion feature for MS Word automation and report generation instead of relying on limited scope of other softwares. We are listing few code snippets for automation and batch conversion of files using **Java Word document library** and dvelopers can easily integrate it.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Inter Conversion Of Microsoft Word Files using Java" %}}
Converting Word document to its own formats is just two steps process in general. Load the source file using [Document class](https://apireference.aspose.com/words/java/com.aspose.words/Document) and calling the [save meothod](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.io.OutputStream,int)) of same class with output file path and SaveFormat.TargetFormat as parameters. 
{{% blocks/products/pf/feature-page-code h3="Java code for DOC to DOCX Conversion" %}}

```cs
// load source Microsoft Word Doc File
Document srcFile = new Document("source-file.doc");

// call Save method while passing SaveFormat.DOCX
srcFile.save("doc-to.docx", SaveFormat.DOCX);   
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="doc-to-docx docx-to-doc docm-to-docx" >}}


{{% blocks/products/pf/feature-page-section  h2="Java Word to PDF Conversion" %}}
Java Word library supports Microsoft Word formats to PDF conversion. Programmers can easily set different options as of the requirement like conversion of only selected pages of word documents as well as to a particular PDF PDF/A-1a, PDF 1.5, etc Standard along with Text or Image Compression and more. For conversion with praticular options **Java Word to PDF converter** API provides [PdfSaveOptions class](https://apireference.aspose.com/java/words/com.aspose.words/PdfSaveOptions) that handles all the specific settings.

{{% blocks/products/pf/feature-page-code h3="Java Word to PDF Converter Code" %}}

```cs
// Load the Word document from disk
Document docxtopdf = new Document("srcFile.docx");
PdfSaveOptions specificOptions = new PdfSaveOptions();

// Convert 3 pages starting from index 1 where 0 is the first page's index 
specificOptions.setPageIndex(1);
specificOptions.setPageCount(3);

// Set compliance to PDF15
specificOptions.setCompliance(PdfCompliance.PDF_15);

// Text and image compression
specificOptions.setTextCompression(PdfTextCompression.FLATE);
specificOptions.setImageCompression(PdfImageCompression.AUTO);

// Save Word as PDF
docxtopdf.save("word-to.pdf", specificOptions);

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="doc-to-pdf docx-to-pdf rtf-to-pdf txt-to-pdf" >}}


{{% blocks/products/pf/feature-page-section  h2="Mircrosoft Word to HTML Conversion" %}}
As of web era, it's the most demanding case, where organizations or individuals wants to convert all of their Micrsoft Word data to HTML to display it on websites in form of webpages instead of document downloading options. So to convert Word data to HTML for the websites developed using Java language, below code makes it easy. Procedure of conversion is almost simple, Load the word documents using Document Class then calling the save method with output file path and SaveFormat.HTML as parameters. For applying special settings, **Jave Word to HTML** API provides [HtmlSaveOptions class](https://apireference.aspose.com/words/java/com.aspose.words/htmlsaveoptions) that deals all the specific settings.
{{% blocks/products/pf/feature-page-code h3="Java code for Word to HTML Generic Conversion" %}}

```cs
Document docxtohtml = new Document("sourceWordFile.docx");
docxtohtml.save("wordtohtml.html", SaveFormat.HTML);
```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Convert Word DOC / DOCX to HTML or HTML5 with Specific Options " %}}

```cs
Document doctohtml = new Document("Source-File.docx");
//Save Word documents to HTML5
HtmlSaveOptions optsHtml5 = new HtmlSaveOptions(SaveFormat.HTML);
optsHtml5.setHtmlVersion(HtmlVersion.HTML_5);
optsHtml5.setExportImagesAsBase64(true);
optsHtml5.setExportPageMargins(true);        
doctohtml.save("word-to-html5.html", optsHtml5);

```
{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="doc-to-html docx-to-html docm-to-html dotm-to-html dot-to-html dotx-to-html md-to-html" >}}

{{% blocks/products/pf/feature-page-section  h2="Convert Word to Image" %}}
Sometime it is needed to convert Microsoft Word DOC / DOCX files to images, one of the case is when someone want to preview of data alongwith pictures in word documents. So Java Word API makes it easy to save in JPEG, BMP, PNG, TIFF or more formats. Conversion procedure is simple as for generic cases i.e loading the document and saving using save method with output file path and [SaveFormat](https://apireference.aspose.com/words/java/com.aspose.words/saveformat) image extension. For setting different options API provides [ImageSaveOptions class](https://apireference.aspose.com/words/java/com.aspose.words/imagesaveoptions). 
{{% blocks/products/pf/feature-page-code h3="Java Word to Image Converter Code" %}}
```cs
// Load the document from disk.
Document doctoImage = new Document("sourceFile.docx");

ImageSaveOptions savePictureinJpg = new ImageSaveOptions(SaveFormat.JPEG);

// Set the "PageSet" to "0" to convert only the first page of a document.
savePictureinJpg.setPageSet(new PageSet(0));

// Change the image's brightness and contrast.
// Both are on a 0-1 scale and are at 0.5 by default.
savePictureinJpg.setImageBrightness(0.3f);
savePictureinJpg.setImageContrast(0.7f);

// Change the horizontal resolution.
// Default value is 96.0, for a resolution of 96dpi.
savePictureinJpg.setHorizontalResolution(72f);

// Save the Word in Image format.
doctoImage.save("word-to-image.jpeg", savePictureinJpg);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="doc-to-png odt-to-jpeg docm-to-bmp ott-to-tiff rtf-to-gif txt-to-png wordml-to-jpeg" >}}