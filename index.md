---
layout: default
title: HOME
---

# 工程設計學習成果

請點選下方區塊開始學習。

<style>

/* 隱藏 Architect 主題的藍色頁首 */
header {
    display: none !important;
}    

/* 隱藏 Architect/Hacker 主題右側的按鈕與側邊資訊 */
aside#sidebar {
    display: none !important;
}

/* 針對某些版本的主題，按鈕可能在 header 或特定的 section 內 */
.button, .view {
    display: none !important;
}

/* 讓主內容區域自動填滿，不再留出右側空間 */
#main_content {
    width: 100% !important;
    max-width: 100% !important;
    margin-right: 0 !important;
}
/* 隱藏頁底維護者與 GitHub Pages 產生資訊 */
footer, .site-footer {
    display: none !important;
}

/* 調整主內容區域的上方間距，確保內容不會頂到最上方 */
.main-content {
    padding-top: 50px;
}
    
    .card-container {
        display: flex;
        flex-wrap: wrap;       /* 允許內容換行 */
        gap: 20px;
        margin-top: 30px;
    }
    .card {
        /* 計算寬度：(100% - 間隔) / 2 */
        flex: 0 0 calc(50% - 10px); 
        box-sizing: border-box; /* 確保 padding 不會撐大卡片 */
        padding: 20px;
        border: 1px solid #e0e0e0;
        border-radius: 12px;
        background-color: #ffffff;
        text-align: center;
        transition: transform 0.2s, box-shadow 0.2s;
        text-decoration: none !important;
        color: #333 !important;
    }
    .card:hover {
        transform: translateY(-5px);
        box-shadow: 0 10px 20px rgba(0,0,0,0.1);
        background-color: #f8fbff;
    }
    .card h2 {
        margin-top: 0;
        color: #007bff;
    }
    .card p {
        font-size: 0.9em;
        color: #666;
    }
    .btn-start {
        display: inline-block;
        margin-top: 15px;
        padding: 8px 20px;
        background-color: #007bff;
        color: white !important;
        border-radius: 5px;
        font-weight: bold;
    }

    /* 針對手機版做優化：螢幕小時改回一列一個 */
    @media (max-width: 600px) {
        .card {
            flex: 0 0 100%;
        }
    }

</style>

<div class="card-container">
    <a href="./matlab/chapter00" class="card">
        <h2> 期中報告</h2>
        <p>MATLAB程式設計</p>
        <span class="btn-start">預覽</span>
    </a>
    <a href="./CNN/chapter01" class="card">
        <h2> 期末報告</h2>
        <p>深度網路設計器</p>
        <span class="btn-start">預覽</span>
    </a>
</div>

---

### 📢 最新更新
- **2026-1-8**: 新增 期末報告。
- **2026-1-8**: 修正 MATLAB 側邊欄導覽連結。
