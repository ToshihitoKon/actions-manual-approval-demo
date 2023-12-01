GitHub Actionsの実行履歴を利用したManual Approvalの例です。

Last deploy: 91de353dd8587a0c8a037d89dfad400a8da13455

## デプロイ

```
gh workflow run deploy -r main
```

![waiting-approval](docs/waiting-approval.png)

```
gh workflow run approve -r main
 ```

![deploy-approved](docs/deploy-approved.png)
