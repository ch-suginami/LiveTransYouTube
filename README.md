# LiveTransYouTube
DeepLを用いたYouTubeチャット自動翻訳ツール。

# 使い方
自分のYouTube APIをキー`YT_API_KEY_BACK_UP`に、[DeepL API](https://www.deepl.com/home) キー(有料)を`DL_API_KEY`にそれぞれ打ち込んでください。

その後`python3 live_trans.py`によりプログラムを実行します。

`YouTubeLiveアドレスを入力してください。`と聞かれるので、チャット欄を翻訳したい配信ページをコピペしてください。

成功すると取得できた、投稿日時、原文、日本語訳、がそれぞれ表示されます。

APIの仕様により、実行時刻以前の投稿も翻訳される場合があります。

またチャット欄に「ひらがな」あるいは「カタカナ」が含まれる場合は翻訳を実行しません（翻訳料低減のため）。

# 制約
YouTubeのAPI制限にかかるとそこでツールが終了します。

# 作者
Made by 杉並委員長[@ch_suginami](https://twitter.com/ch_suginami) 2020-2021
