# 🌟 500以上のAIエージェントプロジェクト / ユースケース集

[![500-AI-Agents-Projects - UseCase](https://img.shields.io/badge/500--AI--Agents--Projects-UseCase-2ea44f?logo=https%3A%2F%2Fstatic-00.iconduck.com%2Fassets.00%2Frobot-emoji-2048x2044-kay057lt.png&logoColor=2ea44f)](https://github.com/ashishpatel26/500-AI-Agents-Projects)

![img](images/AIAgentUseCase.jpg)

様々な業界におけるAIエージェントのユースケースを厳選して収集したコレクションです。実用的なアプリケーションを紹介し、実装に役立つオープンソースプロジェクトへのリンクを提供しています。医療、金融、教育など、AIエージェントがどのように産業を変革しているかをご覧ください！ 🤖✨

---

## 📋 目次

- [はじめに](#-はじめに)
- [業界別ユースケースマインドマップ](#-業界別ユースケースマインドマップ)
- [ユースケース一覧](#-ユースケース一覧)
- [フレームワーク別ユースケース](#フレームワーク別ユースケース)
  - [CrewAI ユースケース](#フレームワーク名-crewai)
  - [AutoGen ユースケース](#フレームワーク名-autogen)
  - [Agno ユースケース](#フレームワーク名-agno)
  - [LangGraph ユースケース](#フレームワーク名-langgraph)
- [コントリビューション](#-コントリビューション)
- [ライセンス](#-ライセンス)

---

## 🧠 はじめに

人工知能（AI）エージェントは、産業の運営方法に革命をもたらしています。パーソナライズされた学習から金融取引ボットまで、AIエージェントは効率性、革新性、スケーラビリティをもたらします。このリポジトリでは以下を提供します：

- AIエージェントが影響を与えている業界のカテゴリ別リスト
- 実装に役立つオープンソースプロジェクトへのリンク付き詳細ユースケース

開発者、研究者、ビジネスに興味をお持ちの方、どなたにとっても、このリポジトリはAIエージェントのインスピレーションと学習のための最適なリソースです。

---

## 🏭 業界別ユースケースマインドマップ

![](images/industry_usecase1.png)

---

## 🧩 ユースケース一覧

| ユースケース                             | 業界           | 説明                                                   | GitHubコード                                                                                                                                                                          |
| ---------------------------------------- | -------------- | ------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **HIA（健康分析エージェント）**          | 医療           | 医療レポートを分析し、健康に関する知見を提供           | [![GitHub](https://img.shields.io/badge/Code-GitHub-black?logo=github)](https://github.com/harshhh28/hia.git)                                                                             |
| **AI健康アシスタント**                   | 医療           | 患者データを使用して疾患の診断とモニタリングを実施     | [![GitHub](https://img.shields.io/badge/Code-GitHub-black?logo=github)](https://github.com/ahmadvh/AI-Agents-for-Medical-Diagnostics.git)                                                 |
| **自動取引ボット**                       | 金融           | リアルタイム市場分析による株式取引の自動化             | [![GitHub](https://img.shields.io/badge/Code-GitHub-black?logo=github)](https://github.com/MingyuJ666/Stockagent.git)                                                                     |
| **仮想AIチューター**                     | 教育           | ユーザーに合わせたパーソナライズ教育を提供             | [![GitHub](https://img.shields.io/badge/Code-GitHub-black?logo=github)](https://github.com/hqanhh/EduGPT.git)                                                                             |
| **24時間365日AIチャットボット**          | カスタマーサービス | 24時間体制で顧客の問い合わせに対応                   | [![GitHub](https://img.shields.io/badge/Code-GitHub-black?logo=github)](https://github.com/NirDiamant/GenAI_Agents/blob/main/all_agents_tutorials/customer_support_agent_langgraph.ipynb) |
| **商品レコメンドエージェント**           | 小売           | ユーザーの好みと履歴に基づいて商品を提案               | [![GitHub](https://img.shields.io/badge/Code-GitHub-black?logo=github)](https://github.com/microsoft/RecAI)                                                                               |
| **自動運転配達エージェント**             | 運輸           | ルートの最適化と自律的な荷物配達                       | [![GitHub](https://img.shields.io/badge/Code-GitHub-black?logo=github)](https://github.com/sled-group/driVLMe)                                                                            |
| **工場プロセス監視エージェント**         | 製造           | 生産ラインの監視と品質管理                             | [![GitHub](https://img.shields.io/badge/Code-GitHub-black?logo=github)](https://github.com/yuchenxia/llm4ias)                                                                             |
| **不動産価格算定エージェント**           | 不動産         | 市場トレンドを分析して不動産価格を算定                 | [![GitHub](https://img.shields.io/badge/Code-GitHub-black?logo=github)](https://github.com/AleksNeStu/ai-real-estate-assistant)                                                           |
| **スマート農業アシスタント**             | 農業           | 作物の健康状態と収穫量予測に関する知見を提供           | [![GitHub](https://img.shields.io/badge/Code-GitHub-black?logo=github)](https://github.com/mohammed97ashraf/LLM_Agri_Bot)                                                                 |
| **エネルギー需要予測エージェント**       | エネルギー     | 電力網管理の最適化のためにエネルギー使用量を予測       | [![GitHub](https://img.shields.io/badge/Code-GitHub-black?logo=github)](https://github.com/yecchen/MIRAI)                                                                                 |
| **コンテンツパーソナライズエージェント** | エンターテインメント | 好みに基づいてパーソナライズされたメディアを推奨   | [![GitHub](https://img.shields.io/badge/Code-GitHub-black?logo=github)](https://github.com/crosleythomas/MirrorGPT)                                                                       |
| **法律文書レビューアシスタント**         | 法律           | 文書レビューの自動化と重要条項のハイライト             | [![GitHub](https://img.shields.io/badge/Code-GitHub-black?logo=github)](https://github.com/firica/legalai)                                                                                |
| **採用レコメンドエージェント**           | 人事           | 求人に最適な候補者を提案                               | [![GitHub](https://img.shields.io/badge/Code-GitHub-black?logo=github)](https://github.com/sentient-engineering/jobber)                                                                   |
| **仮想旅行アシスタント**                 | ホスピタリティ | 好みに基づいて旅行プランを作成                         | [![GitHub](https://img.shields.io/badge/Code-GitHub-black?logo=github)](https://github.com/nirbar1985/ai-travel-agent)                                                                    |
| **AIゲームコンパニオンエージェント**     | ゲーム         | リアルタイムアシスタンスでプレイヤー体験を向上         | [![GitHub](https://img.shields.io/badge/Code-GitHub-black?logo=github)](https://github.com/onjas-buidl/LLM-agent-game)                                                                    |
| **リアルタイム脅威検知エージェント**     | サイバーセキュリティ | 潜在的な脅威を特定し攻撃を緩和                     | [![GitHub](https://img.shields.io/badge/Code-GitHub-black?logo=github)](https://github.com/NVISOsecurity/cyber-security-llm-agents)                                                       |
| **ECパーソナルショッパーエージェント**   | Eコマース      | 顧客が気に入る商品を見つける手助け                     | [![GitHub](https://img.shields.io/badge/Code-GitHub-black?logo=github)](https://github.com/Hoanganhvu123/ShoppingGPT)                                                                     |
| **物流最適化エージェント**               | サプライチェーン | 効率的な配送ルートの計画と在庫管理                   | [![GitHub](https://img.shields.io/badge/Code-GitHub-black?logo=github)](https://github.com/microsoft/OptiGuide)                                                                           |
| **Vibeハッキングエージェント**           | サイバーセキュリティ | 自律型マルチエージェントベースのレッドチームテストサービス | [![GitHub](https://img.shields.io/badge/Code-GitHub-black?logo=github)](https://github.com/PurpleAILAB/Decepticon) |
| **MediSuite-Ai-Agent**                   | 医療保険       | 病院/保険請求ワークフローの自動化を支援する医療AIエージェント | [![GitHub](https://img.shields.io/badge/Code-GitHub-black?logo=github)](https://github.com/MahmoudRabea13/MediSuite-Ai-Agent)                                         |
| **Lina-Egyptian-Medical-Chatbot**        | 医療保険       | 病院/保険請求ワークフローの自動化を支援する医療AIエージェント | [![GitHub](https://img.shields.io/badge/Code-GitHub-black?logo=github)](https://github.com/MahmoudRabea13/MediSuite-Ai-Agent)                                         |

## フレームワーク別ユースケース

---

### **フレームワーク名**: **CrewAI**

| ユースケース                      | 業界              | 説明                                                                           | GitHub                                                                                                                                              |
| --------------------------------- | ----------------- | ------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------- |
| 📧 メール自動返信フロー           | 🗣️ コミュニケーション | 事前定義された基準に基づいてメール返信を自動化し、コミュニケーション効率を向上 | [![GitHub](https://img.shields.io/badge/GitHub-Repository-blue)](https://github.com/crewAIInc/crewAI-examples/tree/main/flows/email_auto_responder_flow) |
| 📝 会議アシスタントフロー         | 🛠️ 生産性         | スケジューリングやアジェンダ作成を含む会議の整理と管理を支援                   | [![GitHub](https://img.shields.io/badge/GitHub-Repository-blue)](https://github.com/crewAIInc/crewAI-examples/tree/main/flows/meeting_assistant_flow) |
| 🔄 自己評価ループフロー           | 👥 人事           | 組織内の自己評価プロセスを促進し、パフォーマンスレビューを支援                 | [![GitHub](https://img.shields.io/badge/GitHub-Repository-blue)](https://github.com/crewAIInc/crewAI-examples/tree/main/flows/self_evaluation_loop_flow) |
| 📈 リードスコアフロー             | 💼 営業           | 見込み客を評価・スコアリングし、営業戦略におけるアウトリーチを優先順位付け     | [![GitHub](https://img.shields.io/badge/GitHub-Repository-blue)](https://github.com/crewAIInc/crewAI-examples/tree/main/flows/lead-score-flow) |
| 📊 マーケティング戦略ジェネレーター | 📢 マーケティング | 市場トレンドとオーディエンスデータを分析してマーケティング戦略を策定           | [![GitHub](https://img.shields.io/badge/GitHub-Repository-blue)](https://github.com/crewAIInc/crewAI-examples/tree/main/crews/marketing_strategy) |
| 📝 求人投稿ジェネレーター         | 🧑‍💼 採用           | 求人要件を分析して求人投稿を作成し、採用プロセスを支援                         | [![GitHub](https://img.shields.io/badge/GitHub-Repository-blue)](https://github.com/crewAIInc/crewAI-examples/tree/main/crews/job-posting) |
| 🔄 採用ワークフロー               | 🧑‍💼 採用           | 採用に関わる様々なタスクを自動化して採用プロセスを効率化                       | [![GitHub](https://img.shields.io/badge/GitHub-Repository-blue)](https://github.com/crewAIInc/crewAI-examples/tree/main/crews/recruitment) |
| 🔍 プロフィールとポジションのマッチング | 🧑‍💼 採用      | 候補者のプロフィールを適切な職位にマッチングし、採用効率を向上                 | [![GitHub](https://img.shields.io/badge/GitHub-Repository-blue)](https://github.com/crewAIInc/crewAI-examples/tree/main/crews/match_profile_to_positions) |
| 📸 Instagram投稿ジェネレーター    | 📱 ソーシャルメディア | Instagram投稿を自動生成・スケジュールし、ソーシャルメディア管理を効率化      | [![GitHub](https://img.shields.io/badge/GitHub-Repository-blue)](https://github.com/crewAIInc/crewAI-examples/tree/main/crews/instagram_post)             |
| 🌐 ランディングページジェネレーター | 💻 Web開発       | Webサイトのランディングページ作成を自動化し、Web開発タスクを促進               | [![GitHub](https://img.shields.io/badge/GitHub-Repository-blue)](https://github.com/crewAIInc/crewAI-examples/tree/main/crews/landing_page_generator)     |
| 🎮 ゲームビルダークルー           | 🎮 ゲーム開発     | ゲーム作成の特定の側面を自動化してゲーム開発を支援                             | [![GitHub](https://img.shields.io/badge/GitHub-Repository-blue)](https://github.com/crewAIInc/crewAI-examples/tree/main/crews/game-builder-crew)          |
| 💹 株式分析ツール                 | 💰 金融           | 株式市場データを分析するツールを提供し、金融意思決定を支援                     | [![GitHub](https://img.shields.io/badge/GitHub-Repository-blue)](https://github.com/crewAIInc/crewAI-examples/tree/main/crews/stock_analysis)             |
| 🗺️ 旅行プランナー                | ✈️ 旅行           | 旅程を整理し旅行の詳細を管理して旅行計画を支援                                 | [![GitHub](https://img.shields.io/badge/GitHub-Repository-blue)](https://github.com/crewAIInc/crewAI-examples/tree/main/crews/trip_planner)               |
| 🎁 サプライズ旅行プランナー       | ✈️ 旅行           | ユーザーの好みに基づいて目的地とアクティビティを選択しサプライズ旅行を計画     | [![GitHub](https://img.shields.io/badge/GitHub-Repository-blue)](https://github.com/crewAIInc/crewAI-examples/tree/main/crews/surprise_trip)              |
| 📚 フローで本を書く               | ✍️ クリエイティブライティング | 構造化されたワークフローと執筆支援を提供して著者の執筆を支援             | [![GitHub](https://img.shields.io/badge/GitHub-Repository-blue)](https://github.com/crewAIInc/crewAI-examples/tree/main/flows/write_a_book_with_flows) |
| 🎬 脚本ライター                   | ✍️ クリエイティブライティング | テンプレートと脚本開発のガイダンスを提供して脚本執筆を支援               | [![GitHub](https://img.shields.io/badge/GitHub-Repository-blue)](https://github.com/crewAIInc/crewAI-examples/tree/main/crews/screenplay_writer)          |
| ✅ Markdownバリデーター           | 📄 ドキュメンテーション | Markdownファイルの適切なフォーマットと標準への準拠を検証                   | [![GitHub](https://img.shields.io/badge/GitHub-Repository-blue)](https://github.com/crewAIInc/crewAI-examples/tree/main/crews/markdown_validator)         |
| 🧠 Meta Questナレッジ             | 📚 ナレッジマネジメント | Meta Questに関する知識を管理・整理し、情報検索を促進                       | [![GitHub](https://img.shields.io/badge/GitHub-Repository-blue)](https://github.com/crewAIInc/crewAI-examples/tree/main/crews/meta_quest_knowledge)       |
| 🤖 NVIDIAモデル統合               | 🤖 AI統合         | ワークフローにNVIDIA AIモデルを統合して計算能力を強化                          | [![GitHub](https://img.shields.io/badge/GitHub-Repository-blue)](https://github.com/crewAIInc/crewAI-examples/tree/main/integrations/nvidia_models) |
| 🗂️ 会議準備                      | 🛠️ 生産性         | 資料を整理しアジェンダを設定して会議準備を支援                                 | [![GitHub](https://img.shields.io/badge/GitHub-Repository-blue)](https://github.com/crewAIInc/crewAI-examples/tree/main/crews/prep-for-a-meeting)         |
| 🛠️スターターテンプレート         | 🛠️ 開発           | 新規プロジェクトのセットアッププロセスを効率化するスターターテンプレートを提供 | [![GitHub](https://img.shields.io/badge/GitHub-Repository-blue)](https://github.com/crewAIInc/crewAI-examples/tree/main/crews/starter_template)           |
| 🔗CrewAI + LangGraph統合          | 🤖 AI統合         | ワークフロー自動化を強化するCrewAIとLangGraphの統合を実演                      | [![GitHub](https://img.shields.io/badge/GitHub-Repository-blue)](https://github.com/crewAIInc/crewAI-examples/tree/main/integrations/CrewAI-LangGraph)           |


### **フレームワーク名**: **Autogen**

> **コード生成、実行、デバッグ**

| ユースケース                                                          | 業界              | 説明                                                       | ノートブック                                                                                                                                                                   |
| --------------------------------------------------------------------- | ----------------- | ---------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 🤖 コード生成・実行・デバッグによる自動タスク解決                      | 💻 ソフトウェア開発 | コードの生成、実行、デバッグによる自動タスク解決を実演     | [![Notebook](https://img.shields.io/badge/View-Notebook-blue?logo=jupyter)](https://microsoft.github.io/autogen/0.2/docs/notebooks/agentchat_auto_feedback_from_code_execution) |
| 🧑‍💻 検索拡張エージェントによる自動コード生成と質問応答               | 💻 ソフトウェア開発 | 検索拡張手法を使用してコード生成と質問応答を実行           | [![Notebook](https://img.shields.io/badge/View-Notebook-blue?logo=jupyter)](https://microsoft.github.io/autogen/0.2/docs/notebooks/agentchat_RetrieveChat)                      |
| 🧠 Qdrantベースの検索による自動コード生成と質問応答                    | 💻 ソフトウェア開発 | 検索拡張エージェントのパフォーマンス向上にQdrantを活用     | [![Notebook](https://img.shields.io/badge/View-Notebook-blue?logo=jupyter)](https://microsoft.github.io/autogen/0.2/docs/notebooks/agentchat_RetrieveChat_qdrant)               |

> **マルチエージェントコラボレーション（3エージェント以上）**

| ユースケース                                                   | 業界                | 説明                                                   | ノートブック                                                                                                                                                            |
| :------------------------------------------------------------- | :------------------ | :----------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| 🤝 グループチャットによる自動タスク解決（3メンバー、1マネージャー） | 🤝 コラボレーション | マルチエージェントコラボレーションによるグループタスク解決を実演 | [![Notebook](https://img.shields.io/badge/View-Notebook-blue?logo=jupyter)](https://microsoft.github.io/autogen/0.2/docs/notebooks/agentchat_groupchat)                  |
| 📊 グループチャットによる自動データ可視化（3メンバー、1マネージャー） | 📊 データ分析       | マルチエージェントコラボレーションを使用してデータ可視化を作成 | [![Notebook](https://img.shields.io/badge/View-Notebook-blue?logo=jupyter)](https://microsoft.github.io/autogen/0.2/docs/notebooks/agentchat_groupchat_vis)              |
| 🧩 グループチャットによる複雑なタスクの自動解決（6メンバー、1マネージャー） | 🤝 コラボレーション | より大きなエージェントグループで複雑なタスクを協調的に解決 | [![Notebook](https://img.shields.io/badge/View-Notebook-blue?logo=jupyter)](https://microsoft.github.io/autogen/0.2/docs/notebooks/agentchat_groupchat_research)         |
| 🧑‍💻 コーディング＆プランニングエージェントによる自動タスク解決 | 🛠️ 計画＆開発      | コーディングエージェントとプランニングエージェントを組み合わせてタスクを効果的に解決 | [![Notebook](https://img.shields.io/badge/View-Notebook-blue?logo=jupyter)](https://github.com/microsoft/autogen/blob/0.2/notebook/agentchat_planning.ipynb)             |
| 📐 グラフで指定された遷移パスによる自動タスク解決               | 🤝 コラボレーション | グラフ内の事前定義された遷移パスを使用してタスクを解決 | [![Notebook](https://img.shields.io/badge/View-Notebook-blue?logo=jupyter)](https://microsoft.github.io/autogen/docs/notebooks/agentchat_groupchat_finite_state_machine) |
| 🧠 SocietyOfMindAgentによる内的独白としてのグループチャット実行 | 🧠 認知科学         | グループチャットを使用した問題解決のための内的独白をシミュレート | [![Notebook](https://img.shields.io/badge/View-Notebook-blue?logo=jupyter)](https://microsoft.github.io/autogen/0.2/docs/notebooks/agentchat_society_of_mind)            |
| 🔧 カスタムスピーカー選択機能によるグループチャット実行         | 🤝 コラボレーション | グループチャットでのスピーカー選択にカスタム関数を実装 | [![Notebook](https://img.shields.io/badge/View-Notebook-blue?logo=jupyter)](https://microsoft.github.io/autogen/0.2/docs/notebooks/agentchat_groupchat_customized)       |

> **シーケンシャルマルチエージェントチャット**

| ユースケース                                                              | 業界                  | 説明                                                             | ノートブック                                                                                                                                                        |
| :------------------------------------------------------------------------ | :-------------------- | :--------------------------------------------------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 🔄 単一エージェントによる連続チャットでの複数タスク解決                    | 🔄 ワークフロー自動化 | 単一の開始エージェントによる連続タスク解決を自動化               | [![Notebook](https://img.shields.io/badge/View-Notebook-blue?logo=jupyter)](https://microsoft.github.io/autogen/0.2/docs/notebooks/agentchat_multi_task_chats)       |
| ⏳ 単一エージェントによる連続チャットでの非同期複数タスク解決              | 🔄 ワークフロー自動化 | 1つのエージェントが開始する連続チャットでの非同期タスク解決を処理 | [![Notebook](https://img.shields.io/badge/View-Notebook-blue?logo=jupyter)](https://microsoft.github.io/autogen/0.2/docs/notebooks/agentchat_multi_task_async_chats) |
| 🤝 異なるエージェントによる連続チャットでの複数タスク解決                  | 🔄 ワークフロー自動化 | 異なるエージェントが各チャットを開始する連続タスク解決を促進     | [![Notebook](https://img.shields.io/badge/View-Notebook-blue?logo=jupyter)](https://microsoft.github.io/autogen/0.2/docs/notebooks/agentchats_sequential_chats)      |

> **ネストチャット**

| ユースケース                                                    | 業界                      | 説明                                                                                       | ノートブック                                                                                                                                                         |
| :-------------------------------------------------------------- | :------------------------ | :----------------------------------------------------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 🧠 ネストチャットによる複雑なタスク解決                          | 🧠 問題解決               | ネストチャットを使用して階層的で複雑な問題を解決                                           | [![Notebook](https://img.shields.io/badge/View-Notebook-blue?logo=jupyter)](https://microsoft.github.io/autogen/0.2/docs/notebooks/agentchat_nestedchat)              |
| 🔄 ネストチャットのシーケンスによる複雑なタスク解決              | 🧠 問題解決               | ネストチャットを使用した連続タスク解決を実演                                               | [![Notebook](https://img.shields.io/badge/View-Notebook-blue?logo=jupyter)](https://microsoft.github.io/autogen/0.2/docs/notebooks/agentchat_nested_sequential_chats) |
| 🏭 ネストチャットによるサプライチェーン最適化問題解決のOptiGuide | 🏭 サプライチェーン最適化 | ネストチャット、コーディングエージェント、セーフガードエージェントを使用したサプライチェーン最適化問題の解決方法を紹介 | [![Notebook](https://img.shields.io/badge/View-Notebook-blue?logo=jupyter)](https://microsoft.github.io/autogen/0.2/docs/notebooks/agentchat_nestedchat_optiguide)    |
| ♟️ ネストチャットとツール使用による会話型チェス                 | 🎮 ゲーム                 | 統合ツールを使用した会話型チェスのためのネストチャット使用を探求                           | [![Notebook](https://img.shields.io/badge/View-Notebook-blue?logo=jupyter)](https://microsoft.github.io/autogen/0.2/docs/notebooks/agentchat_nested_chats_chess)      |

> **アプリケーション**

| ユースケース                                                                      | 業界                      | 説明                                                                     | ノートブック                                                                                                                                                      |
| :-------------------------------------------------------------------------------- | :------------------------ | :----------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| 🔄 新しいデータからの自動継続学習                                                  | 📊 機械学習               | 適応型AIのために新しいデータ入力から継続的に学習                         | [![Notebook](https://img.shields.io/badge/View-Notebook-blue?logo=jupyter)](https://github.com/microsoft/autogen/blob/0.2/notebook/agentchat_stream.ipynb)         |
| 🏭 OptiGuide - サプライチェーン最適化のためのコーディング、ツール使用、セーフガード、質問応答 | 🏭 サプライチェーン最適化 | サプライチェーン最適化のためにコーディング、ツール使用、セーフガードを組み合わせたソリューションを紹介 | [![Notebook](https://img.shields.io/badge/View-Notebook-blue?logo=jupyter)](https://microsoft.github.io/autogen/0.2/docs/notebooks/agentchat_nestedchat_optiguide) |
| 🤖 AutoAnny - AutoGenで構築されたDiscordボット                                     | 💬 コミュニケーションツール | 強化されたインタラクションのためのAutoGenを使用したDiscordボット開発を紹介 | [![Notebook](https://img.shields.io/badge/View-Notebook-blue?logo=jupyter)](https://github.com/microsoft/autogen/tree/main/samples/apps/auto-anny)                 |

> **ツール**

| ユースケース                                                | 業界                    | 説明                                                               | ノートブック                                                                                                                                                                         |
| :---------------------------------------------------------- | :---------------------- | :----------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 🌐 Web検索：Web情報を必要とするタスクの解決                  | 🔍 情報検索             | タスク完了に必要な情報を収集するためにWebを検索                    | [![Notebook](https://img.shields.io/badge/View-Notebook-blue?logo=jupyter)](https://github.com/microsoft/autogen/blob/0.2/notebook/agentchat_web_info.ipynb)                          |
| 🔧 提供されたツールを関数として使用                          | 🛠️ ツール統合          | AutoGenで事前提供されたツールを呼び出し可能な関数として使用する方法を実演 | [![Notebook](https://img.shields.io/badge/View-Notebook-blue?logo=jupyter)](https://microsoft.github.io/autogen/0.2/docs/notebooks/agentchat_function_call_currency_calculator)       |
| 🔗 同期・非同期関数呼び出しによるツール使用                  | 🛠️ ツール統合          | AutoGenワークフロー内での同期・非同期ツール使用を説明              | [![Notebook](https://img.shields.io/badge/View-Notebook-blue?logo=jupyter)](https://microsoft.github.io/autogen/0.2/docs/notebooks/agentchat_function_call_async)                     |
| 🧩 Langchain提供ツールを関数として使用したタスク解決         | 🔍 言語処理             | AutoGen内でタスク解決のためにLangchainツールを活用                 | [![Notebook](https://img.shields.io/badge/View-Notebook-blue?logo=jupyter)](https://github.com/microsoft/autogen/blob/0.2/notebook/agentchat_langchain.ipynb)                         |
| 📚 RAG：検索拡張生成によるグループチャット                   | 🤝 コラボレーション     | 情報共有をサポートする検索拡張生成（RAG）によるグループチャットを実現 | [![Notebook](https://img.shields.io/badge/View-Notebook-blue?logo=jupyter)](https://microsoft.github.io/autogen/0.2/docs/notebooks/agentchat_groupchat_RAG)                           |
| ⚙️ 関数インセプション：会話中の関数更新/削除               | 🔧 開発ツール           | AutoGenエージェントが会話中に動的に関数を変更することを可能に      | [![Notebook](https://img.shields.io/badge/View-Notebook-blue?logo=jupyter)](https://github.com/microsoft/autogen/blob/0.2/notebook/agentchat_inception_function.ipynb)                |
| 🔊 Whisperとのエージェントチャット                           | 🎙️ 音声処理            | Whisperを使用した文字起こしと翻訳のためのAIエージェント機能を実演  | [![Notebook](https://img.shields.io/badge/View-Notebook-blue?logo=jupyter)](https://microsoft.github.io/autogen/0.2/docs/notebooks/agentchat_video_transcript_translate_with_whisper) |
| 📏 ガイダンスによる制約付き応答                              | 💡 自然言語処理         | エージェントが生成する応答を制約するためにガイダンスを使用する方法を紹介 | [![Notebook](https://img.shields.io/badge/View-Notebook-blue?logo=jupyter)](https://github.com/microsoft/autogen/blob/0.2/notebook/agentchat_guidance.ipynb)                          |
| 🌍 エージェントによるWebブラウジング                         | 🌐 情報検索             | Webを閲覧して情報を取得するようにエージェントを設定する方法を説明  | [![Notebook](https://img.shields.io/badge/View-Notebook-blue?logo=jupyter)](https://github.com/microsoft/autogen/blob/0.2/notebook/agentchat_surfer.ipynb)                            |
| 📊 SQL：Spiderベンチマークを使用した自然言語からSQLクエリへの変換 | 💾 データベース管理     | Spiderベンチマークを使用して自然言語入力をSQLクエリに変換          | [![Notebook](https://img.shields.io/badge/View-Notebook-blue?logo=jupyter)](https://github.com/microsoft/autogen/blob/0.2/notebook/agentchat_sql_spider.ipynb)                        |
| 🕸️ ApifyによるWebスクレイピング                            | 🌐 データ収集           | AutoGenでApifyを使用したWebスクレイピング技術を説明                | [![Notebook](https://img.shields.io/badge/View-Notebook-blue?logo=jupyter)](https://microsoft.github.io/autogen/0.2/docs/notebooks/agentchat_webscraping_with_apify)                  |
| 🕷️ Webクローリング：Spider APIによるドメイン全体のクロール | 🌐 データ収集           | Spider APIを使用してドメイン全体をクロールする方法を説明           | [![Notebook](https://img.shields.io/badge/View-Notebook-blue?logo=jupyter)](https://microsoft.github.io/autogen/0.2/docs/notebooks/agentchat_webcrawling_with_spider)                 |
| 💻 特別設計された関数によるタスク単位でのソフトウェアアプリ作成 | 💻 ソフトウェア開発     | 設計された関数を使用してソフトウェアアプリケーションを段階的に構築 | [![Notebook](https://img.shields.io/badge/View-Notebook-blue?logo=jupyter)](https://github.com/microsoft/autogen/blob/0.2/notebook/agentchat_function_call_code_writing.ipynb)        |

> **人間開発**

| ユースケース                                              | 業界                | 説明                                                                     | ノートブック                                                                                                                                                      |
| :-------------------------------------------------------- | :------------------ | :----------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| 💬 ChatGPTスタイルのシンプルな例                           | 🧠 会話型AI         | ChatGPTスタイルのシンプルな会話例を実演                                  | [![Example](https://img.shields.io/badge/View-Example-blue?logo=openai)](https://github.com/microsoft/autogen/blob/0.2/samples/simple_chat.py)                     |
| 🤖 自動コード生成、実行、デバッグと人間のフィードバック    | 💻 ソフトウェア開発 | ワークフローに人間のフィードバックを統合したコード生成、実行、デバッグを紹介 | [![Notebook](https://img.shields.io/badge/View-Notebook-blue?logo=jupyter)](https://github.com/microsoft/autogen/blob/0.2/notebook/agentchat_human_feedback.ipynb) |
| 👥 GPT-4 + 複数人間ユーザーによる自動タスク解決            | 🤝 コラボレーション | 複数の人間ユーザーがGPT-4と協力してタスクを解決することを可能に          | [![Notebook](https://img.shields.io/badge/View-Notebook-blue?logo=jupyter)](https://github.com/microsoft/autogen/blob/0.2/notebook/agentchat_two_users.ipynb)      |
| 🔄 非同期人間入力によるエージェントチャット                | 🧠 会話型AI         | エージェント会話中の非同期人間入力をサポート                             | [![Notebook](https://img.shields.io/badge/View-Notebook-blue?logo=jupyter)](https://github.com/microsoft/autogen/blob/0.2/notebook/Async_human_input.ipynb)        |

> **エージェントの教育と学習**

| ユースケース                                                  | 業界                  | 説明                                                                    | ノートブック                                                                                                                                                                |
| :------------------------------------------------------------ | :-------------------- | :---------------------------------------------------------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 📘 自動チャットによる新しいスキルの習得と再利用                | 🎓 教育＆トレーニング | エージェントへの新しいスキルの教育と自動チャットでの再利用を実演        | [![Notebook](https://img.shields.io/badge/View-Notebook-blue?logo=jupyter)](https://microsoft.github.io/autogen/0.2/docs/notebooks/agentchat_teaching)                       |
| 🧠 コーディング以外の新しい事実、ユーザー設定、スキルの習得    | 🎓 教育＆トレーニング | エージェントに新しい事実、ユーザー設定、非コーディングスキルを教える方法を紹介 | [![Notebook](https://img.shields.io/badge/View-Notebook-blue?logo=jupyter)](https://microsoft.github.io/autogen/0.2/docs/notebooks/agentchat_teachability)                   |
| 🤖 GPTAssistantAgentによるOpenAIアシスタントへの教育           | 💻 AIアシスタント開発 | GPTAssistantAgentを使用したOpenAIアシスタントの機能強化方法を説明       | [![Notebook](https://img.shields.io/badge/View-Notebook-blue?logo=jupyter)](https://github.com/microsoft/autogen/blob/0.2/notebook/agentchat_teachable_oai_assistants.ipynb) |
| 🔄 エージェントオプティマイザー：エージェント的方法でエージェントをトレーニング | 🛠️ 最適化            | エージェントオプティマイザーを使用してエージェント的方法で効果的にエージェントをトレーニングする方法を説明 | [![Notebook](https://img.shields.io/badge/View-Notebook-blue?logo=jupyter)](https://github.com/microsoft/autogen/blob/0.2/notebook/agentchat_agentoptimizer.ipynb)           |

> **OpenAIアシスタントを含むマルチエージェントチャット**

| ユースケース                                          | 業界               | 説明                                                           | ノートブック                                                                                                                                                                     |
| :---------------------------------------------------- | :----------------- | :------------------------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 🌟 AutoGenでのOpenAIアシスタントとのHello-Worldチャット | 🤖 会話型AI        | AutoGenを使用したOpenAIアシスタントとのチャットの基本例        | [![Notebook](https://img.shields.io/badge/View-Notebook-blue?logo=jupyter)](https://github.com/microsoft/autogen/blob/0.2/notebook/agentchat_oai_assistant_twoagents_basic.ipynb) |
| 🔧 関数呼び出しを使用したOpenAIアシスタントとのチャット | 🔧 開発ツール      | チャットでOpenAIアシスタントと関数呼び出しを使用する方法を説明 | [![Notebook](https://img.shields.io/badge/View-Notebook-blue?logo=jupyter)](https://github.com/microsoft/autogen/blob/0.2/notebook/agentchat_oai_assistant_function_call.ipynb)   |
| 🧠 コードインタープリター付きOpenAIアシスタントとのチャット | 💻 ソフトウェア開発 | チャットでOpenAIアシスタントをコードインタープリターとして使用する方法を実演 | [![Notebook](https://img.shields.io/badge/View-Notebook-blue?logo=jupyter)](https://github.com/microsoft/autogen/blob/0.2/notebook/agentchat_oai_code_interpreter.ipynb)          |
| 🔍 検索拡張付きOpenAIアシスタントとのチャット           | 📚 情報検索        | OpenAIアシスタントとの検索拡張会話を実現                       | [![Notebook](https://img.shields.io/badge/View-Notebook-blue?logo=jupyter)](https://github.com/microsoft/autogen/blob/0.2/notebook/agentchat_oai_assistant_retrieval.ipynb)       |
| 🤝 グループチャットでのOpenAIアシスタント               | 🤝 コラボレーション | OpenAIアシスタントが他のエージェントとグループチャットで協力する方法を紹介 | [![Notebook](https://img.shields.io/badge/View-Notebook-blue?logo=jupyter)](https://github.com/microsoft/autogen/blob/0.2/notebook/agentchat_oai_assistant_groupchat.ipynb)       |
| 🛠️ GPTAssistantAgentベースのマルチエージェントツール使用 | 🔧 開発ツール      | マルチエージェントツール使用のためのGPTAssistantAgentの使用方法を説明 | [![Notebook](https://img.shields.io/badge/View-Notebook-blue?logo=jupyter)](https://github.com/microsoft/autogen/blob/0.2/notebook/gpt_assistant_agent_function_call.ipynb)       |

> **非OpenAIモデル**

| ユースケース                                  | 業界       | 説明                                           | ノートブック                                                                                                                                                              |
| :-------------------------------------------- | :--------- | :--------------------------------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ♟️ 非OpenAIモデルを使用した会話型チェス       | 🎮 ゲーム  | 非OpenAIモデルで実装された会話型チェスを探求   | [![Notebook](https://img.shields.io/badge/View-Notebook-blue?logo=jupyter)](https://microsoft.github.io/autogen/0.2/docs/notebooks/agentchat_nested_chats_chess_altmodels) |

> **マルチモーダルエージェント**

| ユースケース                                   | 業界             | 説明                                                           | ノートブック                                                                                                                                                       |
| :--------------------------------------------- | :--------------- | :------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 🎨 DALLEとGPT-4Vによるマルチモーダルエージェントチャット | 🖼️ マルチメディアAI | マルチモーダルエージェント通信のためにDALLEとGPT-4Vを組み合わせ | [![Notebook](https://img.shields.io/badge/View-Notebook-blue?logo=jupyter)](https://github.com/microsoft/autogen/blob/0.2/notebook/agentchat_dalle_and_gpt4v.ipynb) |
| 🖌️ Llavaによるマルチモーダルエージェントチャット | 📷 画像処理      | 画像処理によるマルチモーダルエージェント会話にLlavaを使用      | [![Notebook](https://img.shields.io/badge/View-Notebook-blue?logo=jupyter)](https://github.com/microsoft/autogen/blob/0.2/notebook/agentchat_lmm_llava.ipynb)       |
| 🖼️ GPT-4Vによるマルチモーダルエージェントチャット | 🖼️ マルチメディアAI | マルチモーダルエージェントでの視覚的・会話的インタラクションにGPT-4Vを活用 | [![Notebook](https://img.shields.io/badge/View-Notebook-blue?logo=jupyter)](https://github.com/microsoft/autogen/blob/0.2/notebook/agentchat_lmm_gpt-4v.ipynb)      |

> **長いコンテキストの処理**

| ユースケース                        | 業界          | 説明                                                            | ノートブック                                                                                                                                                    |
| :---------------------------------- | :------------ | :-------------------------------------------------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 📜 能力としての長いコンテキストの処理 | 🧠 AI能力     | AIワークフロー内で長いコンテキストを効果的に処理する技術を実演  | [![Notebook](https://img.shields.io/badge/View-Notebook-blue?logo=jupyter)](https://microsoft.github.io/autogen/0.2/docs/notebooks/agentchat_transform_messages) |

> **評価と査定**

| ユースケース                                                             | 業界                 | 説明                                                                    | ノートブック                                                                                                                                               |
| :----------------------------------------------------------------------- | :------------------- | :---------------------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------- |
| 📊 AgentEval：LLMベースアプリケーションの有用性を評価するマルチエージェントシステム | 📈 パフォーマンス評価 | LLMベースアプリケーションのパフォーマンス評価・査定のためのAgentEvalを紹介 | [![Notebook](https://img.shields.io/badge/View-Notebook-blue?logo=jupyter)](https://github.com/microsoft/autogen/blob/0.2/notebook/agenteval_cq_math.ipynb) |

> **自動エージェント構築**

| ユースケース                                               | 業界           | 説明                                                              | ノートブック                                                                                                                                                     |
| :--------------------------------------------------------- | :------------- | :---------------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 🏗️ AgentBuilderによるマルチエージェントシステムの自動構築 | 🤖 AI開発      | AgentBuilderツールを使用してマルチエージェントシステムを自動構築する方法を説明 | [![Notebook](https://img.shields.io/badge/View-Notebook-blue?logo=jupyter)](https://github.com/microsoft/autogen/blob/0.2/notebook/autobuild_basic.ipynb)         |
| 📚 エージェントライブラリからのマルチエージェントシステムの自動構築 | 🤖 AI開発      | 事前定義されたエージェントライブラリを活用してマルチエージェントシステムを構築する方法を紹介 | [![Notebook](https://img.shields.io/badge/View-Notebook-blue?logo=jupyter)](https://github.com/microsoft/autogen/blob/0.2/notebook/autobuild_agent_library.ipynb) |

> **可観測性**

| ユースケース                                                   | 業界                   | 説明                                                           | ノートブック                                                                                                                                                |
| :------------------------------------------------------------- | :--------------------- | :------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------ |
| 📊 AgentOpsによるLLM呼び出し、ツール使用、アクション、エラーの追跡 | 📈 モニタリング＆分析 | AgentOpsを使用してLLMインタラクション、ツール使用、エラーを監視する方法を実演 | [![Notebook](https://img.shields.io/badge/View-Notebook-blue?logo=jupyter)](https://github.com/microsoft/autogen/blob/0.2/notebook/agentchat_agentops.ipynb) |

> **強化された推論**

| ユースケース                                                       | 業界           | 説明                                                               | ノートブック                                                                                                                                                                     |
| :----------------------------------------------------------------- | :------------- | :----------------------------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 🔗 API統一                                                         | 🔧 API管理     | ドキュメントとコード例を使用してAPI使用を統一する方法を説明        | [![Documentation](https://img.shields.io/badge/View-Documentation-blue?logo=readthedocs)](https://microsoft.github.io/autogen/docs/Use-Cases/enhanced_inference/#api-unification) |
| ⚙️ API設定を効果的に管理するためのユーティリティ関数             | 🔧 API管理     | API設定をより効果的に管理するためのユーティリティ関数を実演        | [![Notebook](https://img.shields.io/badge/View-Notebook-blue?logo=jupyter)](https://microsoft.github.io/autogen/0.2/docs/topics/llm_configuration)                                |
| 💰 コスト計算                                                      | 📈 コスト管理  | LLMインタラクションのトークン使用量追跡とコスト見積もり方法を紹介  | [![Notebook](https://img.shields.io/badge/View-Notebook-blue?logo=jupyter)](https://github.com/microsoft/autogen/blob/0.2/notebook/agentchat_cost_token_tracking.ipynb)           |
| ⚡ コード生成の最適化                                              | 📊 最適化      | LLMによるコード生成を改善するためのコスト効率の良い最適化技術を紹介 | [![Notebook](https://img.shields.io/badge/View-Notebook-blue?logo=jupyter)](https://github.com/microsoft/autogen/blob/0.2/notebook/oai_completion.ipynb)                          |
| 📐 数学の最適化                                                    | 📊 最適化      | 数学的問題解決のためのLLMパフォーマンス最適化技術を説明            | [![Notebook](https://img.shields.io/badge/View-Notebook-blue?logo=jupyter)](https://github.com/microsoft/autogen/blob/0.2/notebook/oai_chatgpt_gpt4.ipynb)                        |

### **フレームワーク名**: **Agno**

> **ユースケース**

| ユースケース                        | 業界                                   | 説明                                                                                                                                                               | ノートブック                                                                                                                                                                                                       |
| :---------------------------------- | :------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 🤖 サポートエージェント              | 💻 ソフトウェア開発 / AI / フレームワークサポート | Agnoサポートエージェントは、リアルタイムの回答、説明、コード例を提供してAgnoフレームワークの開発者を支援                                                          | [![AI Agent Code - Python](https://img.shields.io/static/v1?label=AI+Agent+Code&message=Python&color=%23244cd1)](https://github.com/agno-agi/agno/blob/main/cookbook/examples/agents/agno_support_agent.py)         |
| 🎥 YouTubeエージェント               | 📺 メディア＆コンテンツ                 | AIツールを使用してYouTube動画を分析し、詳細な要約、タイムスタンプ、テーマ、コンテンツの内訳を生成するインテリジェントエージェント                                  | [![AI Agent Code - Python](https://img.shields.io/static/v1?label=AI+Agent+Code&message=Python&color=%23244cd1)](https://github.com/agno-agi/agno/blob/main/cookbook/examples/agents/youtube_agent.py)              |
| 📊 ファイナンスエージェント          | 💼 金融                                | リアルタイムの株式市場の洞察、アナリストの推奨、財務分析、セクター固有のトレンドを提供する高度なAI搭載市場アナリスト。AAPL、TSLA、NVDAなどの企業の詳細分析プロンプトをサポート | [![AI Agent Code - Python](https://img.shields.io/static/v1?label=AI+Agent+Code&message=Python&color=%23244cd1)](https://github.com/agno-agi/agno/blob/main/cookbook/examples/agents/thinking_finance_agent.py)     |
| 📚 学習パートナー                    | 🎓 教育                                | リソースの検索、質問への回答、学習計画の作成によってユーザーの学習を支援                                                                                           | [![AI Agent Code - Python](https://img.shields.io/static/v1?label=AI+Agent+Code&message=Python&color=%23244cd1)](https://github.com/agno-agi/agno/blob/main/cookbook/examples/agents/study_partner.py)              |
| 🛍️ ショッピングパートナーエージェント | 🏬 Eコマース                           | Amazon、Flipkartなどの信頼できるプラットフォームからユーザーの好みに基づいてマッチする商品を見つけるのを支援する商品レコメンドエージェント                         | [![AI Agent Code - Python](https://img.shields.io/static/v1?label=AI+Agent+Code&message=Python&color=%23244cd1)](https://github.com/agno-agi/agno/blob/main/cookbook/examples/agents/shopping_partner.py)           |
| 🎓 リサーチスカラーエージェント      | 🧠 教育 / 研究                         | 高度な学術検索、最新の出版物分析、分野横断的な発見の統合、適切な引用を含む構造化された学術レポートの作成を行うAI搭載の学術アシスタント                             | [![AI Agent Code - Python](https://img.shields.io/static/v1?label=AI+Agent+Code&message=Python&color=%23244cd1)](https://github.com/agno-agi/agno/blob/main/cookbook/examples/agents/research_agent_exa.py)         |
| 🧠 リサーチエージェント              | 🗞️ メディア＆ジャーナリズム           | Web検索とプロのジャーナリスティックライティングを組み合わせたリサーチエージェント。深い調査を行い、NYTスタイルのレポートを作成                                     | [![AI Agent Code - Python](https://img.shields.io/static/v1?label=AI+Agent+Code&message=Python&color=%23244cd1)](https://github.com/agno-agi/agno/blob/main/cookbook/examples/agents/research_agent.py)             |
| 🍳 レシピクリエーター                | 🍽️ 食品＆料理                         | 材料、好み、時間の制約に基づいてパーソナライズされたレシピを提供するAI搭載のレシピ推奨エージェント                                                                 | [![AI Agent Code - Python](https://img.shields.io/static/v1?label=AI+Agent+Code&message=Python&color=%23244cd1)](https://github.com/agno-agi/agno/blob/main/cookbook/examples/agents/recipe_creator.py)             |
| 🗞️ ファイナンスエージェント        | 💼 金融                                | リアルタイム株式データ、アナリストの洞察、企業の基礎、市場ニュースを組み合わせた強力な金融アナリストエージェント。Apple、Tesla、NVIDIAなどの企業や半導体・自動車などのセクター分析に最適 | [![AI Agent Code - Python](https://img.shields.io/static/v1?label=AI+Agent+Code&message=Python&color=%23244cd1)](https://github.com/agno-agi/agno/blob/main/cookbook/examples/agents/finance_agent.py)              |
| 🧠 金融推論エージェント              | 📈 金融                                | Claude-3.5 SonnetベースのエージェントでNVDAなどの株式を推論ツールとYahoo Financeデータを使用して分析                                                               | [![AI Agent Code - Python](https://img.shields.io/static/v1?label=AI+Agent+Code&message=Python&color=%23244cd1)](https://github.com/agno-agi/agno/blob/main/cookbook/examples/agents/reasoning_finance_agent.py)    |
| 🤖 READMEジェネレーターエージェント  | 💻 ソフトウェア開発                    | リポジトリのメタデータを使用してGitHubリポジトリ用の高品質なREADMEを生成するエージェント                                                                           | [![AI Agent Code - Python](https://img.shields.io/static/v1?label=AI+Agent+Code&message=Python&color=%23244cd1)](https://github.com/agno-agi/agno/blob/main/cookbook/examples/agents/readme_generator.py)           |
| 🎬 映画レコメンドエージェント        | 🎥 エンターテインメント                | ExaとGPT-4oを使用して、ジャンル、テーマ、最新の評価を分析し、パーソナライズされた映画推奨を提供するインテリジェントエージェント                                    | [![AI Agent Code - Python](https://img.shields.io/static/v1?label=AI+Agent+Code&message=Python&color=%23244cd1)](https://github.com/agno-agi/agno/blob/main/cookbook/examples/agents/movie_recommedation.py)        |
| 🔍 メディアトレンド分析エージェント  | 📰 メディア＆ニュース                  | AI搭載エージェントとスクレイピングを使用してデジタルプラットフォームからの新興トレンド、パターン、インフルエンサーを分析                                          | [![AI Agent Code - Python](https://img.shields.io/static/v1?label=AI+Agent+Code&message=Python&color=%23244cd1)](https://github.com/agno-agi/agno/blob/main/cookbook/examples/agents/media_trend_analysis_agent.py) |
| ⚖️ 法律文書分析エージェント        | 🏛️ リーガルテック                     | PDF URLから法律文書を分析し、ベクトル埋め込みとGPT-4oを使用したナレッジベースに基づいて法的洞察を提供するAIエージェント                                            | [![AI Agent Code - Python](https://img.shields.io/static/v1?label=AI+Agent+Code&message=Python&color=%23244cd1)](https://github.com/agno-agi/agno/blob/main/cookbook/examples/agents/legal_consultant.py)           |
| 🤔 DeepKnowledge                    | 🧠 研究                                | ナレッジベースを通じて反復検索を実行し、複雑なクエリをサブ質問に分解して包括的な回答を統合するエージェント。デモンストレーションにAgnoドキュメントを使用し、深い推論と探索のために設計 | [![AI Agent Code - Python](https://img.shields.io/static/v1?label=AI+Agent+Code&message=Python&color=%23244cd1)](https://github.com/agno-agi/agno/blob/main/cookbook/examples/agents/deep_knowledge.py)             |
| 📚 書籍レコメンドエージェント        | 🧠 出版＆メディア                      | 文学データ、読者の好み、レビュー、発売情報を使用してパーソナライズされた書籍提案を提供するインテリジェントエージェント                                            | [![AI Agent Code - Python](https://img.shields.io/static/v1?label=AI+Agent+Code&message=Python&color=%23244cd1)](https://github.com/agno-agi/agno/blob/main/cookbook/examples/agents/book_recommendation.py)        |
| 🏠 MCP Airbnbエージェント            | 🛎️ ホスピタリティ                     | MCPとLlama 4を使用して、ワークスペースと交通機関への近さなどのフィルターでAirbnbリスティングを検索するAIエージェントを作成                                         | [![AI Agent Code - Python](https://img.shields.io/static/v1?label=AI+Agent+Code&message=Python&color=%23244cd1)](https://github.com/agno-agi/agno/blob/main/cookbook/examples/agents/airbnb_mcp.py)                 |
| 🤖 アシストエージェント              | 🧠 AIフレームワーク                    | ハイブリッド検索と埋め込み知識を使用してAgnoフレームワークに関する質問に答えるGPT-4oを使用したAIエージェント                                                      | [![AI Agent Code - Python](https://img.shields.io/static/v1?label=AI+Agent+Code&message=Python&color=%23244cd1)](https://github.com/agno-agi/agno/blob/main/cookbook/examples/agents/agno_assist.py)                |

### **フレームワーク名**: **LangGraph**

> **ユースケース**

| ユースケース                           | 業界                       | 説明                                                  | ノートブック                                                     |
| :------------------------------------- | :------------------------- | :---------------------------------------------------- | :----------------------------------------------------------- |
| 🤖 チャットボットシミュレーション評価   | 💻 💬 AI / 品質保証         | ユーザーインタラクションをシミュレートしてチャットボットのパフォーマンスを評価し、実際のシナリオでの堅牢性と信頼性を確保 | [![AI Agent Code - Python](https://img.shields.io/static/v1?label=AI+Agent+Code&message=Python&color=%23244cd1)](https://github.com/langchain-ai/langgraph/blob/main/docs/docs/tutorials/chatbot-simulation-evaluation/agent-simulation-evaluation.ipynb) |
| 🧠 プロンプティングによる情報収集       | 🧠 AI / 研究開発           | このチュートリアルでは、プロンプティング技術を活用して効果的に情報を収集するLangGraphワークフローの設計方法を実演。プロンプトの構造化と情報フローの管理によるインテリジェントエージェント構築方法を紹介 | [![AI Agent Code - Python](https://img.shields.io/static/v1?label=AI+Agent+Code&message=Python&color=%23244cd1)](https://github.com/langchain-ai/langgraph/blob/main/docs/docs/tutorials/chatbots/information-gather-prompting.ipynb) |
| 🧠 LangGraphによるコードアシスタント    | 💻 ソフトウェア開発        | このチュートリアルでは、LangGraphを使用して堅牢なコードアシスタントを構築する方法を実演。コード生成、エラーチェック、反復的な改良を処理できるグラフベースのエージェント作成をガイドし、堅牢で正確なコーディング支援を保証 | [![AI Agent Code - Python](https://img.shields.io/static/v1?label=AI+Agent+Code&message=Python&color=%23244cd1)](https://github.com/langchain-ai/langgraph/blob/main/docs/docs/tutorials/code_assistant/langgraph_code_assistant.ipynb) |
| 🧑‍💼 カスタマーサポートエージェント     | 🧑‍💼 カスタマーサポート     | このチュートリアルでは、LangGraphを使用してカスタマーサポートエージェントを構築する方法を実演。顧客の問い合わせを処理し、自動サポートを提供し、ユーザーエクスペリエンスを向上させるグラフベースのエージェント作成をガイド | [![AI Agent Code - Python](https://img.shields.io/static/v1?label=AI+Agent+Code&message=Python&color=%23244cd1)](https://github.com/langchain-ai/langgraph/blob/main/docs/docs/tutorials/customer-support/customer-support.ipynb) |
| 🔁 リトライ付き抽出                     | 🧠 AI / データ抽出         | このチュートリアルでは、LangGraphワークフローにリトライメカニズムを実装する方法を実演し、一時的なエラーを処理して信頼性を向上させる堅牢なデータ抽出プロセスを保証 | [![AI Agent Code - Python](https://img.shields.io/static/v1?label=AI+Agent+Code&message=Python&color=%23244cd1)](https://github.com/langchain-ai/langgraph/blob/main/docs/docs/tutorials/extraction/retries.ipynb) |
| 🧠 マルチエージェントワークフロー       | 🧠 AI / ワークフローオーケストレーション | このチュートリアルでは、LangGraphのエージェントスーパーバイザーを使用してマルチエージェントシステムを構築する方法を実演。複数の専門エージェントをオーケストレーションし、タスク委任とコミュニケーションフローを管理するスーパーバイザーエージェントの作成をガイド | [![AI Agent Code - Python](https://img.shields.io/static/v1?label=AI+Agent+Code&message=Python&color=%23244cd1)](https://github.com/langchain-ai/langgraph/blob/main/docs/docs/tutorials/multi_agent/agent_supervisor.ipynb) |
| 🧠 階層型エージェントチーム             | 🧠 AI / ワークフローオーケストレーション | このチュートリアルでは、LangGraphを使用して階層型エージェントシステムを構築する方法を実演。専門のサブエージェントにタスクを委任するトップレベルのスーパーバイザーエージェント作成をガイドし、明確なタスク委任とコミュニケーションによる複雑なワークフローを可能に | [![AI Agent Code - Python](https://img.shields.io/static/v1?label=AI+Agent+Code&message=Python&color=%23244cd1)](https://github.com/langchain-ai/langgraph/blob/main/docs/docs/tutorials/multi_agent/hierarchical_agent_teams.ipynb) |
| 🤝 マルチエージェントコラボレーション   | 🧠 AI / ワークフローオーケストレーション | このチュートリアルでは、LangGraphを使用したマルチエージェントコラボレーションの実装方法を実演。複雑なタスクを達成するために協力する複数の専門エージェント作成をガイドし、AIワークフローにおけるエージェントコラボレーションの力を紹介 | [![AI Agent Code - Python](https://img.shields.io/static/v1?label=AI+Agent+Code&message=Python&color=%23244cd1)](https://github.com/langchain-ai/langgraph/blob/main/docs/docs/tutorials/multi_agent/multi-agent-collaboration.ipynb) |
| 🧠 計画・実行エージェント               | 🧠 AI / ワークフローオーケストレーション | このチュートリアルでは、LangGraphを使用した「計画・実行」スタイルのエージェント構築方法を実演。まず複数ステップの計画を生成し、各ステップを順次実行し、必要に応じて計画を再検討・修正するエージェント作成をガイド。このアプローチはPlan-and-Solve論文とBaby-AGIプロジェクトに触発され、AIワークフローにおける長期計画とタスク実行の強化を目指す | [![AI Agent Code - Python](https://img.shields.io/static/v1?label=AI+Agent+Code&message=Python&color=%23244cd1)](https://github.com/langchain-ai/langgraph/blob/main/docs/docs/tutorials/plan-and-execute/plan-and-execute.ipynb) |
| 🧠 SQLエージェント | 🧠 AI / データベースインタラクション | このチュートリアルでは、SQLデータベースに関する質問に答えられるエージェントの構築方法を実演。エージェントは利用可能なテーブルを取得し、質問との関連性を判断し、スキーマを取得し、クエリを生成し、エラーをチェックし、実行して回答を作成 | [![AI Agent Code - Python](https://img.shields.io/static/v1?label=AI+Agent+Code&message=Python&color=%23244cd1)](https://github.com/langchain-ai/langgraph/blob/main/docs/docs/tutorials/sql-agent.ipynb) |
| 🧠 リフレクションエージェント | 🧠 AI / ワークフローオーケストレーション | このチュートリアルでは、LangGraphを使用したリフレクションエージェントの構築方法を実演。自身の出力を批評・修正し、生成コンテンツの品質と信頼性を向上させるエージェント作成をガイド | [![AI Agent Code - Python](https://img.shields.io/static/v1?label=AI+Agent+Code&message=Python&color=%23244cd1)](https://github.com/langchain-ai/langgraph/blob/main/docs/docs/tutorials/reflection/reflection.ipynb)|
| 🧠 リフレクシオンエージェント | 🧠 AI / ワークフローオーケストレーション | このチュートリアルでは、LangGraphを使用したリフレクシオンエージェントの構築方法を実演。行動と結果を振り返り、反復的な改善と複雑なワークフローでのより正確な意思決定を可能にするエージェント作成をガイド | [![AI Agent Code - Python](https://img.shields.io/static/v1?label=AI+Agent+Code&message=Python&color=%23244cd1)](https://github.com/langchain-ai/langgraph/blob/main/docs/docs/tutorials/reflexion/reflexion.ipynb)|
| **LangGraph エージェンティックRAG**     |                            |                                                       |                                                              |
| 🧠 **アダプティブRAG**                  | 🧠 AI / 情報検索           | このチュートリアルでは、LangGraphを使用したアダプティブRAGシステムの構築方法を実演。クエリの複雑さに応じて調整する動的検索プロセス作成をガイドし、情報検索の効率と精度を向上 | [![AI Agent Code - Python](https://img.shields.io/static/v1?label=AI+Agent+Code&message=Python&color=%23244cd1)](https://github.com/langchain-ai/langgraph/blob/main/docs/docs/tutorials/rag/langgraph_adaptive_rag.ipynb) |
| 🧠 **アダプティブRAG（ローカル）**      | 🧠 AI / 情報検索           | このチュートリアルでは、ローカルモデルを使用したアダプティブRAGの実装に焦点を当て、インターネットアクセスが制限された環境やプライバシーが懸念される場合に重要なオフライン検索と生成を可能に | [![AI Agent Code - Python](https://img.shields.io/static/v1?label=AI+Agent+Code&message=Python&color=%23244cd1)](https://github.com/langchain-ai/langgraph/blob/main/docs/docs/tutorials/rag/langgraph_adaptive_rag_local.ipynb) |
| 🤖 **エージェンティックRAG**            | 🤖 AI / インテリジェントエージェント | エージェントが応答生成前に最適な検索戦略を決定するエージェンティックRAGシステムの構築方法を学び、回答の関連性と精度を向上 | [![AI Agent Code - Python](https://img.shields.io/static/v1?label=AI+Agent+Code&message=Python&color=%23244cd1)](https://github.com/langchain-ai/langgraph/blob/main/docs/docs/tutorials/rag/langgraph_agentic_rag.ipynb) |
| 🤖 **エージェンティックRAG（ローカル）** | 🤖 AI / インテリジェントエージェント | このチュートリアルでは、エージェンティックRAGをローカル環境に拡張し、検索・生成タスクにローカルモデルとデータソースを使用可能に | [![AI Agent Code - Python](https://img.shields.io/static/v1?label=AI+Agent+Code&message=Python&color=%23244cd1)](https://github.com/langchain-ai/langgraph/blob/main/docs/docs/tutorials/rag/langgraph_agentic_rag_local.ipynb) |
| 🧠 **コレクティブRAG（CRAG）**          | 🧠 AI / 情報検索           | ジェネレーターに渡す前に取得したドキュメントを評価・改良し、より高品質な出力を保証するコレクティブRAGシステムを実装 | [![AI Agent Code - Python](https://img.shields.io/static/v1?label=AI+Agent+Code&message=Python&color=%23244cd1)](https://github.com/langchain-ai/langgraph/blob/main/docs/docs/tutorials/rag/langgraph_crag.ipynb) |
| 🧠 **コレクティブRAG（ローカル）**      | 🧠 AI / 情報検索           | このチュートリアルでは、ローカルリソースを使用したコレクティブRAGシステムの構築に焦点を当て、オフラインでのドキュメント評価・改良プロセスを可能に | [![AI Agent Code - Python](https://img.shields.io/static/v1?label=AI+Agent+Code&message=Python&color=%23244cd1)](https://github.com/langchain-ai/langgraph/blob/main/docs/docs/tutorials/rag/langgraph_crag_local.ipynb)       |
| 🧠 **セルフRAG**                        | 🧠 AI / 情報検索           | システムが応答を振り返り、必要に応じて追加情報を検索し、生成コンテンツの精度と関連性を向上させるセルフRAGの実装方法を学習 | [![AI Agent Code - Python](https://img.shields.io/static/v1?label=AI+Agent+Code&message=Python&color=%23244cd1)](https://github.com/langchain-ai/langgraph/blob/main/docs/docs/tutorials/rag/langgraph_self_rag.ipynb)                       |
| 🧠 **セルフRAG（ローカル）**            | 🧠 AI / 情報検索           | このチュートリアルでは、ローカルモデルとデータソースを使用したセルフRAGの実装方法を実演し、オフラインでの振り返りと検索プロセスを可能に | [![AI Agent Code - Python](https://img.shields.io/static/v1?label=AI+Agent+Code&message=Python&color=%23244cd1)](https://github.com/langchain-ai/langgraph/blob/main/docs/docs/tutorials/rag/langgraph_self_rag_local.ipynb)         |





---

## 🤝 コントリビューション

コントリビューションを歓迎します！ 🎉 貢献方法：

1. リポジトリをフォークする
2. 新しいユースケースを追加するか、既存のものを改善する
3. 変更内容をプルリクエストとして提出する

詳細は[コントリビューションガイドライン](CONTRIBUTING.md)をご覧ください。

---

## 📜 ライセンス

このリポジトリはMITライセンスの下で公開されています。詳細は[LICENSE](LICENSE)ファイルをご覧ください。

---

## 🚀 一緒に作りましょう！

このリポジトリをネットワークで共有し、役に立つと思ったらスター ⭐ をお願いします。AIエージェントのユースケースのための究極のリソースを一緒に作りましょう！
