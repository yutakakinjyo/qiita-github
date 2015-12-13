この記事は[Git Advent Calendar 2015](http://qiita.com/advent-calendar/2015/git)の16日目の記事です。

# GitHub, Git の普及ノウハウ記事

この記事を読むと、GitHub と Git を人に紹介する時、導入後のノウハウ、普及時のメンタルヘルスについて知識が得られます。
これから現場に GitHub を普及させたい方に有用な記事かもしれません。
技術的な Tips は少なめです。

# GitHub について人に伝えるポイント

どうも、[GitHub おじさん](http://www.slideshare.net/yutakakinjyo/github-36864200)、または [一度死んだおじさん](http://www.slideshare.net/yutakakinjyo/hackerscample-lt-49900119) こと沖縄の金城です。「GitHub とは何か?」と人に説明する機会が多いので、その経験から、伝え方のノウハウが少し溜まってるので書いています。

**技術紹介編**
- Git はバージョン管理ツール、 GitHub は Git のホスティングサービス
- Git には worktree, index, repository の３つの領域がある
- ブランチは並行世界(世界線)
- PullRequest は変更のバッファ
- GitHub Flow がわかりやすい

**導入後 Tips 編**
- 難しい運用をしない
- diff にコメントできる
- 画像がドラッグアンドドロップで貼れる
- コミットは細かく、メッセージは詳しく理由を、Pull Request は短く
- push -f 禁止、分からなくなっても clone し直さない
- 変更をコミットしないとブランチを異動した時持ち越す
- 「fix」, 「修正」文言はコミットメッセージに使わない

**「おじさん」編**
- 「おじさん」になるには名乗るだけ。中身は後からついてくる
- 「これが出来てから」ではなくてさっさと全部やる



