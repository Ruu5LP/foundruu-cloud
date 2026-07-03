# foundruu-cloud

[FoundRuu](https://github.com/Ruu5LP/foundruu) のレポート集約リポジトリです。

各プロジェクトから `foundruu cloud push` で送信された `doctor --deep` レポートを
`reports/<project>/` に保存し、push をトリガーに GitHub Pages のダッシュボードを自動ビルドします。

- ダッシュボード: https://ruu5lp.github.io/foundruu-cloud/
- 設計: [foundruu/docs/cloud.md](https://github.com/Ruu5LP/foundruu/blob/main/docs/cloud.md)

## レポートの送り方

```bash
foundruu doctor --deep --report reports
foundruu cloud push
```
