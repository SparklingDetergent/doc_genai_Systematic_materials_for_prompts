# doc_genai_Systematic_materials_for_prompts
プロンプトの体系的な資料

  - このリポジトリは、生成AIを活用するためのプロンプトに関する知識を体系的にまとめたものです。
  - プロンプトを上手に使いこなすためのヒントや注意点を提供し、実践的に役立つ情報を提供します。
  - **参考資料として、当リポジトリの TEMPLATE01.MD～、ご参考ください。（このページで紹介したプロンプトを基に作成した、具体的なプロンプトテンプレートを示した資料です）**
  - **参考資料として、当リポジトリの SAMPLE01.MD～、ご参考ください。（複数の生成AIとの会話履歴を基に作成した、具体的なプロンプトを示した資料です）**

## 生成AIプロンプトの特徴
生成AIに対するプロンプトは、プログラミング言語におけるIf 構文や For 構文と同様、部品を組み合わせて機能します。この資料では、それぞれの部品について詳しく説明しています。実際にプロンプトを使用する際には、これらの部品を効果的に組み合わせることで、より精度高く意図した結果を得ることができます。

プロンプトの「部品」とは、例えば以下のような要素です：
- **命令**：生成AIに何をして欲しいかを指示します。
- **コンテキスト**：生成AIが理解するための背景情報を提供します。
- **条件**：生成AIが処理を行う際の制約や条件を指定します。
- **結果のフォーマット**：生成されるアウトプットの形式を指定します。

これらの部品を組み合わせることで、生成AIに対して精度高く指示を出すことができます。実践的なプロンプトを作成する際には、これらの部品を柔軟に組み合わせ、意図した結果を導き出すことが重要です。

## 利用方法
このリポジトリに含まれているプロンプトのテンプレートや使用例を参照し、生成AIとの対話を効果的に構築するための参考にしてください。各テンプレートには以下の情報が含まれています：
- **プロンプトの概要**：そのプロンプトの目的や使用方法について簡潔に説明します。
- **プロンプトテンプレート**：実際に使用可能なプロンプトの例を提供します。
- **生成結果**：プロンプトを使用した場合に得られる出力結果の例を示します。
- **注意点**：プロンプト使用時に気をつけるべきポイントや、失敗しないためのコツを記載します。

## 注意点
生成AIのプロンプトは非常に強力ですが、その効果を最大化するためには注意深い設計が必要です。特に以下の点に留意することをお勧めします：
- **具体性**：プロンプトがあまりにも抽象的だと、生成AIが適切に意図を理解できない場合があります。可能な限り具体的で明確な指示を与えましょう。
- **コンテキストの提供**：生成AIはコンテキストを重要視します。関連する背景情報や前提条件を十分に提供することで、結果の精度が向上します。
- **フィードバックの反映**：生成AIとの対話を通じて結果を修正し、再試行することでより良い結果を得ることができます。プロンプトの微調整は効果的です。


この資料を元に、生成AIを最大限に活用するためのスキルを高めていってください。

---

## プロンプトの種類（参考）表形式

**1. プロンプトの基本構造と種類:**

|中分類 * 小分類|説明|例|
|-----|-----|-----|
|**一言プロンプト:**|簡潔な言葉で指示や質問を行うプロンプト。|「東京の天気は？」|
|**構造化プロンプト:**|特定のフォーマットに従って情報を提供するプロンプト。||
|  * XML/HTMLタグ形式:|XMLまたはHTMLタグを使用して構造化されたプロンプト。|章末参照|
|  * JSONスキーマ形式:|JSONスキーマに従ってデータ構造を定義するプロンプト。|章末参照|
|  * マークダウン形式:|マークダウン記法を使用して構造化されたプロンプト。|章末参照|
|  * YAML形式:|YAML形式を使用して構造化されたプロンプト。|章末参照|
|**キーワードプロンプト:**|関連するキーワードを列挙して指示するプロンプト。|「猫、かわいい、写真」|
|**質問プロンプト:**|質問形式で情報を求めるプロンプト。|「日本の首都はどこですか？」|
|**文章プロンプト:**|文章でタスクや指示を与えるプロンプト。|「猫の生態について説明する文章を書いてください。」|
|**指示型プロンプト:**|直接的な指示を与えるプロンプト。|「1から10まで数えてください。」|
|**例示型プロンプト:**|例題を示して、同様のタスクを指示するプロンプト。|「英語：Hello, how are you?  日本語：こんにちは、元気ですか？  上記を参考に、次の英文を翻訳してください：Good morning.」|
|**コンテキストプロンプト:**|背景情報や文脈を提供するプロンプト。|「19世紀の産業革命について説明し、その影響を論じてください。特にイギリスの綿工業の発展に焦点を当ててください。」|
|**カスタマイズプロンプト:**|特定のニーズに合わせて調整されたプロンプト。|「ビジネスレポート風で、企業の成長戦略についてのレポートを作成してください。」|
|**クリエイティブプロンプト:**|創造性を促すプロンプト。|「不思議な力を操る猫の物語を書いてください。その猫の名前はミケで、魔法の帽子をかぶっています。」|
|**シーケンスプロンプト:**|順序付けられた複数の指示を与えるプロンプト。|「1. パスタのレシピを教えてください 2. 材料のリストを表示してください 3. 調理方法を詳しく説明してください」|



**2. プロンプトの機能と用途:**

|中分類 * 小分類|説明|例|
|-----|-----|-----|
|**テンプレート型プロンプト:**|事前に定義されたテンプレートを用いるプロンプト。||
|  * フォーマット指定型:|出力形式を指定するテンプレート型プロンプト。出力形式を指定するテンプレート型プロンプト。XML/HTMLタグ形式, JSONスキーマ形式, マークダウン形式, YAML形式, など様々な形式を指定。|日付をYYYY-MM-DD形式で出力するよう指示する。「日付をYYYY-MM-DD形式で出力してください。」|
|  * 変数置換型:|変数を埋め込むことで動的にプロンプトを生成するテンプレート型プロンプト。|「{名前}さんは{年齢}歳です。{出身地}出身です。」  (名前、年齢、出身地に値を代入して使用)|
|  * スロット埋め込み型:|空欄を埋めさせることでプロンプトを完成させるテンプレート型プロンプト。|「次の式の空欄を埋めるための計算式をpowershellで記述してください。3+4*____/5=6」|
|**タスク実行プロンプト:**|特定のタスクを実行させるプロンプト。||
|  * 文章生成:|文章を作成させるプロンプト。|「以下の要件で記事を作成してください：（要件）」|
|  * コード生成:|プログラムコードを生成させるプロンプト。|「以下の要件でプログラムコードを作成してください：（要件）」|
|  * データ分析:|データ分析を実行させるプロンプト。|「このデータセットを分析し、重要な傾向を特定してください。（データセット）」|
|  * 翻訳:|文章を翻訳させるプロンプト。|「英語の文章を日本語に翻訳してください：The quick brown fox jumps over the lazy dog.」|
|  * 要約:|文章を要約させるプロンプト。|「この論文を簡潔に要約してください。(論文本文をここに挿入)」|
|  * 質問応答:|質問に答えるプロンプト。|「光合成とは何ですか？」|
|**システム制御プロンプト:**|AIの動作を制御するプロンプト。||
|  * ペルソナ設定:|AIの性格や役割を設定するプロンプト。|「あなたは以下の特徴を持つAIアシスタントとして応答してください：」|
|  * 出力フォーマット指定:|出力形式を指定するプロンプト。|「箇条書きで答えてください。」|
|  * 制約条件設定:|出力内容に制約を与えるプロンプト。|「100文字以内で答えてください。」|
|  * エラーハンドリング指定:|エラー発生時の処理を指定するプロンプト。|「データが不足している場合は、「データ不足です」と出力してください。」|
|**対話型プロンプト:**|対話形式のプロンプト。|チャットボットとの会話。「こんにちは。今日の予定を教えてください。」|
|**生成型プロンプト:**|新しいコンテンツを生成させるプロンプト。|「サーバーダウン時の迅速な対応方法を提案してください。」|
|**翻訳プロンプト:**|言語翻訳を依頼するプロンプト。|「フランス語を日本語に翻訳してください。」|
|**要約プロンプト:**|文章の要約を依頼するプロンプト。|「このニュース記事を要約してください。(ニュース記事本文をここに挿入)」|
|**コード生成プロンプト:**|プログラムコードの生成を依頼するプロンプト。|「JavaScriptで、ユーザーの入力に応じて「Hello, {ユーザー名}!」と表示するプログラムを書いてください。」|
|**クリエイティブライティングプロンプト:**|小説や詩などの創作を依頼するプロンプト。|「孤独な宇宙飛行士が、未知の惑星で遭遇する不思議な生き物について、SF短編小説を書いてください。」|
|**質問応答型プロンプト:**|質問に答えることを目的としたプロンプト。|「日本の歴史における重要な出来事を5つ挙げてください。」|
|**シナリオベースプロンプト:**|特定の状況を設定して指示するプロンプト。|「あなたは医者です。患者が頭痛を訴えています。どのような診察をしますか？」|


**3. 学習方法に基づくプロンプト:**

|中分類 * 小分類|説明|例|
|-----|-----|-----|
|**Zero-Shot学習プロンプト:**|事前に学習データを与えずにタスクを実行するプロンプト。||
|  * 直接指示型:|直接的にタスクを指示するZero-Shotプロンプト。|「1から10まで数えてください。」|
|  * 説明要求型:|タスクの説明を求めるZero-Shotプロンプト。|「素数とは何か説明してください。」|
|  * タスク定義型:|タスクを定義するZero-Shotプロンプト。|「与えられた文章の感情を分析し、ポジティブ、ネガティブ、ニュートラルのいずれかに分類してください。」|
|**Few-Shot学習プロンプト:**|少数の学習データを与えてタスクを実行するプロンプト。||
|  * 例示学習型:|いくつかの例を示してタスクを指示するFew-Shotプロンプト。|「英語を日本語に翻訳してください。例：Hello -> こんにちは,  Goodbye -> さようなら。  Then ->  それから」|
|  * パターンマッチング型:|パターンを学習させてタスクを実行するFew-Shotプロンプト。|「日付をYYYY-MM-DD形式に変換してください。例：2024年3月8日 -> 2024-03-08, 2023/12/25 -> 2023-12-25」|
|  * アナロジー型:|類推を用いてタスクを実行するFew-Shotプロンプト。|「猫は犬と同様に哺乳類です。では、鳥は？ 」|
|**Chain-of-Thoughtプロンプト:**|思考過程を明示的に記述してタスクを実行するプロンプト。||
|  * 思考過程明示型:|思考過程を段階的に記述するChain-of-Thoughtプロンプト。|「質問：東京から大阪までの新幹線でかかる時間は？ 思考過程：東京から大阪までは約500キロメートル。新幹線は時速約300キロメートルで走行する。500キロメートル ÷ 300キロメートル/時 ＝ 約1.6時間。答え：約1.6時間」|
|  * ステップバイステップ型:|ステップごとに指示を行うChain-of-Thoughtプロンプト。|「問題：1 + 2 * 3 = ? ステップ1: まず掛け算を行う。ステップ2: 2 * 3 = 6。ステップ3: 1 + 6 = 7。答え：7」|
|  * 論理展開型:|論理的な推論に基づいてタスクを実行するChain-of-Thoughtプロンプト。|「すべての犬は哺乳類です。ポチは犬です。したがって、ポチは哺乳類です。」|


**4. プロンプトの高度なテクニック:**

|中分類 * 小分類|説明|例|
|-----|-----|-----|
|**ロールプレイプロンプト:**|特定の役割を演じさせるプロンプト。||
|  * エキスパート設定:|専門家の役割を演じさせるロールプレイプロンプト。|「あなたは、気象学の専門家です。来週の日本の天気予報を詳細に説明してください。」|
|  * シナリオベース:|特定の状況を設定したロールプレイプロンプト。|「あなたは、宇宙船の船長です。酸素が不足し始めています。どうしますか？」|
|  * マルチペルソナ:|複数の役割を同時に演じさせるロールプレイプロンプト。|「あなたは、探偵と容疑者の二人を演じてください。探偵は容疑者に事件について質問し、容疑者は嘘をつきながら答えます。」|
|**制約付きプロンプト:**|出力内容に制約を加えるプロンプト。|「100文字以内で、今日の出来事を要約してください。」|
|**逐次プロンプト:**|順次的に指示を与えるプロンプト。|「まず、タイトルを考えてください。次に、概要を書いてください。最後に、本文を書いてください。」|
|**システム指示型プロンプト:**|システムレベルの指示を与えるプロンプト。|「エラーが発生した場合は、エラーメッセージとエラーコードを出力してください。」|
|**段階的指示プロンプト:**|段階的に指示を与えるプロンプト。|「ステップ1：材料を準備する。ステップ2：材料を混ぜる。ステップ3：オーブンで焼く。」|
|**再帰型プロンプト:**|自身が出力した内容を再入力として利用するプロンプト。(複雑で説明が難しいので、例は省略)|
|**デバッグプロンプト:**|エラーを発見・修正するためのプロンプト。|「このコードにエラーがあります。エラーを発見し、修正してください。(コードをここに挿入)」|
|**メタプロンプト:**|プロンプトを生成するためのプロンプト。||
|  * プロンプト生成プロンプト:|別のプロンプトを生成させるメタプロンプト。|「短編小説を書くためのプロンプトを5つ生成してください。テーマは「猫」です。」|
|  * 自己改善型プロンプト:|自身の性能を改善するためのメタプロンプト。(複雑で説明が難しいので、例は省略)|
|  * フィードバック統合型:|フィードバックを統合してプロンプトを改善するメタプロンプト。(複雑で説明が難しいので、例は省略)|
|**ハイブリッドプロンプト:**|複数のプロンプト手法を組み合わせたプロンプト。||
|  * ハイブリッドプロンプト:|複数のプロンプト手法を組み合わせたプロンプト。|「あなたは親切な図書館員です。この論文(論文本文を挿入)を要約し、箇条書きで重要な点を5つ挙げてください。」|
|  * マルチモーダル統合:|画像や音声など複数のモーダルを統合したプロンプト。(モデルの仕様に依存するので、例は省略)|
|  * クロスドメイン連携:|異なるドメインの知識を組み合わせたプロンプト。|「経済学と歴史学の知識を用いて、1929年の世界恐慌の原因を分析し、その後の経済政策への影響を論じてください。」|
|  * 条件分岐型:|条件によって異なる処理を行うプロンプト。(複雑で説明が難しいので、例は省略)|
|**ステップバイステッププロンプト:**|手順を段階的に指示するプロンプト。|上記「段階的指示プロンプト」と同じ例|
|**コンテキスト制御プロンプト:**|コンテキスト情報を制御するプロンプト。||
|  * コンテキスト注入:|追加のコンテキスト情報を注入するプロンプト。|「次の文脈に基づいて質問に答えてください。(文脈をここに挿入) 質問：・・・」|
|  * コンテキスト制限:|コンテキスト情報を制限するプロンプト。|「以下の情報だけを用いて質問に答えてください。(制限された情報をここに挿入) 質問：・・・」|
|  * コンテキスト拡張:|コンテキスト情報を拡張するプロンプト。|「以下の情報に加えて、一般常識も用いて質問に答えてください。(情報をここに挿入) 質問：・・・」|
|**出力制御プロンプト:**|出力内容を制御するプロンプト。||
|  * フォーマット指定:|出力フォーマットを指定するプロンプト。|「箇条書きで、5つのポイントに絞って答えてください。」|
|  * 長さ制御:|出力の長さを制御するプロンプト。|「100文字以内で答えてください。」|
|  * スタイル制御:|出力のスタイルを制御するプロンプト。|「フォーマルな文章で答えてください。」|
|**反復的プロンプト技術:**|繰り返し処理を行うプロンプト。(複雑で説明が難しいので、例は省略)|
|  * フィードバックループ:|フィードバックに基づいて繰り返し処理を行うプロンプト。(複雑で説明が難しいので、例は省略)|
|  * イテレーティブリファインメント:|反復的にプロンプトを改良する技術。(複雑で説明が難しいので、例は省略)|
|  * マルチターン:|複数回のやり取りを行うプロンプト。|「最初の回答は分かりにくいので、もう少し詳しく説明してください。」|
|**カスケードプロンプト:**|複数のモデルを連携してタスクを実行するプロンプト。(複雑で説明が難しいので、例は省略)|
|**マルチモーダルプロンプト:**|複数の入力形式（テキスト、画像など）を用いるプロンプト。(モデルの仕様に依存するので、例は省略)|
|**インタラクションプロンプト:**|対話を通じてタスクを実行するプロンプト。|**「東京の天気について教えてください。→ 雨です。→ それでは、傘を持っていくべきですか？ → はい、持っていくべきです。」**|
|  * フォローアップ質問:|追加の質問を行うインタラクションプロンプト。|上記と同じ例|
|  * コンテキスト維持:|コンテキストを維持しながら対話を続けるインタラクションプロンプト。|上記と同じ例|
|  * マルチターン会話:|複数ターンにわたる会話を行うインタラクションプロンプト。|上記と同じ例|


**5. プロンプトの評価と改善:**

|**中分類** * 小分類|説明|例|
|-----|-----|-----|
|**プロンプトのリファイン:**|プロンプトを改良するプロセス。|「最初のプロンプトでは曖昧な表現があったため、より具体的な指示を追加しました。」|
|**プロンプトチューニング:**|プロンプトのパラメータを調整するプロセス。(パラメータの具体的な例はモデルに依存)|
|  * パラメータ調整:|プロンプトのパラメータを調整する。(パラメータの具体的な例はモデルに依存)|
|  * コンテキスト最適化:|コンテキスト情報を最適化する。|「プロンプトに関連性の低い情報を削除し、より重要な情報を追加することで、出力の精度が向上しました。」|
|  * トークン効率化:|トークンの使用量を最適化する。|「プロンプトを簡潔にすることで、トークン数を削減し、処理時間を短縮しました。」|
|**プロンプトテスト手法:**|プロンプトを評価する手法。||
|  * A/Bテスト:|異なるプロンプトを比較するテスト。|「プロンプトAとプロンプトBをそれぞれ100回実行し、出力結果の正確性と質を比較しました。」|
|  * パフォーマンス評価:|プロンプトのパフォーマンスを評価する。|「プロンプトを実行時間、正確性、出力の質などの指標を用いて評価しました。」|
|  * 品質チェック:|プロンプトの品質をチェックする。|「出力結果に事実誤認や矛盾がないかを確認しました。」|
|**プロンプトバージョニング:**|プロンプトのバージョン管理。|**「プロンプトの改良履歴をバージョン管理システム(Gitなど)で管理しました。」**|
|  * イテレーション管理:|プロンプトの改良履歴を管理する。|上記と同じ例|
|  * 履歴追跡:|プロンプトの変更履歴を追跡する。|上記と同じ例|
|  * 性能比較:|異なるバージョンのプロンプトの性能を比較する。|「以前のバージョンのプロンプトと比較して、現在のプロンプトの方が出力の精度が向上していることを確認しました。」|


**6. プロンプトの構成要素:**

|中分類 * 小分類|説明|例|
|-----|-----|-----|
|**指示 (Instruction):**|実行すべきタスクを指示する部分。|「猫の写真を生成してください。」|
|**文脈 (Context):**|タスクの背景情報や文脈を提供する部分。|「茶トラ猫で、寝ている姿です。」|
|**入力データ (Input Data):**|タスクを実行するための入力データ。|  (画像データやテキストデータなど、具体的な例はモデルに依存)|
|**出力形式/出力指示子 (Output Indicator):**|期待する出力形式や指示を指定する部分。|「高解像度のJPEG画像で出力してください。」|


**7. その他:**

|中分類 * 小分類|説明|例|
|-----|-----|-----|
|**タスク特化型プロンプト:**|特定のタスクに特化したプロンプト。|「テキストからのキーワード抽出プロンプト」|
|**分類プロンプト:**|データ分類のためのプロンプト。|「この文章はポジティブ、ネガティブ、ニュートラルのどれに分類されますか？(文章本文を挿入)」|
|**生成プロンプト:**|新しいコンテンツを生成するためのプロンプト。|「未来都市をテーマにした物語を書いてください。」|
|**数学問題解決プロンプト:**|数学の問題を解くためのプロンプト。|「2x + 5 = 11 を解いてください。」|
|**セキュリティ・倫理関連プロンプト:**|セキュリティや倫理に関する制約を加えたプロンプト。|「個人情報を含む回答は避けてください。」|
|**プロンプトインジェクション防御:**|プロンプトインジェクション攻撃を防ぐための対策。(具体的な例は技術的に複雑なので省略)|
|**バイアス軽減プロンプト:**|バイアスを軽減するためのプロンプト。|「ジェンダーや人種に関するステレオタイプな表現は避けてください。」|
|**プライバシー保護プロンプト:**|プライバシーを保護するためのプロンプト。|「個人を特定できる情報は含めないでください。」|
|**自己評価プロンプト:**|自身の出力を評価するためのプロンプト。(複雑で説明が難しいので、例は省略)|
|**比較プロンプト:**|複数の選択肢を比較するためのプロンプト。|「A案とB案を比較し、それぞれのメリットとデメリットを箇条書きで説明してください。」|


これらの例は、多くの場合、大規模言語モデルを想定していますが、使用するAIモデルによって、適切なプロンプトやその効果は異なります。  それぞれのプロンプトの種類やテクニックを理解し、試行錯誤を通じて最適なプロンプトを作成することが重要です。


## 構造化プロンプトの例
### XML/HTMLタグ形式:
```xml
<request>
  <language>PowerShell</language>
  <task>FizzBuzz</task>
  <details>
    <description>1から100までの数字を出力するFizzBuzzプログラムを作成してください。3の倍数のときは"Fizz"、5の倍数のときは"Buzz"、3と5の両方の倍数のときは"FizzBuzz"を出力してください。</description>
    <constraints>
      <constraint>ループを使用すること</constraint>
      <constraint>関数を使用しないこと</constraint>
    </constraints>
    <outputFormat>PowerShellスクリプト</outputFormat>
  </details>
</request>
```

### JSONスキーマ形式:
```json
{
  "language": "PowerShell",
  "task": "FizzBuzz",
  "description": "1から100までの数字を出力するFizzBuzzプログラムを作成してください。3の倍数のときは\"Fizz\"、5の倍数のときは\"Buzz\"、3と5の両方の倍数のときは\"FizzBuzz\"を出力してください。",
  "constraints": [
    "ループを使用すること",
    "関数を使用しないこと",
    "エラーハンドリングは不要"
  ],
  "outputFormat": "PowerShellスクリプト"
}
```

### マークダウン形式:
```markdown
## PowerShell FizzBuzz プログラム作成依頼

**タスク:** FizzBuzzプログラムの作成

**説明:** 1から100までの数字を出力するプログラムを作成してください。

* 3の倍数の場合は"Fizz"と出力する
* 5の倍数の場合は"Buzz"と出力する
* 3と5の両方の倍数の場合は"FizzBuzz"と出力する
* それ以外の場合は数字自身を出力する

**制約:**

* ループを使用すること
* 関数は使用しないこと
* エラー処理は不要です

**出力形式:** PowerShellスクリプト

```

### YAML形式:

```yaml
language: PowerShell
task: FizzBuzz
description: |
  1から100までの数字を出力するFizzBuzzプログラムを作成してください。
  3の倍数のときは"Fizz"、5の倍数のときは"Buzz"、3と5の両方の倍数のときは"FizzBuzz"を出力してください。
constraints:
  - ループを使用すること
  - 関数を使用しないこと
outputFormat: PowerShellスクリプト
```



---

## プロンプトの種類を分析した例
### プロンプトの例
````markdown
🌸😊You: 
「プロンプトの種類（参考）分類用」をベースとし、下記のプロンプトがどのプロンプトの種類に該当するか、分類してください。
複数のプロンプトの種類に分類される場合は、複数回答してください。

# プロンプト
`powershellでfizzbuzz。`

レベル１を最低限要求を満たす内容とし、レベル８を、不特定多数の人間が利用しても問題が無く、
読みやすい、説明しやすい、汎用性の高い内容とします。

初めに、各レベル（レベル１、レベル２，レベル３，レベル４、レベル５、レベル６，レベル７，レベル８）
で目指す完成度の目標を日本語で説明してください。

その後、まずはレベル１の内容だけを示してください。
````
### 上記プロンプトの例に含まれるプロンプトの種類の分類
````markdown
🚀🤖Copilot: 
このプロンプトは以下の複数のカテゴリーに分類できます：

1. **プロンプトの基本構造と種類**から：
   - **構造化プロンプト** - レベル1から8までの段階的な構造を要求しています
   - **指示型プロンプト** - 具体的な要求事項を直接的に指示しています

2. **プロンプトの機能と用途**から：
   - **タスク実行プロンプト > コード生成** - PowerShellでのFizzBuzz実装を求めています
   - **システム制御プロンプト > 出力フォーマット指定** - 回答の構造（目標説明→レベル1のコード）を指定しています

3. **プロンプトの高度なテクニック**から：
   - **段階的指示プロンプト** - レベル1から8まで段階的な改善を想定しています
   - **出力制御プロンプト** - 出力の順序と内容を明確に指定しています

4. **プロンプトの構成要素**として：
   - **指示 (Instruction)** - PowerShellでのFizzBuzz実装という具体的なタスク
   - **出力形式/出力指示子** - レベル別の目標説明を先に、その後レベル1の実装という明確な出力順序

5. **その他**から：
   - **タスク特化型プロンプト** - FizzBuzzという特定の課題に焦点を当てています

このプロンプトは、段階的な品質向上を目指す体系的なアプローチを要求しており、特に出力の構造と品質基準を明確に指定している点が特徴的です。
````
### 参考
この分類を行った際のプロンプトテンプレートは以下を参照
https://github.com/SparklingDetergent/doc_genai_Prompt_template_collection_-Japanese-/blob/main/README.md#-特定のドキュメントを一定のルールに応じて分類解析したい

---
<br/><br/> <br/><br/>



# 以下、前の章「プロンプトの種類（参考）表形式」のベースとした情報。特定のプロンプトを生成AIで分類するときに用いる用途としてメモ

# プロンプトの種類（参考）分類用

**1. プロンプトの基本構造と種類:**

* **一言プロンプト:** 簡潔な言葉で指示や質問を行うプロンプト。
* **構造化プロンプト:**  特定のフォーマットに従って情報を提供するプロンプト。
    * **XML/HTMLタグ形式:** XMLまたはHTMLタグを使用して構造化されたプロンプト。
    * **JSONスキーマ形式:** JSONスキーマに従ってデータ構造を定義するプロンプト。
    * **マークダウン形式:** マークダウン記法を使用して構造化されたプロンプト。
    * **YAML形式:** YAML形式を使用して構造化されたプロンプト。
* **キーワードプロンプト:** 関連するキーワードを列挙して指示するプロンプト。
* **質問プロンプト:** 質問形式で情報を求めるプロンプト。
* **文章プロンプト:** 文章でタスクや指示を与えるプロンプト。
* **指示型プロンプト:**  直接的な指示を与えるプロンプト。
* **例示型プロンプト:** 例題を示して、同様のタスクを指示するプロンプト。
* **コンテキストプロンプト:**  背景情報や文脈を提供するプロンプト。
* **カスタマイズプロンプト:** 特定のニーズに合わせて調整されたプロンプト。
* **クリエイティブプロンプト:**  創造性を促すプロンプト。
* **シーケンスプロンプト:** 順序付けられた複数の指示を与えるプロンプト。


**2. プロンプトの機能と用途:**

* **テンプレート型プロンプト:**  事前に定義されたテンプレートを用いるプロンプト。
    * **フォーマット指定型:** 出力形式を指定するテンプレート型プロンプト。XML/HTMLタグ形式, JSONスキーマ形式, マークダウン形式, YAML形式, など様々な形式を指定。
    * **変数置換型:** 変数を埋め込むことで動的にプロンプトを生成するテンプレート型プロンプト。
    * **スロット埋め込み型:**  空欄を埋めさせることでプロンプトを完成させるテンプレート型プロンプト。
* **タスク実行プロンプト:** 特定のタスクを実行させるプロンプト。
    * **文章生成:** 文章を作成させるプロンプト。
    * **コード生成:** プログラムコードを生成させるプロンプト。
    * **データ分析:** データ分析を実行させるプロンプト。
    * **翻訳:** 文章を翻訳させるプロンプト。
    * **要約:** 文章を要約させるプロンプト。
    * **質問応答:** 質問に答えるプロンプト。
* **システム制御プロンプト:** AIの動作を制御するプロンプト。
    * **ペルソナ設定:** AIの性格や役割を設定するプロンプト。
    * **出力フォーマット指定:** 出力形式を指定するプロンプト。
    * **制約条件設定:**  出力内容に制約を与えるプロンプト。
    * **エラーハンドリング指定:** エラー発生時の処理を指定するプロンプト。
* **対話型プロンプト:**  対話形式のプロンプト。
* **生成型プロンプト:** 新しいコンテンツを生成させるプロンプト。
* **翻訳プロンプト:** 言語翻訳を依頼するプロンプト。
* **要約プロンプト:** 文章の要約を依頼するプロンプト。
* **コード生成プロンプト:** プログラムコードの生成を依頼するプロンプト。
* **クリエイティブライティングプロンプト:**  小説や詩などの創作を依頼するプロンプト。
* **質問応答型プロンプト:** 質問に答えることを目的としたプロンプト。
* **シナリオベースプロンプト:** 特定の状況を設定して指示するプロンプト。


**3. 学習方法に基づくプロンプト:**

* **Zero-Shot学習プロンプト:**  事前に学習データを与えずにタスクを実行するプロンプト。
    * **直接指示型:** 直接的にタスクを指示するZero-Shotプロンプト。
    * **説明要求型:**  タスクの説明を求めるZero-Shotプロンプト。
    * **タスク定義型:** タスクを定義するZero-Shotプロンプト。
* **Few-Shot学習プロンプト:** 少数の学習データを与えてタスクを実行するプロンプト。
    * **例示学習型:**  いくつかの例を示してタスクを指示するFew-Shotプロンプト。
    * **パターンマッチング型:** パターンを学習させてタスクを実行するFew-Shotプロンプト。
    * **アナロジー型:** 類推を用いてタスクを実行するFew-Shotプロンプト。
* **Chain-of-Thoughtプロンプト:**  思考過程を明示的に記述してタスクを実行するプロンプト。
    * **思考過程明示型:**  思考過程を段階的に記述するChain-of-Thoughtプロンプト。
    * **ステップバイステップ型:**  ステップごとに指示を行うChain-of-Thoughtプロンプト。
    * **論理展開型:** 論理的な推論に基づいてタスクを実行するChain-of-Thoughtプロンプト。


**4. プロンプトの高度なテクニック:**

* **ロールプレイプロンプト:** 特定の役割を演じさせるプロンプト。
    * **エキスパート設定:** 専門家の役割を演じさせるロールプレイプロンプト。
    * **シナリオベース:** 特定の状況を設定したロールプレイプロンプト。
    * **マルチペルソナ:** 複数の役割を同時に演じさせるロールプレイプロンプト。
* **制約付きプロンプト:**  出力内容に制約を加えるプロンプト。
* **逐次プロンプト:**  順次的に指示を与えるプロンプト。
* **システム指示型プロンプト:**  システムレベルの指示を与えるプロンプト。
* **段階的指示プロンプト:**  段階的に指示を与えるプロンプト。
* **再帰型プロンプト:**  自身が出力した内容を再入力として利用するプロンプト。
* **デバッグプロンプト:**  エラーを発見・修正するためのプロンプト。
* **メタプロンプト:** プロンプトを生成するためのプロンプト。
    * **プロンプト生成プロンプト:**  別のプロンプトを生成させるメタプロンプト。
    * **自己改善型プロンプト:**  自身の性能を改善するためのメタプロンプト。
    * **フィードバック統合型:**  フィードバックを統合してプロンプトを改善するメタプロンプト。
* **ハイブリッドプロンプト:**  複数のプロンプト手法を組み合わせたプロンプト。
    * **マルチモーダル統合:** 画像や音声など複数のモーダルを統合したプロンプト。
    * **クロスドメイン連携:** 異なるドメインの知識を組み合わせたプロンプト。
    * **条件分岐型:** 条件によって異なる処理を行うプロンプト。
* **ステップバイステッププロンプト:**  手順を段階的に指示するプロンプト。
* **コンテキスト制御プロンプト:**  コンテキスト情報を制御するプロンプト。
    * **コンテキスト注入:**  追加のコンテキスト情報を注入するプロンプト。
    * **コンテキスト制限:**  コンテキスト情報を制限するプロンプト。
    * **コンテキスト拡張:**  コンテキスト情報を拡張するプロンプト。
* **出力制御プロンプト:**  出力内容を制御するプロンプト。
    * **フォーマット指定:**  出力フォーマットを指定するプロンプト。
    * **長さ制御:**  出力の長さを制御するプロンプト。
    * **スタイル制御:**  出力のスタイルを制御するプロンプト。
* **反復的プロンプト技術:**  繰り返し処理を行うプロンプト。
    * **フィードバックループ:**  フィードバックに基づいて繰り返し処理を行うプロンプト。
    * **イテレーティブリファインメント:**  反復的にプロンプトを改良する技術。
    * **マルチターン:**  複数回のやり取りを行うプロンプト。
* **カスケードプロンプト:**  複数のモデルを連携してタスクを実行するプロンプト。
* **マルチモーダルプロンプト:**  複数の入力形式（テキスト、画像など）を用いるプロンプト。
* **インタラクションプロンプト:**  対話を通じてタスクを実行するプロンプト。
    * **フォローアップ質問:**  追加の質問を行うインタラクションプロンプト。
    * **コンテキスト維持:**  コンテキストを維持しながら対話を続けるインタラクションプロンプト。
    * **マルチターン会話:**  複数ターンにわたる会話を行うインタラクションプロンプト。


**5. プロンプトの評価と改善:**

* **プロンプトのリファイン:**  プロンプトを改良するプロセス。
* **プロンプトチューニング:**  プロンプトのパラメータを調整するプロセス。
    * **パラメータ調整:**  プロンプトのパラメータを調整する。
    * **コンテキスト最適化:**  コンテキスト情報を最適化する。
    * **トークン効率化:**  トークンの使用量を最適化する。
* **プロンプトテスト手法:**  プロンプトを評価する手法。
    * **A/Bテスト:**  異なるプロンプトを比較するテスト。
    * **パフォーマンス評価:**  プロンプトのパフォーマンスを評価する。
    * **品質チェック:**  プロンプトの品質をチェックする。
* **プロンプトバージョニング:**  プロンプトのバージョン管理。
    * **イテレーション管理:**  プロンプトの改良履歴を管理する。
    * **履歴追跡:**  プロンプトの変更履歴を追跡する。
    * **性能比較:**  異なるバージョンのプロンプトの性能を比較する。


**6. プロンプトの構成要素:**

* **指示 (Instruction):**  実行すべきタスクを指示する部分。
* **文脈 (Context):**  タスクの背景情報や文脈を提供する部分。
* **入力データ (Input Data):**  タスクを実行するための入力データ。
* **出力形式/出力指示子 (Output Indicator):**  期待する出力形式や指示を指定する部分。


**7. その他:**

* **タスク特化型プロンプト:**  特定のタスクに特化したプロンプト。
* **分類プロンプト:**  データ分類のためのプロンプト。
* **生成プロンプト:**  新しいコンテンツを生成するためのプロンプト。
* **数学問題解決プロンプト:**  数学の問題を解くためのプロンプト。
* **セキュリティ・倫理関連プロンプト:**  セキュリティや倫理に関する制約を加えたプロンプト。
* **プロンプトインジェクション防御:**  プロンプトインジェクション攻撃を防ぐための対策。
* **バイアス軽減プロンプト:**  バイアスを軽減するためのプロンプト。
* **プライバシー保護プロンプト:**  プライバシーを保護するためのプロンプト。
* **自己評価プロンプト:**  自身の出力を評価するためのプロンプト。
* **比較プロンプト:**  複数の選択肢を比較するためのプロンプト。

