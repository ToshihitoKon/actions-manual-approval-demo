GitHub Actionsの実行履歴を利用したManual Approvalの例です。

Last deploy: e61b9df20eb81fdabc011ff08984cb69faba2d42

## デプロイ

```
gh workflow run deploy -r main
```

![waiting-approval](docs/waiting-approval.png)

```
gh workflow run approve -r main
 ```

![deploy-approved](docs/deploy-approved.png)
