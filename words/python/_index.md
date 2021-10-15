---
title: Python Word Document Processing API - Aspose 
weight: 2200
url: /python/ 
description: Python library to work with Word and PDF files. Create, edit, convert documents, generate reports in Python.
---

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/upper-banner h1="Python APIs to Process Word Documents" h2="Create, manipulate, render or convert Word files to multiple formats as well as generate reports without depending on any external software." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/words/aspose_words-for-cpp.svg" pfName="Aspose.Words" subTitlepfName="for Python via .NET" downloadUrl="https://downloads.aspose.com/words/python" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Words" subTitlepfName="for Python via .NET" >}}

{{< blocks/products/pf/sub-menu logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/words/aspose_words-for-net.svg" liveDemosLink="https://products.aspose.app/words/family" PricingLink="https://docs.aspose.com/words/python/licensing/#purchased-license" buyLink="https://purchase.aspose.com/buy" docsLink="https://docs.aspose.com/words/python/" installationsDocsLink="https://docs.aspose.com/words/python/installation/" >}}

{{< blocks/products/pf/tab-content >}}

<p>With the advent of powerful computer hardware in the last decades, Python has become a programming language widely used in web development (together with popular Django, Flask, Pyramid frameworks), scientific tasks, and data analytics. The usefulness of Python derives from a vast ecosystem of third-party packages. Supplied with enormous amount of progressively developing libraries, Python is considered to be the best choice for rapid software development.</p>

<p>According to TIOBE Programming Index, which reflects the popularity of programming languages, Python is considered to be a programming language number one.

<p>Aspose.Words team decided to keep up in the line with the latest programming trends and supply Python community with professional software to process DOC, DOCX, PDF, RTF, DOT, DOTX, DOTM, DOCM FlatOPC, ODT, OTT, HTML, MHTML, MOBI, TXT, XPS, PS, TIFF, JPEG, PNG, BMP, SVG, EMF, GIF, PCL, EPUB, XML, XAML files.</p>

<h2 class="h2title">Functionality of Aspose.Words for Python via .NET</h2>

<p><strong>Aspose.Words for Python via .NET</strong> is a package, designed to read and manipulate documents of various types, with a primary focus on Microsoft Word (DOC, DOCX, ODT), PDF, and Web (HTML, Markdown) documents. This product enables Python developers a unique possibility to implement script-based document automation. Our library contains more than 100 Python classes to handle low-level operations behind document processing and data formatting.</p>

<p>It's a self-contained Python library - you don't require to install any office suite to get your Python code working. This Python API relies on the "Document Object Model" (DOM) to access document nodes and elements.</p>

{{< /blocks/products/pf/tab-content >}}

<h3 class="h3title">Create and modify Word documents in Python</h2>

<ul>
  <li>Work with major industry-standard document and image formats</li>
  <li>Create new documents as well as make changes to existing ones</li>
  <li>Generate PDF using Python by specifying the output format when saving the document</li>
</ul>

<h3 class="h3title">Read, write and convert documents using Python</h2>

<ul>
  <li>Access and manipulate document elements programmatically: text, paragraphs, tables, images, sections, headers, footers, lists, fields, OLE objects</li>
  <li>Specify formatting and styling of any complexity</li>
  <li>Render document's content to a print-ready representation</li>
  <li>Save document pages as images: JPG, PNG, GIF, EMF pictures</li>
  <li>Add watermark to documents or remove it</li>
  <li>Edit document's metadata that stores information about date of creation, editing time, etc.</li>
</ul>

<h3 class="h3title">Build reports, Mail Merge in Python</h2>

<p>You can generate custom reports based on templates and data sources in JSON and XML formats. Use this powerful feature to create bulk email, letters, envelopes, and labels. In current version, only basic Reporting/Mail Merge features are supported.</p>

<h3 class="h3title">Split, merge, compare documents with Python</h2>

<p>You can use a powerful set of utility functions that are rarely available in common office suites, like Microsoft Word, LibreOffice, OpenOffice, WPS Office:</p>

<ul>
  <li>Join several documents to a single file</li>
  <li>Split documents into parts</li>
  <li>Compare document differences</li>
  <li>Set and remove document protection</li>
  <li>and much more...</li>
</ul>

<h2 class="h2title">System Requirements</h2>

<ul>
  <li>Compatible with Python 3.5, 3.6, 3.7, 3.8 and 3.9</li>
  <li>In case you write Python code on Linux, have a look at [additional requirements for Linux](https://pypi.org/project/Aspose.Words-for-Python-via-NET/)<li>
</ul>

<h2 class="h2title">How to Install</h2>

<p>Use <strong>pip</strong> to install our Python library for Word document processing from the [PyPI repository](https://pypi.org/project/Aspose.Words-for-Python-via-NET/):

<pre>
<code>
pip install Aspose.Words-for-Python-via-NET
</code>
</pre>

<h2 class="h2title">Edit a Word document in Python</h2>

The following code example shows how to insert text to a document, and save the result as PDF:

<pre>
<code class="python">
import aspose.words as aw

# Create a blank document
doc = aw.Document()

# Use a DocumentBuilder instance to add content to the document
builder = aw.DocumentBuilder(doc)

# Add a paragraph to the document
builder.writeln("Hello World!")

# Save the result as a PDF document. The output format is determined by the file extension
doc.save("Output.pdf")
</code>
</pre>

<h2 class="h2title">Convert a Word document in Python</h2>

You can easily convert files from one format to another. Do you know how to extract text from Word documents via Python? The following code sample shows how to do it with a single line of code by converting DOCX to HTML (or TXT):

<pre>
<code class="python">
import aspose.words as aw

# Load a document from the local drive
doc = aw.Document("Input.docx")

# Save the output as hypertext
doc.save("Output.html")
</code>
</pre>

{{< blocks/products/pf/support-learning-resources >}}
{{< blocks/products/pf/slr-tab tabTitle="Learning Resources" tabId="resources" >}}
{{< blocks/products/pf/slr-element name="Documentation" href="https://docs.aspose.com/words/python/" >}}
{{< blocks/products/pf/slr-element name="Source Code" href="https://github.com/aspose-words/Aspose.Words-for-Python-via-.NET" >}}
{{< blocks/products/pf/slr-element name="API References" href="https://apireference.aspose.com/words/net" >}}
{{< blocks/products/pf/slr-element name="Tutorial Videos" href="https://www.youtube.com/user/asposevideo" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< blocks/products/pf/slr-tab tabTitle="Product Support" tabId="support" >}}
{{< blocks/products/pf/slr-element name="Free Support" href="https://forum.aspose.com/c/words" >}}
{{< blocks/products/pf/slr-element name="Paid Support" href="https://helpdesk.aspose.com/" >}}
{{< blocks/products/pf/slr-element name="Blog" href="https://blog.aspose.com/category/words/" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< blocks/products/pf/slr-tab tabTitle="Why Aspose.Words for Python via .NET?" tabId="success-stories" >}}
{{< blocks/products/pf/slr-element name="Customers List" href="https://company.aspose.com/customers" >}}
{{< blocks/products/pf/slr-element name="Success Stories" href="https://company.aspose.com/customers/success-stories/aspose-words" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< /blocks/products/pf/support-learning-resources >}}

{{< blocks/products/pf/download-section downloadFreeTrialLink="https://downloads.aspose.com/words/net" pricingInformationLink="https://purchase.aspose.com/pricing/words/net" >}}

{{< blocks/products/pf/offers-section pfName="Aspose.Words" description="Aspose.Words offers individual Word processing APIs for other popular development environments as listed below:" >}}

    {{< blocks/products/pf/offers-section-item link="/words/net/" imgSrc="https://www.aspose.cloud/templates/aspose/img/products/words/aspose_words-for-net.svg" sdkName=".NET" >}}
    {{< blocks/products/pf/offers-section-item link="/words/java/" imgSrc="https://www.aspose.cloud/templates/aspose/img/products/words/aspose_words-for-java.svg" sdkName="Java" >}}
    {{< blocks/products/pf/offers-section-item link="/words/cpp/" imgSrc="https://www.aspose.cloud/templates/aspose/img/products/words/aspose_words-for-cpp.svg" sdkName="C++" >}}
    {{< blocks/products/pf/offers-section-item link="/words/android-java/" imgSrc="https://www.aspose.cloud/templates/aspose/img/products/words/aspose_words-for-android-java.svg" sdkName="Android via Java" >}}
    {{< blocks/products/pf/offers-section-item link="/words/sharepoint/" imgSrc="https://www.aspose.cloud/templates/aspose/img/products/words/aspose_words-for-sharepoint.svg" sdkName="SharePoint" >}}
    {{< blocks/products/pf/offers-section-item link="/words/reporting-services/" imgSrc="https://www.aspose.cloud/templates/aspose/img/products/words/aspose_words-for-reporting-services.svg" sdkName="Reporting Services" >}}
    {{< blocks/products/pf/offers-section-item link="/words/jasperreports/" imgSrc="https://www.aspose.cloud/templates/aspose/img/products/words/aspose_words-for-jasperreports.svg" sdkName="JasperReports" >}}

{{< /blocks/products/pf/offers-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
