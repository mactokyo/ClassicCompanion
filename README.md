> **Moved / 已迁移 / 移転しました** → [xtymac/ClassicCompanion](https://github.com/xtymac/ClassicCompanion). Source, DMG downloads and new feedback are now in one place. This legacy repository and its original release remain available.

<img src="https://raw.githubusercontent.com/xtymac/ClassicCompanion/main/assets/marketing/poster-en.png" alt="Classic Companion — One press away. The Option Space shortcut and two native macOS chat windows." width="960">

# <img src="https://raw.githubusercontent.com/xtymac/ClassicCompanion/main/assets/icon/AppIcon-1024.png" alt="" width="48" height="48" align="absmiddle"> Classic Companion

The official ChatGPT website, a shortcut away in a native macOS window.

**[Download DMG →](https://github.com/xtymac/ClassicCompanion/releases/download/v0.1.0-beta.1/ClassicCompanion-0.1.0-beta.1-20261110.0137-arm64.dmg)** · [Release notes](https://github.com/xtymac/ClassicCompanion/releases) · [Feedback](https://github.com/xtymac/ClassicCompanion/issues)

<sub>Public beta · macOS 15+ · Apple silicon only · Independent app, not affiliated with OpenAI.</sub>

---

## 简体中文

<details>
<summary>展开使用说明、安装步骤与已知问题</summary>

<img src="https://raw.githubusercontent.com/xtymac/ClassicCompanion/main/assets/marketing/poster-zh-hans.png" alt="Classic Companion 宣传图：标题“一按，就在眼前。”，⌥ + Space 快捷键，两个显示 ChatGPT 对话的小窗。" width="960">

Classic Companion 用原生 macOS 窗口打开 ChatGPT 官方网页。默认按 `⌥Space` 唤出，`⌃⌘F` 切换小窗和完整窗口；两个快捷键都可以在 设置 → 快捷键 里改。如果别的应用也用同一个组合，按下时可能会触发那个应用，也可能让这里的快捷键不起作用，请换一个组合。

本仓库保留旧版本。源码、DMG 下载和新反馈已统一迁往页首的新仓库，源码采用 Apache-2.0；源码更新不代表已发布安装包同步更新。

**现状**：首个试用版 0.1.0-beta.1 已发布，可以从 [Releases](https://github.com/xtymac/ClassicCompanion/releases) 下载。这是试用版，不是正式稳定版。直接下载：[DMG](https://github.com/xtymac/ClassicCompanion/releases/download/v0.1.0-beta.1/ClassicCompanion-0.1.0-beta.1-20261110.0137-arm64.dmg)

**安装**

用 DMG 安装：
1. 从 Releases 下载 DMG，可以用同页的 `SHA256SUMS` 核对文件。
2. 双击 DMG 打开，把 `Classic Companion` 拖到“应用程序”文件夹。
3. 在“应用程序”里双击打开，然后登录 ChatGPT 账号。

<details>
<summary>备用安装方式：从 Releases 获取 ZIP</summary>

用 ZIP 安装：
1. 从 Releases 下载 ZIP，可以用同页的 `SHA256SUMS` 核对文件。
2. 浏览器没有自动解压的话，在“访达”里双击 ZIP 解压。
3. 把 `Classic Companion` 拖到“应用程序”文件夹，再在“应用程序”里双击打开，然后登录 ChatGPT 账号。

</details>

第一次打开时，macOS 可能会弹出安全确认，确认是 Classic Companion 后选择打开即可。如果 macOS 提示无法打开，请不要更改系统的安全设置，可以到 Issues 反馈。

**系统要求**：macOS 15.0 或更新版本；只支持 Apple 芯片（arm64），不支持 Intel Mac。

**已验证**：一台搭载 Apple M4 Max 的 MacBook Pro，macOS 27.2（用 DMG 安装、第一次打开、四种界面语言和主要功能）；一台搭载 Apple M4 Pro 的 MacBook Pro，macOS 27.0.1（用 DMG 安装、登录、设置、四种界面语言、退出重开后保留登录和设置）。

**未验证**：macOS 15、macOS 26；其他 Mac 和全新的用户环境；用 ZIP 安装；部分实体按键和输入法操作只做过工具驱动的测试。

**界面语言**：简体中文、繁體中文、English、日本語，默认跟随 macOS 的首选语言（都对不上时用英文），可以在 设置 → 通用 → 应用语言 里改。只影响应用界面，不改变 ChatGPT 网页的语言。

**已知问题**（每个版本的完整说明见 Release 附带的 `TrialNotes.zh-Hans.md`）：
- 图片预览关闭后，缩略图可能空白。
- 交互组件未验证，可能显示或操作异常。
- 朗读只能开始和停止；朗读中重新生成时，旧朗读可能继续播放。
- 长对话快速向上滚动时偶尔回弹。
- 单显示器下，在其他应用的全屏界面上唤醒窗口还没有测试。
- 在小窗里编辑已发送的消息时，编辑框可能在视野上方。
- 按 `⌘M` 后再次打开应用，窗口偶尔停在 Dock 图标处；退出再打开可以恢复。
- 在系统语言为英文的测试机上，各界面语言下编辑菜单的“撤销 / 重做”都显示为 Undo / Redo；界面是中文或日文时，“显示”菜单里没有“进入全屏幕”等项目。这是在测试机上观察到的现象，原因待查。
- 在首选语言为英文、日文、简体中文的测试机上手动选择繁體中文时，应用原生界面里的标点按简体中文或日文的字形显示（例如“，”“。”在左下而不是居中）。这是在测试机上观察到的现象，原因尚未确认。

**反馈**：请用 [Issues](https://github.com/xtymac/ClassicCompanion/issues)，附上“关于 Classic Companion”窗口里“复制版本信息”的内容。Issues 是公开的，不要贴对话内容、账号信息或截图里的私人内容。

<sub>非 OpenAI 官方应用，与 OpenAI 没有关联。ChatGPT 是 OpenAI 的商标。</sub>

</details>

## 繁體中文

<details>
<summary>展開使用說明、安裝步驟與已知問題</summary>

<img src="https://raw.githubusercontent.com/xtymac/ClassicCompanion/main/assets/marketing/poster-zh-hant.png" alt="Classic Companion 宣傳圖：標題「一按，就在眼前。」，⌥ + Space 快速鍵，兩個顯示 ChatGPT 對話的小視窗。" width="960">

Classic Companion 以原生 macOS 視窗開啟 ChatGPT 官方網頁。預設按 `⌥Space` 叫出，`⌃⌘F` 切換小視窗和完整視窗；兩個快速鍵都可以在 設定 → 快速鍵 中更改。如果其他 App 也使用同一個組合，按下時可能會觸發那個 App，也可能讓這裡的快速鍵無法使用，請換一個組合。

本儲存庫保留舊版本。原始碼、DMG 下載與新回饋已統一遷往頁首的新儲存庫，原始碼採用 Apache-2.0；原始碼更新不代表已發布安裝包同步更新。

**現況**：第一個試用版 0.1.0-beta.1 已發佈，可以從 [Releases](https://github.com/xtymac/ClassicCompanion/releases) 下載。這是試用版，不是正式穩定版。直接下載：[DMG](https://github.com/xtymac/ClassicCompanion/releases/download/v0.1.0-beta.1/ClassicCompanion-0.1.0-beta.1-20261110.0137-arm64.dmg)

**安裝**

用 DMG 安裝：
1. 從 Releases 下載 DMG，可以用同一頁的 `SHA256SUMS` 核對檔案。
2. 按兩下 DMG 打開，把 `Classic Companion` 拖到「應用程式」檔案夾。
3. 在「應用程式」中按兩下打開，然後登入 ChatGPT 帳號。

<details>
<summary>備用安裝方式：從 Releases 取得 ZIP</summary>

用 ZIP 安裝：
1. 從 Releases 下載 ZIP，可以用同一頁的 `SHA256SUMS` 核對檔案。
2. 如果瀏覽器沒有自動解壓縮，在「Finder」中按兩下 ZIP 解壓縮。
3. 把 `Classic Companion` 拖到「應用程式」檔案夾，再在「應用程式」中按兩下打開，然後登入 ChatGPT 帳號。

</details>

第一次打開時，macOS 可能會要求安全確認，確認是 Classic Companion 後選擇打開即可。如果 macOS 提示無法打開，請不要更改系統的安全設定，可以到 Issues 回饋。

**系統需求**：macOS 15.0 或以上版本；只支援 Apple 晶片（arm64），不支援搭載 Intel 處理器的 Mac。

**已驗證**：一台搭載 Apple M4 Max 的 MacBook Pro，macOS 27.2（用 DMG 安裝、第一次打開、四種介面語言和主要功能）；一台搭載 Apple M4 Pro 的 MacBook Pro，macOS 27.0.1（用 DMG 安裝、登入、設定、四種介面語言、結束後重新打開仍保留登入和設定）。

**尚未驗證**：macOS 15、macOS 26；其他 Mac 和全新的使用者環境；用 ZIP 安裝；部分實體按鍵和輸入法操作只做過工具驅動的測試。

**介面語言**：简体中文、繁體中文、English、日本語，預設跟隨 macOS 的偏好語言（都不符合時使用英文），可以在 設定 → 一般 → App 語言 中更改。只影響 App 介面，不會改變 ChatGPT 網頁的語言。

**已知問題**（每個版本的完整說明見 Release 附帶的 `TrialNotes.zh-Hant.md`）：
- 關閉圖片預覽後，縮圖可能空白。
- 互動元件未驗證，可能顯示或操作異常。
- 朗讀只能開始和停止；朗讀中重新產生回答時，舊的朗讀可能繼續播放。
- 長對話快速向上捲動時偶爾回彈。
- 單一顯示器時，在其他 App 的全螢幕畫面上叫出視窗尚未測試。
- 在小視窗中編輯已傳送的訊息時，編輯框可能在可見範圍上方。
- 按 `⌘M` 後再次打開 App，視窗偶爾停在 Dock 圖像處；結束後再打開可以恢復。
- 在系統語言為英文的測試機上，各介面語言下「編輯」選單的「還原／重做」都顯示為 Undo / Redo；介面為中文或日文時，「顯示方式」選單中沒有「進入全螢幕」等項目。這是在測試機上觀察到的行為，原因待查。
- 在偏好語言為英文、日文、簡體中文的測試機上手動選擇繁體中文時，App 原生介面中的標點會以簡體中文或日文的字形顯示（例如「，」「。」位於左下而非置中）。這是在測試機上觀察到的行為，原因尚未確認。

**回饋**：請使用 [Issues](https://github.com/xtymac/ClassicCompanion/issues)，附上「關於 Classic Companion」視窗中「拷貝版本資訊」的內容。Issues 是公開的，請勿貼上對話內容、帳號資訊或截圖中的私人內容。

<sub>非 OpenAI 官方 App，與 OpenAI 沒有關聯。ChatGPT 是 OpenAI 的商標。</sub>

</details>

## English

<details>
<summary>Read the guide, installation steps and known issues</summary>

Classic Companion opens the official ChatGPT website in a native macOS window. By default, press `⌥Space` to bring it up and `⌃⌘F` to switch between the Quick and Full window; you can change both under Settings → Shortcuts. If another app uses the same combination, pressing it may trigger that app or stop the shortcut from working here, so choose a different combination.

This legacy repository preserves old releases. Source (Apache-2.0), downloads and new feedback now live together in the repository linked above. Source changes may not yet be included in published installers.

**Status**: the first trial build, 0.1.0-beta.1, is out. You can download it from [Releases](https://github.com/xtymac/ClassicCompanion/releases). It’s a trial build, not a stable release. Direct download: [DMG](https://github.com/xtymac/ClassicCompanion/releases/download/v0.1.0-beta.1/ClassicCompanion-0.1.0-beta.1-20261110.0137-arm64.dmg)

**Install**

From the DMG:
1. Download the DMG from Releases. You can check it against `SHA256SUMS` on the same page.
2. Double-click the DMG to open it, and drag `Classic Companion` to the Applications folder.
3. Double-click it in Applications, then sign in to your ChatGPT account.

<details>
<summary>Alternative installation: ZIP from Releases</summary>

From the ZIP:
1. Download the ZIP from Releases. You can check it against `SHA256SUMS` on the same page.
2. If your browser didn’t unzip it, double-click the ZIP in Finder.
3. Drag `Classic Companion` to the Applications folder, double-click it there, then sign in to your ChatGPT account.

</details>

The first time you open it, macOS may ask you to confirm; check that it’s Classic Companion and choose to open it. If macOS says the app can’t be opened, don’t change your Mac’s security settings; please report it on Issues instead.

**Requirements**: macOS 15.0 or later; Apple silicon (arm64) only. Intel-based Macs aren’t supported.

**Verified on**: one MacBook Pro with Apple M4 Max running macOS 27.2 (installing from the DMG, first launch, all four app languages and the main features); one MacBook Pro with Apple M4 Pro running macOS 27.0.1 (installing from the DMG, signing in, settings, all four app languages, and keeping sign-in and settings after quitting and reopening).

**Not yet verified**: macOS 15 and macOS 26; other Macs and fresh user accounts; installing from the ZIP; some physical-key and input-method actions, which have been tested only with tool-driven input.

**App language**: Simplified Chinese, Traditional Chinese, English and Japanese. By default it follows your macOS preferred languages (English if none match); change it under Settings → General → App Language. It affects only the app’s interface, not the language of the ChatGPT web page.

**Known issues** (the full notes for each build are in `TrialNotes.en.md` attached to its release):
- Thumbnails may be blank after closing an image preview.
- Interactive components are unverified and may display or behave incorrectly.
- Read Aloud can only start and stop; regenerating during Read Aloud may keep the old reading playing.
- Fast upward scrolling in long chats occasionally bounces.
- Bringing the window up over another app’s full-screen view hasn’t been tested with a single display.
- When you edit a sent message in the Quick window, the edit box may be above the visible area.
- After `⌘M`, reopening the app occasionally leaves the window at the Dock icon; quitting and reopening fixes it.
- On the test Mac, whose system language is English, the Edit menu shows Undo / Redo in English whatever the app language, and with the app in Chinese or Japanese the View menu has no Enter Full Screen and similar items. This was observed on the test Mac; the cause hasn’t been confirmed.
- On the test Mac, whose preferred languages are English, Japanese and Simplified Chinese, choosing Traditional Chinese by hand shows punctuation in the app’s native windows in its Simplified Chinese or Japanese form (for example, “，” and “。” sit at the lower left instead of the center). This was observed on the test Mac; the cause hasn’t been confirmed.

**Feedback**: please use [Issues](https://github.com/xtymac/ClassicCompanion/issues) and include the text from Copy Version Info in the About Classic Companion window. Issues are public, so don’t paste chat content, account details or private content from screenshots.

<sub>Not an official OpenAI app and not affiliated with OpenAI. ChatGPT is a trademark of OpenAI.</sub>

</details>

## 日本語

<details>
<summary>使い方・インストール手順・既知の問題を表示</summary>

<img src="https://raw.githubusercontent.com/xtymac/ClassicCompanion/main/assets/marketing/poster-ja.png" alt="Classic Companion の紹介画像：「ひと押しで、すぐそこに。」、⌥ + Space のショートカット、ChatGPT を表示したクイックウインドウ 2 つ。" width="960">

Classic Companion は、ChatGPT の公式 Web サイトをネイティブの macOS ウインドウで開きます。初期設定では `⌥Space` で呼び出し、`⌃⌘F` でクイックウインドウとフルウインドウを切り替えます。どちらも 設定 → ショートカット で変更できます。ほかのアプリが同じ組み合わせを使っていると、押したときにそのアプリが反応したり、このアプリのショートカットが効かなくなったりすることがあるので、別の組み合わせに変えてください。

こちらは旧リリースの保存用です。ソース（Apache-2.0）、ダウンロード、新しいフィードバックはページ上部の新リポジトリにまとめました。ソースの更新が配布済みインストーラーに含まれているとは限りません。

**現在の状況**：最初のベータ版 0.1.0-beta.1 を公開しました。[Releases](https://github.com/xtymac/ClassicCompanion/releases) からダウンロードできます。ベータ版で、安定版ではありません。直接ダウンロード：[DMG](https://github.com/xtymac/ClassicCompanion/releases/download/v0.1.0-beta.1/ClassicCompanion-0.1.0-beta.1-20261110.0137-arm64.dmg)

**インストール**

DMG からインストールする場合：
1. Releases から DMG をダウンロードします。同じページの `SHA256SUMS` でファイルを確認できます。
2. DMG をダブルクリックして開き、`Classic Companion` を「アプリケーション」フォルダにドラッグします。
3. 「アプリケーション」でダブルクリックして開き、ChatGPT アカウントにログインします。

<details>
<summary>代替のインストール方法：Releases の ZIP</summary>

ZIP からインストールする場合：
1. Releases から ZIP をダウンロードします。同じページの `SHA256SUMS` でファイルを確認できます。
2. ブラウザが展開していない場合は、Finder で ZIP をダブルクリックして展開します。
3. `Classic Companion` を「アプリケーション」フォルダにドラッグし、そこでダブルクリックして開き、ChatGPT アカウントにログインします。

</details>

初めて開くとき、macOS が確認を求めることがあります。Classic Companion であることを確かめてから開いてください。開けないと表示された場合は、Mac のセキュリティ設定を変更せず、Issues でお知らせください。

**動作環境**：macOS 15.0 以降、Apple シリコン（arm64）のみ。Intel プロセッサ搭載の Mac には対応していません。

**確認済み**：Apple M4 Max 搭載の MacBook Pro 1 台、macOS 27.2（DMG からのインストール、初回起動、4 つの画面言語、主な機能）。Apple M4 Pro 搭載の MacBook Pro 1 台、macOS 27.0.1（DMG からのインストール、ログイン、設定、4 つの画面言語、終了して開き直したあともログインと設定が保たれること）。

**未確認**：macOS 15、macOS 26、ほかの Mac や新しいユーザ環境、ZIP からのインストール。一部の物理キーと入力メソッドの操作は、ツールによる入力でのみ確認しています。

**アプリの言語**：簡体字中国語、繁体字中国語、英語、日本語。最初は macOS の優先する言語に合わせ（どれにも当てはまらないときは英語）、設定 → 一般 → アプリの言語 で変更できます。アプリの画面にだけ適用され、ChatGPT の Web ページの言語は変わりません。

**既知の問題**（各ビルドの詳しい説明はリリースに添付の `TrialNotes.ja.md` にあります）：
- 画像のプレビューを閉じたあと、サムネールが空白になることがあります。
- インタラクティブなコンポーネントは未確認で、表示や操作がおかしくなることがあります。
- 読み上げは開始と停止のみです。読み上げ中に再生成すると、前の読み上げが続くことがあります。
- 長いチャットで素早く上にスクロールすると、ときどき跳ね返ります。
- ディスプレイ 1 台で、ほかのアプリのフルスクリーン表示の上に呼び出す操作はまだ試していません。
- クイックウインドウで送信済みのメッセージを編集すると、編集欄が表示範囲の上に隠れることがあります。
- `⌘M` のあとにアプリを開き直すと、ウインドウが Dock のアイコンの位置で止まることがあります。終了して開き直すと直ります。
- システムの言語が英語のテスト機では、アプリの言語にかかわらず編集メニューの「取り消す／やり直す」が Undo / Redo と表示され、アプリが中国語か日本語のときは「表示」メニューに「フルスクリーンにする」などの項目がありません。テスト機で観察された動作で、原因は未確認です。
- 優先する言語が英語・日本語・簡体字中国語のテスト機で繁体字中国語を手動で選ぶと、アプリのネイティブ画面の句読点が簡体字中国語または日本語の字形で表示されます（たとえば「，」「。」が中央ではなく左下に寄ります）。テスト機で観察された動作で、原因は未確認です。

**フィードバック**：[Issues](https://github.com/xtymac/ClassicCompanion/issues) にお寄せください。「Classic Companion について」ウインドウの「バージョン情報をコピー」の内容を添えてください。Issues は公開されるため、チャットの内容、アカウント情報、スクリーンショットに写った個人的な内容は貼り付けないでください。

<sub>OpenAI の公式アプリではなく、OpenAI とは提携していません。ChatGPT は OpenAI の商標です。</sub>

</details>

---

Made by [Mac Xiang](https://github.com/xtymac) · [MacTokyo](https://mactokyo.com/)
