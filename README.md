# Classic Companion

> Not an official OpenAI app and not affiliated with OpenAI. ChatGPT is a trademark of OpenAI.
> 非 OpenAI 官方应用，与 OpenAI 没有关联。ChatGPT 是 OpenAI 的商标。
> 非 OpenAI 官方 App，與 OpenAI 沒有關聯。ChatGPT 是 OpenAI 的商標。
> OpenAI の公式アプリではなく、OpenAI とは提携していません。ChatGPT は OpenAI の商標です。

[简体中文](#简体中文) · [繁體中文](#繁體中文) · [English](#english) · [日本語](#日本語)

## 简体中文

Classic Companion 用原生 macOS 窗口打开 ChatGPT 官方网页。默认按 `⌥Space` 唤出，`⌃⌘F` 切换小窗和完整窗口；两个快捷键都可以在 设置 → 快捷键 里改。如果 `⌥Space` 已经被别的应用占用，请换一个组合。

本仓库只用来发布试用版和收集反馈，不含源码；应用没有以开源许可证发布。

**现状**：首个试用版 0.1.0-beta.1 正在准备，还不能下载。公开后可以从 [Releases](https://github.com/mactokyo/ClassicCompanion/releases) 下载。

**安装**（试用版公开后）
1. 从 Releases 下载 DMG（或 ZIP），可以用同页的 `SHA256SUMS` 核对文件。
2. 打开 DMG，把 `Classic Companion` 拖到“应用程序”，然后在“应用程序”里双击打开。
3. 第一次打开时，macOS 会提示这是从互联网下载的App，问“确定要打开它吗？”，并说明“Apple对其进行了检查，未检测到任何恶意软件。”点“打开”，然后登录 ChatGPT 账号。提示的措辞随 macOS 版本可能略有不同。

**系统要求**：macOS 15 或更新版本，只支持 Apple Silicon（arm64），以实际构建设置为准。

**已验证环境**：一台搭载 Apple M4 Max 的 MacBook Pro，macOS 27.2。macOS 15、26 和其他 Mac 还没有实测。

**界面语言**：简体中文、繁體中文、English、日本語，默认跟随 macOS 的首选语言（都对不上时用英文），可以在 设置 → 语言 → 应用语言 里改。只影响应用界面，不改变 ChatGPT 网页的语言。

**已知问题**（每个版本的完整说明随 Release 附带的 `TrialNotes.zh-Hans.md`）：
- 图片预览关闭后，缩略图可能空白。
- 交互组件未验证，可能显示或操作异常。
- 朗读只能开始和停止；朗读中重新生成时，旧朗读可能继续播放。
- 长对话快速向上滚动时偶尔回弹。
- 单显示器下，在其他应用的全屏界面上唤醒窗口还没有测试。
- 在小窗里编辑已发送的消息时，编辑框可能在视野上方。
- 按 `⌘M` 后再次打开应用，窗口偶尔停在 Dock 图标处；退出再打开可以恢复。
- 在系统语言为英文的测试机上，各界面语言下编辑菜单的“撤销 / 重做”都显示为 Undo / Redo；界面是中文或日文时，“显示”菜单里没有“进入全屏幕”等项目。这是在测试机上观察到的现象，原因待查。
- 在首选语言为英文、日文、简体中文的测试机上手动选择繁體中文时，应用原生界面里的标点按简体中文或日文的字形显示（例如“，”“。”在左下而不是居中）。

**反馈**：请用 [Issues](https://github.com/mactokyo/ClassicCompanion/issues)，附上“关于 Classic Companion”窗口里“复制版本信息”的内容。Issues 是公开的，不要贴对话内容、账号信息或截图里的私人内容。

## 繁體中文

Classic Companion 以原生 macOS 視窗開啟 ChatGPT 官方網頁。預設按 `⌥Space` 叫出，`⌃⌘F` 切換小視窗和完整視窗；兩個快速鍵都可以在 設定 → 快速鍵 中更改。如果 `⌥Space` 已被其他 App 使用，請換一個組合。

本儲存庫只用來發佈試用版和收集回饋，不含原始碼；App 沒有以開放原始碼授權發佈。

**現況**：第一個試用版 0.1.0-beta.1 正在準備，目前還不能下載。公開後可以從 [Releases](https://github.com/mactokyo/ClassicCompanion/releases) 下載。

**安裝**（試用版公開後）
1. 從 Releases 下載 DMG（或 ZIP），可以用同一頁的 `SHA256SUMS` 核對檔案。
2. 打開 DMG，把 `Classic Companion` 拖到「應用程式」，然後在「應用程式」中按兩下打開。
3. 第一次打開時，macOS 會提示這是一個從網際網路下載的App，詢問「確定要打開嗎？」，並說明「Apple已進行檢查但並未偵測到惡意軟體。」按一下「打開」，然後登入 ChatGPT 帳號。提示的措辭可能因 macOS 版本而略有不同。

**系統需求**：macOS 15 或以上版本，只支援 Apple 晶片（arm64），以實際建置設定為準。

**已驗證環境**：一台搭載 Apple M4 Max 的 MacBook Pro，macOS 27.2。macOS 15、26 和其他 Mac 尚未實測。

**介面語言**：简体中文、繁體中文、English、日本語，預設跟隨 macOS 的偏好語言（都不符合時使用英文），可以在 設定 → 語言 → App 語言 中更改。只影響 App 介面，不會改變 ChatGPT 網頁的語言。

**已知問題**（每個版本的完整說明見 Release 附帶的 `TrialNotes.zh-Hant.md`）：
- 關閉圖片預覽後，縮圖可能空白。
- 互動元件未驗證，可能顯示或操作異常。
- 朗讀只能開始和停止；朗讀中重新產生回答時，舊的朗讀可能繼續播放。
- 長對話快速向上捲動時偶爾回彈。
- 單一顯示器時，在其他 App 的全螢幕畫面上叫出視窗尚未測試。
- 在小視窗中編輯已傳送的訊息時，編輯框可能在可見範圍上方。
- 按 `⌘M` 後再次打開 App，視窗偶爾停在 Dock 圖像處；結束後再打開可以恢復。
- 在系統語言為英文的測試機上，各介面語言下「編輯」選單的「還原／重做」都顯示為 Undo / Redo；介面為中文或日文時，「顯示方式」選單中沒有「進入全螢幕」等項目。這是在測試機上觀察到的行為，原因待查。
- 在偏好語言為英文、日文、簡體中文的測試機上手動選擇繁體中文時，App 原生介面中的標點會以簡體中文或日文的字形顯示（例如「，」「。」位於左下而非置中）。

**回饋**：請使用 [Issues](https://github.com/mactokyo/ClassicCompanion/issues)，附上「關於 Classic Companion」視窗中「拷貝版本資訊」的內容。Issues 是公開的，請勿貼上對話內容、帳號資訊或截圖中的私人內容。

## English

Classic Companion opens the official ChatGPT website in a native macOS window. By default, press `⌥Space` to bring it up and `⌃⌘F` to switch between the Quick and Full window; you can change both under Settings → Shortcuts. If another app already uses `⌥Space`, choose a different combination.

This repository is used only to publish trial builds and collect feedback. It doesn’t contain the source code, and the app isn’t released under an open-source license.

**Status**: the first trial build, 0.1.0-beta.1, is being prepared and isn’t available to download yet. Once it’s public, you can download it from [Releases](https://github.com/mactokyo/ClassicCompanion/releases).

**Install** (once the trial build is public)
1. Download the DMG (or ZIP) from Releases. You can check the files against `SHA256SUMS` on the same page.
2. Open the DMG, drag `Classic Companion` to Applications, then double-click it in Applications.
3. The first time you open it, macOS says it’s an app downloaded from the Internet, asks “Are you sure you want to open it?” and notes “Apple checked it for malicious software and none was detected.” Click Open, then sign in to your ChatGPT account. The wording may differ slightly between macOS versions.

**Requirements**: macOS 15 or later, Apple silicon (arm64) only, as set in the build configuration.

**Verified on**: one MacBook Pro with Apple M4 Max running macOS 27.2. macOS 15, 26 and other Macs haven’t been tested yet.

**App language**: Simplified Chinese, Traditional Chinese, English and Japanese. By default it follows your macOS preferred languages (English if none match); change it under Settings → Language → App Language. It affects only the app’s interface, not the language of the ChatGPT web page.

**Known issues** (the full notes for each build are in `TrialNotes.en.md` attached to its release):
- Thumbnails may be blank after closing an image preview.
- Interactive components are unverified and may display or behave incorrectly.
- Read Aloud can only start and stop; regenerating during Read Aloud may keep the old reading playing.
- Fast upward scrolling in long chats occasionally bounces.
- Bringing the window up over another app’s full-screen view hasn’t been tested with a single display.
- When you edit a sent message in the Quick window, the edit box may be above the visible area.
- After `⌘M`, reopening the app occasionally leaves the window at the Dock icon; quitting and reopening fixes it.
- On the test Mac, whose system language is English, the Edit menu shows Undo / Redo in English whatever the app language, and with the app in Chinese or Japanese the View menu has no Enter Full Screen and similar items. This was observed on the test Mac; the cause hasn’t been confirmed.
- On the test Mac, whose preferred languages are English, Japanese and Simplified Chinese, choosing Traditional Chinese by hand shows punctuation in the app’s native windows in its Simplified Chinese or Japanese form (for example, “，” and “。” sit at the lower left instead of the center).

**Feedback**: please use [Issues](https://github.com/mactokyo/ClassicCompanion/issues) and include the text from Copy Version Info in the About Classic Companion window. Issues are public, so don’t paste chat content, account details or private content from screenshots.

## 日本語

Classic Companion は、ChatGPT の公式 Web サイトをネイティブの macOS ウインドウで開きます。初期設定では `⌥Space` で呼び出し、`⌃⌘F` でクイックウインドウとフルウインドウを切り替えます。どちらも 設定 → ショートカット で変更できます。`⌥Space` をほかのアプリがすでに使っている場合は、別の組み合わせに変えてください。

このリポジトリはベータ版の配布とフィードバックの受け付けにだけ使っています。ソースコードは含まれておらず、アプリはオープンソースライセンスで公開されていません。

**現在の状況**：最初のベータ版 0.1.0-beta.1 を準備中で、まだダウンロードできません。公開後は [Releases](https://github.com/mactokyo/ClassicCompanion/releases) からダウンロードできます。

**インストール**（ベータ版の公開後）
1. Releases から DMG（または ZIP）をダウンロードします。同じページの `SHA256SUMS` でファイルを確認できます。
2. DMG を開き、`Classic Companion` を「アプリケーション」にドラッグして、「アプリケーション」でダブルクリックします。
3. 初めて開くとき、macOS はインターネットからダウンロードされたアプリケーションであることを示して「開いてもよろしいですか?」と確認し、「Appleによるチェックで悪質なソフトウェアは検出されませんでした。」と表示します。「開く」をクリックし、ChatGPT アカウントにログインします。表示の文言は macOS のバージョンによって多少異なることがあります。

**動作環境**：macOS 15 以降、Apple シリコン（arm64）のみ（ビルド設定による）。

**確認済みの環境**：Apple M4 Max 搭載の MacBook Pro 1 台、macOS 27.2。macOS 15・26 やほかの Mac ではまだ確認していません。

**アプリの言語**：簡体字中国語、繁体字中国語、英語、日本語。最初は macOS の優先する言語に合わせ（どれにも当てはまらないときは英語）、設定 → 言語 → アプリの言語 で変更できます。アプリの画面にだけ適用され、ChatGPT の Web ページの言語は変わりません。

**既知の問題**（各ビルドの詳しい説明はリリースに添付の `TrialNotes.ja.md` にあります）：
- 画像のプレビューを閉じたあと、サムネールが空白になることがあります。
- インタラクティブなコンポーネントは未確認で、表示や操作がおかしくなることがあります。
- 読み上げは開始と停止のみです。読み上げ中に再生成すると、前の読み上げが続くことがあります。
- 長いチャットで素早く上にスクロールすると、ときどき跳ね返ります。
- ディスプレイ 1 台で、ほかのアプリのフルスクリーン表示の上に呼び出す操作はまだ試していません。
- クイックウインドウで送信済みのメッセージを編集すると、編集欄が表示範囲の上に隠れることがあります。
- `⌘M` のあとにアプリを開き直すと、ウインドウが Dock のアイコンの位置で止まることがあります。終了して開き直すと直ります。
- システムの言語が英語のテスト機では、アプリの言語にかかわらず編集メニューの「取り消す／やり直す」が Undo / Redo と表示され、アプリが中国語か日本語のときは「表示」メニューに「フルスクリーンにする」などの項目がありません。テスト機で観察された動作で、原因は未確認です。
- 優先する言語が英語・日本語・簡体字中国語のテスト機で繁体字中国語を手動で選ぶと、アプリのネイティブ画面の句読点が簡体字中国語または日本語の字形で表示されます（たとえば「，」「。」が中央ではなく左下に寄ります）。

**フィードバック**：[Issues](https://github.com/mactokyo/ClassicCompanion/issues) にお寄せください。「Classic Companion について」ウインドウの「バージョン情報をコピー」の内容を添えてください。Issues は公開されるため、チャットの内容、アカウント情報、スクリーンショットに写った個人的な内容は貼り付けないでください。
