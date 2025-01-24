---
UID: NF:appmodel.VerifyPackageFamilyName
title: VerifyPackageFamilyName
description: Verifies whether or not a package family name is syntactically valid.
ms.date: 01/24/2025
tech.root: appxpkg
targetos: Windows
req.assembly: 
req.construct-type: function
req.ddi-compliance: 
req.dll: 
req.header: appmodel.h
req.idl: 
req.include-header: 
req.irql: 
req.kmdf-ver: 
req.lib: 
req.max-support: 
req.namespace: 
req.redist: 
req.target-min-winverclnt: Windows 10
req.target-min-winversvr: 
req.target-type: 
req.type-library: 
req.umdf-ver: 
req.unicode-ansi: 
topic_type:
 - apiref
api_type:
 - HeaderDef
api_location:
 - appmodel.h
api_name:
 - VerifyPackageFamilyName
f1_keywords:
 - VerifyPackageFamilyName
 - appmodel/VerifyPackageFamilyName
dev_langs:
 - c++
dev_langs:
 - c++
helpviewer_keywords:
 - VerifyPackageFamilyName
---

## -description

Verifies whether or not a package family name is syntactically valid.

## -parameters

### -param packageFamilyName

Type: \_In\_ **[PCWSTR](/windows/win32/winprog/windows-data-types)**

The package family name to verify.

## -returns

Type: **LONG**

Returns **ERROR_SUCCESS** if the input is syntactically valid; otherwise **ERROR_INVALID_PARAMETER**.

## -remarks

## -see-also
