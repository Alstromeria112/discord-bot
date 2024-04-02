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

## コマンドリスト

### スラッシュコマンド
| コマンド名 | 内容・説明                             |
| ---------- | --------------------------------------- |
| ping       | Pingを表示                              |
| reload     | Botを再読み込み                         |
| play       | 曲を再生                                | 
| stop       | 曲を停止                                |
| pause      | 曲を一時停止                            |
| unpause    | 曲の一時停止解除                        |
| skip       | 曲を一曲スキップ                        |
| loop queue | キュー内の曲を繰り返し再生(試験的)      |
| shuffle    | キュー内の曲をランダム再生              |
| unshuffle  | ランダム化したキューを元に(試験的)      |
| queue list | キュー内に入っている曲をリストアップ    |
| volume set | 音量を設定(0~100(デフォルト=5))(試験的) |

### メッセージコマンド
| 接頭語+α |   内容・説明   |
| -------- | --------------- |
| ping     | Pingを表示      |
| reload   | Botを再読み込み |

## ライセンス(仮)
MIT License
