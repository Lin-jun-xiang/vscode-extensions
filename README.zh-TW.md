# vscode-extensions [Best]

<div>
    <img src="https://readme-typing-svg.demolab.com/?pause=1&size=50&color=f75c7e&center=True&width=1200&height=120&vCenter=True&lines=Click+the+⭐+Star+請.;Any+questions+can+be+asked+in+Issue." />
</div>


[中文版README.md](README.zh-TW.md)

<details>
<summary>Vscode Common Commands</summary>

* 使用vscode命令面板可以提高開發速度.

* 打開命令面板:`ctrl+shift+p`

* 常用命令:
    * `File: Open Folder`:打開文件夾作為工作空間.
    * `Preferences: Color Theme`:為編輯器選擇顏色主題.
    * `Preferences: File Icon Theme`:為文件選擇圖標主題.
    * `Developer: Reload Window`:重新加載 VSCode 窗口.

</details>

---

* 記錄分享vscode擴展，包括提升開發效率、必備、主題美化等.
* 本項目將為每個擴展提供詳細的使用說明，希望能幫助全世界的碼友們一起愉快地碼字:sunglasses:
* 本項目提供["**擴展分享區**"](./share/README.md)，任何人都可以在這裡提交感興趣的擴展.
* 如果你想**拉取請求**，只需更新 `README.md`

    ([`README.zh-TW.md`](https://github.com/Lin-jun-xiang/action-translate-markdown/tree/main) 會通過CI自動更新)

* 擴展概要:
    - [快速下載多個擴展（先閱讀這個）](#starquickly-download-multiple-extensions)
    - [透明編輯器](#snowflaketransparent-editor)
    - [主題](#purple_hearttheme)
    - [編輯器和環境美化](#yellow_heart-beautifying-editor-and-editing-environment)
    - [必備和強烈推薦](#green_heart-must-have-highly-recommended)
    - [大數據與AI工程師-Jupyter(Python)](#star2big-data-ai-engineer---jupyter-python)
    - [Git 和 Markdown 助手](#wavegitmarkdown-support)
    - [遠程 WSL 和開發容器](#computer-remote-wsl--dev-container)
    - [修復器](#wrenchfixer-fix-vscode-corrupt)
    - [社區共享和貢獻](./share/README.md)

---

## :star:Quickly download multiple extensions
後面會介紹很多vscode擴展.這裡有一個技巧，可以快速下載很多擴展，不用一個一個找.

如果以後想把舊電腦的擴展轉移到新電腦上，也可以用這個方法:kissing:

* 您可以下載此項目附帶的 `.ps1` 文件，並按照下面的第三步排除您不需要的擴展.
* 在`extensions.ps1`文件中，每個擴展名都有註釋.請在執行安裝命令前刪除不需要的.

> 方法:
>
> 1. 訪問當前電腦上vscode的所有擴展，並輸出為文本. 在終端（`powershell`）輸入如下命令:
> `code --list-extensions | ForEach-Object {"code --install-extension $_"} > extensions.ps1`
>
> 2. 命令執行後會在當前目錄下得到`extensions.ps1`文件（文件名在執行命令時定義）.
>
> 3. 在新電腦的終端（`powershell`）中輸入以下命令:
> `./extensions.ps1`
>
> 4. 下載完成
> <img src="https://user-images.githubusercontent.com/63782903/226086537-1dddd375-3206-44db-8208-17715d70c744.png" width="60%">

<details>
<summary>Missing Extensions</summary>

* [`extensions-compare`](./extensions_compare/)

* 比較兩個`.ps`文件，找出兩個擴展記錄的**差異**.

* 用法（選擇以下之一）:
    * `compare.py`
        運行 `Python` 腳本.

        <img src="img/2023-04-19-11-06-37.png">
    * `compare.sh`
        在 `./extensions_compare/compare.sh` 上運行 `git bash, wsl, or linux` 等.

        <img src="img/2023-04-19-11-07-16.png">
</details>

---

## :snowflake:Transparent editor
透明效果很贊.

可以當個懶人工具（邊看視頻邊碼字~）.

您可以在編碼和觀看時使用自己的桌面背景**Gura**.

### GlassIt-VSC

> 用法:
`ctrl+alt+z`:降低飽和度（透明）
`ctrl+alt+c`:增加飽和度（不透明）

<img src="img/2023-03-20-20-35-03.png" width="60%">

<a href="#top">Back to top</a>

---

## :purple_heart:Theme

使用vscode最大的原因就是要有`eye-catching`, `elegant`, `comfortable`, `pleasant editing interface`. 只有好看的編輯環境才能讓coder願意敲鍵盤~:sunglasses:

接下來，筆者將他最喜歡的主題一一分享給大家（以下示例均基於Python，不同語言可能略有差異）

哦！稍等一下，這裡有一個快速切換主題的方法.畢竟你可能每天都想換主題~~

> 快速切換主題
>
> "ctrl+shift+p": 打開vscode命令輸入框
>
> "Preferences:Color Theme": 進入並選擇你想要的主題

### Arc Dark for Visual Studio Code
* 主題有點類似於Visual Studio Code的深色主題，但整體色調更柔和，類似馬卡龍的顏色.

<img src="img/2023-03-25-16-10-51.png" width="60%">

### ButterTheme
* 顧名思義，這是一款不傷眼的*奶油黃色*主題
* 非常難得的一個主題（說白了，用的人不多），但是作者很喜歡
* 如果找不到這個主題，<a href="https://marketplace.visualstudio.com/items?itemName=Levampire.Buttur" target="_blank">鏈接</a >

<img src="img/2023-03-17-14-36-15.png" width="60%">

### Coder200
* 這次光看名字就完全不知道了...
* 非常難得的主題，滿滿的*橙色*，好性感~:flushed:

<img src="img/2023-03-17-14-44-30.png" width="60%">


### doom-emacs-theme
* 簡約風格

<image src="https://user-images.githubusercontent.com/63782903/232356902-fc57dbc3-f650-4c41-b5a6-f33497954cc7.png" width="60%" />

### Dracula Official
* 非常有名，吸血鬼顏色為*粉色*和*紫色*

<img src="img/2023-03-17-14-51-36.png" width="60%">

### LaserWave
* 具有日落感覺的*紫粉色*主題

<img src="img/2023-03-17-20-17-56.png" width="60%">

### Moegi Theme
* 溫柔又養眼的主題

<img src="img/2023-03-17-20-20-13.png" width="60%">

### Material Dark
* 經典題材之一，不容忽視

<img src="img/2023-03-17-20-37-24.png" width="60%">

### One Dark Pro
* 經典題材之一，不容忽視

<img src="img/2023-03-17-20-36-31.png" width="60%">

### Panda Theme
* 頂級主題 *湖綠* :panda_face:
* 這個主題真不錯！

<img src="img/2023-03-17-20-21-23.png" width="60%">

### Simple Dark
* 背景很暗，文字顏色不會太刺眼

<img src="img/2023-03-17-20-23-37.png" width="60%">

### Skyline
* 藍色愛好者必須使用它:blue_heart:

<img src="img/2023-03-17-20-25-15.png" width="60%">

### SynthWave '84
* 超高科技、炫目的熒光主題:sunglasses:
* 選擇主題後，記得開啟熒光效果（也可以和其他主題色搭配:fu:）

> 啟用熒光模式:
>
> 1. "ctrl+shift+p": 打開VS Code命令輸入框
>
> 2. "Synthwave '84: Enable/Disable Neon Dreams": 打開/關閉（見圖）
>
> 3. "Restart": 重啟 VS Code

<img src="img/2023-03-17-20-28-44.png" width="60%">

<img src="img/2023-03-17-20-27-06.png" width="60%">

### Tearz
* 有點類似於之前推出的萌木主題
* 不過這個*紫色*真的很吸引作者~

<img src="img/2023-03-17-20-33-32.png" width="60%">

### Xcode Theme
* 經典題材之一，不容忽視

<img src="img/2023-03-17-20-35-39.png" width="60%">

<a href="#top">Back to top</a>

---
## :yellow_heart: Beautifying editor and editing environment
裝修完我們的編輯器，接下來要介紹的插件不僅可以增加美感，還可以提高工作效率~

### Color Highlight
* 如果你是**前端**工程師或**數據分析師**，經常需要做**視覺**工作，一定要下載這個！
* 編輯的時候，只要出現一個**16進制**的顏色表達式，就可以清楚的看到顏色（不用跑代碼看顏色好看不好看）.

<img src="img/2023-03-17-20-48-11.png" width="60%">

### Material Theme Icons
* 不同的文件擴展名有不同的圖標
* 不僅好看而且可以更快地找到文件.

<img src="img/2023-03-17-20-51-07.png" width="60%">

### vscode-icons
* 與 Material 主題圖標略有不同
* 作者比較喜歡用這個~

<img src="img/2023-03-17-20-53-26.png" width="60%">

<a href="#top">Back to top</a>

---
## :green_heart: Must-have, highly recommended
下面要介紹的插件真的好用！

其中絕大多數都可以提高開發效率，千萬不要錯過:heart_eyes:

### Code Runner
* 相信用過VSCode的朋友對這個插件應該不會陌生吧！？
* 允許VSCode一鍵執行程序.
* 支持多種語言，如C、C++、Java、JavaScript、PHP、Python、Perl...etc.

<img src="img/2023-03-17-20-59-33.png" width="60%">

### Comment Divider
* 用快捷鍵生成好看的**評論樣式**.
* 如下圖，可以看到兩種樣式:`Shift+Alt+x`和`Alt+x`.

<img src="img/2023-03-17-21-03-04.png" width="60%">

### autoDocstring - Python Docstring Generator
* 該插件是為Python開發者引入的.
* 使用快捷鍵快速生成 **Docstring** 風格的註釋.
* 描述函數的用途、參數、返回值等信息.
* 支持不同的**Docstring**風格，如google、sphinx、numpy等.

> 使用方法:在要生成評論的地方按下面的鍵
Windows:`ctrl+shift+2`
蘋果機:`cmd+shift+2`

<img src="img/2023-03-17-21-07-10.png" width="60%">

### Draw.io Integration
* 流程圖繪製工具
* 設計項目時，可以使用本插件規劃可行性.
* 可以作為筆記工具使用.
* 支持很多常用的模式，比如穀歌云平台代表功能符號（如圖）.

<img src="img/2023-03-17-21-14-00.png" width="60%">

### Path Intellisense
* 編碼時有這個插件真的很棒 :kissing_heart:
* 適合經常讀寫文件的碼農.
* 寫路徑時，會自動列出你要查找的路徑下的文件.

<img src="img/2023-03-17-21-17-09.png" width="60%">

<a href="#top">Back to top</a>

---

## :star2:Big data, AI engineer - Jupyter (Python)
這裡介紹的插件真的很給力！

筆者知道很多使用Python的人都不習慣使用vscode，原因有很多:
* 互動模式
* 查看變量數據類型和變量值（就像在Spyder、Pycharm中一樣）
* 逐行執行代碼，執行部分代碼（真的很實用，比Debug還厲害~:heart_eyes:)

該插件提供以下功能:
* :pushpin:**交互模式**
* :pushpin:**查看變量數據類型和變量值**（就像在 Spyder、Pycharm 中一樣）
* :pushpin:**逐行執行代碼**和**執行部分代碼**（真的很實用，比Debug還厲害~:heart_eyes:)

> 如果你能看懂中文，建議花5分鐘快速學習如何使用Jupyter插件（查看<a href="https://www.bilibili.com/video/BV1Bg411J78F/" target= "_blank">鏈接</a>)

> 用法:
>
> :bulb:下載以下插件（有些可能用不到，忘記了~）
>
> `Jupyter`、`Jupyter keymap`、`Jupyter slide show`、`Jupyter cell tag`、`Jupyter notebook renderes`、`vs code jupyter notebook previewer`
>
><img src="img/2023-03-17-21-50-07.png" width="40%">

> :bulb:**在交互模式下執行代碼**
>
> 1. 在腳本中右擊.
> 2. 選擇 `Run Current File in Interactive Window`
（建議設置一個VS Code快捷鍵，我設置為`F10`）.
> 3. 執行後會出現`Interactive`窗口.
>
><img src="img/2023-03-17-21-54-03.png" width="40%">
><img src="img/2023-03-17-21-57-03.png" width="40%">

> :bulb:**查看變量數據類型和變量值**（需要處於交互模式）
>
> 在交互窗口中點擊 *Variables*.
>
><img src="img/2023-03-20-13-17.PNG" width="60%">

> :bulb:**逐行或部分執行**
>
> 1. 選擇要執行的代碼（可以是一行或多行）.
> 2. 右擊選中的代碼.
> 3. 選擇 *在交互式窗口中運行選擇/行*.
>
><img src="img/2023-03-17-22-04-33.png" width="60%">

<a href="#top">Back to top</a>

---

## :wave:Git、Markdown Support
下面介紹的插件對於從事Github或Gitlab項目的開發者來說是必不可少的.

### GitLens
* 下載後，腳本代碼會顯示**哪些**部分被**修改**，**誰**做了修改，**何時**修改了.
* 注意屏幕右側的代碼.`170`行有一條綠線表示有新增代碼的記錄（紅色表示刪除代碼）.
* 請記住使用 `git` 跟踪項目以使該插件工作.

<img src="img/2023-03-17-22-08-15.png" width="60%">

### Markdown Preview Enhanced
* 寫入`.md`文件時，可以預覽結果.
* 按 `ctrl+k`，然後按 `v` 打開預覽窗口.
* 下圖中間為`.md`文件，右側為預覽窗口.


<img src="img/2023-03-17-22-15-20.png" width="60%">

<a href="#top">Back to top</a>

---

## :computer: Remote WSL & Dev Container

### Remote WSL
* vscode 將在 `Windows Subsystem Linux` 環境中打開 .
* 您可以在 vscode 編輯器中編輯 `WSL` 環境中的文件，而無需使用 `vim` 或 `nano`.

> 用法:
> 1. `ctrl+shift+p`:打開命令面板.
> 2. `WSL: New WSL Window`: 在vscode.內打開`WSL`環境

<img src="img/2023-03-20-11-47-42.png" width="60%">

### Dev-Container
* 借助`Docker`，vscode內部的整個開發環境都可以在一個容器中運行，包括編輯、終端、調試、執行.

* `Node.js`, `Python`, `Java`, etc. 等各種開發任務，只需要安裝`Docker`和vscode，就可以在只安裝%_inlinecode_%和vscode的環境中，以最舒適的方式進行，無需安裝相應的runtime和編譯軟件.

<img src="img/2023-03-20-11-48-43.png" width="60%">

<a href="#top">Back to top</a>

---

## :wrench:Fixer (Fix Vscode Corrupt)
有時，在卸載插件時，VS Code 窗口的右下角會出現如下錯誤信息:

<img src="https://user-images.githubusercontent.com/63782903/231321298-916da9d3-0e90-4bd5-bfc6-859371545ec7.png" width="60%" />

您可以使用以下方法解決此問題:

> 用法:
> 1. 下載修復 VSCode 校驗和插件.
> 2. `ctrl+shift+p`: 打開命令調色板.
> 3. `Fix ChecksumS: Apply`: 執行修復.
> 4. `ctrl+shift+p`: 打開命令調色板.
> 5. `Developer: Reload Window`: 重啟 VS Code.

<img src="img/2023-03-17-21-36-48.png" width="60%">

<a href="#top">Back to top</a>
