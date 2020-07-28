---
title: Adobe Campaign Classic에서 유효성 검사 워크플로우를 구성하는 방법
seo-title: Adobe Campaign Classic에서 유효성 검사 워크플로우를 구성하는 방법
description: Adobe Campaign은 마케터가 전달 컨텐츠, 캠페인 목표, 데이터 추출 및 예산 승인을 검토하고 제공할 수 있는 여러 옵션을 제공합니다. 이 자습서에서는 다양한 승인 유효성 검사 워크플로우를 구성하는 방법을 설명합니다.
seo-description: 이 비디오에서는 ACAadobe Campaign에서 배달 템플릿을 구성 및 사용하는 방법에 대해 설명합니다. 마케터는 배포 컨텐츠, 캠페인 대상, 데이터 추출 및 예산 승인을 검토하고 제공할 수 있는 여러 옵션을 제공합니다. 이 자습서에서는 다양한 승인 유효성 검사 워크플로우를 구성하는 방법을 설명합니다.
uuid: fdeb7aef-95aa-4bc1-9c51-2eb7ce802107
discoiquuid: 29abc57d-c359-472d-817a-0671818894f0
feature: Workflow
topics: Validation
kt: KT-1566
doc-type: feature video
activity: setup
team: TM
translation-type: tm+mt
source-git-commit: b2820c65a88d25f9b7a4ed5005cd5083463e000a
workflow-type: tm+mt
source-wordcount: '357'
ht-degree: 0%

---


# Adobe Campaign Classic에서 유효성 검사 워크플로우를 구성하는 방법

Adobe Campaign은 마케터가 전달 컨텐츠, 캠페인 목표, 데이터 추출 및 예산 승인을 검토하고 제공할 수 있는 여러 옵션을 제공합니다.

이 자습서에서는 다양한 승인 유효성 검사 워크플로우를 구성하는 방법을 설명합니다.

## 사전 요구 사항 {#prerequisite}

승인 단계를 활성화하기 전에 마케팅 팀은 개별 검토자를 정의해야 합니다.

* 승인 활동 내의 Adobe Campaign 검토자 역할은 단일 검토자(운영자) 또는 검토자 그룹(운영자 역할)일 수 있습니다.
* 검토자 및 검토자 그룹은 Adobe Campaign에서 관리자 역할에 의해 이전에 구성되어야 합니다. 이를 통해 캠페인 개발자는 캠페인 또는 전달의 승인자로 검토자를 선택할 수 있습니다.

## 캠페인에 대한 승인 구성  {#configuring-approvals-for-campaigns}

캠페인 워크플로우의 모든 게재에 대해 동일한 검토자 세트가 있는 경우 캠페인 승인 기능을 활용할 수 있습니다. 캠페인 수준에서 승인 및 검토자를 설정하면 워크플로우가 실행되면 승인 작업과 검토자가 워크플로우의 각 전달 활동으로 푸시됩니다.

>[!VIDEO](https://video.tv.adobe.com/v/25175?quality=12)

## 전달에 대한 승인 구성  {#configuring-approvals-for-deliveries}

전달 수준에서 승인을 설정할 수도 있습니다. 게재 승인 단계 및 검토자가 캠페인 승인 단계 및 검토자와 다를 경우, 게재 설정이 캠페인 설정을 덮어씁니다.

>[!VIDEO](https://video.tv.adobe.com/v/25176?quality=12)

## 승인 활동 구성  {#configuring-an-approval-activity}

전달 또는 캠페인 승인과 달리 승인 활동을 통해 워크플로우 내에서 승인 프로세스를 만들 수 있습니다. 이렇게 하면 배달을 실행하기 전에 타깃팅 선택 로직을 승인할 수 있습니다. 또한 필요한 경우 워크플로우 내에서 여러 수준에서 승인을 받을 수 있습니다.

>[!VIDEO](https://video.tv.adobe.com/v/25174?quality=12)

For more information, refer to the [Approval Documentation](https://docs.adobe.com/help/en/campaign-classic/using/automating-with-workflows/flow-control-activities/approval.html)
