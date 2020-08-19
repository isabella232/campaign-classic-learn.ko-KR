---
title: Campaign 컨트롤 패널
seo-title: Campaign 컨트롤 패널
description: Campaign 컨트롤 패널을 사용하면 인스턴스 및 허용 목록 IP 주소별로 SFTP 저장소를 모니터링하고 관리할 수 있습니다.
seo-description: Campaign 컨트롤 패널을 사용하면 인스턴스 및 허용 목록 IP 주소별로 SFTP 저장소를 모니터링하고 관리할 수 있습니다.
feature: Control Panel
topics: Control Panel
kt: 3262
doc-type: feature video
activity: use
team: PM
translation-type: tm+mt
source-git-commit: ca3b7933927914b9965f6f059293041dd1db1da2
workflow-type: tm+mt
source-wordcount: '419'
ht-degree: 100%

---


# [!UICONTROL Control Panel]

>[!NOTE]
>
>&#39;[!UICONTROL whitelist]&#39; 및 &#39;[!UICONTROL blacklist]&#39;라는 용어가 Adobe Campaign 설명서에서 &#39;[!UICONTROL allow list]&#39;및 &#39;[!UICONTROL block list]&#39;로 대체되었습니다.
>이러한 용어 중 일부는 제품 UI, 옵션 이름, 내부 코드 및 자습서 비디오에 여전히 존재할 수 있습니다. 향후 Campaign 컨트롤 패널 릴리스에서 대체될 예정입니다.

Adobe Campaign 관리자는 [!UICONTROL Control Panel]을(를) 통해 주요 자산을 모니터링하고 인스턴스 또는 [!UICONTROL allow list] IP 주소별 SFTP 저장소 관리와 같은 관리 작업을 수행할 수 있습니다.

## [!UICONTROL Control Panel]에 액세스 

Campaign 컨트롤 패널에 액세스하려면 다음의 Experience Cloud 홈으로 이동하십시오. [https://experiencecloud.adobe.com](https://experiencecloud.adobe.com):

* **[!UICONTROL Experience Cloud Home]** > **[!UICONTROL Quick Access]**

   또는
* **[!UICONTROL Experience Cloud Home]**  > [!UICONTROL Solution picker]: **Campaign** > **[!UICONTROL Control Panel]카드**

   또는

* 다음 URL에서 직접 액세스: [https://experience.adobe.com/#/controlpanel](https://experience.adobe.com/#/controlpanel)

## 사전 요구 사항

시작하기 전에 다음 사전 요구 사항을 완료하십시오.

### [!DNL IMS Org ID] 확인 

자신의 [!DNL IMS org ID]을(를) 알아야 합니다. 다음 비디오에서는 인스턴스의 [!DNL IMS org ID]을(를) 조회할 수 있는 위치를 설명합니다.

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)
*확인[!DNL IMS Org ID](00:26)*

### 관리자 권한

[!UICONTROL Control Panel]에 액세스하려면 관리자 권한이 필요합니다.
다음 비디오에서는 Campaign 인스턴스에 관리자를 추가하는 방법을 설명합니다.

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)
*[!UICONTROL Control Panel]을(를) 사용하기 위해 제품 프로필 &quot;[!UICONTROL Administrators]&quot;에 관리자를 추가하는 방법(01:03)*

## [!UICONTROL Control Panel] 자습서

* **SFTP 서버 관리**

   *서버 용량 모니터링,[!UICONTROL allow list]IP 주소 및 SSH 키 추가 방법*

   * [서버 용량 모니터링, 허용 목록 IP 주소 및 SSH 키 추가](/help/acc/monitoring-campaign-classic/control-panel/monitoring-server-capacity-allow-listing-adding-ssh-key.md)
   * [SSH 키 생성](/help/acc/monitoring-campaign-classic/control-panel/generate-ssh-key.md)
   * [SFTP 서버에 연결](/help/acc/monitoring-campaign-classic/control-panel/connect-to-sftp-server.md)

* **[하위 도메인 위임](/help/acc/monitoring-campaign-classic/control-panel/subdomain-delegation.md)**

   *하위 도메인을[!UICONTROL Adobe Campaign]*&#x200B;에 완전히 위임하는 방법을 알아봅니다.

* **[SSL 인증서 추가](/help/acc/monitoring-campaign-classic/control-panel/adding-ssl-certificates.md)**

   *Campaign 컨트롤 패널로 SSL 인증서를 추가하여 하위 도메인을 보호하는 방법을 배웁니다.*

* **[URL 권한 추가](/help/acc/monitoring-campaign-classic/control-panel/adding-url-permissions.md)**

   *인스턴스가 연결할 수 있도록 권한이 부여된 URL 목록에 일부 외부 URL을 추가하는 방법.*

* **[인스턴스 액세스에 대한 IP 허용 목록](/help/acc/monitoring-campaign-classic/control-panel/ip-allow-listing.md)**

   ** IP 주소 범위별로 인스턴스에 새 연결을 설정하는 방법을 배웁니다.[!UICONTROL allow listing]

* **[Google TXT 레코드 관리](/help/acc/monitoring-campaign-classic/control-panel/google-txt-record-management.md)**

   *[!UICONTROL Campaign Control Panel]을(를) 통해[!DNL GMAIL]주소로 이메일을 전송하는 데 사용되는 모든 하위 도메인에[!DNL Google TXT]사이트 확인 레코드를 추가하는 방법을 배웁니다.*

* **GPG 키 관리**

   *아웃바운드 데이터의 암호화를 위해 지정된 Campaign 인스턴스에 공개/개인 키 쌍을 생성 및 설치하고 인바운드 데이터의 암호 해독을 위해 Campaign 인스턴스에 공개 키를 가져와 설치하는 방법을 배웁니다.*

   * [데이터 암호화에 대한 GPG 키 생성 및 설치](./gpg-key-management/generating-and-installing-gpg-keys-for-data-encryption.md)
   * [GPG 키를 사용하여 데이터 암호화](./gpg-key-management/using-a-gpg-key-to-encrypt-data.md)
   * [데이터 암호 해독](./gpg-key-management/decrypting-data.md)

* **[Campaign 컨트롤 패널 문제 해결](/help/acc/monitoring-campaign-classic/control-panel/trouble-shooting.md)**

   *문제 해결 방법 이해[!UICONTROL Control Panel]*

## 추가 리소스

* [Campaign 컨트롤 패널 도움말 센터](https://docs.adobe.com/content/help/ko-KR/control-panel/using/control-panel-home.html)
