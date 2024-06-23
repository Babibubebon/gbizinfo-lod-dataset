# gBizINFO-LOD-Dataset

[gbizinfo-lod](https://github.com/Babibubebon/gbizinfo-lod) を用いて生成したデータセット公開用リポジトリ

GitHub Actionsを利用して毎週自動生成され、[Releases](https://github.com/Babibubebon/gbizinfo-lod-dataset/releases)からダウンロードできる。

## 生成ファイル

- 法人基本情報: `hojin.nq.gz`
- 補助金情報: `hojyokin.nq.gz`
- 調達情報: `chotatsu.nq.gz`
- 表彰情報: `hyosho.nq.gz`
- 届出認定情報: `todokede.nq.gz`
- 特許情報: `tokkyo.nq.gz`
- 職場情報: `shokuba.nq.gz`
- 財務情報: `zaimu.nq.gz`

それぞれファイルサイズが2GiB以上となる場合は `{basename}.part0.nq.gz`, `{basename}.part1.nq.gz` ... のようなファイル名で複数ファイルに分割される。
