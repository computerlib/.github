# .github

`computerlib` org の**既定ファイル**を置くリポ。ここに置いたファイルは、org のどのリポからも「自前を持っていなければ」既定として使われる（[公式](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file)）。

## 置いてあるもの

| ファイル | 効き方 |
|---|---|
| `pull_request_template.md` | org の全リポで PR 作成時に出る雛形。自前の `.github/pull_request_template.md` を持つリポはそちらが勝つ |
| `profile/README.md` | 公開の org プロフィールページ（https://github.com/computerlib ）に出る |

## 気をつけること

- **このリポは公開**。置いたものは誰でも読める。顧客名・案件の事情・内部の判断は書かない
- **既定が効くにはこのリポが公開である必要がある**。private にすると既定として配られなくなる
- 自前を持つリポはそちらが勝つ。既定に寄せたいなら、各リポの自前を消す

## 関連

PR／CI の運用は handbook の `dev/github-flow.md` が SSOT。ここは置き場であって、規約の本文は持たない。
