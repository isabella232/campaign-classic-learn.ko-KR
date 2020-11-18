---
title: Android용 푸시 알림 시작하기 - 소개
description: 이 자습서는 Adobe Campaign에서 푸시 알림을 전송하고 Android 앱에서 이러한 알림을 받는 것과 관련된 단계를 설명합니다.
feature: push
topics: mobile channels
kt: 6438
doc-type: article
activity: setup
team: TM
translation-type: tm+mt
source-git-commit: 412fe93f45be1e98343b4e63cbd7dd9285444e46
workflow-type: tm+mt
source-wordcount: '389'
ht-degree: 6%

---


# Android용 푸시 알림 시작하기 - 소개

Adobe Campaign allows you to send personalized and segmented [!DNL push] notifications to [!DNL iOS] and [!DNL Android ]mobile devices.

이 자습서에서는 Adobe Campaign에서 앱으로 [!DNL push] 알림을 전송하는 데 관련된 단계를 [!DNL Android] 안내합니다.

## 사전 요구 사항

시작하기 전에 다음 사전 요구 사항을 충족해야 합니다

1) 모바일 응용 프로그램이 자습서에서는 모바일 응용 프로그램을 설정하는 데 필요한 세부 단계를 다루지 않습니다. 통합된 **[!DNL Android]모바일 애플리케이션이 필요합니다[!DNL Campaign SDK]** .

   * Campaign SDK를 모바일 애플리케이션에 [통합하는 데 필요한 단계에 대한 자세한 설명을 볼 수 있습니다](https://experienceleague.adobe.com/docs/campaign-classic/using/sending-messages/sending-push-notifications/integrating-campaign-sdk-into-the-mobile-application.html).

   * Experience Platform Mobile SDK를 사용할 수도 있습니다. 자세한 내용은 Experience Platform [Mobile SDK](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/push-channel/configure-push-using-aep-mobile-sdk.html) 자습서 비디오를 사용하여 푸시 채널 구성을 참조하십시오.

2) 모바일 앱 채널 패키지가 설치됨

   인스턴스에 모바일 앱 채널 패키지를 설치해야 합니다. 다음 비디오에서는 모바일 앱 채널이 인스턴스에 설치되어 있는지 확인하는 방법과 설치되어 있지 않은지 확인하는 방법을 설명합니다.

>[!VIDEO](https://video.tv.adobe.com/v/326544?quality=12)

## 자습서

Adobe는 Neotrip 모바일 앱의 가입자에게 개인화된 홍보 푸시 알림을 전송하려고 [!DNL Android] 합니다. Neotrip 앱은 Campaign SDK로 구성되며 Adobe에서는 Campaign 인스턴스에서 모바일 앱 채널이 활성화되었는지 확인합니다.

다음 구성 단계가 필요합니다.

### 1단계:앱 구독 스키마를 확장하여 푸시 알림 개인화

푸시 알림을 개인화하고 싶은 경우, 먼저 사용자가 서비스에 가입하면 앱에서 받은 개인화 값을 저장할 수 있도록 앱 구독 스키마 [를](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md) 확장할 것입니다.

### 2단계:Android 서비스를 구성하고 Campaign에서 모바일 앱 응용 프로그램 만들기

다음으로 Android 서비스를 [구성하고 Campaign에서 모바일 앱 응용 프로그램을 만들어야 합니다](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-an-android-service-in-campaign.md). 이 단계에서는 푸시 알림의 대상으로 Neotrip 앱을 정의합니다.

### 3단계:푸시 알림 구성 및 전송

그러면 푸시 알림을 [구성하고 전송할 준비가 됩니다](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-and-sending-push-notifications.md).

## 튜토리얼 시작

**[1단계:앱 구독 스키마 확장](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md)**
