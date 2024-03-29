---
title: Generate Word DOCX documents from template via Java 
weight: 7690

description: Java Sample code for creating template based DOCX documents. Use it for automated generation of Word DOCX files within Java based desktop or web application.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Create Template Based DOCX Files via Java" h2="Native and high performance Microsoft Word DOCX document generation from templates programmatically using Java library." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/words/aspose_words-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="DOCX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DOCX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Words " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/words/aspose_words-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-words" liveDemosLink="https://products.aspose.app/words/family" docsLink="https://docs.aspose.com/words/java" installationsDocsLink="https://docs.aspose.com/words/java" nugetLink="https://www.nuget.org/packages/aspose.words" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/words/java" learnAsLink="https://docs.aspose.com/words/java" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="" %}}

 A template is a file with pre-applied formatting like tabs, styles, line spacing etc. Generating MS Word DOCX file dynamically from templates within running application is easy. In order to generate a batch of documents with the same structure based on the template without requiring MS Office, we’ll use
 [Aspose.Words for .NET](https://products.aspose.com/words/java) 
 API that offers different features for document creation, manipulation and conversion using .NET platform.  For populating the predefined Word template, we’ll create a Word DOCX file with the following placeholders as the content of the document: <code><<[s.getName()]>> says: "<<[s.getMessage()]>>.""</code> where <code>s</code> is the <code>Sender</code> class object that will be used to populate the template. Beside a predefine class like Sender in our case, One can also use XML, JSON and CSV data as a source data sources. You can download its latest version directly from
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-words) 
 and install it within your Maven-based project by adding the following configurations to the pom.xml.

{{% blocks/products/pf/agp/code-block title="Repository" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Dependency" offSpacer="true" %}}

```cs
<dependency>
<groupId>com.aspose</groupId>
<artifactId>aspose-words</artifactId>
<version>version of aspose-words API</version>
<classifier>jdk17</classifier>
</dependency>

```

{{% /blocks/products/pf/agp/code-block %}}




{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="How to Create Word DOCX File Using Template via Java" %}}

{{% blocks/products/pf/agp/text %}}

 It is easy for the developers to creat DOCX files from template using ReportingEngine within running Word Automation applications for data processing in just a few lines of code. Reporting Engine supports different data sources including XML, JSON and CSV data.

{{% /blocks/products/pf/agp/text %}}

1.  Create the Document object having template’s path as parameter.
1.  Create and initialize an object of Sender class.
1.  Create ReportingEngine class object.
1.  Use ReportingEngine.buildReport() method to build the report having document template, data source, and data source name.
1.  Save created Word file using save() method..

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Requirements" %}}

{{% blocks/products/pf/agp/text %}}

Before running the Java conversion sample source code, make sure that you have the following prerequisites. 

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows or a compatible OS with Java Runtime Environment for JSP/JSF Application and Desktop Applications.
- Get latest version of Aspose.Words for Java directly from Maven.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Following source code shows how to create a Word DOCX file from template using Java." offSpacer="" %}}

```cs
public class Sender {
    public Sender(String name, String message) {
        _name = name;
        _message = message;
    } 
    public String getName() {
        return _name;
    } 
    public String getMessage() {
        return _message;
    } 
    private String _name;
    private String _message;
}
///
// Create Document object and initialize with DOCX template.
Document docx = new Document("template.docx");
// Create Sender object.
Sender sender = new Sender("LINQ Reporting Engine", "Message that should be displayed");
// Create ReportingEngine object.
ReportingEngine engine = new ReportingEngine();
// Build report.
engine.buildReport(docx, sender, "s");
// Save as Word document.
docx.save("word.docx");
// In case of XML, JSON and CSV datasources, Reporting Engine will take relevant datasource as parameters


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<!-- aboutfile Starts -->

     
     {{% blocks/products/pf/agp/content h2="" %}}

Word Processing Automation Library to perform a wide range of document management and manipulation tasks including DOCX generation, editing, conversion, rendering and printing. .NET Word API supports all of word-processing formats as well as allows exporting or **converting DOCX to PDF**, HTML, fixed-layout and most commonly used image & multimedia formats.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="DOCX" readMoreLink="https://docs.fileformat.com/word-processing/docx/" >}}
Files with .DOCX extension represent documents generated by Microsoft Word or other word processing documents in binary file format. The extension was initially used for plain text documentation on several different operating systems. It can contain different types of data such as images, formatted as well as plain text, graphs, charts, embedded objects, links, pages, formatting, print settings and a lot more.

        {{< /blocks/products/pf/agp/about-file-text >}}

          {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Document Creation From Template" subTitle="You can also generate other Microsoft Words file from a predefined template including few listed below." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/java/create/template/doc/" name="DOC" description="Microsoft Word Binary Format" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/java/create/template/docx/" name="DOCX" description="Office 2007+ Word Document" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/java/create/template/rtf/" name="RTF" description="Rich Text Format" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/java/create/template/dot/" name="DOT" description="Microsoft Word Template Files" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/java/create/template/dotx/" name="DOTX" description="Microsoft Word Template File " >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/java/create/template/dotm/" name="DOTM" description="Microsoft Word 2007+ Template File" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/java/create/template/docm/" name="DOCM" description="Microsoft Word 2007 Marco File" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/java/create/template/odt/" name="ODT" description="OpenDocument Text File Format" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}