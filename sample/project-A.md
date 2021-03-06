# Doneの定義サンプル（プロジェクトAの場合）

## Done

### 通常スプリント

* 各ストーリーチケットに記載の完了条件を満たしている。
* 全てのバグが解決しているか、対応時期を決めて課題チケットに載せている。
(Undoneとなり得そうなものは、まず課題チケットに載せること。）
* コードレビューを通過している。

＜コードレビューの観点（一部抜粋）＞

|観点|説明|
|:-- |:-- |
|業務要件を満たしていること<br>(実際に動かす)|チケットに記載の完了条件を満たしていること。（＝外部設計書の該当項目の記載内容を満たすこと）<br>業務QAで未解決の照会がないこと。|
|コード規約を満たしていること|ESListの静的チェックエラーがでないこと。（対応有無の切り分けは実施する。）<br>wikiコーディング規約を満たすこと。|
|タスクの積み残しがないこと|不要なTODO、FIXMEは残さない。|
|コメントが適切であること|処理に即した内容が書かれているか。<br>判定内容等は、逆または異なることを書いていないか。|
|可用性を考慮できていること|第三者にわかりやすく、かつ見せても恥ずかしくない成果物となっているか。|
|不要なループ処理がないこと|不要なループ処理が入っていないか。<br>静的要件が明確でない場合でも、性能への意識は大切。<br>無駄な処理は書かない。|

### テストスプリント

* 全てのコードがdevelopブランチにマージされている。
* 全ての単体テストケースの合格条件を満たしている
* ケースに紐づくエビデンスが取得できている
