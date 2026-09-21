# Pawprint Support MM v0.1.0

Pawprint Supportをベースに、マルチモニター環境向けの判定範囲追従を追加した別プラグインです。
通常版とはInternalName・設定保存先・DLL名・コマンドを分離しています。

## MM版の追加点

- PawprintのON/OFF判定範囲をFF14ウィンドウ位置基準で追従。
- FF14を別モニターへ移動した場合や、複数画面をまたいで配置した場合の利用を想定。
- 通常版Pawprint Supportの闘獣練補助機能をベースにしています。

## 主な機能

- Pawprintの自動攻略ボタンのON/OFF状態を画像登録で判定し、必要に応じて自動復帰。
- 2周目以降の選択画面で「闘獣練」を自動選択。
- 戦闘中の「ひきつけろ」補助使用。
- 死亡結果画面の復帰補助。
- テント確認の補助。
- FF14非フォーカス時の背面クリックと必要時のみの一時フォーカス。

## 重要

- マルチモニター環境での実機確認を目的とした独立版です。
- 通常版とMM版を同時に自動実行ONへしないでください。同じPawprint画面を両方が操作するため競合します。
- 初回はMM版側でPawprintの判定範囲・OFF画像・ON画像を登録してください。
- 自動実行OFF時はSupport由来の自動処理を停止します。

## コマンド

`/pawprintsupportmm`

## Repository

https://github.com/elpapityo/PawprintSupportMM
