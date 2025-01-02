# marp-client

Marp で作ったプレゼンテーション資料を一元管理しているリポジトリです。  
Cloudflare Pages でホスティングしています。

## Installation

- clone

```bash
$ git clone git@github.com:1zumisawashun/marp-client.git
$ cd marp-client
```

- install

```bash
$ npm install
```

- md ファイルは以下の VSCode 拡張機能を有効にしプレビュー画面で動作確認をする

  - marp-team.marp-vscode

- html ファイルは以下の VSCode 拡張機能を有効にしプレビュー画面で動作確認をする

  - ritwickdey.LiveServer

上記の手順で失敗する場合 [Troubleshoot](#Troubleshoot)を確認してください

## Deprecated

- ローカル開発用 URL を開き動作確認をすることもできますが非推奨です。上記方法で開発を進めてください。

```bash
$ npm run dev
```

http://localhost:8080/

## Troubleshoot

- デプロイプロセスはどうなっている？
  - Cloudflare Pages でホスティングしているため main にマージするとデプロイされます

## その他ドキュメント

See [Marp Configuration Reference](https://marp.app/).  
See [Marpit Configuration Reference](https://marpit.marp.app/).
