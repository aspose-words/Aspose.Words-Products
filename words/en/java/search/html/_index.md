---
title: Search HTML document without opening via Java 
weight: 3270

description: Java source code to search words with pattern in HTML file on Java Runtime Environment for JSP/JSF Application and Desktop Applications.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Search HTML Formats in Java" h2="Native and high performance HTML file search using Java APIs, without the use of any software like Microsoft or Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/words/aspose_words-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="HTML" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Words " subTitlepfName="for Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/words/aspose_words-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-words" liveDemosLink="https://products.aspose.app/words/family" docsLink="https://docs.aspose.com/words/java" installationsDocsLink="https://docs.aspose.com/words/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/words/java" learnAsLink="https://docs.aspose.com/words/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-words" >}}

{{% blocks/products/pf/agp/content h2="How to Search HTML File Using Java" %}}

 In order to search HTML file, we’ll use
 [Aspose.Words for Java](https://products.aspose.com/words/java) 
 API which is a feature-rich, powerful and easy to use Search API for Java platform. You can download its latest version directly from
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

{{% blocks/products/pf/agp/feature-section-col title="Steps to Search HTML Files in Java" %}}

{{% blocks/products/pf/agp/text %}}

 Developers can easily integrate code with just few lines as listed.

{{% /blocks/products/pf/agp/text %}}

+  Load HTML file by instantiating Document Class object.
+  Instantiate FindReplaceOptions.
+  Use Pattern.compile() method to define a regex pattern
+  Use getRange().replace method to find and replace
+  Save HTML file.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Requirements" %}}

{{% blocks/products/pf/agp/text %}}

 Before integrating the code, make sure that you have the following prerequisites.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows or a compatible OS with Java Runtime Environment for JSP/JSF Application and Desktop Applications.
-  Get latest version of Aspose.Words for Java directly from
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-words)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Search HTML Files - Java" offSpacer="" %}}

```cs
// Load HTML file
Document html = new Document("sourceFile.html");
// Find and replace similar pattern words in the file
FindReplaceOptions options = new FindReplaceOptions();
html.getRange().replace(Pattern.compile("[B|S|M]ad"), "[replaced]", options);
// Save the HTML file
html.save("output.html");  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="" %}}

 Java Words API can be used to load, view and convert Microsoft Word and OpenDocument Formats like DOC, DOCX, ODT to PDF, XPS, HTML and various other formats. You can also create new documents from scratch and save them in the supported formats. It is a standalone API that is suitable for server side and backend systems where high performance is required. It does not depend on any software like Microsoft or OpenOffice. ‎



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="Online HTML Search Live Demos" sectionDescription="Search text, words, phrases within HTML documents right now by visiting our [Live Demos website](https://products.aspose.app/words/search). The live demo has the following benefits" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Just upload your HTML files." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Search result appears instantly." >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/about-file-text fileFormat="HTML " readMoreLink="https://docs.fileformat.com/web/html/" >}}
HTML (Hyper Text Markup Language) is the extension for web pages created for display in browsers. Known as language of the web, HTML has evolved with requirements of new information requirements to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from server, where these are hosted, or can be loaded from local system as well. Each HTML page is made up of HTML elements such as forms, text, images, animations, links, etc. These elements are represented by tags such as img, a, p and several others where each tag has start and end. It can also embed applications written in scripting languages such as JavaScript and Style Sheets (CSS) for overall layout representation. 

    {{< /blocks/products/pf/agp/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Search Documents" subTitle="Using Java, one can also search other files including." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/java/search/doc/" name="DOC" description="Microsoft Word Binary Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/java/search/docx/" name="DOCX" description="Office 2007+ Words Document" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/java/search/mhtml/" name="MHTML" description="Web Page Archive Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/java/search/odt/" name="ODT" description="OpenDocument Text File Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/java/search/ott/" name="OTT" description="OpenDocument Standard Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/java/search/rtf/" name="RTF" description="Rich Text Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/java/search/txt/" name="TXT" description="Text Document" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/words/java/search/xhtml/" name="XHTML" description="XML Text Based Markup" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}