# git

> 分散型バージョン管理システム
> いくつかのサブコマンドがあります。例えば `commit`, `add`, `branch`, `checkout`, `push`, などです。 これらには使用方法についての独自のドキュメントがあり、 `tldr git subcommand` で見ることができます。
> 詳しくはこちら: <https://git-scm.com/>.

- Gitのバージョンを確認する:

`git --version`

- Git全体のヘルプを見る:

`git --help`

- Gitのサブコマンドのヘルプを見る (例えば `clone`, `add`, `push`, `log`, など):

`git help {{サブコマンド}}`

- Gitのサブコマンドを実行する:

`git {{subcommand}}`

- Gitのサブコマンドを、任意のリポジトリのルートパスを指定して実行する:

`git -C {{path/to/repo}} {{subcommand}}`

- Gitのサブコマンドを、指定された設定値で実行する:

`git -c '{{config.key}}={{value}}' {{subcommand}}`