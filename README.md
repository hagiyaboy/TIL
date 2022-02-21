# TIL
Today I Learned

<!-- Use Github -->
<!-- structure -->
[work tree] -- [index] -- [local repository] -- [remote repository]


<!-- start repository -->
// Githubからワーキングツリー（ローカルの作業スペース）にリポジトリをクローン作成する
// 「pull」はGithubから差分を取得するため、初めは「clone」を使用する
1. git clone https://github.com/hagiyaboy/[repository name].git

~ after work ~

// コミットしたいファイルをインデックスに追加する
2. git add [file name], [file name]....

// インデックス上のファイルをローカルリポジトリにコミットする
3. git commit -m [leave log]

// ローカルリポジトリからリモートリポジトリ（Github）に差分を追加。
// ユーザー名、パスワードを聞かれるがコマンドラインでのサポートが終了しているため、CotEditorに保存済みのTokenを使用して認証する
4. git push origin(?) [branch name]

<!-- etcetra command -->
// ディレクトリを移動する
cd usr/Users/hagi8kaiyote/GWS    //一番親の「GWS」ディレクトリに移動
cd TIL    // フルパスじゃなくても下層のディレクトリに移動できる
cd -    // 1つ前のディレクトリに移動