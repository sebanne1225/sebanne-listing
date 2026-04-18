# Sebanne VPM Listing

## 概要

この repository は、sebanne の VRChat 向け Unity ツールを VPM / VCC で配布するための listing repo です。

package 本体の repository とは別管理で、GitHub Pages に公開される listing と案内ページを保持しています。今後 package が増えても、この listing repo に追加して配布していく前提です。

## いま入っている package

- `sebanne1225/blendshape-clip-fixer`
- `sebanne1225/sebanne-skinned-mesh-mirror`
- `sebanne1225/animation-clip-start-delay`
- `sebanne1225/avatar-audio-safety-guard`
- `sebanne1225/flipbook-material-generator`
- `sebanne1225/afk-manager`

今後 package を追加した場合も、この repository の listing からまとめて参照できるようにします。

## VCC への追加方法

VCC の `Settings > Packages > Add Repository` から、次の URL を追加してください。

`https://sebanne1225.github.io/sebanne-listing/index.json`

追加後、各 Unity project の package 一覧から利用できます。

## repo 更新について

この repository は listing repo です。package の release 情報をもとに、GitHub Actions で listing を再ビルドし、GitHub Pages に公開します。

現在は `source.json`、README、Pages 用ファイル、workflow 自身の変更でも再ビルドされるようにしてあります。package を追加・更新する場合は、必要に応じて `source.json` を更新してください。

新しい package を追加する場合も、まず `source.json` の `githubRepos` を更新してください。

## ライセンス

この repository には現時点で個別の `LICENSE` ファイルはありません。

掲載している package の利用条件やライセンスは、各 package repository / release の記載を確認してください。
