---
title: "XML Data Types (XMLA) | Microsoft Docs"
ms.date: 05/08/2018
ms.prod: sql
ms.technology: analysis-services
ms.custom: xmla
ms.topic: reference
ms.author: owend
ms.reviewer: owend
author: minewiskan
manager: kfile
---
# XML Data Types (XMLA)
[!INCLUDE[ssas-appliesto-sqlas-aas](../../../includes/ssas-appliesto-sqlas-aas.md)]
  In addition to the standard primitive and derived types defined by the XML 1.0 recommendation, the XML for Analysis (XMLA) 1.1 specification defines additional data types to support the representation of multidimensional and tabular data.  
  
 XMLA uses the data types listed in the following table.  
  
|Data types|Description|  
|----------------|-----------------|  
|Boolean|The standard XML **boolean** data type.|  
|Decimal|The standard XML **decimal** data type.|  
|[EmptyResult](../../../analysis-services/xmla/xml-data-types/emptyresult-data-type-xmla.md)|A namespace on the **root** element. This namespace is returned when an XMLA command does not return a result because either the XMLA command does not normally return a result or because an error occurred on the Analysis Services instance while executing the XMLA command.|  
|[EnumString](../../../analysis-services/xmla/xml-data-types/enumstring-data-type-xmla.md)|A set of named string constants for a given enumerator.|  
|Integer|The standard XML **int** data type.|  
|[MDDataSet](../../../analysis-services/xmla/xml-data-types/mddataset-data-type-xmla.md)|Multidimensional data returned by the *Result* parameter of the [Execute](../../../analysis-services/xmla/xml-elements-methods-execute.md) method.|  
|[Resultset](../../../analysis-services/xmla/xml-data-types/resultset-data-type-xmla.md)|A self-describing XML result set returned by the **Execute** method.|  
|[Rowset](../../../analysis-services/xmla/xml-data-types/rowset-data-type-xmla.md)|Rows from a data source, structured by an embedded XML schema, returned by the [Discover](../../../analysis-services/xmla/xml-elements-methods-discover.md) method.|  
|String|The XML **string** data type.|  
|UnsignedInt|The XML **unsignedInt** schema type.|  
  
 For complete descriptions of the standard XML data types, see the World Wide Web Consortium (WC3) candidate recommendation.  
  
## See also
 [XML Elements &#40;XMLA&#41;](http://msdn.microsoft.com/library/40ab2360-efb6-4ba6-bf23-e84964e51008)   
 [XML for Analysis  &#40;XMLA&#41; Reference](../../../analysis-services/xmla/xml-for-analysis-xmla-reference.md)  
  
  
