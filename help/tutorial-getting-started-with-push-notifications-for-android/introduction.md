---
title: 자습서 소개
description: 이 자습서는 Adobe Campaign에서 푸시 알림을 전송하고 Android 앱에서 이러한 알림을 받는 것과 관련된 단계를 설명합니다.
feature: push
topics: mobile channels
kt: 6438
doc-type: article
activity: setup
team: TM
translation-type: tm+mt
source-git-commit: 9b26dfd30e60c3e12c52e4318a853498af186b4a
workflow-type: tm+mt
source-wordcount: '353'
ht-degree: 9%

---


# 자습서 소개

Adobe Campaign allows you to send personalized and segmented [!DNL push] notifications to [!DNL iOS] and [!DNL Android] mobile devices. 이 자습서에서는 Adobe Campaign에서 앱으로 [!DNL push] 알림을 전송하는 데 관련된 단계를 [!DNL Android] 안내합니다.

## 사전 요구 사항

시작하려면 먼저 다음을 수행해야 합니다.

1) **Android 모바일 애플리케이션**

   이 자습서에서는 모바일 응용 프로그램을 설정하는 데 필요한 세부 단계를 다루지 않습니다. 통합된 **[!DNL Android]모바일 애플리케이션이 필요합니다 [!DNL Campaign SDK]**.

   제품 설명서에서 필요한 단계에 대한 자세한 설명을 확인할 수 있습니다.

   [모바일 애플리케이션에 Campaign SDK 통합](https://experienceleague.adobe.com/docs/campaign-classic/using/sending-messages/sending-push-notifications/integrating-campaign-sdk-into-the-mobile-application.html)

   Experience Platform Mobile SDK를 사용할 수도 있습니다. 자세한 내용은 튜토리얼 비디오를 참조하십시오.

   [Experience Platform Mobile SDK를 사용하여 푸시 채널 구성](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/push-channel/configure-push-using-aep-mobile-sdk.html)

2) **[!DNL Mobile App channel]패키지 설치**

   패키지 [!DNL Mobile App channel] 를 인스턴스에 설치해야 [!DNL Campaign] 합니다. 다음 비디오에서는 인스턴스에 설치되어 있는지 확인하는 방법 [!DNL Mobile App channel] 과 설치되어 있지 않은지 확인하는 방법을 설명합니다.

>[!VIDEO](https://video.tv.adobe.com/v/326544?quality=12)

## 자습서 개요

모바일 앱의 가입자에게 개인화된 홍보 [!DNL push] 알림을 [!DNL Neotrip] [!DNL Android] 전송하려고 합니다. 이 [!DNL Neotrip] 앱은 이 [!DNL Campaign SDK] 로 구성되었으며 인스턴스에서 [!DNL Mobile App channel] 활성화되도록 [!DNL Campaign] 했습니다.

다음 구성 단계가 필요합니다.

### 1단계:앱 구독 스키마를 확장하여 [!DNL push] 알림 개인화

Adobe는 [!DNL push] 알림을 개인화하고자 하므로 사용자가 서비스에 가입했을 때 앱으로부터 받은 개인화 값을 저장할 수 있도록 먼저 앱 구독 스키마를 [확장할 것입니다](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md) .

### 2단계:Android 서비스를 구성하고 Campaign에서 모바일 애플리케이션 만들기

다음으로 Android 서비스를 [구성하고 Campaign에서 모바일 애플리케이션을 만들어야 합니다](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-an-android-service-in-campaign.md). 이 단계에서는 [!DNL Neotrip] 앱을 푸시 알림의 대상으로 정의합니다.

### 3단계:푸시 알림 구성 및 전송

그러면 푸시 알림을 [구성하고 전송할 준비가 됩니다](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-and-sending-push-notifications.md).

## 튜토리얼 시작

1단계: [앱 구독 스키마 확장](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md)
