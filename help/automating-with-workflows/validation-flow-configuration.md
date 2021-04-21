---
title: Adobe Campaign Classic에서 유효성 검사 워크플로우를 구성하는 방법
seo-title: Adobe Campaign Classic에서 유효성 검사 워크플로우를 구성하는 방법
description: 다양한 승인 유효성 검사 워크플로우를 구성하는 방법을 알아봅니다.
seo-description: 이 비디오에서는 ACCAadobe Campaign에서 배달 템플릿을 구성 및 사용하는 방법에 대해 설명합니다. 마케터는 배포 컨텐츠, 캠페인 대상, 데이터 추출 및 예산 승인을 검토하고 제공할 수 있는 여러 옵션을 제공합니다. 이 자습서에서는 다양한 승인 유효성 검사 워크플로우를 구성하는 방법에 대해 설명합니다.
uuid: fdeb7aef-95aa-4bc1-9c51-2eb7ce802107
discoiquuid: 29abc57d-c359-472d-817a-0671818894f0
feature: 워크플로우, 승인
kt: KT-1566
doc-type: feature video
activity: setup
team: TM
role: Business Practitioner
level: Experienced
exl-id: 34fbb91d-ae99-497c-872e-55ce2e6ea2aa
translation-type: tm+mt
source-git-commit: 137d1e0c36d038f3fb8a4742bafef6fbac96f41d
workflow-type: tm+mt
source-wordcount: '336'
ht-degree: 0%

---

# Adobe Campaign Classic에서 유효성 검사 워크플로우를 구성하는 방법

Adobe Campaign은 마케터가 전달 컨텐츠, 캠페인 목표, 데이터 추출 및 예산 승인을 검토하고 제공할 수 있는 여러 옵션을 제공합니다.

이 자습서에서는 다양한 승인 유효성 검사 워크플로우를 구성하는 방법에 대해 설명합니다.

## 필수 조건 {#prerequisite}

승인 단계를 활성화하기 전에 마케팅 팀은 개별 검토자를 정의해야 합니다.

* 승인 활동 내의 Adobe Campaign 리뷰어 역할은 단일 검토자(연산자) 또는 검토자 그룹(운영자 역할)일 수 있습니다.
* 검토자 및 검토자 그룹은 이전에 관리자 역할에 의해 Adobe Campaign에서 구성해야 합니다. 이렇게 하면 캠페인 개발자는 캠페인 또는 전달의 승인자로 검토자를 선택할 수 있습니다.

## 캠페인 {#configuring-approvals-for-campaigns}에 대한 승인 구성

캠페인 워크플로우의 모든 게재에 대해 동일한 검토자 세트가 있는 경우 [!DNL Campaign] 승인 기능을 활용할 수 있습니다. 캠페인 수준에서 승인 및 검토자를 설정하면 승인 작업 및 검토자가 워크플로우가 실행되면 워크플로우의 각 전달 활동으로 푸시됩니다.

>[!VIDEO](https://video.tv.adobe.com/v/25175?quality=12)

## 배달 승인 구성 {#configuring-approvals-for-deliveries}

전달 수준에서 승인을 설정할 수도 있습니다. 게재 승인 단계 및 검토자가 캠페인 승인 단계 및 검토자와 다를 경우, 게재 설정이 캠페인 설정을 덮어씁니다.

>[!VIDEO](https://video.tv.adobe.com/v/25176?quality=12)

## 승인 활동 구성 {#configuring-an-approval-activity}

게재 또는 캠페인 승인과 달리 승인 활동을 통해 워크플로우 내에서 승인 프로세스를 만들 수 있습니다. 이렇게 하면 배달을 실행하기 전에 타깃팅 선택 논리를 승인할 수 있습니다. 또한 필요한 경우 워크플로우 내에서 여러 수준에서 승인을 받을 수 있습니다.

>[!VIDEO](https://video.tv.adobe.com/v/25174?quality=12)

자세한 내용은 [승인 설명서](https://docs.adobe.com/help/en/campaign-classic/using/automating-with-workflows/flow-control-activities/approval.html)를 참조하십시오.
