# Content Notes · v1

## 沿用的既有內容

快照日期：2026-09-15。保留公開版所需的來源名稱；不附組織內部連結。

| 來源 | 用途 |
| --- | --- |
| BIOS PM 新人教學專案｜AI Tool Enhanced Project | 四大 Layers、專業導覽、協作方向與 L1–L4 |
| BIOS 0→1 新手學習路徑｜Learning Hub Curriculum | 11 步學習順序與看圖、理解、探索、練習的章節模式 |
| BIOS PM 0→1 Project Tracker | 核對 Module 完成狀態及 Internal Only 分類 |
| PC / Notebook 公版硬體架構與 BIOS 常用名詞 | 硬體正文與 platform.png |
| UEFI 開機流程與為什麼需要初始化 | 開機正文與 boot-flow.png |
| BIOS/UEFI Knowledge Base：12 大知識分類與名詞地圖 | 知識正文、117 個唯一術語與 knowledge-map.png |
| Storage 基礎：HDD / SSD / SATA / PCIe / NVMe / M.2 | Storage 正文與公開練習依據 |

## 圖解

三張圖片直接沿用既有圖檔，未以新圖冒充原圖。
舊站提到的「BIOS/UEFI 整體體制」獨立圖檔未在本次查得；知識地圖已有相關整體位置示意。
受限的 CRB/RVP 與 Project Board 工作流程圖未納入。
Storage 正文收錄文字與表格，該頁其他圖片未打包；保留可理解的文字路徑。

圖解旁的補充說明區分概念圖與平台實作。PCH/SoC、Display 路由與 Firmware 元件
配置依平台而異，不可當成所有硬體的固定拓樸。
開機阶段症狀僅作初步定位線索；Secure Boot 與 TPM 也不是同一種機制。

技術補充核對來源：

- [UEFI Boot Services：ExitBootServices](https://uefi.org/specs/UEFI/2.10_A/07_Services_Boot_Services.html)
- [UEFI Runtime Services](https://uefi.org/specs/UEFI/2.9_A/08_Services_Runtime_Services.html)
- [Microsoft：Secure Boot 與 TPM 的區別](https://learn.microsoft.com/en-us/windows/security/operating-system-security/system-security/protect-high-value-assets-by-controlling-the-health-of-windows-10-based-devices)

## 呈現與維護

公開版不載入任何外部 API，不含私有資料快照。新增教材時，先依實際內容分類確認可公開範圍。
本次略去 Mermaid 原始碼的直接顯示，改搭配既有圖解與網站流程元件；不依賴第三方 CDN。
正文與補充練習分開標示；Module 狀態與閱讀進度分開管理。
正式考核、Insyde 組織教材、真實案例及其評分規則尚未完成，因此未標記 Done。
