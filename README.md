GitHub Actionsの実行履歴を利用したManual Approvalの例です。

Last deploy: 6a2ed01cebcbc1ebbb899f6dc0ebe40e60f2e5fa

## デプロイ

```
gh workflow run deploy -r main
```

![waiting-approval](docs/waiting-approval.png)

```
gh workflow run approve -r main
 ```

![deploy-approved](docs/deploy-approved.png)
