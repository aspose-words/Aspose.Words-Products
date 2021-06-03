---
title: Generate Reports in XHTML Files via Java 
weight: 3060
url: /java/assembly/xhtml/ 
description: Try our On-Premise document report creation APIs to create XHTML format reports on Java Runtime Environment for JSP/JSF Application and Desktop Applications.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Bulk Report Generation in XHTML Format via Java" h2="Generate reports in XHTML format using data source & a template." logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/words/272x272/aspose_words-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="XHTML" pfName="Aspose.Words" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XHTML" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Words " subTitlepfName="for Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/words/272x272/aspose_words-for-java.png" apiHomeLink="https://products.aspose.app/words/family" codeSamplesLink="https://github.com/aspose-words" liveDemosLink="https://products.aspose.app/words/family" docsLink="https://docs.aspose.com/words/java" installationsDocsLink="https://docs.aspose.com/words/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/words/java" learnAsLink="https://docs.aspose.com/words/java" apiReference="" >}}

{{% blocks/products/pf/agp/content h2="How to Generate XHTML Reports Using Java" %}}

 In order to create XHTML file reports, we’ll use
 [Aspose.Words for Java](https://products.aspose.com/words/java) 
 API which is a feature-rich, powerful and easy to use assembly API for Java platform. You can download its latest version directly from
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

{{% blocks/products/pf/agp/feature-section-col title="Steps to Generate XHTML Reports via Java" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1.  Load template in an instance of Document class
1.  Create an object of ReportingEngine
1.  Build report using Call engine.buildReport method
1.  Save the result with Doucment.save method

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Requirements" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Words for Java supports on all major platforms and Operating Systems. Please make sure that you have the following prerequisites.

{{% /blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Generate Word Reports in XHTML Format - C#" offSpacer="" %}}

```cs
// Create Document object and initialize with XHTML template.
Document xhtml = new Document("template.xhtml");
// Create Sender object.
Sender sender = new Sender("LINQ Reporting Engine", "Hello World");
// Create ReportingEngine object.
ReportingEngine engine = new ReportingEngine();
// Build report.
engine.buildReport(xhtml, sender, "s");
// Save as XHTML document.
xhtml.save("word.xhtml");
    

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="About Aspose.Words for Java API" %}}

 Aspose.Words API can be used to load, view and convert Microsoft Word and OpenDocument Formats like DOC, DOCX, ODT to PDF, XPS, HTML and various other formats. You can also create new documents from scratch and save them in the supported formats. Aspose.Words is a standalone API that is suitable for server side and backend systems where high performance is required. It does not depend on any software like Microsoft or OpenOffice. ‎



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Free App to Assemble XHTML" sectionDescription="Check our live demos to [create XHTML files](https://products.aspose.app/words/assembly/xhtml) with following benefits." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write or compile code" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload XHTML file and hit the \"Assemble\" button" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Download the resultant XHTML file from the link" >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="XHTML" readMoreLink="https://docs.fileformat.com/web/xhtml/" >}}
The XHTML is a text based file format with markup in the XML, using a reformulation of HTML 4.0. These files are well suited to be open or viewed in a web browser. XHTML was designed to be more structured, less scripting, generic; using all the existing facilities of XML and more device independent. XHTML provides a generally worthwhile set of elements and attributes, with extension options in combination with style sheets. The attributes are used from the metadata attributes collection. XHTML provides flexibility and accessibility by subordinating all HTML presentation elements to style sheets. Style sheets are more versatile than these presentational elements.  Specifications for HTML 4.01, HTML5 and XHTML are being dynamically developed by the World Wide Web Consortium (W3C).

        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}