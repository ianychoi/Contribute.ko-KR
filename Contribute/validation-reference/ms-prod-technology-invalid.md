---
title: ms-prod-and-technology-invalid
description: Docs 빌드 문제 ms-prod-and-technology-invalid에 대한 설명 및 해결 방법
author: meganbradley
ms.author: mbradley
ms.topic: error-reference
ms.date: 1/15/2019
ms.prod: non-product-specific
ms.openlocfilehash: 8c6f12629cf4b8cf7fd2471ef4d1287562435696
ms.sourcegitcommit: 8e897e90268a8a87dc4b97d7c28d22ed5950c8d9
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 03/29/2019
ms.locfileid: "58636842"
---
# <a name="ms-prod-and-technology-invalid"></a>ms-prod-and-technology-invalid

## <a name="warning"></a>경고

`Invalid value for ms.prod: '{value}'.`

`Invalid value for ms.technology: '{value}' is not valid with ms.prod value '{value}'.`

`ms.prod`를 사용하여 온-프레미스 제품을 지정합니다. `ms.prod`에 대한 더 자세한 정보를 지정하려면 필요에 따라 `ms.technology`를 지정하면 됩니다. `ms.prod` 및 `ms.technology`의 값은 유효한 쌍이어야 합니다. `ms.prod` 값이 잘못되었거나, `ms.technology` 값이 `ms.prod`와 유효한 쌍이 아닙니다.

## <a name="resolution"></a>해결 방법

`ms.prod` 값이 문서에 적합한지 확인합니다. 그런 다음, 유효한 `ms.technology` 값을 선택합니다.

유효한 값은 [이 Microsoft 내부 사이트](https://docsmetadatatool.azurewebsites.net/allowlists)에서 찾을 수 있습니다.

<!--make sure to add this file to your includes folder and verify the path-->
[!INCLUDE [validation-reference-help](includes/validation-reference-help.md)]
