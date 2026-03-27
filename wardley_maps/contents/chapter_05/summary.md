# 第5章 The Play and a Decision to Act（プレイと行動の決断）

> [Medium](https://medium.com/wardleymaps/the-play-and-a-decision-to-act-8eb796b1dff1) | PDF p.138-177

## 概要

マップ上で「Where（どこで戦うか）」を特定した後、具体的な「How（どう戦うか）」を決定するプロセスを描く章。コンテキスト固有のゲームプレイ（accelerators/decelerators/constraints、ILCモデル）を学び、それらを組み合わせて実際のプラン（Zimki）を策定。最終的にプランを実行に移すが、親会社との政治的対立により失敗。ゲームプレイの分類体系と、戦略実行における「全ユーザーを考慮する」ことの重要性を痛感する。

## セクション別サマリー

### 1. コンテキスト固有のゲームプレイを学ぶ

#### Accelerators, Decelerators and Constraints

- **Accelerators**: オープンソース、オープンデータ等のオープンアプローチにより、コンポーネントの進化を加速できる（Figure 54参照 -- Mediumで閲覧可能）
- **Decelerators**: FUD（Fear, Uncertainty, Doubt）や特許によるリングフェンシングで進化を減速させられる
- **Constraints**: 依存コンポーネントの制約が進化を阻害する（例: ユーティリティコンピュートにはデータセンター建設が必要）
- ランドスケープは操作可能である

#### Innovate, Leverage, Commoditise（ILCモデル）

- 既存のプロダクトをユーティリティ化してAPI公開 → エコシステム（外部のPioneer）がその上でイノベーション → メタデータで成功パターンを検知 → 次のコンポーネントサービスとして産業化
- ILCの循環: Commoditise → 外部イノベーション → Leverage（メタデータ分析）→ 新コンポーネント → さらにCommoditise
- エコシステムが大きくなるほどネットワーク効果が強化される（Figure 55-56参照 -- Mediumで閲覧可能）
- 「first mover to industrialise, fast follower to the uncharted」という独自のポジションを構築

### 2. プレイの策定（The Plan）

著者はZimkiプラットフォーム（コード実行プラットフォーム）として具体的なプランを策定（Figure 57参照 -- Mediumで閲覧可能）:

- **Point 1**: JavaScriptベースのユーティリティコード実行プラットフォームを提供。コンポーネントサービス（課金、メッセージング、オブジェクトストア等）をAPI公開
- **Point 2**: オープンソースで公開し、プラットフォーム開発を加速
- **Point 3**: 単一サービスではなく、競争的なプロバイダーのマーケットプレイスを目指す。GPLライセンスで機能差異を最小化
- **Point 4**: ILCモデルでエコシステムを構築し、将来のサービスを特定
- **Point 5**: 「Pre-shaved Yaks」-- アプリ開発の無駄な作業を徹底排除
- **Point 6**: ユーティリティインフラ（将来のAWS等）の上に構築
- **Point 7-8**: データセンターの制約を利用したカウンタープレイ。Borgシステムのオープンソース化

### 3. 目的への影響（Impacts on Purpose）

- 行動の決断は会社の目的そのものを変える -- 「Creative Solutions Group」から「Provider of Utility Platforms」へ
- 目的を単に述べるだけでは不十分。モラルインペラティブ（道義的使命）が必要
- 「Pre-shaved Yaks」がチームの旗印になった

### 4. 何が起きたか -- 成功と失敗

- 2006年3月にベータ版リリース、Google AppEngineの2年前
- 急成長を遂げたが、親会社が「クラウドは未来ではない」と判断
- オープンソース化の延期、収益サービスの契約解除を命じられる
- 著者は辞任。プラットフォームは年内に閉鎖

### 5. 何を間違えたか

- 親会社の取締役会（重要なユーザー群）のニーズを無視していた
- マップを取締役会に十分に説明していなかった
- 政治的資本の獲得を怠った
- 技術的に正しい方向であっても、全ステークホルダーの支持がなければ実行できない

### 6. ゲームプレイの分類（Categorising Gameplay）

ゲームプレイを以下のカテゴリに分類（Figure 59参照 -- Mediumで閲覧可能）:

- User Perception、Accelerators、De-accelerators、Dealing with toxicity、Market、Defensive、Attacking、Ecosystem、Competitor、Positional、Poison

## チェックリスト

- [ ] マップ上のコンポーネントに対するAccelerator/Decelerator/Constraintを特定しているか
- [ ] ILCモデルの適用可能性を検討しているか
- [ ] プランには技術面だけでなく、全ステークホルダー（特に意思決定者）のニーズが含まれているか
- [ ] ゲームプレイの分類表を参照し、使える戦術を網羅的に検討しているか
- [ ] カウンタープレイ（競合や制約への対抗手段）を準備しているか

## ポイント

この章の最大の教訓は二重である。第一に、ILCモデルに代表されるコンテキスト固有のゲームプレイを学ぶことで、マップから実行可能な戦略を導き出せること。第二に、どれほど優れた戦略であっても、全てのユーザー（取締役会を含む）のニーズを考慮しなければ実行に失敗するということ。著者がZimkiで犯した失敗は、技術的な失敗ではなく、政治的・組織的な失敗であった。
