GitHub Actionsの実行履歴を利用したManual Approvalの例です。

Last deploy: adb31be27131f48ad5e9bf4e8ae2f1dfbccc171f

## デプロイ

```
gh workflow run deploy -r main
```

![waiting-approval](docs/waiting-approval.png)

```
gh workflow run approve -r main
 ```

![deploy-approved](docs/deploy-approved.png)
