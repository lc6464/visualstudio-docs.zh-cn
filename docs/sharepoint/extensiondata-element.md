---
title: ExtensionData 元素 |Microsoft Docs
description: 查看有关 ExtensionData 元素的参考信息，该元素是 SharePoint 项目项架构中的一个元素。
ms.custom: SEO-VS-2020
ms.date: 02/02/2017
ms.topic: conceptual
dev_langs:
- VB
- CSharp
helpviewer_keywords:
- ExtensionData element
author: John-Hart
ms.author: johnhart
manager: jillfra
ms.workload:
- office
ms.openlocfilehash: 3131aca3664e37198b0a32bdc0ade0499c12a1e6
ms.sourcegitcommit: 3d96f7a8c9affab40358c3e81e3472db31d841b2
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 11/17/2020
ms.locfileid: "94672530"
---
# <a name="extensiondata-element"></a>ExtensionData 元素
  表示与 SharePoint 项目项关联的自定义数据项的集合。

## <a name="syntax"></a>语法

```xml
<ExtensionData>
  <ExtensionDataItem.../>
</ExtensionData>
```

## <a name="attributes-and-elements"></a>特性和元素
 下列各节描述了特性、子元素和父元素。

### <a name="attributes"></a>特性
 无。

### <a name="child-elements"></a>子元素

|元素|说明|
|-------------|-----------------|
|[ExtensionDataItem](../sharepoint/extensiondataitem-element.md)|可选元素。<br /><br /> 表示与 SharePoint 项目项关联的自定义数据项，以键/值格式表示。 键和值都必须是字符串。|

### <a name="parent-elements"></a>父元素

|元素|说明|
|-------------|-----------------|
|[ProjectItem](../sharepoint/projectitem-element.md)|表示 SharePoint 项目项。 此元素是文件必需的根元素 `.spdata` 。|

## <a name="remarks"></a>注解
 使用对象的属性将自定义数据与 SharePoint 项目项相关联时 <xref:Microsoft.VisualStudio.SharePoint.ISharePointProjectItem.ExtensionData%2A> <xref:Microsoft.VisualStudio.SharePoint.ISharePointProjectItem> ，Visual Studio 会将数据保存到项目项的文件中的 **ExtensionData** 元素 `.spdata` 。 有关详细信息，请参阅 [在 SharePoint 项目系统的扩展中保存数据](../sharepoint/saving-data-in-extensions-of-the-sharepoint-project-system.md)。

## <a name="element-information"></a>元素信息

|属性|值|
|-|-|
|**Namespace**|http： \/ \/ schemas.microsoft.com/VisualStudio/<br>2010/SharePointTools/SharePointProjectItemModel|
|**架构名称**|SharePoint 项目项架构|
|**验证文件**|ProjectItemModelSchema|
|**可以为空**|否|

## <a name="see-also"></a>另请参阅
- [SharePoint 项目项架构参考](../sharepoint/sharepoint-project-item-schema-reference.md)
