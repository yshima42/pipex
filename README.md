# レビュー指摘ポイント
- Makefileにてrmはマクロに設定されているので書く必要はない
- 環境変数のPathがない時に動かない
- envpではなく、extern environを使うべき
- 関数は機能ごとにラッピングをするべき
- ""に値が入っていない時にも動いてしまう
- child1と2は一つの関数で対応できるはず
- childのifの部分はwhileで書いた方が良い