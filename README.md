# ティラノスクリプトメモ

## スクリプトの構成

* 画像の差し替えくらいでほとんどそのまま必要なファイル
    - **tyrano.ks**: 標準関数群
    - **first.ks**: エントリポイント
    - **title.ks**: タイトル画面
    - **make.ks**: セーブデータロード時に呼ばれる特殊なファイル
    - **config.ks**: 設定画面
* 場合によっては必要なファイル
    - **replay.ks**: 回想モード画面
    - **cg.ks**: CG一覧画面
* メインのストーリーファイル
    - **scene1.ks**: メインストーリー

## tyrano.ksに含まれる関数

- **back**: 背景を変更する
- **charaset**: キャラクターの表示・設定を行う
- **chararemove**: 

## メモ

- ``[bg storage="xx.jpg" time=1000]``などの``storage``には、読み込む外部ファイルを与える
- キャラクター関連のタグ
    - ``chara_new``
    - ``chara_show``
    - ``chara_hide``
    - ``chara_face``
    - ``chara_mod``