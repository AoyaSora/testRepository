# testRepository
It is for Github test. 
## 手順 

- リモートリポジトリの作成
  - Newでリポジトリを作成
  - Repository NameとConfigtionを指定
- ローカルリポジトリにコミット
  - /User/ディレクトリ名/github/に`cd ディレクトリ名/github`で移動する
  - そのディレクトリにローカルリポジトリを`mkdir sample`で作成する
  - sampleディレクトリに移動し,`git init`でローカルリポジトリにする
  - sampleディレクトリにファイルを作成する
  - 保存したファイルを`git add ファイル名`でインデックス(一時的の保存する場所)に追加する
  - 追加したファイルを`git commit -m "[Add] index"`
  - `git log`で確認
  - リモートリポジトリにプッシュ
  - ローカルリポジトリとリモートリポジトリを紐づける`git remote add origin https://github.com/ユーザ名/リモートリポジトリ名.git`
  - 紐付け後，`git push origin master`でプッシュを実行する
conflictテスト
