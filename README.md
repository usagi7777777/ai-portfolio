# AI 開発ポートフォリオ

Claude エージェントを用いて開発した AI アプリケーションの成果物を集めたポートフォリオサイトです。

🌐 **公開URL**: https://usagi7777777.github.io/ai-portfolio/

## 特徴

- **単一HTMLファイル**（`index.html`）で完結。ビルドツール・パッケージマネージャ・外部依存なし（Vanilla JS）
- デザインシステム「**Warm Elegant Minimal**」— 明朝体・くすみピンクのアクセント・余白主体の上品なミニマル
- 均等3カラムの Project Gallery（タブレット2列 / モバイル1列のレスポンシブ）
- カテゴリフィルタ、クリックで詳細モーダル表示
- 成果物は `index.html` 内の `works` 配列で管理（追加は配列に1要素足すだけ）

## 掲載作品

| 作品 | プロジェクト |
|------|------------|
| Codebase Analyzer | Automated Documentation Agent |
| UX Optimizer | NanoBanana Pro UX Agent |
| Data Agent Integrator | Multi-Process Agent Workflows |
| Chatbot Interaction Panel | Kawaii Vector Style Chatbot |

## 構成

```
.
├── index.html          # サイト本体（HTML/CSS/JS すべて埋込）
├── images/             # 各成果物のスクリーンショット
│   ├── codebase-analyzer.png
│   ├── ux-optimizer.png
│   ├── data-agent-integrator.png
│   └── chatbot-panel.png
└── .nojekyll           # GitHub Pages に Jekyll 処理をさせずそのまま配信
```

## ローカルで開く

`index.html` をブラウザで開くだけで動作します。

---

Built with [Claude Code](https://claude.com/claude-code)
