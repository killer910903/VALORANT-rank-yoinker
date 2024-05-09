<p align="center">
    <a href="https://github.com/isaacKenyon/valorant-rank-yoinker/">
        <img src="assets/Logo.png" alt="Logo" width="160" height="160">
    </a>
<h5 align="center"> VALORANT rank yoinker 繁體中文版 BY.Pika Development</h5>

> [!IMPORTANT]
> 請務必先開啟您的特戰英豪在啟動主程式.

[![Discord][discord-shield]][discord-url]
[![Downloads][downloads-shield]][downloads-url]
    
 
  <ol>
    <li><a href="#關於本專案">關於本專案</a></li>
    <li><a href="#使用方法">使用方法</a></li>
    <li><a href="#貢獻">專案貢獻</a></li>
    <li><a href="#聯繫我們">聯繫我們</a></li>
    <li><a href="#致謝名單">致謝名單</a></li>
    <li><a href="#免責聲明">免責聲明</a></li>
  </ol>

    
## 關於本專案

 ![Screenshot](assets/Example.png)
 ![Skin Showcase Image](assets/SkinShowcase.png)

|玩家組隊|使用造型|當前牌位|牌位評分|最高牌位|玩家等級|
|:---:|:---:|:---:|:---:|:---:|:---:|
|![Parties](assets/Party.png)|![Skin](assets/Skin.png)|![Rank](assets/Rank.png)|![Rating](assets/Rating.png)|![Peak](assets/PeakRank.png)|![Level](assets/Level.png)|
    

## 使用方法
 **VALORANT 必須開啟!**

### 你必須照著下方步驟:

1) 下載 [Microsoft Visual C++ Libraries](https://github.com/abbodi1406/vcredist/releases)
2) 下載 [最新版本](https://github.com/killer910903/VALORANT-rank-yoinker/releases/tag/2.60).
3) 解壓縮 **所有** 檔案.
4) 啟動 vRY.exe.

### 從原代碼運行(不推薦):

1) 下載 [Python 3.10](https://www.python.org/downloads/release/python-3100/)。確保它已添加到PATH。(這是安裝時的選項.)
   1) 3.10 之後的任何 Python 版本都應該可以運作。
2) 下載 [原始碼]([https://github.com/isaacKenyon/VALORANT-rank-yoinker/archive/refs/heads/main.zip](https://github.com/killer910903/VALORANT-rank-yoinker/archive/refs/heads/main.zip)).
3) 在該源資料夾中開啟終端.並運行下列指令
4) `pip install -r requirements.txt`
5) `main.py`

### 從原始碼編譯:

1) `pip install cx_Freeze`
2) `python setup.py build`
3)  打開新的Build資料夾並運行vRY.exe

> `-` 您可以透過在`config.json`中編輯槍來更改所需的武器，或刪除vRY重新提示您的文件.

> `-` 查看所有造型: <https://vry.netlify.app/matchLoadouts>.

<!-- 待完成 -->

### 讓 Github 編譯:

對「main」分支的最新提交將由 [Github Actions](https://github.com/isaacKenyon/VALORANT-rank-yoinker/actions) 進行編譯。
成功編譯應該會產生一個編譯好的文件，您可以下載並試用。
查看 [Actions tab](https://github.com/isaacKenyon/VALORANT-rank-yoinker/actions)，點選 `Build` 工作流程， 
選擇特定的工作流程運行，它應該有一個可供下載的工件。 

如果您想對應用程式進行一些小更改，您可以：
1) [Fork](https://github.com/isaacKenyon/VALORANT-rank-yoinker/fork) 這個專案。
2) 更改分叉儲存庫中的程式碼.
3) 讓 Github Actions 工作流程為您建置 vRY.exe。
4) 下載並測試他。
5) 如果您希望您的變更包含在未來版本中，請提交拉取請求。

## 官方聲明不能使用第三方程式?

 在 [這則推文](https://twitter.com/PlayVALORANT/status/1539728676815642624), 詳細介紹了 Riot 的 API 政策，並說明了不被允許應用程式暴露遊戲客戶端隱藏的資料。從版本 1.262 開始，vRY 就一直遵守著這項政策。
## 專案貢獻

 - 感謝[原作者zayKenyon](https://github.com/zayKenyon)開發這項[專案](https://github.com/zayKenyon/VALORANT-rank-yoinker)。
 - 感謝[Pika Development](https://discord.gg/rtsWs2UWX8)翻譯這項專案。
 
## 聯繫我們 

 加入官方Discord群組:         
 
[![Discord Banner 2][discord-banner]][discord-url]

## 致謝名單

 - [Valorant-API.com](https://valorant-api.com/)
 - [Hamper](https://hamper.dev/)
 - [D3CRYPT](https://d3crypt360.pages.dev/)
 - [Pika Development](https://discord.gg/rtsWs2UWX8)
 
## 免責聲明

 本專案與 Riot Games 沒有關係或認可。Riot Games 及所有相關財產均為 Riot Games, Inc. 的商標或註冊商標。
    
 雖然本專案已盡力遵守 Riot 的 API 規則；但您使用本軟體的風險必須由您自行承擔。

<!-- 待完成 -->
[discord-shield]: https://img.shields.io/discord/872101595037446144?color=7289da&label=Support&logo=discord&logoColor=7289da&style=for-the-badge
[discord-url]: https://discord.gg/HeTKed64Ka
[discord-banner]: https://discordapp.com/api/guilds/872101595037446144/widget.png?style=banner1

[downloads-shield]: https://img.shields.io/github/downloads/zayKenyon/VALORANT-rank-yoinker/total?style=for-the-badge&logo=github
[downloads-url]: https://github.com/killer910903/VALORANT-rank-yoinker/releases/tag/2.60
