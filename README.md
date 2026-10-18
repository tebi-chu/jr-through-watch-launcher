# JR直通ウォッチ入口ページ

GitHub Pagesで公開する静的な入口ページ。PCのファビコンとiPhoneのホーム画面用アイコンを、同じ電車正面画像で指定する。運行情報の取得、通知、メール送信は既存の本人限定Google Apps Scriptで実行する。

公開するのは `index.html`、`manifest.webmanifest` と4つのPNGだけ。`index.html` に既存のApps Script URLをリンクとして含むため、このURLは公開される。アプリへのアクセス権はApps Scriptの「自分のみ」のまま維持する。

GitHub Pagesをリポジトリのルートから配信する。公開後はGitHub PagesのURLをPCでブックマークし、iPhoneのSafariから同じURLを「ホーム画面に追加」する。入口ページのボタンで本人限定アプリを開く。
