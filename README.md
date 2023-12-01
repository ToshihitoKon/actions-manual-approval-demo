GitHub Actionsの実行履歴を利用したManual Approvalの例です。

Last deploy: 06e371769644332754818db3803c85dc8837b43f

## デプロイ

```
gh workflow run deploy -r main
```

![waiting-approval](docs/waiting-approval.png)

```
gh workflow run approve -r main
 ```

![deploy-approved](docs/deploy-approved.png)
