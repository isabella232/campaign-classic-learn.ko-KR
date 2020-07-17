---
title: 반복 및 연속 이메일 캠페인을 설정하는 방법
description: 이 자습서에서는 반복 및 연속 배달을 설정하는 방법과 ACC(Adobe Campaign Classic)에서 두 접근 방식 간의 차이점을 설명합니다.
feature: workflows
topics: channel activities
kt: 1560
doc-type: feature video
activity: use
team: TM
translation-type: tm+mt
source-git-commit: d1799d978a9a29f69d637178439fe770ffd4b281
workflow-type: tm+mt
source-wordcount: '272'
ht-degree: 0%

---


# 반복 및 연속 이메일 캠페인을 설정하는 방법

이 자습서에서는 반복 및 연속 배달을 설정하는 방법과 두 접근 방식 간의 차이점을 설명합니다.

## 반복 및 연속 배달 추적 {#recurring-and-continuous-delivery-tracking}

반복 및 연속 배달은 연락처 데이터의 관리 방식에 따라 다릅니다.

* 연속 배달 **** 기능을 사용하면 기존 전달에 새 받는 사람을 추가할 수 있으며 새 받는 사람이 추가될 때마다 새 배달을 만들지 않아도 됩니다. 캠페인 워크플로우에서 직접 크리에이티브를 업데이트할 수 있으며 게재 템플릿 리소스 폴더의 템플릿을 업데이트합니다.

   연속 배달은 SINGLE 배달 로그(broadLog)와 배달이 실행될 때마다 1개가 추가되었음을 참조하는 추적 로그를 만듭니다.

![연속 전달](/help/acc/assets/delivery_continuous.jpg)

* 반복 **배달은** 실행될 때마다 새 배달 인스턴스를 만듭니다. 예를 들어, 워크플로우가 일주일에 한 번 실행되도록 예약된 경우 1년 후에 52회의 배달이 됩니다. 또한 광범위한 로그 및 추적 로그가 각 배달 인스턴스로 구분됩니다.

![반복 배달](/help/acc/assets/delivery_recurring.jpg)

## 반복 배달을 설정하는 방법 {#how-to-set-up-a-recurring-delivery}

이 비디오에서는 반복 게재 및 스케줄러 활동을 구성하는 방법을 설명합니다.

>[!VIDEO](https://video.tv.adobe.com/v/25040?quality=12)

## 연속 배달을 설정하는 방법 {#how-to-set-up-a-continuous-delivery}

이 비디오에서는 증분 쿼리를 사용하여 연속 배달을 구성하는 방법을 보여 줍니다.

>[!VIDEO](https://video.tv.adobe.com/v/25039?quality=12)

## 추가 자료

[타깃팅 워크플로우에서 반복 배달 만들기](https://docs.adobe.com/content/help/en/campaign-classic/using/automating-with-workflows/use-cases/sending-a-birthday-email.html#creating-a-recurring-delivery-in-a-targeting-workflow)