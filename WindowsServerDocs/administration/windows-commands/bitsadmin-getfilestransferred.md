---
title: bitsadmin getfilestransferred
description: Windows Commands topic for **bitsadmin getfilestransferred**, which retrieves the number of files transferred for the specified job.
ms.prod: windows-server
ms.technology: manage-windows-commands
ms.topic: article
ms.assetid: e282815c-938b-4ac0-a09d-9baafb656dcb
author: coreyp-at-msft
ms.author: coreyp
manager: dongill
ms.date: 10/16/2017
---

# bitsadmin getfilestransferred

Retrieves the number of files transferred for the specified job.

## Syntax

```
bitsadmin /getfilestransferred <job>
```

### Parameters

| Parameter | Description |
| -------------- | -------------- |
| job | The job's display name or GUID. |

## <a name=BKMK_examples></a>Examples

The following example retrieves the number of files transferred in the job named *myDownloadJob*.

```
C:\>bitsadmin /getfilestransferred myDownloadJob
```

## Additional References

- [Command-Line Syntax Key](command-line-syntax-key.md)