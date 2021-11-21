---
title: Campaign 컨트롤 패널 문제 해결
description: Campaign 컨트롤 패널을 사용하면 인스턴스 및 IP 주소별로 SFTP 저장소를 모니터링하고 관리할 허용 목록에 추가하다 수 있습니다.
feature: Control Panel
kt: 2938
doc-type: article
activity: use
team: PM
source-git-commit: 8910430585bdaa0db076db9c34b34798f649d39c
workflow-type: tm+mt
source-wordcount: '330'
ht-degree: 80%

---


# [!UICONTROL Control Panel] 문제 해결

## 로그인 및 홈페이지

### 증상: Experience Cloud에 로그인할 수 없음

**해결 방법:**
사용자는 IMS 조직 ID(xxx)를 찾아야 합니다. 관리자는 관리하려는 각 인스턴스에 대해 제품 프로필 &quot;Campaign-xxx-Admins&quot;에 사용자를 추가해야 합니다. 사용자가 모든 인스턴스의 관리자인 경우에도 자신을 사용자로 추가해야 할 수 있습니다.

### 증상: Experience Cloud 홈에서 [!UICONTROL Control Panel]로 액세스하는 링크가 사용자에게 표시되지 않음

**원인:**
사용자는 제품 프로필 _Campaign-xxx-Administrators/Admin_&#x200B;에 사용자로 추가될 때까지 링크를 볼 수 없습니다.

**해결 방법:**
관리자는 관리하려는 각 인스턴스에 대해 제품 프로필 _Campaign-xxx-Admins_&#x200B;에 사용자를 추가해야 합니다. 사용자가 모든 인스턴스의 관리자인 경우 자신을 &quot;사용자&quot;로 추가해야 합니다.

### 증상: 인스턴스가 [!UICONTROL Control Panel]에 나열되지 않음

**원인:**
사용자는 &quot;사용자&quot; 제품 프로필로 추가해야 합니다 _Campaign-xxx-Administrators/Admin_ 누락된 인스턴스에 대해

**해결 방법:** 관리자는 관리하려는 각 인스턴스에 대해 제품 프로필 _Campaign-xxx-Admins_&#x200B;에 사용자를 추가해야 합니다. 사용자가 모든 인스턴스의 관리자인 경우에도 자신을 &quot;사용자&quot;로 추가해야 할 수 있습니다.

### 유용한 비디오

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)

*IMS 조직 ID 확인(00:26)*

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)

*[!UICONTROL Control panel]을(를) 사용하기 위해 제품 프로필 관리자에 관리자를 추가하는 방법(01:03)*

### 유용한 설명서

* [Campaign 컨트롤 패널 살펴보기](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=ko)
* [[!UICONTROL Control Panel]에 대한 권한 관리](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en)

## SFTP 서버에 연결 설정(클라이언트 또는 API)

SFTP 서버에 연결하려면 다음이 필요합니다.

* [!UICONTROL Allow listing] SFTP 서버에 연결할 IP 주소
* Adobe Campaign에 등록해야 하는 개인/공개 키 쌍
* SFTP 서버에 직접 연결하는 경우 SFTP 클라이언트 소프트웨어가 필요합니다

### 유용한 설명서 {#helpful-docs}

* [SFTP 서버에 로그인](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en)

