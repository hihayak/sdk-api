---
UID: NN:uiautomationclient.IUIAutomationProxyFactory
title: IUIAutomationProxyFactory (uiautomationclient.h)
description: Exposes properties and methods of an object that creates a Microsoft UI Automation provider for UI elements that do not have native support for UI Automation. This interface is implemented by proxies.
helpviewer_keywords: ["IUIAutomationProxyFactory","IUIAutomationProxyFactory interface [Windows Accessibility]","IUIAutomationProxyFactory interface [Windows Accessibility]","described","uiauto.uiauto_IUIAutomationProxyFactory","uiauto_IUIAutomationProxyFactory","uiautomationclient/IUIAutomationProxyFactory","winauto.uiauto_IUIAutomationProxyFactory"]
old-location: winauto\uiauto_IUIAutomationProxyFactory.htm
tech.root: WinAuto
ms.assetid: cdb2c94e-a5a7-41c3-b847-b23ea077abd3
ms.date: 12/05/2018
ms.keywords: IUIAutomationProxyFactory, IUIAutomationProxyFactory interface [Windows Accessibility], IUIAutomationProxyFactory interface [Windows Accessibility],described, uiauto.uiauto_IUIAutomationProxyFactory, uiauto_IUIAutomationProxyFactory, uiautomationclient/IUIAutomationProxyFactory, winauto.uiauto_IUIAutomationProxyFactory
req.header: uiautomationclient.h
req.include-header: UIAutomation.h
req.target-type: Windows
req.target-min-winverclnt: Windows 7, Windows Vista with SP2 and Platform Update for Windows Vista, Windows XP with SP3 and Platform Update for Windows Vista [desktop apps only]
req.target-min-winversvr: Windows Server 2008 R2, Windows Server 2008 with SP2 and Platform Update for Windows Server 2008, Windows Server 2003 with SP2 and Platform Update for Windows Server 2008 [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: UIAutomationClient.idl
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: UIAutomationCore.dll
req.irql: 
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
f1_keywords:
 - IUIAutomationProxyFactory
 - uiautomationclient/IUIAutomationProxyFactory
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - UIAutomationCore.dll
api_name:
 - IUIAutomationProxyFactory
---

# IUIAutomationProxyFactory interface


## -description

Exposes properties and methods of an object that creates a Microsoft UI Automation provider for UI elements that do not have native support for UI Automation. This interface is implemented by proxies.

## -inheritance

The <b xmlns:loc="http://microsoft.com/wdcml/l10n">IUIAutomationProxyFactory</b> interface inherits from the <a href="/windows/desktop/api/unknwn/nn-unknwn-iunknown">IUnknown</a> interface. <b>IUIAutomationProxyFactory</b> also has these types of members:
<ul>
<li><a href="https://docs.microsoft.com/">Methods</a></li>
<li><a href="https://docs.microsoft.com/">Properties</a></li>
</ul>

## -members

The <b>IUIAutomationProxyFactory</b> interface has these methods.
<table class="members" id="memberListMethods">
<tr>
<th align="left" width="37%">Method</th>
<th align="left" width="63%">Description</th>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="/windows/desktop/api/uiautomationclient/nf-uiautomationclient-iuiautomationproxyfactory-createprovider">CreateProvider</a>
</td>
<td align="left" width="63%">
Creates a proxy object that provides UI Automation support for a UI element.

</td>
</tr>
</table> 
<h3><a id="properties"></a>Properties</h3>The <b xmlns:loc="http://microsoft.com/wdcml/l10n">IUIAutomationProxyFactory</b> interface has these properties.
<table class="members" id="memberListProperties">
<tr>
<th align="left" width="27%">Property</th>
<th align="left" width="10%">Access type</th>
<th align="left" width="63%">Description</th>
</tr>
<tr data="declared;">
<td align="left" width="27%" xml:space="preserve">

<a href="/windows/desktop/api/uiautomationclient/nf-uiautomationclient-iuiautomationproxyfactory-get_proxyfactoryid">ProxyFactoryId</a>


</td>
<td align="left" width="10%">
Read-only

</td>
<td align="left" width="63%">
Retrieves the identifier of the proxy factory. 

</td>
</tr>
</table>

## -see-also

<a href="/windows/desktop/WinAuto/uiauto-client-proxyfactoryinterfaces">Proxy Factory Interfaces for Clients</a>