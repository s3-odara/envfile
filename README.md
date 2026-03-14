# envfile

`env/` には shell で `source` できる断片を置きます。

例:

```sh
export CONTEXT7_API_KEY='...'
```

`files/` にはホームディレクトリ相対で展開したいファイルを置きます。

例:

```text
files/.codex/auth.json
files/.config/gh/hosts.yml
```

展開時は `files/.codex/auth.json` -> `~/.codex/auth.json` のようにコピーされます。
