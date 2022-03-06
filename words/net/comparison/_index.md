---
title: Compare Microsoft Word Documents in C#
url: /net/comparison/
description: C# source codes that explains how to compare Microsoft Word files using Visual C#.NET applications
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Microsoft<sup>&reg;</sup> Word Files Comparison via .NET" h2="Compare Microsoft Word documents using C# code within .NET based applications" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Word Library](/words/net/) is capable to compare word documents to find the differences within .NET based applications. Developers can compare text in word files and highlight changes as well as compare documents from URL. And it's quiet smooth to design such application to select two documents from the list and get the differences between both. New designed web or desktop applocation can show the summary of changes describing what is added and deleted. Newly inserted text can be formatted in some highlighted fonts such as red-underlined font. Similarly, deleted text can be formatted in some other font such as red color and strike-through font settings. On comparison, differences of the latter file from the former show up as revisions to the former. On modifying the file, each edit will have its own revision after running the compare method.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Compare Micrsoft Word Documents" %}}


To identify the differences, API provides [Compare](https://apireference.aspose.com/words/net/aspose.words/document/methods/compare/index) method. It's just like the Microsoft Word document compare feature that is capable to check documents or document versions to find differences and changes such as formatting modifications, font changes, spacing changes, the addition of words and paragraphs etc. The result is either documents are equal or not equal. Equal means both documents are same and comparison method is not able to represent changes as revisions. But there could be other differences in files like Microsoft Word supports only format revisions for styles, and one cannot get style insertion/deletion. So documents can have a different set of styles, and the Compare method still produces no revisions. 

API provides [CompareOptions](https://apireference.aspose.com/words/net/aspose.words.comparing/compareoptions) class for advance settings such as to ignore changes made during a comparison for certain types of objects within the original document. Few of the properties [IgnoreHeadersAndFooters](https://apireference.aspose.com/words/net/aspose.words.comparing/compareoptions/properties/ignoreheadersandfooters), [IgnoreFormatting](https://apireference.aspose.com/words/net/aspose.words.comparing/compareoptions/properties/ignoreformatting), [IgnoreComments](https://apireference.aspose.com/words/net/aspose.words.comparing/compareoptions/properties/ignorecomments) to set them true or false as of comparison requirement. Programmers can also set [Granularity](https://apireference.aspose.com/words/net/aspose.words.comparing/compareoptions/properties/granularity) property to specify whether to track changes by character or by word.


{{% blocks/products/pf/feature-page-code h3="C# Code for Document Comparison Equality" %}}

{{< gist "aspose-com-gists" "91fafae083e7a544c77b872f69e34e83" "compare-documents-equality.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% blocks/products/pf/feature-page-code h3="C# Code to Compare Two Documents" %}}

{{< gist "aspose-com-gists" "91fafae083e7a544c77b872f69e34e83" "compare-two-documents.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Compare">}}