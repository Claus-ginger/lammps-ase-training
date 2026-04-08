# LAMMPS・ASE・Python 演習

LAMMPS・ASE・Python を用いた計算材料科学演習の記録・コード・結果をまとめるリポジトリです。

## 概要
このリポジトリでは、以下の流れで原子シミュレーションの基礎を学びます。

- **ASE** による構造生成と前処理
- **LAMMPS** による静的計算・分子動力学計算
- **Python** による解析・可視化
- **OVITO / VMD** による構造確認

## 目的
- 原子シミュレーションの基本的なワークフローを理解する
- 各ツールの役割分担を整理して使えるようにする
- 入力・出力・図・ログを対応付けて記録する
- 結果を再現できる形で残す

## ディレクトリ構成

~~~text
.
├── 00_notes/        # メモ・セットアップ記録・作業ログ
├── 01_structures/   # ASEで生成した構造
├── 02_lammps/       # LAMMPSの入力・出力
├── 03_python/       # 解析・作図用Pythonスクリプト
├── 04_figures/      # 作成した図
├── 05_reports/      # まとめ・考察
├── potentials/      # 使用するポテンシャル
├── README.md
└── .gitignore
~~~

## 使用環境
- Windows + WSL2 + Ubuntu
- Antigravity
- Python 3
- LAMMPS
- ASE
- OVITO / VMD
