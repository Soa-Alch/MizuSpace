# 水 Space（MizuSpace）

**SuiPlay0X1 用の非公式ランチャー**
Windows 化した SuiPlay0X1 を、ゲーム機らしく快適に使うためのアプリです。

*An unofficial launcher for SuiPlay0X1 running Windows 11.*
[English](#english) ・ [简体中文](#简体中文) ・ [한국어](#한국어)

> [!NOTE]
> **近日、販売開始予定です！**（現在 Ver. 0.8 系を最終テスト中）
> 販売開始の際は、このページと [YouTube](https://www.youtube.com/@SoaAlch)・[X](https://x.com/SoaAlch) でお知らせします。
>
> 💧 **発売記念価格 9.99ドル（予定）** → 通常価格 14.99ドル（予定）
>
> *Coming soon* – Launch price **$9.99** (planned) → regular $14.99<br>
> *即将发售* – 首发优惠价 **9.99 美元**（计划）→ 正常价格 14.99 美元<br>
> *곧 판매 예정* – 출시 기념가 **9.99달러**(예정) → 정가 14.99달러

<p align="center"><img src="images/home_en.png" width="800" alt="水 Space home screen"></p>

---

## 水 Space でできること

### 🏠 ホーム画面
- 本体のホームボタンで、いつでもホーム画面を呼び出せます
- Steam・Epic Games・GOG のゲームを表紙付きで一覧にして、そのまま起動
- ゲームを閉じると、元の操作状態に自動で戻ります

<img src="images/games_ja.png" width="640" alt="ゲーム一覧">

### ⚡ クイック設定
本体の「水」ボタンを押すと、画面の右からパネルがスライドして出てきます。ゲーム中でもすぐ変更できます。

| タブ | できること |
|---|---|
| 性能 | 省電力／バランス／性能のプリセット、消費電力（TDP）の細かい調整、FPS 制限 |
| デバイス | 明るさ・音量・リフレッシュレート・解像度、Wi-Fi・Bluetooth・機内モード |
| 操作 | コントローラーでのパソコン操作、ボタンの割り当て |
| 電池 | バイパス充電、充電上限（60〜90%）、自動かけ直し |
| システム | テーマ・言語・背景画像など |

<table><tr>
<td><img src="images/quick_perf_ja.png" alt="クイック設定：性能"></td>
<td><img src="images/quick_battery_ja.png" alt="クイック設定：電池"></td>
</tr><tr><td align="center">性能タブ</td><td align="center">電池タブ</td></tr></table>

### 🎯 FPS 制限
- クイック設定のスイッチひとつで、FPS の上限をオン／オフ
- 30／40／45／60 FPS から選べます。電池を長持ちさせたいときや、本体の発熱を抑えたいときに
- AMD のドライバ標準の機能を使うので、ゲームごとの設定はいりません

### 🌈 スティックのライト
- スティックまわりのライトを、9 色（空色・白・赤・橙・黄・緑・青・紫・桃）から好きな色に
- 明るさを細かく調整。「完全オフ」もワンタッチ
- 「初期値に戻す」で、本体もとの光り方に戻せます
- 起動時やスリープから戻ったときも、選んだ色をそのまま保ちます
- 画面の見本と同じ色に見えるよう、本体のライトに合わせて色を調整しています

<table><tr>
<td><img src="images/led_orange.jpg" alt="橙"></td>
<td><img src="images/led_pink.jpg" alt="桃"></td>
<td><img src="images/led_green.jpg" alt="緑"></td>
</tr><tr><td align="center">橙</td><td align="center">桃</td><td align="center">緑</td></tr></table>

### 💧 バッテリーと本体にやさしい充電 ― バイパス充電・充電上限
水が器に合わせて形を変えるように、遊び方に合わせて充電のしかたを選べます。
バッテリーの劣化や本体の発熱をおさえて、SuiPlay0X1 を**長く大切に使う**ための機能です。

| モード | こんなときに | 動き |
|---|---|---|
| 🔌 通常充電 | 出かける前に満タンにしたい | 100% まで充電 |
| 💧 バイパス | 充電器をつないだまま、長く遊ぶ | バッテリーには充電せず、充電器の電気で直接動かします。充電による熱と劣化をおさえます |
| 🌊 充電上限 | ふだんは充電器につなぎっぱなし | 60／70／80／90% で充電を止め、5% 下がったら再開。満充電のまま置かないので、バッテリーが長持ち |

**安心して任せられる、細かな気配り**
- 🔁 **自動でかけ直し**：充電器の抜き差しやスリープからの復帰で設定が外れても、自動で元どおりに（最大 3 回。それでも戻らないときはお知らせします）
- 🛡️ **必ず通常の充電に戻る**：アプリを終了したとき、本体を再起動・シャットダウンしたときは通常の充電に戻ります。「気づいたら充電されていなかった」を防ぎます（スリープ中は設定をそのまま保ちます）
- 👀 **今の状態がひと目で分かる**：「バイパス中」「充電中 ○W」など、状態と電力を表示
- ⏱️ **反映までの時間もお知らせ**：切り替えてから反映まで約 30 秒かかることを、画面で伝えます
- 🔒 **SuiPlay0X1 専用の安全ロック**：対応機種であることを確かめてから動くので、ほかの PC で誤って動くことはありません
- 🎯 **TDP・FPS 制限と組み合わせて**：消費電力と発熱を、さらにおさえられます

<img src="images/charge_ja.png" width="640" alt="充電の設定">

### 🎮 コントローラーでパソコン操作
- スティックでマウス、ボタンでクリック。デスクトップもコントローラーだけで操作できます
- ボタンの割り当ては自分で変えられます
- ディスプレイキーボードもワンタッチで呼び出し

### 📊 パフォーマンス表示
- FPS・CPU・GPU・メモリ・消費電力・温度・電池残量・時刻を、画面の隅に表示
- 表示位置と背景の濃さを選べます

<img src="images/overlay_game_1.jpg" width="800" alt="ゲーム中のパフォーマンス表示">

<sub>右上がパフォーマンス表示です。</sub>

### 🩺 動作チェック・ドライバチェック
- ボタン・スティック・振動の動作確認
- ドライバの状態を診断し、古いものや足りないものがあれば公式のダウンロードページへ案内します（勝手にドライバを入れることはしません）

<table><tr>
<td><img src="images/driver_ja.png" alt="ドライバチェック"></td>
<td><img src="images/diag_en.png" alt="動作チェック"></td>
</tr><tr><td align="center">ドライバチェック</td><td align="center">動作チェック</td></tr></table>

### 🎨 見た目
- テーマはダーク／ライト／Windows に合わせる、から選べます
- 好きな画像をガラス越しのような背景にできます。ホーム画面とクイック設定で、見せる位置・拡大・ぼかしを別々に調整
- 8 言語対応：日本語・English・简体中文・繁體中文・한국어・Español・Français・Deutsch

<table><tr>
<td><img src="images/settings_en.png" alt="English"></td>
<td><img src="images/settings_ko.png" alt="한국어"></td>
<td><img src="images/home_zh.png" alt="简体中文"></td>
</tr><tr><td align="center">English</td><td align="center">한국어</td><td align="center">简体中文</td></tr></table>

### 📦 かんたんインストール
- exe 1 つで、インストール・更新・アンインストールができます
- Windows の起動時に自動で立ち上がります（オフにもできます）

<img src="images/installer_ja.png" width="640" alt="インストーラー">

---

## 動作環境

| 項目 | 内容 |
|---|---|
| 対応機種 | **SuiPlay0X1（Windows 11）専用** |
| 注意 | SuiPlay0X1 以外の PC では起動しません |

---

## 更新履歴

新しい順に並べています。▶ を押すと各版の内容が開きます。

<details open>
<summary><b>Ver. 0.8 系</b>（2026/11）― FPS 制限・スティックのライト</summary>

| 版 | 内容 |
|---|---|
| 0.8l | 追加で開いた画面は、水ボタン・ホームボタンでまず閉じるように |
| 0.8k | 横に並んだ選択肢（ライトの色など）が、端まで行くと反対側に戻るように |
| 0.8j | ゲーム中のパフォーマンス表示を軽く。重いゲームでカクつく件を改善 |
| 0.8i | 背景の画像を選ぶとき、コントローラーとマウスを続けて使うと固まることがある不具合を修正 |
| 0.8h | ライトの色を、画面の見本どおりに見えるよう調整 |
| 0.8g | 動作チェックを 2 ページ（コントローラー／本体・状態）に整理 |
| 0.8f | ライトの色の切り替え、「完全オフ」「初期値に戻す」を追加 |
| 0.8e | **スティックのライト**：明るさ・オン／オフを本体に反映。起動時とスリープ復帰でも設定を保つ |
| 0.8d | スティックのライトの準備：本体の状態を読み取れるように |
| 0.8c | スティックのライトの準備：確認用の機能を追加 |
| 0.8b | **FPS 制限**：クイック設定のスイッチでオン／オフ、30／40／45／60 FPS から選べるように |
| 0.8a | FPS 制限の準備：今の FPS 制限の状態を、クイック設定と動作チェックに表示 |

</details>

<details>
<summary><b>Ver. 0.7 系</b>（2026/11）― ドライバチェック・背景画像・仕上げ</summary>

| 版 | 内容 |
|---|---|
| 0.7j | 消費電力の表示を改善。今の消費電力がすぐ分かるように |
| 0.7i | クイック設定の性能タブで、消費電力の数字が消えることがある不具合を修正 |
| 0.7h | 画面を ✕ で閉じた直後に、裏のゲームが誤って起動してしまう不具合を修正。水 Space の画面の上ではマウスカーソルを隠すように（マウスやリモート操作のときは表示、タッチには影響なし） |
| 0.7g | 背景の調整に「既定に戻す」を追加 |
| 0.7f | 背景のぼかしの強さを調整できるように（0〜100%） |
| 0.7e | 背景のボタンを、設定ページの「テーマ」の横に移動 |
| 0.7d | 背景の調整画面を追加（ホーム／クイック設定で別々に、見せる位置と拡大を選べる。仕上がりの見本付き）。クイック設定を開いたときに背景が半分しか出ない不具合を修正 |
| 0.7c | ホーム・クイック設定の背景画像に対応（ぼかし＋ガラス越しの見た目、ガラスの濃さ）。「このアプリについて」に開発ブランドとリンク、コピーライトを追加 |
| 0.7b | ドライバの状態を自動で診断（問題なし・古い・見つからない・エラー）。SuiPlay0X1 以外では起動しないように（アンインストールはどの PC でも可） |
| 0.7a | ドライバチェック画面を追加。機器ごとに公式のダウンロードページへ案内 |

</details>

<details>
<summary><b>Ver. 0.6 系</b>（2026/10）― 多言語・パフォーマンス表示・ブランド</summary>

| 版 | 内容 |
|---|---|
| 0.6i | 「このアプリについて」を、角の丸い横長の小窓に一新 |
| 0.6h | ロゴの書体のクレジットを表示。設定から動作チェック・アンインストールを開けるように |
| 0.6g | 非公式キャラクターを「このアプリについて」とインストーラーに小さく表示 |
| 0.6f | 「SuiPlay0X1 用の非公式ランチャー」の表記を追加 |
| 0.6e | 新しいロゴ（筆文字の「水」＋「Space」）。どの言語でも「水 Space」と表示 |
| 0.6d | パフォーマンス表示に FPS を追加。ゲームを終えたら、コントローラー操作を元の状態に戻すように。インストーラーで前の版に戻せるように |
| 0.6c | パフォーマンス表示を追加（CPU・GPU・メモリ・消費電力・温度・電池・時刻。背景の濃さと表示位置を選べる） |
| 0.6b | 8 言語に対応（日本語・English・简体中文・繁體中文・한국어・Español・Français・Deutsch）。Windows の言語に合わせて自動で切り替え、設定で変更も可 |
| 0.6a | 本体のホームボタンでホーム画面を開けるように（ボタンの登録し直しも可） |

</details>

<details>
<summary><b>Ver. 0.5 系</b>（2026/10）― 性能調整・インストーラー・改名</summary>

| 版 | 内容 |
|---|---|
| 0.5m | 古い版の自動起動が残っていると起動時にエラーが出る件に対処 |
| 0.5l | プリセット中は TDP スライダーを灰色にし、触るとカスタムに切り替わるように。設定の状態を「✓ 適用中」「↻ 適用しています…」「! エラー」の印で表示 |
| 0.5k | 性能調整の安定性を改善。起動時にコントローラーでのパソコン操作をいつもオンに |
| 0.5j | ボタンの割り当て画面を追加。ディスプレイキーボードをスイッチに。コントローラーのテストは開始ボタンで始まり、B 長押しで終了 |
| 0.5i | 性能調整とバイパス充電が同時に動いても衝突しないように。性能調整がうまくいかないときは自動で別の方式に切り替え |
| 0.5h | 動作チェック画面を追加（コントローラー・振動・水ボタン・状態をひとまとめに） |
| 0.5g | コントローラーでのマウス操作がかくつく件を修正し、なめらかに |
| 0.5f | **アプリ名を「水 Space」に変更**。インストーラーを内蔵（インストール・更新・入れ直し・アンインストール、「設定 → アプリ」に登録）。英語版 Windows でも文字化けしないように。以前の版の設定を引き継ぎ |
| 0.5e | バイパス充電に必要な部品が無いときの案内を追加 |
| 0.5d | 性能調整に必要な部品を公式の配布元から取得するボタンを追加 |
| 0.5c | 性能調整の方式を自動で選ぶように（W 単位で調整できる環境ならそれを、無理なら Windows の電源設定で） |
| 0.5b | Windows の電源設定だけで CPU を抑える方式を追加（追加の部品なしで使える） |
| 0.5a2 | 自動起動のオン／オフを、ホームとクイック設定の両方から切り替えられるように |
| 0.5a | 性能タブ：TDP の調整（プリセット・カスタム）、消費電力・CPU 温度の表示 |

</details>

<details>
<summary><b>Ver. 0.4 系</b>（2026/10）― コントローラーでパソコン操作</summary>

| 版 | 内容 |
|---|---|
| 0.4a3 | 本体の水ボタンへの対応を改善 |
| 0.4a2 | 状態の診断表示を追加。Steam の新しい表紙画像に対応 |
| 0.4a | コントローラーでマウス・キーボード操作（スティックでカーソルとスクロール、ボタンでクリック、画面キーボード）。View＋Menu 長押しでオン／オフ。画面上部に短いお知らせ表示。カーソルの速さなどを調整可能 |

</details>

<details>
<summary><b>Ver. 0.3 系</b>（2026/10）― ゲームランチャー</summary>

| 版 | 内容 |
|---|---|
| 0.3a2 | ゲームパッドでの項目移動の不具合を修正 |
| 0.3a | Steam・Epic Games・GOG のゲームを表紙付きで一覧にして起動。最近遊んだ順、ストアで絞り込み |

</details>

<details>
<summary><b>Ver. 0.2 系</b>（2026/10）― 充電・画面・無線</summary>

| 版 | 内容 |
|---|---|
| 0.2c | Wi-Fi・Bluetooth・機内モードの切り替え |
| 0.2b2 | 画面が真っ暗になる組み合わせのリフレッシュレートを出さないように |
| 0.2b | 明るさ・音量・リフレッシュレート・解像度の変更（時間内に確定しないと元に戻る安全設計） |
| 0.2a | バイパス充電・充電上限（抜き差しやスリープ復帰で自動でかけ直し、終了時は通常充電に戻す）。SuiPlay0X1 専用の安全ロック。Windows 起動時の自動起動 |

</details>

<details>
<summary><b>Ver. 0.1 系</b>（2026/10）― 土台・見た目</summary>

| 版 | 内容 |
|---|---|
| 0.1e3 | 振動の「中」を、実機でちょうど良かった強さに調整 |
| 0.1e2 | 振動の強さ（弱・中・強）と振動テスト |
| 0.1e | テーマ（システム・ダーク・ライト）。Windows のダーク／ライトに追従 |
| 0.1d2 | 本体の水ボタンでクイック設定を開けるように。スライダーは A でつかんでから ←→ で操作 |
| 0.1d | ゲームパッド操作（十字キーで移動・A 決定・B 戻る・LB/RB ページ切り替え）、操作音、操作時の振動 |
| 0.1c3 | しずくのロゴ。文字をなめらかな表示に、書体を選べるように |
| 0.1c2 | クイック設定を左の縦タブ（性能・デバイス・操作・電池・システム）＋右の項目リストに作り直し |
| 0.1c | クイック設定にタイルと明るさ・音量のスライダー |
| 0.1b | ホーム画面に左の縦メニューとページごとのカード |
| 0.1a | 最初の版。ホーム画面と、右からスライドするクイック設定の枠、時刻と電池残量の表示 |

</details>

---

## 今後の予定

🌈 **スティックの LED ライティングが完成しました！**（0.8 系）

次の新しい機能も準備中です。お楽しみに！

---

## 開発者について

はじめまして、**そあ（SoaAlch）** です。日本で個人開発をしています。
携帯ゲーミングPC が大好きで、[YouTube](https://www.youtube.com/@SoaAlch) でも発信しています。

AYANEO の **AIR シリーズ（AIR・Pro・Plus・1S）**、**AYANEO 2／2S**、**Retro Power**、**FLIP シリーズ（HX 370 搭載機まで）** など、Windows の携帯ゲーミングPC はほぼひととおり実際に使ってきました。**SuiPlay0X1 と OneXFly は、予備も含めて複数台**を手元に置いています。
たくさんの機種と専用アプリに触れてきたからこそ分かる「良いところ」と「困るところ」を、水 Space に注いでいます。

SuiPlay0X1 を Windows 化して使い始めたとき、**本体の設定をまとめて操作できるランチャーが無い**ことに困りました。バイパス充電も電力の設定も、別々のツールやファイルを使い分けるしかありませんでした。「同じことで困っている人がきっといる」と思い、水 Space を作り始めました。

目指しているのは、**水のようにやさしく、まっさらな SuiPlay0X1 でも迷わないアプリ**です。実機で一つずつ確かめながら、少しずつ育てています。

ブランド名の「Alch」は、錬金術（Alchemy）から。身近なものを組み合わせて、便利なものに変える。そんなものづくりを続けていきます。

---

## ご注意
- 本アプリは個人が開発した**非公式**のアプリです。SuiPlay0X1 のメーカーとは関係ありません。
- BIOS などのファームウェアを書き換えることはありません。
- ご利用は自己責任でお願いします。

---

## English

**水 Space (MizuSpace)** is an unofficial launcher for the SuiPlay0X1 running Windows 11.

- **Home screen** – launch your Steam / Epic Games / GOG games with cover art
- **Quick settings** – press the "水" button for a slide-in panel: performance (TDP presets), FPS limit (30/40/45/60), brightness, volume, refresh rate, resolution, Wi-Fi / Bluetooth / airplane mode
- **Battery-friendly charging** – gentle on your battery and device, like water:
  - *Bypass* – runs straight from the charger without charging the battery, reducing heat and wear during long plugged-in sessions
  - *Charge limit* – stops at 60/70/80/90% and resumes when it drops 5%, so the battery isn't kept at 100%
  - Re-applies automatically after plugging/unplugging or waking from sleep, always returns to normal charging when the app exits, and shows the current status at a glance
- **Desktop control with the gamepad** – remappable buttons, on-screen keyboard
- **Stick LED lighting** – 9 colors, brightness, full off; keeps your color after boot and sleep
- **Performance overlay** – FPS, CPU, GPU, RAM, power, temperature, battery, clock
- **Device & driver check** – links to official download pages (never installs drivers by itself)
- **Themes & wallpaper**, **8 languages**, one-exe installer
- Runs **only on SuiPlay0X1**. **Coming soon** – sales will start shortly (now in final testing, Ver. 0.8 series). Follow YouTube / X for the announcement.

This is an unofficial app made by an individual developer and is not affiliated with the device manufacturer.

**About the developer** – Hi, I'm **Soa (SoaAlch)**, an indie developer in Japan and a handheld-PC fan. I've used almost every Windows handheld – the AYANEO AIR series (AIR / Pro / Plus / 1S), AYANEO 2 / 2S, Retro Power, the FLIP series up to HX 370 models and more – and I keep several SuiPlay0X1 and OneXFly units on hand. When I started using my SuiPlay0X1 on Windows, there was no launcher to control the device in one place – so I built one. My goal is an app that feels gentle like water and is easy to use even on a fresh SuiPlay0X1.

<table><tr>
<td><img src="images/quick_perf_en.png" alt="Quick settings - Performance"></td>
<td><img src="images/quick_battery_en.png" alt="Quick settings - Battery"></td>
</tr><tr>
<td><img src="images/driver_en.png" alt="Driver check"></td>
<td><img src="images/overlay_game_2.jpg" alt="Performance overlay in game"></td>
</tr></table>

**News:** stick LED lighting is now done! More new features are on the way – stay tuned!

---

## 简体中文

**水 Space（MizuSpace）** 是一款为运行 Windows 11 的 SuiPlay0X1 打造的非官方启动器。

- **主页** – 带封面显示 Steam / Epic Games / GOG 的游戏，并可直接启动
- **快捷设置** – 按下"水"键，面板从屏幕右侧滑出：性能（TDP 预设）、帧率限制（30/40/45/60）、亮度、音量、刷新率、分辨率、Wi-Fi / 蓝牙 / 飞行模式
- **呵护电池与机身的充电** – 像水一样温柔：
  - *旁路充电* – 不给电池充电，直接由充电器供电，减少长时间插电游玩时的发热与电池损耗
  - *充电上限* – 充到 60/70/80/90% 即停止，下降 5% 后再继续，避免电池长期满电
  - 插拔充电器或从睡眠唤醒后自动重新应用；退出应用时一定恢复正常充电；当前状态一目了然
- **用手柄操作电脑** – 可自定义按键，屏幕键盘
- **摇杆灯光** – 9 种颜色、亮度调节、完全关闭，开机和睡眠唤醒后也会保持设置
- **性能显示** – FPS、CPU、GPU、内存、功耗、温度、电量、时间
- **设备与驱动检查** – 引导至官方下载页面（不会自动安装驱动）
- **主题与壁纸**、**8 种语言**、单个 exe 即可安装
- **仅支持 SuiPlay0X1**。**即将发售**（目前正在进行最终测试，Ver. 0.8 系列）。发售消息将在 YouTube / X 公布。

本应用由个人开发者制作，属于非官方应用，与设备制造商无关。

**关于开发者** – 我是来自日本的个人开发者 **Soa（SoaAlch）**，热爱掌机 PC。我几乎用过所有 Windows 掌机：AYANEO AIR 系列（AIR / Pro / Plus / 1S）、AYANEO 2 / 2S、Retro Power、FLIP 系列（直到 HX 370 机型）等，手边还备有多台 SuiPlay0X1 和 OneXFly。在 Windows 上使用 SuiPlay0X1 时，发现没有能统一管理本机设置的启动器，于是自己做了一个。目标是做出像水一样温和、即使是全新的 SuiPlay0X1 也能轻松上手的应用。

**最新消息：** 摇杆 LED 灯光功能已完成！更多新功能正在准备中，敬请期待！

---

## 한국어

**水 Space(MizuSpace)**는 Windows 11을 설치한 SuiPlay0X1용 비공식 런처입니다.

- **홈 화면** – Steam / Epic Games / GOG 게임을 표지와 함께 표시하고 바로 실행
- **빠른 설정** – "水" 버튼을 누르면 화면 오른쪽에서 패널이 나타납니다: 성능(TDP 프리셋), FPS 제한(30/40/45/60), 밝기, 음량, 주사율, 해상도, Wi-Fi / Bluetooth / 비행기 모드
- **배터리와 본체에 부드러운 충전** – 물처럼 부드럽게:
  - *바이패스* – 배터리를 충전하지 않고 충전기 전원으로 직접 구동해, 오래 연결해서 플레이할 때의 발열과 열화를 줄입니다
  - *충전 상한* – 60/70/80/90%에서 멈추고 5% 내려가면 다시 충전. 배터리를 100%로 계속 두지 않아 오래 갑니다
  - 충전기 연결·분리나 절전 해제 후 자동 재적용, 앱 종료 시 반드시 일반 충전으로 복귀, 현재 상태를 한눈에 표시
- **컨트롤러로 PC 조작** – 버튼 재지정, 화상 키보드
- **스틱 조명** – 9가지 색상, 밝기 조절, 완전 끄기. 부팅·절전 해제 후에도 설정 유지
- **성능 표시** – FPS, CPU, GPU, 메모리, 소비 전력, 온도, 배터리, 시각
- **장치·드라이버 점검** – 공식 다운로드 페이지로 안내(드라이버를 자동으로 설치하지 않음)
- **테마와 배경 화면**, **8개 언어**, exe 하나로 설치
- **SuiPlay0X1 전용**입니다. **곧 판매 예정**입니다(현재 최종 테스트 중, Ver. 0.8 시리즈). 판매 소식은 YouTube / X에서 알려 드립니다.

개인 개발자가 만든 비공식 앱이며, 기기 제조사와는 관계가 없습니다.

**개발자 소개** – 안녕하세요, 일본에서 개인 개발을 하고 있는 **Soa(SoaAlch)**입니다. 휴대용 게이밍 PC를 좋아합니다. AYANEO AIR 시리즈(AIR / Pro / Plus / 1S), AYANEO 2 / 2S, Retro Power, FLIP 시리즈(HX 370 탑재 모델까지) 등 Windows 휴대용 게이밍 PC는 거의 다 직접 써 왔고, SuiPlay0X1과 OneXFly는 예비까지 여러 대 갖고 있습니다. SuiPlay0X1을 Windows로 쓰기 시작했을 때 본체 설정을 한곳에서 조작할 수 있는 런처가 없어서 직접 만들었습니다. 물처럼 부드럽고, 처음 쓰는 SuiPlay0X1에서도 헤매지 않는 앱을 목표로 하고 있습니다.

**새 소식:** 스틱 LED 조명이 완성되었습니다! 새로운 기능도 준비 중이니 기대해 주세요!

---

## Links
- YouTube: https://www.youtube.com/@SoaAlch
- X: https://x.com/SoaAlch

---

© 2026 SoaAlch. All rights reserved.
無断での転載・再配布・改変を禁止します。詳しくは [LICENSE](LICENSE) をご覧ください。
