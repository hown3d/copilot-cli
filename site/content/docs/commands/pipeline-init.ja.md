# pipeline init
```bash
$ copilot pipeline init [flags]
```

## コマンドの概要
`copilot pipeline init` は、ワークスペース内の全ての Service をデプロイする Pipeline 用の Manifest を作成します。この Manifest では Application に関連づけられた Environment がデプロイターゲットとなります。

## フラグ
```bash
-a, --app string             Name of the application.
-e, --environments strings   Environments to add to the pipeline.
-b, --git-branch string      Branch used to trigger your pipeline.
-h, --help                   help for init
-n, --name string            Name of the pipeline.
-u, --url string             The repository URL to trigger your pipeline.
```

## 実行例
ワークスペース内の全ての Service をデプロイする Pipeline 用の Manifest を作成します。
```bash
$ copilot pipeline init \
--name frontend-main \
--url https://github.com/gitHubUserName/frontend.git \
--git-branch main \
--environments "test,prod" 
```
