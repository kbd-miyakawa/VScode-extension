
Visual Studio Codeのためのキー割り当て
======================================


訳文
----

Visual Studio
Codeは、あなたが、ほとんどのタスクを、キーボードから、直接。実行できます。
このページは、既定のキー割り当て（キーボード・ショートカット）を一覧で示しています。
そして、あなたが、それらをどのように更新するかについて説明しています。

#### 備考：

あなたが、Mac上で、このページを訪れている場合、
あなたは、Macのためのキー割り当てを見るでしょう。
あなたが、WindowsやLinuxを使用して訪れている場合、あなたは、そのプラットホームのためのキーを見るでしょう。
あなたが、他のプラットホームのためのキー割り当てを必要とする場合、
あなたが興味があるキーの上に、あなたのマウスカーソルを重ねます。


キーマップ拡張機能
------------------


Keymap Extensions

キーボード・ショートカットは、生産性を上げるためには不可欠です。
そして、キーボードの入力習慣を変更するのは難しいかもしれません。
これを支援するために、「ファイル」&gt;「設定」&gt;「キーマップ拡張機能」で、一般的なキーマップ拡張の一覧が表示されます。
これらの拡張機能は、他のエディタのショートカットと一致するように、VS
Codeのショートカットを変更します。
そのため、あなたは、新しいキーボード・ショートカットを学ぶ必要はありません。
また、Marketplaceには、[キーマップ拡張機能](https://marketplace.visualstudio.com/search?target=VSCode&category=Keymaps&sortBy=Downloads)のカテゴリもあります。


#### ヒント：

上記の拡張機能は、動的に問い合わせられます。
どの拡張機能が、最も良いか決定するために説明とレビューを読み、そして、上記の拡張機能タイルをクリックします。
詳細については、[Marketplace](https://marketplace.visualstudio.com/vscode)を参照してください。


基本的な編集
------------


Basic Editing


#### 備考

次のキーは、標準的なUSキーボード・レイアウトを前提として提供されています。
あなたが、異なるキーボードレイアウトを使用する場合、<span
class="FontColorBlue">以下</span>([原文リンク](https://code.visualstudio.com/docs/customization/keybindings#_keyboard-layouts))をお読みください。



| Key      |           Command            |                                   Command id |
|-------------------|-----------------------------------------------------|---------------------------------------------------|
|  Ctrl+X           |   行を切り取る（空選択）                              |  editor.action.clipboardCutAction| 
|  Ctrl+C            |  行をコピー（空選択）                                |  editor.action.clipboardCopyAction 
|  Ctrl+Shift+K      |  行を削除                                            |  editor.action.deleteLines 
|  Ctrl+Enter        |  行を下に挿入                                        |  editor.action.insertLineAfter 
|  Ctrl+Shift+Enter  |  行を上に挿入                                        |  editor.action.insertLineBefore 
|  Alt+↓            |   行を下に移動                                       |   editor.action.moveLinesDownAction 
|  Alt+↑            |   行を上に移動                                       |   editor.action.moveLinesUpAction 
|  Shift+Alt+↓      |   行を下にコピー                                     |   editor.action.copyLinesDownAction 
|  Shift+Alt+↑      |   行を上にコピー                                     |   editor.action.copyLinesUpAction 
|  Ctrl+D            |  次の一致を検索するための選択を追加                  |  editor.action.addSelectionToNextFindMatch 
|  Ctrl+K Ctrl+D     |  次の一致を検索するために最後の選択に移動            |  editor.action.moveSelectionToNextFindMatch 
|  Ctrl+U            |  最後のカーソル操作を元に戻す                        |  cursorUndo 
|  Ctrl+Shift+I      |  選択される各々の行の端の挿入カーソル                |  editor.action.insertCursorAtEndOfEachLineSelected
|  Ctrl+Shift+L      |  現在の選択範囲のすべての出現箇所を選択              |  editor.action.selectHighlights 
|  Ctrl+F2           |  現在の単語のすべての出現箇所を選択                  |  editor.action.changeAll 
|  Ctrl+I            |  現在の行を選択                                      |  expandLineSelection 
|  Ctrl+Alt+↓       |   カーソルを下に挿入                                 |   editor.action.insertCursorBelow 
|  Ctrl+Alt+↑       |   カーソルを上に挿入                                 |   editor.action.insertCursorAbove 
|  Ctrl+Shift+\\     |  対応する括弧に移動                                  |  editor.action.jumpToBracket 
|  Ctrl+］           |  行をインデント                                      |  editor.action.indentLines 
|  Ctrl+［           |  行のインデントを解除する                            |  editor.action.outdentLines 
|  Home              |  行の先頭に移動                                      |  cursorHome 
|  End               |  行の末尾に移動                                      |  cursorEnd 
|  Ctrl+End          |  ファイルの末尾に移動                                |  cursorBottom 
|  Ctrl+Home         |  ファイルの先頭に移動                                |  cursorTop 
|  Ctrl+↓           |   行を下に、スクロールする                           |   scrollLineDown 
|  Ctrl+↑           |   行を上に、スクロールする                           |   scrollLineUp 
|  Ctrl+PageDown     |  ページを下に、スクロールする                        |  scrollPageDown 
|  Ctrl+PageUp       |  ページを上に、スクロールする                        |  scrollPageUp 
|  Ctrl+Shift+\[     |  領域を折り畳む                                      |  editor.fold
|  Ctrl+Shift+\]     |  領域を展開する                                      |  editor.unfold
|  Ctrl+K Ctrl+J     |  すべての領域を展開する                              |  editor.unfoldAll
|  Ctrl+K Ctrl+C     |  行コメントの追加                                    |  editor.action.addCommentLine 
|  Ctrl+K Ctrl+U     |  行コメントを削除                                    |  editor.action.removeCommentLine 
|  Ctrl+/            |  行コメントをトグル                                  |  editor.action.commentLine 
|  Shift+Alt+A       |  ブロック・コメントをトグル                          |  editor.action.blockComment 
|  Ctrl+F            |  検索                                                |  actions.find 
|  Ctrl+H            |  置換                                                |  editor.action.startFindReplaceAction 
|  F3                |  次を検索                                            |  editor.action.nextMatchFindAction 
|  Shift+F3          |  前を検索                                            |  editor.action.previousMatchFindAction 
|  Alt+Enter         |  見つかったすべての一致を選択する                    |  editor.action.selectAllMatches
|  Alt+C             |  大文字小文字を区別する                              |  toggleFindCaseSensitive 
|  Alt+R             |  正規表現を検索する                                  |  toggleFindRegex 
|  Alt+W             |  全体の単語を検索する                                |  oggleFindWholeWord 
|  Ctrl+M            |  フォーカスを設定するためのTabキーの使用を切り替える |  editor.action.toggleTabFocusMode 
|  unassigned        |  描画する空白文字を切り替える                        |  toggleRenderWhitespace
|  Alt+Z             |  ワードラップを切り替える                            |  editor.action.toggleWordWrap
|

高機能な言語の編集
------------------


Rich Languages Editing



|  Key|                Command|                      Command id|
|  -------------------| -----------------------------| ---------------------------------------------|
|  Ctrl+Space|         提案をトリガ|                 editor.action.triggerSuggest|
|  Ctrl+Shift+Space|   パラメータ・ヒントをトリガ|   editor.action.triggerParameterHints|
|  Shift+Alt+F|        ドキュメントの書式設定        editor.action.format|
|  F12|                定義に移動する|               editor.action.goToDeclaration|
|  Alt+F12|            Peekの定義|                   editor.action.previewDeclaration|
|  Ctrl+.|             応急処置|                     editor.action.quickFix|
|  Shift+F12|          参照を表示|                   editor.action.referenceSearch.trigger|
|  F2|                 シンボルの名前を変更|         editor.action.rename|
|  Ctrl+Shift+.|       次の値に置き換え|             editor.action.inPlaceReplace.down|
|  Ctrl+Shift+,|       先程の値に置き換え|           editor.action.inPlaceReplace.up|
|  Shift+Alt+→|        ASTの選択を拡大|              editor.action.smartSelect.grow|
|  Shift+Alt+←|        ASTの選択を縮小|              editor.action.smartSelect.shrink|
|  Ctrl+Shift+X|       末尾の空白文字を削除|         editor.action.trimTrailingWhitespace|
|  Ctrl+K M|           言語モードの変更|             workbench.action.editor.changeLanguageMode|
|

ナビゲーション
--------------


Navigation


|  Key|                Command|                      Command id|
|  -------------------| -----------------------------| ---------------------------------------------|
|  Ctrl+T|          すべての記号を表示|                  workbench.action.showAllSymbols|
|  Ctrl+G|          行に移動...|                         workbench.action.gotoLine|
|  Ctrl+P|          ファイルに移動...|                   workbench.action.quickOpen|
|  Ctrl+Shift+O|    記号に移動...|                       workbench.action.gotoSymbol|
|  Ctrl+Shift+M|    エラーと警告を表示|                  workbench.action.showErrorsWarnings|
|  F8|              次のエラーや警告に移動|              editor.action.marker.next|
|  Shift+F8|        先程のエラーや警告に移動|            editor.action.marker.prev|
|  Ctrl+Shift+P     すべてのコマンドを表示|              workbench.action.showCommands|
|  Ctrl+Shift+Tab   エディタ・グループの履歴に移動する   workbench.action.openPreviousRecentlyUsedEditorInGroup|

|  Alt+←|           戻る|                                workbench.action.navigateBack|
|  Alt+→|           進む|                                workbench.action.navigateForward|

エディタ/ウィンドウ管理
-----------------------


Editor/Window Management

|  Key |                Command |                      Command id|
|  ------------------- | -----------------------------| ---------------------------------------------|
|  Ctrl+Shift+N |         ウィンドウの新規作成 |                    workbench.action.newWindow |
|  Ctrl+W                ウィンドウを閉じる|                      workbench.action.closeWindow|
|  Ctrl+F4|              エディタを閉じる|                        workbench.action.closeActiveEditor|
|  Ctrl+K F|             フォルダを閉じる|                        workbench.action.closeFolder|
|  unassigned            エディタ・グループ間を循環する           workbench.action.navigateEditorGroups
|  Ctrl+\\|              エディタを分割|                          workbench.action.splitEditor|
|  Ctrl+1|               左側のエディタにフォーカスする|          workbench.action.focusFirstEditor|
|  Ctrl+2|               横のエディタにフォーカスする|            workbench.action.focusSecondEditor|
|  Ctrl+3|               右側のエディタにフォーカスする|          workbench.action.focusThirdEditor|
|  Ctrl+K Ctrl+Left |     エディタ・グループの左にフォーカスする|   workbench.action.focusPreviousGroup
|  Ctrl+K Ctrl+Right|     エディタ・グループの右にフォーカスする|   workbench.action.focusNextGroup
|  Ctrl+Shift+PageUp |    エディタを左に移動する             |      workbench.action.moveEditorLeftInGroup
|  Ctrl+Shift+PageDown |  エディタを右に移動する             |      workbench.action.moveEditorRightInGroup
|  Ctrl+K ←|             アクティブ・エディタの左に移動|          workbench.action.moveActiveEditorLeft|
|  Ctrl+K →|             アクティブ・エディタの右に移動|          workbench.action.moveActiveEditorRight|


ファイル管理
------------


File Management


|  Key|             Command|                                            Command id|
|  -------------------| -----------------------------| ---------------------------------------------|
|  Ctrl+N|         | ファイルの新規作成|                                 workbench.action.files.newUntitledFile|
|  Ctrl+O|         | ファイルを開きます...|                              workbench.action.files.openFile|
|  Ctrl+S|         | 保存|                                               workbench.action.files.save|
|  Ctrl+K S        | すべてを保存します                                  workbench.action.files.saveAll|
|  Ctrl+Shift+S    | 名前を付けて保存...                                 workbench.action.files.saveAs|
|  Ctrl+F4         | 閉じる                                              workbench.action.closeActiveEditor|
|  Ctrl+F4         | 閉じる                                              workbench.action.closeActiveEditor|
|  unassigned      | 他を閉じる                                          workbench.action.closeOtherEditors|
|  unassigned      | 他のグループを閉じる                                workbench.action.closeEditorsInOtherGroups|
|  unassigned      | グループを左に閉じる                                workbench.action.closeEditorsToTheLeft|
|  unassigned      | グループを右に閉じる                                workbench.action.closeEditorsToTheRight|
|  Ctrl+K Ctrl+W   | すべてを保存します|                                 workbench.action.files.saveAll||
|  Ctrl+Shift+T    | 閉じたエディタを再び開く                            workbench.action.reopenClosedEditor|
|  Ctrl+K Enter|   | 作業ファイルへ追加|                                 workbench.files.action.addToWorkingFiles|
|  Ctrl+Tab        | 次を開く                                            workbench.action.openNextRecentlyUsedEditorInGroup|
|  Ctrl+Shift+Tab  | 前を開く                                            workbench.action.openPreviousRecentlyUsedEditorInGroup|
|  Ctrl+K P|       | アクティブ・ファイルのパスをコピーする              workbench.action.files.copyPathOfActiveFile|
|  Ctrl+K R|       | ウィンドウ内のアクティブなファイルを表示する        workbench.action.files.revealActiveFileInWindows|
|  Ctrl+K O|       | 新しいウィンドウ内の、開かれたファイルを表示する|   workbench.action.files.showOpenedFileInNewWindow|
|  unassigned      | 開いたファイルを比較する                            workbench.files.action.compareFileWith|


表示
----


Display


|  Key|            Command|                                        Command id|
|  --------------- |-----------------------------------------------| ----------------------------------------------|
|  F11|            フルスクリーンに切り替える                    |  workbench.action.toggleFullScreen|
|  Ctrl+=|         拡大|                                         |  workbench.action.zoomIn|
|  Ctrl+-|         縮小|                                         |  workbench.action.zoomOut|
|  Ctrl+Numpad 0|    ズームをリセット                            |    workbench.action.zoomReset
|  Ctrl+B|         サイドバーの表示属性を切り替える              |  workbench.action.toggleSidebarVisibility|
|  Ctrl+Shift+D|   デバッグを表示|                               |  workbench.view.debug|
|  Ctrl+Shift+E|   エクスプローラー/トグルのフォーカスを表示する |  workbench.view.explorer|
|  Ctrl+Shift+G|   Gitを表示|                                    |  workbench.view.git|
|  Ctrl+Shift+F|   検索を表示|                                   |  workbench.view.search|
|  Ctrl+Shift+H    ファイルの交換                                |  workbench.action.replaceInFiles|
|  Ctrl+Shift+X    拡張機能を表示する                            |  workbench.view.extensions|
|  Ctrl+Shift+J|   検索の詳細を切り替える                        |  workbench.action.search.toggleQueryDetails|
|  Ctrl+Shift+C|   新しいコマンド・プロンプトを開く|             |  workbench.action.terminal.openNativeConsole|
|  Ctrl+Shift+U|   出力を表示|                                   |  workbench.action.output.toggleOutput|
|  Ctrl+Shift+V|   Markdownプレビューに切り替える                |  workbench.action.markdown.togglePreview|
|  Ctrl+K V|        プレビューを側面で開く                       |   markdown.showPreviewToSide|
|  Ctrl+\` |        統合ターミナルを切り替える                   |   workbench.action.terminal.toggleTerminal
|

環境設定
--------


Preferences


|  Key|            Command|                                        Command id|
|  --------------- |-----------------------------------------------| ----------------------------------------------|
|  割り当てられていません|   ユーザー設定を開く|                 workbench.action.openGlobalSettings|
|  割り当てられていません|   作業スペース設定を開く|             workbench.action.openWorkspaceSettings|
|  Ctrl+K Ctrl+S         |    キーボード・ショートカットを開く|   workbench.action.openGlobalKeybindings|
|  割り当てられていません|   ユーザー・スニペットを開く|         workbench.action.openSnippets|
|  割り当てられていません|   カラー・テーマを選択|               workbench.action.selectTheme|
|  割り当てられていません|   表示言語を設定する |                 workbench.action.configureLocale|


デバッグ
--------


Debug

|  Key|            Command|                                        Command id|
|  --------------- |-----------------------------------------------| ----------------------------------------------|
|  F9|           |  ブレークポイントを切り替える|   editor.debug.action.toggleBreakpoint|
|  F5|           |  再開|                          workbench.action.debug.continue|
|  F5|           |  一時停止|                      workbench.action.debug.start|
|  F11|          |  ステップ実行|                  workbench.action.debug.stepInto|
|  Shift+F11|    |  ステップ実行を終了             Out workbench.action.debug.stepOut|
|  F10|          |  ステップ・オーバー             workbench.action.debug.stepOver|
|  Shift+F5|     |  停止|                          workbench.action.debug.stop|
|  Ctrl+K Ctrl+I |  ホバーを表示する |              editor.action.showHover|
|

タスク
------


Tasks



|  Key|            Command|                                        Command id|
|  --------------- |-----------------------------------------------| ----------------------------------------------|
|  Ctrl+Shift+B|  | タスクのビルドを実行|   workbench.action.tasks.build|
|  unassigned     | タスクのテストを実行|   workbench.action.tasks.test|




拡張機能
--------


Extensions



  Key|                      Command|                        Command id|
  ------------------------- ------------------------------- -----------------------------------------------------
  割り当てられていません|   拡張をインストール|             workbench.extensions.action.installExtension|
  割り当てられていません|   インストールされた拡張を表示|   workbench.extensions.action.listExtensions|
  割り当てられていません|   古い拡張を表示|                 workbench.extensions.action.listOutdatedExtensions|
  割り当てられていません|   人気のある拡張機能を表示する    workbench.extensions.action.showPopularExtensions
  割り当てられていません|   すべての拡張機能を更新する      workbench.extensions.action.updateAllExtensions




ショートカットをカスタマイズする
--------------------------------


Customizing Shortcuts

VS Codeのすべてのキーボードショートカットは、User/keybindings.jsonファイルにより、カスタマイズすることができます。

-   VS
    Codeのすべてのキーボードショートカットは、User/keybindings.jsonファイルにより、カスタマイズすることができます。
-   あなたが望む方法で、キーボードショートカットを設定するために、File、Preferences、Keyboard
    Shortcutsの下にメニューに移動します。

<!-- -->

-   あなたが望む方法で、キーボードショートカットを設定するために、メニューの下のファイル&gt;キーボード・ショートカットへ移動します。（Macでは、コード&gt;設定&gt;キーボード・ショートカット）
-   これは、左側に、既定のキーボード・ショートカットを、そして、あなたが、右側に、既定の結合を上書きできる、あなたのUser/keybindings.jsonファイルを開くでしょう。
-   上の一覧は、網羅的なものではありません。より多くのコマンドは、既定のキーボード・ショートカットの「その他の利用可能なコマンドはこちら」の下に、一覧になっているかもしれません。






キーボード規則
--------------

Keyboard Rules

キーボードショートカットのディスパッチは、JSONで表される規則のリストを分析することによって行われます。ここに、いくつかの例があります。：

``` {.prettyprint}
// Keybindings that are active when the focus is in the editor
// フォーカスが、エディタにあるとき、キー割り当てがアクティブです。
{ "key": "home",            "command": "cursorHome",                  "when": "editorTextFocus" },
{ "key": "shift+home",      "command": "cursorHomeSelect",            "when": "editorTextFocus" },

// Keybindings that are complementary
// キー割り当ては、補完的です
{ "key": "f5",              "command": "workbench.action.debug.continue", "when": "inDebugMode" },
{ "key": "f5",              "command": "workbench.action.debug.start",    "when": "!inDebugMode" },

// Global keybindings
// 広範囲のキー割り当て
{ "key": "ctrl+f",          "command": "actions.find" },
{ "key": "alt+left",        "command": "workbench.action.navigateBack" },
{ "key": "alt+right",       "command": "workbench.action.navigateForward" },

// Global keybindings using chords (two separate keypress actions)
//広範囲なキー割り当ては、コードを使用しています（別々に2つ押されたキー動作）
{ "key": "ctrl+k enter",    "command": "workbench.action.keepEditor" },
{ "key": "ctrl+k ctrl+w",   "command": "workbench.action.closeAllEditors" },
```

それぞれの規則は、以下から構成されています。：

-   押されたキーを説明するキー。
-   実行するコマンドの識別子が含まれるコマンド
-   句に、現在のコンテキストに従い評価されるbool式が含まれているときのオプション。

キーが押されるとき：

-   規則は、下から上に評価されます。
-   最初の規則は、キーと受け入れられた時の言葉の両方に一致します。
-   どんな規則も処理されません。
-   規則が見つかり、コマンドが設定されていると、コマンドが、実行されます。

追加されたUser/keybindings.json規則は、規定のルールの下に、実行時に添付されます。このように、それらは、規定のルールを上書きできます。
User/keybindings.jsonファイルは、このように、それを編集するVS
Codeで監視されます。VS
Codeが実行している間、実行時に規則が更新されるでしょう。




受け入れられるキー
------------------

Accepted keys

キーは、修飾子とキーそのもので構成されています。

次の修飾子は受け入れられます：

  OS|        修飾子|
  ---------- -----------------------------
  OS X|      ctrl+, shift+, alt+, cmd+|
  Windows|   ctrl+, shift+, alt+, win+|
  Linux|     ctrl+, shift+, alt+, meta+|

次のキーは、受け入れられます：

-   f1-f19, a-z, 0-9
-   \`, -, =, \[, \], \\, ;, ', ,, ., /
-   left, up, right, down, pageup, pagedown, end, home
-   tab, enter, escape, space, backspace, delete
-   pausebreak, capslock, insert
-   numpad0-numpad9, numpad\_multiply, numpad\_add, numpad\_separator
-   numpad\_subtract, numpad\_decimal, numpad\_divide

コードは、スペースで2つのkeypressesを分離することによって説明されます。例えば：ctrl+k
ctrl+c。




when句の内容
------------


when Clause Contexts

あなたのキー割り当てが、オプションのwhen句を通して有効なとき、VS
Codeは、あなたが細かく制御することができます。
あなたのキー割り当てが、when句を持っていない場合、キー割り当ては、常に、広範囲に利用できます。

bool型のtrue/falseを評価する、使用できるwhen句コンテキストの一部を下記に示します。：

コンテキストの名前
Trueのとき
エディタのコンテキスト
editorFocus
テキストかウィジェットで、エディタは、フォーカスを持っています。
editorTextFocus
エディタ内のテキストは、フォーカスを持っています（カーソルが点滅しています）。
editorHasSelection
テキストは、エディタ内で選択されています。
editorHasMultipleSelections
テキストの複数の領域が、選択されています（複数のカーソル）。
editorReadOnly
エディタは、読取専用です。
editorLangId
エディタの関連付けた言語idが、一致するときTrueです。例："editorLangId ==
typescript".
モード・コンテキスト
inDebugMode
デバッグ・セッションが、実行されています。
inSnippetMode
エディタは、スニペット・モードです。
inQuickOpen
クイック・オープン・ドロップダウンは、フォーカスを持っています。
エディタ・ウィジェット・コンテキスト
findWidgetVisible
エディタの検索ウィジェットが表示されています。
suggestWidgetVisible
提案ウィジェット（インテリセンス）が、表示されます。
suggestWidgetMultipleSuggestions
複数の提案が、表示されました。
renameInputVisible
名前の変更入力テキスト・ボックスが、表示されます。
referenceSearchVisible
全ての参照を検索覗き見ウィンドウが、開いています。
inReferenceSearchEditor
全ての参照を検索覗き見ウィンドウ・エディタが、フォーカスを持っています。
config.editor.stablePeek
覗き見エディタを開いたままにする（editor.stablePeek設定によって制御されています）。
quickFixWidgetVisible
素早く修正ウィジェットが、表示されます。
parameterHintsVisible
パラメータ・ヒントが、表示されます（editor.parameterHints設定によって制御されています）。
parameterHintsMultipleSignatures
複数のパラメータ・ヒントが、表示されます。
統合ターミナル・コンテキスト
terminalFocus
統合ターミナルは、フォーカスを持っています。
グローバルUIのコンテキスト
resourceLangId
Explorerやエディタのタイトル言語idが、一致するときTrueです。例："resourceLangId
== markdown"
globalMessageVisible
メッセージボックスは、VS Codeの一番上に表示されています。
searchViewletVisible
検索ビューは、開いています。
replaceActive
検索ビュー置換テキスト・ボックスは、開いています。
上の一覧は、網羅的なものではありません。そして、あなたは、既定のキーボード・ショートカットの中で、
VS CodeのUI固有のwhenコンテキストのいくつかを見るかもしれません。






固有のキー割り当て規則を削除する
--------------------------------


Removing a specific key binding rule

あなたは、キー割り当て規則を記述することができます。それは、特定の既定のキー割り当ての削除を目的としています。
keybindings.jsonで、それは、常に、VS
Codeのすべてのキー割り当てを再定義することが可能ですが、
TabやEscのような、特にオーバーロードされたキーの周辺で、小さな微調整を行うことが、非常に困難です。
特定のキー割り当てを削除するために、単純に、－コマンドと追加すると、規則は、削除は規則になります。

ここに例があります。

``` {.prettyprint}
// In Default Keyboard Shortcuts
// 既定のキーボードショートカットで
...
{ "key": "tab", "command": "tab", "when": ... },
{ "key": "tab", "command": "editor.emmet.action.expandAbbreviation", "when": ... },
{ "key": "tab", "command": "jumpToNextSnippetPlaceholder", "when": ... },
{ "key": "tab", "command": "acceptSelectedSuggestion", "when": ... },
...

// To remove the second rule, for example, add in keybindings.json:
// ２つ目の規則を削除するには、例えば、keybindings.jsonのadd：
{ "key": "tab", "command": "-editor.emmet.action.expandAbbreviation" }
```






キーボードレイアウト
--------------------

Keyboard layouts

#### 備考

このセクションは、エディタで入力することではなく、キー割り当てにのみ、関連しています。

より正確には、上記のキーは、仮想キーの文字列表現です。そして、それらが押されるとき、
作成された文字と関連づけられて、必ず、行うわけではありません。：

-   参照：https://msdn.microsoft.com/en-us/library/windows/desktop/dd375731(v=vs.85)
-   tab for VK\_TAB (0x09)
-   ; for VK\_OEM\_1 (0xBA)
-   = for VK\_OEM\_PLUS (0xBB)
-   , for VK\_OEM\_COMMA (0xBC)
-   - for VK\_OEM\_MINUS (0xBD)
-   . for VK\_OEM\_PERIOD (0xBE)
-   / for VK\_OEM\_2 (0xBF)
-   \` for VK\_OEM\_3 (0xC0)
-   \[ for VK\_OEM\_4 (0xDB)
-   \\ for VK\_OEM\_5 (0xDC)
-   \] for VK\_OEM\_6 (0xDD)
-   ' for VK\_OEM\_7 (0xDE)
-   etc

異なるキーボードレイアウトは、それらが押されるとき、
通常、上記の仮想キーを再配置するか、生成される文字を変更します。標準的なUSではなく、
異なるキーボードレイアウトを使用するとき、Visual Studio
Codeは、以下を処理します。：

すべてのキー割り当てが、UI内に、現在のシステムのキーボードレイアウトを使用して提供されます。
例えば、フランスの（France）キーボードレイアウトを使用して、現在、Ctrl+\*として提供されるとき、エディタを分割します：

![エディタを分割](../Images017/014-005_keybinding_render-key-binding.png)

keybindings.jsonを編集するとき、VS
Codeは、まぎらわしいキー割り当てを強調します。－
それらは、標準的なUSキーボード・レイアウトの下で文字を生成して、ファイル内に表示します。
しかし、それは、現在のシステムのキーボードレイアウトの下で、異なるラベルのキーを押す必要があります。
例えば、ここに、フランスの（France）キーボードレイアウトを使用するとき、既定のキー割り当ての規則が、どのように検索されるかがあります。：

![既定のキー割り当ての規則](../Images017/014-006_keybinding_keybindings-json.png)

また、keybindings.jsonを編集するとき、キー割り当て規則の入力を支援するウィジェットがあります。定義されたキー割り当てされたウィジェットを起動するために、
Ctrl+K
Ctrl+Kを押します。ウィジェットは、キー入力のために待機します。そして、テキストボックスで、
そして、その下に、シリアル化されたJSON表示を描画します。VS
Codeのキーは、あなたの現在のキーボードレイアウトの下で、検出します。
一旦、あなたが望むキーの組み合わせをタイプする場合、あなたは、Enterを押すことができ、そして、規則スニペットが挿入されます。

![定義されたキー割り当てされたウィジェットを起動するために、Ctrl+K
Ctrl+Kを押します。](../Images017/014-007_keybinding_key-binding-widget.png)

#### 備考

Visual Studio
Codeは、スタートアップ上で、あなたの現在のキーボードレイアウトを検出して、
続いて、この情報をキャッシュします。優れた経験のため、あなたが、キーボードレイアウトを変更する場合、私たちは、VS
Codeを再起動することを推奨します。




### 次の手順

Next Steps

現在、あなたは、私たちのキー割り当てのサポートについて知っています。次は...

-   [カスタム化](Doc008_CustomizeVisualStudioCode.html)([原文リンク](https://code.visualstudio.com/docs/customization/overview))－あなたが望む方法で、Codeを設定します－テーマ、設定など
-   [言語サポー](Doc014_DisplayLanguages.html)ト([原文リンク](https://code.visualstudio.com/docs/languages/overview))－私達の優れた、より優れた、最高の言語グリッドは、あなたが期待できるか確認します。
-   [デバッグ](../Editor/Doc005_Debugging.html)([原文リンク](https://code.visualstudio.com/docs/editor/debugging))－これは、VS
    Codeが本当に輝くところです
-   [Node.js](../Runtimes/Doc023_NodeJsApplicationsWithVSCode.html)([原文リンク](https://code.visualstudio.com/docs/runtimes/nodejs))－サンプル・アプリとNode.js使い方の端から端まで



### 一般的な質問


Common Questions

Q:どのように、どんなコマンドが、特定のキーに結合されるのか、見つけるのでしょうか？

A:既定のキーボード・ショートカットでは、Ctrl+Shift+Oを押すことによって、簡単な概要を開きます。

![簡単な概要](../Images017/014-008_keybinding_outline.png)

Q:どのように、動作にキー割り当てを追加するのでしょうか？例えば、行を削除するために、Ctrl+D追加する

A:既定のキーボードショートカットで動作を起動する規則を検索します。そして、あなたのUser/keybindings.jsonファイルで、その修正版を記述します。：

``` {.prettyprint}
// Original, in Default Keyboard Shortcuts
//元の既定のキーボードショートカットでは、
{ "key": "ctrl+shift+k",          "command": "editor.action.deleteLines",
                                     "when": "editorTextFocus" },
// Modified, in User/keybindings.json, Ctrl+D now will also trigger this action
// 修正されたUser/keybindings.jsonでは、また、Ctrl+Dは、現在、この動作を起動します。

{ "key": "ctrl+d",                "command": "editor.action.deleteLines",
                                     "when": "editorTextFocus" },
```

Q:どのように、動作からキー割り当てを削除するのでしょうか？例えば、Delete
LinesからCtrl+Shift+Kを削除します。

A:既定のキーボードショートカットで動作を起動する規則を検索します。そして、あなたのUser/keybindings.jsonファイルに、その修正版を記述します。：

``` {.prettyprint}
// Original, in Default Keyboard Shortcuts
// 元の既定のキーボードショートカットでは、
{ "key": "ctrl+shift+k",          "command": "editor.action.deleteLines",
                                     "when": "editorTextFocus" },
// Modified, in User/keybindings.json, Ctrl+D now will also trigger this action
// 修正されたUser/keybindings.jsonでは、また、Ctrl+Dは、現在、この動作を起動します。
{ "key": "ctrl+d",                "command": "editor.action.deleteLines",
                                     "when": "editorTextFocus" },
```

Q:私は、キー割り当てを、特定のファイルタイプのためだけに、どのように、追加することができるのでしょうか？

A:あなたの条項の、editorLangId context keyを使用します。：

``` {.prettyprint}
{ "key": "shift+alt+a",           "command": "editor.action.blockComment",
                                     "when": "editorTextFocus && editorLangId == 'csharp'" },
```

Q:私は、User/keybindings.jsonでキー割り当てを修正しましたが、なぜ、それらが動作しないのでしょう？

A:ほとんどの、一般的な問題は、ファイルでの構文エラーです。それ以外の場合には、条項を削除するか、
あるいは、別のキーを選択してください。残念ながら、ここで重要な点は、それは、試行錯誤的なプロセスということです。



