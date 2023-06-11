# Oysters Podcast
Oysters Podcast は、若手ものづくり集団「Oysters」のPodcastです。所属エンジニアが、技術のことから暮らしのことまで語っていきます。

# podcastを公開したいときは？
- images/members 直下に出演者と編集者の400x400の画像を追加しよう
- _posts 直下にmdファイルを追加しよう（ファイル名は {YYYY-MM-DD}-{第n回のnの番号}）
    - actor/member_ids: 出演者たちのid。_config.ymlのmembers.*が該当
    - editor/member_id: 編集者のid。_config.ymlのmembers.*が該当
    - audio_file_path: 音声ファイルのパス。基本は audio/{第n回のnの番号}.mp3
    - audio_file_size: 音声ファイルサイズ
    - date: 投稿日。過去の日付じゃないと公開されないので注意
    - description: 詳細説明
    - duration: 音声ファイルの時間を入力
    - layout: article でOK
    - title: {第n回のnの番号}. タイトル名 を書こう
- audio/{第n回のnの番号}.mp3 に録音ファイルを置こう

# Special Thanks

## Yattecast
https://r7kamura.github.io/yattecast/
