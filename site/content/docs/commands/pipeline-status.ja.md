# pipeline status
```bash
$ copilot pipeline status [flags]
```

## コマンドの概要
`copilot pipeline status` では、デプロイされた Pipeline のステージの状態を表示します。

## フラグ
```bash
-a, --app string    Name of the application.
-h, --help          help for status
    --json          Optional. Outputs in JSON format.
-n, --name string   Name of the pipeline.
```

## 実行例
Pipeline "my-repo-my-branch" の状態を表示します。
```bash
$ copilot pipeline status -n my-repo-my-branch
```

## 出力例

![Running copilot pipeline status](https://raw.githubusercontent.com/kohidave/copilot-demos/master/pipeline-status.svg?sanitize=true)
