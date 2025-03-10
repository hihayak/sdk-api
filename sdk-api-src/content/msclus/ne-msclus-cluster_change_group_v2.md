---
UID: NE:msclus.CLUSTER_CHANGE_GROUP_V2
title: CLUSTER_CHANGE_GROUP_V2 (msclus.h)
description: Defines the list of notifications that are generated for a group.
helpviewer_keywords: ["CLUSTER_CHANGE_GROUP_ALL_V2","CLUSTER_CHANGE_GROUP_COMMON_PROPERTY_V2","CLUSTER_CHANGE_GROUP_DELETED_V2","CLUSTER_CHANGE_GROUP_HANDLE_CLOSE_V2","CLUSTER_CHANGE_GROUP_OWNER_NODE_V2","CLUSTER_CHANGE_GROUP_PREFERRED_OWNERS_V2","CLUSTER_CHANGE_GROUP_PRIVATE_PROPERTY_V2","CLUSTER_CHANGE_GROUP_RESOURCE_ADDED_V2","CLUSTER_CHANGE_GROUP_RESOURCE_GAINED_V2","CLUSTER_CHANGE_GROUP_RESOURCE_LOST_V2","CLUSTER_CHANGE_GROUP_STATE_V2","CLUSTER_CHANGE_GROUP_V2","CLUSTER_CHANGE_GROUP_V2 enumeration [Failover Cluster]","clusapi/CLUSTER_CHANGE_GROUP_ALL_V2","clusapi/CLUSTER_CHANGE_GROUP_COMMON_PROPERTY_V2","clusapi/CLUSTER_CHANGE_GROUP_DELETED_V2","clusapi/CLUSTER_CHANGE_GROUP_HANDLE_CLOSE_V2","clusapi/CLUSTER_CHANGE_GROUP_OWNER_NODE_V2","clusapi/CLUSTER_CHANGE_GROUP_PREFERRED_OWNERS_V2","clusapi/CLUSTER_CHANGE_GROUP_PRIVATE_PROPERTY_V2","clusapi/CLUSTER_CHANGE_GROUP_RESOURCE_ADDED_V2","clusapi/CLUSTER_CHANGE_GROUP_RESOURCE_GAINED_V2","clusapi/CLUSTER_CHANGE_GROUP_RESOURCE_LOST_V2","clusapi/CLUSTER_CHANGE_GROUP_STATE_V2","clusapi/CLUSTER_CHANGE_GROUP_V2","msclus/CLUSTER_CHANGE_GROUP_ALL_V2","msclus/CLUSTER_CHANGE_GROUP_COMMON_PROPERTY_V2","msclus/CLUSTER_CHANGE_GROUP_DELETED_V2","msclus/CLUSTER_CHANGE_GROUP_HANDLE_CLOSE_V2","msclus/CLUSTER_CHANGE_GROUP_OWNER_NODE_V2","msclus/CLUSTER_CHANGE_GROUP_PREFERRED_OWNERS_V2","msclus/CLUSTER_CHANGE_GROUP_PRIVATE_PROPERTY_V2","msclus/CLUSTER_CHANGE_GROUP_RESOURCE_ADDED_V2","msclus/CLUSTER_CHANGE_GROUP_RESOURCE_GAINED_V2","msclus/CLUSTER_CHANGE_GROUP_RESOURCE_LOST_V2","msclus/CLUSTER_CHANGE_GROUP_STATE_V2","msclus/CLUSTER_CHANGE_GROUP_V2","mscs.cluster_change_group_v2"]
old-location: mscs\cluster_change_group_v2.htm
tech.root: MsCS
ms.assetid: 0D7871CA-A186-4693-AD0B-2FA8CF25D634
ms.date: 12/05/2018
ms.keywords: CLUSTER_CHANGE_GROUP_ALL_V2, CLUSTER_CHANGE_GROUP_COMMON_PROPERTY_V2, CLUSTER_CHANGE_GROUP_DELETED_V2, CLUSTER_CHANGE_GROUP_HANDLE_CLOSE_V2, CLUSTER_CHANGE_GROUP_OWNER_NODE_V2, CLUSTER_CHANGE_GROUP_PREFERRED_OWNERS_V2, CLUSTER_CHANGE_GROUP_PRIVATE_PROPERTY_V2, CLUSTER_CHANGE_GROUP_RESOURCE_ADDED_V2, CLUSTER_CHANGE_GROUP_RESOURCE_GAINED_V2, CLUSTER_CHANGE_GROUP_RESOURCE_LOST_V2, CLUSTER_CHANGE_GROUP_STATE_V2, CLUSTER_CHANGE_GROUP_V2, CLUSTER_CHANGE_GROUP_V2 enumeration [Failover Cluster], clusapi/CLUSTER_CHANGE_GROUP_ALL_V2, clusapi/CLUSTER_CHANGE_GROUP_COMMON_PROPERTY_V2, clusapi/CLUSTER_CHANGE_GROUP_DELETED_V2, clusapi/CLUSTER_CHANGE_GROUP_HANDLE_CLOSE_V2, clusapi/CLUSTER_CHANGE_GROUP_OWNER_NODE_V2, clusapi/CLUSTER_CHANGE_GROUP_PREFERRED_OWNERS_V2, clusapi/CLUSTER_CHANGE_GROUP_PRIVATE_PROPERTY_V2, clusapi/CLUSTER_CHANGE_GROUP_RESOURCE_ADDED_V2, clusapi/CLUSTER_CHANGE_GROUP_RESOURCE_GAINED_V2, clusapi/CLUSTER_CHANGE_GROUP_RESOURCE_LOST_V2, clusapi/CLUSTER_CHANGE_GROUP_STATE_V2, clusapi/CLUSTER_CHANGE_GROUP_V2, msclus/CLUSTER_CHANGE_GROUP_ALL_V2, msclus/CLUSTER_CHANGE_GROUP_COMMON_PROPERTY_V2, msclus/CLUSTER_CHANGE_GROUP_DELETED_V2, msclus/CLUSTER_CHANGE_GROUP_HANDLE_CLOSE_V2, msclus/CLUSTER_CHANGE_GROUP_OWNER_NODE_V2, msclus/CLUSTER_CHANGE_GROUP_PREFERRED_OWNERS_V2, msclus/CLUSTER_CHANGE_GROUP_PRIVATE_PROPERTY_V2, msclus/CLUSTER_CHANGE_GROUP_RESOURCE_ADDED_V2, msclus/CLUSTER_CHANGE_GROUP_RESOURCE_GAINED_V2, msclus/CLUSTER_CHANGE_GROUP_RESOURCE_LOST_V2, msclus/CLUSTER_CHANGE_GROUP_STATE_V2, msclus/CLUSTER_CHANGE_GROUP_V2, mscs.cluster_change_group_v2
req.header: msclus.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: None supported
req.target-min-winversvr: Windows Server 2012
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: 
req.irql: 
targetos: Windows
req.typenames: CLUSTER_CHANGE_GROUP_V2
req.redist: 
ms.custom: 19H1
f1_keywords:
 - CLUSTER_CHANGE_GROUP_V2
 - msclus/CLUSTER_CHANGE_GROUP_V2
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - HeaderDef
api_location:
 - ClusAPI.h
 - MsClus.h
api_name:
 - CLUSTER_CHANGE_GROUP_V2
---

# CLUSTER_CHANGE_GROUP_V2 enumeration


## -description

Defines the list of notifications that are generated for a group.

## -enum-fields

### -field CLUSTER_CHANGE_GROUP_DELETED_V2

Indicates that a group was deleted.

### -field CLUSTER_CHANGE_GROUP_COMMON_PROPERTY_V2

Indicates that a group's common property changed.

### -field CLUSTER_CHANGE_GROUP_PRIVATE_PROPERTY_V2

Indicates that a group's private property changed.

### -field CLUSTER_CHANGE_GROUP_STATE_V2

Indicates that the group's state changed.

### -field CLUSTER_CHANGE_GROUP_OWNER_NODE_V2

Indicates that the group's owner node has changed.

### -field CLUSTER_CHANGE_GROUP_PREFERRED_OWNERS_V2

Indicates that the group's preferred owners have changed.

### -field CLUSTER_CHANGE_GROUP_RESOURCE_ADDED_V2

Indicates that a resource was added to the group.

### -field CLUSTER_CHANGE_GROUP_RESOURCE_GAINED_V2

Indicates that the group gained a resource.

### -field CLUSTER_CHANGE_GROUP_RESOURCE_LOST_V2

Indicates that a resource is no longer part of the group.

### -field CLUSTER_CHANGE_GROUP_HANDLE_CLOSE_V2

Indicates that the group's context handle was closed.

### -field CLUSTER_CHANGE_GROUP_ALL_V2

Indicates all V2 group notifications.

## -remarks

Protocol version 2.0 servers do not support this enumeration.

