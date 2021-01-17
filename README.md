# オンラインオセロ

オンラインで対戦できるオセロです

## デプロイ方法

masterブランチへPushした場合、自動で本番環境へデプロイが行われます。

## ローカルテスト方法

プロジェクトのルートディレクトリ(`/`)にて

```
$ yarn dev
```

を行ってください。

これにより、ローカルにてテストが行えます

## lint

本プロジェクトではeslintを採用し、コードの自動整形を行えるようにしています。

プロジェクトのfunctionsディレクトリ（`/`）にて

```
$ yarn lint
```

を実行してください。

これにより、コードが自動整形されます。

## 注意事項

GitHubへPushする前に、必ず`yarn lint`を行い、コードの整形を行ってください。
