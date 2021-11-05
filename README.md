# Winget を導入する

## Winget のインストール

### Microsoft Store の起動

Windows キーを押して `microsoft store` で検索。Microsoft Store を起動する。

### 「アプリ インストーラ―」を入手

Microsoft Store で `wiget` と検索。

検索結果から、「アプリ インストーラー」を選択。

「入手」ボタンをクリック。

### インストールできたかの確認

PowerShell を起動。次のコマンドを実行。

``` console
winget -v
```

`実行結果: `
``` console
v1.1.12653
```

## Winget の使い方

Winget は、アプリのインストールなどをスクリプトやバッチで一括して行う用途を想定しているため、コマンドラインで操作を行う。

Winget のコマンド書式は次の通り。

`winget.exe の書式`
``` console
winget ［＜サブコマンド＞］ ［＜サブコマンドオプション＞］
```

Winget は、引数を何も付けずに実行するとオンラインヘルプを表示する。サブコマンドが分からなくなったら、`winget` のみのコマンドを実行すればよい。

### Winget のサブコマンド

|サブコマンド	|説明 |
|:-- |:-- |
|-v／--version	|wingetのバージョンを表示 |
|--info	|wingetの情報を表示 |
|install	|指定されたパッケージをインストール |
|show	|パッケージに関する情報を表示 |
|source	|パッケージのソースの管理 |
|search	|アプリの基本情報を見つけて表示 |
|list	|インストール済みパッケージを表示 |
|upgrade	|指定されたパッケージをアップグレード |
|uninstall	|指定されたパッケージをアンインストール |
|hash	|インストーラーファイルをハッシュするヘルパー |
|validate	|マニフェストファイルを検証 |
|settings	|設定（settings.josnファイル）を開く |
|features	|試験的な機能の状態を表示 |
|export	|インストールされているパッケージのリストをエクスポート |
|import	|ファイル中の全てのパッケージをインストール |



