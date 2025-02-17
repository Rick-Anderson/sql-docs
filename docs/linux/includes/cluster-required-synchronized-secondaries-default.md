---
author: rwestMSFT
ms.author: randolphwest
ms.date: 06/28/2024
ms.service: sql
ms.subservice: linux
ms.topic: include
ms.custom:
  - linux-related-content
---
> [!NOTE]  
> When you create the resource, and periodically afterwards, the Pacemaker resource agent automatically sets the value of `REQUIRED_SYNCHRONIZED_SECONDARIES_TO_COMMIT` on the availability group based on the availability group's configuration. For example, if the availability group has three synchronous replicas, the agent will set `REQUIRED_SYNCHRONIZED_SECONDARIES_TO_COMMIT` to `1`. For details and additional configuration options, see [High availability and data protection for availability group configurations](../sql-server-linux-availability-group-ha.md).
