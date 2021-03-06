---
title: ksetup:setcomputerpassword
description: Reference topic for **** - 

ms.prod: windows-server


ms.technology: manage-windows-commands

ms.topic: article
ms.assetid: e307d8f6-3b93-4c24-ac04-f31549f7dc7d
author: coreyp-at-msft
ms.author: coreyp
manager: dongill
ms.date: 10/16/2017
---

# ksetup:setcomputerpassword



Sets the password for the local computer.

## Syntax

```
ksetup /setcomputerpassword <Password>
```

#### Parameters

|Parameter|Description|
|---------|-----------|
|\<Password>|Uses the supplied password to set the computer account on the local computer.</br>The password can only be set by using an account with administrative privileges. The password can be from 1 to 156 alphanumeric or special characters.|

## Remarks

This command affects the computer account only.

You must restart the computer for the password change to take effect.

The computer account password is not displayed in the registry or as output from the **ksetup** command.

## Examples

Change the computer account password on the local computer from IPops897 to IPop$897!.
```
ksetup /setcomputerpassword IPop$897!
```

## Additional References

-   [Ksetup](ksetup.md)
-   - [Command-Line Syntax Key](command-line-syntax-key.md)