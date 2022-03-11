---
title: 瞭解適用於企業的 Creative Cloud和Acrobat序號到期
description: 瞭解適用于適用於企業的 Creative Cloud和Acrobat的序號到期體驗
role: User
level: Beginner, Intermediate
exl-id: bc457be0-86dc-4e8a-b6b2-34bc76af2d21
source-git-commit: 6b819aef801e003e5a160d24ba69522cf6a7e715
workflow-type: tm+mt
source-wordcount: '848'
ht-degree: 3%

---

# 瞭解適用於企業的 Creative Cloud和Acrobat序號到期

從過去看，Adobe透過企業授權合約 （ETDA） 向客戶發佈應用程式的序號 （即Creative Suite、適用於企業的 Creative Cloud、Acrobat XI Acrobat DC）。 這些序號確實有過期日期。 一旦過期日期過期，產品將無法再運作，因此請務必在序號到期之前規劃您的移轉。 本頁面概述了確保您的使用者能夠繼續存取其Adobe應用程式和服務的必要步驟。

## 查看您的序號，以取得其到期日

### 尋找序號

您可以透過Adobe授權網站 ](https://licensing.adobe.com/) （LWS） 取得與您ETLA合約相關聯的 [ 序號授權。請依照下列指示顯示和下載：

1. [使用您的Adobe ID和密碼登入 Adobe 授權網站 ](https://licensing.adobe.com/) （LWS）。
1. 選擇 **「授權>擷取序號** 。
1. 輸入您的 **一般使用者 ID** 或 **「部署至 ID」** 。
1. （選擇性）選取 **產品名稱** 、 **產品版本** 或 **平臺** 以篩選結果。
1. 按一下「搜尋」。
1. 產品名稱和序號便會顯示。
1. （選擇性）選取「匯出至CSV」以下載序號清單。

![尋找序號](assets/retrieveserialnumbers.png)

### 檢查過期日期

[AdobeExpiryCheck ](https://helpx.adobe.com/enterprise/kb/volume-license-expiration-check.html) 是命令列公用程式，供 IT 管理員檢查Adobe電腦上的產品是使用已過期或即將過期的序號。此工具會顯示產品授權識別碼 （LEID）、加密序號和到期日等資訊。 本 [ 頁面 ](https://helpx.adobe.com/enterprise/kb/volume-license-expiration-check.html) 包含在 Mac 或 Windows 電腦上下載和使用該工具的指示。

## 瞭解序號到期前後的一般使用者體驗

Acrobat和適用於企業的 Creative Cloud應用程式將從到期前 60 天開始顯示訊息 （在應用程式中）。 序號過期後，產品就會停止運作，並提示使用者採取行動。

### 適用於企業的 Creative Cloud體驗

下列資訊概述了一般使用者的體驗。 以下有簡短的影片，接著檢視一般使用者體驗。

>[!VIDEO](https://video.tv.adobe.com/v/331746?hidetitle=true)

**到期前**

從序號到期的 60 天開始，所有適用於企業的 Creative Cloud應用程式都會向使用者顯示產品對話方塊。 此訊息會每週顯示一次，直到過期前 30 天才會出現，直到過期日為止，說明 *您的授權即將過期。 此Adobe產品使用的授權將于 2020 年 11 月 29 日到期。 請連絡您的管理員，以確保能繼續存取* 。

![CCE 到期前訊息](assets/cceexpiring.png)

**到期後**

序號過期後，使用者將無法再存取 適用於企業的 Creative Cloud 應用程式。 第一次啟動時，系統會在使用者到期時顯示對話方塊，說明 *您輸入的序號已過期。 此產品無法獲得授權。 請聯絡客戶支援* 。

![到期訊息後的 CCE](assets/cceafterexpire.png)

如果後續嘗試啟動應用程式，系統會提示 **使用者「立即** 登入」，然後出現選項建立自己的Adobe ID並進入試用模式。 但是，一般使用者建立的任何新Adobe ID將不會與您組織的授權相關聯，而且會對您的使用者造成額外的混淆。 為避免業務中斷和/或不必要的混淆，請在序號到期前，將您的使用者轉換為指名使用者授權。

![CCE 登入對話方塊 1](assets/ccesignin1.png)

![CCE 登入對話方塊 2](assets/ccesignin2.png)

### Acrobat體驗

下列資訊概述了一般使用者的體驗。 以下有簡短的影片，接著檢視一般使用者體驗。

>[!VIDEO](https://video.tv.adobe.com/v/331749?hidetitle=true)


**到期前**

從序號到期的 60 天開始，Acrobat向使用者顯示產品中的快顯訊息。 這會每週顯示一次，直到到期前 7 天為止。 接著，系統就會開始每天顯示，說明 *您的Adobe Acrobat授權將于 2020 年 30 月 11 日過期。 請聯絡您的管理員，以繼續使用Acrobat而不會中斷。*

![Acrobat訊息](assets/acrobatexpiring.png)

**到期後**

序號過期後，使用者將無法再存取 Acrobat。 第一次啟動時，系統會在使用者到期時顯示對話方塊，說明 *您輸入的序號已過期。 此產品無法獲得授權。 請聯絡客戶支援。*

![Acrobat過期訊息後](assets/acrobatafterexpire.png)

如果後續嘗試啟動Acrobat，系統會提示 **使用者「立即** 登入」，然後出現選項，建立自己的Adobe ID並進入試用模式。 但是，一般使用者建立的任何新Adobe ID將不會與您組織的授權相關聯，而且會對您的使用者造成額外的混淆。

![Acrobat登入對話方塊 1](assets/acrobatsignin1.png)

![Acrobat登入對話方塊 2](assets/acrobatsignin2.png)

## 如有需要協助，請聯絡我們

如果您對於使用 [ AdobeExpiryCheck ](https://helpx.adobe.com/enterprise/kb/volume-license-expiration-check.html) 工具有任何疑問，或需要從序號部署遷移到指名使用者的協助，您有以下幾項選項：
* 傳送電子郵件給 Adobe Enterprise Onboarding 團隊 – **entonb@adobe.com**
* 在 Admin Console 中開 [ 啟支援票證](https://adminconsole.adobe.com/support)
* 請聯絡您的Adobe客戶經理或客戶成功經理
