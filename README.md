# アプリケーションの概要
- 音声アプリケーションによって、APIによる応答のほか、追加機能として天気予報の表示やサイコロの機能などを実装した。

# 使⽤⽅法
- 「Start」をクリックしてマイクの認識を開始。
- 「おはよう」「こんにちは」などの声をかけると、効果音が鳴り、AIによる対話が開始される。
-  Yahoo!の自然言語理解APIによって、あいさつや、「歌って」などの対話に対応。
- 「○○（都道府県）の天気」のように声をかけると、weathernewsと連携してその地点の天気予報を表示。
 - 「今日の天気」「明日の天気」などについては、現在地の天気を表示するよう設定。(今回は現在地を和歌山に固定した)
- 「さいころ」や「コイントス」、「占い」、「ビンゴ」といった機能を乱数によって対応し、声をかけることでそれに応じた数字や結果が出力される。
# ⼯夫した点
- HTMLのiframe属性を用いて、天気予報のページを直接出力するようにした点。
- 「さいころ」や「占い」といったオリジナルの機能を実装した点。
- CSSによって、画面をメッセージアプリのようにデザインした点。
