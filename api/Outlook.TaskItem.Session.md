---
title: TaskItem.Session Property (Outlook)
keywords: vbaol11.chm1684
f1_keywords:
- vbaol11.chm1684
ms.prod: outlook
api_name:
- Outlook.TaskItem.Session
ms.assetid: f2c0a916-b654-98de-c134-d9736d482cea
ms.date: 06/08/2017
localization_priority: Normal
---


# TaskItem.Session Property (Outlook)

Returns the  **[NameSpace](Outlook.NameSpace.md)** object for the current session. Read-only.


## Syntax

_expression_. `Session`

_expression_ A variable that represents a [TaskItem](./Outlook.TaskItem.md) object.


## Remarks

The  **Session** property and the **[GetNamespace](Outlook.Application.GetNamespace.md)** method can be used interchangeably to obtain the **NameSpace** object for the current session. Both members serve the same purpose. For example, the following statements do the same function:


```vb
Set objNamespace = Application.GetNamespace("MAPI") 
```


```vb
Set objSession = Application.Session
```


## See also


[TaskItem Object](Outlook.TaskItem.md)

[!include[Support and feedback](~/includes/feedback-boilerplate.md)]