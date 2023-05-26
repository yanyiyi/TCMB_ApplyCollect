# 追逐記憶的機器人
這機器人主要以這三個部分所組成以提供，以讓各處有關記憶庫的資料，可以被追到並且進入 Line 機器人通知及進入 Google Sheet 供彙整。

## 將 Notion 更新資料到 RSS
- 使用 Zapier 申請免費帳號
- 使用 Zap 腳本：https://zapier.com/shared/093ba6a07d1b98ae77950667d27403be283b7c68

## 整理語彙整 RSS 及臉書訂閱服務
這邊彙整了曾經引用過記憶庫的相關新聞、臉書、部落格等來源的 RSS 。

- 使用 Inoreader 服務 https://www.inoreader.com/
- 這個需要購買每月 8.99 美金的 ENTERPRISE 客製化方案。（對網頁的追蹤功能、Facebook 追蹤公開頁通能、自定義 RSS 功能）
- 其 OMPL 檔案為 XML 格式，最新更新時間為：2023-03-02-20-00-51-UTC ，詳：Inoreader-OPML.xml 檔案。


## 串接到 Line 與 Google Spreadsheet 
- 這個需要每月購買 10.8 美金的 Make.com 的服務 
- 其服務檔案格視為 json ，最新更新時間為：2023-02-24 ，詳：
blueprint.json 檔案


## 注意
- 各種前述的使用皆須自行串接到指定的 Google 文件、Notion 等等的，該文件內部架構請再自行設定之。