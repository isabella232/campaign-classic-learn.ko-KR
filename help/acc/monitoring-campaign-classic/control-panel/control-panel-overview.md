---
title: 컨트롤 패널
seo-title: 컨트롤 패널
description: Campaign 컨트롤 패널을 사용하면 인스턴스 및 허용 목록 IP 주소별로 SFTP 저장소를 모니터링하고 관리할 수 있습니다.
seo-description: Campaign 컨트롤 패널을 사용하면 인스턴스 및 허용 목록 IP 주소별로 SFTP 저장소를 모니터링하고 관리할 수 있습니다.
feature: Control Panel
topics: Control Panel
kt: 3262
doc-type: feature video
activity: use
team: PM
translation-type: tm+mt
source-git-commit: 37c36a52fb6fc7a5ccfe5d82dc9a32397b9a7d89
workflow-type: tm+mt
source-wordcount: '441'
ht-degree: 6%

---


# [!UICONTROL Control Panel]

>[!NOTE]
>
>&#39;[!UICONTROL whitelist]&#39; 및 &#39;[!UICONTROL blacklist]&#39;라는 용어가 Adobe Campaign 설명서에서 &#39;[!UICONTROL allow list]&#39;및 &#39;[!UICONTROL block list]&#39;로 대체되었습니다.
>이러한 용어 중 일부는 제품 UI, 옵션 이름, 내부 코드 및 자습서 비디오에 여전히 존재할 수 있습니다. 향후 Campaign 컨트롤 패널 릴리스에서 교체될 예정입니다.

Adobe Campaign 관리자는 이 [!UICONTROL Control Panel] 를 통해 주요 자산을 모니터링하고 인스턴스 또는 [!UICONTROL allow list] IP 주소별 SFTP 저장소 관리와 같은 관리 작업을 수행할 수 있습니다.

## 액세스 [!UICONTROL Control Panel]

Campaign 컨트롤 패널에 액세스하려면 Experience Cloud 홈으로 이동합니다. [https://experiencecloud.adobe.com](https://experiencecloud.adobe.com):

* **[!UICONTROL Experience Cloud Home]** > **[!UICONTROL Quick Access]**

   또는
* **[!UICONTROL Experience Cloud Home]**  > [!UICONTROL Solution picker]: **캠페인** > **[!UICONTROL Control Panel]카드&#x200B;**

   또는

* URL에서 바로 [https://experience.adobe.com/#/controlpanel](https://experience.adobe.com/#/controlpanel)

## 사전 요구 사항

시작하기 전에 다음 전제 조건을 완료하십시오.

### 확인 [!DNL IMS Org ID]

당신 자신을 알아야 [!DNL IMS org ID]해요 다음 비디오에서는 인스턴스의 조회 위치를 설명합니다 [!DNL IMS org ID].

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)
*확인[!DNL IMS Org ID](00:26분)*

### 관리자 권한

이 파일에 액세스하려면 관리자 권한이 필요합니다 [!UICONTROL Control Panel].
다음 비디오에서는 캠페인 인스턴스에 관리자를 추가하는 방법을 설명합니다

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)
*제품 프로필 &quot;[!UICONTROL Administrators]&quot;에 관리자를 추가하여 사용할 수 있는 방법[!UICONTROL Control Panel](01:03분)*

## [!UICONTROL Control Panel] 자습서

* **SFTP 서버 관리**

   *서버 용량,[!UICONTROL allow list]IP 주소 모니터링 및 SSH 키 추가 방법*

   * [서버 용량 모니터링, IP 주소 나열 허용 및 SSH 키 추가](/help/acc/monitoring-campaign-classic/control-panel/monitoring-server-capacity-allow-listing-adding-ssh-key.md)
   * [SSH 키 생성](/help/acc/monitoring-campaign-classic/control-panel/generate-ssh-key.md)
   * [SFTP 서버에 연결](/help/acc/monitoring-campaign-classic/control-panel/connect-to-sftp-server.md)

* **[하위 도메인 위임](/help/acc/monitoring-campaign-classic/control-panel/subdomain-delegation.md)**

   *하위 도메인을[!UICONTROL Adobe Campaign]*

* **[SSL 인증서 추가](/help/acc/monitoring-campaign-classic/control-panel/adding-ssl-certificates.md)**

   *SSL 인증서를 추가하여 Campaign 컨트롤 패널을 사용하여 하위 도메인을 보호하는 방법을 알아봅니다.*

* **[SSL 인증서 관리](/help/acc/monitoring-campaign-classic/control-panel/managing-ssl-certificates.md)**

   *하위 도메인의 SSL 인증서 상태 및 요청 갱신을 확인하는 방법을 알아봅니다.*

* **[URL 권한 추가](/help/acc/monitoring-campaign-classic/control-panel/adding-url-permissions.md)**

   *인스턴스가 URL에 연결할 수 있도록 외부 URL을 인증된 URL 목록에 추가하는 방법*

* **[인스턴스 액세스에 대한 IP 허용 목록](/help/acc/monitoring-campaign-classic/control-panel/ip-allow-listing.md)**

   *IP 주소 범위별로 인스턴스에 새 연결을 설정하는 방법을[!UICONTROL allow listing]알아봅니다.*

* **[Google TXT 레코드 관리](/help/acc/monitoring-campaign-classic/control-panel/google-txt-record-management.md)**

   *을 통해 주소로 이메일을 전송하는 데 사용되는 모든 하위 도메인에[!DNL Google TXT]사이트 확인 레코드를 추가하는 방법을[!DNL GMAIL]알아보십시오[!UICONTROL Campaign Control Panel].*

* **GPG 키 관리**

   *아웃바운드 데이터의 암호화를 위해 지정된 캠페인 인스턴스에 공개/비공개 키 쌍을 생성 및 설치하고 인바운드 데이터의 암호 해독을 위해 캠페인 인스턴스에 공개 키를 가져와 설치하는 방법을 알아봅니다.*

   * [데이터 암호화에 대한 GPG 키 생성 및 설치](./gpg-key-management/generating-and-installing-gpg-keys-for-data-encryption.md)
   * [GPG 키를 사용하여 데이터 암호화](./gpg-key-management/using-a-gpg-key-to-encrypt-data.md)
   * [데이터 암호 해독](./gpg-key-management/decrypting-data.md)

* **[컨트롤 패널 문제 해결](/help/acc/monitoring-campaign-classic/control-panel/trouble-shooting.md)**

   *문제 해결 방법 이해[!UICONTROL Control Panel]*

## 추가 자료

* [Campaign 컨트롤 패널 도움말 센터](https://docs.adobe.com/content/help/ko-KR/control-panel/using/control-panel-home.html)
