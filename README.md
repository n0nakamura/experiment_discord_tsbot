# tsbot

tsbotはDiscordのBotの試作です。サードパーティライブラリ [Discord.js](https://github.com/discordjs/discord.js) を利用しています。プログラミング言語はTypeScriptです。

次のように実行します。

```shell
docker build . -t tsbot-image
docker run --rm --name tsbot tsbot-image
```

## 参考文献

### Docker

- [Dockerで、Next.js,TypeScript環境構築方法](https://zenn.dev/tasuya/articles/da033574b85e6d)
- [Node.js Web アプリケーションを Docker 化する ｜ Node.js](https://nodejs.org/ja/docs/guides/nodejs-docker-webapp)

### TypeScript

- [TypeScript + Node.js プロジェクトのはじめかた2020 - Qiita](https://qiita.com/notakaos/items/3bbd2293e2ff286d9f49)
