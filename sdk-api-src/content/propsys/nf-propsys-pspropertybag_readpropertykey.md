---
UID: NF:propsys.PSPropertyBag_ReadPropertyKey
title: PSPropertyBag_ReadPropertyKey function (propsys.h)
description: Reads the property key of a property in a specified property bag.
helpviewer_keywords: ["PSPropertyBag_ReadPropertyKey","PSPropertyBag_ReadPropertyKey function [Windows Properties]","properties.PSPropertyBag_ReadPropertyKey","propsys/PSPropertyBag_ReadPropertyKey","shell.PSPropertyBag_ReadPropertyKey"]
old-location: properties\PSPropertyBag_ReadPropertyKey.htm
tech.root: properties
ms.assetid: 910D1356-DC61-470b-90BB-0DCF1B861E05
ms.date: 12/05/2018
ms.keywords: PSPropertyBag_ReadPropertyKey, PSPropertyBag_ReadPropertyKey function [Windows Properties], properties.PSPropertyBag_ReadPropertyKey, propsys/PSPropertyBag_ReadPropertyKey, shell.PSPropertyBag_ReadPropertyKey
req.header: propsys.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 7 [desktop apps only]
req.target-min-winversvr: Windows Server 2008 R2 [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: Propsys.lib
req.dll: Propsys.dll (version 6.0 or later)
req.irql: 
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
f1_keywords:
 - PSPropertyBag_ReadPropertyKey
 - propsys/PSPropertyBag_ReadPropertyKey
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - DllExport
api_location:
 - Propsys.dll
api_name:
 - PSPropertyBag_ReadPropertyKey
---

# PSPropertyBag_ReadPropertyKey function


## -description

Reads the property key of a property in a specified property bag.

## -parameters

### -param propBag [in]

Type: <b><a href="/previous-versions/windows/internet-explorer/ie-developer/platform-apis/aa768196(v=vs.85)">IPropertyBag</a>*</b>

A pointer to an <a href="/previous-versions/windows/internet-explorer/ie-developer/platform-apis/aa768196(v=vs.85)">IPropertyBag</a> object that represents the property bag in which the property is stored.

### -param propName [in]

Type: <b>LPCWSTR</b>

A null-terminated property name string.

### -param value [out]

Type: <b><a href="/windows/desktop/api/wtypes/ns-wtypes-propertykey">PROPERTYKEY</a>*</b>

When this function returns, contains a pointer to a property key value.

## -returns

Type: <b>HRESULT</b>

If this function succeeds, it returns <b xmlns:loc="http://microsoft.com/wdcml/l10n">S_OK</b>. Otherwise, it returns an <b xmlns:loc="http://microsoft.com/wdcml/l10n">HRESULT</b> error code.

## -remarks

The property bag property function API converts between window types and the <b>VARIANT</b> type that is used to express values in a property bag. Doing so eases property bag usage, simplifies applications, and avoids common coding errors.

## -see-also

<a href="/windows/desktop/api/propsys/nf-propsys-pspropertybag_writepropertykey">PSPropertyBag_WritePropertyKey</a>