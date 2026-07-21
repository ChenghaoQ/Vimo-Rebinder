<!--
Canonical source: README.md
Locale: ja
Do not edit product facts independently from the English canonical README.
-->

<p align="center">
  <img src="assets/readme/vimo-rebinder-icon.png" width="96" height="96" alt="Vimo Rebinder icon">
</p>

<h1 align="center">Vimo Rebinder</h1>

<p align="center">
  <strong>すべてのアプリを、あなたのショートカットの習慣に合わせる。</strong>
</p>

<p align="center">
  Windows と macOS 向けの、ノーコードで使えるアプリ別キーボードワークフローマネージャーです。
</p>

<p align="center">
  <a href="https://github.com/ChenghaoQ/Vimo-Rebinder/releases/latest"><img alt="Latest release" src="https://img.shields.io/github/v/release/ChenghaoQ/Vimo-Rebinder?label=latest%20release"></a>
  <img alt="Windows 10 and 11" src="https://img.shields.io/badge/Windows-10%20%2F%2011-2563eb">
  <img alt="macOS App Store" src="https://img.shields.io/badge/macOS-App%20Store-111827">
</p>

<p align="center">
  <a href="https://github.com/ChenghaoQ/Vimo-Rebinder/releases/latest"><strong>Windows をダウンロード</strong></a>
  ·
  <a href="https://apps.microsoft.com/store/detail/9NVCW6P19QL7">Microsoft Store</a>
  ·
  <a href="https://apps.apple.com/us/app/vimo-rebinder/id6472165219?mt=12">Mac App Store</a>
  ·
  <a href="https://app.vimorebinder.com">公式サイト</a>
  ·
  <a href="https://github.com/ChenghaoQ/Vimo-Rebinder/releases">Releases</a>
</p>

<p align="center">
  <a href="README.md">English</a> ·
  <a href="README_zh.md">简体中文</a> ·
  <strong>日本語</strong> ·
  <a href="README_ko.md">한국어</a> ·
  <a href="README_de.md">Deutsch</a> ·
  <a href="README_fr.md">Français</a> ·
  <a href="README_es.md">Español</a> ·
  <a href="README_pt-BR.md">Português</a> ·
  <a href="README_ru.md">Русский</a>
</p>

<p align="center">
  <img src="assets/readme/vimo-rebinder-hero.png" alt="Vimo Rebinder shortcuts manager with the headline Every Shortcut at Your Fingertips">
  <br>
  <em>ひとつのショートカット構造を、その時アクティブなアプリに自動で合わせます。</em>
</p>

## アプリごとに、ショートカットの言語は違います。

ブラウザーのタブ、エディター、オフィスソフト、デザインツール、システム操作は、それぞれ独自のショートカット規則を持っています。同じ意図でもアプリごとに別のキー操作になり、覚える負担、手の移動、コンテキストの切り替えが積み重なります。

Vimo Rebinder は、そうしたばらばらのショートカットを構造化されたワークフローにまとめます。新しいキー操作をさらに覚えさせるのではなく、一貫したコマンド層を保ちながら、現在使っているアプリに合わせてショートカットを送ります。

Vimo はショートカットを増やすのではなく、使う負担を減らします。

## Before / After

| Vimo なし | Vimo あり |
| --- | --- |
| アプリごとに異なるショートカット | 一貫した個人ワークフロー |
| 押しにくい複数キーの組み合わせ | 覚えやすい構造化されたキー列 |
| バラバラのキー操作を個別に暗記 | 機能別グループと空間配置 |
| スクリプトを書いて保守する | 見える化されたノーコード設定 |
| 毎回ゼロから環境を作り直す | 使い回せるプリセットとアプリ別プロファイル |

## 単なるキーリマッパーではありません

従来のキーリマッパーは、どのキーが何を出すかを変えます。自動化やスクリプトツールは、コンピューターにできることを広げますが、その分セットアップや保守の手間も増えます。

Vimo が扱うのは別の層です。ショートカットを使うときの記憶負荷、移動負荷、衝突、コンテキスト切り替えの負担を下げます。AutoHotkey、PowerToys、Karabiner-Elements などと一部で重なる場面はありますが、完全な置き換えではなく補完を意図しています。

## Vimo の動き方を見る

| ワークフロー | 例 |
| --- | --- |
| ブラウザーとエディターのタブ | 切り替え、閉じる、再び開く、移動を同じ構造にまとめます。 |
| ウィンドウとデスクトップの操作 | ウィンドウ操作、デスクトップ移動、繰り返し動作を、手が覚えた位置に置きます。 |
| アプリ専用の作業 | 各アプリに独自のショートカットを割り当てつつ、同じ Vimo の操作習慣は保てます。 |

## コアシステム

| 機能 | 実際の意味 |
| --- | --- |
| アプリ別プロファイル | 同じ個人ワークフローをアプリ間で使い回し、Vimo がアクティブなアプリに合うショートカットを送ります。 |
| Super Key | 選んだキーを押すかタップして Vimo のコマンド層に入り、離すと通常入力に戻ります。 |
| 機能グループ | ウィンドウ、タブ、デスクトップ、編集、ナビゲーションなどの関連操作をまとめます。 |
| 空間キーゾーン | ウィンドウ操作は W、デスクトップ操作は D の周りに置き、関連コマンドはグループキーの近くに集めます。 |
| ビジュアルヒント | すべてを覚えなくても、次に使える操作をその場で確認できます。 |
| プリセットと分析 | 用意されたレイアウトから始めて、一定期間のショートカット利用を見直せます。 |

<p align="center">
  <img src="assets/readme/key-zones.png" alt="Vimo Rebinder keyboard layout showing Superkey, text shortcuts, arrow keys, repeat action, and extension zones">
</p>

<p align="center">
  <img src="assets/readme/grouping-shortcuts.png" alt="Vimo Rebinder shortcut grouping example showing complex shortcuts simplified into Superkey sequences">
</p>

<p align="center">
  <img src="assets/readme/key-hints.png" alt="Vimo Rebinder key hints showing available commands after pressing Superkey">
</p>

## 3 ステップで開始

1. Vimo Rebinder をインストールします。
2. グローバルなワークフローを選ぶか、アプリを選択します。
3. 自分に自然なショートカット構造へ操作を割り当てます。

レイアウトを覚える間は、浮動ヒントを使えば十分です。スクリプトは不要で、すべてのショートカットは調整または削除できます。

## Free と Pro

| 機能 | Free | Pro |
| --- | --- | --- |
| 無制限のグローバルショートカット | ✓ | ✓ |
| タブの矢印ナビゲーション | ✓ | ✓ |
| システムショートカットのプリセット | ✓ | ✓ |
| アプリ別プロファイル | — | ✓ |
| 完全なプリセットライブラリ | — | ✓ |
| アプリ間でショートカットを移動または複製 | — | ✓ |
| 最大 3 台のデバイスで利用 | — | ✓ |

現在のプランと価格は、[pricing page](https://app.vimorebinder.com/pricing/) をご覧ください。

## ダウンロード

| プラットフォーム | 入口 | 補足 |
| --- | --- | --- |
| Windows 10 / 11 | [Latest GitHub Release](https://github.com/ChenghaoQ/Vimo-Rebinder/releases/latest) | Windows インストーラーは GitHub Releases で配布されます。 |
| Windows 10 / 11 | [Microsoft Store](https://apps.microsoft.com/store/detail/9NVCW6P19QL7) | ストアでのインストール、更新、購入管理に対応します。 |
| macOS 13.0+ | [Mac App Store](https://apps.apple.com/us/app/vimo-rebinder/id6472165219?mt=12) | macOS は App Store で配布され、GitHub Release アセットではありません。 |

## Windows のインストールとプライバシー

直接配布される Windows インストーラーは、公式 [Vimo Rebinder GitHub Releases](https://github.com/ChenghaoQ/Vimo-Rebinder/releases/latest) から入手できます。

このインストーラーは Vimo の自己署名の発行者証明書を使います。初回インストール時に、Windows が証明書のインポートを求める場合があります。Microsoft Store 版ではこの手順は不要です。

ショートカット設定はローカルに保存されます。Vimo がキーボードショートカットと現在のアクティブアプリを確認するのは、ワークフロー機能が有効な間だけです。

詳細は [Privacy Policy](https://app.vimorebinder.com/docs/privacy-policy/)、[Windows Installation Guide](docs/windows-installation.md)、[Privacy and Data Notes](docs/privacy-and-data.md) をご覧ください。

## プラットフォームと言語

- Windows 10 / 11
- Windows インストーラー: x64
- macOS 13 以降
- English、简体中文、日本語、한국어、Français、Deutsch、Español、Português、Русский

## FAQ

### Vimo Rebinder はキーリマッパーですか？

ショートカットワークフローの再割り当てはできますが、主な目的はそれだけではありません。アプリ別のショートカット構造、視覚的なヒント、プリセット、そして一貫したコマンド層が中心です。

### AutoHotkey、PowerToys、Karabiner-Elements、スクリプトツールの代わりになりますか？

いいえ。これらのツールは多くの自動化やリマップ用途にとても有用です。Vimo はノーコードのショートカットワークフロー管理に集中しており、役割が衝突しない範囲で併用できます。

### GitHub は macOS のダウンロードを提供しますか？

いいえ。GitHub Release アセットは Windows インストーラーのみを公開します。macOS ユーザーは [Mac App Store](https://apps.apple.com/us/app/vimo-rebinder/id6472165219?mt=12) を利用してください。

### 公式 Vimo 購入と Microsoft Store 購入は互換ですか？

いいえ。製品機能は同等ですが、購入記録とライセンスの復元方法は別管理です。

### なぜ Vimo にはキーボードアクセスが必要なのですか？

Super Key、アプリ別ワークフロー、フローティングヒント、再割り当て後のショートカット実行には、キーボードイベントの処理が必要です。必要ないときは Vimo を無効にしてください。

## サポート

- [GitHub Issues](https://github.com/ChenghaoQ/Vimo-Rebinder/issues): バグ、インストール問題、再現可能な不具合の報告先です。
- [GitHub Releases](https://github.com/ChenghaoQ/Vimo-Rebinder/releases): Windows の配布アセットとリリース履歴を確認できます。
- [Official Website](https://app.vimorebinder.com): 製品ページ、価格、ポリシーへのリンクがあります。
- Email: [vimo_rebinder@outlook.com](mailto:vimo_rebinder@outlook.com)

## プロプライエタリソフトウェア

Vimo Rebinder はプロプライエタリソフトウェアです。このリポジトリは Vimo Rebinder の公開製品および配布入口であり、オープンソースのライセンス付与そのものではありません。
