# workshop-2
- テストの画面上部の "Run" ボタンを押下してください。"Console"に結果が出力されます。
- 初回実行はデーモンを起動させるために Shell から "gradle --daemon test" コマンドの実行する。
  （"Run" ボタンからはデーモンを起動できないため...）
- 新しいモジュールを追加した場合は、"Shell"から`gradle test --refresh-dependencies`コマンドを実行してモジュールの更新を行ってください。