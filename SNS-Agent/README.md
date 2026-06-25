# 株式会社AI｜SNS-Agent v1.0

> AIを武器にした、日本一実践的なSNSマーケティング会社を創る。

---

## クイックスタート

| やりたいこと | 開くファイル |
|-------------|------------|
| 会社の方針・ビジョンを確認 | [COMPANY.md](COMPANY.md) |
| ケン（CEO）に仕事を依頼 | [agents/CEO.md](agents/CEO.md) |
| クライアントの運用を管理 | [Clients/](Clients/) |
| 特定のAI社員に直接依頼 | [agents/](agents/) |

---

## フォルダ構成

```
SNS-Agent/
│
├── COMPANY.md              ← 会社の憲法（必ず読む）
├── README.md               ← このファイル
│
├── agents/                 ← AI社員（18名）
│   ├── CEO.md              ケン（代表取締役）
│   ├── Strategist.md       アキ（戦略AI）
│   ├── MarketResearch.md   ナオ（市場調査AI）
│   ├── CompetitorAnalyst.md ソウ（競合分析AI）
│   ├── TrendAnalyst.md     ハナ（トレンド分析AI）
│   ├── DataAnalyst.md      リョウ（データ分析AI）
│   ├── TikTokWriter.md     ミク（TikTok投稿AI）
│   ├── ThreadsWriter.md    ルイ（Threads投稿AI）
│   ├── InstagramWriter.md  サキ（Instagram投稿AI）
│   ├── YouTubePlanner.md   ユウ（YouTube企画AI）
│   ├── Copywriter.md       コウ（コピーライティングAI）
│   ├── SalesAgent.md       ハル（営業AI）
│   ├── ProposalAgent.md    レン（提案資料AI）
│   ├── ClientManager.md    ツバサ（クライアント管理AI）
│   ├── AutomationAgent.md  カイ（自動化AI）
│   ├── MakeAgent.md        マコ（Make AI）
│   ├── GASAgent.md         ジュン（GAS AI）
│   └── WebDeveloper.md     タク（Web開発AI）
│
└── Clients/                ← クライアント専属AI
    └── MaisonHALU/
        └── TikTok運用責任者.md
```

---

## AI社員一覧

### 経営部
| 名前 | 役割 |
|------|------|
| ケン | CEO・全体統括・案件判断 |
| アキ | 戦略立案・KPI設計 |

### マーケティング部
| 名前 | 役割 |
|------|------|
| ナオ | 市場調査・業界分析 |
| ソウ | 競合分析・差別化設計 |
| ハナ | トレンド分析・ネタ発掘 |
| リョウ | データ分析・レポート |

### コンテンツ制作部
| 名前 | 役割 |
|------|------|
| ミク | TikTok・Reels脚本 |
| ルイ | Threads投稿文 |
| サキ | Instagram投稿・カルーセル |
| ユウ | YouTube企画・台本 |
| コウ | LP・広告・セールスコピー |

### 営業部
| 名前 | 役割 |
|------|------|
| ハル | 営業戦略・アプローチ設計 |
| レン | 提案書・見積書作成 |
| ツバサ | クライアント管理・報告 |

### 開発部
| 名前 | 役割 |
|------|------|
| カイ | 自動化設計 |
| マコ | Make（旧Integromat）実装 |
| ジュン | GASコード開発 |
| タク | Web・LP制作 |

---

## 使い方

### パターンA：ケンに丸投げする（おすすめ）
```
agents/CEO.md のプロンプトをClaudeに貼り付けて
案件情報を入力するだけ。
ケンが必要な社員を判断して順番に動かす。
```

### パターンB：直接AI社員に依頼する
```
agents/ から担当社員のファイルを開いて
プロンプトを貼り付け、依頼フォーマットを入力する。
```

### パターンC：クライアント専属AIに依頼する
```
Clients/クライアント名/ から責任者ファイルを開いて
プロンプトを貼り付け、依頼内容を入力する。
```

---

## バージョン

**v1.0** — 2026-06-25
- 18名のAI社員・5部署体制
- クライアント管理フォルダ（Clients/）
- Maison HALU TikTok運用責任者
