<div id="top"></div>

# Discord-Bot

## 準備
Node.jsで使用するパッケージをインストール
```
npm install
```
※package.jsonが存在するディレクトリで実行

## 実行
```
npm start
```

## 設定
`.env.sample`を`.env`に名称変更
```
TOKEN="AAABBBCCC" # BotのToken
CLIENT_ID="1234" # BotのClientID
GUILD_ID="1234" # ログなどの出力先ギルド
CHANNEL_ID="1234" # ログなどの出力先
OWNER_ID="782142078464425995" # BotのOwnerID
MAINTAINERS_ID="1234" # Owner以外実行できないコマンドを実行可能にするUserID
PREFIX="!" # メッセージコマンドを実行する際の接頭語
ICON_URL="https://cdn.discordapp.com/embed/avatars/0.png" # EmbedのiconURLに使用される
POWERED="Powered by Discord Bot" # EmbedのFooterに使用される
SUCCESS="✅ SUCCESS ✅" # SUCCESS時に出力される文字列
ERROR="❌ ERROR ❌" # Error時に出力される文字列
```

## スラッシュコマンド
| コマンド名 | Description |
| ---------- | ----------- |
|    play    | Play music  |
|    stop    | Stop music  |
|    play    | Play music  |
|    stop    | Stop music  |
|    play    | Play music  |
|    stop    | Stop music  |
|    play    | Play music  |
|    stop    | Stop music  |
|    play    | Play music  |
|    stop    | Stop music  |
|    play    | Play music  |
|    stop    | Stop music  |

## メッセージコマンド
| 接頭語+α |      説明       |
|   ping   |   Pingを表示    |
|  reload  | Botを再読み込み |
