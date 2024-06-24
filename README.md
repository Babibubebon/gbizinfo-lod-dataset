# gBizINFO-LOD-Dataset

[![Build dataset](https://github.com/Babibubebon/gbizinfo-lod-dataset/actions/workflows/build.yml/badge.svg)](https://github.com/Babibubebon/gbizinfo-lod-dataset/actions/workflows/build.yml)

[gbizinfo-lod](https://github.com/Babibubebon/gbizinfo-lod) を用いて生成したデータセット公開用リポジトリ

GitHub Actionsを利用して毎週自動生成され、[Releases](https://github.com/Babibubebon/gbizinfo-lod-dataset/releases)からダウンロードできる。

## 生成ファイル

gzip圧縮されたN-Quads形式のRDFデータセット

- 法人基本情報: `hojin.nq.gz`
- 補助金情報: `hojyokin.nq.gz`
- 調達情報: `chotatsu.nq.gz`
- 表彰情報: `hyosho.nq.gz`
- 届出認定情報: `todokede.nq.gz`
- 特許情報: `tokkyo.nq.gz`
- 職場情報: `shokuba.nq.gz`
- 財務情報: `zaimu.nq.gz`

[リリースのファイルサイズ制限](https://docs.github.com/en/repositories/releasing-projects-on-github/about-releases#storage-and-bandwidth-quotas)のため、それぞれファイルサイズが2GiB以上となる場合は `{basename}.part0.nq.gz`, `{basename}.part1.nq.gz` ... のようなファイル名で複数ファイルに分割される。
