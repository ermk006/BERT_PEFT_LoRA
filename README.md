# BERT_PEFT_LoRA

## 準備
学習データ（train.csv）と検証データ（valid.csv）を準備します。

ラベルを"text","label"とし、labelを推論するよう学習します。

Google ColabでJapanese_AI_vs_Human_Classifier_Colab.ipynbを開いたら、2つのファイルをアップロードする（図参照）。

<img width="622" height="354" alt="スクリーンショット 2025-08-26 1 27 08" src="https://github.com/user-attachments/assets/e357f2fc-d19a-4bca-8658-27e793cc5b02" />


## プログラムを実行

Google Colabのメニューから「ランタイム」をクリックし「ランタイムのタイプを変更」を選ぶ。「T4 GPU」をクリックして保存する。（これをしないと処理が遅い）

プログラムのセルを上から順番に実行する。

1) セットアップ（インストール）を実行したとき、出力に「CUDA available: True」と表示されることを確認する。もしFalseの場合はGPUが使用できる設定になっていない。
<img width="773" height="440" alt="スクリーンショット 2025-08-26 1 30 53" src="https://github.com/user-attachments/assets/72762f76-ad4f-4c70-9bb9-a844ece4c57b" />



