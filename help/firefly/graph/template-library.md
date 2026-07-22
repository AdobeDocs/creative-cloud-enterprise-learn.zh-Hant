---
title: 範本程式庫
description: 瀏覽現成的Firefly Graph範本，以讓您開啟並適應自己的專案
feature: Image Editing, Gen AI
role: User
level: Beginner
jira: KT-
hide: true
hidefromtoc: true
source-git-commit: aa0ae4747f081c69d8a01d3f9acdd7844cca6afe
workflow-type: tm+mt
source-wordcount: '996'
ht-degree: 2%

---

# &#x200B;5. 範本程式庫

Firefly Graph範本的快速參考索引，依每個範本產生或執行的內容組織。 每個範例都是起點 — 在生產中使用範本之前，交換您自己的品牌、產品和提示。

## 影像產生與樣式

| 圖表範本 | 說明 | [!BADGE 使用案例]{type=Informative tooltip="使用案例"} |
|---|---|---|
| [**快速入門 — 產生影像**](/help/firefly/graph/templates/get-started-gen-image.md) | 此範本是基本圖形：一個提示節點放入一個世代節點放入一個輸出。 使用它作為第一個與任何全新使用者一起開啟的範本。 | 零售、健康、教育 |
| [**產生一致的字元**](/help/firefly/graph/templates/character-gen.md) | 在此圖表範本中，您載入一個字元的參考影像，然後交換每個新快照的場景或姿勢提示。 當周圍場景變更時，字元參照會保持鎖定狀態。 | 旅遊、零售、教育 |
| [**樣式擷取**](/help/firefly/graph/templates/style-extraction.md) | 在此圖形範本中，您會傳入參考影像以擷取其顏色、光線和紋理處理。 然後，您可以將該處理套用至透過相同圖形執行的任何新影像。 | 旅遊、零售、飲料 |
| [**日落視覺**](/help/firefly/graph/templates/sunset-vibes.md) | 在此圖形範本中，您可以從文字提示建立3D排版影像。 範本會自動處理位置和色彩平衡。 | 旅遊、飲料、零售 |

## 細分和組合

| 圖表範本 | 說明 | [!BADGE 使用案例]{type=Informative tooltip="使用案例"} |
|---|---|---|
| [**快速入門 — 將影像分段**](/help/firefly/graph/templates/get-started-segment-image.md) | 在此圖表範本中，您會載入任何來源影像並執行分割節點，以將主題與其背景隔離。 與背景取代節點配對，以取得乾淨的挖剪圖案。 | 健康、零售、汽車 |
| [**複合與混合圖層**](/help/firefly/graph/templates/composite-blend-layers.md) | 在此圖形範本中，您可以將產品切除和背景場景棧疊為單獨的圖層輸入。 調整混合模式和光源節點，直到複合讀取為單次拍攝為止。 | 飲料、零售、旅遊 |
| [**選擇性色彩校正**](/help/firefly/graph/templates/selective-color-correction.md) | 在此圖表範本中，您可以遮罩需要修正的特定區域，並僅在該節點上設定目標顏色。 影像的其餘部分則未觸及圖形。 | 通訊與電信、零售、金融 |

## 視訊與動作

| 圖表範本 | 說明 | [!BADGE 使用案例]{type=Informative tooltip="使用案例"} |
|---|---|---|
| [**快速入門 — 視訊產生**](/help/firefly/graph/templates/get-started-video-gen.md) | 在此圖形範本中，您會加入已核准的靜態關鍵圖稿和簡短動作提示。 此範本會產生視訊剪下，該剪下是由相同的關鍵藝術作品所建置，而非新的拍攝。 | 金融、飲料、零售 |
| [**專案符號時間VFX**](/help/firefly/graph/templates/bullet-time-vfx.md) | 在此圖表範本中，您輸入主圖產品或主旨影像，以產生圍繞主圖產品或主圖影像的旋轉角度序列，然後自動拼接凍結影格掃描。 | 戶外、零售、汽車 |

## 分鏡指令碼

| 圖表範本 | 說明 | [!BADGE 使用案例]{type=Informative tooltip="使用案例"} |
|---|---|---|
| [**文字到分鏡指令碼**](/help/firefly/graph/templates/text-to-storyboard.md) | 在此圖表範本中，您會以內文中的元素取代文字輸入節點。 每一行會成為自己的分鏡指令碼影格，依序產生，並作為單一面板組配置以供檢閱。 | 金融、零售、科技 |
| [**分鏡指令碼產生器**](/help/firefly/graph/templates/storyboard-builder.md) | 在此圖表範本中，您可以依場景建立指令碼場景，為敘述的每一個節拍新增一個節點。 重新排序節點以測試不同的序列，然後再鎖定最終的面板順序。 | 通訊與電信、飲料、旅遊 |

## 3D與字元

| 圖表範本 | 說明 | [!BADGE 使用案例]{type=Informative tooltip="使用案例"} |
|---|---|---|
| [**即時著色器**](/help/firefly/graph/templates/real-time-shaders.md) | 在此圖表範本中，您會從影像開始，套用三種不同的自訂著色器，並即時預覽結果。 直接在節點上調整著色器引數，而非從頭開始重新演算。 | 科技，汽車，零售 |
| [**字元模型產生**](/help/firefly/graph/templates/character-model-generation.md) | 在此圖形範本中，您可以建立插圖的3D動畫樣式。 範本會產生一個基礎3D模型路徑，準備交給模型工具進行清除，而不是從空白場景開始。 | 戶外、科技、教育 |
| [**乙烯基玩具設計**](/help/firefly/graph/templates/vinyl-toy-design.md) | 在此圖表範本中，您輸入字元或吉祥物參考，然後以風格化的乙烯基玩具形式呈現。 授權或產品檢閱資料有轉換角度。 | 零售、飲料、娛樂 |
| [**草繪3D週轉**](/help/firefly/graph/templates/sketch-to-3d.md) | 在此圖形範本中，您可將草繪轉換為3D字元。 圖表會從中建立旋轉的3D迴轉，以便在任何實體原型之前進行內部設計稽核。 | 科技，汽車，娛樂 |

## 產品與品牌模型

| 圖表範本 | 說明 | [!BADGE 使用案例]{type=Informative tooltip="使用案例"} |
|---|---|---|
| [**品牌視覺效果**](/help/firefly/graph/templates/branding-visualization.md) | 在此圖表範本中瞭解如何在產品場景中視覺化標誌或品牌。 品牌方針或標誌與調色盤中的摘要，以及圖形在一次執行中同時輸出靜態關鍵線條和短時間移動路徑，因此兩種格式在視覺上都會保持一致。 | 科技、飲料、金融 |
| [**品牌產品模型**](/help/firefly/graph/templates/brand-product-mockup.md) | 在此圖表範本中瞭解如何在不同的場景中顯示您的產品。 您可以將產品彩現或像片拖放到模型節點中，然後圖形會將其置於完全品牌化的場景中，並自動配合該場景的光線和陰影。 | 零售、飲料、技術 |
| [**編輯拍照**](/help/firefly/graph/templates/editorial-photoshoot.md) | 在此圖形範本中，您載入模型參照並交換每個新外觀的服裝輸入。 姿勢和光源節點會持續鎖定在集內，以維持一致的編輯感覺。 | 零售、美容、戶外 |
| [**攝影工作室**](/help/firefly/graph/templates/photography-studio.md) | 在此圖形範本中，您可以將產品轉譯器放置在攝影棚背景上，並調整光線，直到結果看起來像是一個真實的攝影棚擷取。 | 飲料、科技、零售 |
| [**套用貼花至表面**](/help/firefly/graph/templates/decal-to-surfaces.md) | 在此圖表範本中，您載入基礎產品模型以及貼花或標誌資產作為單獨的輸入。 範本會將貼花包裝在曲面幾何上，使其正確遵循輪廓。 | 戶外、汽車、零售 |

## 批次與一致性作業

| 圖表範本 | 說明 | [!BADGE 使用案例]{type=Informative tooltip="使用案例"} |
|---|---|---|
| [**設計系統產生器**](/help/firefly/graph/templates/design-system-generator.md) | 在此圖表範本中，您會根據網站熒幕擷圖產生設計系統。 圖形會在單一批次執行中產生一組相符的圖示、圖樣和版面配置元件。 | 科技、金融、通訊與電信 |
| [**產生大頭照**](/help/firefly/graph/templates/headshots-generation.md) | 在此圖表範本中，您可以協調一整批公司大頭照。 載入來源像片（每人一個），圖形會在一次執行中標準化整個組合的光線、背景和裁切。 | 科技，金融，健康 |

返回[開始使用Firefly圖形](https://experienceleague.adobe.com/en/docs/creative-cloud-enterprise-learn/cce-learning-hub/fireflyoverview/firefly-graph/overview-firefly-graph)。