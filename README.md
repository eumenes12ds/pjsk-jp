# pjsk-jp

『プロジェクトセカイ カラフルステージ！ feat. 初音ミク』を題材にした **SillyTavern 用キャラクターカード（日本語版）** です。

## 収録内容

| 種別 | ファイル | 説明 |
| --- | --- | --- |
| キャラクターカード | `characters/pjsk-jp.png` | 初音ミクたち Virtual Singer と各ユニットのメンバーが登場するロールプレイカード（MVU ステータスバー対応） |
| ワールドブック | `worlds/pjsk-jp.json` | 世界観・キャラクター設定・イベント（421 エントリ）の日本語版 |
| プリセット | `OpenAI Settings/Oneself-jp.json` | 「明月秋青」系プリセットの日本語版（執筆スタイル・思考連鎖・各種スイッチ類） |

## 使い方

1. SillyTavern を開き、`characters/pjsk-jp.png` をインポートします。
2. ワールドブック `worlds/pjsk-jp.json` をインポートします（カードの `extensions.world` は `pjsk-jp` を参照）。
3. `OpenAI Settings/Oneself-jp.json` をプリセットとして読み込みます。
4. カードの MVU ステータスバー（`<UpdateVariable>` タグを置換）と Tavern Helper スクリプトを有効にすると、時間・場面・好感度・内心などの状態表示が動作します。

> 出力言語は日本語です。生成モデルに合わせて「Oneself-jp」プリセット内の `output_language` 変数は `日本語` に設定されています。

## クレジット

- 本カードは中国語版カード「【pjsk】初音未来 缤纷舞台」（作者: ct-org）を日本語向けにローカライズした派生版です。
- プリセット「Oneself-jp」は中国語版プリセット「明月秋青by oneself」（作者: 三明月）を日本語向けにローカライズした派生版です。
- プロジェクトセカイ関連の版権は セガ／Colorful Palette／Crypton Future Media 等の各権利者に帰属します。非公式のファンメイドコンテンツです。

## 注意

- 本リポジトリは非公式のファンメイド作品であり、株式会社セガ／Colorful Palette 等とは一切関係ありません。