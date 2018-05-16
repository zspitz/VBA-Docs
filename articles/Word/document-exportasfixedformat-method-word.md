---
title: Document.ExportAsFixedFormat Method (Word)
keywords: vbawd10.chm158007848
f1_keywords:
- vbawd10.chm158007848
ms.prod: word
api_name:
- Word.Document.ExportAsFixedFormat
ms.assetid: fe248ff2-0a2a-b10e-fed9-d5bfb73ff1b2
ms.date: 06/08/2017
---


# Document.ExportAsFixedFormat Method (Word)

Saves a document as PDF or XPS format.


## Syntax

 _expression_ . **ExportAsFixedFormat**( **_OutputFileName_** , **_ExportFormat_** , **_OpenAfterExport_** , **_OptimizeFor_** , **_Range_** , **_From_** , **_To_** , **_Item_** , **_IncludeDocProps_** , **_KeepIRM_** , **_CreateBookmarks_** , **_DocStructureTags_** , **_BitmapMissingFonts_** , **_UseISO19005_1_** , **_FixedFormatExtClassPtr_** )

 _expression_ An expression that returns a **[Document](document-object-word.md)** object.


### Parameters



|**Name**|**Required/Optional**|**Data Type**|**Description**|
|:-----|:-----|:-----|:-----|
| _OutputFileName_|Required| **String**|The path and file name name of the new PDF or XPS file.|
| _ExportFormat_|Required| **[WdExportFormat](wdexportformat-enumeration-word.md)**|Specifies either PDF or XPS format.|
| _OpenAfterExport_|Optional| **Boolean**|Opens the new file after exporting the contents.|
| _OptimizeFor_|Optional| **[WdExportOptimizeFor](wdexportoptimizefor-enumeration-word.md)**|Specifies whether to optimize for screen or print.|
| _Range_|Optional| **[WdExportRange](wdexportrange-enumeration-word.md)**|Specifies whether the export range is the entire document, the current page, a range of text, or the current selection. the default is to export the entire document.|
| _From_|Optional| **Long**|Specifies the starting page number, if the Range parameter is set to  **wdExportFromTo** .|
| _To_|Optional| **Long**|Specifies the ending page number, if the Range parameter is set to  **wdExportFromTo** .|
| _Item_|Optional| **[WdExportItem](wdexportitem-enumeration-word.md)**|Specifies whether the export process includes text only or includes text with markup.|
| _IncludeDocProps_|Optional| **Boolean**|Specifies whether to include document properties in the newly exported file.|
| _KeepIRM_|Optional| **Boolean**|Specifies whether to copy IRM permissions to an XPS document if the source document has IRM protections. Default value is  **True** .|
| _CreateBookmarks_|Optional| **[WdExportCreateBookmarks](wdexportcreatebookmarks-enumeration-word.md)**|Specifies whether to export bookmarks and the type of bookmarks to export.|
| _DocStructureTags_|Optional| **Boolean**|Specifies whether to include extra data to help screen readers, for example information about the flow and logical organization of the content. Default value is  **True** .|
| _BitmapMissingFonts_|Optional| **Boolean**|Specifies whether to include a bitmap of the text. Set this parameter to  **True** when font licenses do not permit a font to be embedded in the PDF file. If **False** , the font is referenced, and the viewer's computer substitutes an appropriate font if the authored one is not available. Default value is **True** .|
| _UseISO19005_1_|Optional| **Boolean**|Specifies whether to limit PDF usage to the PDF subset standardized as ISO 19005-1. If  **True** , the resulting files are more reliably self-contained but may be larger or show more visual artifacts due to the restrictions of the format. Default value is **False** .|
| _FixedFormatExtClassPtr_|Optional| **Variant**|Specifies a pointer to an add-in that allows calls to an alternate implementation of code. The alternate implementation of code interprets the EMF and EMF+ page descriptions that are generated by the applications to make their own PDF or XPS. For more information, see "Extending the Office (2007) Fixed-Format Export Feature" on MSDN.|

## See also


#### Concepts


[Document Object](document-object-word.md)
