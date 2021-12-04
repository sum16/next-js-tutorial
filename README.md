# Next.js のチュートリアル

## pages ディレクトリについて

- Next.js では、ページとは pages ディレクトリに存在するファイルからエクスポートされる React コンポーネント
- ページは ファイル名 に基づいてルーティングに関連づけられる  
  -ファイルへのパスが URL のパスになる
  -pages/index.js は / にルーティングされる  
  -pages/posts/first-post.js は /posts/first-post としてルーティングされる

---

## リンクを貼る

<Link> を用いてリンクを作成する
※Next.js のアプリの外にある外部のページにリンクを貼る必要があるときは、 Link 無しで <a> タグを使う
#className といった属性を加える必要があるときは、 Link タグでなく、a タグに加える
