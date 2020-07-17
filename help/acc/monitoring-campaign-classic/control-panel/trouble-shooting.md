---
title: 문제 촬영 Campaign 컨트롤 패널
description: Campaign 컨트롤 패널을 사용하면 인스턴스 및 허용 목록 IP 주소별로 SFTP 저장소를 모니터링하고 관리할 수 있습니다.
feature: Control Panel
topics: Control Panel
kt: 2938
doc-type: article
activity: use
team: PM
translation-type: tm+mt
source-git-commit: b2820c65a88d25f9b7a4ed5005cd5083463e000a
workflow-type: tm+mt
source-wordcount: '339'
ht-degree: 1%

---


# 문제 사격 [!UICONTROL Control Panel]

## 로그인 및 홈 페이지

### 증상: Experience Cloud에 로그인할 수 없습니다.

**방법:**
사용자는 IMS 조직 ID(xxx)를 찾아야 합니다. 관리자는 관리하려는 각 인스턴스에 대해 제품 프로필 &quot;Campaign-xxx-Admins&quot;에 사용자를 추가해야 합니다. 사용자가 모든 인스턴스의 관리자인 경우에도 사용자를 사용자로 추가해야 할 수 있습니다.

### 증상: Experience Cloud 홈에서 액세스할 수 있는 링크가 사용자에게 나타나지 [!UICONTROL Control Panel] 않습니다.

**원인:**
사용자는 제품 프로필 _Campaign-xxx-Administrators/Admin에 사용자로 추가될 때까지 링크를 볼 수 없습니다_.

**방법:**
관리자는 관리하려는 각 인스턴스에 대해 제품 프로필 _캠페인-xxx-Admins_ 에 사용자를 추가해야 합니다. 사용자가 모든 인스턴스의 관리자인 경우에도 자신을 &quot;사용자&quot;로 추가해야 할 수 있습니다.

### 증상: 인스턴스가 [!UICONTROL Control Panel]

**원인:**
누락된 인스턴스에 대해 &quot;사용자&quot; 제품 프로필 _Campaign-xxx-Administrators/Admin_ 으로 사용자를 추가해야 합니다.

**방법:**
관리자는 관리하려는 각 인스턴스에 대해 제품 프로필 _캠페인-xxx-Admins_ 에 사용자를 추가해야 합니다. 사용자가 모든 인스턴스의 관리자인 경우에도 자신을 &quot;사용자&quot;로 추가해야 할 수 있습니다.

### 유용한 비디오

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)
*IMS 조직 ID 확인(00:26분)*

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)
*제품 프로필 관리자에 관리자를 추가하여 사용할 수 있는 방법[!UICONTROL Control panel](01분 3초)*

### 유용한 설명서

* [Campaign 컨트롤 패널 검색](https://helpx.adobe.com/campaign/kb/control-panel-overview.html)
* [에 대한 권한 관리 [!UICONTROL Control Panel]](https://helpx.adobe.com/campaign/kb/control-panel-access.html)

## SFTP 서버에 연결 설정(클라이언트 또는 API)

SFTP 서버에 연결하려면 다음이 필요합니다.

* [!UICONTROL Allow listing] SFTP 서버에 연결하는 IP 주소
* Adobe Campaign에 등록해야 하는 개인/공개 키 쌍
* SFTP 서버에 직접 연결하는 경우 SFTP 클라이언트 소프트웨어도 필요합니다

### 유용한 설명서

* [SFTP 서버에 로그인](https://helpx.adobe.com/campaign/kb/control-panel-sftp.html#LoggingintoyourSFTPserver)

