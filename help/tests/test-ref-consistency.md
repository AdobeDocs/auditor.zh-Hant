---
description: 此參考文件主要探討 Adobe Experience Platform Auditor 為維持標記一致所執行的各項測試，為使用者提供詳細資訊。
seo-description: This reference provides more information about the tests Adobe Experience Platform Auditor performs for tag consistency.
seo-title: Tag consistency
title: 標記一致性
uuid: 16271dd6-3587-4f33-92f8-54ec4a3d6469
exl-id: 681cf2f8-e022-4fb0-a06a-b4986710f501
source-git-commit: 286a857b2ff08345499edca2e0eb6b35ecf02332
workflow-type: tm+mt
source-wordcount: '105'
ht-degree: 100%

---

# 標記一致性

此參考文件主要探討 Adobe Experience Platform Auditor 為維持標記一致所執行的各項測試，為使用者提供詳細資訊。

Platform Auditor 的一致性測試會在所有掃描的頁面上尋找不一致之處。這些值或設定在網站的所有頁面上均應相同，以確保資料收集的正確性。

<table id="table_4F9ED873BAF741D19BFB0F297B3A1FDB"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 測試 </th> 
   <th colname="col2" class="entry"> 標準 </th> 
   <th colname="col3" class="entry"> 建議 </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> 
    <!--
      1.0.1 
    --> <p><b>Analytics - 一致的程式碼版本</b> </p> <p>權重：5 </p> <p><a href="https://docs.adobe.com/content/help/zh-Hant/analytics/implementation/home.html" format="html" scope="external"> 其他資訊</a> </p> </td> 
   <td colname="col2"> <p> 找到多個 Analytics 程式碼版本。 </p> </td> 
   <td colname="col3"> <p>將所有 Analytics 執行個體取代為目前版本。 </p> </td> 
  </tr> 
 </tbody> 
</table>
