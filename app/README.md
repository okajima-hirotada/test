This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.tsx`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.ts`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

git からプロジェクトを落としたときは npm install をしないと使えない
しないと react コマンドなどが見つからず、サーバを立ち上げることすらできない
npm install の動作について
https://www.codegrid.net/articles/2020-npm-install-1/

prettier のインストールコマンド
npm install --save-dev eslint-config-prettier
npm i -D eslint-config-prettier
上の二つのコマンドは同じ
--save-dev のショートカットが -D 　 install のショートカットが i

prettier や ESlint は vscode に同名の拡張をインストール必要がある

package.json の scripts を使用する場合は
npm run scripts で記述したキー

.vscode フォルダは.git と同じ階層に入れるべき？
→dockerfile などを作成する場合は app と同じ階層に dockerfile が入る
つまり、いずれ docker を使用することを決めたときに app の中に.vscode が入っていると setting が機能しなくなる
しかし、app と同階層に.vscode をおいても閉じていれば、そこまで気になるものではないので、docker を考えているのであれば、同階層で良い！

prettier のコマンドは
npm i -D prettier
で prettier をインストールすれば使用できる
