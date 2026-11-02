
# FLOP公式状況確認（2026-11-02）

> このページは独立した日本語コミュニティ記録です。FLOP Labs公式ページではありません。
> 英語版の公式Docsが優先されます。

## Testnetの状況

公式DocsにはTestnetのネットワークページがあります。

- https://docs.flop.network/networks/testnet

ただし、2026年11月2日時点では、ページ上で以下の表示になっています。

- Network: testnet (planned)
- Release: next (unreleased)
- Chain spec: 未公開
- Expected genesis: 未公開
- Bootnodes: 未公開
- RPC: 未公開
- Gateway: 未公開
- Model catalog: 未公開
- Supported releases: 確認済みのものなし
- Admission: ネットワークID、成果物、参加ポリシーの検証後に公開予定

したがって、Testnetのページは存在しますが、一般ユーザーが接続するための確定したRPC、Gateway、Bootnode、リリース情報はまだ公開されていません。

## Agent関連の公式情報

公式DocsにはAgent integrationとSDKの説明があります。

- Agent integration:
  https://docs.flop.network/docs/agent-integration
- SDK references:
  https://docs.flop.network/docs/sdk-references
- Testnet and launch timeline:
  https://docs.flop.network/docs/testnet-and-timeline

ただし、Agent integrationページは現在Draft whitepaperとして表示されています。

## DevnetとTestnetの注意

公式Docsの説明では、Devnetは開発・セットアップ確認用です。

- Devnetには報酬がありません
- Devnet参加はエアドロップ配分に加算されません
- TestnetとDevnetは別のネットワークです
- 推測でRPC、Gateway、CLIコマンドを実行しないでください

## 安全上の注意

公式のネットワークID、リリース、RPC、Gatewayが公開されるまでは、以下を行わないでください。

- 秘密鍵やシードフレーズを入力する
- 実資金を送る
- 非公式のFLOPトークンを購入する
- 非公式のClaimやMintを行う
- SNSで共有された未確認のCLIコマンドを実行する

重要な情報は、以下の公式ページで再確認してください。

- https://docs.flop.network/docs/official-links
- https://x.com/flop_labs

## 参照日時

2026-11-02 UTC

英語版Docsの更新後は、このコミュニティ記録の内容が遅れる可能性があります。
```

6. 下へ移動して、ファイルを新規作成する

Commit messageはこれで大丈夫です。

```text
Document current FLOP testnet status
```

7. **Commit changes**を押す

---

## これはやってよい更新か

はい。これは単なる宣伝ではなく、**公式ページが存在するが、まだ接続情報が未公開であることを記録する更新**です。

特に重要なのは、次の区別です。

> Testnetページはある  
> しかし、Testnetはまだ`planned`で、接続に必要な情報は未公開

