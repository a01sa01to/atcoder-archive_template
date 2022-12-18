# atcoder-archive_template

<details open>

<summary>English</summary>

## What is this?

This is a template repository for AtCoder Archive.
It saves submissions of AtCoder to local directory.

Just press the button `Use this template` and create your own repository.

## Todo

- [ ] Change the reviewers and assignees to your GitHub ID (`.github/dependabot.yml`: Line 10, 12, 25, 27)
- [ ] Change the crawl time (`.github/workflows/crawl.yml`: Line 6)<br>Recommend: The time when you don't submit to AtCoder
- [ ] Add GPG **secret** key to your repository if you want to sign the commit<br>Please name the key `GPG_PRIVATE_KEY` and the passphrase `PASSPHRASE` (`.github/workflows/crawl.yml`: Line 33, 34)
- [ ] If you don't want to sign the commit, remove the lines 30-36 of `.github/workflows/crawl.yml` and the lines 27-33 of `.github/workflows/crawl_all.yml`
- [ ] Change the API Query to your AtCoder ID (`_src/fetch.py`: Line 10, 19)
- [ ] Enable GitHub Actions in your repository settings

## Disclaimer

This repository is not affiliated with AtCoder.
I am not responsible for any damage caused by this repository.

</details>

<details>

<summary>日本語</summary>

## これは何？

AtCoderの提出をローカルに保存するためのテンプレートリポジトリ。

`Use this template`ボタンを押して、自分のリポジトリを作成してください。

## やること

- [ ] レビュアーやアサイン先を自分のGitHub IDに変更する（`.github/dependabot.yml`: Line 10, 12, 25, 27）
- [ ] クロールの時間を変更する（`.github/workflows/crawl.yml`: Line 6）<br>おすすめ: 普段AtCoderに提出しない時間
- [ ] もしコミットに署名をしたい場合は、GPGの **秘密鍵** をリポジトリに追加する<br>鍵は`GPG_PRIVATE_KEY`、パスフレーズは`PASSPHRASE`としてください（`.github/workflows/crawl.yml`: Line 33, 34）
- [ ] もし署名をしない場合は、`.github/workflows/crawl.yml`の30-36行目と`.github/workflows/crawl_all.yml`の27-33行目を削除する
- [ ] APIのクエリを自分のAtCoder IDに変更する（`_src/fetch.py`: Line 10, 19）
- [ ] リポジトリの設定でGitHub Actionsを有効にする

## 免責事項

このリポジトリにはAtCoder社は関わっていません。
このリポジトリによって生じた、いかなる損害についても、私は責任を負いません。

</details>

## License

MIT License, made by [a01sa01to](https://github.com/a01sa01to)

## Reference

- [AtCoder Problems API](https://github.com/kenkoooo/AtCoderProblems/blob/master/doc/api.md) (Using this API)
- [atcoder-dumper](https://github.com/yu7400ki/atcoder-dumper) (Created based on this)
