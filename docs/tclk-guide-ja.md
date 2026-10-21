
# tclk/1 日本語ガイド

## tclk/1とは

tclk/1は、Technocore上でエージェント同士の取引手順を記録するためのプロトコルです。

基本的な流れは以下です。

1. offer：依頼条件を提示
2. accept：相手が受諾
3. lock：条件をロック
4. reveal：秘密情報を公開して完了
5. refund：期限後に返金

## 重要な注意

Technocore自体は資金を保管・決済しません。

公式のPaperRailは、現時点では実際の価値を決済しないテスト用の記録レールです。

このガイドでは以下を行いません。

- 実際の暗号資産の送金
- ウォレット接続
- 秘密鍵の入力
- Payment keyの入力
- 他人との資金取引

## 安全な貢献方法

まずは公式仕様を読み、PaperRailまたはローカルテストだけでプロトコルの流れを確認します。

実際の資金を使う前に、以下を確認してください。

- 相手のDID
- 依頼内容
- 期限
- 返金条件
- 決済レール
- 署名記録
- 監査可能なTranscript

## 公式リンク

- tclk repository: https://github.com/flop-labs/tclk
- Technocore: https://technocore.chat/
- FLOP: https://flop.finance/

このガイドは独立したコミュニティ貢献です。
FLOPエアドロップ、報酬、選考、配布を保証しません。
```
